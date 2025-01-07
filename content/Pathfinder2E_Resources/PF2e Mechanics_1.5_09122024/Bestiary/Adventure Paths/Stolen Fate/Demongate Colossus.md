---
title: "Demongate Colossus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sNnaSNFkUlqTOAL3" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Demongate Colossus"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Demongate Colossus"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[construct]]
trait_03: [[evil]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Chthonian"
skills:
  - name: "Skills"
    desc: "Arcana: +25, Athletics: +26, Occultism: +25, Abyss Lore: +27"
abilityMods: [8, 5, 4, 5, 4, 0]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +27, __Ref__ +25, __Will__ +22"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ mental 15, physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Abyssal Link"
    desc: "  The Demongate Colossus is built around a seething, churning mass of Abyssal energy that looks like a sphere of electrified red mist encompassing a single floating harrow card at its center—The Survivor. The Abyssal link is obscured until the Demongate Colossus is reduced to fewer than 120 Hit Points, at which point glimpses of it become visible through tears and holes in its leathery \"flesh.\" The potent magic drawn from this card, combined with the radiant warden's gatewarper aura, is what allowed the Prince of Wolves to invade Harrow Court. Once the Abyssal link is revealed, a character can attempt to counter the Abyssal link with a [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 34), or can attempt to [[Actions/Steal|Steal]] the card with a DC 35 Thievery check (master) check (on a failure, a thief attempting to Steal the card takes 5d10 chaotic and 5d10 evil damage—this damage is doubled on a critical failure). Either success causes a link collapse."

  - name: "Gatewarper Aura"
    desc: " (aura,occult) 60 feet. A creature that uses a teleportation ability within the aura's emanation or enters the emanation via a teleportation ability must succeed at a DC 31 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure) as its body warps and distorts painfully, and have its destination changed to a point of the radiant warden's choosing within the emanation."

  - name: "Link Collapse"
    desc: "  If the Demongate Colossus is destroyed or its belly portal is deactivated, demons that used the colossus's portal within a 40-foot emanation take 7d10 spirit damage (basic DC 30 Fortitude check save). A creature that takes full or double damage is [[Conditions/Enfeebled|Enfeebled 2]] for 1 minute. If the Demongate Colossus is still active when it suffers a link collapse, it becomes [[Conditions/Stunned|Stunned 3]] and loses its gatewarper aura."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hammer"
    desc: "+30 (magical, reach 15 feet, shove)\n__Damage__  3d8 + 14 bludgeoning plus radiant-blow"

  - name: "**Ranged** `pf2:1` Corrupted Radiant Beam"
    desc: "+27 (magical, range 15 feet, unholy)\n__Damage__  3d6 spirit 3d6 force"

  - name: "Occult Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Planar Seal|Dimensional Lock]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_; __6th __  _[[Spells/Collective Transposition|Collective Transposition]]_; __5th __  _[[Spells/Translocate|Dimension Door (At will)]]_"

  - name: "Corrupted Radiant Blast"
    desc: "`pf2:2` (force,occult) The Demongate Colossus releases a 50-foot cone of crimson energy that deals 4d12 force damage and 4d12 spirit damage (DC 34 Reflex check save). The Demongate Colossus can't use Corrupted Radiant Blast again for 1d4 rounds."

  - name: "Corrupted Radiant Blow"
    desc: "  When a non-evil creature is hit by the Demongate Colossus's hammer Strike, a red flash of Abyssal energy attempts to infuse the target with evil. The creature must attempt a DC 34 Will check save; on a failure, the creature can't use any teleportation effects for 1 minute. On a critical failure, the creature is also [[Conditions/Enfeebled|Enfeebled 2]]."
 
```

```encounter-table
name: Demongate Colossus
creatures:
  - 1: Demongate Colossus
```


Variant radiant warden

The enigmatic and strange radiant wardens were constructed thousands of years ago to protect observatories and scholars against the incursion of alien aggressors from the Dominion of the Black. Over time, their roles as guardians expanded to include watching over any region where the laws of time and space have worn thin, particularly near portals and permanent gates between planets, planes, or dimensions.

Named for both the radial nature of the concentric rings that make up their bodies as well as the glowing radiance of their attacks, radiant wardens carry on their orders, defending sites from invasion with single-minded purpose.
