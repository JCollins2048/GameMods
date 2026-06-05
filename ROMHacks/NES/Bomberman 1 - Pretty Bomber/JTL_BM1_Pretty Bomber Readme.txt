"Bomberman, Starring Pretty Bomber"
  A Bomberman ROM hack by Josephine Lithius

[1. (INDE) INDEX]
 1. (INDE) Index ------------------------------------------- Hey, look!  Words!
 2. (INDU) Introduction & Questions --------------------------- Why you do dis?
 3. (COTE) Archive Contents --------------- Patches, puffery, and printed word.
 4. (HOTO) How to Use ----------------------- Surprisingly simple instructions!
 5. (NOBU) Known Bugs ------------------------ Glitches galore!  Or, maybe not?
 6. (SPTH) Special Thanks -------- Peeps who inspire me to do this sorta thing.
 7. (COFO) Contact Information -------------------------------- Meep!  I'm shy!

[2. (INDU) INTRODUCTION & QUESTIONS]
- "What is 'Bomberman, Starring Pretty Bomber?'"
  It's Bomberman, on the NES.  Starring Pretty Bomber.  Um... yeah.

- "Wait, is this just another 'skin/player swap' mod?"
  More-or-less.  I changed a few other graphics to look nicer, but other than
  that... yeah.  Pretty Bomber is the 

- "Who is the 'Pretty Bomber?'"
  Pretty Bomber is a character first introduced in the 1994 video game,
  "Super Bomberman 2."  In this game, she is a villain -- one of the Five
  Dastardly Bombers -- who wants to capture Shiro/White Bomberman and take
  over the universe.
  After her first appearance, she becames one of Bomberman's friendly rivals,
  his occasional love interest, and even returned to villainy, a few times.
  When not causing mischief, though, she likes to sing.  Apparently?

  Despite their similar looks, Pretty Bomber is NOT related to Miss Honey, a
  cowgirl character who appears from Super Bomberman 4 onward.

- "Why did you make this, anyway?"
  I wanted to play Bomberman, but I didn't want to play AS Bomberman.
  Plus, I like Pretty Bomber.
  (I also like Lady Bomber from Super Bomberman 4, but I know Pretty Bomber is
   a little more widely-recognized.)

- "What's the storyline of this ROM hack?"
  The original Japanese and English stories are a bit different, but for this
  purposes of this hack, I used the English storyline:
  Pretty Bomber didn't like working in the bomb-making factory, so when she
  heard that anyone who can reach the surface of the planet will become human,
  she set a course through the underground building, fighting her way through
  all the enemies that dare to get in her way.
  
- "Will you do other character swaps for this game?"
  Mm, probably not.

- "Why did you go with 'IPS' format instead of your usual 'BPS' format?"
  Usually, I go with BPS format because, on certain games, IPS files can be
  pretty darn big because they copy the data from the START of the changes to
  the END of them.  In this case, though?  The IPS and BPS files were the same
  size, so I figured there was no point.

- "Why are there 'Player Only' patches for both regions?"
  Because, the palette address changes between regions.
  (It's $308 in the US ROM and $300 in the Japan ROM.)
  And, yes, I tried making a BPS file.  It didn't work.

[3. (COTE) ARCHIVE CONTENTS]
  - [Patches]
    - JTL_BM1_Pretty Bomber vxxx (J).ips
    - JTL_BM1_Pretty Bomber vxxx (U).ips
    - JTL_BM1_Pretty Bomber vxxx (J, Player Only).ips
    - JTL_BM1_Pretty Bomber vxxx (U, Player Only).ips
        The most current version of the patches.
	NOTE: The "Player Only" patches ONLY change Bomberman's sprites/palette.
	      Everything else, including the title screen, stays the same.
  - JTL_BM1_Pretty Bomber Changelog.txt
      Wanna see what's different between versions?  Check this out.
  - JTL_BM1_Pretty Bomber Readme.txt
      This is the very document you are reading!

DO NOTE: THE CHANGE LOGS CONTAIN SPOILERS AND MAKE NO ATTEMPTS TO HIDE THEM!
         Most changes probably won't be real game-breakers, so you can probably
         ignore the text files if you want to play the game and try to figure
         out what's brand new content and what's just rehashed stuff.

[4. (HOTO) HOW TO USE]
  Things You'll Need
  - The patch file of choice that SHOULD have come with this TXT file
  - A Bomberman US or Japanese NES ROM (24,592 bytes in size)
   (I will not provide EITHER, no matter how much you ask.  Sorry!)
  - A program to apply patch files to ROMs
  - An NES emulator or NES flash cart of your choice (to play the game)

  Suggested Programs
  - PATCHING: Floating LIPS (https://www.romhacking.net/utilities/1040/) or
              Lunar IPS (https://fusoya.eludevisibility.org/lips/)
    These are both pretty easy to use, but FLIPS has more features.
    (Kind of irrelevant for the purposes of this, though.)
  - EMULATION: FCE Ultra X (https://www.fceux.com/) or
               VirtuaNES (https://virtuanes.s1.xrea.com:8080/) or
               Nestopia UE (https://0ldsk00l.ca/nestopia/)
    Nestopia and VirtuaNES are super-lightweight emulators which run most games
    pretty flawlessly.  FCE Ultra X, however, is pretty much the best emulator
    I've ever used and still doesn't require a hugely-powerful computer.

  How to Apply the patches to the ROM, The Simple Way (tm)
  - Toss your UNMODIFIED ROM(s) and the IPS file(s) from this archive into
    into the same directory as your patching utility of choice.
  - Open your patching utility.  Direct it to the ROM and patch.
  - Do the command that makes the ROM patched. (Varies by program.)
  - If everything went well, your Bomberman ROM should be patched.
    NO CHANGE IN SIZE SHOULD OCCUR.  If it does, something may have gone wrong.
  - Enjoy!

  IF ROM DOES NOT RUN or if the graphics appear garbled or weird,
  you more-than-likely tried to apply the wrong patch to the wrong ROM
  or wrong type of ROM.  Please, check your files and try again!

[5. (NOBU) KNOWN BUGS]
_v1.0.0 ONWARD_
- So, there's a weird tile just... sitting there in the upper-left of the
  screen.  Specifically, a "1" tile from the point values.  I'm not sure why
  that's there.  I just know that this is in the original game, too.
  I might see if I can get rid of it, at some point... though, I'm not sure.

[ROM HACK-SPECIFIC]
_v1.0.0 ONWARD_
  I HAVE NOT TESTED THIS HACK WITH OTHER HACKS.
  You may experience some weirdness, bugs, or otherwise, if applying this to
  existing hacks or applying existing hacks to this one.

[6. (SPTH) SPECIAL THANKS]
  - Romhacking.net -- https://www.romhacking.net (Duh...)
    A cool community full of nice, helpful people!  Check it out!

  - Christian Maas -- http://www.chmaas.handshake.de/
    Made a nice, easy-to-use hex editor.  Great for manually finding-and-editing
    values such as palettes and EVERY SINGLE TILE IN THE TITLE SCREEN ARGH
    (Seriously, this was very helpful for that.)

  - YY -- https://www.geocities.jp/yy_6502/
    They made the BEST graphic tile editor I have ever used.
    This gets my seal of approval!

    Googie -- https://www.romhacking.net/community/569/
    Super-nice guy in the community and a fellow Bomberman fan.
    Also suggested some changes that I added into v1.1.0!

[7. (COFO) CONTACT INFORMATION]
  If you have any questions, comments, etc. you can hit me up at the
  ROMhacking.net forums (https://www.romhacking.net/forum/) under the username
  "Josephine Lithius".  I'll do my best to answer your inquiries!

  Sometimes, ROM hacking can be a real BLAST!
  ~ J