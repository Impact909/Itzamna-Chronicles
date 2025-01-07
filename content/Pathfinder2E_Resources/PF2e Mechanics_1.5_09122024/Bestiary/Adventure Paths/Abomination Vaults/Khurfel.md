---
title: "Khurfel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SDRm2yNS5GkZroYz" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Khurfel"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Khurfel"
level: "Creature 10"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[urdefhan]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Greater Darkvision"
languages: "Aklo, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Intimidation: +19, Survival: +20"
abilityMods: [5, 4, 3, 0, 5, 4]
speed: 25 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +19, __Will__ +22"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200, void healing; __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Rhoka Sword|+1 Striking Rhoka Sword]], [[Equipment/Chain Mail|Chain Mail]], [[Equipment/Emerald Fulcrum Lens|Emerald Fulcrum Lens]], 10x [[Equipment/Bolts|Bolts]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Necrotic Decay"
    desc: " (divine,void) When Khurfel dies, his invisible flesh quickly rots away and sublimates into a foul-smelling gas that fills a 10-foot emanation around his body. The gas deals 10d6 void damage to creatures in this area as their flesh too curdles and rots (DC 28 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rhoka Sword"
    desc: "+24 (deadly 2d8, magical, two-hand d10)\n__Damage__  2d8 + 11 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 ()\n__Damage__  2d8 + 11 piercing plus wicked-bite"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+22 (range increment 120 feet, reload 2)\n__Damage__  1d10 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 28, attack +20; __4th __ (2 slots) _[[Spells/Harm|Harm]]_, _[[Spells/Read Omens|Read Omens]]_; __3rd __ (2 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __ (2 slots) _[[Spells/Augury|Augury]]_, _[[Spells/Death Knell|Death Knell]]_; __1st __ (1 slots) _[[Spells/Gentle Landing|Feather Fall (At Will) (Self Only)]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_"

  - name: "Frenzied Attack"
    desc: "`pf2:2`  Khurfel makes one rhoka sword Strike and two jaws Strikes against one or two different creatures (splitting up the attacks any way he wishes).\n\nHis multiple attack penalty doesn't increase until after all three attacks."

  - name: "Insightful Swing"
    desc: "`pf2:2`  Khurfel makes a melee weapon Strike. On this Strike, he gains a +2 circumstance bonus to the attack roll and ignores any concealment the target has."

  - name: "Wicked Bite"
    desc: "`pf2:1`  **Requirements** Khurfel damaged a creature with a jaws Strike on his last action\n* * *\n\n**Effect** Khurfel maintains contact, turning the creature's flesh translucent around the injury. Khurfel chooses one of two options, each of which requires a DC 28 Fortitude check save. If the jaws Strike was a critical hit, the creature suffers both effects, using the same save result for both.\n\n*   Drain Blood Khurfel drinks some of the creature's blood. On a failed save, the creature is [[Conditions/Drained|Drained 1]] and Khurfel regains 10 healing HP (or, on a critical failure, it's [[Conditions/Drained|Drained 2]] and Khurfel regains 20 healing HP).\n*   Drain Vitality Khurfel draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a critical failure)."
 
```

```encounter-table
name: Khurfel
creatures:
  - 1: Khurfel
```


Male urdefhan war champion

Khurfel leads the largest and most active group of adversaries the heroes face in the Abomination Vaults. His fated confrontation with the heroes is necessary because he holds the Emerald Fulcrum Lens and refuses to give it up as long as he lives, as it symbolizes the leadership of his cult. Khurfel's vision of falling at the heroes' hands doesn't inspire fear-it inspires fury, and he fights against his prophesized enemies as long as breath remains in his body.
