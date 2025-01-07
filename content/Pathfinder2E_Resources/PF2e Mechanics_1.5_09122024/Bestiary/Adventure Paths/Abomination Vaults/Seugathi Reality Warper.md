---
title: "Seugathi Reality Warper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Npq3irFfAXbfMgSh" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/seugathi
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Seugathi Reality Warper"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Seugathi Reality Warper"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[seugathi]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Aklo, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Arcana: +19, Crafting: +19, Deception: +20, Intimidation: +18, Nature: +17, Occultism: +19, Stealth: +19"
abilityMods: [4, 6, 3, 4, 2, 5]
speed: 25 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +21, __Will__ +15; +1 status to all saves vs. magic"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  mental,  poison; __Resistances__ bludgeoning 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|+1 Battle Axe]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Command Confusion"
    desc: "`pf2:r`  **Trigger** A creature fails its save against the seugathi's mindfog aura\n* * *\n\n**Effect** The seugathi determines who the [[Conditions/Confused|Confused]] creature attacks for that round, instead of the target being randomly determined by the GM.\n\nIf the chosen target is the confused creature's ally, the creature can immediately attempt a DC 25 Will check save; on a success, its target is determined randomly as normal for confusion, and on a critical success the target is no longer confused."

  - name: "Mindfog Aura"
    desc: " (mental) 20 feet. A creature that starts its turn in the aura must succeed at a DC 25 Will check save or become [[Conditions/Confused|Confused]] for 1 round; on a success, that creature is temporarily immune for 1 minute. A seugathi can suppress or activate this aura as a single action with the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+19 (agile, finesse)\n__Damage__  2d6 + 8 piercing plus seugathi-venom 1d10 spirit plus seugathi-venom"

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+18 (magical, reach 10 feet, sweep)\n__Damage__  1d8 + 8 bludgeoning 1d10 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Synesthesia|Synesthesia]]_, _[[Spells/Wave of Despair|Wave of Despair]]_; __4th __  _[[Spells/Confusion|Confusion (x3)]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Hypercognition|Hypercognition (x3)]]_, _[[Spells/Levitate|Levitate (x3)]]_, _[[Spells/Mind Reading|Mind Reading (x3)]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Envenom Weapon"
    desc: "`pf2:1` (manipulate) The seugathi applies their seugathi venom to one weapon they wield."

  - name: "Magic Item Mastery"
    desc: "  A seugathi can Cast a Spell from a magic item even if the spell isn't on their spell list. All such spells are occult spells and use the seugathi's innate spell DC and attack modifier."

  - name: "Seugathi Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 2d6 poison damage and [[Conditions/Deafened|Deafened]] and [[Conditions/Stupefied|Stupefied 2]] (1 round)"

  - name: "Warp Reality"
    desc: "`pf2:3` (concentrate,occult) The seugathi bends reality in their choice of a 10-foot emanation or a 60-foot line, altering the terrain of the area. The terrain becomes a different type of terrain (such as aquatic, arctic, or desert) and becomes normal or difficult terrain, as the seugathi chooses. Structures, general geographic features, and creatures in the area aren't transformed, but creatures in the area take 5d6 spirit damage (DC 28 Fortitude check save) as reality tries to bend them along with the terrain.\n\nThough changes to the area are permanent, the natural environment might eventually revert the land back to its original state (aquatic areas drain, arctic areas thaw, and so on)."
 
```

```encounter-table
name: Seugathi Reality Warper
creatures:
  - 1: Seugathi Reality Warper
```



Seugathi reality warpers create and destroy inhospitable environments on a small scale by manipulating the forces of raw chaos. A neothelid might spawn such a seugathi to create habitats for unique slaves or guests, or to destroy the ecosystem of a troublesome species. Darklands scholars refer to reality warpers as veterans in the seugathi ranks, but they're more accurately compared to aggressive landscape architects.

* * *

The wicked, alien [[Bestiary 2/Neothelid|Neothelids]] impregnate themselves through ritualistic magic to produce wormlike servitor creatures called seugathis. These creatures spawn with a strong psychic drive to complete some task on behalf of the neothelids' far-reaching plans. These directives are diverse, strange, and usually cruel toward humanoid life.
