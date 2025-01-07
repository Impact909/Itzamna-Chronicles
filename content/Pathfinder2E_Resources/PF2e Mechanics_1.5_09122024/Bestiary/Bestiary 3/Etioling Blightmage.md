---
title: "Etioling Blightmage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MNrWIlLcbQOWVEBr" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mortic
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Etioling Blightmage"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Etioling Blightmage"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[gnome]]
trait_03: [[humanoid]]
trait_04: [[mortic]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common, Fey, Gnomish, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Deception: +22, Diplomacy: +22, Intimidation: +22, Nature: +19"
abilityMods: [3, 5, 3, 3, 5, 7]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +21, __Will__ +17"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, void healing"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Consecration Vulnerability"
    desc: "  An etioling in a place of worship dedicated to a non-evil deity or on sacred ground, such as an area blessed by [[Spells/Anointed Ground|Anointed Ground]], is [[Conditions/Slowed|Slowed 1]]."

  - name: "Ectoplasmic Secretions"
    desc: " (occult) Any creature that hits the etioling with an unarmed attack, tries to [[Conditions/Grabbed|Grapple]] them, or otherwise touches them becomes partially coated in ectoplasm.\n\nThe creature takes 1d6 void damage and must succeed at a DC 27 Reflex check save or become [[Conditions/Enfeebled|Enfeebled 2]] until the ectoplasm is removed.\n\nThe ectoplasm can be removed with a total of 3 Interact actions by the creature or creatures adjacent to the creature. These actions don't need to be consecutive or made by the same creature."

  - name: "Ectoplasmic Shield"
    desc: "`pf2:r` (occult) **Trigger** The etioling is the target of a physical ranged attack\n* * *\n\n**Effect** The etioling interposes a wave of ectoplasm between themself and the source of the ranged attack, giving them a +2 circumstance bonus to AC against the triggering attack. If the attack misses, the ectoplasm deflected it. The ectoplasm can't deflect unusually large or heavy ranged projectiles (such as boulders or ballista bolts)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Withering Aura"
    desc: " (aura,occult) 20 feet. The etioling drains nutrients from nearby plant and animal life. Each round a creature begins its turn in this aura, it takes 1d6 void damage and must succeed at a DC 27 Fortitude check save or become [[Conditions/Drained|Drained 1]].\n\nAll non-magical plant life in this aura instantly withers, removing any cover and concealment provided by trees and undergrowth."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Corrupting Touch"
    desc: "+21 (agile, finesse, magical)\n__Damage__  2d12 + 6 void"

  - name: "Occult Spontaneous Spells"
    desc: "DC 29, attack +21; __5th __ (4 slots) _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Synesthesia|Synesthesia]]_; __4th __ (4 slots) _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_; __3rd __ (4 slots) _[[Spells/Earthbind|Earthbind]]_, _[[Spells/False Vitality|False Life]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __ (4 slots) _[[Spells/Blur|Blur]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Mist|Obscuring Mist]]_; __1st __ (4 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(5th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Prestidigitation|Prestidigitation]]_"

  - name: "Death Gasp"
    desc: "`pf2:1` (divine) The etioling draws in a deep breath and holds it, temporarily suspending their biological processes and becoming undead.\n\nThe etioling gains the undead and incorporeal traits and becomes immune to bleed, death effects, disease, [[Conditions/Paralyzed|Paralyzed]], poison, and sleep. Any such effects the etioling is currently suffering from are suspended, but take effect again once they take a breath. They gain a fly Speed of 25 feet, resistance 10 to all damage (except force, ghost touch, or vitality; double this resistance vs. non-magical) while they hold their breath.They can't cast spells during this time.\n\nDeath Gasp lasts as long as the etioling blightmage holds their breath (up to 8 rounds).\n\n[[Bestiary Effects/Effect_ Death Gasp (Etioling)|Effect: Death Gasp (Etioling)]]"
 
```

```encounter-table
name: Etioling Blightmage
creatures:
  - 1: Etioling Blightmage
```



When the primal spark of the First World nestled in a gnome's heart is engulfed in _Radiant Fire_, it fights back, pushing against death with riotous life and creating an etioling. Within their small frames, churning vitality and void energy fiercely battle for dominance, occasionally causing convulsions and babbling speech. This intense inner conflict warps an etioling's primal magic, transmogrifying it into an occult hybrid singular to these unfortunate mortics.

Nearly devoid of color, etiolings have vibrant eyes and pulsing green veins. Their bodies force the corrupting void energy out through their pores, where it distills on their skin, covering them in a thin layer of ectoplasm and concentrated death. Around them, the world withers.

Incapable of focusing for long, etiolings are impulsive and moody, rapidly alternating between kindness, malice, and trickery. They forget themselves, their friends, and the things they once loved.

* * *

Mortics are humanoids overwhelmed by void energy who still cling to life, surviving as twisted amalgams of living and undead. Though they feel unnatural cravings and resemble corpses, mortics live, breathe, eat, sleep, and procreate. However, a mortic can suspend their living functions simply by holding their breath, becoming more like a true undead.

Mortics are largely new to Golarion, with most created in droves when the Whispering Tyrant destroyed entire cities with his Radiant Fire, a magical explosion fueled by the collision of void and vitality energy. From among the corpses of these tragedies rose mortics, living survivors mistaken for corpses and left behind as a result. They found themselves in a twilight state-neither fully alive or undead. The necrotic pollutants of the Gravelands and the Isle of Terror continue to create mortics, seeping into neighboring lands through the air, earth, and water to infect the populace. Though most of the living in these lands fear becoming transformed, some believe becoming a mortic is their best chance of survival in the face of the encroaching hordes of the dead.

A mortic's powers differ by ancestry, though they do have a few commonalities. Reading or hearing scripture induces headaches, and they experience great discomfort when treading upon sacred ground. For those who were religious in life, these new changes can be devastating.
