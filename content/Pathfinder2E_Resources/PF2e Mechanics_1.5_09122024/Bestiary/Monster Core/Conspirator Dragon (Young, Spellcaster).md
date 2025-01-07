---
title: "Conspirator Dragon (Young, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6WUlUXiw1iqk4sPB" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/occult
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Conspirator Dragon (Young, Spellcaster)"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Conspirator Dragon (Young, Spellcaster)"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[occult]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Shadowtongue; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +16, Deception: +18, Diplomacy: +18, Intimidation: +16, Occultism: +16, Performance: +18, Society: +16, Stealth: +16, Lore (any one region or settlement): +16"
abilityMods: [5, 3, 2, 2, 4, 4]
speed: 30 feet,  climb 30 feet,  fly 120 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +14, __Ref__ +15, __Will__ +18; +2 status to all saves vs. occult"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  controlled,  paralyzed,  sleep"
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
    desc: "+19 (magical, reach 10 feet)\n__Damage__  2d8 + 8 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile, magical)\n__Damage__  2d6 + 8 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+17 (magical, reach 15 feet)\n__Damage__  1d10 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Mental Blast"
    desc: "+18 (mental, range 100 feet)\n__Damage__  3d6 + 3 mental"

  - name: "Occult Prepared Spells"
    desc: "DC 26, attack +19; __3rd __  _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Veil of Privacy|Veil of Privacy]]_; __2nd __  _[[Spells/Calm|Calm]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Paranoia|Paranoia]]_; __1st __  _[[Spells/Bane|Bane]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(3rd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Message|Message]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Occult Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_; __1st __  _[[Spells/Charm|Charm (At Will)]]_"

  - name: "Conjure Disguise"
    desc: " (manipulate,occult,polymorph) **Frequency** once per day\n* * *\n\n**Effect** The dragon conjures a perfect flesh-suit replica of a humanoid they've seen of their size or smaller and compresses themself into it, along with generating appropriate clothing for the humanoid. This process takes 1 minute to complete, during which the dragon is [[Conditions/Off-Guard|Off-Guard]]. If the dragon stops or is interrupted in this process, the suit is destroyed. Once the process is complete, the dragon can remain in this disguise indefinitely.\n\nThe transformation has the effects of [[Bestiary Ability Glossary/Change Shape|Change Shape]], except that the disguise is not actively magical in nature and doesn't register as magical to detect magic and similar effects. The dragon loses Retract Body while transformed.\n\nIf the dragon is critically hit while wearing the disguise, the suit is destroyed and immediately explodes. This has the effects of Detonate Disguise, except that creatures use the outcome one degree of success better than they rolled on their save."

  - name: "Detonate Disguise"
    desc: "`pf2:2` (occult) **Requirements** The dragon is wearing their conjured disguise\n* * *\n\n**Effect** The dragon erupts from the disguise, destroying it. The explosive revelation deals 9d6 bludgeoning damage to creatures in a 5-foot emanation with a DC 26 Reflex check save. A creature that fails its save is [[Conditions/Dazzled|Dazzled]] for 1 round as it becomes covered in scraps from the disguise.\n\nAny creature sharing a space with the dragon after they erupt is pushed into the nearest empty space."

  - name: "Rushed Transformation"
    desc: "`pf2:3` (concentrate,manipulate,occult,polymorph) **Frequency** once per hour\n* * *\n\n**Effect** Using the aid of magic and an exhausting amount of effort, the dragon quickly reshapes their body into the form of a generic humanoid figure. This has the effects of [[Spells/Humanoid Form|Humanoid Form]] except that it lasts only 1 minute, and the dragon doesn't gain the +4 status bonus to Deception as the transformation makes use of the dragon's body to crudely mimic a humanoid form. The dragon can Dismiss the effect.\n\nWhenever the effect ends, the dragon leaves behind scraps of magically conjured flesh, which could give away the dragon's presence."

  - name: "Smoke Breath"
    desc: "`pf2:2` (occult,poison) The dragon unleashes a noxious cloud of smoke that deals 7d6 poison damage in a 40-foot cone (DC 26 Fortitude check save). The smoke remains for 1 minute. This has the effects of [[Spells/Mist|Mist]], except it fills the cone's area.\n\nThe dragon can't use Smoke Breath again for 1d4 rounds."

  - name: "Sneak Attack"
    desc: "  The dragon's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."
 
```

```encounter-table
name: Conspirator Dragon (Young, Spellcaster)
creatures:
  - 1: Conspirator Dragon (Young, Spellcaster)
```



Hidden among the shadows and upper echelons of society are the conspirator dragons. These dragons are schemers, always looking to manipulate and control others, either for personal gain or simply for the thrill of watching their machinations play out. Conspirator dragons see themselves above others and typically speak with infantilizing tones and words. However, as most conspirator dragons meet others while in disguise, they do their best to maintain their disguise.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
