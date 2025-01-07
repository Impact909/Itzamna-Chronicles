---
title: "Mnoghoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.f1Z8iYBgudsPczm4" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/seugathi
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Mnoghoth"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Mnoghoth"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[seugathi]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Aklo, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Crafting: +17, Deception: +20, Intimidation: +18, Occultism: +19, Stealth: +20"
abilityMods: [5, 6, 4, 4, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +17, __Ref__ +20, __Will__ +14; +1 status to all saves vs. magic"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130; __Immunities__  mental,  poison; __Resistances__ bludgeoning 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+2 Striking Corrosive Longsword]], [[Equipment/Magic Wand (2nd-Rank Spell)|Wand of Telekinetic Maneuver (Rank 2)]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Command Confusion"
    desc: "`pf2:r`  **Trigger** A creature fails its save against Mnoghoth's mindfog aura\n* * *\n\n**Effect** Mnoghoth determines who the [[Conditions/Confused|Confused]] creature attacks for that round, instead of the target being randomly determined by the GM. If the chosen target is the confused creature's ally, the creature can immediately attempt a DC 25 Will check save; on a success, its target is determined randomly as normal for confusion, and on a critical success the target is no longer confused."

  - name: "Mindfog Aura"
    desc: " (mental) 20 feet. A creature that starts its turn in the aura must succeed at a DC 25 Will check save or become [[Conditions/Confused|Confused]] for 1 round; on a success, that creature is temporarily immune for 1 minute. Mnoghoth can suppress or activate this aura as a single action with the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+19 (agile, finesse)\n__Damage__  2d8 + 11 piercing plus seugathi-venom"

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+20 (reach 10 feet, versatile p)\n__Damage__  1d6 acid 2d8 + 11 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Synesthesia|Synesthesia]]_; __4th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_; __3rd __  _[[Spells/Hypercognition|Hypercognition]]_, _[[Spells/Levitate|Levitate]]_, _[[Spells/Mind Reading|Mind Reading (x3)]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Envenom Weapon"
    desc: "`pf2:1` (manipulate) Mnoghoth applies their seugathi venom to their longsword."

  - name: "Magic Item Mastery"
    desc: "  Mnoghoth can Cast a Spell from a magic item even if the spell isn't on their spell list. All such spells are occult spells and use Mnoghoth's innate spell DC and attack modifier."

  - name: "Seugathi Venom"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 2d6 poison damage and [[Conditions/Deafened|Deafened]] and [[Conditions/Stupefied|Stupefied 2]] (1 round)"
 
```

```encounter-table
name: Mnoghoth
creatures:
  - 1: Mnoghoth
```


Agender variant seugathi

The most common seugathis spawned by neothelids are seugathi servants. Their masters equip them with tools useful in their tasks (often a wand and a weapon), and they rarely value other material things beyond their usefulness in completing their imprinted mission.

* * *

The wicked, alien [[Bestiary 2/Neothelid|Neothelids]] impregnate themselves through ritualistic magic to produce wormlike servitor creatures called seugathis. These creatures spawn with a strong psychic drive to complete some task on behalf of the neothelids' far-reaching plans. These directives are diverse, strange, and usually cruel toward humanoid life.
