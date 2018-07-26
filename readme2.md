#### Pillars of Eternity 2
# Enhanced User Interface
*The Enhanced User Interface mod aims to improve the standard user interface by highlighting gameplay mechanics such as afflictions and inspirations, damage and defense keywords and much more. In total 1057 ability, item or UI entries have been modified to enhance the user experience and to make some fairly opaque game mechanics a bit more transparent.*

**Credits:**\
English: *Spherikal*\
German: *Xaratatas*\
Italian: *Kilay*\
Korean: *Xinkle*\
Russian: *phenomenum*

***

## Useful links:
- [Changelog](https://github.com/Spherikal/PoE2-EnhancedUserInterface/blob/master/changelog.md)
- [Modding Resources](https://github.com/Spherikal/PoE2-EnhancedUserInterface/wiki)

## Table of Contents
- [Installation](#installation)
- [Recently Added Features](#recently-added-features)
- [Implemented Features](#implemented-features)

***

## Contents of this Git
- `PoE2-EnhancedUserInterface-Main` (Recommended)
  Includes all currently implemented features. For a full list of implemented features please [click here](#).
- `PoE2-EnhancedUserInterface-Damage-and-Defense` (Stand-alone)
  Use this version if you *only* want the Accuracy, Health, Damage and Defense icons.
- `PoE2-EnhancedUserInterface-Afflictions-and-Inspirations` (Stand-alone)
  Use this version if you *only* want icons, colorization and rank indicators for afflictions and inspirations.
- `PoE2-EnhancedUserInterface-Afflictions-Inspirations-and-Damage-Defense` (Stand-alone)
This version contains *both* the `Damage-and-Defense` package as well as the `Afflictions-and-Inspirations` package. Use this version if you *only* want those features and aren't interested in any [additional features](#).

***

## Installation

1. Download the `v0.9-beta.6.zip` or `v0.9-beta.6.tar.gz` file over [here](https://github.com/Spherikal/PoE2-EnhancedUserInterface/releases).
2. Go to your `Pillars of Eternity II\PillarsOfEternityII_Data\` directory.
3. Look for (or create) an `override` folder in your `PillarsOfEternityII_Data` directory.
The correct file path should look like this: `Pillars of Eternity II\PillarsOfEternityII_Data\override`
4. Extract the `PoE2-EnhancedUserInterface-0.9-beta.6` folder into your `override` folder.
5. Launch the game.

Once extracted the folder structure should look like this:
```
Pillars of Eternity II
└─ PillarsOfEternityII_Data
   └─ override
      └─ PoE2-EnhancedUserInterface-0.9-beta.6
         ├─ localized
         │  └─ en
         │     └─ text
         │        └─ game
         │           ├─ abilities.stringtable
         │           ├─ cyclopedia.stringtable
         │           ├─ gui.stringtable
         │           ├─ items.stringtable
         │           ├─ recipes.stringtable
         │           └─ statuseffects.stringtable
         ├─ EnhancedUI-NewKeywords.gamedatabundle
         ├─ manifest.json
         └─ thumb.png
```

***

#### *Recently Added Features*
## New Enchanting Icons for Weapons and Armor
**Armor and Weapon Enchants**\
As of mod `v0.9-beta.6` armor enchantments got a icon next to their name in order to show which enchantments are mutually exclusive.

![](images/item_enchantment.png)

An enchantment with the `♀` symbol next to their name means that it's grouped with the other enchant with the `♀` symbol next to it. If you choose an enchantment with the `♀` symbol then the other enchanment with the `♀` symbol will disapear, i.e. they are mutually exclusive. The same is true for the `♂` symbol.

If an item only have one (1) of either `♂` or `♀` then that means that it wont cancel another enchantment out.

If an item have more than two (2) of either `♀` or `♂` then that means that you'll only be able to pick **one** of the enchantments with the same symbol next to it's name.

***

#### *Implemented Features*
## Afflictions & Inspirations
Our first (and to this day biggest!) feature includes colorization of affliction and inspiration names, added icons to all edited entries, and a  rank indicator next to the attribute icon.

![These are the colors and icons for each attribute](images/attributes_color.png)

*Colors:*\
Each affliction/inspiration get a color based off of their affected attribute. For example, the **Strong** inspiration affects the **Might** attribute and will therefore be using a red color scheme used by other **Might Afflictions** and **Inspirations**.

![Example of what the icons will look like in-game](images/afflictions_inspirations.png)

*Icons:*\
In addition to added color schemes all afflictions and inspirations also come with a icon that once again reminds the player what attribute gets affected by what buff/debuff.

*Ranks*\
This feature also adds a rank number (1, 2 or 3) next to the attribute icon so that the player immediately knows how severe or powerful an affliction or inspiration is.

**In-Game Example**

![Example of what the icons will look like in-game](images/features_1.png)

***

## Damage and Defense Icons
**Details**\
The damamge icon set is the only icon set in this mod that isn't colorized. I did this  family of icons is the only I choose to render the damage icons in a plain white color mainly because we are using so many colors already and I don't want to over saturate this mod. The colors we got are flashy enough as is.

![Example of what the defense and damage icons will look like in-game](images/damage_defense.png)

As can be seen the defense icons were colorized to look as close to how they look in the standard UI in order to avoid any confusion about in what context they should be relevant to the player.

**In-Game Example**

![Example of what the defense icons will look like in-game](images/features_3.png)

![Example of what the damage icons will look like in-game](images/features_2.png)

***

## New Tooltips for Afflictions and Inspirations
### Why would I want this?
Well, because the old ones were rather dull and a little bit confusing, right?

![Example of what the damage icons will look like in-game](images/tooltip_before_after.png)

The unmodded tooltip is, in my opinion, too condensed and messy. By breaking up the attribute affliction name into a kind of sub-header made the tooltip easier to read at a glance which makes the UX a little bit more pleasant.

**In-Game Example**

![Example of what the defense icons will look like in-game](images/features_4.png)

***

## Cyclopedia Entries for All Damage Types
### Description
Under construction.

**In-Game Example**

![Example of what the defense icons will look like in-game](images/features_5.png)

***

## Colorized Reputation Gains
### Description
Under construction.

**In-Game Example**

![Example of what the defense icons will look like in-game](images/features_6.png)
