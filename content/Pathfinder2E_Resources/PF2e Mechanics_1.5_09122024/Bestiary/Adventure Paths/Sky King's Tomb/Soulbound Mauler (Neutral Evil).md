---
title: "Soulbound Mauler (Neutral Evil)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0CVlRLuklfYnS7Gw" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2e/creature/type/soulbound
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Soulbound Mauler (Neutral Evil)"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Soulbound Mauler (Neutral Evil)"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[evil]]
trait_03: [[soulbound]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "one spoken by its creator (typically common)"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Occultism: +6, Stealth: +9"
abilityMods: [5, 3, 4, 0, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +14, __Ref__ +11, __Will__ +9"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72; __Immunities__  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void"
abilities_top:
  - name: ""

  - name: "Personality Cage"
    desc: "  A soulbound mauler encapsulates an entire soul within its soul focus gem, with that soul's personality and past shining through along with a confusing mix of fragmented memories and instincts. This causes a soulbound mauler to match the donor soul's alignment and gain the corresponding alignment traits. When the mauler doesn't have a soul bound, it's inanimate."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile, magical)\n__Damage__  2d6 + 5 bludgeoning plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 18, attack +10; __3rd __  _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __1st __  _[[Spells/Enfeeble|Ray of Enfeeblement (At Will)]]_"

  - name: "Eager Rend"
    desc: "`pf2:2`  The soulbound mauler has a living creature [[Conditions/Grabbed|Grabbed]].\n* * *\n\n**Effect** The soulbound mauler holds the creature it has grabbed and attempts to tear it in two. That creature takes 5d6 bludgeoning damage (basic DC 18 Fortitude check). On a critical failure, the target also becomes [[Conditions/Enfeebled|Enfeebled 1]]."

  - name: "Tethered Soul"
    desc: "  The soul focus gem that powers a soulbound mauler is tethered with eight ectoplasmic leashes inside an open cavity in the creature's chest. It can be targeted directly with a [[Actions/Disarm|Disarm]], [[Actions/Grapple|Grapple]], or [[Actions/Steal|Steal]] action. Rather than the normal result of these actions, the soulbound mauler takes 4d6 mental damage and is [[Conditions/Stunned|Stunned 1]] on a success; on a critical success, it takes 8d6 mental damage and is [[Conditions/Stunned|Stunned 2]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Soulbound Mauler (Neutral Evil)
creatures:
  - 1: Soulbound Mauler (Neutral Evil)
```



If a soulbound doll isn't large and strong enough for one's needs, there's the oversized soulbound mauler. An upgrade to the soulbound doll, this mannequin is powered by the entire soul of a sapient creature. Many a necromancer has attempted to use these constructs as a method to live forever, likely as a shortcut around the complicated and ultimately morbid path to lichdom. However, the soul within the mannequin has problems properly expressing itself and displays rudimentary control over the host, often resulting in childlike behavior anywhere from curious to sadistic.

Rather than embedding the soul focus gem in the construct's neck or chest, it's tethered by bands of ectoplasm within an exposed chamber on the mannequin's chest. Until the soulbound mauler is destroyed, the focus gem cannot be removed from the empty cavity in its chest. However, the gem can be displaced which causes the soulbound mauler significant anguish, not only damaging the connection between the gem and artificial body, but also impairing the construct's ability to function.

## Innate Spells

Like a soulbound doll, a soulbound mauler gains an additional 3rd-rank innate spell depending on its alignment, as listed below.

Lawful Good: [[Spells/Heal|Heal]]

Neutral Good: [[Spells/Jump|Jump]]

Chaotic Good: [[Spells/Haste|Haste]]

Lawful Neutral: [[Spells/Blindness|Blindness]]

Neutral: [[Spells/Shared Invisibility|Shared Invisibility]]

Chaotic Neutral: [[Spells/Shatter|Shatter]]

Lawful Evil: [[Spells/Slow|Slow]]

Neutral Evil: [[Spells/Stinking Cloud|Stinking Cloud]]

Chaotic Evil: [[Spells/Harm|Harm]]
