Super Mario Bros: Definitive Tweaks
A compilation of addendum hacks
by Josephine Lithius (Jo Li)
--

[1. (INDE) INDEX]

 1. (INDE) Index ---------------------------------- You aren't NOT here. (:
 2. (INDU) Introduction & Questions --------------- 
 3. (COTE) Archive Contents ----------------------- 
 4. (HOTO) How to Use ----------------------------- 
 5. (NOBU) Known Bugs ----------------------------- 
 6. (SPTH) Special Thanks ------------------------- 
 7. (COFO) Contact Information -------------------- 
 8. (CORI) Legal Stuff ---------------------------- 
--

[2. (INDU) INTRODUCTION & QUESTIONS]

- "What is 'Super Mario Bros: Definitive Tweaks'?"
  As the name suggests, this is a collection of little tweaks and modifications
which may make Super Mario Bros. Definitive even better.

- "What is 'Super Mario Bros: Definitive'?"
  Super Mario Bros: Definitive is, as one might guess, the self-proclaimed
"definitive edition" of the original Super Mario Bros.  Created by
Simplistic_Memes and SeraphmIII, it basically takes everything great about
Super Mario Bros. 1 and 2 (the Famicom Disk System one) and combines them into
one long adventure, running exclusively on the Super Mario Bros. 2 engine!

  You can find the original ROM hack download and information here:
  https://www.romhacking.net/hacks/8509/

- "What do these 'tweaks' of yours do?"
  Well, there are four different tweaks I've made:

  - Spiny Egg Behavior Fix
    Enables the CORRECT Spiny Egg behavior.
   (Bouncing off walls, aiming where the player WILL be.)
    
  - Warp Zone Scroll Lock Fix
    Enables the screen's scroll stop just before a Warp Zone.
   (Unless the player is at the top of the screen, of course.)
   
  - Super Mario Bros. Graphics
    Replaces all Super Mario Bros. 2 graphics with their SMB1 ones.
    
  - Super Mario Bros. Luigi Colors
    Changes Luigi's colors BACK to his Super Mario Bros. 1 versions.
   (But does NOT disable his SMB2 physics.)

- "Why did you make this?"
  Honestly, I was inspired by a review by legoboy7107.  He mentioned that the
"Spiny Egg Fix" and "Warp Scroll Stop Fix" patches didn't work -- which is
absolutely correct.  Due to the changed values, the original versions of those
hacks don't work with Definitive Edition.  So, I took a few minutes to make
ones that DID.

  And then I made patches for "reverting" the graphics to their SMB1 versions.
Just because I can.

- "Do these patches / can I apply these patches all together?"
  Yes, indeed.  Every single patch does its own thing in completely isolated
areas of the Definition Edition ROM, so you can stack these in any way at all!

  Want SMB1 graphics with the Warp Zone scroll stop?  Go for it.
  Want Luigi's palette from SMB1 with "seeker" Spiny Eggs?  It's yours!
  Want only one of these, or all of these at once?  You can absolutely have it!
--

[3. (COTE) ARCHIVE CONTENTS]

  - [Patches] (folder)
  - JDC_SMB1DE Tweaks Changed Values.txt
      A list of addresses and values changed by three of the tweaks.
     (The "SMB1 GFX" values are omitted since a LOT changed, there.)
  - JDC_SMB1DE Tweaks Changelog.txt
      Changes which were / are made by the patches.
  - JDC_SMB1DE Tweaks Readme.txt
      "Are you a roadmap?  'cause I am following ALL your twists and turns~"
    - [MMC3] (folder)
      - SMB1Def-MMC3 - SMB1 GFX.ips
      - SMB1Def-MMC3 - SMB1 Luigi Colors.ips
      - SMB1Def-MMC3 - Spiny Egg Fix.ips
      - SMB1Def-MMC3 - Warp Scroll Lock Fix.ips 
          The most current versions of the patches in "IPS" format.
	  For use ONLY with the MMC3 version of "SMB Definitive Edition".
    - [VRC3] (folder)
      - SMB1Def-VRC3 - SMB1 GFX.ips
      - SMB1Def-VRC3 - SMB1 Luigi Colors.ips
      - SMB1Def-VRC3 - Spiny Egg Fix.ips
      - SMB1Def-VRC3 - Warp Scroll Lock Fix.ips 
          The most current versions of the patches in "IPS" format.
	  For use ONLY with the VRC3 version of "SMB Definitive Edition".

REGARDING THE CHANGE LOG:
THE CHANGE LOG CONTAINS SPOILERS AND MAKE NO ATTEMPTS TO HIDE THEM!
Most changes probably won't be real game-breakers, so you can probably ignore
the text file if you want to play the game and try to figure out what's brand
new content and what's just rehashed stuff.
--

[4. (HOTO) HOW TO USE]

  Things You'll Need
  - The IPS file(s) that SHOULD have come with this TXT file
  - A MODIFIED game ROM matching these specifications:
    Super Mario Bros: Definitive (MMC3 Mapper)
      Size: 81,936 bytes -- ROM CRC32: C1A0C9D8
        OR
    Super Mario Bros: Definitive (VRC3 Mapper)
      Size: 65,552 bytes -- ROM CRC32: 6447D139
   (I will NOT provide links to an unmodified ROM file!)
  - A program to apply IPS files to ROMs
  - A system emulator or flash cart to play the game

  Suggested Programs
  - ROM HASHING: ROMhacking.net's Hasher-js (https://www.romhacking.net/hash/)
    It's ALWAYS a good idea to check your ROM's "CRC32" hash.  That way, there
    can be no mistake about the patches and such!

  - PATCHING: Floating IPS (http://www.romhacking.net/utilities/1040/) or
              beat (http://www.romhacking.net/utilities/893/)
    Floating IPS is easy to use and very reliable.
    beat would work just fine, too.  I just prefer FLIPS.
    
  - EMULATION: Varies
   (https://emulation.gametechwiki.com)
    Commentary

  How to Apply the patches to the ROM, The Simple Way
  - Toss your PRE-MODIFIED ROM and the IPS patches from this archive into
    into the same directory as your patching utility of choice.
  - Open your patching utility.  Direct it to the ROM and patch.
  - Do the command that makes the ROM patched. (Varies by program.)
  - If everything went well, your ROM should be patched.
    NO CHANGE IN SIZE SHOULD OCCUR.  If it does, something may have gone wrong.
  - Enjoy!

  IF ROM DOES NOT RUN, you more than likely tried to apply the wrong patch to
the wrong ROM or wrong type of ROM.
--

[5. (NOBU) KNOWN BUGS]

_VERSION 1.0_
- When using the "Super Mario Bros. Graphics" patch, the SMB2 Continue screen
  uses a STEEL GIRDER graphic instead of a tiny mushroom.  This is because
  that screen normally uses a moving platform graphic rather than the mushroom
  seen on the title screen.  That's just how it was in SMB2.
--

[6. (SPTH) SPECIAL THANKS]

  - ROMhacking.net
    A group of pretty cool people with one collective goal in mind: modifying,
    changing, and often improving classic games for fans new and old!  Warm and
    welcoming, talented and totally cool, this is the place for ROM hacks!

  - Simplistic_Memes (https://www.romhacking.net/community/6842/)
  - SeraphmIII (https://www.romhacking.net/community/8547/)
    The minds behind Super Mario Bros: Definitive.  These tweaks were
    made specifically FOR their hack, so you know...

  - legoboy7107
   (https://www.romhacking.net/forum/index.php?action=profile;u=195138)
    As mentoned, his review was the one that inspired me to do this.

  - Shigeru Miyamoto (https://en.wikipedia.org/wiki/Shigeru_Miyamoto)
    The man behind the plumber.  Without him, there would be no Mario Bros,
    much less SUPER Mario Bros.  He always deserves a shout-out.

  - Famicom Emulator Ultra X (FCEUX) Team (https://fceux.com)
    The crazy minds behind the premier Nintendo 8-bit emulator.  It has a lot
    of very useful debugging features, AND it's just a darn good emulator.

  - YY (https://w.atwiki.jp/yychr/)
    The mysterious creator of YY_CHR.NET, a very handy-dandy little graphic
    tile editor!  This tool has been extremely helpful in a lot of what I and
    others do.
  
  - Christian Maas (http://www.chmaas.handshake.de/)
    The fella behind my hex editor of choice, XVI32.  It might not have the
    "table" functions of more dedicated editors, but it's a darn good piece
    of software for general poking-around!
--

[7. (COFO) CONTACT INFORMATION]

    If you need to get in contact with me, you can find me here:
  - ROMHacking.net: https://www.romhacking.net/community/3879/
  -         Tumblr: https://jolikmc.tumblr.com
  -   Other places: Check Tumblr!

    As always, contact me if need be!
--

[8. (CORI) LEGAL STUFF]

    Game content, "game series", and related ideas and concepts created by
people and © company.

    These ROM hacks were created by Josephine Lithius and is distributed as a
"Public Domain" work which MAY BE SHARED AND DISTRIBUTED FREELY so long as the
contents -- including copyrights and contact information -- are NOT MODIFIED.
I mean it.  Don't make me wag my finger at you.

    These ROM hacks were originally released EXCLUSIVELY to ROMhacking.net.  If
you found it anywhere else, THAT'S PERFECTLY FINE!  I don't mind!  Just know
that the version at ROMhacking.net is ALWAYS going to be the most up-to-date!
  
    Use of these ROM hacks IS ALLOWED under a public-domain-equivalent license,
so go nuts.  If you RELEASE you ROM hack with this modification, though, it
would be a REALLY nice gesture if credited me for the original changes.
It makes me smile when people like the stupid little things I do for myself~
