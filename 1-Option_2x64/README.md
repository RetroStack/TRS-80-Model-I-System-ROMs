# TRS-80 Model 1 System ROMs - Binaries for 2x64 ROMs (8kb)

This repository offers individual ROM binaries for recreating TRS-80 Model 1 ROMs.

All binaries are 8kb and padded with zeros where the original ROM is smaller. There are always two ROMs: ROM A (left - Z33) and ROM B (right - Z34). ROM B is only a 4kb part, so the upper half of every ROM B binary is zero.

Unlike the bundles, these files hold a single version each, so there is nothing to select - there are no "r", "f" or "rf" variants here, and none are needed.

## [Adrians' Diagnostic ROM](https://github.com/misterblack1/trs80-diagnosticrom) padded for 8kb

- [ROM A](rom_a_diag.bin)
- No ROM B needed!

## Level I ROM

- [ROM A](rom_a_L1.bin)
- [ROM B](rom_b_L1.bin) - blank!

Level I is only 4kb and fits entirely in the lower half of ROM A. No ROM B is needed. The blank `rom_b_L1.bin` is kept so a socket can be populated and to match what the bundles put in that slot.

## Level II ROM - version 1.0

- [ROM A](rom_a_L2_v10.bin)
- [ROM B](rom_b_L2_v10.bin)

## Level II ROM - version 1.1a

- [ROM A](rom_a_L2_v11a.bin)
- [ROM B](rom_b_L2_v11a.bin)

## Level II ROM - version 1.1b

- [ROM A](rom_a_L2_v11b.bin)
- [ROM B](rom_b_L2_v11b.bin)

## Level II ROM - version 1.2

- [ROM A](rom_a_L2_v12.bin)
- [ROM B](rom_b_L2_v12.bin)

## Level II ROM - version 1.3 (latest)

- [ROM A](rom_a_L2_v13.bin)
- [ROM B](rom_b_L2_v13.bin)

## Level II ROM - version 1.3 (+patch)

The trailing "p" marks the patched variant. The patch doesn't require the duplicate characters for the lowercase mod, provided by MattB.

- [ROM A](rom_a_L2_v13p.bin)
- [ROM B](rom_b_L2_v13p.bin)

## Notes on Identical Binaries

Every version above is listed with a complete pair, so you can grab the two files you need without cross-referencing a table. That means some files are byte-identical on purpose:

- `rom_a_L2_v11a.bin`, `rom_a_L2_v11b.bin` and `rom_a_L2_v12.bin` are identical. Versions 1.1a, 1.1b and 1.2 differ only in ROM B.
- `rom_b_L2_v13p.bin` is identical to `rom_b_L2_v13.bin`. MattB's patch changes three bytes in ROM A only.

These are the same binaries used to build the [2x128](../2-Option_2x128), [2x256](../4-Option_2x256) and [2x512](../8-Option_2x512) bundles.
