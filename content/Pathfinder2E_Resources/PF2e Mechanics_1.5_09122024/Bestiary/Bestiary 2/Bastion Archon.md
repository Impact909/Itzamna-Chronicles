---
title: "Bastion Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wLRBiLP7cmYo4Srd" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Bastion Archon"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Bastion Archon"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Darkvision, Truesight"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +38, Diplomacy: +34, Intimidation: +34, Religion: +32"
abilityMods: [10, 7, 10, 6, 8, 6]
speed: 70 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +38, __Ref__ +31, __Will__ +34; +1 status to all saves vs. magic"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, (fast healing 30); __Weaknesses__ unholy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Bastion Aura"
    desc: " (aura,divine,healing) 50 feet. All good-aligned creatures in the aura have fast healing 30 for as long as they remain in range, and they gain a +2 status bonus to attack rolls and damage rolls.\n\n[[Bestiary Effects/Effect_ Bastion Aura|Effect: Bastion Aura]]"

  - name: "[[Bestiary Ability Glossary/Retributive Strike|Retributive Strike]]"
    desc: "`pf2:r`  **Damage Reduction** 22\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

  - name: "Ultimate Sacrifice"
    desc: " (divine,healing) If the bastion archon is slain by an evil creature, it explodes in a geyser of holy light, restoring 140 HP to all good-aligned creatures in a 40-foot emanation. The ground in the affected area is also subjected to a level 10 [[Spells/Consecrate|Consecrate]] ritual, and the ground is consecrated for 10 years (or only 24 hours if the ultimate sacrifice took place in Hell, Abaddon, or the Abyss)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+40 (holy, magical, reach 15 feet)\n__Damage__  4d8 + 20 bludgeoning 2d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +34; __10th __  _[[Spells/Falling Stars|Meteor Swarm]]_, _[[Spells/Polar Ray|Polar Ray]]_, _[[Spells/Sunburst|Sunburst]]_; __7th __  _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/True Target|True Target (x3)]]_, _[[Spells/Vibrant Pattern|Vibrant Pattern]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_\n__Constant__  __(10th)__ _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast [[Spells/Translocate|Translocate]], the archon can use dimension door (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's dimension door. If the archon's dimension door has enough distance, the archon appears the same distance and direction from the creature as before either creature used dimension door."

  - name: "Blinding Beams"
    desc: "  **Trigger** The bastion archon hits a creature with two fist Strikes this turn and can use its Holy Beam\n* * *\n\n**Effect** The bastion archon fires its Holy Beam at only the creature it hit twice. The creature's save result is one degree of success worse than the result it rolled."

  - name: "Entrench"
    desc: "`pf2:1` (move) The bastion archon locks itself in place, becoming voluntarily [[Conditions/Immobilized|Immobilized]]. While Entrenched, the archon can't be forcibly moved or tripped, and it gains a +2 circumstance bonus to AC and Reflex saves. Entrench ends automatically as soon as the bastion archon uses another move action."

  - name: "Holy Beam"
    desc: "`pf2:2` (divine,holy,incapacitation,light) The bastion archon releases a blinding beam of holy light in a 500-foot line that deals 20d6 spirit damage to non-archons in the area, with a DC 38 Reflex check save.\n\nThe bastion archon can't use Holy Beam again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Blinded|Blinded]] for 1d4 rounds.\n\n**Critical Failure** The creature takes double damage and is blinded permanently."
 
```

```encounter-table
name: Bastion Archon
creatures:
  - 1: Bastion Archon
```



The mightiest of archon-kind form in the heat of battle from incredibly uncommon circumstances. When a gathering of lantern archons converges into a gestalt in order to defend allies in a fight that seems all but lost, a fellow archon of significant strength-such as a star archon-can commit a brave act of self-sacrifice by dimensionally transposing itself with the gestalt. If the circumstances are just right and luck is with the archons, the result is not a glorious sacrifice, but instead the earth-rocking emergence of a bastion archon. In this way, the lowliest of archons-the lanterns-can, in an instant, become their kind's greatest hope.

Bastion archons are massive beings made of the very stone of Heaven's Holy Mountain, with their visages obscured by a blinding light surrounding the gestalt that originally formed the bastion. Tireless in their embodiment of the virtue of sacrifice, a bastion archon almost always protects the area where they manifested, and even when they are destroyed they leave an indelible mark of righteousness upon the surrounding region.
