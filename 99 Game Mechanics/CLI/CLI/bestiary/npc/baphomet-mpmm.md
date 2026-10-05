---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Baphomet"
---
# [Baphomet](99%20Game%20Mechanics/CLI/bestiary/npc/baphomet-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 58, Mordenkainen's Tome of Foes p. 143*  

Civilization is weakness and brutality is strength in the credo of Baphomet, the Horned King and the Prince of Beasts. He is worshiped by those who want to break the confines of civility and unleash their bestial natures, for Baphomet envisions a world without restraint, where creatures live out their most bloodthirsty desires.

Cults devoted to Baphomet use mazes and complex knots as their emblems. They create secret places to indulge themselves, including labyrinths of the sort their master favors. Bloodstained crowns and weapons of iron and brass decorate their profane altars.

Over time, a cultist of Baphomet becomes tainted by his influence, gaining bloodshot eyes and coarse, thickening hair. Small horns eventually sprout from the cultist's forehead. In time, a devoted cultist might transform entirely into a minotaur, which is considered the greatest gift of the Prince of Beasts.

Baphomet appears as a fearsome, 20-foot-tall minotaur with six iron horns. A fiendish light burns in his red eyes. Although he is filled with bestial blood lust, there lies within him a cruel and cunning intellect devoted to subverting all civilization.

Baphomet wields a great glaive called Heartcleaver. He also charges his enemies and gores them with his horns, trampling his foes into the earth and rending them with his teeth like a beast.

## Cultists of Baphomet

> [!note]
> See the Cult of Baphomet entry.

## Baphomet's Lair

Baphomet's lair is his palace, the Lyktion, which is on the layer of the Abyss called the Endless Maze. Nestled within the twisting passages of the plane-wide labyrinth, the Lyktion is immaculately maintained and surrounded by a moat constructed in the fashion of a three-dimensional maze. The palace is a towering structure whose interior is as labyrinthine as the plane on which it stands; it is populated by [minotaurs](99%20Game%20Mechanics/CLI/bestiary/monstrosity/minotaur.md), [goristros](99%20Game%20Mechanics/CLI/bestiary/fiend/goristro.md), and [quasits](99%20Game%20Mechanics/CLI/bestiary/fiend/quasit.md).

```statblock
"name": "Baphomet (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "319"
"hit_dice": "22d12 + 176"
"modifier": !!int "2"
"stats":
  - !!int "30"
  - !!int "14"
  - !!int "26"
  - !!int "18"
  - !!int "24"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "15"
  - "wisdom": !!int "14"
"skillsaves":
  - "name": "[Intimidation](99%20Game%20Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+17"
  - "name": "[Perception](99%20Game%20Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+14"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison; bludgeoning, piercing, slashing that is nonmagical"
"condition_immunities": "[charmed](99%20Game%20Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](99%20Game%20Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](99%20Game%20Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](99%20Game%20Mechanics/CLI/rules/senses.md#Truesight) 120 ft.,\
  \ passive Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "23"
"traits":
  - "desc": "Baphomet can perfectly recall any path he has traveled, and he is immune\
      \ to the [maze](99%20Game%20Mechanics/CLI/spells/maze.md) spell."
    "name": "Labyrinthine Recall"
  - "desc": "If Baphomet fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Baphomet has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Baphomet makes one Bite attack, one Gore attack, and one Heartcleaver\
      \ attack. He also uses Frightful Presence."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 19 (2d8 + 10) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (2d6 + 10) piercing damage. If Baphomet moved at least 10 feet straight\
      \ toward the target immediately before the hit, the target takes an extra 16\
      \ (3d10) piercing damage. If the target is a creature, it must succeed on\
      \ a DC 25 Strength saving throw or be pushed up to 10 feet away and knocked\
      \ [prone](99%20Game%20Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Gore"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 15 ft., one target. *Hit:*\
      \ 21 (2d10 + 10) force damage."
    "name": "Heartcleaver"
  - "desc": "Each creature of Baphomet's choice within 120 feet of him and aware of\
      \ him must succeed on a DC 18 Wisdom saving throw or become [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A [frightened](99%20Game%20Mechanics/CLI/rules/conditions.md#Frightened)\
      \ creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success. These later saves have disadvantage if\
      \ Baphomet is within line of sight of the creature.\n\nIf a creature succeeds\
      \ on any of these saves or the effect ends on it, the creature is immune to\
      \ Baphomet's Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "Baphomet casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n**3/day\
      \ each:** [dispel magic](99%20Game%20Mechanics/CLI/spells/dispel-magic.md),\
      \ [dominate beast](99%20Game%20Mechanics/CLI/spells/dominate-beast.md), [maze](99%20Game%20Mechanics/CLI/spells/maze.md),\
      \ [wall of stone](99%20Game%20Mechanics/CLI/spells/wall-of-stone.md)\n\n**1/day:**\
      \ [teleport](99%20Game%20Mechanics/CLI/spells/teleport.md)"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Baphomet can expend a use to take one of the following actions. Baphomet\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Baphomet makes one Heartcleaver attack."
    "name": "Heartcleaver Attack"
  - "desc": "Baphomet moves up to his speed without provoking [opportunity attacks](99%20Game%20Mechanics/CLI/rules/actions.md#Opportunity%20Attack),\
      \ then makes a Gore attack."
    "name": "Charge (Costs 2 Actions)"
"source":
  - "MPMM"
  - "MTF"
"image": "99%20Game%20Mechanics/CLI/bestiary/npc/token/baphomet-mpmm.webp"
```
^statblock