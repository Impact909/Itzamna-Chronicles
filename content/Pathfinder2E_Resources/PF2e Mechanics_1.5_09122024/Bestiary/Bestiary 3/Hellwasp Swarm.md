---
title: "Hellwasp Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pPg06dR0oqXkfvst" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/swarm
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Hellwasp Swarm"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Hellwasp Swarm"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[swarm]]
trait_05: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Diabolic; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Stealth: +18"
abilityMods: [0, 4, 6, -3, 2, -2]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +16, __Will__ +14"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ bludgeoning 5, fire 10, piercing 10, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Abandon Corpse"
    desc: "`pf2:1`  **Requirements** The hellwasp swarm is controlling a corpse with Infest Corpse\n* * *\n\n**Effect** The hellwasp swarm leaves its host corpse, which dies instantly and becomes a normal corpse in all respects. The hellwasp swarm expands out from that space to its normal size."

  - name: "Hellwasp Stings"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 4d8 piercing damage (DC 26 Reflex check save). Any creature that fails its saving throw is exposed to hellwasp venom."

  - name: "Hellwasp Venom"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d8 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 2d8 poison damage and clumsy 2 (1 round)"

  - name: "Infest Corpse"
    desc: "`pf2:2` (manipulate) The hellwasp swarm animates the corpse of a Small, Medium, or Large humanoid that protected by [[Spells/Peaceful Rest|Peaceful Rest]] or similar magic, crawling into its mouth and other orifices.\n\nIts size changes to that of the corpse and it loses its piercing and slashing resistances, fly Speed, and Hellwasp Stings.\n\nIt gains a fist melee Strike with a +18/+13/+8 attack modifier that deals 2d8 bludgeoning damage plus 2d8 piercing damage and hellwasp venom. The hellwasp swarm gains 40 temporary Hit Points when it Infests a Corpse; when these temporary HP are depleted, the corpse falls apart and the swarm Abandons the Corpse automatically."

  - name: "Torturous Buzz"
    desc: "`pf2:2` (auditory,emotion,incapacitation,occult) The swarm emits a distracting, cacophonous buzzing. Each creature within 20 feet must attempt a DC 26 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The creature is confused for 1d4 rounds."
 
```

```encounter-table
name: Hellwasp Swarm
creatures:
  - 1: Hellwasp Swarm
```



Hellwasps' infernal nature allows them to collectively inhabit and control humanoid corpses, and they use this ability to infest and horrify large swathes of territory unless destroyed. While individual hellwasp poses little threat, these fist-sized insects instinctively form into aggressive swarms that will viciously attack any creature approaching their colony, the lone exception being powerful fiends.

Hellwasp swarms have a rudimentary intelligence focused on the protection and expansion of their colony. They can understand Infernal but are incapable of speech. They sometimes obey simple commands from a lawful fiend more powerful than their swarm, but there is no nuance or understanding to this obedience, and if left alone for more than a day they stop obeying and return to their colony.
