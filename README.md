![EBGui Logo](https://user-images.githubusercontent.com/38049304/185819538-c7dadb62-c88a-40f0-9ee9-3772b3c4d845.png)

# Welcome to EBGUI.

![Milestone 2](https://github.com/EarthToAccess/EBGui/blob/main/images/milestone-version-3.svg)
[![Earth's Roblox Profile](https://github.com/EarthToAccess/EBGui/blob/main/images/my-profile.svg)](https://www.roblox.com/users/32573334/profile)
[![Contact Us](https://github.com/EarthToAccess/EBGui/blob/main/images/contact-us.svg)](mailto:ebgui.staff@gmail.com)
[![EBGui Discord](https://github.com/EarthToAccess/EBGui/blob/main/images/our-discord.svg)](https://discord.gg/z3QZzFJBvj)

---

# Notice

### EBGui is no longer being maintained.

EBGui will no longer get updates, and keys will not be changed. For updated features, a streamlined interface, and better performance, please use [its successor, Eos, instead.](https://github.com/EarthToAccess/Eos)

---

EBGui is a quick and easy user interface for those with the means to enhance their gameplay in Gamer Robot's Elemental Battlegrounds on Roblox. Included in EBGui is a random shard color creator, visual changes, and better utility options!

---

## Disclaimer

**EarthToAccess does not take any responsibility for any consequences of improperly using EBGui and/or its features.** Using any user interface such as this in unintended or malicious manners may get your account banned from Elemental Battlegrounds or Roblox. 

## Terms and Conditions

You can view the Terms and Conditions for using this script [at this link.](https://docs.google.com/document/d/15qLJqaVDGmreg5xAgqxvFeVPghS-YcuUUu355M5BJkM/edit?usp=sharing) Please note that, in using the script, you will be bound by these terms.

## Loading

To use EBGui, you're going to need an executor, such as [Synapse](x.synapse.to), which is paid, or [Krnl](https://krnl.vip/), which is free. Once you have that;

- Ensure your executor is properly attached to your game.
- Copy this script into the executor's script window;

  ```lua
  _L = "key_string_here"
  loadstring(game:HttpGet('https://raw.githubusercontent.com/EarthToAccess/EBGui/main/EBGui.lua'))()
  ```

  "`key_string_here`" will be a specific string that is required to load the script properly. You can obtain the key by going to the Discord link located in the badges above!

  After obtaining the proper key and executing this script, you should be good to go! EBGui will load to the right side of your game.

## Features

Features of EBGui include, but absolutely are not limited to;

- Long-range attacks
- Instant Ultimates
- Enhanced ESP
- Infinite Stamina

This list is not comprehensive; there is so much more in store for you to find!

## EBGui Gold

EBGui Gold is our premium membership-based bonus features service that gets you even *more* than what EBGui provides at its base! Visit the Discord at the link above to find more information about what Gold offers and how to Go Gold!

## Contributions

If you have any contributions, fixes, or additions you wish to include in EBGui, you can visit the appropriate channel in the EBGui Discord to submit them! Alternatively, you may also contact me using the email in the "Contact Me" badge above. We can discuss the details as needed there.

## Changelog

<sup>Entries in this changelog are denoted by using asterisks (*) for changes, pluses (+) for additions, and dashes (-) for removals.</sup>

### Latest - v3.2.1

- [`*`] Fixed an issue with key registration in which the variable wasn't being registered properly.
- [`+`] Promotional keys will now provide a loading splash in your console (F9) informing you of the date and time of expiry.
- [`+`] Promotional keys will now also be named in the UI itself, next to your username (e.g. "Name | EBGui Promo | Stable"; see [the Docs](/Docs.md) for more information).

### Previous

#### v3.2

- [`*`] Changed the loadstring a bit! A better system is a happy system.
- [`*`] Changed how keys work. Instead of a specified variable, you just need to use the one `_G` variable.
- [`*`] The `;refresh` command has now had its functionality extended to the keybind "P".
  - Hopefully, this will allow for even quicker refreshes than requiring to type a full command; in the future, the `;refresh` may even be removed in favor of the keybind.
- [`+`] Added `kos` as an option for `;targetsetting`, which takes two arguments; `file` or `link`, and a source list. Choose a source type, the source list location, and EBGui will now target the person topmost on the list who's also in your server.
  - For example, `;targetsetting kos file kos.txt` will pull names or User IDs from a file in your executor's Workspace folder named "kos.txt". For more information on what EBGui expects, visit the repository for the module script made specifically for this feature in mind, [PFL.](https://github.com/EarthToAccess/PFL)
- [`+`] Added `click` as an option for `;targetsetting`, taking no arguments. `click` will let you click on your target to select them, and set it accordingly. It'll reset your target setting back to `select` after you've clicked on someone.
  - It should be noted that, due to how Elemental Battlegrounds is coded, using the `click` target setting will cause your aim to act as if you were shooting in the air. This is not an intended feature and is being worked on, but can be circumvented by jumping/flipping after you've set it.
    - ...though, for the most part, if you're using the `click` target setting, you're probably not doing much aiming, are you?
- [`+`] From now on, EBGui's birthday will be met with fanfare and *Golden* confetti! That's right; every year for the entire day of August 21st, everyone will get free Gold to use for the day.

#### v3.1.2

- [`*`] Fixed a serious key handling problem that nearly brought EBGui to its proverbial knees.  
- [`*`] Promo key for above.  
- [`*`] Shutdown cleanup now properly checks that certain things exist before trying to destroy them.

#### v3.1.1

- [`*`] Fixed a problem with Standard ESP that caused it to incorrectly appear even while disabled.  
- [`*`] Fixed lag caused by Standard and Detailed ESP's respective holders and information not being properly cleared.  
- [`*`] Anti-AFK has been optimized, and the counter has been returned.  

#### v3.1

- [`*`] Changed a few internal names to improve performance.  
- [`*`] Made Anti-AFK stop spamming you.  
- [`-`] You can no longer `;teleport` to the Tournament or Mega maps.  
  - Teleporting to these maps have been patched since Solar's update, and attempting to do so at all results in an instant kick.  
- [`*`] You no longer need to remember cryptic names for `;teleport`. Now, you can simply type in their names normally (with or without capitals) and it will work fine! For example, `;teleport Standard Low` will teleport you properly to the under-40 Standard.  
- [`+`] Re-added the `;refresh` command. Now, `;refresh` will instantly reset and refresh your character! Keep in mind due to how this works, it can't be used to evade death.  
  - Also has an alias, `;re`.  
- [`*`] `;rejoin` now has an alias `;rj`.  
- [`*`] Anti-lag will now properly stop lag.  
- [`+`] Promo key capabilities have been properly added.  
- [`*`] Infinite Sprint now works properly.  
- [`*`] The text for the auto-disabling of conflicting moves will now tell you the spell type it disabled (e.g. "Disabled Fire AoE" vs. "Disabled Fire").  
- [`*`] Fixed an issue with Space-Time Rupture where it wouldn't properly disable.  

#### v3.0.1

- [`*`] Changed the keybind to focus the Command Box, as a recent Roblox update caused the previous one (backslash) to not work.

#### v3.0

- [`*`] Enabling a hack with conflicting spell types (e.g. Blaze Column and Murky Missiles, as AoEs) will now automatically disable the previously enabled move.  
- [`*`] Random Shard Colors will now only change the shard once rather than constantly.  
- [`*`] Renamed `;e` to `;echoes`.  
- [`+`] `;echoes` now has two arguments; `phase` and `auto`. `phase` will accept "POW", "BRN", "STN", or a number 1 through 3, and acts identical to how `;e` used to. `auto` accepts "t" or "on" and "f" or "off", or alternatively takes no other arguments. The former will turn auto-targeting on or off, while the latter simply toggles its current state.  
- [`*`] Orbital Strike Hack now fires 500 studs above the target, sending them flying into the air.  
- [`*`] Light Orbs Hack now fires 5 studs below the target, making them guaranteed to hit while on solid ground (which they should be if you're trying to hit them anyway).  
- [`*`] Fixed a problem with Hyperrang Hack not properly "turning off" when disabling it.    
- [`+`] Added 33 more loading quotes.  
- [`+`] Added 16 more crash quotes.  
- [`*`] Certain dates will now add a blurb above the EBGui loading art.  
- [`-`] Removed "GUI successfully loaded!" output in console, as the crash handler took its function as debugger.  
- [`*`] Changed the font... again.
- [`*`] Changed the colors to clash less.  
- [`+`] Re-added `;desp` (now with 100% more functionality).  
- [`+`] Added `;antiafk`, an anti-AFK functionality that should've been added eons ago. Also includes a counter of how many times it's saved you from disconnection.  
- [`+`] Re-added Gold feature coloring. Features which require EBGui Gold will now be gold in color.  
- [`-`] Removed "(G)" prefix from in front of Gold hacks.

#### v2.13

- [`*`] Standard and Detailed ESPs will now properly disable and go away when quitting EBGui.  
- [`+`] Added "Explode at Mouse". While enabled, you can press C to spawn a Lightning Bolt explosion at the feet of your foes or instantly smack someone ulting, even from across the map!  
- [`+`] Added "Space-Time Rupture Hack". Open up the wrath of a Time Lord by placing multiple explosions at your enemy's location.  
- [`*`] Fixed Solar Stick Bug's name becoming "Solar Freeze" after you've clicked the button.

#### v2.12

- [`*`] Anti-Lag will now properly remove Light Disk continuously, as it should've initially.  
- [`+`] Added 20 new randomized quotes that show up on launch!  
- [`*`] Changed "Double Ray Hack" to be "Instant Double Ray" to match with the standard of the "Instant" versus "Hack" naming conventions.  
- [`+`] Added "Remove Ult Cooldown". You can now remove your ult cooldown that's imposed on reset/refresh.  
- [`+`] Added Solar Stick Bug. Fire it to stick your opponents in place!  
- [`*`] Alt Farm will now teleport you to one of three potential locations while enabled, keeping teleport checks at bay and allowing you a specific place each time it's enabled to go to. The location will change if you en- and re-enable it.  
- [`*`] The Docs now have flavor text for the buttons cuz I was bored.  
- [`*`] Changed "Target RQed" to "Target left" when your target leaves the game.  

#### v2.11 

<sup>The biggest EBGui update EVER.</sup>
- [`+`] Added a crash handler that will provide a crash log and error message in the console if something goes wrong.  
- [`*`] Fixed a problem with Spectral Embodiment's keybind where it wouldn't fire.  
- [`*`] You no longer need both a Gold Key and a standard Key in your script to load EBGui if you have Gold; you'll now just need the Gold Key.  
- [`*`] `;help` will now copy the link directing you to the [Documentation](/Docs.md).  
- [`*`] `;changelog` will now copy the link directing you here, to the changelog.  
- [`*`] Fixed some text scaling with the Main Menu.  
- [`-`] Temporarily removed the drop teleport buttons, as teleporting to drops currently is unreliable.  
- [`*`] Changed the font of EBGui to a rounder, less-angular font. 

#### v2.10

- [`*`] Fixed the problem with Detailed ESP was off-center from the player it was attached to.  
- [`*`] Detailed ESP now has funky colors!  
- [`*`] Potentially fixed an issue regarding the ESP lag. 

#### v2.8.2

- [`*`] Fixed an issue with Instant Chain Hack where it would take mana but not fire.

#### v2.8

- [`*`] Fixed a problem with Infinite Sprint where dying would require to you toggle it off and back on.  
- [`*`] Fixed a problem regarding Detailed ESP where using it for an extended period of time would cause lag.

#### v2.7.2

- [`*`] Fixed an issue where Detailed ESP wouldn't update properly if a player died or joined after it was enabled.

#### v2.7.1

- [`*`] Fixed an issue regarding the recent Detailed ESP update where a misnamed function caused both ESPs to function erratically and irregularly.

#### v2.7

- [`+`] Added "Detailed ESP" as a Gold feature. The Detailed ESP will provide not just location and health akin to the standard ESP, but will also show users' Mana and Stamina.  
  - Keep in mind, unfortunately, that due to the nature of how the two are stored, there is no way to tell when it increases until another one of the two values update. This means if someone sprints for a split second and stops, their Stamina won't rise again until they either sprint, flip, get punched, or use a move.  
- [`+`] Added "Infinite Stamina" as a Gold feature. Enable this, and sprinting will no longer cost you any Stamina! Say goodbye to the days of using Speedhack and potentially making it obvious, this one relies entirely on your sprinting status and is virtually undetectable by others!  
- [`*`] Fixed an issue where ESPs sometimes refused to update themselves back to normal if something got caught. It should now properly reset itself.  

#### v2.6

- [`+`] Added `;info <info>` command. The two arguments you can provide are "status" and "github", the former providing the working status as shown in the Discord, and the latter providing the link to the very repo you're looking at.  
- [`+`] Added `;update` command. If your version is current, it will tell you no update is needed. If it isn't, it will tell you you're outdated and give the current version number.  
  - There is no progress on the `;farm` command, and it's been disabled until a fix can be found. Currently, it appears that Genesis Ray just refuses to fire at the anchor in question and opts to go way past it or deflect away from it. While the cause is unknown, we're looking into it!  

#### v2.5

- [`+`] (v2.5) Added command `;farm`. `;farm` will create a small, blue orb way up in the sky that makes creating Genesis Ray setups significantly easier, without the hassle of needing multiple accounts up acting as anchors.  
- [`*`] ~~(Update v2.5.1) Fixed issue with above in which the command send you so high up Genesis Ray stopped working.~~ This issue is still ongoing and will be updated as soon as possible.

#### v2.4.1

- [`*`] Fixed an issue where, after a target leaves, some keybinds wouldn't work because they left. It should now properly recalibrate to yourself.  

#### v2.4

- [`*`] Moved some stuff around to be more organized. All the bullets in one place, all the AoEs in another.  
- [`*`] Fixed an issue where spacing of the Gold buttons caused options at the bottom of the UI to be cut off (namely, Loop TP to Target, ESP, and Teleport to Drops).  
- [`*`] Removed the button coloring and instead opted for a simple "(G)" indicator for Gold hacks.  
  - The Gold coloring will return soon, but currently all implementations have failed and caused issues.  
- [`+`] Added Creation's Continuous Strikes as a Gold hack.  
- [`+`] Added Reaper's Ult (Reaper's Rage) as a Gold hack. 

#### v2.3

- [`+`] Added a welcome message for Master List users.  
  - Considering the very small number of people who will have Master List access, this may seem redundant, but it's neat so who cares.  
- [`*`] Fixed an issue with Instant Crystal Armament where its text's starting value read "On".  
- [`*`] Did some performance cleanup involving the constant indexing of something that was already declared.  
- [`-`] Completely removed "ebguicast" as it was useless.  
  - While the idea of having a cheeky branding option in-game was fun to start, technical limitations and the overall brand change of EBGui just didn't line up.  
- [`*`] Made the "terminate UI" text below the main window less ambiguous.  
- [`+`] Added a functionality where EBGui Gold members would have "EBGui Gold" instead of "EBGui" in the text above the buttons.  
- [`+`] Running `;heal` will now also use Angelic Aura if you use it on yourself.

#### v2.2

- [`+`] Added EBGui Gold  
  - This new premium version of EBGui is intended to give thanks to members who support the project financially by providing them with a selection of hacks that were deemed "too powerful" for standard users to use!  
- [`*`] Made Orbital Strike a Gold hack.  
- [`*`] Made Slime Buddies a Gold hack.  
- [`*`] Made Double Ray a Gold hack.  
- [`*`] Made Instant Dispersion a Gold hack.  

#### v2.1

- [`+`] Added Storm's Lightning Dispersion.  
  - This fires instantly, and will still fire even when in the air.  
- [`+`] Added Darkness' Murky Missiles.  
  - Like most AoEs of its kind, you need to be near the target for it to work.  
- [`+`] Added Technology's Hyperangs.  
- [`+`] Added Slime's Slime Buddies.  
- [`*`] Changed "Crystal Armament Hack" to "Instant Crystal Armament".  
  - The original intention of the move was patched beyond repair, but the current implementation still allowed for instant use of the move without warning, so it was kept.  
- [`+`] Added Technology's Orbital Strike.  
- [`-`] Removed "Amplified Luminous Dispersion."  
  - This was patched well beyond repair eons ago, and simply was never removed.  
- [`-`] Removed "Enable Sans Immunity" and "Teleport to Sans".  
  - The original intention of the above was for sansing to be made more consistent and easy, but with the addition of the teleport confirmation both of most executors and in-game, it was made impossible to do so; thus, the decision to remove the two options was made.

#### v2.0

- [`+`] Added Solar's Double Ray.  
  - You need to be close by the opponent for it to fire, much like Instant Blaze, Vine Trap, and Skeleton Grab.  
- [`+`] Added Storm's Lightning Barrage.  
- [`+`] Added Spirit's Vigor Gyration.  
- [`+`] Added Space's Asteroid Belt.  
- [`-`] Removed Infinite Flame Body, Invisible Infinit Flame Body, and Hide Flames.  
- [`*`] Changed "Infinite Rock Armor" to "Instant Rock Armor".  
  - Most, if not all, body move scripts across the board for EBG have been patched, rendering the Flame Body scripts useless. Rock Armor almost went too, but it was found that it would let you use Rock Armor while moving, so it was just rebranded.  
- [`-`] Removed anything relating to CBring (client bringing).  
  - Loopbring-based scripts were patched beyond repair, and the implementation here was buggy even prior to that. It didn't make sense to beat the dead horse.  
- [`-`] Remove the "Rejoin Server" button.  
  - Using the command `;rejoin` will still work fine.  

#### v1.7.1

- [`+`] Added a blocklist to prevent specific user from accessing the script, key or not.  
- [`+`] Added a masterlist to allow specific users to access the script, key or not.  
- [`*`] Fixed the "welcome" art on successful load to be more in-line.  
- [`*`] Changed the overall style of the UI, including animations.  

#### v1.7

- [`+`] A key is now required to load the script properly. Keys can be found in the Discord.  
- [`+`] Changed how the loading text appears in the developer's console. Now it has fun ASCII text art!  
      - You'll be notified if your key is incorrect/nonexistent in a similar fashion.  

#### v1.6.6

- [`*`] The top status bar will now show the current user's name rather than "Earth".  
- [`-`] Removed "ebguicast" as it was causing medals to simply stop appearing entirely.  

#### v1.6.5

- [`*`] Changed the text command from "e" to "echoes" to prevent interference with other commands.  
  - Note to self, the letter E really causes a LOT of issues.  
- [`+`] Added command "ebguicast", which will change every emblem to the EBGui logo.  

#### v1.6.4

- [`*`] Fixed an issue where "magiccolor" changed the color of Shards and Diamonds.  
  - An issue where the color of Crystal spells also changes exists. The cause is known, but unable to be changed due to how the game handles the moves themselves.

#### v1.6.3

- [`*`] Fixed an issue where "magiccolor" would change the color of players on the server.  
- [`*`] Changed the keybind of Longflash from "E" to backtick.
