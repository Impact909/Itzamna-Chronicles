---
title: "Vatumledor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SMDc8bAniGBJRgq3" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/occult
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Vatumledor"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Vatumledor"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[dragon]]
trait_02: [[occult]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Azlanti, Common, Draconic, Shadowtongue, Sussuran, Thassilonian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +30, Deception: +35, Diplomacy: +33, Intimidation: +33, Occultism: +31, Religion: +32, Society: +31, Stealth: +30, Achaekek Lore: +31, Mediogalti Island Lore: +33"
abilityMods: [9, 5, 6, 6, 7, 8]
speed: 50 feet,  climb 50 feet,  fly 200 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
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
    desc: "`pf2:r`  **Trigger** Vatumledor is hit or critically hit by an attack made by a creature the dragon can see\n* * *\n\n**Effect** Vatumledor retracts the targeted body part or twists away to avoid the attack, gaining a +2 circumstance bonus to his Armor Class against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (magical, reach 15 feet)\n__Damage__  3d8 + 17 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 10 feet)\n__Damage__  3d6 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (magical, reach 20 feet)\n__Damage__  2d10 + 17 bludgeoning"

  - name: "**Ranged** `pf2:1` Mental Blast"
    desc: "+31 (range 100 feet)\n__Damage__  6d6 + 6 mental"

  - name: "Occult Prepared Spells"
    desc: "DC 37, attack +29; __6th __  _[[Spells/Scrying|Scrying]]_, _[[Spells/Teleport|Teleport]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Detect Scrying|Detect Scrying]]_, _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Blur|Blur]]_, _[[Spells/See the Unseen|See the Unseen]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_, _[[Spells/Translate|Translate]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Sanctuary|Sanctuary]]_, _[[Spells/Sleep|Sleep]]_, _[[Spells/Soothe|Soothe]]_, _[[Spells/Sure Strike|Sure Strike]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __9th __  _[[Spells/Dominate|Dominate]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory (At Will)]]_"

  - name: "Conjure Disguise"
    desc: " (manipulate,occult,polymorph) **Frequency** once per day\n* * *\n\n**Effect** Vatumledor conjures a flesh suit that's a replica of a humanoid he has seen and compresses himself into the suit, along with clothing appropriate for the humanoid. This process takes 1 minute, during which Vatumledor is [[Conditions/Off-Guard|Off-Guard]]. If he stops or is interrupted in this process, the suit is destroyed. Once the process is complete, he can remain in his disguise indefinitely.\n\nThe transformation has the effects of change shape, except that the disguise is not actively magical in nature and doesn't register as magical to detect magic and similar effects. Vatumledor loses Retract Body while transformed.\n\nIf Vatumledor is critically hit while wearing the disguise, the suit is destroyed, and immediately explodes. This has the effects of Detonate Disguise, except that creatures use the outcome one degree of success better than they rolled on their save."

  - name: "Detonate Disguise"
    desc: "`pf2:2` (occult) **Requirements** Vatumledor is wearing his conjured disguise\n* * *\n\n**Effect** Vatumledor erupts from the disguise, destroying it. The explosive revelation deals 18d6 bludgeoning damage to creatures adjacent to the dragon (DC 39 Reflex check save). Creatures that fail their save become [[Conditions/Dazzled|Dazzled]] for 1 round as they become covered in scraps from the disguise. Any creatures sharing a space with Vatumledor after he erupts are pushed into the nearest empty space."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  Vatumledor makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  When Vatumledor scores a critical hit with a Strike, he recharges Smoke Breath."

  - name: "Rushed Transformation"
    desc: "`pf2:3` (concentrate,manipulate,occult,polymorph) **Frequency** once per hour\n* * *\n\n**Effect** Vatumledor quickly reshapes his body into the form of a generic humanoid figure. This has the effects of humanoid form except that it only lasts 1 minute, and he doesn't gain the +4 status bonus to Deception as the transformation makes use of his own scales and plating to crudely mimic a humanoid form. Vatumledor can Dismiss the effect. Whenever the effect ends, Vatumledor leaves behind scraps of magically conjured flesh, which could give away his presence."

  - name: "Smoke Breath"
    desc: "`pf2:2` (occult,poison) Vatumledor unleashes a 60-foot cone of smoke that deals 16d6 poison damage (DC 39 Fortitude check save). The smoke remains for 1 minute, obscuring sight with the effects of mist in the cone's area. He can't use Smoke Breath again for 1d4 rounds."

  - name: "Sneak Attack"
    desc: "  Vatumledor's Strikes deal an additional 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."
 
```

```encounter-table
name: Vatumledor
creatures:
  - 1: Vatumledor
```


Male ancient conspirator dragon

Hidden among the shadows and upper echelons of society are the conspirator dragons. These dragons are schemers, always looking to manipulate and control others, either for personal gain or simply for the thrill of watching their machinations play out. Conspirator dragons see themselves above others and typically speak with infantilizing tones and words. However, as most conspirator dragons meet others while in disguise, they do their best to maintain their disguise.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
