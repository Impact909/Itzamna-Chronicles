---
title: "Scarecophagus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kJb093qvFlAGx48e" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Scarecophagus"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #179: Cradle of Quartz"
name: "Scarecophagus"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[evil]]
trait_03: [[lawful]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Necril, Osiriani"
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [5, 2, 4, -2, 4, 2]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #179: Cradle of Quartz_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +10, __Will__ +16"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Immunities__  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void"
abilities_top:
  - name: ""

  - name: "Magic Sense (Imprecise) 30 feet"
    desc: " (magical) The scarecophagus detects the presence of magic items and spell effects within 30 feet as an imprecise sense."

abilities_mid:
  - name: ""
  - name: "Despair"
    desc: " (aura,divine,emotion,fear,incapacitation,mental) 30 feet. Living creatures are [[Conditions/Frightened|Frightened 1]] while in a scarecophagus' despair aura. They can't naturally recover from this fear while in the emanation but recover instantly once they leave it. When a creature first enters the emanation, it must succeed at a DC 22 Will check save (after taking the penalty from being frightened 1) or be [[Conditions/Paralyzed|Paralyzed]] for 1 round. The creature is then temporarily immune to this paralysis for 24 hours.\n\n[[Bestiary Effects/Effect_ Despair|Effect: Despair]]"

  - name: "Disgorge Mummy"
    desc: "  If a scarecophagus is reduced to 0 Hit Points by any damage other than vitality energy, it cracks open as it's destroyed, allowing the undead mummy trapped for eons within its core to rise. This is a weak [[Monster Core/Mummy Guardian|Mummy Guardian]]; if the mummy guardian survives on its own for a month, it loses the weak adjustment. If the scarecophagus is reduced to 0 Hit Points by vitality energy, it cracks open as it's destroyed and the mummy within turns to dust, destroyed as well."

  - name: "Vulnerable to Vitality Energy"
    desc: "  A scarecophagus takes damage from vitality energy as if it were an undead creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+15 (agile, magical, reach 10 feet)\n__Damage__  2d6 + 7 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 24, attack +16; __3rd __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Acid Arrow|Acid Arrow]]_, _[[Spells/Dispel Magic|Dispel Magic]]_; __1st __  _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(3rd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Sarcophagus"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the scarecophagus appears to be a normal stone sarcophagus. It has an automatic result of 34 on Deception checks and DCs to pass as a sarcophagus."

  - name: "Shifting Scuttle"
    desc: "  **Frequency** once per turn\n* * *\n\n**Effect** The scarecophagus Steps up to 10 feet."
 
```

```encounter-table
name: Scarecophagus
creatures:
  - 1: Scarecophagus
```



Originally created by Gebbite necromancers during the war against Nex, the scarecophagus is an evil construct that draws power directly from the undead mummy trapped forever within its sealed core. This necromantic energy is channeled throughout the construct's body, allowing it to scuttle about on legs of stone, animate tentacles to strike at foes, and use the mummy's trapped mind for its own sapience and magical powers.
