---
title: "Hezrou"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t4eGFTo1r5RnfKvC" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Hezrou"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Hezrou"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[demon]]
trait_04: [[evil]]
trait_05: [[fiend]]
trait_06: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +21, Athletics: +24, Intimidation: +23, Stealth: +20"
abilityMods: [7, 3, 6, 4, 5, 4]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +18, __Will__ +22; +1 to all saves vs. magic"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Purity Vulnerability"
    desc: " (mental) A hezrou revels in the foulness it exudes and becomes distraught when contaminations are purified. The first time in a round when a contamination is purified (such as via purify food and drink) or a toxin is neutralized (such as via neutralize poison) within 30 feet of a hezrou, the demon takes 6d6 mental damage."

  - name: "Stench"
    desc: " (aura,disease,olfactory) 30 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 27 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as itʼs sickened on a critical failure).\n\nWhile within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (magical, reach 10 feet, unholy)\n__Damage__  2d12 + 13 piercing plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 13 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +17; __6th __  _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Paranoia|Paranoia]]_; __5th __  _[[Spells/Abyssal Plague|Abyssal Plague]]_, _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_, _[[Spells/Divine Wrath|Divine Wrath (At will)]]_, _[[Spells/Vapor Form|Gaseous Form]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_, _Blight_"

  - name: "Poisonous Pustules"
    desc: "`pf2:1` (poison) **Requirements** The hezrou is grappling a creature\n* * *\n\n**Effect** Toxic fluids spurt from burst boils and weeping wens on the hezrou's body. A creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the hezrou takes 2d12+6 poison damage (DC 30 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Hezrou
creatures:
  - 1: Hezrou
```



Hezrous dwell in the vast and endless Abyssal swamps, mires, and waterways and are equally at home on land and in the water. A hezrou's presence has an obvious effect on nearby flora and water, causing plant life to twist and knot and infusing water with a foul odor and brackish taste-signs much easier to spot on the Material Plane than in the Abyss. Long exposure to this corruption can cause vile transformations and hideous mutations, and entire miserable communities of corrupted creatures sometimes rise in swamplands where a hezrou dwells. Hezrous themselves prefer simple pleasures, and they often waste their considerable intellect in the pursuit of comfortable places to slumber, squealing meals to eat, or objects of beauty to deface. They do not seek out cults to fawn over them but will not turn away those who seek to worship on their own. Hezrous form from the souls of those who abused and polluted their environs or neighbors, either through the introduction of toxins to the region or the insidious spread of drugs and poisons through a society.
