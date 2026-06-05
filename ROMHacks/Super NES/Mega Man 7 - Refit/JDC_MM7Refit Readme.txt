Mega Man 7 Refit
A Mega Man 7 US ROM hack
by DarkSamus993 and Josephine Lithius (Jo Li)
--

[1. (INDE) INDEX]

 1. (INDE) Index ------------------------ Do not pass go; do not collect $200!
 2. (INDU) Introduction & Questions ----------------------- All of the basics.
 3. (COTE) Archive Contents ------------------------------- What's in the ZIP?
 4. (HOTO) How to Use ------------------------------ How to make the thing go.
 5. (NOBU) Known Bugs -------------------------------- Icky-sticky bug-a-boos.
 6. (SPTH) Special Thanks --------------------------------- Heroes of the Day.
 7. (COFO) Contact Information ----------------------------------------- MEEP!
 8. (CORI) Legal Stuff ------------------------ Copyrights can never be wrong~
--

[2. (INDU) INTRODUCTION & QUESTIONS]

- "What is Mega Man 7 Refit?"

  "Refit" is a hack that makes a few modifications to how core mechanics of
  the game work, as well as a few minor graphic alterations.

- "What sort of modifications are we talking about?"

  I always found it really annoying that in Mega Man 7, the Mega Buster's
  Charge Shot was nigh-useless, not only because it did so little damage, but
  because it took AGES to charge. (Seriously!  Only Rockman & Forte has a
  longer charge time... and you can FIX that with a shop item!)  I also found
  it really frustrating that the after-damage invulnerability in this game was
  so ridiculously short compared to other games. (It has the SMALLEST amount
  of "I-frames" in all the series.)  And so... I decided to finally do
  something about it.

- "Can you be more specific?"

  I made the Mega Buster charge-up time and Megaman's I-frame length match the
  ones from Mega Man 5.  I also did a little tinkering to the boss damage data
  so that the Buster is a little more effective -- but only where it made
  sense (meaning heavily/armored bosses still only take 2 damage from a
  fully-charged shot).
  As for the graphics?  Well... the most obvious change is the game font, which
  now looks like the NES game fonts... but I also removed the "sparkle" that
  Megaman gets when he charges a shot.  Oh!  And I added the hack's title
  ("refit") to the title screen and weapon get screen.

- "Will you be making a version of this for Rockman 7 as well?"

  As soon as I can figure out a way to edit the graphics of that game.  Seems
  the tool I have doesn't work with the Japanese ROM...
 (Of course, nothing's really stopping me from trying to do it MANUALLY...
  Aside from laziness, I mean.)

- "Will you consider making separate patches for the various changes?
   (For example, a 'Megaman-only' patch or a 'boss damage update-only' patch?)"

  Already done!  Check the "Individual Patches.zip" file for the patches and
  specific documentation about said patches!

- "Will you consider making separate patches for the various changes... for
   the European and Japanese versions of the game?

  I... might.  I mean, I know what to look for, so it wouldn't be TOO hard...
  The only problem would be relocating the boss weaknesses in the JP/EU ROM.
  THAT... I don't exactly know how to do, myself.
--

[3. (COTE) ARCHIVE CONTENTS]

  - [Patches Folder]
    - [Individual Patches Folder]
        Patches for specific changes!
       (Check the documentation for more info.)
    - JDC_MM7Refit-vxxx Complete (H).bps
    - JDC_MM7Refit-vxxx Complete (NH).bps
        The most current version of the complete patches.
         (H) = For use with ROMs with a HEADER!
        (NH) = For use with ROMs with NO HEADER!
  - JDC_MM7Refit Changelog.txt
      What's new?  What's OLD?  Find out here!
  - JDC_MM7Refit Readme.txt
      Hi.

DO NOTE: THE CHANGE LOGS CONTAIN SPOILERS AND MAKE NO ATTEMPTS TO HIDE THEM!
         Most changes probably won't be real game-breakers, so you can probably
         ignore the text files, if you want to play the game and try to figure
         out what's brand new content and what's just rehashed stuff.
--

[4. (HOTO) HOW TO USE]

  Things You'll Need
  - The BPS file that SHOULD have come with this TXT file
  - A Mega Man 7 (U) ROM (which I will NOT provide)
  - A program to apply IPS files to ROMs
  - A Super NES emulator to play the game

  Suggested Programs
  - PATCHING: Floating IPS (http://www.romhacking.net/utilities/1040/) or
              beat (http://www.romhacking.net/utilities/893/)
    Floating IPS is easy to use and very reliable.  You can use the unheadered
    patch on both a HEADERED or an UNHEADERED ROM with Floating IPS.
    With beat, however, if the PATCH is for one kind of ROM, you can only
    use that patch with that specific kind of ROM.
  - EMULATION: SNES9X (http://www.snes9x.com/) or
               ZSNES (http://www.zsnes.com/)
    Both are fairly lightweight emulators.  Just be warned.  SNES9X likes to
    associate file types to itself and ZSNES' sound engine is a little off.

  How to Apply the patches to the ROM, The Simple Way
  - Toss your UNMODIFIED ROM and the ISP patches from this archive into
    into the same directory as your patching utility of choice.
  - Open your patching utility.  Direct it to the ROM and patch.
    IMPORTANT: If using beat, PLEASE USE THE RIGHT PATCH WITH THE RIGHT ROM.
               The patch will fail to be applied, otherwise.
  - Do the command that makes the ROM patched. (Varies by-program.)
  - If everything went well, your Mega Man 7 ROM should be patched.
    NO CHANGE IN SIZE SHOULD OCCUR.  If it does, something may have gone wrong.
  - Enjoy!

  IF ROM DOES NOT RUN, you more than likely tried to apply the wrong patch to
  the wrong ROM or wrong type of ROM.
--

[5. (NOBU) KNOWN BUGS]

_v1.0.6 ONWARD_
- RUSH STILL BLOCKS PROJECTILES DESPITE NOT TAKING DAMAGE
  This is ultimately pretty minor, but there are some rare circumstances where
  riding Rush Jet will make Megaman invincible to enemies attacking his feet.
 (Try gliding through the timed flame section in Turboman's stage!)
  I might look into fixing it, but like I said... it's pretty negligible.

_v1.0.5_
- PROTOSHIELD NO LONGER MAKES ANY NOISE, BUT STILL BLOCKS SHOTS
  **FIXED IN v1.0.6**
  The way they did Rush's collision code is kind of odd...
  If you disable his collision code outright, it also keeps the Protoshield
  from doing its job.  However, if you disable the "injury" flag that gets set
  upon Rush bumping into an enemy (at least the way I did it), it causes the
  Protoshield to NOT PLAY A NOISE when it blocks something.
  That being said, the Protoshield STILL WORKS PERFECTLY FINE.
  It just doesn't make that "DONG" sound anymore.

_ALL VERSIONS_
- This ROM hack is ABSOLUTELY NOT COMPATABLE with most other ROM hacks.
  However, individual patches can be added to most US ROM hacks which add the
  benefits of this hack into those.
--

[6. (SPTH) SPECIAL THANKS]

  - ROMhacking.net
    For an having an awesome community and a treasure trove of hacking
    materials, resources, help, and pretty much anything you could want!

  - DarkSamus993 -- http://www.romhacking.net/community/4006/
    For being the beautiful and generous person who provided me with ALL the
    information I needed to make this hack quick-and-painless!  Seriously, this
    REALLY saved me a lot of time!

  - Christian Maas -- http://www.chmaas.handshake.de/
    For making a dang good hex editor.
    Check out XVI32 if you're in the market for an easy-to-use hex editor!

  - YY -- http://www.geocities.jp/yy_6502/
    They made an extremely easy, feature-rich tile editing program which makes
    editing graphics in ROMs a breeze!  It's what I use all the time.

  - Denim -- http://www.romhacking.net/community/2943/
    His Mega Man 7 De/Compression Tools were extremely useful for editing the
    graphics of the game as painlessly as possible.  Check it out!

  - Anonymous D
    Someone who wishes to remain anonymous, but whose advice was invaluable
    all-the-same!

  - Bohepans the Third -- http://www.youtube.com/user/BohepansTheThird
    Caught a typo that I missed from the US script. (Auto really doesn't
    like telling you what things ACTUALLY do, does he?)
    Also convinced me to make a less terrible logo for Refit.  It really did
    need it, looking back...

  - darthvaderx -- http://www.romhacking.net/community/5437/
    Honestly, if darthvaderx hadn't messaged me about some incompatibilities
    between my hack and other hacks (like the MSU-1 one and Restoration), I
    probably wouldn't have gotten my butt in gear and released a new update,
    and I DEFINITELY wouldn't have added the individual patches.  So, thank
    darthvaderx for that one!  I know I sure did~!
--

[7. (COFO) CONTACT INFORMATION]

    Since I'm the ringleader of this operation, I'd highly suggest contacting
me, Josephine Lithius, if you have any questions.  If it's something more
TECHNICAL, though, such as where the boss weakness data was moved or how
certain values were found, you might be better off asking DarkSamus993.
    We're both on the ROMhacking.net forums (http://www.romhacking.net/forum/)
under the usernames of, uh, "Josephine Lithius" and "DarkSamus993".

Additional contact info for Jo Li:
- Twitter: https://twitter.com/JoLiKMC
-  Tumblr: https://jolikmc.tumblr.com/
- YouTube: https://www.youtube.com/user/JosephCollins
--

[8. (CORI) LEGAL STUFF]

    "Mega Man 7", "Rockman 7", Mega Man, Rockman, and related characters and
concepts created by Akira Kitamura and Keiji Inafune, and © Capcom Co, Ltd.

    This ROM hack was created by DarkSamus993 and Josephine Lithius and is
distributed as a "Public Domain" work which MAY BE SHARED AND DISTRIBUTED
FREELY so long as the contents -- including copyrights and contact
information -- are NOT MODIFIED.  I mean, it's not like we'll KNOW or
anything, but c'mon.  Be nice, huh?
  
    Use of the mini-patches in your own ROM hacks IS ALLOWED under a public-
domain-equivalent license, so go nuts.  If you RELEASE you ROM hack with OUR
modification, though, ot would be a REALLY nice gesture if credited the two of
us -- DarkSamus993 and Josephine Lithius -- for research and programming.  I
mean... why WOULDN'T you credit us?  We're AWESOME, right~?
