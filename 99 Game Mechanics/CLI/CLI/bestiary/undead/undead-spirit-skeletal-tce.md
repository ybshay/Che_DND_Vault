---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tce
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Undead Spirit (Skeletal)"
---
# [Undead Spirit (Skeletal)](99%20Game%20Mechanics/CLI/bestiary/undead/undead-spirit-skeletal-tce.md)
*Source: Tasha's Cauldron of Everything p. 114*  

```statblock
"name": "Undead Spirit (Skeletal) (TCE)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor)"
"hp": "20 + 10 for each spell level above 3rd"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "4"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](99%20Game%20Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](99%20Game%20Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](99%20Game%20Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](99%20Game%20Mechanics/CLI/rules/senses.md#Darkvision) 60 ft.,\
  \ passive Perception 10"
"languages": "understands the languages you speak"
"actions":
  - "desc": "The spirit makes a number of attacks equal to half this spell's level\
      \ (rounded down)."
    "name": "Multiattack"
  - "desc": "*Ranged Spell Attack:* your spell attack modifier to hit, range 150 ft.,\
      \ one target. *Hit:* 2d4 + 3 + the spell's level necrotic damage."
    "name": "Grave Bolt"
"source":
  - "TCE"
```
^statblock