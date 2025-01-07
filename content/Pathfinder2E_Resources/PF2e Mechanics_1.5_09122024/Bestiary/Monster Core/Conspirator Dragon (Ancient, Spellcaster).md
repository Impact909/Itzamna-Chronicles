---
title: "Conspirator Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aGwzRD2YxBAZPqe9" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/occult
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Conspirator Dragon (Ancient, Spellcaster)"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Conspirator Dragon (Ancient, Spellcaster)"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[occult]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Shadowtongue, Sussuran, Aklo; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +30, Deception: +35, Diplomacy: +33, Intimidation: +33, Occultism: +31, Performance: +35, Society: +31, Stealth: +30, Lore (any one region or settlement): +31"
abilityMods: [9, 5, 6, 6, 7, 8]
speed: 50 feet,  climb 50 feet,  fly 200 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +27, __Ref__ +28, __Will__ +32; +2 status to all saves vs. occult"
hp: 345
health:
  - name: ""
  - name: HP
    desc: "345; __Immunities__  controlled,  paralyzed,  sleep"
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
    desc: "+32 (magical, reach 15 feet)\n__Damage__  3d8 + 17 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 10 feet)\n__Damage__  3d6 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (magical, reach 20 feet)\n__Damage__  2d10 + 17 bludgeoning"

  - name: "**Ranged** `pf2:1` Mental Blast"
    desc: "+31 (mental, range 100 feet)\n__Damage__  6d6 + 6 mental"

  - name: "Occult Prepared Spells"
    desc: "DC 39, attack +31; __8th __  _[[Spells/Hidden Mind|Hidden Mind]]_, _[[Spells/Unrelenting Observation|Unrelenting Observation]]_; __7th __  _[[Spells/Duplicate Foe|Duplicate Foe]]_, _[[Spells/Project Image|Project Image]]_, _[[Spells/Warp Mind|Warp Mind]]_; __6th __  _[[Spells/Mislead|Mislead]]_, _[[Spells/Scrying|Scrying]]_, _[[Spells/Truesight|Truesight]]_; __5th __  _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Synaptic Pulse|Synaptic Pulse]]_, _[[Spells/Truespeech|Truespeech]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Honeyed Words|Honeyed Words]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Veil of Privacy|Veil of Privacy]]_; __2nd __  _[[Spells/Calm|Calm]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Paranoia|Paranoia]]_; __1st __  _[[Spells/Bane|Bane]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Message|Message]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __9th __  _[[Spells/Dominate|Dominate]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory (At Will)]]_"

  - name: "Conjure Disguise"
    desc: " (manipulate,occult,polymorph) **Frequency** once per day\n* * *\n\n**Effect** The dragon conjures a perfect flesh-suit replica of a humanoid they've seen of their size or smaller and compresses themself into it, along with generating appropriate clothing for the humanoid. This process takes 1 minute to complete, during which the dragon is [[Conditions/Off-Guard|Off-Guard]]. If the dragon stops or is interrupted in this process, the suit is destroyed. Once the process is complete, the dragon can remain in this disguise indefinitely.\n\nThe transformation has the effects of [[Bestiary Ability Glossary/Change Shape|Change Shape]], except that the disguise is not actively magical in nature and doesn't register as magical to detect magic and similar effects. The dragon loses Retract Body while transformed.\n\nIf the dragon is critically hit while wearing the disguise, the suit is destroyed and immediately explodes. This has the effects of Detonate Disguise, except that creatures use the outcome one degree of success better than they rolled on their save."

  - name: "Detonate Disguise"
    desc: "`pf2:2` (occult) **Requirements** The dragon is wearing their conjured disguise\n* * *\n\n**Effect** The dragon erupts from the disguise, destroying it. The explosive revelation deals 18d6 bludgeoning damage to creatures in a 5-foot emanation with a DC 39 Reflex check save. A creature that fails its save is [[Conditions/Dazzled|Dazzled]] for 1 round as it becomes covered in scraps from the disguise.\n\nAny creature sharing a space with the dragon after they erupt is pushed into the nearest empty space."

  - name: "Rushed Transformation"
    desc: "`pf2:3` (concentrate,manipulate,occult,polymorph) **Frequency** once per hour\n* * *\n\n**Effect** Using the aid of magic and an exhausting amount of effort, the dragon quickly reshapes their body into the form of a generic humanoid figure. This has the effects of [[Spells/Humanoid Form|Humanoid Form]] except that it lasts only 1 minute, and the dragon doesn't gain the +4 status bonus to Deception as the transformation makes use of the dragon's body to crudely mimic a humanoid form. The dragon can Dismiss the effect.\n\nWhenever the effect ends, the dragon leaves behind scraps of magically conjured flesh, which could give away the dragon's presence."

  - name: "Smoke Breath"
    desc: "`pf2:2` (occult,poison) The dragon unleashes a noxious cloud of smoke that deals 16d6 poison damage in a 60-foot cone (DC 39 Fortitude check save). The smoke remains for 1 minute. This has the effects of [[Spells/Mist|Mist]], except it fills the cone's area.\n\nThe dragon can't use Smoke Breath again for 1d4 rounds."

  - name: "Sneak Attack"
    desc: "  The dragon's Strikes deal an additional 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."
 
```

```encounter-table
name: Conspirator Dragon (Ancient, Spellcaster)
creatures:
  - 1: Conspirator Dragon (Ancient, Spellcaster)
```



Hidden among the shadows and upper echelons of society are the conspirator dragons. These dragons are schemers, always looking to manipulate and control others, either for personal gain or simply for the thrill of watching their machinations play out. Conspirator dragons see themselves above others and typically speak with infantilizing tones and words. However, as most conspirator dragons meet others while in disguise, they do their best to maintain their disguise.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
