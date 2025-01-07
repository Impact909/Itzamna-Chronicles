---
title: "Corrupted Nosoi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WYpNKUQiIrE7BccQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Corrupted Nosoi"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Malevolence"
name: "Corrupted Nosoi"
level: "Creature 2"
rare_03: [[Rare]]
alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[monitor]]
trait_03: [[psychopomp]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Stealth: +8"
abilityMods: [-1, 3, 1, 1, 2, 3]
speed: 15 feet,  fly 40 feet
sourcebook: "_Pathfinder Adventure: Malevolence_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +10, __Will__ +8"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28, void healing; __Immunities__  death effects,  disease; __Weaknesses__ slashing 3; __Resistances__ void 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: " (divine) Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+8 (finesse, magical)\n__Damage__  1d4 + 1 piercing plus corrupted-touch"

  - name: "Corrupted Touch"
    desc: "  A corrupted nosoi's Strikes deal 1d6 void damage to living creatures. A creature critically hit by a corrupted nosoi's Strike must attempt a DC 18 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure) as rot spreads through their flesh."

  - name: "Haunting Melody"
    desc: "`pf2:1` (auditory,concentrate,divine,incapacitation,mental) The nosoi croons \"_the Lord slumbers below, you're nothing but his dreams, and when the lord awakes, you'll know the end of things!_\". Each living or undead creature within a 60-foot emanation must attempt a DC 18 Will check save. The effect lasts for 1 round, but a nosoi can use this ability again on subsequent rounds to extend the duration by 1 round for all affected creatures. A creature that succeeds at any save is temporarily immune for 24 hours. Despite being a mental effect, this ability affects mindless undead. Psychopomps are immune to this ability.\n* * *\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]].\n\n**Critical Failure** As failure, and the creature must spend each of its actions on its turn to move closer to the nosoi as expediently as possible while avoiding obvious dangers. If a [[Conditions/Fascinated|Fascinated]] creature is adjacent to the nosoi, it stays still and doesn't act. If the creature is attacked, the fascination ends."
 
```

```encounter-table
name: Corrupted Nosoi
creatures:
  - 1: Corrupted Nosoi
```




