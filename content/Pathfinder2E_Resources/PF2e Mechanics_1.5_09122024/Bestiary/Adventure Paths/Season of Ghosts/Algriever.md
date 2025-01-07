---
title: "Algriever"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vAxHpSTlL3gthLNZ" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/spirit
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Algriever"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #199: To Bloom Below the Web"
name: "Algriever"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[spirit]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Intimidation: +19, Religion: +19, Stealth: +21, Survival: +21"
abilityMods: [4, 4, 4, 0, 6, 2]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #199: To Bloom Below the Web_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +15, __Ref__ +17, __Will__ +21"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Acolyte's Defense"
    desc: "`pf2:r` (attack,move) **Requirements** The algriever is bonded with a shrine\n\n**Trigger** A creature within sight of the algriever damages, desecrates, or defiles their bonded shrine\n* * *\n\n**Effect** The algriever Strides toward the creature; this movement doesn't trigger reactions. The algriever marks the creature as its enemy and gains a +2 status bonus to attack rolls against that enemy until they select a new enemy with Acolyte's Defense."

  - name: "Shrine Bond"
    desc: "  The algriever bonds with a shrine after they spend 24 hours at the site. While bonded, the algriever gains a +2 circumstance bonus to Perception checks and skill checks."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+19 (agile, magical)\n__Damage__  2d12 + 7 piercing plus algriever-venom"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+19 (range increment 30 feet)\n__Damage__ "

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +20; __5th __  _[[Spells/Crisis of Faith|Crisis of Faith]]_; __4th __  _[[Spells/Anathematic Reprisal|Anathematic Reprisal (x3)]]_"

  - name: "Algriever Venom"
    desc: " (mental,poison) **Saving Throw** DC 28 Will check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 mental\n\n**Stage 2** 2d6 mental and [[Conditions/Stupefied|Stupefied 1]]\n\n**Stage 3** 2d6 mental and [[Conditions/Stupefied|Stupefied 2]]"

  - name: "Pilgrim's Ward"
    desc: "`pf2:2` (divine) **Frequency** once per month\n* * *\n\n**Effect** The algriever touches a willing creature and fills it with reverence for their bonded shrine. As long as the target creature obeys the edicts and anathemas of the algriever's bonded shrine, or until that algriever grants Pilgrim's Ward to a different creature, that creature gains a +1 status bonus to all Religion checks and Will saves.\n\n[[Bestiary Effects/Effect_ Pilgrim's Ward|Effect: Pilgrim's Ward]]"

  - name: "Web Trap"
    desc: "  A creature hit by an algriever's web Strike is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface until it [[Actions/Escape|Escapes]] (DC 28)."
 
```

```encounter-table
name: Algriever
creatures:
  - 1: Algriever
```



Some mistake these spiderlike spirits as scavengers looking to loot abandoned shrines, but they're actually the opposite: self-appointed guardians of forgotten places of worship, defending the sanctity of discarded faiths and tending sites that have no caretakers. Sometimes, an algriever's duties are tinged with sadness and grief, as they mourn the loss of those who once attended their chosen shrine. Others are filled with frustration and rage, viewing any who stumble upon their shrine as lapsed faithful at best or blasphemers at worse—sinners who deserve punishment.

Algrievers have little interest in living creatures until they wander into their territory. Once an algriever's shrine has been breached, they block passage until the interlopers pay their respects. Aggressive algrievers steal from travelers or take hostages until their demands for an offering are satisfied. When algrievers suspect someone of committing blasphemy, no gifts can slake their thirst for vengeance.

## Reactive Punishment

An algriever follows the edicts and anathemas of the deity or faith of the shrine to which they're bonded, although they remain neutral in alignment. Regardless of how large the shrine is, an algriever chooses three Medium or smaller objects in the shrine as their own focus for defense, and can use Acolyte's Defense against any creature that touches or disturbs those objects.
