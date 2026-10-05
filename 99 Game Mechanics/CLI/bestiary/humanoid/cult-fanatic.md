---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cult Fanatic"
---
# [Cult Fanatic](99%20Game%20Mechanics/CLI/bestiary/humanoid/cult-fanatic.md)
*Source: Monster Manual p. 345. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Fanatics are often part of a cult's leadership, using their charisma and dogma to influence and prey on those of weak will. Most are interested in personal power above all else

```statblock
"name": "Cult Fanatic"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "13"
"ac_class": "[leather armor](99%20Game%20Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](99%20Game%20Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](99%20Game%20Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
  - "name": "[Religion](99%20Game%20Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[dagger](99%20Game%20Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
  - "desc": "The fanatic is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 11, +3 to hit with spell attacks). The fanatic has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](99%20Game%20Mechanics/CLI/spells/light.md),\
      \ [sacred flame](99%20Game%20Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](99%20Game%20Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [command](99%20Game%20Mechanics/CLI/spells/command.md),\
      \ [inflict wounds](99%20Game%20Mechanics/CLI/spells/inflict-wounds.md), [shield\
      \ of faith](99%20Game%20Mechanics/CLI/spells/shield-of-faith.md)\n\n**2nd level\
      \ (3 slots):** [hold person](99%20Game%20Mechanics/CLI/spells/hold-person.md),\
      \ [spiritual weapon](99%20Game%20Mechanics/CLI/spells/spiritual-weapon.md)"
    "name": "Spellcasting"
  - "desc": "The fanatic has advantage on saving throws against being [charmed](99%20Game%20Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
"actions":
  - "desc": "The fanatic makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "MM"
"image": "99%20Game%20Mechanics/CLI/bestiary/humanoid/token/cult-fanatic.webp"
```
^statblock

## Environment

urban