Final Fantasy V Clean Editions
June 2025, v1.97
----
- Berserkers improved by RoSoDude: ATB gauge behaves like other Jobs
- Dancers use Sword Dance more often as they equip more Dancer armor
- Remedy !Mix recipe (Antidote + Eyedrops) removes Petrification
- "Kiss of Blessing" bugfix finally works XD
----
Hello, the Clean Editions offer interface, gameplay, and graphic improvements to FFV without changing the original game concepts too much. This project is the result of many talented hackers!

Apply any of the "FFV Clean" patches to an *unheadered* copy of FFVJ.sfc-- the checksum & CRC data are these:

File/ROM CRC32: C1BC267D

(Use https://www.romhacking.net/hash/ to check this value, and use the Tush utility available on rhdn if you need to remove the header.)

VARIANTS

Very Clean & Hella Clean are two variants that add extra accessibility to the game. Hella is the more extreme, it makes Stealing more effective and gives extra weapon equips to most Jobs; they both make previously weak weapons more powerful.

----

Control, Menu, Etc Improvements:

+ use Menu button to pass turn in battle

+ Dash in towns and dungeons with all jobs (Thief/Dash is faster)

+ L & R buttons page scroll Item and Magic Menus

+ Blue Magic has its own icon (Diamond)

+ Many icons improved (some courtesy of tsushiy)

+ Espers have Black/White/Time icons by effect type

+ Many Ability, item and enemy names match their appearance in FFV Advance, or elsewhere in the FF series

+ All Jobs and Abilities have descriptions

+ The 12 items that work with !Mix command are more obvious

+ Equipment Weight works the same as in Pixel Remaster edition (it's 4x more impactful in reducing Agility now)

+ FFV: MSU-1 chip support added for enhanced soundtracks (not included, so DYOR)

----
1. Clean Battle Improvements:

+ Berserk doesn't merely Attack: can work with Jump, Mug, SwdSlap, Dance, Aim, RapidFire

+ Berserk heroes display their Active Time Battle gauge accurately, and act like expected-- no lag on battle start, no instant turn when revived

+ Check works as described, showing elemental weakness

+ SwdSlap hits like a normal Attack and may stun the target; it doesn't remove Sleep, Confuse, or Control

+ "Surge" Time spell replaces pointless "Drag"; free to cast and restores 12 MP

+ Images can stack up to 3 (still 2 per spell cast or !Image)


2. Very Clean Battle Improvements, the above plus...

+ Harps, Bells, Rods, Whips, Knives, Spears all do more damage

+ Axes, Katana, Hammers, even some Knives work with MagicSword

+ Spears and some other new options work with Double Grip; Dbl.Grip combos with Jump for additional damage


3. Hella Clean Battle Improvements, the above plus...

+ Stealing is significantly more effective

+ All Jobs except Monk & Mime gain at least one more weapon they can wield

See details here:
https://www.notion.so/xj4cks/Even-Better-Job-Equipment-patch-2f7aef57fe0a4ff4afbf28dae0a32f65

Very & Hella Clean are intended to provide less restrictive versions of the game. They are made possible thanks to Modoh's "Weapon Formula Tweaks" overhaul, Gen's "Steal Buff" work, and RoSoDude's adaptation of the SwdSlap code.

----
Bugfixes:
Kiss of Blessings, PowerDrink, HP Drain limit, and many other bugs were properly addressed by the FFV hacking community. Please read the changelog to see them all, and for many other details of the Clean Editions.

----
For a full list of the UX/UI, Item/Magic, Job System & Text adjustments, please consult the included readme file.

For hotfixes and more info, please visit: https://tinyurl.com/ff5-clean

With opensource content & utilities from:

* http://x11.s11.xrea.com/ff5patches

* https://github.com/cubear/FFV-DressCode/releases

* https://www.romhacking.net/hacks/6885/

* https://www.romhacking.net/hacks/7573/

* https://www.romhacking.net/hacks/4537/

* https://www.romhacking.net/hacks/3219/

* https://www.romhacking.net/hacks/1408/

* https://www.romhacking.net/hacks/6818/

* https://www.romhacking.net/hacks/3216/

* https://www.romhacking.net/hacks/3687/

* https://everything8215.github.io/ff6tools/ff6tools.html

* https://www.ff6hacking.com/ff5wiki/index.php/Main_Page


Thanks to everything8215, noisecross, Inu, RoSoDude, Modoh, Gens, Cubear, Tzepish, Leet Sketcher, Chicken Knife, Nintenja, clymax, BladePotato, tsushiy, Squall, Samurai Goroh, madsiur, hakumen99, Guysons, Mareel, m340857, Serity, KimbleeCA, J121, KainStryder, Steela Light, Kandowontu, mantecol de mierda, & ScarabEnigma for any of these: patches, tools, guides, playtesting, translation, feedback, good vibes!

Thank you to RPGe team for inspiring this community and delivering an epochal work, 27 years ago!
Thanks to Squaresoft for Final Fantasy V!

----
CHANGLELOG & DETAILED CONTENTS

Main patches:
* FFV Clean v197.ips
* FFV Very Clean v197.ips
* FFV Hella Clean v197.ips

Optional patches:
* FFV Clean classic menu font.ips
* FFV Clean classic speech font.ips
* FFV Clean GBA Dark menu font.ips
* FFV - Accessible Lix, by xJ4cks.ips

----
KNOWN WEIRDNESS
o Thief and Ninja can equip Boomerang but it's not shown in Equip/Status/Job menus
o Mage Hat, Medium Armor (Suit), and Hat not shown in Status/Job menus 
o if a Zombified character Jumps, game will soft lock
o Sort keeps the top 4 rows of the Item menu however you wish

----
DEVELOPMENT PLAN, see more at 
https://www.notion.so/xj4cks/FFV-Clean-Editions-bfe70f9215bd4cc881fc803ae684359e

(~v2.0)
_ Upgrade DressCode to v2 (16 colors, Job battle palette)
_ Add new colors for MP gain/loss (like in FFVI, cyan and dark red)
_ Maybe get new armor & weapon icons to show as equips??
_ Apply any compatible bugfixes that still aren't included
_ Bugfix Zombie Jump?

Eventually...
_ Enhance FFV romhacking ecosystem by providing RPGe compatible patches of changes made to names, icons, fonts

Please reach out to  < alex@j4cks.com > or find me in the 
FF4Ultima Discord < https://discord.gg/PGMASbSnD9 >
if you need help patching or have glitches or typos to report!

----
CHANGELOG NOTES

They are long, and it's best to have them in a single place that's easy to update. Hence, now maintained at:
https://www.notion.so/xj4cks/FFV-Clean-Changelog-21a6bad314298043a826e21e4b5fad6c