---
title: "Warden of Peaks and Skies"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NqsvRx0hzEZkKbtA" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/22
  - remaster
statblock: inline
name: "Warden of Peaks and Skies"
level: 22
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Warden of Peaks and Skies"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[air]]
trait_02: [[beast]]
modifier: 40
perception:
  - name: "Perception"
    desc: "+40; "
languages: "voice of nature"
skills:
  - name: "Skills"
    desc: "Acrobatics: +42, Diplomacy: +34, Medicine: +38, Nature: +40, Survival: +38, Bird Lore: +38, Mountain Lore: +38"
abilityMods: [8, 12, 9, 6, 10, 8]
speed: 60 feet,  fly 240 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +36, __Ref__ +40, __Will__ +38; +1 to all saves vs primal"
hp: 445
health:
  - name: ""
  - name: HP
    desc: "445; __Immunities__  electricity; __Resistances__ fire 15, cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Scent|Scent (Imprecise) 60 feet]]"
    desc: "  Scent involves sensing creatures or objects by smell, and is usually a vague sense. The range is listed in the ability, and it functions only if the creature or object being detected emits an aroma (for instance, incorporeal creatures usually do not exude an aroma).\n\nIf a creature emits a heavy aroma or is upwind, the GM can double or even triple the range of scent abilities used to detect that creature, and the GM can reduce the range if a creature is downwind."

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Stormsight"
    desc: "  Wind, precipitation, and clouds don't impair the warden's vision; she ignores the [[Conditions/Concealed|Concealed]] condition from storms, mist, precipitation, and the like."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Voice of Nature|Voice of Nature]]"
    desc: "  Though the Wardens of the Wild do not speak in words, they can communicate complex concepts flawlessly and wordlessly with any animal, beast, plant, or other creature of the natural world through prolonged eye contact. Sapient creatures with strong ties to the natural world, such as animal instinct barbarians or druids who speak the Wildsong, can somewhat understand a Warden of the Wild, though the meaning can be vague."

  - name: "[[Creature Family Ability Glossary/(Warden of the Wild) Warden's Crown|Warden's Crown]]"
    desc: "  A Warden of the Wild's horned crown commands respect from wild creatures. Wild creatures native to a warden's biome automatically improve their attitude toward it by one step (up to friendly) and typically do not take hostile actions towards each other while in the warden's presence."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+41 (finesse, magical, reach 10 feet)\n__Damage__  4d12 + 16 piercing"

  - name: "**Melee** `pf2:1` Horned Crown"
    desc: "+41 (agile, finesse, magical, reach 15 feet)\n__Damage__  4d8 + 16 piercing"

  - name: "**Ranged** `pf2:1` Gale Blast"
    desc: "+39 (air, magical, range increment 90 feet)\n__Damage__  2d8 + 16 bludgeoning 2d8 electricity"

  - name: "Primal Innate Spells"
    desc: "DC 45, attack +0; __10th __  _[[Spells/Revival|Revival]]_, _[[Spells/Wrathful Storm|Wrathful Storm]]_; __9th __  _[[Spells/Soothing Spring|Soothing Spring]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Crystal Exhalation"
    desc: "`pf2:2` (cold,primal) The warden breathes, creating a storm of ice crystals. All creatures in a 60-foot cone take 4d8 cold damage and 4d8 slashing damage (DC 44 Reflex check save). On a critical failure, a creature is [[Conditions/Immobilized|Immobilized]] by ice. The warden then can't use Crystal Exhalation for 1d4 rounds."

  - name: "Orogenesis Dive"
    desc: "`pf2:3` (air,earth,move,primal) The warden flies 240 feet upward in a straight line. As she does so, the ground in a 30-foot burst from her starting point rises into a 120-foot-high rocky pillar topped with a mountainous peak that becomes greater difficult terrain. All other creatures in that burst must succeed at a DC 44 Fortitude check save or be [[Conditions/Fatigued|Fatigued]] by the sudden altitude shift. The warden then flies straight downward to the center of the pillar's peak, driving her horns into the stone. As she lands, the newly formed mountains tremble. All other creatures in the area must succeed at a DC 42 Reflex check save or plummet off the peaks, falling 120 feet and landing in the nearest square outside the area. The pillar is permanent."

  - name: "Song of the Skies"
    desc: "`pf2:1` (air,auditory,primal) The warden trills a cheerful birdsong, granting a boon to all allies within 60 feet and evoking the freedom of flight. For the next minute, affected allies gain [[Spells/Unfettered Movement|Unfettered Movement]], a fly speed of 60 feet, and treat creatures on the ground as [[Conditions/Off-Guard|Off-Guard]] when they are airborne.\n\n[[Bestiary Effects/Effect_ Song of the Skies|Effect: Song of the Skies]]"

  - name: "Tempest Downdrafts"
    desc: " (air,primal) **Trigger** The warden Flies\n* * *\n\n**Effect** s The warden's flapping wings generate powerful gusts that blow smaller creatures off course. A 60-foot emanation, centered on the warden, fills with lightning-pierced winds until the beginning of the warden's next turn. Creatures must succeed at a DC 42 Reflex check save to take any move action within the winds; flying creatures use the outcome one degree of success worse than what they roll. Creatures who critically fail are blown 30 feet away from the warden, knocked [[Conditions/Prone|Prone]], and take 4d6 electricity damage."
 
```

```encounter-table
name: Warden of Peaks and Skies
creatures:
  - 1: Warden of Peaks and Skies
```



## Warden's Blessing

Legend says that the Warden of Peaks and Sky invites those who particularly earn their favor into their home, a nest within a hollow peak deep in the Kodar Mountains. There, the guest is treated to a grand feast, after which the warden offers to turn them into a thunderbird so they might enjoy the sky for the rest of their days, though they are not offended if anyone demurs.
