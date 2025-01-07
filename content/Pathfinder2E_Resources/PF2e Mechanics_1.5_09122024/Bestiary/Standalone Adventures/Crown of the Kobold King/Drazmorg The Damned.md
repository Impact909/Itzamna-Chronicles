---
title: "Drazmorg The Damned"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Oe87zf4FEViItNgj" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Drazmorg The Damned"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Drazmorg The Damned"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[wight]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Dwarven, Necril"
skills:
  - name: "Skills"
    desc: "Arcana: +17, Crafting: +15, Deception: +13, Intimidation: +15, Medicine: +15, Occultism: +17, Religion: +13, Society: +15, Stealth: +15, Academia Lore: +17"
abilityMods: [2, 4, 2, 6, 4, 2]
speed:  fly 25 feet
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +13, __Ref__ +15, __Will__ +17"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Drazmorg's Staff of All-Sight|Drazmorg's Staff of All-Sight]], [[Equipment/In the Shadows of Toil|In the Shadows of Toil]]"
abilities_mid:
  - name: ""
  - name: "[[Monster Core/Wight/Final Spite|Final Spite]]"
    desc: "`pf2:r`  **Trigger** The wight is reduced to 0 Hit Points.\n* * *\n\n**Effect** The wight makes a Strike before being destroyed. It doesn't gain any temporary HP from drain life on this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 ()\n__Damage__  2d6 + 4 slashing plus drain-life"

  - name: "Arcane Prepared Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_; __3rd __  _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Mind Reading|Mind Reading]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/False Vitality|False Life]]_, _[[Spells/Mirror Image|Mirror Image]]_, _[[Spells/Ghostly Carrier|Spectral Hand]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(4th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Light|Light]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "[[Monster Core/Wight/Drain Life|Drain Life]]"
    desc: " (divine) When the wight damages a living creature with its claw Strike, the wight gains 3 temporary Hit Points and the creature must succeed at a DC 25 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the wraith increases the amount of drain by 1 on a failed save to a maximum of drained 4."

  - name: "Raise Bone Wall"
    desc: "`pf2:2` (divine) **Frequency** once per day\n\n**Requirements** Drazmorg is in the Lower Vault of Droskar's Crucible\n* * *\n\n**Effect** Drazmorg draws upon the necromantic energy that infuses the area and causes a tangled wall of bones to rise from the ground. The wall is 5 feet thick, 10 feet wide, and 10 feet tall; once created, it's permanent until Drazmorg uses this ability again, whereupon a previously created bone wall (such as the one at area **G2**) crumbles. The bone wall has AC 10, Hardness 10, and 25 Hit Points. It's immune to critical hits and precision damage, and it heals damage to itself at a rate of 2d6 Hit Points at the end of a round. Everything on each side of the wall has greater cover from creatures on the opposite side, and the wall can't be moved through. A destroyed section of the wall of bones can be moved through freely and no longer heals damage. A creature caught in a space when a bone wall is created must attempt a DC 25 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected, and the bone wall fails to form in any square occupied by that creature.\n\n**Success** The creature is forced into an adjacent square of its choice as the bone wall forms in its previous space.\n\n**Failure** As success, but the creature is also knocked [[Conditions/Prone|Prone]].\n\n**Critical Failure** As failure, but the creature also takes 4d6 piercing and 4d6 bludgeoning damage from the force of being struck by the bone wall."

  - name: "Wight Spawn"
    desc: " (divine) A living humanoid slain by a wight's claw Strike rises as a [[Monster Core/Wight|Wight Spawn]] after [[/gmr 1d4 #Wight Spawn Transformation]]{1d4 rounds}. This wight spawn is under the command of the wight that killed it. It doesn't have Drain Life or Wight Spawn and becomes [[Conditions/Clumsy|Clumsy 2]] for as long as it is a wight spawn. If the creator of the wight spawn dies, the wight spawn becomes a full-fledged, autonomous wight; it regains its free will, gains Drain Life and Wight Spawn, and is no longer clumsy."
 
```

```encounter-table
name: Drazmorg The Damned
creatures:
  - 1: Drazmorg The Damned
```


Male variant wight necromancer


