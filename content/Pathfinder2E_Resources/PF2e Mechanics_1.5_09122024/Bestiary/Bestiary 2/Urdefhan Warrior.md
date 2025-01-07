---
title: "Urdefhan Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9Aj95HnVapzvKsVU" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Urdefhan Warrior"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Urdefhan Warrior"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[urdefhan]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Greater Darkvision"
languages: "Aklo, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Intimidation: +9, Religion: +7, Survival: +7"
abilityMods: [3, 1, 2, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +8, __Will__ +9"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55, (void healing); __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Rhoka Sword|Rhoka Sword]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Necrotic Decay"
    desc: " (divine,void) When an urdefhan dies, its invisible flesh quickly rots away and sublimates into a foul-smelling gas that fills a 5-foot emanation around the body.\n\nThis gas deals 3d6 void damage to creatures in this area as their flesh curdles and rots as well (DC 17 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rhoka Sword"
    desc: "+12 (deadly d8, two-hand d10)\n__Damage__  1d8 + 6 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  1d6 + 6 piercing plus wicked-bite"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+10 (deadly d10, propulsive, range increment 100 feet, volley 30 ft.)\n__Damage__  1d8 + 4 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __2nd __  _[[Spells/Death Knell|Death Knell]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall (Self only)]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_"

  - name: "Ravenous Attack"
    desc: "`pf2:2`  The urdefhan makes one rhoka sword Strike and one jaws Strike against a single creature. Its multiple attack penalty doesn't increase until after both attacks."

  - name: "Wicked Bite"
    desc: "`pf2:1`  **Requirements** The urdefhan damaged a creature with a jaws Strike on its last action\n* * *\n\n**Effect** The urdefhan maintains contact, turning the creature's flesh translucent around the site of the injury. The urdefhan chooses one of two options, each of which requires a DC 20 Fortitude check save. If the jaws Strike was a critical hit, the creature suffers both effects, using the same save result for both.\n\n*   **Drain Blood** The urdefhan drinks some of the creature's blood. On a failed save, the creature is [[Conditions/Drained|Drained 1]] and the urdefhan regains 5 healing HP (or, on a critical failure, it's [[Conditions/Drained|Drained 2]] and the urdefhan regains 10 healing HP).\n*   **Drain Vitality** The urdefhan draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a critical failure)."
 
```

```encounter-table
name: Urdefhan Warrior
creatures:
  - 1: Urdefhan Warrior
```



From the moment they are born, urdefhans are prepared for war. Urdefhan warriors are among the least powerful urdefhans one might encounter outside of their eerie underground cities.
