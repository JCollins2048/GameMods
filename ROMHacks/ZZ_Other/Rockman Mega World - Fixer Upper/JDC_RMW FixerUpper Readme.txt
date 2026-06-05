Rockman Mega World "Fixer Upper"
A Rockman Mega World ROM Hack
by Josephine Lithius (Jo Li)
--

[1. (INDE) INDEX]

 1. (INDE) Index ---------------------------------- The table of contents!
 2. (INDU) Introduction & Questions --------------- Pre-emptively answering Qs!
 3. (COTE) Archive Contents ----------------------- What's in the box?!
 4. (HOTO) How to Use ----------------------------- Instructions and such!
 5. (NOBU) Known Bugs ----------------------------- Probably more to be found!
 6. (SPTH) Special Thanks ------------------------- You people are awesome!
 7. (COFO) Contact Information -------------------- Oh, no -- I'm shy!
 8. (CORI) Legal Stuff ---------------------------- I am not a lawyer!
--

[2. (INDU) INTRODUCTION & QUESTIONS]

- "What is 'Fixer Upper'?"
  This is a ROM hack designed to "fix up" some of the more annoying things
  about this remake -- or at least the things that annoyed ME.  The ultimate
  goal of this hack is to make the Mega Drive remake play a LITTLE more like
  its NES counterparts in terms of the game engine.

- "What does this ROM hack do?"
  At present, it removes the forced delay between shots and removes enemy
  I-Frames, which allows players to rapidly fire projectiles and potentially
  overwhelm enemies.  It also increases the speed of the default weapon by
  about 33.3%, making it match the Famicom version more closely.

- "What do you mean 'forced delay'?"
  In the original Famicom games, the player could potentially fire a shot every
  2 frames or 0.03~ seconds.  This was usually achieved by "turbo" controllers
  and the like.  When Minakuchi Engineering remade the first three Rockman
  games, they decided to but a HARD limit on how frequently a player can
  actually shoot.  This limit was 8 frames (0.13~ seconds) for most weapons.
  So, instead of shooting 30 times a second, players could only shoot 7.5 times.

- "This doesn't sound like that big of a deal."
  For someone who can press the fire button up to 15 times per second?  IT IS.

- "Freak."
  Thank you~  (:

- "What are 'I-Frames'?"
  "I-Frames", or "invulnerability frames", are frames of animation where an
  object cannot be injured or interacted with.  By default, Rockman Mega World
  has this set to 8 frames, meaning enemies could only be hurt every 0.13~
  seconds.  I've reduced this to 1 frame, meaning enemies can be hurt every
  single frame they're on screen.

- "This sounds cheat-y.  Why do all this?  Doesn't this make the game too easy?"
  The main reason I did this wasn't to make the game easier -- which, really,
  it's not.  The main reason I did this was to bring it more in line with its
  NES counterparts.  

- "Why label it 'Rockman Mega World' when there's patches for both versions
   of the game?"
  I actually created patch codes for the Japanese version first, then located
  the values in the European ROM and set them to match.
 (Check the "Changed Addresses" document for more details!)

- "Why are there two patches for the US versions of the game?"
  For some dang reason, Retro-bit decided to move the command code located at
  Address $B647 ALL the way back to Address $B62F.  As such, one patch is for
  the Genesis Mini ROM and one patch is for the Retro-bit ROM.  Otherwise, the
  two game ROMs are mostly identical...
 (See the Changed Addresses for the specifics.)

- "A patch didn't work on a specific version / region of the game!"
  I dunno what to tell ya.  I've personally tested my patches on every known
  dump of every region of the game that I could get my hands on and can verify
  that they work on ALL known variations EXCEPT for the following:
  "Mega Man - The Wily Wars (E) [f2]" (CRC32: AFCCDD5)
  This "cracked" version by "Jarre" is not compatible with my hack due to what
  appears to be a shifted header location?  I'm not sure.  Regardless, I'd
  recommend checking the CRC32 of your ROM and make sure it's both clean AND
  registered in the No-Intro database.  Otherwise, unpredictable things may
  happen.

- "This game doesn't run on [Emulator X] / real hardware!"
  You might be using an old version of the patch.  As of v1.0.5, the patched
  game should run on real hardware and most modern-day emulators.

- "I can't save the game using the European ROM with [Emulator X]!"
  Entirely possible.  I only tested the European version on Regen, Exodus, and
  GENS-RR.  Regen refused to save properly, regardless of whether I was using
  SRAM or EEPROM, while Exodus and GENS-RR saved just fine.  Regardless, I'll
  look into it further.
--

[3. (COTE) ARCHIVE CONTENTS]

  - [Patches] (folder)
    -    JDC_MMWW FixerUpper (E)-v105.ips
    - JDC_MMWW FixerUpper (U-GM)-v105.ips          ("Genesis Mini" USA version)
    - JDC_MMWW FixerUpper (U-RB)-v105.ips          ("Retro-bit" USA version)
    -     JDC_RMW FixerUpper (J)-v105.ips
        The most current version of the patch in "IPS" format.
       (These CANNOT be mixed-and-matched.)
  - JDC_RMW FixerUpper Changed Addresses.txt
      As a change of pace, here's a list of ALL the addresses that were changed
      to make this ROM hack happen.  Includes both (J) and (E) addresses.
  - JDC_RMW FixerUpper Changelog.txt
      A bunch of changes were made.  Here's a list of them.
  - JDC_RMW FixerUpper Readme.txt
      "Why do they call it oven when you 'of in' the cold food...?"

REGARDING THE CHANGE LOG:
THE CHANGE LOG CONTAINS SPOILERS AND MAKE NO ATTEMPTS TO HIDE THEM!
Most changes probably won't be real game-breakers, so you can probably ignore
the text file if you want to play the game and try to figure out what's brand
new content and what's just rehashed stuff.
--

[4. (HOTO) HOW TO USE]

  Things You'll Need
  - The IPS file(s) that SHOULD have come with this TXT file
  - An unmodified game ROM matching one of these descriptions:
    Rockman Mega World (Japan)
      Size: 2,097,152 bytes -- CRC32: 85C956EF
    Mega Man: The Wily Wars (Europe)
      Size: 2,097,152 bytes -- CRC32: DCF6E8B2
    Mega Man: The Wily Wars (USA, Genesis Mini)
      Size: 2,097,152 bytes -- CRC32: CD405DB
    Mega Man: The Wily Wars (USA, Aftermarket / Retrobit)
      Size: 2,097,152 bytes -- CRC32: 831020B
   (I will NOT provide these!  Sorry~)
  - A program to apply IPS files to ROMs
  - A Mega Drive / Genesis emulator or flash cart to play the game

  Suggested Programs
  - ROM HASHING: ROMhacking.net's Hasher-js (https://www.romhacking.net/hash/)
    It's ALWAYS a good idea to check your ROM's "CRC32" hash.  That way, there
    can be no mistake about the patches and such!

  - PATCHING: Floating IPS (http://www.romhacking.net/utilities/1040/) or
              beat (http://www.romhacking.net/utilities/893/)
    Floating IPS is easy to use and very reliable.
    beat would work just fine, too.  I just prefer FLIPS.
    
  - EMULATION: ???
   (https://emulation.gametechwiki.com/index.php/Sega_Genesis_emulators)
    Honestly?  I don't know what to recommend.  I tend to use severely outdated
    emulators like GENS-RR and Regen, but those are not widely recommended by
    the community.  I guess as long as you're not using something ancient
    like Genecyst (still great for its time!), you should be good to go?

  How to Apply the patches to the ROM, The Simple Way
  - Toss your UNMODIFIED ROM and the IPS patch from this archive into
    into the same directory as your patching utility of choice.
  - Open your patching utility.  Direct it to the ROM and patch.
  - Do the command that makes the ROM patched. (Varies by-program.)
  - If everything went well, your ROM should be patched.
    NO CHANGE IN SIZE SHOULD OCCUR.  If it does, something may have gone wrong.
  - Enjoy!

  IF ROM DOES NOT RUN, you more than likely tried to apply the wrong patch to
  the wrong ROM or wrong type of ROM.
--

[5. (NOBU) KNOWN BUGS]

_ALL VERSIONS_
- Certain enemies -- such as the Kerog units in Bubbleman's stage -- no longer
  flicker when damaged.  I don't know why, so I don't know how to fix it.
 (Probably has to do with how I did the "I-Frames" thing.)
 
- When the game is lagging, it's possible for projectiles to pierce enemies
  they're not supposed to and keep doing damage.
 (This occasionally happens in the normal game, but it's especially noticeable
  in this hack since I-Frames are disabled and there's no shot delay.)
  
- The European version DOES NOT SAVE under certain emulators.
 (I've only experienced this with Regen.  I'm SORT of leaning toward this being
  an issue with Regen, but considering Regen gives me 16 KB SRAM files for all
  three other versions, well...)
  
- The European version will occasionally confuse an emulator's region detection
  and throw up a "wrong region" error.  Forcing the emulator to use its
  European / PAL region setting will fix this.
--

[6. (SPTH) SPECIAL THANKS]

  - ROMhacking.net
    For an having an awesome community and a treasure trove of hacking
    materials, resources, help, and pretty much anything you could want!

  - Overseer190 (https://www.youtube.com/channel/UCh6BvNl4rXMnPxf9vRS-9Tg)
    This is the person who got me back into caring about Rockman Mega World.
    He sort of twisted my arm (indirectly) on The Cutting Room Floor and even
    made some great videos demonstrating some very odd things you wouldn't
    think were possible with the game!  Check out his channel!

  - Tony H and gedowski @ GameHacking.org (https://https://gamehacking.org/)
    These two code monkeys provided some of the coding used in this ROM hack.
    It was extremely helpful and these guys do good work.  Cheers, lads!

  - Stéphane Dallongeville (https://www.youtube.com/user/stefda)
    He created the original version of the GENS emulator!

  - The TASvideos.org community (https://tasvideos.org/)
    Some of these brave souls made the modified version of GENS that I use!

  - Nemesis (http://www.exodusemulator.com/)
    This person made a VERY good Sega Genesis / Mega Drive emulator.  It's very
    accurate AND it has a bevy of debugging features which helped me track down
    all the values and things that make this hack tick.

  - Christian Maas (http://www.chmaas.handshake.de/)
    He created the hex editor I used on this ROM hack, XVI32.  It's great!

  - Pethronos @ ROMhacking.net
   (https://www.romhacking.net/?page=submissions&action=submissions&id=26115)
    This person alerted me to the fact that the hack wasn't working under Kega.
    They also recommended I just slap the SRAM patches into my own work, since
    patching the SRAM versions worked fine for them.  Lo and behold, that made
    the ROMs run under Kega and Exodus just fine.  Thanks for the tip!

  - Unknown contributor
    Someone, somewhere, made the original "Rockman Mega World" alternate ROM
    which uses SRAM saving.  No idea who they are, but they laid the groundwork
    for the next two thanks.

  - MottZilla (http://thegaminguniverse.org/ninjagaiden4/mottzilla/)
    They made the European Wily Wars SRAM patch, which I totally stole-- I mean
    borrowed for my own work.  Eh heh heh.

  - Plombo (https://www.romhacking.net/community/6638/)
    They converted the Euro Wily Wars SRAM patch for the US Genesis Mini ROM.
    And of course, I used that one for my work, too.  Cheers!

  - Kuwabara @ ROMhacking.net (https://www.romhacking.net/community/701/)
    Created the Genesis / Mega Drive FixCheckSum program.  Which I used.
    Thanks, Kuwabara!
--

[7. (COFO) CONTACT INFORMATION]

    You can find me at the ROMhacking.net forums as "Josephine Lithius"
(http://www.romhacking.net/forum/), but also the following places:
  - Twitter: https://twitter.com/JoLiKMC
  -  Tumblr: https://jolikmc.tumblr.com/
  - YouTube: https://www.youtube.com/@JoLiKMC

    As always, contact me if need be!
--

[8. (CORI) LEGAL STUFF]

    "Mega Man", "Rockman", and related ideas and concepts created by MANY
people and © Capcom Co, Ltd.

    This ROM hack was created by Josephine Lithius and is distributed as a
"Public Domain" work which MAY BE SHARED AND DISTRIBUTED FREELY so long as the
contents -- including copyrights and contact information -- are NOT MODIFIED.
I mean it.  Don't make me wag my finger at you.

    This ROM hack was originally released EXCLUSIVELY to ROMhacking.net.  If
you found it anywhere else, THAT'S PERFECTLY FINE!  I don't mind!  Just know
that the version at ROMhacking.net is ALWAYS going to be the most up-to-date!
  
    Use of this ROM hack IS ALLOWED under a public-domain-equivalent license,
so go nuts.  If you RELEASE you ROM hack with this modification, though, it
would be a REALLY nice gesture if credited me for the original changes.
You don't HAVE to, but I'd certainly appreciate the hey-ho!
