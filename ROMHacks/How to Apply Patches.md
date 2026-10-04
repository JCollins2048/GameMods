## How to Apply Patches to ROMs

The basic idea is same across all game consoles, but the execution method may vary slightly.

**Instructions:**
1. Gather your game files and patch files somewhere — preferably in the same folder.
2. Open your ROM patcher of choice.
3. Select or drop your original game file and patch file into the ROM patcher
4. Hit **Apply**.

It should return your patched file to you lickety-split. Test your file, and if everything worked, enjoy your modified game!

### Lunar IPS (LIPS)

The format that launched a thousand ROM hacks. A little old, but still a very solid choice for simple patch jobs.

**Website:** https://fusoya.eludevisibility.org/lips/

**Supported Formats:**
- International Patching System (`IPS`)

**Pros:**
- Very simple interface
- Easy to use — no fuss, no muss

**Cons:**
- Has a 16 MB limit for input files
- Uses simple "find address, paste code" method, potentially leading to larger patch sizes
- Doesn't warn you if a ROM and patch don't go together

### beat

The de facto successor to *Lunar IPS*. Improves upon the idea in several ways.

**Website:** https://romhackplaza.org/utilities/beat-utility/ (mirror)

**Supported Formats:**
- International Patching System (`IPS`)
- Beat Patching System (`BPS`)

**Pros:**
- Accepts files larger than 16 MB
- Uses source/target delta-style encoding, resulting in smaller patches
- Warns you if a ROM and patch don't go together

**Cons:**
- **Extremely** stubborn about matching the exact file with the exact patch
- Mostly for advanced users

### Floating IPS (Flips)

An advancement on *Lunar IPS* which also supports `BPS` files.

**Website:** https://git.disroot.org/Sir_Walrus/Flips

**Supported Formats:**
- International Patching System (`IPS`)
- Beat Patching System (`BPS`)

**Pros:**
- Based on *Lunar IPS*, so it has a simple interface
- Warns you if a ROM and patch don't go together

**Cons:**
- A tiny bit more finicky than *Lunar IPS*
- Slightly over-engineered for everyday usage

### PPF-O-Matic

A classic disc-based patching system. It was made for PlayStation discs, but is most commonly used on large, disc-based files.

**Website:** https://gamingdoc.org/software/generic/windows/patching-tools/ppf-o-matic/

**Supported Formats:**
- PlayStation Patch Format (`.ppf`) (also works on other CD-based formats)

**Pros:**
- Easy to use — no fuss, no muss
- Has an "undo patch" function

**Cons:**
- Input only; cannot *create* patches
- Doesn't warn you if an image and patch don't go together

### Xdelta Patcher

A cross-platform frontend for use with *xdelta tool*. Makes patching and creating `xdelta` patches a snap!

**Website:** https://github.com/marco-calautti/DeltaPatcher

**Supported Formats:**
- *xdelta tool* format (`.xdelta`)

**Pros:**
- Easy to use — no fuss, no muss
- Can be used on pretty much any file in existence
- Uses delta encoding, making for tidy code and small-sized patch files

**Cons:**
- Doesn't warn you if a file and patch don't go together

### Rom Patcher JS

The absolute easiest way, but not necessarily the most sure-fire, to patch just about any kind of file to any kind of game.

**Website:** https://www.marcrobledo.com/RomPatcher.js/<br>
*<small>\* It can also be found on a number of ROM hacking websites.</small>*

**Supported Formats:**
- All of the above, and then some!

**Pros:**
- It's on most hacking websites and doesn't require a download
- It's really easy to use
- It shows the main three file hashes most sites use
- It generally does its job well

**Cons:**
- Doesn't warn you if a ROM and patch don't go together
    - This is especially the case with `IPS` files