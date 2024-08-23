# TRS-80 Model 1 System ROMs - Bundles for 2x256 ROMs - 32kb

This repository offers 32kb bundles of ROM binaries for recreating TRS-80 Model 1 ROMs, allowing version selection and easy switching as needed.

## Identifiers

Each bundle is grouped by format, identified by a code:

- Default bundles have ROMs recorded sequentially.
- Bundles marked "r" have all ROMs reversed.
- Bundles marked "f" have all ROM addresses flipped, reversing the binary address from right-to-left to left-to-right.
- Bundles marked "rf" have both ROMs reversed and addresses flipped.

**NOTE:** When using the ROM adapters provided by RetroStack, use the "rf" version. This is necessary because the addressing uses pull-up resistors on 0 (negative logic) and DIP switches that reverse the addresses from right-to-left, while the PCB is left-to-right.

## ROM Bundle

| Bit Pattern | Name              | Comment                                                                             |
| ----------- | ----------------- | ----------------------------------------------------------------------------------- |
| `00`        | Level I           | First version                                                                       |
| `01`        | Level II v1.3     | Final system version                                                                |
| `10`        | Level II v1.3 (p) | Patch doesn't require the duplicate characters for lowercase mod, provided by MattB |
| `11`        | Diagnostic ROM    | [Adrians' Diagnostic ROM](https://github.com/misterblack1/trs80-diagnosticrom)      |

## Default Bundle

- [ROM A](/rom_a_4.bin)
- [ROM B](/rom_b_4.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `00`        | Level I                |
| `01`        | Level II v1.3          |
| `10`        | Level II v1.3 (+patch) |
| `11`        | Diagnostic ROM         |

## Reversed "r"

- [ROM A](/rom_a_4_r.bin)
- [ROM B](/rom_b_4_r.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `00`        | Diagnostic ROM         |
| `01`        | Level II v1.3 (+patch) |
| `10`        | Level II v1.3          |
| `11`        | Level I                |

## Flipped "f"

- [ROM A](/rom_a_4_f.bin)
- [ROM B](/rom_b_4_f.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `00`        | Level I                |
| `01`        | Level II v1.3 (+patch) |
| `10`        | Level II v1.3          |
| `11`        | Diagnostic ROM         |

## Reversed & Flipped "rf"

- [ROM A](/rom_a_4_rf.bin)
- [ROM B](/rom_b_4_rf.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `00`        | Diagnostic ROM         |
| `01`        | Level II v1.3          |
| `10`        | Level II v1.3 (+patch) |
| `11`        | Level I                |
