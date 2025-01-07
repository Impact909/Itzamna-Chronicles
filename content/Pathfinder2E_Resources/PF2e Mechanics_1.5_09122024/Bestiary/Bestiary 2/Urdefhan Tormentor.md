---
title: "Urdefhan Tormentor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kZRKtwUlRo27bpwW" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Urdefhan Tormentor"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Urdefhan Tormentor"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[urdefhan]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Greater Darkvision"
languages: "Aklo, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Crafting: +9, Intimidation: +11, Occultism: +11, Religion: +13"
abilityMods: [3, 1, 3, 2, 4, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +10, __Will__ +15"
hp: 77
health:
  - name: ""
  - name: HP
    desc: "77, (void healing); __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|Warhammer]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Necrotic Decay"
    desc: " (divine,void) When an urdefhan dies, its invisible flesh quickly rots away and sublimates into a foul-smelling gas that fills a 5-foot emanation around the body.\n\nThis gas deals 5d6 void damage to creatures in this area as their flesh curdles and rots as well (DC 21 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+12 (shove)\n__Damage__  1d8 + 5 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d6 + 5 piercing plus wicked-bite"

  - name: "Divine Innate Spells"
    desc: "DC 23, attack +15; __3rd __  _[[Spells/Harm|Harm (x3)]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Death Knell|Death Knell]]_, _[[Spells/False Vitality|False Life]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall (Self only)]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_"

  - name: "Rituals"
    desc: "_Daemonic Pact_"

  - name: "Stoke the Fervent"
    desc: "`pf2:2` (auditory,divine,emotion,mental) **Frequency** once per day\n* * *\n\n**Effect** The urdefhan lets out a battle cry, sending itself and its allies into a fanatical frenzy. Each ally that hears the call gains a +1 status bonus to attack rolls, damage rolls, and saving throws, and takes a -1 status penalty to AC. Affected allies must use at least one of their actions to Strike each round, if they are able (even if it means attacking an ally, object, or thin air).\n\nThis lasts for [[/gmr 2d4 #rounds]]{2d4 rounds}.\n\n[[Bestiary Effects/Effect_ Stoke the Fervent|Effect: Stoke the Fervent]]"

  - name: "Wicked Bite"
    desc: "`pf2:1`  **Requirements** The urdefhan damaged a creature with a jaws Strike on its last action\n* * *\n\n**Effect** The urdefhan maintains contact, turning the creature's flesh translucent around the site of the injury. The urdefhan chooses one of two options, each of which requires a DC 22 Fortitude check save. If the jaws Strike was a critical hit, the creature suffers both effects, using the same save result for both.\n\n*   **Drain Blood** The urdefhan drinks some of the creature's blood. On a failed save, the creature is [[Conditions/Drained|Drained 1]] and the urdefhan regains 5 healing HP (or, on a critical failure, it's [[Conditions/Drained|Drained 2]] and the urdefhan regains 10 healing HP).\n*   **Drain Vitality** The urdefhan draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a critical failure)."
 
```

```encounter-table
name: Urdefhan Tormentor
creatures:
  - 1: Urdefhan Tormentor
```



Urdefhan spellcasters with a knack for the divine are invariably unholy worshippers of daemonkind, typically taking on one of Abaddon's Four Horsemen of the Apocalypse as their patron deity. With their unholy gifts, these urdefhan tormentors summon daemons into battle and bolster their allies with profane magic, preferring to stick to the sidelines rather than enter the fray directly.
