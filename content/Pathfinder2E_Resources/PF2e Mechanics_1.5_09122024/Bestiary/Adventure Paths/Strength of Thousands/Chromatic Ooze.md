---
title: "Chromatic Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fgf6fJOqEIsPUoW1" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Chromatic Ooze"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Chromatic Ooze"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Motion Sense (Precise) 240 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +35"
abilityMods: [9, -5, 10, -5, 0, -5]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +33, __Ref__ +16, __Will__ +20"
hp: 550
health:
  - name: ""
  - name: HP
    desc: "550; __Immunities__  critical hits,  precision,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Caustic Aura"
    desc: " (alchemical,aura,olfactory) 90 feet. The chromatic ooze emanates noxious chemicals into the environment. A creature that enters the aura or starts its turn within it is [[Conditions/Sickened|Sickened 1]] unless it succeeds at a DC 37 Fortitude check save. Creatures with the scent ability or a particularly heightened sense of smell are [[Conditions/Sickened|Sickened 2]], or sickened 1 on a successful Fortitude save. Creatures in the aura can't recover from the sickened condition."

  - name: "Chromatic Shift"
    desc: "`pf2:r`  **Trigger** The chromatic ooze takes acid, cold, electricity, fire, or poison damage\n* * *\n\n**Effect** The chromatic ooze changes its color based on the triggering damage (to dark green, pale blue, dark blue, red, or light green, respectively) and gains resistance 20 to the triggering damage. If it already had resistance to another damage type from this ability, it loses the resistance to that damage type and gains weakness 20 to it. If it already had weakness to another damage type from this ability, it loses that weakness. After 1 minute, the chromatic ooze returns to its usual rippling, multicolored hue and loses the resistance and weakness from this ability."

  - name: "Motion Sense"
    desc: "  A chromatic ooze can sense nearby motion through vibration and air movement."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+35 (reach 10 feet)\n__Damage__  3d10 + 17 bludgeoning plus chromatic-slam,improved-grab"

  - name: "Chromatic Slam"
    desc: "  The ooze's pseudopod Strikes deal an additional 2d10 damage of the same type it resists from its Chromatic Shift ability, if any."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d10+13 bludgeoning damage, DC 40 Fortitude check\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Pseudopod Eruption"
    desc: "`pf2:2`  The chromatic ooze concentrates its mass into several pseudopods, increasing its reach to 30 feet until the end of its turn. It then Strikes at up to four different creatures within its reach. This counts as two attacks for the ooze's multiple attack penalty, but the penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Chromatic Ooze
creatures:
  - 1: Chromatic Ooze
```



Chromatic oozes result from the worst kind of alchemical mishaps: attempts to combine as many types of elemental damage as possible into a single alchemical substance. Although the source of these alchemical concatenations are as varied as the alchemists who attempt to distill them, one of the most common methods for creating them involves combining the essences of multiple types of chromatic dragons together using eldritch alchemical processes. When this type of experimentation goes dangerously wrong-as it often does-the result is a combination of terrible elemental power with the mindless destructive power of an ooze. A chromatic ooze is a rippling, seething substance that shifts through several different colors, but chemical reactions within the ooze can lock its energy and its color into a specific phase for a short time. Whether a chromatic ooze's destructive urges derive from the frustrated ingenuity of an alchemist creator or from the hunger of the chromatic dragons that so often constitute these oozes' forms, the best way to deal with a chromatic ooze is to stay out of its way.
