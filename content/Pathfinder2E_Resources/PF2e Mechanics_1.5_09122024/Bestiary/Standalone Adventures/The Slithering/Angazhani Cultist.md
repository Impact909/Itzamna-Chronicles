---
title: "Angazhani Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.umn3D7oC4dNoFl5H" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Angazhani Cultist"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Angazhani Cultist"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: "Chthonian, Common, Mwangi"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Diplomacy: +8, Intimidation: +10, Religion: +8, Stealth: +9, Survival: +11, Demon Lore: +8"
abilityMods: [4, 1, 1, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +9, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Spear|Spear]], [[Equipment/Wooden Shield|Wooden Shield]], [[Equipment/Hide Armor|Hide Armor]], [[Equipment/Religious Symbol (Silver)|Silver Religious Symbol of Angazhan]]"
abilities_mid:
  - name: ""
  - name: "Bloody Fanaticism"
    desc: "`pf2:r`  **Trigger** The cultist rolls a failure (but not a critical failure) on a Will save against an effect with the mental or fear trait\n* * *\n\n**Effect** The cultist takes 2d8 mental damage, and the saving throw is a success."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+14 (fatal d10)\n__Damage__  1d6 + 6 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+11 (thrown 20 ft., fatal d10)\n__Damage__  1d6 + 6 piercing"

  - name: "Divine Prepared Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Noise Blast|Sound Burst]]_; __1st __  _[[Spells/Bane|Bane]]_, _[[Spells/Command|Command]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Light|Light]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Demonic Strength"
    desc: "  Angazhani cultists inflict an extra 1d6 damage with their spears, and any spear gains the fatal d10 trait while the cultist is using it (both the extra weapon damage die and the fatal trait have already been included in the cultist's spear Strikes above)."
 
```

```encounter-table
name: Angazhani Cultist
creatures:
  - 1: Angazhani Cultist
```




