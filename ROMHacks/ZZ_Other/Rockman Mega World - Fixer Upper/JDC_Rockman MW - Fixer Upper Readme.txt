Rockman Mega World - "Fixer Upper"
  A Mega Drive / Sega Genesis hack by JCollins2048

---

[Introduction]
This is a ROM hack designed to "fix up" some of the more annoying things
about this remake -- or at least the things that annoyed ME.  The ultimate
goal of this hack is to make the Mega Drive remake play a LITTLE more like
its NES counterparts in terms of the game engine.

So basically: reduced refire delay, smaller I-Frames for enemies, and a couple
of other little changes.

[Package Contents]
- JDC_Mega Man WW - Fixer Upper (E) -- The hack itself, European version.
- JDC_Mega Man WW - Fixer Upper (U-GM) -- "Genesis Mini" USA version.
- JDC_Mega Man WW - Fixer Upper (U-RB) -- Retro-Bit reproduction version.
- JDC_Rockman MW - Fixer Upper (J) -- Original Japanese version.

[Tested CRC32 ROM Hashes]
- dcf6e8b2 -- Mega Man - The Wily Wars (Europe)
- 85c956ef -- Rockman - Mega World (Japan)
- 0cd405db -- Mega Man - The Wily Wars (USA) (Mega Drive Mini, Genesis Mini)
- 0831020b -- Mega Man - The Wily Wars (World) (Retro-Bit)

[Known Bugs]
_All versions_
- Certain enemies no longer flicker when damaged
  (Example: Kerog units in Bubbleman's stage)
- Some projectiles will pierce and do more damage when the gane lags
  (Vanilla bug, but *much* more noticeable here.)
- The European version DOES NOT SAVE under certain emulators
- The European version will occasionally confuse an emulator's region detection
  (Forcing European / PAL region will fix this.)

[Tools Used]
- XVI32 -- http://www.chmaas.handshake.de/delphi/freeware/xvi32/xvi32.htm
    A simple hex editor. Used to alter all of the changed code.

- Exodus -- https://www.exodusemulator.com/
    A highly-accurate Sega 16-bit emulator with debugging functions.
    I used this to find the values I was looking for.

- Fix CheckSum -- https://www.romhacking.net/utilities/342/
    Apparently, Sega 16-bit ROM hacks need their checksums recalculated.
    This made that possible.

- GENS-RR -- https://github.com/TASEmulators/gens-rerecording
    A version of the GENS Sega 16-bit emulator tailored for tool-assisted stuff.
    Used this while testing my edits.

- Regen -- https://segaretro.org/Regen (mirror)
    A very capable Sega 16-bit emulator. Used this while testing my edits.

- Floating IPS -- https://git.disroot.org/Sir_Walrus/Flips
    A ROM patching and patch-making program. Used to make and test patches.

[Special Thanks]
- Overseer190 -- https://www.youtube.com/channel/UCh6BvNl4rXMnPxf9vRS-9Tg
    This is the person who got me back into caring about Rockman Mega World.
    He sort of twisted my arm (indirectly) on The Cutting Room Floor and even
    made some great videos demonstrating some very odd things you wouldn't
    think were possible with the game!

- Tony H and gedowski -- https://https://gamehacking.org/
    These two provided some of the coding used in this ROM hack.
    It was extremely helpful and these guys do good work.

- Pethronos --
   https://www.romhacking.net/?page=submissions&action=submissions&id=26115
    This person alerted me to the fact that the hack wasn't working under Kega.
    They also recommended I just slap the SRAM patches into my own work, since
    patching the SRAM versions worked fine for them.  Lo and behold, that made
    the ROMs run under Kega and Exodus just fine.  Thanks for the tip!

- Unknown contributor
    Someone, somewhere, made the original "Rockman Mega World" alternate ROM
    which uses SRAM saving.  No idea who they are, but they laid the groundwork
    for the next two thanks.

- MottZilla -- http://thegaminguniverse.org/ninjagaiden4/mottzilla/
    Made the European Wily Wars SRAM patch, which I used.

- Plombo -- https://www.romhacking.net/community/6638/
    Converted the Euro Wily Wars SRAM patch for the US Genesis Mini ROM.