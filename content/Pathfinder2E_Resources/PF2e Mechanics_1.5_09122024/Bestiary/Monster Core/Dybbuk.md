---
title: "Dybbuk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9tXCtFoRwZQsO6sD" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Dybbuk"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dybbuk"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[spirit]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Aklo, Chthonian, Common; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Deception: +31, Diplomacy: +27, Intimidation: +29, Stealth: +28"
abilityMods: [-5, 7, 0, 1, 6, 8]
speed:  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +21, __Ref__ +28, __Will__ +29"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 10 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 33 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+28 (agile, finesse, magical, unholy)\n__Damage__  3d10 + 14 void 2d6 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +30; __6th __  _[[Spells/Dominate|Dominate]]_, _[[Spells/Never Mind|Never Mind]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_; __5th __  _[[Spells/Chilling Darkness|Chilling Darkness (x2)]]_, _[[Spells/Fear|Fear]]_; __4th __  _[[Spells/Rewrite Memory|Rewrite Memory]]_; __3rd __  _[[Spells/Fear|Fear (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Malevolent Possession"
    desc: "`pf2:2` (incapacitation,mental,occult,possession) The dybbuk attempts to possess an adjacent corporeal creature. This has the same effect as the [[Spells/Possession|Possession]] spell (DC 34 Will check) with an unlimited duration, except since the dybbuk doesn't have a physical body, they aren't [[Conditions/Unconscious|Unconscious]], and aren't [[Conditions/Paralyzed|Paralyzed]] when the effect ends, though they take 5d6 spirit damage if the body is knocked unconscious or killed.\n\nIf the dybbuk took control of the target with Malevolent Possession, when the dybbuk departs, the target has only incoherent memories of the interval it was possessed."
 
```

```encounter-table
name: Dybbuk
creatures:
  - 1: Dybbuk
```



The discorporated spirits called dybbuks arise from souls denied respite in the afterlife, often because they committed some great transgression in life. These spirits are said to cling to life through possessing victims to escape the punishment awaiting them in the afterlife. Only by trapping, cowing, or destroying such spirits can a mortal hope to drive them back.

Dybbuks, who are most often the spirits of men, hide within possessed victims. Their targets of possession are usually young women on the eve of their wedding nights, which can be seen as an omen of an ill-fitting match, particularly in arranged marriages. Male and nonbinary victims do exist as well, though in lesser quantities, and also often on the eve of a troubled marriage. No one knows for sure why dybbuks are drawn to such situations, though it may be because the transgressive soul of a dybbuk seeks to bring chaos to the most strictly regimented aspects of society.

A victim possessed by a dybbuk might be loud and crude, refuse to eat or drink, perform profane acts, or otherwise stir up trouble in the victim's household. The possessed victim has no memory of these events after their possession ends.

Certain classes of specially trained priests can expel dybbuks from their victims through exorcism. Typically, this uses a methodology combining smoke, the blowing of a horn from a ram, and the recitation of holy verses. Exorcisms are, however, extremely difficult and dangerous, and require great knowledge and skill on the part of the priest due to the power of these malevolent spirits.
