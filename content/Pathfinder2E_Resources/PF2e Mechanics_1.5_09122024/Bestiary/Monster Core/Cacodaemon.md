---
title: "Cacodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1Ha13TJYRw7PrQae" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Cacodaemon"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cacodaemon"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[daemon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Daemonic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Deception: +5, Religion: +6, Stealth: +8"
abilityMods: [0, 3, 2, -1, 1, 2]
speed: 5 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +7, __Ref__ +8, __Will__ +6"
hp: 22
health:
  - name: ""
  - name: HP
    desc: "22; __Immunities__  death effects; __Weaknesses__ holy 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+8 (agile, disease, finesse, magical, reach 0 feet, unholy)\n__Damage__  1d8 piercing plus cacodaemonia"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_; __1st __  _[[Spells/Fear|Fear]]_\n__Cantrips__  __(1st)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Cacodaemonia"
    desc: " (disease) The cacodaemon can telepathically communicate with the afflicted creature at any distance on the same plane.\n\n**Saving Throw** DC 17 Fortitude check\n* * *\n\n**Stage 1** carrier (1 day)\n\n**Stage 2** [[Conditions/Stupefied|Stupefied 1]] (1 day)\n\n**Stage 3** [[Conditions/Stupefied|Stupefied 2]] (1 day)"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) *   **Lizard**\n    *   **Speed** 20 feet;\n    *   **Melee** jaws +8 (agile, finesse), **Damage** 1d8+1 piercing\n*   **Octopus**\n    *   **Size** Small;\n    *   **Speed** 20 feet, swim 30 feet;\n    *   **Skills** Athletics +6;\n    *   **Melee** tentacle +8 (finesse), **Damage** 1d8+1 bludgeoning plus [[Bestiary Ability Glossary/Grab|Grab]];\n    *   **Melee** beak +8 (agile, finesse), **Damage** 1d6 piercing plus 2 poison\n*   **Scorpion**\n    *   **Size** Small;\n    *   **Speed** 30 feet;\n    *   **Melee** pincer +8 (agile, finesse), **Damage** 1d6+1 bludgeoning plus Grab;\n    *   **Melee** stinger +8 (agile, finesse), **Damage** 1d6+1 piercing plus 1d4 poison\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Soul Lock"
    desc: "`pf2:3` (death,divine) **Frequency** once per day\n* * *\n\n**Effect** The cacodaemon ingests the soul of a sentient creature within 30 feet that died within the last minute. When they do, the cacodaemon grows a fist-sized soul gem (Hardness 2, HP 8) in their gut and can regurgitate it at any time as an Interact action. Destroying the gem frees the soul within but doesn't return the deceased creature to life. If a caster attempts to return to life a creature whose soul is trapped within a soul gem, they fail unless they succeed at a DC 30 Religion check check. A success causes the soul gem to shatter so the creature is returned to life as normal for the spell.\n\nA fiend can Interact to ingest a soul gem it is holding, condemning the soul to the fiend's home plane. The fiend gains fast healing 5 for 1 minute.\n\n[[Bestiary Effects/Effect_ Soul Lock (Healing)|Effect: Soul Lock (Healing)]]"
 
```

```encounter-table
name: Cacodaemon
creatures:
  - 1: Cacodaemon
```



These twisted embodiments of violence and spite are spawned from eddies of angry and warped souls amid Abaddon's mists. Cacodaemons constantly hunger for mortal souls and yearn to create suffering. As gnashing spheres of teeth, fins, and spines, they are the weakest of daemonkind, an amalgam of various petty forms of death without the strength that comes from focusing on a single cause of demise.

* * *

Denizens of the bleak and terrible plane of Abaddon, daemons are shaped by and devoted to the destruction of life in all its forms. They seek the death of every mortal being by the most painful and horrible means possible, in service to the Apocalypse Riders. Each kind of daemon represents a different way to die, and their powers are nearly always aimed at spreading that particular form of death. Through the use of these powers, they seek to drag all existence down into a pit of hopelessness and despair, and to commit all souls to oblivion.

While mortals who summon daemons usually seek to use the creatures' destructive and corrupting powers for their own ends, daemons always look for ways to spread fear, doubt, and despair wherever they go. Often, daemons disguise their plots as the workings of other fiends, knowing that such confusion compounds mortals' fear and keeps those mortals from bringing the most effective weapons. As a result, learned mortals sometimes refer to daemons as "riders" after their leaders or "soul mongers" after their largest industry.

While many fiends seek to tempt mortals into lives of nihilistic evil to increase their own numbers and power on their native planes, daemons are further driven by a supernatural hunger for mortal souls and use a variety of methods—not least of which is the cacodaemons' soul gems—to entrap them. On Abaddon and in other forbidding places across the multiverse, souls are simultaneously a delicacy, a trade good, and a source of magical power, and the daemons are among the greatest gluttons, merchants, and abusers of this spiritual "resource."
