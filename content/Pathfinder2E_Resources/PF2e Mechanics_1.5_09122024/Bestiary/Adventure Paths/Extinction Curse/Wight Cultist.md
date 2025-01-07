---
title: "Wight Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.StTUF2BxO2Qqoiz1" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Wight Cultist"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Wight Cultist"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Intimidation: +24, Occultism: +17, Stealth: +22"
abilityMods: [7, 4, 6, -1, 6, 4]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +24, __Ref__ +20, __Will__ +22"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ranseur|+1 Striking Ranseur]], [[Equipment/Religious Symbol (Silver)|Religious Symbol of Bokrug (Platinum)]]"
abilities_mid:
  - name: ""
  - name: "Dreadful Spite"
    desc: "`pf2:r`  **Trigger** The wight cultist is reduced to 0 Hit Points\n* * *\n\n**Effect** The wight makes a Strike before being destroyed. It doesn't gain any temporary HP from drain life on this Strike. A creature hit by this Strike is also [[Conditions/Doomed|Doomed 1]] for 1 minute."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ranseur"
    desc: "+26 (disarm, magical, reach)\n__Damage__  2d10 + 13 piercing plus drain-life"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 ()\n__Damage__  3d6 + 13 bludgeoning plus drain-life"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +19; __6th __ (1 slots) _[[Spells/Wave of Despair|Crushing Despair]]_; __5th __ (2 slots) _[[Spells/Confusion|Confusion]]_, _[[Spells/Downpour|Downpour]]_; __3rd __ (1 slots) _[[Spells/Paralyze|Paralyze (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Shield|Shield]]_"

  - name: "Drain Life"
    desc: " (divine) When the wight damages a living creature with its claw or ranseur Strike, the wight gains 12 temporary Hit Points and the creature must succeed at a DC 29 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the wight increases the amount of drain by 1 on a failed save, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Wight Spawn"
    desc: " (divine) A living humanoid slain by a wight's claw or ranseur Strike rises as a wight after 1d4 rounds. This wight spawn is under the command of the wight that killed it. It doesn't have drain life or wight spawn and becomes [[Conditions/Clumsy|Clumsy 2]] for as long as it is a wight spawn. If the creator of the wight spawn dies, the wight spawn becomes a full-fledged, autonomous wight; it regains its free will, gains drain life and wight spawn, and is no longer clumsy."
 
```

```encounter-table
name: Wight Cultist
creatures:
  - 1: Wight Cultist
```


Variant wight


