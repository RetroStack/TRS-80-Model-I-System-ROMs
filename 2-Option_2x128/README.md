# TRS-80 Model 1 System ROMs - Bundles for 2x128 ROMs - 16kb

This repository offers 16kb bundles of ROM binaries for recreating TRS-80 Model 1 ROMs, allowing version selection and easy switching as needed.

## Identifiers

Each bundle is grouped by format, identified by a code:

- Default bundles have ROMs recorded sequentially.
- Bundles marked "r" have all ROMs reversed.

## ROM Bundles

| Bit Pattern | Name           | Comment                                                                        |
| ----------- | -------------- | ------------------------------------------------------------------------------ |
| `0`         | Level II v1.3  | Final system version                                                           |
| `1`         | Diagnostic ROM | [Adrians' Diagnostic ROM](https://github.com/misterblack1/trs80-diagnosticrom) |

## Default Bundle

- [ROM A](rom_a_2.bin)
- [ROM B](rom_b_2.bin)

| Bit Pattern | Name           |
| ----------- | -------------- |
| `0`         | Level II v1.3  |
| `1`         | Diagnostic ROM |

## Reversed "r"

- [ROM A](rom_a_2_r.bin)
- [ROM B](rom_b_2_r.bin)

| Bit Pattern | Name           |
| ----------- | -------------- |
| `0`         | Diagnostic ROM |
| `1`         | Level II v1.3  |
