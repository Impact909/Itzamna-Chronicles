---
title: "Nyogoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nTgnYvIuGCTUZoif" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Nyogoth"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Nyogoth"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[qlippoth]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Chthonian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +21, Intimidation: +19, Occultism: +16, Stealth: +21"
abilityMods: [7, 5, 6, 0, 5, 3]
speed: 5 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +20, __Ref__ +19, __Will__ +16"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  acid,  controlled,  fear effects; __Resistances__ mental 10, physical 10 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Caustic Blood"
    desc: "`pf2:r`  **Trigger** The nyogoth takes piercing or slashing damage\n* * *\n\n**Effect** The nyogoth sprays its acidic blood on adjacent creatures, dealing 6d6 acid damage (DC 29 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (magical, unholy)\n__Damage__  2d6 + 13 piercing plus grab 2d6 acid plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Tentacle Mouth"
    desc: "+23 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 13 piercing plus grab 1d6 acid plus grab 1d6 spirit plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 26, attack +20; __5th __  _[[Spells/Toxic Cloud|Cloudkill]]_; __4th __  _[[Spells/Acid Arrow|Acid Arrow (At will)]]_, _[[Spells/Translocate|Dimension Door]]_; __3rd __  _[[Spells/Fear|Fear (At will)]]_"

  - name: "Feeding Frenzy"
    desc: "`pf2:1`  **Requirements** The nyogoth has [[Conditions/Grabbed|Grabbed]] a creature\n* * *\n\n**Effect** The nyogoth slavers and chews at the grabbed creature, dealing 2d6+7 slashing and 1d6 acid damage (DC 29 Fortitude check save)."

  - name: "Nauseating Display"
    desc: "`pf2:2` (concentrate,emotion,fear,incapacitation,mental,occult,visual) The nyogoth untangles its tentacles and prolapses its many mouths, turning itself inside out in a truly nauseating display. Creatures in a 30-foot emanation must attempt a DC 29 Will check save, after which they are temporarily immune to further Nauseating Displays for 1 minute.\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 3]] and [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 5]] and [[Conditions/Sickened|Sickened 2]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Nyogoth
creatures:
  - 1: Nyogoth
```



Little more than a coiled mass of intestines encircling a massive gaping maw, this qlippoth is an Abyssal scavenger, subsisting on the filth and leftovers of demons and qlippoth alike, although it relishes any opportunity to consume living prey. Despite this seeming lowly role in the Abyssal ecosystem, a nyogoth is far from a stupid beast and can orchestrate cunning ambushes to secure its next meal.
