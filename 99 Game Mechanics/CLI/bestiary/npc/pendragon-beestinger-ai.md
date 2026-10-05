---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pendragon Beestinger"
---
# [Pendragon Beestinger](99%20Game%20Mechanics/CLI/bestiary/npc/pendragon-beestinger-ai.md)
*Source: Acquisitions Incorporated p. 206*  

Able arcanist Pendragon Beestinger took over as "B" Team cartographer after Brahma Lutier left the group. In fact, his first assignment was to assist in the team's attempts to apprehend the wandering bard. An adopted child of the "C" Team's Rosie Beestinger, Pendragon is his mother's foil in almost every way-including his goal of wanting to mainstream some of the family's rumored criminal interests. Pendragon has, in fact, attempted to kill his mother-and been killed himself in the process. Despite his having been resurrected at Rosie's request, things remain cool between the two.

Pendragon was kicked out of wizarding school as a result of the dark rumors following the Beestinger clan. Now a self-taught mage, he specializes in making use of the dangerous spells and weird trinkets he often comes across in his role as a kind of arcane archaeologist. Seeking out the family feeling that an adventuring group provides keeps him in the "B" Team, even if that unfortunately comes with Oak Truestrike as a kind of father figure.

```statblock
"name": "Pendragon Beestinger (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](99%20Game%20Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](99%20Game%20Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Investigation](99%20Game%20Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Performance](99%20Game%20Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+2"
"gear":
  - "[shortsword](99%20Game%20Mechanics/CLI/items/shortsword.md)"
"senses": "passive Perception 10"
"languages": "Common, Draconic, Elvish, Halfling"
"cr": "2"
"traits":
  - "desc": "Pendragon is a 4th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [acid splash](99%20Game%20Mechanics/CLI/spells/acid-splash.md),\
      \ [light](99%20Game%20Mechanics/CLI/spells/light.md), [mage hand](99%20Game%20Mechanics/CLI/spells/mage-hand.md),\
      \ [poison spray](99%20Game%20Mechanics/CLI/spells/poison-spray.md), [shocking\
      \ grasp](99%20Game%20Mechanics/CLI/spells/shocking-grasp.md)\n\n**1st level\
      \ (4 slots):** [detect magic](99%20Game%20Mechanics/CLI/spells/detect-magic.md),\
      \ [mage armor](99%20Game%20Mechanics/CLI/spells/mage-armor.md), [magic missile](99%20Game%20Mechanics/CLI/spells/magic-missile.md),\
      \ [sleep](99%20Game%20Mechanics/CLI/spells/sleep.md)\n\n**2nd level (3 slots):**\
      \ [blindness/deafness](99%20Game%20Mechanics/CLI/spells/blindness-deafness.md),\
      \ [cloud of daggers](99%20Game%20Mechanics/CLI/spells/cloud-of-daggers.md),\
      \ [scorching ray](99%20Game%20Mechanics/CLI/spells/scorching-ray.md)"
    "name": "Spellcasting"
  - "desc": "Pendragon can cast the spell he cast on his last turn, whose casting\
      \ time becomes 1 bonus action. This bonus casting uses a spell slot as normal."
    "name": "Echo Spell (1/Day)"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage."
    "name": "Shortsword"
"source":
  - "AI"
"image": "99%20Game%20Mechanics/CLI/bestiary/npc/token/pendragon-beestinger-ai.webp"
```
^statblock