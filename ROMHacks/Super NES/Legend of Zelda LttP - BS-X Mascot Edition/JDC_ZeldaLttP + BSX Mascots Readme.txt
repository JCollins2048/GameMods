The Legend of Zelda: A Link to the Past — "BS-X Mascot Edition"
  A Super NES ROM hack by JCollins2048

---

[Introduction]
It's exactly what it says on the tin: a version of A Link to the Past which has
the BS-X Mascots in it rather than Link.

I didn't know how to implement a character select screen, and the person who
had the idea didn't seem eager to help. So... two patches.

(You can learn more about BS Zelda and how to play it on a replication cart
emulator at the BS Zelda HomePage: https://bszelda.zeldalegends.net/)

[Package Contents]
Note: Patches come in Headered and Unheadered format.

- JDC_ZeldaLttP + BSX Boy -- BS-X boy version.
- JDC_ZeldaLttP + BSX Girl -- BS-X girl version.

[Tested CRC32 ROM Hashes]
- F59F60D1 -- Legend of Zelda, The - A Link to the Past (USA, Headered)
- 777AAC2F -- Legend of Zelda, The - A Link to the Past (USA, No Headered)

[Known Bugs]
_v1.0.0 Onward_
- There seems to be some odd (or sometimes VERY odd) compatibility issues with
  the Girl Version and certain other ROM hacks due to the altered dialogue.
  Most of these issues are graphical, but if you combine certain patches with
  others, you may also experience scrolling issues in dungeons and missing
  dialogue (such as the Save/Continue prompt).

[Tools Used]
- Hyrule Magic -- https://www.romhacking.net/utilities/200/
    The premier Link to the Past editor. Edited dialog + title screen with it.

- Hexecute -- https://www.romhacking.net/utilities/206/
    A very nice table-based hex editor. Fixed the ellipses Hyrule Magic broke.

- YY-CHR -- https://w.atwiki.jp/yychr/
    A graphic tile editor. Used to edit the graphics.

- XVI32 -- http://www.chmaas.handshake.de/delphi/freeware/xvi32/xvi32.htm
    A simple hex editor. Used to edit something — I don't remember what.

- Snes9x -- https://github.com/snes9xgit/snes9x
    A Super Famicom and Super NES emulator. Used to test the edits.

- Floating IPS -- https://git.disroot.org/Sir_Walrus/Flips
    A ROM patching and patch-making program. Used to make and test patches.

[Special Thanks]
- Con -- https://www.romhacking.net/community/1110/
         https://bszelda.zeldalegends.net/
    Without him, I never would have been able to play as BS-X Mascot Girl!

- kerberos7 -- http://www.romhacking.net/forum/index.php?action=profile;u=69540
    They were able to dig up the address for Bunny Link's palette when I
    couldn't find it.  Thanks!

- PuzzleDude -- http://www.romhacking.net/community/1346/
    Originally found Bunny Link's palette, from what I can gather.

- BohepansTheThird - http://www.youtube.com/user/BohepansTheThird
    Found some stuff I missed + moral support.