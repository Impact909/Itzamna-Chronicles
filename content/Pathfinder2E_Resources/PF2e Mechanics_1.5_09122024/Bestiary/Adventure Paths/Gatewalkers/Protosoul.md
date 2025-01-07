---
title: "Protosoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.S3MQs60Z7OgNYopl" 
tags:
  - pf2e/creature/type/divine
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Protosoul"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #189: Dreamers of the Nameless Spires"
name: "Protosoul"
level: "Creature 11"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[divine]]
trait_02: [[mindless]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Lifesense"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22"
abilityMods: [5, 5, 7, -5, 0, -5]
speed:  fly 40 feet
sourcebook: "_Pathfinder #189: Dreamers of the Nameless Spires_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +22, __Will__ +17"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  void,  nonlethal attacks,  paralyzed,  poison,  sickened,  unconscious,  mental"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Absorb Necromancy"
    desc: "  A protosoul is made of necromantic energy. Any time it would be affected by another creature's non-cantrip necromancy spell, after applying its immunity, it also regains 10 healing Hit Points."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Necromantic Tendril"
    desc: "+22 (divine, magical, reach 10 feet)\n__Damage__  3d10 + 11 force"

  - name: "**Ranged** `pf2:1` Necromantic Bolt"
    desc: "+22 (divine, magical, range increment 30 feet)\n__Damage__  2d10 + 11 force"

  - name: "Divine Innate Spells"
    desc: "DC 30, attack +22; __5th __  _[[Spells/Harm|Harm (At Will, see Unstable Magic)]]_; __4th __  _[[Spells/Enervation|Enervation (At Will, see Unstable Magic)]]_; __3rd __  _[[Spells/Sudden Blight|Sudden Blight (At Will, see Unstable Magic)]]_\n__Cantrips__  __(6th)__ _[[Spells/Void Warp|Chill Touch]]_"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 30 Reflex check, 2d8 force damage plus 3d8 void damage, [[Actions/Escape|Escape]] DC 30, Rupture 25\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Unstable Magic"
    desc: "  The roiling protosoul can't be healed or Repaired, and is destroyed at 0 Hit Points. So long as it is not destroyed, it naturally recovers 77 healing Hit Points each day. Each time a roiling protosoul casts one of its non-cantrip spells, it drains its own magic to do so, taking 6 force damage."
 
```

```encounter-table
name: Protosoul
creatures:
  - 1: Protosoul
```


Variant roiling incant

Though many spellcasters can harness the forces of magic in a consistent manner, such power can't always be controlled, especially in the hands of reckless researchers, megalomaniacal villains, or untested novices. When magical accidents result in large-scale property damage and the loss of life, these forces sometimes take on lives of their own, forming a dangerous amalgamation of ongoing magical energy known as a roiling incant.

A roiling incant's appearance depends on the type of magic it sprang forth from, though it always carries with it an echo of the destruction it has caused. A fiery evocation roiling incant might look like a storm of burning ashes echoing with the sounds of crackling timber, while a necromancy roiling incant could be mistaken for ghostly tendrils puppeteering shambling corpses. No matter what it looks like, a roiling incant roams mindlessly, attacking everything it encounters, heedless of further carnage it causes.
