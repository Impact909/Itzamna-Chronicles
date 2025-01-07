---
title: "Zuhra Shuyookh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fAcpemyXg0P59eNr" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/genie
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Zuhra Shuyookh"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Zuhra Shuyookh"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[genie]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common, Talican; truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +24, Crafting: +26, Deception: +26, Intimidation: +24, Performance: +28, Society: +22"
abilityMods: [5, 6, 8, 5, 4, 7]
speed: 30 feet,  fly 35 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +29, __Ref__ +23, __Will__ +21"
hp: 212
health:
  - name: ""
  - name: HP
    desc: "212; __Resistances__ electricity 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+2 Striking Spiked Chain]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Actor.nHgfiWS35zsMEe4k.Item.RrpDOSh8ukqc73TP|Conductive Redirection]]"
    desc: "`pf2:r` (arcane,concentrate,electricity) **Trigger** The zuhra is hit by an attack, spell, or effect that deals electricity damage\n* * *\n\n**Effect** The zuhra conducts the electricity through their body, taking damage as normal, and redirecting a bolt at one target within 30 feet that they can see. The zuhra makes a ranged attack roll with a +27 modifier against the target's AC. On a hit or critical hit, the target takes electricity damage equal to the full damage of the triggering effect."

  - name: "Magnetic Field"
    desc: " (arcane,aura,metal) 10 feet.\n\nAll squares in the aura are difficult terrain for creatures wearing metal armor or made of metal. Strikes with metallic weapons made by or against creatures in this aura take a –2 status penalty to the attack roll. Zuhras ignore these effects."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+27 (disarm, finesse, magical, reach 15 feet, trip)\n__Damage__  1d12 electricity 2d8 + 11 slashing"

  - name: "**Melee** `pf2:1` Hand Blade"
    desc: "+25 (agile, finesse, magical, reach 15 feet)\n__Damage__  2d4 + 11 slashing 4d4 bleed"

  - name: "Arcane Innate Spells"
    desc: "DC 32, attack +24; __7th __  _[[Spells/Clad In Metal|Clad In Metal (Can Choose Uncommon and Rare Metals)]]_, _[[Spells/Enthrall|Enthrall]]_, _[[Compendium.pf2e.spells-srd.Item.nRINcQb81Wt4KeFu|Interplanar Teleport (At Will) (To Astral Plane, Elemental Planes, or Universe only)]]_, _[[Spells/Weapon Storm|Weapon Storm]]_; __6th __  _[[Spells/Mercurial Stride|Mercurial Stride]]_, _[[Spells/Wall of Metal|Wall of Metal]]_; __5th __  _[[Spells/Invisibility|Invisibility (x2)]]_, _[[Spells/Magnetic Acceleration|Magnetic Acceleration (At Will)]]_, _[[Spells/Magnetic Attraction|Magnetic Attraction (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The zuhra transforms into a Small or Medium metal elemental or animal. This doesn't affect the zuhra's statistics, but it could change the damage type of their Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Magnetic Reposition"
    desc: "`pf2:1` (arcane) **Frequency** once per round\n* * *\n\n**Effect** The shuyookh targets any number of creatures affected by their magnetic field, and moves each target 10 feet in a direction the zuhra chooses. Each target can resist being moved if it succeeds at a DC 32 Fortitude check save."

  - name: "Magnetic Storm"
    desc: "`pf2:3` (arcane) **Requirements** The shuyookh's magnetic field is active\n* * *\n\n**Effect** The shuyookh electromagnetically flings razor-sharp metal scraps. Each creature in a 30-foot emanation takes 8d6 slashing + 3d12 electricity damage, with a DC 32 Fortitude check save.\n\nThe shuyookh's magnetic field is deactivated for 1d4 rounds."

  - name: "Mercurial Wish"
    desc: " (downtime) **Frequency** three times per year\n* * *\n\n**Effect** The shuyookh conducts a [[Spells/Wish|Wish]] ritual for the benefit of a mortal, requiring no cost or secondary casters. The shuyookh's result is a success if they succeed at a DC 5 Flat check or a failure if not. The shuyookh attempts to fulfill the wish in a way that creates an unstable or impermanent benefit."
 
```

```encounter-table
name: Zuhra Shuyookh
creatures:
  - 1: Zuhra Shuyookh
```



The most powerful zuhras draw followers and elemental metal with overwhelming force of personality and literal magnetism. When called upon to conduct wish rituals, they use their long isolation from the other planes as an excuse to misinterpret requests outlandishly, claiming linguistic differences.

* * *

Zuhras, the genies of the elemental Plane of Metal, are bold and imposing, fond of being the center of attention and drawing a crowd with flashy performances, displays of skill, and tales of their personal victories. Despite their large personalities, their long-term relationships tend to be cool and somewhat distant; zuhras often make alliances but rarely form friendships, and the trust required for deeper relationships is rarer still. The few mortals who've gotten to know a zuhra often describe them as bombastic but emotionally aloof.

Since the reconnection with other planes, zuhras have sought out and formed bonds with other genies. They find their jabali cousins to be capable smithing partners, if a bit staid and dull. Zuhras rarely pay non-genie elementals any more than a passing glance, finding even the intelligent ones uninteresting to communicate with or hard to relate to.
