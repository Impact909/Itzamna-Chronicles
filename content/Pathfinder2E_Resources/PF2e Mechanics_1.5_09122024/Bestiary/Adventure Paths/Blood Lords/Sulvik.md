---
title: "Sulvik"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Adhn6ByZHnpJTLpZ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Sulvik"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Sulvik"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Intimidation: +19, Stealth: +18"
abilityMods: [6, 3, 4, -2, 3, 4]
speed: 35 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +16, __Will__ +16"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ piercing 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Independent Brains"
    desc: "  Each of Sulvik's heads rolls its own initiative and has its own turn. Neither head can [[Actions/Delay|Delay]]. At the start of a head's turn, that head gets 2 actions and 1 reaction. Each brain controls its own tongue and one of Sulvik's arms, but both can move the legs. Any ability that would sever Sulvik's head (such as the _[[Equipment/Vorpal|Vorpal]]_ weapon property) doesn't cause him to die if he has his other head, but does cause him to lose the turns, actions, and reactions of the severed head. Mental effects that target a single creature affect only one of Sulvik's heads."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (reach 10 feet)\n__Damage__  2d10 + 12 slashing plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+21 (agile, reach 10 feet)\n__Damage__ "

  - name: "Mohrg Spawn"
    desc: "  When Sulvik kills a living creature of 8th level or less, that creature rises as a [[Bestiary 2/Mohrg|Mohrg]] after 1d4 rounds, on its turn. This mohrg spawn is under Sulvik's command. If Sulvik is destroyed, the mohrg spawn is destroyed as well, immediately collapsing into a pile of decayed flesh and bones."

  - name: "Paralysis"
    desc: " (incapacitation,occult) A living creature hit by Sulvik's tongue Strike must succeed at a DC 28 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. The creature can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each attempt."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sulvik
creatures:
  - 1: Sulvik
```


Variant ettin mohrg


