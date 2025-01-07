---
title: "Frostripper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Z47hULkcOZ9qhq6M" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Frostripper"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Frostripper"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[evil]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Jotun, Skald"
skills:
  - name: "Skills"
    desc: "Athletics: +29, Deception: +24, Intimidation: +26, Religion: +24, Stealth: +22, Survival: +26"
abilityMods: [7, 5, 7, 1, 5, 5]
speed: 40 feet,  swim 20 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +20, __Will__ +22"
hp: 232
health:
  - name: ""
  - name: HP
    desc: "232; __Resistances__ cold 15"
abilities_top:
  - name: ""

  - name: "Voice Imitation"
    desc: "  Kokogiaks can mimic the sounds of a person in distress by attempting a Deception check to [[Actions/Lie|Lie]]. The kokogiak has a +4 circumstance bonus to this check."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (reach 20 feet)\n__Damage__  3d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (reach 15 feet)\n__Damage__  3d8 + 13 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 33, attack +24; __6th __  _[[Spells/Howling Blizzard|Howling Blizzard]]_; __5th __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Wall of Ice|Wall of Ice]]_\n__Cantrips__  __(6th)__ _[[Spells/Frostbite|Frostbite]]_"

  - name: "Mauling Rush"
    desc: "`pf2:3`  The kokogiak Strides up to its Speed. It can make up to four claw Strikes at any point during this movement, each against a different target. These attacks count toward the kokogiak's multiple attack penalty, but the multiple attack penalty doesn't increase until after the kokogiak makes all of its attacks."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The kokogiak's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Tormented Snarl"
    desc: "`pf2:2` (auditory,illusion,mental,primal) Using their voice imitation abilities, a kokogiak emits the horrific wails of its former victims. Each creature within 120 feet takes 4d6 mental damage and must attempt a DC 33 Will check save.\n\nA creature frightened by this ability is [[Conditions/Off-Guard|Off-Guard]] to the kokogiak.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 1 minute.\n\n**Success** The creature takes half damage and becomes [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes full damage and becomes [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature takes double damage, becomes [[Conditions/Frightened|Frightened 3]], and is [[Conditions/Fleeing|Fleeing]] until the end of its next turn."

  - name: "Trackless Step"
    desc: "  The kokogiak always gains the benefits of [[Actions/Cover Tracks|Cover Tracks]] in natural surroundings, even while moving at full speed."
 
```

```encounter-table
name: Frostripper
creatures:
  - 1: Frostripper
```


Variant kokogiak

As deadly on land as in the water, kokogiaks are one of the most feared predators of the tundra. From a distance they might be mistaken for a frightfully large polar bear, but anyone unfortunate enough to see one up close will notice the creature's six additional legs and disturbingly elongated neck before meeting an untimely end. These ursine monstrosities stalk their prey tirelessly across ice and snow; they're also powerful swimmers, lurking under the ice to burst up and ambush unsuspecting creatures on the surface or diving for a marine meal.

As if numerous claws and a brutal bite weren't concerning enough, these nightmare-inducing creatures can be wickedly deceptive, luring their prey out in winter storms. The cunning kokogiak imitates the sounds of a creature in distress, deceiving its target into abandoning the safety of their shelter and embarking on an ill-fated rescue attempt. Those who live in arctic realms have learned to respond with caution upon hearing cries for help during a long winter night.
