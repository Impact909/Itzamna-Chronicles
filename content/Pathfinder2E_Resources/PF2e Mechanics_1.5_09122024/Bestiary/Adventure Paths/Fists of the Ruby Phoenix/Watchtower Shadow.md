---
title: "Watchtower Shadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uxykaTlc09dqCpnG" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Watchtower Shadow"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Watchtower Shadow"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Necril, Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Stealth: +33"
abilityMods: [-5, 7, 0, 0, 4, 6]
speed:  fly 30 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +21, __Ref__ +29, __Will__ +26"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  The shadow is tied to its watchtower.\n* * *\n\nA typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  An object shedding magical light (such as from the [[Spells/Light|Light]] spell) is treated as magical when used to attack the shadow."

  - name: "Rejuvenation"
    desc: " (occult) When the watchtower shadow is destroyed, it re-forms, fully healed, at the watchtower after 12 hours. Destroying the shadow and lighting its watchtower's brazier permanently destroys it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+30 (finesse, magical)\n__Damage__  4d10 + 10 void"

  - name: "Innate Divine Spells"
    desc: "DC 36, attack +28; __5th __  _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a [[Monster Core/Shadow|Shadow Spawn]] under the command of the shadow that created it. This shadow spawn doesn't have Steal Shadow and is perpetually and incurably [[Conditions/Clumsy|Clumsy 2]]. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its [[Conditions/Enfeebled|Enfeeblement]], its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) **Requirements** The shadow hit a living creature with a shadow hand Strike on its previous action.\n* * *\n\n**Effect** The shadow pulls at the target's shadow, making the creature [[Conditions/Enfeebled|Enfeebled 1]]. This is cumulative with other enfeebled conditions from shadows, to a maximum of enfeebled 4. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body. Enfeebled from Steal Shadow decreases by 1 every hour."
 
```

```encounter-table
name: Watchtower Shadow
creatures:
  - 1: Watchtower Shadow
```


Variant shadow

The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light. Those who parley with shadows, typically by keeping them at bay with a glowing weapon, may learn great secrets, for they are ideal spies.
