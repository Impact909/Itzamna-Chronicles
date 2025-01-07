---
title: "Lifeleecher Brawler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.udyjHX1B4JwCi1xZ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mortic
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Lifeleecher Brawler"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Lifeleecher Brawler"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[mortic]]
trait_05: [[orc]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +16, Survival: +15"
abilityMods: [6, 4, 6, 3, 3, 4]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +20, __Ref__ +16, __Will__ +13"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165, void healing"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+1 Striking Composite Shortbow]], [[Equipment/Breastplate|Breastplate]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Consecration Vulnerability"
    desc: "  A lifeleecher in a place of worship dedicated to a non-evil deity or on sacred ground, such as an area blessed by [[Spells/Anointed Ground|Anointed Ground]], is [[Conditions/Slowed|Slowed 1]]."

  - name: "[[Bestiary Ability Glossary/Ferocity|Mortic Ferocity]]"
    desc: "`pf2:r`  The lifeleecher is also surrounded by visibly flickering fragments of the souls they've consumed, becoming [[Conditions/Concealed|Concealed]] until the end of their next turn.\n* * *\n\n**Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "Soul Feast"
    desc: "`pf2:r` (divine,void) **Trigger** A creature adjacent to the lifeleecher dies\n* * *\n\n**Effect** The lifeleecher consumes a portion of the creature's soul, regaining 2d8 healing Hit Points."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tusk"
    desc: "+20 ()\n__Damage__  2d6 + 6 piercing plus leech-essence"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d8 + 6 slashing 1d6 bleed"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+19 (deadly d10, magical, propulsive, range increment 30 feet)\n__Damage__  2d6 + 3 piercing"

  - name: "Death Gasp"
    desc: "`pf2:1` (divine) The lifeleecher draws in a deep breath and holds it, temporarily suspending their biological processes and becoming undead.\n\nThe lifeleecher gains the undead trait and becomes immune to bleed, death effects, disease, [[Conditions/Paralyzed|Paralyzed]], poison, and sleep. Any such effects the angheuvore is currently suffering from are suspended, but take effect again once they take a breath.\n\nDeath Gasp lasts as long as the lifeleecher holds their breath (up to 11 rounds).\n\n[[Bestiary Effects/Effect_ Death Gasp|Effect: Death Gasp]]"

  - name: "Ghost Hunter"
    desc: "  The lifeleecher's tusks have the effects of the _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune on attacks against incorporeal undead."

  - name: "Leech Essence"
    desc: " (divine) When the lifeleecher damages a living or undead creature with their jaws Strike, they drain the target's life essence.\n\nThe lifeleecher gains 5 temporary Hit Points that last for 1 minute, and the target must succeed at a DC 24 Fortitude check save or become [[Conditions/Drained|Drained 1]] if living, or [[Conditions/Stunned|Stunned 1]] if undead. If the target was already drained or stunned, the value of this condition instead increases by 1, to a maximum of 3."
 
```

```encounter-table
name: Lifeleecher Brawler
creatures:
  - 1: Lifeleecher Brawler
```



Lifeleechers are mortic orcs with gray flesh, sharp claws, and protruding tusks. Resilient and strong, they devour the vital essence of their enemies, which heals their wounds and shackles those souls to the lifeleecher.

Many orcs believe lifeleechers are possessed by the spirits of fallen orc warriors too stubborn to die. Feared and revered, lifeleechers often rise to positions of power in their holds and battle on the front lines against the undead armies of the Whispering Tyrant.

* * *

Mortics are humanoids overwhelmed by void energy who still cling to life, surviving as twisted amalgams of living and undead. Though they feel unnatural cravings and resemble corpses, mortics live, breathe, eat, sleep, and procreate. However, a mortic can suspend their living functions simply by holding their breath, becoming more like a true undead.

Mortics are largely new to Golarion, with most created in droves when the Whispering Tyrant destroyed entire cities with his Radiant Fire, a magical explosion fueled by the collision of void and vitality energy. From among the corpses of these tragedies rose mortics, living survivors mistaken for corpses and left behind as a result. They found themselves in a twilight state-neither fully alive or undead. The necrotic pollutants of the Gravelands and the Isle of Terror continue to create mortics, seeping into neighboring lands through the air, earth, and water to infect the populace. Though most of the living in these lands fear becoming transformed, some believe becoming a mortic is their best chance of survival in the face of the encroaching hordes of the dead.

A mortic's powers differ by ancestry, though they do have a few commonalities. Reading or hearing scripture induces headaches, and they experience great discomfort when treading upon sacred ground. For those who were religious in life, these new changes can be devastating.
