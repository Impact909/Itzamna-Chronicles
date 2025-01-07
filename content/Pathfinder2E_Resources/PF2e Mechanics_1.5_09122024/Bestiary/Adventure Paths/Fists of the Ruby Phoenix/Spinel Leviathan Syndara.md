---
title: "Spinel Leviathan Syndara"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.agiqfjPNQDDlsCSa" 
tags:
  - pf2e/creature/type/aeon
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/24
statblock: inline
name: "Spinel Leviathan Syndara"
level: 24
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Spinel Leviathan Syndara"
level: "Creature 24"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[aeon]]
trait_02: [[evil]]
trait_03: [[lawful]]
trait_04: [[monitor]]
modifier: 46
perception:
  - name: "Perception"
    desc: "+46; "
languages: "Senzar, Taldane, Tien, Utopian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +45, Athletics: +48, Intimidation: +45, Demiplane Lore: +48"
abilityMods: [12, 9, 10, 8, 8, 7]
speed: 60 feet,  fly 60 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 51
armorclass:
  - name: AC
    desc: "51; __Fort__ +46, __Ref__ +38, __Will__ +42"
hp: 550
health:
  - name: ""
  - name: HP
    desc: "550; __Immunities__  emotion,  death effects,  disease,  fear effects"
abilities_top:
  - name: ""

  - name: "Center of the World"
    desc: " (divine,teleportation) **Trigger** A creature finishes moving, even if it moved using something other than a move action\n* * *\n\n**Effect** Syndara is the figurative and literal center of this world. As the triggering creature moves, space reasserts itself, teleporting Syndara to be in the same position relative to the creature as he was when the creature began its movement. If the space he would teleport into is occupied, he displaces the obstructing creature or object into the nearest available space."

  - name: "Keeper of the Lighthouse"
    desc: "  Syndara can choose whether he is affected by his worldspheres."

  - name: "Portal Redirection"
    desc: " (divine,teleportation) **Trigger** Syndara is targeted by a ranged Strike or spell attack roll\n* * *\n\n**Effect** Syndara opens a portal in front of the incoming missile, then opens another portal nearby that fires the missile at another creature within 60 feet of him. He takes no damage from the triggering attack and makes a ranged Strike with a +43 attack bonus. The Strike deals damage according to the triggering ability."

  - name: "Spatial Sense"
    desc: "  Syndara instinctively knows the position of all creatures and objects within the Glass Lighthouse as a precise sense. His senses do not extend into extraplanar spaces (such as a bag of holding), even if the entrance to these spaces is within the Lighthouse."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Extradimensional Immunity"
    desc: "  Syndara can foil any attempts to use planar powers against him. He is immune to all extradimensional effects, such as [[Spells/Quandary|Quandary]], but can choose to be affected by such effects normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spatial Pincers"
    desc: "+43 (magical, reach 15 feet, versatile s)\n__Damage__  7d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+43 (agile, magical, reach 20 feet)\n__Damage__  7d8 + 20 bludgeoning plus improved-grab"

  - name: "**Ranged** `pf2:1` Warpspines"
    desc: "+43 (agile, brutal, magical, propulsive, range increment 120 feet, splash)\n__Damage__  4d6 + 12 piercing 4d6 piercing"

  - name: "Dimensional Flurry"
    desc: "`pf2:2`  Syndara makes six Strikes. Any creature struck must succeed at a DC 46 Will check save or be teleported to a location of Syndara's choice within 60 feet of him when the flurry is complete. The teleportation has the conjuration, divine, and teleportation traits."

  - name: "Dimensional Grasp"
    desc: " (divine) Syndara's grasp extends across dimensions. Creatures grabbed by Syndara can't benefit from teleportation, extradimensional effects, or effects that would move them to a different plane."

  - name: "Mover of Worlds"
    desc: "`pf2:2` (divine) With great regret, Syndara calls his masterpieces from the firmament to crash down upon his enemies. He flings four worldspheres to any four points within 500 feet. Each worldsphere deals 20d6 damage in a 40-foot burst (DC 48 Reflex check save). Syndara chooses the type of damage for each worldsphere, which can be any type he chooses, though each worldsphere must deal a different type of damage. On a failed save, the target is pushed to the edge of the burst. No matter how many overlapping explosions it's caught in, a creature can take damage from only one worldsphere per round. Syndara is immune to the damage dealt by his worldspheres. Syndara can't use Mover of Worlds again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Spatial Pincers\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Spinel Leviathan Syndara
creatures:
  - 1: Spinel Leviathan Syndara
```




