---
title: "Urdefhan Lasher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.io1WBprbXfU5LB4Z" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Urdefhan Lasher"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Urdefhan Lasher"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[urdefhan]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Greater Darkvision"
languages: "Aklo, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Intimidation: +13, Religion: +14, Survival: +14"
abilityMods: [5, 3, 4, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +14, __Will__ +16"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, void healing; __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shauth Lash|Shauth Lash]], [[Equipment/Chain Shirt|Chain Shirt]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Necrotic Decay"
    desc: " (divine,void) When an urdefhan dies, its invisible flesh quickly rots away and sublimates into a foul-smelling gas that fills a 5-foot emanation around the body.\n\nThis gas deals 7d6 void damage to creatures in this area as their flesh curdles and rots as well (DC 24 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shauth Lash"
    desc: "+18 (deadly d8, trip)\n__Damage__  2d8 + 7 slashing plus grab,wicked-bite"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 ()\n__Damage__  2d6 + 7 piercing plus wicked-bite"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +14; __3rd __  _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Death Knell|Death Knell]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall (At Will) (Self Only)]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+7 slashing damage, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Shauth Seize"
    desc: "  The lasher gains the [[Bestiary Ability Glossary/Grab|Grab]] ability with a shauth lash and can use their Wicked Bite through magical shauth weapon Strikes."

  - name: "Wicked Bite"
    desc: "`pf2:1`  **Requirements** The urdefhan damaged a creature with a jaws Strike on its last action\n* * *\n\n**Effect** The urdefhan maintains contact, turning the creature's flesh translucent around the site of the injury. The urdefhan chooses one of two options, each of which requires a fortitude save. If the jaws Strike was a critical hit, the creature suffers both effects, using the same save result for both.\n\n*   **Drain Blood** DC 25 Fortitude check The urdefhan drinks some of the creature's blood. On a failed save, the creature is [[Conditions/Drained|Drained 1]] and the urdefhan regains 10 healing HP (or, on a critical failure, it's [[Conditions/Drained|Drained 2]] and the urdefhan regains 20 healing HP).\n*   **Drain Vitality** (necromancy) DC 25 Fortitude check The urdefhan draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Urdefhan Lasher
creatures:
  - 1: Urdefhan Lasher
```



Trained from a young age with the strange and powerful shauth lashes, urdefhan lashers would rather die than retreat from combat.

* * *

Translucent-skinned scourges of the Darklands, urdefhans are remorseless killers and foot soldiers of the world's end.
