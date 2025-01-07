---
title: "Fluxwraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uO3j9RhvtyRZ9LDP" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Fluxwraith"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Fluxwraith"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Lifesense (Imprecise) 60 Feet"
languages: "Common, Necril; any four languages (typically ancient languages)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Arcana: +30, Intimidation: +29, Occultism: +30, Stealth: +28"
abilityMods: [-5, 9, 0, 5, 7, 6]
speed:  fly 40 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +34, __Will__ +30"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense (Imprecise) 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Time-shifting Touch"
    desc: "+34 (agile, finesse, magical)\n__Damage__  3d8 + 14 force plus time-shift"

  - name: "**Ranged** `pf2:1` Temporal Fracturing Ray"
    desc: "+34 (magical, range increment 30 feet)\n__Damage__  3d6 + 14 mental plus terrible-foresight"

  - name: "Occult Innate Spells"
    desc: "DC 39, attack +31; __10th __  _[[Spells/Freeze Time|Time Stop]]_; __8th __  _[[Spells/Déjà Vu|Déjà Vu (At Will)]]_; __7th __  _[[Spells/Cast into Time|Cast into Time]]_, _[[Spells/Day's Weight|Day's Weight]]_, _[[Spells/Paralyze|Paralyze]]_; __3rd __  _[[Spells/Haste|Haste (Self Only)]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image]]_\n__Cantrips__  __(9th)__ _[[Spells/Daze|Daze]]_"

  - name: "Terrible Foresight"
    desc: " (mental,occult,prediction) A creature struck by the fluxwraith's temporal fracturing ray receives a glimpse of a possible tragic event in its future. It must succeed at a DC 35 Will check save or become [[Conditions/Slowed|Slowed 1]] and [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Slowed|Slowed 2]] and [[Conditions/Stupefied|Stupefied 2]] on a critical failure). If the creature is already affected by terrible foresight, it increases its stupefied value by 1 on a failed save, to a maximum of stupefied 4. Each time the creature gets a full night's rest, its condition values from terrible foresight decrease by 1."

  - name: "Time Shift"
    desc: " (occult) A creature struck by the fluxwraith's time-shifting touch must succeed at a DC 35 Will check saving throw or be thrust forward in time, vanishing from its space. The target automatically reappears in the same location after 1d4 rounds but can attempt an additional Will save at the end of each of its turns to end the duration. If its original space is occupied when it returns, the creature appears in the nearest unoccupied space. Since the creature is shunted forward in time, it doesn't experience any of the intervening time. Likewise, any effects on the creature with a duration don't decrease their duration, resuming when the creature reappears. A creature that succeeds at any saving throw against time shift is temporarily immune for 1 hour."
 
```

```encounter-table
name: Fluxwraith
creatures:
  - 1: Fluxwraith
```



To cheat mortality, the rare spellcaster turns to potent temporal stasis magic, or even cryogenic technology. However, such methods are highly unreliable and often fracture the sleeper's soul across the time stream as their physical body perishes. Such an individual can rise as a fluxwraith, an incorporeal undead with a kaleidoscopic consciousness.
