---
title: "Grave Karina"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QuRKplJwYRo9mSho" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Grave Karina"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Grave Karina"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Necril; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +21, Deception: +22, Stealth: +24"
abilityMods: [4, 7, 4, -1, 2, 7]
speed: 10 feet,  fly 50 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +24, __Will__ +19"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a grave karina's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from smoke, including the ash they create with their Breath Weapon."

  - name: "Sound Imitation"
    desc: "  A grave karina who succeeds at a Deception check to Lie can mimic any voice they have heard. They have a +4 circumstance bonus to this check."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+24 (magical, reach 10 feet, unholy)\n__Damage__  2d10 + 16 piercing plus grave-blight"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile, magical, unholy)\n__Damage__  2d8 + 13 slashing plus grave-blight"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+24 (magical, unholy)\n__Damage__  2d6 + 13 piercing plus grab"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,fire) The grave karina breathes a cloud of burning ash in 30-foot cone that deals 9d8 fire damage (DC 30 Reflex check save). The area becomes filled with ash for 1 round. All creatures within the cloud of ash become [[Conditions/Concealed|Concealed]], and all creatures outside the cloud become concealed to creatures within it. The grave karina can't use Breath Weapon again for 1d4 rounds."

  - name: "Grave Blight"
    desc: " (disease) **Saving Throw** DC 27 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 poison damage, and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** 2d8 poison damage, every hour the victim must succeed at another Fortitude save or be [[Conditions/Confused|Confused]] for 1 minute, and [[Conditions/Sickened|Sickened 2]] (1 day)"

  - name: "Mocking Cry"
    desc: "`pf2:1` (auditory) The grave karina mimics a voice and mocks a creature within 30 feet. They attempt a Deception check to Demoralize the creature. Regardless of whether the check succeeds, the target is temporarily immune to the grave karina's mocking cry for 1 hour."

  - name: "Shadow Command"
    desc: "`pf2:2` (concentrate,manipulate) **Frequency** once per day **Requirements** The grave karina is adjacent to a creature that's casting a shadow\n* * *\n\n**Effect** The grave karina drives a talon into a creature's shadow and attempts to manipulate it like a puppet with the effects of [[Spells/Dominate|Dominate]](DC 27 Will check save), except the duration is only 1 minute."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Grave Karina
creatures:
  - 1: Grave Karina
```




