---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Blood Witch"
---
# [Blood Witch](99%20Game%20Mechanics/CLI/bestiary/humanoid/blood-witch-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 248*  

Blood witches imagine themselves to be the intermediaries between Rakdos and his cult-the pinnacle of his priesthood, his trusted advisors, and the messengers who communicate his will to the scattered troupes and ringmasters. The Cult of Rakdos recognizes no authority but Rakdos, and the demon lord requires no advisors. Nonetheless, the blood witches are smart, charismatic, and powerful, so their voices do carry some weight.

Blood witches strive both to protect the cult from external interference and to punish those who bring harm to the guild. They claim grandiose titles, such as Tormentor of the Wojek, as a way of mocking their intended victims.

```statblock
"name": "Blood Witch (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](99%20Game%20Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "13"
  - !!int "9"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "2"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](99%20Game%20Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Intimidation](99%20Game%20Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](99%20Game%20Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](99%20Game%20Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "psychic"
"gear":
  - "[longsword](99%20Game%20Mechanics/CLI/items/longsword.md)"
  - "[shortsword](99%20Game%20Mechanics/CLI/items/shortsword.md)"
"senses": "[darkvision](99%20Game%20Mechanics/CLI/rules/senses.md#Darkvision) 120\
  \ ft., passive Perception 12"
"languages": "Abyssal plus any one language (usually Common)"
"cr": "7"
"traits":
  - "desc": "The witch's innate spellcasting ability is Charisma (spell save DC 15,\
      \ +7 to hit with spell attacks). The witch can innately cast the following\
      \ spells, requiring no material components:\n\n**At will:** [alter self](99%20Game%20Mechanics/CLI/spells/alter-self.md),\
      \ [detect magic](99%20Game%20Mechanics/CLI/spells/detect-magic.md), [eldritch\
      \ blast](99%20Game%20Mechanics/CLI/spells/eldritch-blast.md) (at 11th level),\
      \ [false life](99%20Game%20Mechanics/CLI/spells/false-life.md), [levitate](99%20Game%20Mechanics/CLI/spells/levitate.md)\
      \ (self only), [mage armor](99%20Game%20Mechanics/CLI/spells/mage-armor.md)\
      \ (self only)\n\n**3/day each:** [hellish rebuke](99%20Game%20Mechanics/CLI/spells/hellish-rebuke.md),\
      \ [hex](99%20Game%20Mechanics/CLI/spells/hex.md), [scorching ray](99%20Game%20Mechanics/CLI/spells/scorching-ray.md)\
      \ (at 3rd level)\n\n**1/day each:** [circle of death](99%20Game%20Mechanics/CLI/spells/circle-of-death.md),\
      \ [enthrall](99%20Game%20Mechanics/CLI/spells/enthrall.md), [suggestion](99%20Game%20Mechanics/CLI/spells/suggestion.md)"
    "name": "Innate Spellcasting"
  - "desc": "The witch can use a bonus action to control the movement of one creature\
      \ cursed by its [hex](99%20Game%20Mechanics/CLI/spells/hex.md) spell that it\
      \ can see within 30 feet of it. The creature must succeed on a DC 15 Charisma\
      \ saving throw or use its reaction to move up to 30 feet in a direction of the\
      \ witch's choice."
    "name": "Blood Witch Dance"
  - "desc": "Magical darkness doesn't impede the witch's darkvision."
    "name": "Devil's Sight"
"actions":
  - "desc": "The witch makes two attacks: one with its longsword and one with its\
      \ shortsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Shortsword"
"source":
  - "GGR"
"image": "99%20Game%20Mechanics/CLI/bestiary/humanoid/token/blood-witch-ggr.webp"
```
^statblock