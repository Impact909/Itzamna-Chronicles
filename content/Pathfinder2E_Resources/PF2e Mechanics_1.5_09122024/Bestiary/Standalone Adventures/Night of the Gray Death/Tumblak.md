---
title: "Tumblak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p89qyaAgR4yadT7O" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/sahkil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Tumblak"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Tumblak"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[incorporeal]]
trait_04: [[sahkil]]
trait_05: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Deception: +31, Intimidation: +35, Religion: +29, Stealth: +31, Grave Lore: +28"
abilityMods: [9, 5, 6, 2, 5, 9]
speed:  fly 40 feet
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +33, __Ref__ +28, __Will__ +31"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305; __Immunities__  disease,  fear effects,  poison,  precision; __Weaknesses__ holy 15; __Resistances__ physical 15 (except force or ghost touch; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Easy to Call"
    desc: "  A sahkil's level is considered 2 lower for the purpose of being conjured by the [[Spells/Binding Circle|Binding Circle]] ritual (and potentially other rituals, at the GM's discretion), but is always free to attack or leave instead of negotiate unless the primary caster's check is a critical success."

  - name: "Focused Force"
    desc: "  Unlike most incorporeal creatures, a tumblak can make Strength-based checks against physical creatures and objects if it chooses, though such creatures still can't make Strength-based checks against the tumblak."

  - name: "Gasping Aura"
    desc: " (air,aura,divine) 100 feet. Creatures within the aura must succeed at a DC 37 Fortitude check save. On a failure, they can't breathe and must hold their breath to avoid suffocation until they leave the aura. The tumblak can activate or deactivate the aura with a single free action, which has the concentrate trait."

  - name: "No Breath"
    desc: "  Tumblaks don't need to breathe."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+35 (magical, reach, reach 10 feet, unholy)\n__Damage__  3d12 + 17 bludgeoning plus entombing-echoes 2d6 spirit plus entombing-echoes"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +30; __9th __ (1 slots) _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Earthbind|Earthbind (At Will)]]_, _[[Spells/Fear|Fear (At Will)]]_, _[[Spells/Mask of Terror|Mask of Terror (At Will) (Self Only)]]_, _[[Spells/Nightmare|Nightmare (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Claustrophobic Nightmares"
    desc: " (curse,divine,mental) A creature [[Conditions/Fatigued|Fatigued]] by the tumblak's [[Spells/Nightmare|Nightmare]] spell is subject to paralyzing glimpses of being buried alive. Anyone using an effect that would remove the fatigued condition through a means other than a full night's rest must succeed on a DC 44 counteract check or the fatigued condition isn't removed. When the fatigued creature enters a stressful situation, such as rolling initiative in combat or entering a high-stakes negotiation, it is affected by Entombing Echoes."

  - name: "Entombing Echoes"
    desc: " (divine,emotion,incapacitation,mental) A creature struck by the tumblak's fist or impacted by Claustrophobic Nightmares must succeed on a DC 44 Will check save or feel itself confined on all sides. The creature is [[Conditions/Immobilized|Immobilized]] and [[Conditions/Off-Guard|Off-Guard]] until it Escapes (DC 44)."

  - name: "Skip Between"
    desc: "`pf2:1` (divine,teleportation) Tumblak moves from the Material Plane to the Ethereal Plane or vice versa, with the effects of [[Spells/Ethereal Jaunt|Ethereal Jaunt]] except the effect has an unlimited duration and can be Dismissed. A summoned sahkil can't use Skip Between."
 
```

```encounter-table
name: Tumblak
creatures:
  - 1: Tumblak
```




