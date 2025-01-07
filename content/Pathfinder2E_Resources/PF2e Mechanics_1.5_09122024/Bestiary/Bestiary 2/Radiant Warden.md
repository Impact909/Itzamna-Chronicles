---
title: "Radiant Warden"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NXoR9ICPN2NCqEmj" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Radiant Warden"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Radiant Warden"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[construct]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "any one ancient language "
skills:
  - name: "Skills"
    desc: "Arcana: +32, Athletics: +33, Occultism: +32, Astronomy Lore: +36"
abilityMods: [9, 6, 5, 6, 5, 0]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +29, __Will__ +28"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ mental 15, physical 15 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Gatekeeper Aura"
    desc: " (aura,occult,teleportation) 60 feet. A creature that uses a teleportation ability within the aura's emanation or enters it via a teleportation ability must succeed a DC 38 Will check save or become [[Conditions/Sickened|Sickened 1]] and have its destination changed to a point of the radiant warden's choosing within the emanation. On a successful save, the creature arrives as intended but is still sickened 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hammer"
    desc: "+32 (magical, reach 15 feet, shove)\n__Damage__  3d12 + 15 bludgeoning plus radiant-blow"

  - name: "**Melee** `pf2:1` Radiant Beam"
    desc: "+32 (magical, reach 15 feet)\n__Damage__  4d10 force"

  - name: "Occult Innate Spells"
    desc: "DC 38, attack +28; __9th __  _[[Spells/Teleport|Teleport]]_; __8th __  _[[Spells/Collective Transposition|Collective Transposition (x3)]]_, _[[Spells/Confusing Colors|Scintillating Pattern]]_; __7th __  _[[Spells/Planar Seal|Dimensional Lock]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_; __5th __  _[[Spells/Translocate|Dimension Door (At will)]]_"

  - name: "Orrery"
    desc: "`pf2:1` (concentrate) Until it acts, the radiant warden appears to be an orrery (or similar large mechanical contraption, such as a telescope). It has an automatic result of 53 on Deception checks and DCs to convincingly pass as such a machine."

  - name: "Radiant Blast"
    desc: "`pf2:2` (force,occult) The radiant warden releases a 50-foot cone of bright energy that deals 10d12 force damage (DC 38 Reflex check save). The radiant warden can't use Radiant Blast for 1d4 rounds."

  - name: "Radiant Blow"
    desc: " (teleportation) When a creature is hit by the radiant warden's hammer Strike, a flash of radiant energy attempts to anchor the creature in place. The creature must attempt a DC 38 Will check save; on a failure, the creature can't use any teleportation effects for 1 minute. On a critical failure, the creature is also permanently [[Conditions/Blinded|Blinded]]."
 
```

```encounter-table
name: Radiant Warden
creatures:
  - 1: Radiant Warden
```



The enigmatic and strange radiant wardens were constructed thousands of years ago to protect observatories and scholars against the incursion of alien aggressors from the Dominion of the Black. Over time, their roles as guardians expanded to include watching over any region where the laws of time and space have worn thin, particularly near portals and permanent gates between planets, planes, or dimensions.

Named for both the radial nature of the concentric rings that make up their bodies as well as the glowing radiance of their attacks, radiant wardens carry on their orders, defending sites from invasion with single-minded purpose.
