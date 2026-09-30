# Made in Heaven - Spell Pack Lite
A lightweight three-component fork of Made in Heaven - Spell Pack for Baldur's Gate 1 and Baldur's Gate 2.


## Introduction

This Lite fork keeps only the Arcane Spellpack, Divine Spellpack and Planescape Torment Spellpack from Angel's original Made in Heaven - Spell Pack. The original spell content and credits are preserved, while the installer is intentionally reduced to these three components.

## Component list

Made in Heaven - Spell Pack Lite intentionally exposes only these three spell-pack components:

- Arcane Spellpack  - Original wizard/sorcerer/bard spells by Angel.
- Divine Spellpack  - Original cleric/druid/shaman spells by Angel.
- PST Spellpack     - Introduces a handful of spells from Planescape Torment.

The original WeiDU component numbers are preserved for compatibility with existing installs and WeiDU logs:

- #0 Arcane Spellpack
- #2 Divine Spellpack
- #4 PST Spellpack

This build also includes the Infinity UI++ compatibility fix that filters SFO class/kit metadata from Infinity UI++ class-level helper functions.

For detailed descriptions, please check the docs directory.

Original mod by Angel. Lite fork maintained by Sauler89.


## Version History

v9-lite-iui-fix2 - September 30 2026
- Renamed the custom fork to Made in Heaven - Spell Pack Lite and synchronized package metadata/documentation.
- Custom three-component fork: Arcane Spellpack, Divine Spellpack, PST Spellpack only.
- Preserved original WeiDU component IDs #0, #2 and #4.
- Added Infinity UI++ compatibility filtering for SFO {K=...,C=...} class/kit metadata.


Version 9 - ???

Version 8 - May 31 2026
- Bug fix release, thanks to testing by Lumorus and others on G3.
- Marked Time Stop tweaks as a work in progress.
- Replaced Web of Lightning with Lightning Ring.
- Updated several icons, thanks to Zenblack.
- Added Animal Growth for druids.

Version 7 - December 27 2025
- Added fourth level Animate Dead for Wizards availability tweak.
- All spells now have proper icons thanks to Zenblack.
- Added new Ranger Powers component.
- Added new Monk Powers component.
- Added IWD Arcane/Divine spell components.
- Split off PST spells into their own component.
- Lots of code changes under the hood to upgrad to new SFO v2.
- Renamed/removed some spells and tweaks that clash with SCS or ToF.
- Removed forced spell renaming from lore changes.
- Removed experimental components that just weren't working out.
- Massive updates to the readme.

Version 6 - December 18 2022
- Fixed many bugs and added some new spells to play around with.
- Documented new paladin powers better, added note about other mods
- Integrated Thalatyr the *Conjurer* with lore-friendly changes
- Various versions of (Super)Heroism won't stack, for real this time (I hope)
- Added new component Bard Powers
- Moved Spell Restorations to new mod Fixes & Restorations

Version 5 - October 18 2021
- Added missing icon for Tattoos of Power
- Added missing graphics for Evard's Black Tentacles
- Fixed erroneous strings in Tattoos of Power and Spell Matrix on BG2(EE)
- Made Heroism and Superheroism not cumulative with each other
- Readme updates, clearly marked experimental components.

Version 4 - August 4 2021
- Finally fixed the issue with Spell Matrix and area effect spells
- Damage spells use proper save for half damage mechanics in EE games
- Added a few experimental epic spells and other high-level abilities
- Paladins can start casting spells at level 4 (as per 3.5e rules)
- Bug fixes and code improvements

Version 3 - October 3 2020
- Fixes to make mod work with WeiDU 247
- Several new tweaks
- Rudimentary graphics for Evard's Black Tentacles
- Bug fixes and code improvements

Version 2 - May 21 2020
- Almost complete rewrite using the SFO library

Version 1 - June 1 2019
- Initial version
