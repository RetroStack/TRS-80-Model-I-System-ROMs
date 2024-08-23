# TRS-80 Model 1 System ROMs

Within this repository, various versions of the Model 1 system ROMs are available in different bundles. This is useful for anyone looking to recreate the system ROMs using modern and readily available ROMs.

## ROM Bundles

The bundles listed below are categorized by their sizes, using standard IC identifiers such as 2x64 and 2x512. Examples include 2764, 27512, and 28512. To calculate the sizes of these ROMs, use the number after the "x" and divide it by 8 (since these ROMs handle 8 bits). For instance, 512/8 = 64.

This means the ROM manages data for 64KB. The full Model 1 ROM is 12KB, distributed across two ROMs. The first ROM requires 8KB, and the second ROM requires 4KB. Instead of using different sizes, you can use the same size for both. The bundles provided are padded with zeros to match the same size, simplifying usage.

In summary: use the same ROM size for both. The address decode will ensure there are no conflicts on the data bus. There are always two ROMs available: ROM A (left - Z33) and ROM B (right - Z34).

If you have a Rev G board, you can simply plug them in. For all versions before Rev G, you'll need to provide a jumper wire to connect all the address lines to the DIP sockets.

The following bundles are available:

- [Binaries for 2x64 ROMs - 8kb](/1-Option_2x64) - Individual ROMs, unbundled
- [Bundles for 2x128 ROMs - 16kb](/2-Option_2x128) - Bundles of two different ROM versions
- [Bundles for 2x256 ROMs - 32kb](/4-Option_2x256) - Bundles of four different ROM versions
- [Bundles for 2x512 ROMs - 64kb](/8-Option_2x512) - Bundles of eight different ROM versions

## Main TRS-80 Model 1 Repository

For additional resources related to the TRS-80 Model 1, be sure to check out the [central page for the TRS-80 Model 1](https://www.github.com/RetroStack/TRS-80-Model-I) on [RetroStack](https://www.github.com/RetroStack).

## Support this Project

RetroStack is passionate about exploring and preserving the legacy of older computer systems. My work involves creating detailed documentation and videos to share the knowledge. I am also dedicated to reviving these classic systems by reimplementing them and offering replacement parts at no cost. If you're keen on supporting this unique project, I invite you to visit my [Patreon page](https://www.patreon.com/RetroStack). Your support would be immensely valuable and greatly appreciated!
