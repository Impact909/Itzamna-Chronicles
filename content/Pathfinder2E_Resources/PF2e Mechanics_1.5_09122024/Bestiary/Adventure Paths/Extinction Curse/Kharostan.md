---
title: "Kharostan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.llAmnW2wUU9HLA0c" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Kharostan"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Kharostan"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[humanoid]]
trait_04: [[unholy]]
trait_05: [[urdefhan]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Truesight"
languages: "Aklo, Common, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +31, Crafting: +25, Intimidation: +28, Religion: +27, Stealth: +28, Survival: +29, Black Desert Lore: +25"
abilityMods: [6, 6, 4, 1, 3, 4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +28, __Ref__ +30, __Will__ +25"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, void healing; __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|+1 Striking Composite Longbow]], [[Equipment/Rhoka Sword|+2 Greater Striking Rhoka Sword]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 40x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Necrotic Decay"
    desc: " (divine,void) When Kharostan dies, his daemon-tainted flesh quickly rots away and sublimates into a foul-smelling gas that fills a 10-foot emanation around his body.\n\nAll creatures within the area take 20d6 void damage as their flesh curdles and rots as well (DC 37 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rhoka Sword"
    desc: "+32 (fatal d10, magical, reach 10 feet, two-hand d12, unholy)\n__Damage__  3d8 + 12 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+31 (unholy)\n__Damage__  3d8 + 12 piercing plus wicked-bite"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+32 (deadly d10, magical, propulsive, range increment 100 feet, reload 0, unholy, volley 30 ft.)\n__Damage__  2d8 + 9 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __2nd __  _[[Spells/Death Knell|Death Knell]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall (At Will) (Self Only)]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Constant__  __(8th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Devastating Strikes"
    desc: "  Kharostan's melee Strikes ignore 10 points of a creature's resistance to physical damage."

  - name: "Furious Sprint"
    desc: "`pf2:2` (rage) Kharostan Strides up to five times his Speed in a straight line. He can increase the number of actions for this activity to 3 in order to Stride up to eight times his Speed in a straight line instead."

  - name: "Rage"
    desc: "`pf2:1` (concentrate,emotion,mental) **Requirements** Kharostan isn't [[Conditions/Fatigued|Fatigued]] or raging\n* * *\n\n**Effect** Kharostan gains 30 temporary Hit Points that last until the rage ends. While raging, he deals an additional 12 damage with melee attacks and takes a -1 penalty to AC.\n\nKharostan can't use concentrate actions except Seek and actions with the rage trait. The rage lasts for 1 minute, until there are no enemies Kharostan can perceive, or until Kharostan falls unconscious. Once the rage ends, Kharostan can't again for 1 minute.\n\n[[Feat_Feature Effects/Effect_ Rage|Effect: Rage]]"

  - name: "Reckless Abandon"
    desc: " (rage) **Trigger** Kharostan's turn begins and he has 140 or fewer Hit Points\n* * *\n\n**Effect** Kharostan throws caution to the wind to finish the fight. He gains a +2 status bonus to attack rolls, a -2 status penalty to AC, and a -1 status penalty to saves. He can also make a Wicked Bite each time he damages a creature with his jaws Strike, in addition to the usual once per round usage for a free action. These effects last until his rage ends or he has more than 140 Hit Points, whichever comes first."

  - name: "Wicked Bite"
    desc: "  **Trigger** Kharostan damages a creature with a jaws Strike\n\n**Frequency** once per round\n* * *\n\n**Effect** Kharostan's bite leaves the victim's flesh translucent around the site of the injury. He chooses one of the effects below, each of which requires the damaged creature to attempt a DC 37 Fortitude check save.\n\nIf the jaws Strike was a critical hit, the creature takes both effects, rolling the saving throw once and using the result for both effects.\n\n*   **Drain Blood** Kharostan drinks some of the victim's blood. On a failed save, the victim is [[Conditions/Doomed|Doomed 1]] and [[Conditions/Drained|Drained 1]], and Kharostan regains 20 healing HP (on a critical failure, the creature is [[Conditions/Doomed|Doomed 2]] and [[Conditions/Drained|Drained 2]], and Kharostan regains 40 healing HP).\n*   **Drain Vitality** (necromancy) Kharostan draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 3]] for 1 hour on a critical failure)."
 
```

```encounter-table
name: Kharostan
creatures:
  - 1: Kharostan
```


Male urdefhan war champion


