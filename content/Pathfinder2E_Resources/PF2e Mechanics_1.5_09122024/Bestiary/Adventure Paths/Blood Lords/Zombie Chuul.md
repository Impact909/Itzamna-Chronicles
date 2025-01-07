---
title: "Zombie Chuul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.59aTMTnSFbr5ABhc" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Zombie Chuul"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Zombie Chuul"
level: "Creature 7"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[zombie]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +11"
abilityMods: [7, 0, 6, -5, 0, -1]
speed: 30 feet,  swim 25 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +18, __Ref__ +10, __Will__ +13"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 15, slashing 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Slow"
    desc: "  The zombie chuul is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (reach 10 feet)\n__Damage__  2d12 + 12 slashing plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+7 bludgeoning damage, DC 25 Fortitude check ([[Conditions/Grabbed|Grabbed]] by claw only)\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Mandibles"
    desc: "`pf2:1`  **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] and [[Conditions/Paralyzed|Paralyzed]] by the zombie chuul's tentacles\n* * *\n\n**Effect** The creature takes 3d6 piercing damage."

  - name: "Paralytic Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 25 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "Tentacle Transfer"
    desc: "`pf2:1`  **Requirements** The zombie chuul has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The zombie chuul transfers the grabbed creature from its claws to its tentacles, or vice versa. The creature is exposed to the zombie chuul's paralytic venom when transferred into the tentacles and at the start of each of the zombie chuul's turns if it remains grabbed by the tentacles."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zombie Chuul
creatures:
  - 1: Zombie Chuul
```




