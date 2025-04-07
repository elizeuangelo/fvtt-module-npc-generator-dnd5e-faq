# Patch Notes

## 1.26.2

-   Fixes damage evaluation bug on martial classes
-   Adds activities to "Bite" and "Unarmed Strike" features

## 1.26.1

-   Fixes several bugs with different races and classes in DnD v4.1.2

## 1.25.1

-   Fixes several compatibility issues with latest v12 versions up to 12.331
-   Adds support for DnD v4.1.1, breaking changes no longer works on DnD v3.x.x

## 1.24.3

-   Fix sourceId bug on character creation and removes deprecated v12 warnings
-   Makes DnD5e v3 compatible with v12

## 1.24.2

-   Babele compatible (module won't break). Still no official translations

## 1.24.1

-   Removed form report
-   Added github FAQ

## 1.24.0

-   Module now compatible with v11
-   Module now compatible with DnD v3
-   Added 100+ new plots
-   Minor job changes
-   Several bug fixes
-   Removed google sheet bug form
-   Added github faq url

## 1.23

-   Fixed some features description

## 1.22

-   Fixed bug where the lack of a token folder kills portrait generation

## 1.21

-   Added CR 0 for creating commoners
-   Experimental CR implemented as core, removed experimental CR configuration
-   Broader validation algorithm

## 1.20

-   Updated report information
-   Changes in Human bio settings
-   Patched issue in last dnd system update, where all skills abilities defaulted to dexterity

## 1.19

-   Changes in Paladin bio settings
-   Age and sex can now be locked

## 1.18

-   Fixes Tidysheet v0.8.19 update integration
-   Application now identifies folders during character creation
-   New setting: Default Folder
-   Packs can now be customized
-   New settings: Custom Feature Packs
-   New settings: Custom Item Packs
-   New settings: Custom Spell Packs

## 1.17

-   New Job: Warlock

## 1.16

-   Fixed Monk job bug regarding Unarmored Defense
-   Fixed issue with portrait generation subfolder search, involving capitalized names
-   Fixed other small issues

## v1.15

-   Fixed bug when selecting the correct compendium for an item, caused by some items, feats and spells having the same name
-   Portrait generation now searches in subfolders as well
-   Berserker job rebuilt

## v1.14

-   Added notifications when creating NPCs
-   Improved sheet type identification
-   Allow experimental 13-20 CR range

## v1.13

-   Alignment is now selected on randomization, to take Bio into account
-   Added age modifications for different jobs
-   Fixed small bugs regarding biographies
-   Minor small changes to several jobs and biographies
-   Biography info now is preserved with 'Build NPC' context menu

## v1.12

-   Fixed createNPC issue when world doesnt have any sheet modules installed

## v1.11

-   Fixes ForgeVTT bug with portrait generation

## v1.10

-   Add roleplay information for the NPCs
-   Add physical traits (height, weight, eyes, etc)

## 1.00

-   Smarter action planning algorithm
-   New Job: Druid
-   New Job: Priest
-   New Job: Sorcerer
-   New Job: Warcleric

## 0.94

-   New Job: Abjurer
-   New Job: Evoker
-   Fully migrated to v10
-   Added precast spells feature
-   Fixes descriptions of items imported from DnD Beyond Importer
-   Fixed some attack bonus inconsistencies
-   Enhanced spell damage evaluation algorithm
-   Remade skill system
-   Images with no race or job filter will be considered as including all races or all jobs
-   Armors now provides alternative armor in case str requirements are not met (except for dwarves)
-   Added 'All' option in the language menu
-   Small changes in most jobs

## 0.931

-   Added compatibility with DnD Beyond Importer
-   Descriptions with unknown commands no longer stops code execution, this is done to increase compatibility with other modules

## 0.93

-   Changed 'Generate NPC' element class, to add compatibility with other modules
-   Fixed Forge-vtt path issue

## 0.92

-   Fixed bug concerning NPCs alignments
-   Thief: slowed down DEX stats growth
-   Updated manifest for v10 compatibility

## 0.91

-   New Job: Paladin
-   Portrait configuration now is defaulted to ''
-   Portrait configuration no longer failsafe to the module's example gallery, meaning the portrait feature is deactivated until the user chooses to use it
    If you already have it enabled and want to deactivate it, simply configure an empty folder or no folder

## 0.9

-   Beta release! 11 jobs + 17 races + 25 name generators!
