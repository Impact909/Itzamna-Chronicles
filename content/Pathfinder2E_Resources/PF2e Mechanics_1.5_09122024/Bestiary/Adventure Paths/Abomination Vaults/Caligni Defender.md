---
title: "Caligni Defender"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3QeYm01dn3CfvAEa" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Caligni Defender"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Caligni Defender"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[caligni]]
trait_02: [[chaotic]]
trait_03: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Greater Darkvision"
languages: "Caligni, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Intimidation: +16, Stealth: +17, Survival: +16"
abilityMods: [4, 5, 1, -1, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +13, __Ref__ +19, __Will__ +16"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, death flame"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortbow|Shortbow]], [[Equipment/Chain Mail|Chain Mail]], 2x [[Equipment/Black Smear Poison|Black Smear Poison]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Bravery"
    desc: "  When the caligni defender rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

  - name: "Death Flame"
    desc: " (light) When the caligni defender dies, their body combusts in a flash of white-hot flame. All creatures in a 20-foot burst take 6d10 fire damage (DC 26 Reflex check save). Their gear and treasure are unaffected by the flames and are left in a pile where they died."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+19 (agile, finesse, versatile s)\n__Damage__  1d6 + 8 piercing plus black-smear-poison"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+19 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 8 piercing plus black-smear-poison"

  - name: "Occult Innate Spells"
    desc: "DC 24, attack +14; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Mist|Obscuring Mist (At Will)]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Black Smear Poison"
    desc: "  Many calignis use a debilitating poison crafted from subterranean fungi.\n* * *\n\n**Saving Throw** DC 16 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** As stage 1\n\n**Stage 3** 1d6 poison damage, and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "Shoulder to Shoulder"
    desc: "  When adjacent to one or more defenders they can see, the defender deals an additional 2d6 damage with their Strikes."
 
```

```encounter-table
name: Caligni Defender
creatures:
  - 1: Caligni Defender
```




