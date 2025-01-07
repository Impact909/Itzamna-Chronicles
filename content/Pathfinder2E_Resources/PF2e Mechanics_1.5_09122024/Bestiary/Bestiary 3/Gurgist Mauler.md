---
title: "Gurgist Mauler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.F6JWENlLRLLQTNjo" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mortic
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Gurgist Mauler"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Gurgist Mauler"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[mortic]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Arcana: +13, Athletics: +17, Crafting: +15, Deception: +14, Medicine: +12, Performance: +12"
abilityMods: [5, 2, 4, 3, 4, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +12, __Will__ +16"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, void healing; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Maul|+1 Maul]], [[Equipment/Hide Armor|Hide Armor]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "Nourishing Feast"
    desc: "  The gurgist spends 1 hour consuming 1 Bulk of raw meat to reverse their body's putrescence. For 1 hour, the gurgist appears to be a pale, bloated human. They have an automatic result of 32 on Deception checks and DCs to pass as a non-mortic human.\n\nWhile under the effects of Nourishing Feast, Rotting Flesh ceases to function."

abilities_mid:
  - name: ""
  - name: "Consecration Vulnerability"
    desc: "  A gurgist in a place of worship dedicated to a non-evil deity or on sacred ground, such as an area blessed by [[Spells/Anointed Ground|Anointed Ground]], is [[Conditions/Slowed|Slowed 1]]."

  - name: "Rotting Flesh"
    desc: "  Any creature that hits the gurgist with an unarmed attack, tries to [[Actions/Grapple|Grapple]] them, or otherwise touches the gurgist is covered with rotten flesh and putrid fluids.\n\nThe creature must succeed at a DC 22 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+18 (magical, shove)\n__Damage__  1d12 + 8 bludgeoning plus knockdown"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 (agile)\n__Damage__  1d8 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+14 (deadly d10, propulsive, range increment 60 feet)\n__Damage__  1d6 + 5 piercing"

  - name: "Calculated Blow"
    desc: "`pf2:2`  The gurgist makes a melee Strike, aiming for their target's weak points and taking their time to line up a precise blow. If this Strike hits, the gurgist deals an additional 1d8 precision damage, and the target must succeed at a DC 23 Fortitude check save or become [[Conditions/Clumsy|Clumsy 2]] for 1 minute."

  - name: "Death Gasp"
    desc: "`pf2:1` (divine) The gurgist draws in a deep breath and holds it, temporarily suspending their biological processes and becoming undead.\n\nThe gurgist gains the undead trait and becomes immune to bleed, death effects, disease, [[Conditions/Paralyzed|Paralyzed]], poison, and sleep. Any such effects the gurgist is currently suffering from are suspended, but take effect again once they take a breath.\n\nDeath Gasp lasts as long as the gurgist holds their breath (up to 9 rounds).\n\n[[Bestiary Effects/Effect_ Death Gasp|Effect: Death Gasp]]"

  - name: "Tackle"
    desc: "`pf2:2`  The gurgist Strides twice and then attempts to [[Actions/Grapple|Grapple]] a creature. On a success, the target is also knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Gurgist Mauler
creatures:
  - 1: Gurgist Mauler
```



Humans that become mortics are known as gurgists. They retain their personalities and intelligence, but their bodies rot with every beat of their heart. Gurgists ceaselessly crave raw meat; consuming large quantities can slow, or even reverse, their body's putrefaction for a short time. A gurgist that refuses to consume raw meat rots to death.

Unlike other mortics, gurgists are capable of sating their hunger without resorting to depravity, making them more likely to be nonevil compared to other mortics. Most gurgists hunt and raise livestock for food-including animals many consider too dangerous to tame. To battle their constant hunger, many take up a single craft, hobby, or performing art to obsess over until the drive to create overcomes the urge to consume. Many study magic or medicine, researching methods to reverse their condition or suspend their putrescence. Others cling to religion, uttering prayers despite the pain and begging the gods to cleanse them of evil.

Nearly all gurgists are disgusted by their clumsy, rotting bodies. They shroud themselves in fine clothes and cover their faces with elaborate masks. Most consider their mask their true face.

* * *

Mortics are humanoids overwhelmed by void energy who still cling to life, surviving as twisted amalgams of living and undead. Though they feel unnatural cravings and resemble corpses, mortics live, breathe, eat, sleep, and procreate. However, a mortic can suspend their living functions simply by holding their breath, becoming more like a true undead.

Mortics are largely new to Golarion, with most created in droves when the Whispering Tyrant destroyed entire cities with his Radiant Fire, a magical explosion fueled by the collision of void and vitality energy. From among the corpses of these tragedies rose mortics, living survivors mistaken for corpses and left behind as a result. They found themselves in a twilight state-neither fully alive or undead. The necrotic pollutants of the Gravelands and the Isle of Terror continue to create mortics, seeping into neighboring lands through the air, earth, and water to infect the populace. Though most of the living in these lands fear becoming transformed, some believe becoming a mortic is their best chance of survival in the face of the encroaching hordes of the dead.

A mortic's powers differ by ancestry, though they do have a few commonalities. Reading or hearing scripture induces headaches, and they experience great discomfort when treading upon sacred ground. For those who were religious in life, these new changes can be devastating.
