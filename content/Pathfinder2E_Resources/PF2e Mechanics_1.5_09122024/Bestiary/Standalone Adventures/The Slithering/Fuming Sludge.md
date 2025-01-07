---
title: "Fuming Sludge"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ncKIGBMtD8YIch7N" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Fuming Sludge"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Fuming Sludge"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +19"
abilityMods: [6, -3, 5, -5, 0, -5]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +18, __Ref__ +8, __Will__ +11"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160; __Immunities__  critical hits,  fire,  piercing,  precision,  slashing,  unconscious,  visual,  mental; __Weaknesses__ cold 5"
abilities_top:
  - name: ""

  - name: "Chemical Sense 60 feet"
    desc: "  A fuming sludge detects nearby living and undead creatures by their complex chemical compositions, but it can't detect elementals or other creatures composed of a single element."

  - name: "Smoldering Haze"
    desc: " (aura,fire) 15 feet. The fuming sludge constantly emits incendiary smoke that creates [[Conditions/Concealed|Concealment]] around it. The smoke doesn't impair the fuming sludge's chemical sense. A creature that enters the aura or begins its turn in the aura becomes [[Conditions/Sickened|Sickened 1]] (DC 25 Fortitude check negates) and cannot recover from [[Conditions/Persistent Damage|Persistent Fire Damage]] for 1 round. It is then temporarily immune to the sickening effect of the smoldering haze for 1 minute.\n\nA creature that is currently holding its breath, that doesn't need to breathe, or that's immune to poison is immune to the aura's sickened effect but not the concealment or inability to recover from persistent fire damage."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+17 ()\n__Damage__  2d10 + 6 bludgeoning plus grab 1d8 fire plus grab"

  - name: "**Ranged** `pf2:1` Ejected Glob"
    desc: "+17 (brutal, range increment 20 feet)\n__Damage__  3d6 + 6 bludgeoning plus cooling-glob 1d8 fire plus cooling-glob"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+6 bludgeoning plus 1d8 persistent fire, DC 24 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Cooling Glob"
    desc: "  A fuming sludge's ejected globs cling to targets.\n\nA creature hit by an ejected glob Strike is [[Conditions/Encumbered|Encumbered]] for 1 round.\n\nIf the attack was a critical hit, the creature is instead [[Conditions/Restrained|Restrained]] for 1 round ([[Actions/Escape|Escape]] DC 24)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Fuming Sludge
creatures:
  - 1: Fuming Sludge
```



The slurry from alchemical experiments is often as flammable as it is toxic. In especially volatile cases, a fuming sludge can form from ignited pools of unstable alchemical runoff. It resembles a charcoal-colored slurry studded with tiny embers, and it continually emits a thin haze of accelerant that amplifies the fires it starts.

A fuming sludge must consume the base chemicals of living creatures to survive and can instinctively identify the complex molecules found in most animate creatures. The first meal of many a fuming sludge is its accidental creator, but it soon moves on to hunt in lush forests or densely populated settlements. A fuming sludge can extrude a powerful pseudopod to strike its victims, but it can also eject portions of its body with peristaltic contractions. These rapidly-cooling globs of goo slow down fleeing prey, but the cold, crusty residue can also alert canny explorers to their presence.
