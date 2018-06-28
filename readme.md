#### Pillars of Eternity 2
# Enhanced User Interface

[Changelog - v. 0.6.0](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/beta/changelog.md#changelog)

## What does this mod do?

This mod aims to improve the standard user interface by highlighting gameplay mechanics such as afflictions and inspirations, damage and defense keywords and much more. In total close to 900 ability, item or UI entries have been modified to enhance the user experience and to make some fairly opaque game mechanics a bit more transparent.

## Latest news:
### A big mod update (and a new game patch)!
**28th of June 2018**\
Obsidian Entertainment just released a beta version of the [1.2.0.0008](https://forums.obsidian.net/topic/103043-patch-120-updates-thread/) game build! There are a lot of cool new features that you should be really excited about, like the [modding documentation](https://eternity.obsidian.net/game-data-formats/concepts) or the fact that we now got a built-in mod manager!

Anyway, I squished a few bugs and added a few missing features to the mod which can be read below:
#### Mod version 0.6.0
**Abilities.stringtable**:
- Removed a duplicated `line-height` tag in ID 564 (abilities.stringtable).
- Added the "Penetrate" keyword to 32 new entries (abilities.stringtable).
- Added the keyword "Armor Rating" to 14 new entries (abilities.stringtable).
- Removed ID incorrectly applied text stylization to ID 607, 631, 643, 811, 1573, 1962, 1964, 1967, 1968, 2271, 2896, 2898, 2900 and 2902 (abilities.stringtable).
- Added missing keywords to ID's 614, 831, 925, 2039, 2663, 2732, 3923, 4092, 4166 and 4774 (abilities.stringtable).
- Might inspiration Energized should now have the correct color code (abilities.stringtable).
- Fixed broken links to glossary entry `Terrified` (abilities.stringtable).\
**Cyclopedia.stringtable**:
- Added missing `line-height` tag in ID `679 (cyclopedia.stringtable).
- Added support for the keywords `Armor Rating` and `Penetrate (cyclopedia.stringtable).\
**Gui.stringtable**:
- Added a lot of missing entries (gui.stringtable).\
**Items.stringtable**:
- Added a few missing font tags to multiple entries (items.stringtable).\
**Statuseffects.stringtable**:
- Added missing `line-height` tags (statuseffects.stringtable).
- Fixed a few incorrectly applied font stylizations (statuseffects.stringtable).

Mod patch notes can always be found [here](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/beta/changelog.md#changelog).

### Mod version 0.4 is released (and the mod changes name)
**19th of June 2018**\
To the great dismay of my fellow co-modders/translators, I am sure, I've just put the finishing touches to the latest version of this mod. The beta version will only be available in English for now but hopefully we'll see German and Italian language support coming shortly!

**New features in mod version 0.4:**\
* Better rank indicators for afflictions and inspirations (all afflictions should now have something similar to subscript numbers next to their icons).
* New cyclopedia entries and tooltips for all damage types (courtesy of the brilliant modder [kilay](https://forums.nexusmods.com/index.php?/user/26711484-kilay/).
* Added color to reputation gains in the chat window (colors are not final yet).
* Defensive stats (Will, Fortitude, Deflection and Reflex) now have a colorized icon:

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://i.imgur.com/JFoMw5O.png "Defense icons")

* Affliction and inspiration tooltips now have a more aesthetically pleasing
appearance mirroring some elements of the standard UI.
* Lots and lots of bug fixes.

**Regarding the name change:**\
Due to the fact that this mod has grown quite far beyond the initial scope of only colorizing afflictions and inspirations it felt quite natural to drop the **Affliction and Inspiration** name in favor of the already half-established **Enhanced User Interface** which I feel is a more accurate representation of what this mod aims to accomplish. I've found some [interesting information](http://digitalnativestudios.com/textmeshpro/docs/rich-text/) regarding styling of `.stringtable` files so expect some cool new features in the future!

/Spherikal

***

### German is in!  de_patch translation pack added!
**11th of June 2018**\
After much tweaking and rewriting of the German translation the icons are in. Starting with version 0.3.0 you can get the visible hint together with the German translation fix: [Corrected German translation](https://www.nexusmods.com/pillarsofeternity2/mods/5)

The dependency is necessary!

**Deutsch:**\
Nach langem anpassen der deutschen Übersetzung sind die Icons ab Version 0.3.0 auch in der korrigierten, deutschen Version enthalten.
Der Mod [Corrected german translation](https://www.nexusmods.com/pillarsofeternity2/mods/5) wird zwingend benötigt!

/Xaratas

***

### Over 200 new entries added to mod version 0.2.3
**11th of June 2018**\
This mod version is trying something a little bit different. I have added icons for defensive stats (Fortification, Toughness, Reflexes and Will), offensive weapon types (Slash, Pierce, Crush and Raw) and spell damage (Frost, Burning, Shock and Corrosive).

![alt text](https://i.imgur.com/p4XGP1G.png "Damage icons")

It is **strongly** advised that you use the latest game version (1.1.0.00035) when using this mod.

***

### Italian translation pack added!
**10th of June 2018**\
Thanks to [kilay](https://forums.nexusmods.com/index.php?/user/26711484-kilay/) we now have support for the Italian version of the game! Not only did he translate the mod, he also improved upon some parts of the game where the translation didn't really make any sense.

***

### Patch 1.1.0.0035 is here!
**10th of June 2018**\
The patch we've all been waiting for has arrived (albeit only on the beta branch so far) and with it comes loads of changes to different abilities and classes. Don't worry though, we got you covered with a new version of the mod (v. 0.2.2-beta) which includes all the balancing changes in the patch. You can read more about the patch [here](https://forums.obsidian.net/topic/101944-patch-notes-for-1100035/). It's well worth a read, there are some massive changes in this patch!

***

### Xaratas joins the team!
**3rd of June 2018**\
I would like to welcome **Xaratas** to the mod development team (check out his outstanding mod [Corrected German Translation](https://www.nexusmods.com/pillarsofeternity2/mods/5))! I think Xaratas will be a great addition to to the mod and that we'll see some really cool stuff down the line (especially for people interested in translating the mod to other languages).
