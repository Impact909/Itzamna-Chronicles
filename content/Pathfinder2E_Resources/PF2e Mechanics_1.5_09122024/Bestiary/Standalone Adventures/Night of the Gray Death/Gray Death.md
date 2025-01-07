---
title: "Gray Death"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.An6Bi8tU3dvpeQLO" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Gray Death"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Gray Death"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Lifesense 1 Feet"
languages: "Common; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Intimidation: +40, Occultism: +34, Performance: +38, Society: +34"
abilityMods: [-5, 7, 4, 6, 7, 10]
speed:  fly 60 feet
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +31, __Ref__ +35, __Will__ +33"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Immunities__  disease,  fear effects,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ mental 15; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 1,000 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Soul Bleed"
    desc: " (aura,occult) 1000 feet. Creatures that begin their turn in the area take 5d6 void damage and must succeed at a DC 42 Fortitude check save or become [[Conditions/Doomed|Doomed 1]]. If the creature is 13th level or lower, this doomed condition from soul bleed is cumulative, increasing by 1 with each failed save until the creature dies (typically at doomed 4)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hand"
    desc: "+38 (finesse, magical, reach, reach 15 feet)\n__Damage__  4d10 + 16 void plus life-sap"

  - name: "Flailing Touch"
    desc: "`pf2:2`  The gray death makes up to four hand Strikes, each against a different target it can reach. It increases its reach to 100 feet with these Strikes. These Strikes count as one attack for the gray death's multiple attack penalty, and the penalty doesn't increase until after the attacks."

  - name: "Life Sap"
    desc: "  A creature damaged by the gray death's hand Strike must succeed at a DC 42 Fortitude check save or become [[Conditions/Drained|Drained 1]], and [[Conditions/Paralyzed|Paralyzed]] for 1 round on a critical failure."

  - name: "Resentful Possession"
    desc: "`pf2:1` (curse,mental,occult,possession) **Frequency** once per round\n* * *\n\n**Effect** The gray death chooses a living creature within 30 feet. The target must succeed at a DC 42 Will check save or a fragment of embittered soul-stuff lodges within the target's spirit and turns it against its allies. While the target has this fragment, it doesn't count as anyone's ally for the purposes of providing flanking, and a would-be ally casting a spell that normally works only on an ally on the creature must succeed at a DC 42 counteract check (level 20) or the spell has no effect. The fragment fades after 24 hours."

  - name: "Spectral Lurker"
    desc: "  The gray death isn't [[Conditions/Slowed|Slowed 1]] when it starts its turn inside an object."
 
```

```encounter-table
name: Gray Death
creatures:
  - 1: Gray Death
```




