---
title: "Sordesdaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MGGDfZD2Zz8M2p0s" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Sordesdaemon"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Sordesdaemon"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Crafting: +29, Intimidation: +28, Medicine: +26, Religion: +28, Stealth: +24, Survival: +28"
abilityMods: [8, 3, 9, 6, 5, 5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +30, __Ref__ +24, __Will__ +26; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  death effects,  disease; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Miasma of Pollution"
    desc: " (aura,disease) 30 feet. Creatures in the aura can't reduce the value of the sickened condition.\n\nA creature that enters the aura or begins its turn in it must succeed at a DC 34 Fortitude check save or be [[Conditions/Sickened|Sickened 2]] (plus [[Conditions/Slowed|Slowed 1]] as long as it is sickened on a critical failure).\n\nA creature that succeeds at its save is temporarily immune for 1 minute.\n\nCreatures made of water (such as water elementals) and plant creatures use an outcome one degree of success worse than the result of their save."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (magical, reach 15 feet, unholy)\n__Damage__  3d8 + 14 bludgeoning plus pollution-infusion 1d6 spirit plus pollution-infusion"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +28; __8th __ (2 slots) _[[Spells/Desiccate|Horrid Wilting]]_, _[[Spells/Spiritual Epidemic|Spiritual Epidemic]]_; __5th __ (2 slots) _[[Spells/Toxic Cloud|Cloudkill (At Will)]]_, _[[Spells/Translocate|Dimension Door]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __ (1 slots) _[[Spells/Detect Alignment|Detect Alignment (At Will) (Good Only)]]_"

  - name: "Pollution Infusion"
    desc: " (disease,virulent) Non-fiend creatures adjacent to the afflicted creature take a -1 circumstance penalty to saving throws against disease\n\n**Saving Throw** DC 36 Fortitude check\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Doomed|Doomed 1]] and [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** [[Conditions/Doomed|Doomed 1]] and [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 4** [[Conditions/Doomed|Doomed 2]] and [[Conditions/Drained|Drained 2]] (1 week)\n\n**Stage 5** dead.\n\n[[Bestiary Effects/Effect_ Pollution Infusion|Effect: Pollution Infusion]]"

  - name: "Retch of Foulness"
    desc: "`pf2:2` (acid,divine) The sordesdaemon exhales a spray of sewage that deals 8d6 acid damage and 8d6 poison damage in a 30-foot cone (DC 40 Fortitude check save).\n\nIt can't use Retch of Foulness again for 1d4 rounds."
 
```

```encounter-table
name: Sordesdaemon
creatures:
  - 1: Sordesdaemon
```




