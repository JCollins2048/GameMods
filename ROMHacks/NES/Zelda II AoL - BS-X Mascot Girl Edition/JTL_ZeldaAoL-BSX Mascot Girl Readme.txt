"Zelda II - BS-X Mascot Girl Edition"
  A Zelda II: The Adventure of Link ROM hack by Josephine Lithius

[1. (INDE) INDEX]
 1. (INDE) Index -------------------------------- AKA, what's in this document.
 2. (INDU) Introduction & Questions --------------------------- Why you do dis?
 3. (COTE) Archive Contents --------------------- The stuff DREAMS are made of!
 4. (HOTO) How to Use ------------------ If you have to ask, you'll NEVER know!
 5. (NOBU) Known Bugs ------------------------------------------ No, not Boons.
 6. (SPTH) Special Thanks ---------------------- Cool people who inspired this.
 7. (COFO) Contact Information -------- Huh?  What?  I wasn't paying attention.

[2. (INDU) INTRODUCTION & QUESTIONS]
- "What is 'The Adventure of BS-X Girl?'"
  It's Zelda II!  But, with a completely different - yet, functionally-
  identical - character, "BS-X Mascot Girl!"  Yes, really.

- "Who is the 'BS-X Mascot Girl?'"
  In the 90s, Nintendo joined forces with a satellite entertainment company,
  "St. GIGA."  Together, they produced an add-on for the Super Famicom
  called the "Broadcast Satellaview," which had an interactive interface
  similar to role-playing games such as EarthBound/MOTHER.
  The interface, "The Town Whose Name Was Stolen," allowed players to log in
  and download all sorts of goodies, such as music, small videos, and of
  course... games!  But, more to the point, it also let players choose their
  avatars: a young boy with a baseball cap, or a small girl with red hair.
  These avatars were also used in some games, such as the two BS Zelda games,
  "BS The Legend of Zelda" and "BS Zelda: The Ancient Stone Tablets."

  (You can learn more about BS Zelda and how to play it on a replication cart
  emulator at the BS Zelda HomePage: https://bszelda.zeldalegends.net/)

- "So, this is just a 'skin swap' mod?  Nothing else?"
  Yup.  No enhanced abilities, no new music or maps.  Just a new character
  that plays exactly like the old one!

- "Why did you make this, anyway?"
  LONG STORY SHORT: I like playing games as girls.
  SHORT STORY LONG: I liked playing as the redheaded girl in The Ancient Stone
  Tablets.  I liked her so much, I added her (and "Boy") to the normal
  Link to the Past (https://www.romhacking.net/hacks/3402/) and when I decided
  to play The Legend of Zelda (NES), I also added her in there (unreleased).
  Now that I've decided to re-play Zelda II... I'm adding her here, as well.

- "So, what's new about the BS-X Girl?"
  Just some new sprites, is all.  Completely original ones!
  I'm quite proud of my work!

- "Did you change any part of the storyline?"
  Nah.  I mean, not really?  The storyline is the same, basically, except you
  play as a cute girl named Karen, instead!
  
- "'Karen?'"
  That's what I've been calling the BS-X Mascot Girl.  It just felt right.

- "You're a creative little oddball, aren't you?"
  Yosh~

- "Will you do a 'Mascot Boy' version of this?"
  If there's interest, maybe!  This was kinda fun to work on.

- "Why does 'Karen' look a little like Isabelle, from Animal Crossing?"
  You know... I didn't mean to do that.  But, with those green clothes
  and that blond hair (red wasn't REMOTELY an option)... she really does.

[3. (COTE) ARCHIVE CONTENTS]
  - [Patches]
    - JTL_ZeldaAoL_BSX Mascot Girl vxxx (FDS).bps
    - JTL_ZeldaAoL_BSX Mascot Girl vxxx (FDS, Just Link).bps
    - JTL_ZeldaAoL_BSX Mascot Girl vxxx (NES).bps
    - JTL_ZeldaAoL_BSX Mascot Girl vxxx (NES, Just Link).bps
        The most current version of the patches.
	NOTE: The "Just Link" patches ONLY change Link's sprites to BS-X Girl.
	      The title screen and story crawl stays the same as default.
  - JTL_ZeldaAoL_BSX Mascot Girl Changelog.txt
      What's new?  What's OLD?  Find out here!
  - JTL_ZeldaAoL_BSX Mascot Girl Readme.txt
      This is the very document you are reading!

DO NOTE: THE CHANGE LOGS CONTAIN SPOILERS AND MAKE NO ATTEMPTS TO HIDE THEM!
         Most changes probably won't be real game-breakers, so you can probably
         ignore the text files if you want to play the game and try to figure
         out what's brand new content and what's just rehashed stuff.

[4. (HOTO) HOW TO USE]
  Things You'll Need
  - The patch file of choice that SHOULD have come with this TXT file
  - A Zelda II - The Adventure of Link US NES ROM and/or
    a CLEAN Link no Bouken - The Legend of Zelda 2 Japanese FDS Image
   (I will not provide EITHER, no matter how much you ask.  Sorry!)
  - A program to apply patch files to ROMs
  - An NES emulator or NES flash cart of your choice (to play the game)

  Suggested Programs
  - PATCHING: Floating LIPS (https://www.romhacking.net/utilities/1040/) or
              beat (https://www.romhacking.net/utilities/893/)
    Floating LIPS is easy to use and very reliable.
    beat is a little less user-friendly, but also works very well.
  - EMULATION: FCE Ultra X (https://www.fceux.com/),
               VirtuaNES (https://virtuanes.s1.xrea.com:8080/),
               Nestopia UE (https://0ldsk00l.ca/nestopia/)
    Nestopia and VirtuaNES are super-lightweight emulators which run most games
    pretty flawlessly.  FCE Ultra X, however, is pretty much the best emulator
    I've ever used and still doesn't require a hugely-powerful computer.

** EXTREMELY IMPORTANT **
  If using beat, PLEASE USE THE RIGHT PATCH WITH THE RIGHT ROM.  The patch may
  incorrectly be applied, otherwise.  Also note, if your ROM's modified date is
  different from the one I used (very likely!), or if you use a FDS image with
  save data on it (also pretty likely), beat may tell you the patching failed.
  You can ignore that.  The patch should work just fine,
  even with pre-existing saves.
  Also, if you want to use Floating LIPS to apply the FDS patch, you will NEED
  to use a COMPLETELY EMPTY, FACTORY DEFAULT image, otherwise FLIPS will tell
  you that the patch "isn't for that game."  Luckily, you can generate a clean
  image by doing the following:
    - Open the Zelda II FDS image in your emulator of choice
    - Create save games in ALL THREE SLOTS (if there isn't, already)
    - Immediately DELETE ALL THREE SLOTS
    - Close the game and the emulator
    - Go to your emulator's battery backup/save game folder
    - Grab the Zelda II .FDS file
    - Congratulations!  You've created a completely clean disk image!
  Complicated?  It sure is.  And, it's for this reason that I
  HIGHLY suggest using beat for the FDS version, for simplicity.

  How to Apply the patches to the ROM, The Simple Way
  - Toss your UNMODIFIED ROM and the BPS patches from this archive into
    into the same directory as your patching utility of choice.
  - Open your patching utility.  Direct it to the ROM and patch.
  - Do the command that makes the ROM patched. (Varies by program.)
  - If everything went well, your Zelda II ROM should be patched.
    NO CHANGE IN SIZE SHOULD OCCUR.  If it does, something may have gone wrong.
  - Enjoy!

  IF ROM DOES NOT RUN, you more than likely tried to apply the wrong patch to
  the wrong ROM or wrong type of ROM.  Check your files and try again!

[5. (NOBU) KNOWN BUGS]
_v1.0.0 ONWARD_
- None that I've been able to find.

_ROM HACK-SPECIFIC_
_v1.0.0 ONWARD_
  There may be some compatibility issues with applying certain other hacks on
  top of this one/applying this hack on top of others, but I haven't tested
  many of them, myself.  However, it SHOULD work just fine with just about any
  hack that DO NOT modify the graphics, already.
  And, yes, it works perfectly fine with the "Remove big flasheffect"
  AND "Restart from palace at game over" hacks.  I checked~

[6. (SPTH) SPECIAL THANKS]
  - Con -- https://www.romhacking.net/community/1110/
           https://bszelda.zeldalegends.net/
    For his work on the Satellaview titles and unofficial homepage.
    Without him, I never would have been able to play as BS-X Mascot Girl!

  - Romhacking.net -- https://www.romhacking.net (Duh...)
    For all the awesome people who are eager to help folks with just about any
    idea they may have for their ROM hacks!

  - Bongo' -- https://www.romhacking.net/utilities/291/
    Made a darn good hex editor with table functions and helpful stuff!
    It made editing the text a breeze and never once complained!

  - YY -- https://www.geocities.jp/yy_6502/
    They made the BEST graphic tile editor I have ever used.
    This gets my seal of approval!

  - Pembroke W. Korgi -- https://www.youtube.com/channel/UC-9Lpw879pCE5Bvt5xQBk8Q
    This li'l dude is the reason I decided to replay Zelda II... and,
    indirectly, the reason I even MADE this hack, so go thank him!

[7. (COFO) CONTACT INFORMATION]
  If you have any questions, comments, etc. you can hit me up at the
  ROMhacking.net forums (https://www.romhacking.net/forum/) under the username
  "Josephine Lithius".  I'll do my best to answer your inquiries!
  I'm still waiting on that pizza coupon from a fan, by the way...
 (Kidding, kidding.  But, if you WANT to...)

  Enjoy the ROM hack and remember: EYES OF GANON ARE EVERYWHERE.
  ~ J