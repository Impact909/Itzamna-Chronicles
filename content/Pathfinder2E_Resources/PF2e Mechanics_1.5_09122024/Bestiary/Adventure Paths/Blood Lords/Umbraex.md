---
title: "Umbraex"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HrMVfCFTN1ynLTP9" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/darvakka
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Umbraex"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Umbraex"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[darvakka]]
trait_04: [[evil]]
trait_05: [[shadow]]
trait_06: [[undead]]
trait_07: [[unholy]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Greater Darkvision, Lifesense 100 Feet"
languages: "Chthonian, Common, Diabolic, Necril; (can&#x27;t speak any language); telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +36, Athletics: +38, Intimidation: +40, Religion: +36, Shadow Plane Lore: +39, The Void Lore: +37"
abilityMods: [9, 7, 10, 8, 7, 8]
speed: 25 feet,  fly 70 feet
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +38, __Ref__ +32, __Will__ +35"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450, ashen rise, void healing, regeneration 20 (deactivated by fire or holy); __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 15, holy 15, silver 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 100 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Fire or Holy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Ashen Rise"
    desc: " (divine) When an umbraex is destroyed, its body discorporates into fine ash before being restored, fully healed, 1d4 rounds later. An umbraex can't use this ability as long as its remains are within an area consecrated to a good deity or an area of bright light. The umbraex can't use Ashen Rise again for 1 day."

  - name: "Entropy's Shadow"
    desc: " (aura,divine,void) 40 feet. Umbraex leak entropy and corruption from their very being. A living creature entering or starting its turn in the aura takes 8d6 void damage with a DC 42 Fortitude check. If it fails, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute and pulled 10 feet toward the vanyver."

  - name: "Sunlight Powerlessness"
    desc: "  An umbraex caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+38 (magical, reach 20 feet)\n__Damage__  2d10 + 12 piercing 2d10 cold 2d10 void"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+38 (agile, magical, reach 20 feet)\n__Damage__  2d8 + 10 piercing 2d10 cold 2d10 void"

  - name: "**Ranged** `pf2:1` Icy Blast"
    desc: "+37 (cold, magical, range increment 60 feet)\n__Damage__  8d6 cold 2d10 void"

  - name: "Divine Innate Spells"
    desc: "DC 44, attack +36; __9th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Harm|Harm (x3)]]_; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (to the Universe, Void, or Netherworld only)]]_, _[[Spells/Truesight|True Seeing]]_; __4th __  _[[Spells/Darkness|Darkness (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Life-Siphoning Screech"
    desc: "`pf2:3` (occult) The umbraex Flies, shrieking as it passes its enemies. Creatures within 20 feet of the umbraex's flight path take 22d6 mental damage depending on their DC 45 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is [[Conditions/Drained|Drained 1]].\n\n**Failure** The creature takes full damage and is [[Conditions/Drained|Drained 2]].\n\n**Critical Failure** The creature takes double damage and is drained 2 and [[Conditions/Doomed|Doomed 1]]."
 
```

```encounter-table
name: Umbraex
creatures:
  - 1: Umbraex
```



An umbraex appears at first glance to be a massive, majestic bird, much like a phoenix. Instead of compassion and warmth, however, it seethes with cold and hate. The umbraex is among the largest of the nihilistic undead called darvakkas.
