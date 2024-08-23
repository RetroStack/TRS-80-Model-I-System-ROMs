# TRS-80 Model 1 System ROMs - Bundles for 2x512 ROMs - 64kb

This repository offers 64kb bundles of ROM binaries for recreating TRS-80 Model 1 ROMs, allowing version selection and easy switching as needed.

## Identifiers

Each bundle is grouped by format, identified by a code:

- Default bundles have ROMs recorded sequentially.
- Bundles marked "r" have all ROMs reversed.
- Bundles marked "f" have all ROM addresses flipped, reversing the binary address from right-to-left to left-to-right.
- Bundles marked "rf" have both ROMs reversed and addresses flipped.

**NOTE:** When using the ROM adapters provided by RetroStack, use the "rf" version. This is necessary because the addressing uses pull-up resistors on 0 (negative logic) and DIP switches that reverse the addresses from right-to-left, while the PCB is left-to-right.

## ROM Bundle

| Bit Pattern | Name                   | Comment                                                                             |
| ----------- | ---------------------- | ----------------------------------------------------------------------------------- |
| `000`       | Level I                | First version                                                                       |
| `001`       | Level II v1.0          | First MS Basic usage                                                                |
| `010`       | Level II v1.1a         |                                                                                     |
| `011`       | Level II v1.1b         |                                                                                     |
| `100`       | Level II v1.2          |                                                                                     |
| `101`       | Level II v1.3          | Final system version                                                                |
| `110`       | Level II v1.3 (+patch) | Patch doesn't require the duplicate characters for lowercase mod, provided by MattB |
| `111`       | Diagnostic ROM         | [Adrians' Diagnostic ROM](https://github.com/misterblack1/trs80-diagnosticrom)      |

## Default Bundle

- [ROM A](rom_a_8.bin)
- [ROM B](rom_b_8.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `000`       | Level I                |
| `001`       | Level II v1.0          |
| `010`       | Level II v1.1a         |
| `011`       | Level II v1.1b         |
| `100`       | Level II v1.2          |
| `101`       | Level II v1.3          |
| `110`       | Level II v1.3 (+patch) |
| `111`       | Diagnostic ROM         |

## Reversed "r"

- [ROM A](rom_a_8_r.bin)
- [ROM B](rom_b_8_r.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `000`       | Diagnostic ROM         |
| `001`       | Level II v1.3 (+patch) |
| `010`       | Level II v1.3          |
| `011`       | Level II v1.2          |
| `100`       | Level II v1.1b         |
| `101`       | Level II v1.1a         |
| `110`       | Level II v1.0          |
| `111`       | Level I                |

## Flipped "f"

- [ROM A](rom_a_8_f.bin)
- [ROM B](rom_b_8_f.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `000`       | Level I                |
| `001`       | Level II v1.2          |
| `010`       | Level II v1.1a         |
| `011`       | Level II v1.3 (+patch) |
| `100`       | Level II v1.0          |
| `101`       | Level II v1.3          |
| `110`       | Level II v1.1b         |
| `111`       | Diagnostic ROM         |

## Reversed & Flipped "rf"

- [ROM A](rom_a_8_rf.bin)
- [ROM B](rom_b_8_rf.bin)

| Bit Pattern | Name                   |
| ----------- | ---------------------- |
| `000`       | Diagnostic ROM         |
| `001`       | Level II v1.1b         |
| `010`       | Level II v1.3          |
| `011`       | Level II v1.0          |
| `100`       | Level II v1.3 (+patch) |
| `101`       | Level II v1.1a         |
| `110`       | Level II v1.2          |
| `111`       | Level I                |
