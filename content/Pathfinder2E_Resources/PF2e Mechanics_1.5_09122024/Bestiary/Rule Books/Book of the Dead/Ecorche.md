---
title: "Ecorche"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TlfIkRfPrlchfPvy" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Ecorche"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ecorche"
level: "Creature 16"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Deception: +31, Intimidation: +31, Stealth: +28"
abilityMods: [9, 6, 7, 0, 5, 5]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +27, __Ref__ +30, __Will__ +27"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile)\n__Damage__  3d8 + 17 slashing"

  - name: "Flaying Flurry"
    desc: "`pf2:2`  The ecorche attempts two claw Strikes against the same target. If both hit and deal damage, it attempts to pull the skin off its target. It attempts an Athletics check check against the enemy's Fortitude DC.\n* * *\n\n**Critical Success** The ecorche fully pulls the target's skin off its body. The creature takes 4d8 bleed, and it's [[Conditions/Frightened|Frightened 4]] and [[Conditions/Stunned|Stunned 4]]. The bleed damage can't end naturally, only ending if the creature regains at least 75 HP or regains at least 10 HP from regeneration.\n\n**Success** The target takes 2d8 bleed and is [[Conditions/Stunned|Stunned 1]]."

  - name: "Muscular Leap"
    desc: "`pf2:1`  The ecorche over-stresses its leg muscles for a massive jump. It loses 20 untyped HP and Leaps up to 120 feet in any direction. If its next action is a Strike or Flaying Flurry, it doesn't fall until after that action."

  - name: "Tear Skin"
    desc: "`pf2:1` (emotion,fear,manipulate,mental,visual) **Requirements** The ecorche is wearing skin\n* * *\n\n**Effect** The ecorche destroys the skin it's currently wearing. The ecorche reverts to its true appearance and size, and anyone within 120 feet who witnesses this must succeed at a DC 37 Will check save or become [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 4]] on a critical failure). Regardless of the results of their saving throws, the creatures are temporarily immune for 24 hours."

  - name: "Wear Skin"
    desc: "`pf2:1` (manipulate) **Requirements** The ecorche is holding the stolen skin of a Small, Medium, or Large creature and isn't already wearing a skin\n* * *\n\n**Effect** The ecorche wears the skin as a disguise. It assumes the creature's size, appearance, and voice. Wearing Skin counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The ecorche's transformation automatically defeats Perception DCs to determine whether it's a member of the ancestry or creature type into which it transformed, and the ecorche gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise.\n\nWearing a skin gives the ecorche a +2 item bonus to AC and 75 temporary Hit Points. If the ecorche takes more than 50 slashing damage from a single source, the skin becomes broken. When broken, the skin no longer provides any of these benefits (any remaining temporary HP are immediately lost) but can still be used for Tear Skin."
 
```

```encounter-table
name: Ecorche
creatures:
  - 1: Ecorche
```



When a necromancer has need of a versatile agent to serve as a bodyguard and do their bidding in disguise, they build an ecorche-a skinless monstrosity filled with putrid alchemical agents, covered in pulsing muscle and sinew grafts, and imbued with razor-sharp claws. The ecorche uses its claws to flay its victims, stripping off skin in seconds. It can then horrifyingly squeeze itself into the stolen skin and impersonate the deceased, which it does to covertly carry out orders or find more victims to expand its collection. If its deception is uncovered, it shreds its disguise, bursting forth in terrible skinless form.
