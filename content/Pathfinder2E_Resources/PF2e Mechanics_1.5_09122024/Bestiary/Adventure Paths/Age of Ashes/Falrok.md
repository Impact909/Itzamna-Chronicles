---
title: "Falrok"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iR4egivmqjNmn2NM" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Falrok"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Falrok"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Draconic, Dwarven, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Crafting: +24, Deception: +27, Diplomacy: +27, Society: +24, Stealth: +29, Saggorak Lore: +24"
abilityMods: [4, 8, 5, 3, 2, 6]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +26, __Ref__ +29, __Will__ +23; lazurite-infused flesh"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ vitality 15"
abilities_top:
  - name: ""

  - name: "Lazurite-Infused Flesh"
    desc: "  Falrok's flesh is infused with lazurite, and he gains the benefits undead creatures gain from this mineral at all times. When in an area infused with lazurite, such as the Sanctum of the Starved, these benefits increase to a +3 circumstance bonus to saving throws against vitality effects. This infusion also grants Falrok his resistance to vitality damage."

abilities_mid:
  - name: ""
  - name: "Opportune Backstab"
    desc: "`pf2:r`  **Trigger** A creature within Falrok's melee reach is hit by a melee attack from one of his allies.\n* * *\n\n**Effect** When Falrok's enemy is hit by one of his allies, he capitalizes upon the distraction, making a Strike against the triggering creature."

  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 34 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (finesse)\n__Damage__  3d8 + 12 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, finesse)\n__Damage__  3d6 + 12 slashing plus ghast-paralysis"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** Falrok is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** Falrok devours a chunk of the corpse and regains 8d6 healing Hit Points.\n\nHe can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease,virulent) **Saving Throw** DC 34 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 34 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Scoundrel"
    desc: "  When Falrok successfully [[Actions/Feint|Feints]], the target is [[Conditions/Off-Guard|Off-Guard]] against melee attacks he attempts against it until the end of his next turn. On a critical success, the target is off-guard against all melee attacks until the end of their next turn, not just Falrok's."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  Falrok deal 4d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Swift Leap"
    desc: "`pf2:1` (move) Falrok jumps up to half his Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Falrok
creatures:
  - 1: Falrok
```




