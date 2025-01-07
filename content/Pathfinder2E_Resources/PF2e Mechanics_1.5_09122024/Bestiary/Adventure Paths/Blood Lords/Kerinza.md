---
title: "Kerinza"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zqm1XWmgPdzGVIuI" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Kerinza"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Kerinza"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common, Draconic, Taldane, Varisian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Deception: +22, Diplomacy: +22, Intimidation: +22, Nature: +21, Stealth: +25"
abilityMods: [4, 7, 2, 2, 5, 4]
speed: 30 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +18, __Ref__ +23, __Will__ +21"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Light Mace|+1 Striking Light Mace]], [[Equipment/Smoked Goggles|Smoked Goggles]]"
abilities_mid:
  - name: ""
  - name: "Biting Snakes"
    desc: "`pf2:r`  **Trigger** A creature ends its turn adjacent to Kerinza\n* * *\n\n**Effect** Kerinza makes a snake fangs Strike against the creature."

  - name: "Petrifying Gaze"
    desc: " (arcane,aura,visual) 30 feet. When a creature ends its turn in the aura, it must attempt a DC 32 Fortitude check save. If the creature fails, it becomes [[Conditions/Slowed|Slowed 1]] for 1 minute. Kerinza can activate or deactivate this aura by using a single action, which has the concentrate trait, but deactivating it is painful for her; she gains weakness 15 to physical damage while her petrifying gaze is deactivated."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Light Mace"
    desc: "+26 (agile, finesse, magical, shove)\n__Damage__  2d4 + 8 bludgeoning"

  - name: "**Melee** `pf2:1` Snake Fangs"
    desc: "+25 ()\n__Damage__  2d6 + 8 piercing plus serpent-venom"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Speak with Stones|Stone Tell]]_, _[[Spells/Stone to Flesh|Stone to Flesh]]_; __5th __ (3 slots) _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Wall of Stone|Wall of Stone]]_; __4th __ (3 slots) _[[Spells/Charm|Charm]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Mountain Resilience|Stoneskin]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Produce Flame|Produce Flame]]_, _[[Spells/Shield|Shield]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (arcane,concentrate,incapacitation,visual) Kerinza fixes her glare on a creature she can see within 30 feet. The target must attempt a DC 32 Fortitude check save against Kerinza's petrifying gaze. If the target was already [[Conditions/Slowed|Slowed]] before attempting its save, a failed save causes it to be [[Conditions/Petrified|Petrified]] permanently. After attempting its save, the creature is then temporarily immune until the start of Kerinza's next turn."

  - name: "Quick Responses"
    desc: "  If Kerinza isn't [[Conditions/Slowed|Slowed]], her Strikes deal an additional 2d6 precision damage to slowed targets."

  - name: "Serpent Venom"
    desc: " (poison) **Saving Throw** DC 32 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 5d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"
 
```

```encounter-table
name: Kerinza
creatures:
  - 1: Kerinza
```


Female medusa exile


