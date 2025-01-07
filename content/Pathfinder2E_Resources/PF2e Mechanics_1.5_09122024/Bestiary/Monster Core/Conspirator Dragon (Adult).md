---
title: "Conspirator Dragon (Adult)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VaCoswkMLwcIC8Aq" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/occult
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Conspirator Dragon (Adult)"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Conspirator Dragon (Adult)"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[occult]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Shadowtongue, Sussuran; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +23, Deception: +25, Diplomacy: +25, Intimidation: +23, Occultism: +23, Performance: +25, Society: +23, Stealth: +21, Lore (any one region or settlement): +25"
abilityMods: [5, 3, 4, 5, 5, 7]
speed: 40 feet,  climb 40 feet,  fly 140 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +20, __Ref__ +21, __Will__ +25; +2 status to all saves vs. occult"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  controlled,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Retract Body"
    desc: "`pf2:r`  **Trigger** The dragon is hit or critically hit by an attack made by a creature the dragon can see\n* * *\n\n**Effect** The dragon retracts the targeted body part or twists away to avoid the attack, gaining a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (magical, reach 10 feet)\n__Damage__  3d8 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile, magical)\n__Damage__  3d6 + 11 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+23 (magical, reach 15 feet)\n__Damage__  2d10 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Mental Blast"
    desc: "+25 (mental, range 100 feet)\n__Damage__  3d6 + 6 mental"

  - name: "Occult Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Charm|Charm]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_; __1st __  _[[Spells/Charm|Charm (At Will)]]_"

  - name: "Conjure Disguise"
    desc: " (manipulate,occult,polymorph) **Frequency** once per day\n* * *\n\n**Effect** The dragon conjures a perfect flesh-suit replica of a humanoid they've seen of their size or smaller and compresses themself into it, along with generating appropriate clothing for the humanoid. This process takes 1 minute to complete, during which the dragon is [[Conditions/Off-Guard|Off-Guard]]. If the dragon stops or is interrupted in this process, the suit is destroyed. Once the process is complete, the dragon can remain in this disguise indefinitely.\n\nThe transformation has the effects of [[Bestiary Ability Glossary/Change Shape|Change Shape]], except that the disguise is not actively magical in nature and doesn't register as magical to detect magic and similar effects. The dragon loses Retract Body while transformed.\n\nIf the dragon is critically hit while wearing the disguise, the suit is destroyed and immediately explodes. This has the effects of Detonate Disguise, except that creatures use the outcome one degree of success better than they rolled on their save."

  - name: "Detonate Disguise"
    desc: "`pf2:2` (occult) **Requirements** The dragon is wearing their conjured disguise\n* * *\n\n**Effect** The dragon erupts from the disguise, destroying it. The explosive revelation deals 13d6 bludgeoning damage to creatures in a 5-foot emanation with a DC 31 Reflex check save. A creature that fails its save is [[Conditions/Dazzled|Dazzled]] for 1 round as it becomes covered in scraps from the disguise.\n\nAny creature sharing a space with the dragon after they erupt is pushed into the nearest empty space."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  When the dragon scores a critical hit with a Strike, they recharge Smoke Breath."

  - name: "Rushed Transformation"
    desc: "`pf2:3` (concentrate,manipulate,occult,polymorph) **Frequency** once per hour\n* * *\n\n**Effect** Using the aid of magic and an exhausting amount of effort, the dragon quickly reshapes their body into the form of a generic humanoid figure. This has the effects of [[Spells/Humanoid Form|Humanoid Form]] except that it lasts only 1 minute, and the dragon doesn't gain the +4 status bonus to Deception as the transformation makes use of the dragon's body to crudely mimic a humanoid form. The dragon can Dismiss the effect.\n\nWhenever the effect ends, the dragon leaves behind scraps of magically conjured flesh, which could give away the dragon's presence."

  - name: "Smoke Breath"
    desc: "`pf2:2` (occult,poison) The dragon unleashes a noxious cloud of smoke that deals 10d6 poison damage in a 50-foot cone (DC 33 Fortitude check save). The smoke remains for 1 minute. This has the effects of [[Spells/Mist|Mist]], except it fills the cone's area.\n\nThe dragon can't use Smoke Breath again for 1d4 rounds."

  - name: "Sneak Attack"
    desc: "  The dragon's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."
 
```

```encounter-table
name: Conspirator Dragon (Adult)
creatures:
  - 1: Conspirator Dragon (Adult)
```



Hidden among the shadows and upper echelons of society are the conspirator dragons. These dragons are schemers, always looking to manipulate and control others, either for personal gain or simply for the thrill of watching their machinations play out. Conspirator dragons see themselves above others and typically speak with infantilizing tones and words. However, as most conspirator dragons meet others while in disguise, they do their best to maintain their disguise.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
