Illusion of Gaia - Sprint Button (for Beta)
An Illusion of Gaia (May 19, 1994 localization prototype) ROM Hack
by C-Dude and Josephine Lithius (Jo Li)
--

[1. (INDE) INDEX]

 1. (INDE) Index ------------------------ A table of contents of this document!
 2. (INDU) Introduction & Questions ------------ Some questions that may arise?
 3. (COTE) Archive Contents ----------------------- What's in the box– er, ZIP?
 4. (HOTO) How to Use ----------------------------- What do I do with all this?
 5. (NOBU) Known Bugs ----------------------- If there are bugs, they are here.
 6. (SPTH) Special Thanks ------------------------- You peeps are A-OK with me!
 7. (COFO) Contact Information ------------------------ Keep in touch, why not?
 8. (CORI) Legal Stuff ------------------------------- Hello, I speak Legalese.
--

[2. (INDU) INTRODUCTION & QUESTIONS]

- "What is 'Sprint Button (for Beta)'?"
    It's a ROM hack that adds a sprint button to the May 19, 1994 localization
prototype of the game "Illusion of Gaia".

- "What does this ROM hack do?"
    By changing some values and adding a little bit of code, this hack makes
it so the player can sprint around the game using just one button instead of
having to double-tap a direction every time.

- "Wait, doesn't this already exist?"
    Yes and no.
    C-Dude released a "sprint button" hack for the final version of the game,
but this patch is specifically for the LOCALIZATION PROTOTYPE of the game.

- "Why?"
    I was playing through the localization prototype – mostly to see if the
story made any more sense than what Nintendo came up with (it doesn't) – and I
wanted a one-button sprint function.  The numbers were already there, so I
figured: "Why not?"

- "Did you get C-Dude or Raeven0's permission to release this?"
    … do I NEED their permission?  All I did was find and transplant the
appropriate values, which C-Dude released PUBLICLY, where they needed to go.
I also give full credit to C-Dude for his work, credit to Raeven0 for finding
the values, AND I've tossed in an associated document with all the changed
values at their addresses, just like in the original.

    But, you know… if this is a problem, I'm all ears.  I just don't see how it
WOULD be when this is a free, public domain patch based on public domain work.
--

[3. (COTE) ARCHIVE CONTENTS]

  - [Patches] (folder)
    - JDC_IoG Beta Sprint Button-vXXX.ips
        The most current version of the patch in "IPS" format.
  - JDC_IoG Beta Sprint Button Addresses.txt
      All of the addresses with all of the values that were changed.
  - JDC_IoG Beta Sprint Button Changelog.txt
      Changes which were / are made by the hack.
  - JDC_IoG Beta Sprint Button Readme.txt
      "You put the lime in the coconut and drink 'em both up~"
--

[4. (HOTO) HOW TO USE]

  Things You'll Need
  - The IPS file(s) that SHOULD have come with this TXT file
  - An unmodified game ROM matching one of these descriptions:
    Illusion of Gaia (USA) (Beta) - NO HEADER!!
      Size: 2,097,152 bytes -- CRC32: CE90286B
   (I will NOT provide this!  Sorry~)
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
    
  - EMULATION: Snes9x
   (https://github.com/snes9xgit/snes9x)
    While I don't like that Snes9x automatically associates a variety of files
    to itself upon first run, I cannot deny that this is one of the most
    up-to-date emulators out there.  I really like it a lot!

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

- A small thing to note:
  If the player holds the Sprint button and brushes up against a wall, then
  Tim (the player character) will seemingly freeze in the first frame of his
  walking animation.  There have been no negative side-effects of this as
  it's simply a graphical oddity (due to how things were coded).
 (This also happens in C-Dude's original hack and is just as harmless there.)
--

[6. (SPTH) SPECIAL THANKS]

  - ROMhacking.net
    For an having an awesome community and a treasure trove of hacking
    materials, resources, help, and pretty much anything you could want!

  - Raeven0 (https://www.romhacking.net/community/5839/)
  - C-Dude  (https://www.romhacking.net/community/6063/)
    Kinda goes without saying, but this ROM hack wouldn't be possible without
    their work.  So, super-big thanks to you two!

  - Christian Maas (http://www.chmaas.handshake.de/)
    Mr. Maas created XVI32, which is my hex editor of choice.  It's a pretty
    simple program and doesn't have "table" functions, but it works for what I
    need it for!

  - Alcaro (https://www.romhacking.net/community/2444/)
    Creator of Floating IPS, an improvement over Lunar IPS in a lot of ways.
    Great for ROM patching, great for ROM patch making!

  - Snes9x Team (https://github.com/snes9xgit/snes9x)
    From Gary Henderson and Jerremy Koot, to the countless others who have
    contributed to the project, I just want to say thank you for making such
    a magnificent emulator a reality!  I mean, it's no "SNESticle", but it's
    not like Sardu was going to make that anyway, right?  (;

--

[7. (COFO) CONTACT INFORMATION]

    If you need to get in contact with me, you can find me here:
  - ROMHacking.net: https://www.romhacking.net/community/3879/
  -         Tumblr: https://jolikmc.tumblr.com
      Other places: Check Tumblr!

    Just remember: be courteous, be kind, and most of all, be cool~
--

[8. (CORI) LEGAL STUFF]

    Tim, "Soul Blazer", "Illusion of Gaia", and related ideas and concepts
created by Tomoyoshi Miyazaki of Quintet and © Enix Corporation.

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
