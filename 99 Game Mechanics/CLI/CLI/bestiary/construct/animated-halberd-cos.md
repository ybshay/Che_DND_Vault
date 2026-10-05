---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/cos
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Animated Halberd"
---
# [Animated Halberd](99%20Game%20Mechanics/CLI/bestiary/construct/animated-halberd-cos.md)
*Source: Curse of Strahd p. 59*  

```statblock
"name": "Animated Halberd (CoS)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "17"
"hit_dice": "5d6"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "11"
  - !!int "1"
  - !!int "5"
  - !!int "1"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  - "dexterity": !!int "4"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](99%20Game%20Mechanics/CLI/rules/conditions.md#Blinded),\
  \ [charmed](99%20Game%20Mechanics/CLI/rules/conditions.md#Charmed), [deafened](99%20Game%20Mechanics/CLI/rules/conditions.md#Deafened),\
  \ [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](99%20Game%20Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](99%20Game%20Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](99%20Game%20Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[halberd](99%20Game%20Mechanics/CLI/items/halberd.md)"
"senses": "[blindsight](99%20Game%20Mechanics/CLI/rules/senses.md#Blindsight) 60 ft.\
  \ (blind beyond this radius), passive Perception 7"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The sword is [incapacitated](99%20Game%20Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ while in the area of an [antimagic field](99%20Game%20Mechanics/CLI/spells/antimagic-field.md).\
      \ If targeted by [dispel magic](99%20Game%20Mechanics/CLI/spells/dispel-magic.md),\
      \ the sword must succeed on a Constitution saving throw against the caster's\
      \ spell save DC or fall [unconscious](99%20Game%20Mechanics/CLI/rules/conditions.md#Unconscious)\
      \ for 1 minute."
    "name": "Antimagic Susceptibility"
  - "desc": "While the sword remains motionless and isn't flying, it is indistinguishable\
      \ from a normal sword."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d10 + 1) slashing damage."
    "name": "Halberd"
"source":
  - "CoS"
"image": "99%20Game%20Mechanics/CLI/bestiary/construct/token/animated-halberd-cos.webp"
```
^statblock