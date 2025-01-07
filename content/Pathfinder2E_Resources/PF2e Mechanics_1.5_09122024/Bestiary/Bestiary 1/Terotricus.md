---
title: "Terotricus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TXnpvz5u730YPaOL" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Terotricus"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Terotricus"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fungus]]
trait_04: [[unholy]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: "Chthonian, Elven, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +37, Deception: +32, Intimidation: +35, Nature: +31, Survival: +31"
abilityMods: [10, 5, 9, -1, 6, 5]
speed: 35 feet,  burrow 25 feet,  climb 25 feet,  swim 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +34, __Ref__ +28, __Will__ +33; +1 status to all saves vs. magic"
hp: 370
health:
  - name: ""
  - name: HP
    desc: "370, regeneration 25 (deactivated by cold); __Immunities__  controlled,  disease,  paralyzed,  sleep; __Weaknesses__ cold 15, cold iron 15, holy 15, slashing 10; __Resistances__ fire 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Cold)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Spore Cloud"
    desc: " (aura,disease) 30 feet. A creature entering the aura or starting its turn there is exposed to spore blight."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+37 (magical, reach 20 feet, unholy)\n__Damage__  4d10 + 16 bludgeoning plus improved-grab,improved-push 4d6 spirit plus improved-grab,improved-push"

  - name: "**Ranged** `pf2:1` Spores"
    desc: "+37 (magical, range increment 80 feet, unholy)\n__Damage__  4d8 + 6 poison plus spore-blight,sticky-spores 4d6 spirit plus spore-blight,sticky-spores"

  - name: "Infest Environs"
    desc: "`pf2:2` (healing,primal) **Frequency** once per day\n\n**Requirements** The terotricus is in a swamp or forested area.\n* * *\n\n**Effect** The terotricus drains nutrients from nearby trees and undergrowth while simultaneously infesting them with fungal growth. All non-magical plant life (though not plant creatures) within a 60-foot emanation withers and sprouts foul mold and slimy mushrooms, removing any cover and concealment provided by trees and undergrowth. The terotricus is healed 200 Hit Points."

  - name: "Spore Blight"
    desc: " (disease) Plants and fungi are immune.\n\n**Saving Throw** DC 40 Fortitude check\n* * *\n\n**Stage 1** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 4]] and [[Conditions/Slowed|Slowed 1]] (1 day)\n\n**Stage 3** [[Conditions/Controlled|Controlled]] by the terotricus (as [[Spells/Dominate|Dominate]]; 5d8 days)\n\n**Stage 4** dead"

  - name: "Sticky Spores"
    desc: "  A creature hit by a terotricus's spores must succeed at a DC 40 Reflex check save or take a -10-foot status penalty to all its Speeds for 1 minute. On a critical failure, the creature is [[Conditions/Immobilized|Immobilized]] until it Escapes (DC 40).\n\n[[Bestiary Effects/Effect_ Sticky Spores|Effect: Sticky Spores]]"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push 20 feet (40 feet on a Critical Hit)]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Terotricus
creatures:
  - 1: Terotricus
```



The legendary terotricus is a massive slime-mold that hails from the Abyss. Its collective consciousness encapsulates entire regions, spreading as far as its ever-growing cloud of spores will take it. Once it has seeped onto the Material Plane from the Abyssal realm, a terotricus's agenda is to feed on all living creatures, infecting them with its spores, and its presence can spell doom for any in its way.

Terotricuses move by rapidly expanding and contracting their slimy "bodies," which are capable of burrowing through soil, gliding across water, and scrabbling up steep slopes. These behemoths of rot don't need to travel to see their plans come to fruition, though; their spores easily latch onto demons and other denizens of the Abyss, who in turn bring this blight to the Material Plane when the flends are summoned.

When a terotricus infects a creature with its spores, web-like fungal growths start appearing on the victim's skin until they cover the entire body, at which point the victim's mind is also subdued and bent to the terotricus's will. The terotricus's favored victims include animals, elves, and fey, though it is happy to infect any creature it can catch. Cults of Treerazer occasionally attempt to make contact with a terotricus, but such acts almost always simply result in a new sect of spore-blighted slaves.
