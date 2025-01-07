---
title: "Grippli Jinxer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5LpHvJUtTIEUu13c" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/grippli
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Grippli Jinxer"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #170: Spoken on the Song Wind"
name: "Grippli Jinxer"
level: "Creature 6"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[grippli]]
trait_03: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Grippli"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +12, Intimidation: +12, Nature: +14, Occultism: +10, Stealth: +14"
abilityMods: [2, 4, 2, 0, 4, 0]
speed: 25 feet,  climb 20 feet
sourcebook: "_Pathfinder #170: Spoken on the Song Wind_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +14, __Will__ +16"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "8x [[Equipment/Dart|Dart]], [[Equipment/Staff|Staff]]"
abilities_mid:
  - name: ""
  - name: "Hypnotic Tattoos"
    desc: "`pf2:r`  **Trigger** A hostile creature targets the jinxer with a melee Strike\n* * *\n\n**Effect** Tattoos on the jinxer's body swirl and shift in mesmerizing patterns. The creature must attempt a DC 22 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 1 hour.\n\n**Success** The creature is unaffected and is temporarily immune for 1 minute.\n\n**Failure** The creature treats the jinxer as [[Conditions/Concealed|Concealed]] until the end of its turn.\n\n**Critical Failure** The creature treats the jinxer as [[Conditions/Hidden|Hidden]] until the end of its turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+14 (two-hand d8)\n__Damage__  1d4 + 6 bludgeoning plus baneback-poison"

  - name: "**Ranged** `pf2:1` Dart"
    desc: "+16 (agile, thrown 20 ft.)\n__Damage__  1d4 + 6 piercing plus baneback-poison"

  - name: "Occult Spontaneous Spells"
    desc: "DC 24, attack +16; __3rd __ (3 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __ (3 slots) _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Summon Animal|Summon Animal (Giant Cockroach, Giant Fly or Giant Tick only)]]_, _[[Spells/Vomit Swarm|Vomit Swarm]]_; __1st __ (3 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Spider Sting|Spider Sting]]_\n__Cantrips__  __(3rd)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Baneback Poison"
    desc: " (poison) **Saving Throw** DC 24 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d4 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 3d4 poison damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)\n\n**Stage 3** 4d4 poison damage, [[Conditions/Stupefied|Stupefied 3]], and [[Conditions/Off-Guard|Off-Guard]] (1 round)"

  - name: "Curse of Baneful Venom"
    desc: "`pf2:3` (occult) The jinxer magically intensifies toxins in their foes. Creatures within 30 feet of the jinxer that are currently afflicted by a poison immediately attempt their next saving throw against the poison with a -2 status penalty, then are temporarily immune to Curse of Baleful Venom for 1 hour.\n\n[[Bestiary Effects/Effect_ Curse of the Baneful Venom|Effect: Curse of the Baneful Venom]]"

  - name: "Jungle Stride"
    desc: "  Gripplis ignore difficult terrain in forests and jungles."
 
```

```encounter-table
name: Grippli Jinxer
creatures:
  - 1: Grippli Jinxer
```



Baneback gripplis with innate magical ability may find themselves drawn to vile magic dealing with poison, vermin, and ill luck. Those who revel in the dreadful legends surrounding their kind often worship evil gods or demons associated with poison, tattooing themselves with mystic symbols to gain powerful control over toxins.

* * *

Gripplis are small, frog-like humanoids native to tropical rainforests. Most gripplis live in tight-knit treetop villages and survive primarily as hunters and gatherers. While most communities are peaceful and harmonious, a lingering superstition has led to a unique group of these people being cut off from their communal bonds and forced to make their own way in the world.

Among the many gripplis who possess poison glands, a rare subset secrete mind-altering chemicals. These gripplis aren't immune to this toxin, and over many years it may render them erratic at best and selfishly misanthropic at worst. Other gripplis view these "banebacks" as cursed and react to their presence with fear and mistrust, which usually leads to their censure and exile. They soon find that their natural skills as hunters, combined with an unlimited supply of their potent toxin, make them ideally suited to taking on work as mercenaries, bandits, or assassins.
