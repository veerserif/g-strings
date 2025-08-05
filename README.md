# g-strings
Text fixes for GAMMA (0.9.4+), using XML overrides instead of direct file replacements

## General style rules
- Only overwrite specific nodes that need to be overwritten	
- Capitalization in sentence case (only capitalize first word of the phrase) where possible	
	- Exception: Capitalize All Words for MCM menu names (if needed)
	- Capitalize proper nouns (e.g. names of locations, faction names, artefacts). Names of things like mutant types are not proper nouns.
- Avoid abbreviations in PDA text and messages, only use them where phrases have to be short (e.g. task titles, dynamic news messages, inventory short names)	
- Mark quest items as quest items	
- Flavor text in item descriptions should not imply the existence of game mechanics that don't exist	
- British English probably wins (e.g. basegame calls them "artefacts" which is British, versus American "artifacts") but don't stress about it	
    - If text **from a mod** uses a particular convention (e.g. American v.s. British English), keep it
- **First-person** PDA messages	where possible
- No punctuation at the end of short strings. Unless it's supposed to be a formatted piece of text like a task description, no punctuation at the end of a line	
	
	
For weapons and outfits:	
- Variant gun names should always be in double quotation marks	
- Alternate variants should be marked with "(alternate)"

## To-do list

- Quest text
  - [x] Vanilla quest text
  - [ ] Mod-added quest text
- Quest dialogues
  - [x] Vanilla quest dialogues
  - [ ] Mod-added quest dialogues
- Non-quest dialogues
  - [ ] Vanilla dialogues
  - [ ] Mod-added dialogues
- PDA text (achievements, encyclopedia, guide)
  - [ ] Vanilla
  - [ ] Mod-added
- UI text strings
  - [ ] Vanilla
  - [ ] Mod-added
- [ ] Loading screens (maybe also fix the loading screen variant cap)
- Item strings
  - Quest items
    - [x] Vanilla
    - [ ] Mod-added
  - Weapons and weapon addons
    - [ ] Vanilla
    - [ ] Mod-added
  - Outfits
    - [ ] Vanilla
    - [ ] Mod-added
  - Ammo
    - [ ] Vanilla
    - [ ] Mod-added
  - Devices, tools, repair items
    - [ ] Vanilla
    - [ ] Mod-added
  - Item parts, upgrades
    - [ ] Vanilla
    - [ ] Mod-added
  - Junk items
    - [ ] Vanilla
    - [ ] Mod-added
  - Other items
    - [ ] Vanilla
    - [ ] Mod-added
- [ ] Mod-added text (e.g. MCM, text in script files)
