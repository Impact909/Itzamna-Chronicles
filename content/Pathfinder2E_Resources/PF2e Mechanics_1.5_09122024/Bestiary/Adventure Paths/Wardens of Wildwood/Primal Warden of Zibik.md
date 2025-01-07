---
title: "Primal Warden of Zibik"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2DjjJnKNLd19rpdu" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Primal Warden of Zibik"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Primal Warden of Zibik"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[plant]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Arboreal, Muan; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +20"
abilityMods: [7, 2, 6, -1, 2, -5]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +20, __Will__ +18"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Aura of Decay"
    desc: " (aura,primal) 30 feet.\n\nPlant objects and creatures in the emanation can't regain Hit Points unless the effect that attempts to heal them counteracts the aura, which has a counteract rank of 6 and a counteract DC of 32.\n\nA primal warden of Zibik can spend 1 action to reverse this aura; it becomes an aura of renewal with the healing trait, instead doubling the number of Hit Points of any healing effect received by a plant creature in the emanation."

  - name: "Primal Destruction"
    desc: " (primal,void) When the primal warden of Zibik is reduced to 0 Hit Points, it erupts with primal energy in a 30-foot emanation, dealing 12d6 void damage. Each creature in the area must attempt a DC 32 Will check save with the following outcomes.\n* * *\n\n**Critical Success** The creature takes half damage.\n\n**Success** The creature takes full damage.\n\n**Failure** The creature takes full damage and becomes temporarily cursed by Zibik to be [[Conditions/Enfeebled|Enfeebled 1]] and [[Conditions/Stupefied|Stupefied 1]] for 1 day; this is a curse effect with a counteract DC of 32.\n\n**Critical Failure** As failure, except the creature becomes [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Stupefied|Stupefied 2]]."

  - name: "Rotten Burst"
    desc: "`pf2:r` (primal) **Trigger** The primal warden of Zibik takes physical damage\n* * *\n\n**Effect** A chunk of rotten bark bursts from the warden's body at its attacker. The warden makes a rotten bark Strike against an adjacent creature without triggering reactions."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Flourishing Fist"
    desc: "+26 (magical, range increment 30 feet)\n__Damage__  3d10 + 13 bludgeoning plus flourishing-growth"

  - name: "**Ranged** `pf2:1` Rotten Bark"
    desc: "+21 (magical, range increment 30 feet)\n__Damage__  3d8 + 13 bludgeoning plus fractal-rot"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Field of Life|Field of Life]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Nature's Pathway|Nature's Pathway (At Will)]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_; __4th __  _[[Spells/Speak with Plants|Speak with Plants (At Will)]]_, _[[Spells/Vital Beacon|Vital Beacon]]_; __3rd __  _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __  _[[Spells/Speak with Animals|Speak with Animals (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Tangle Vine|Tangle Vine]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Flourishing Growth"
    desc: " (plant,primal) The first time each round a creature takes damage from the warden's fists, the target must attempt a DC 32 Fortitude check save. On a failure, tiny sprouts burst from the creature's flesh, and it becomes [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "Fractal Rot"
    desc: " (disease,primal) The first time each round a creature takes damage from the warden's rotten bark, the target becomes [[Conditions/Sickened|Sickened 1]] as the flesh where it was struck momentarily twists and rots, causing considerable pain."
 
```

```encounter-table
name: Primal Warden of Zibik
creatures:
  - 1: Primal Warden of Zibik
```




