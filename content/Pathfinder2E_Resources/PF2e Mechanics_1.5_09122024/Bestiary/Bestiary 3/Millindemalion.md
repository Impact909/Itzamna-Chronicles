---
title: "Millindemalion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AV2kypBThazThHmY" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Millindemalion"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Millindemalion"
level: "Creature 13"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[fey]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Crafting: +28, Occultism: +24, Society: +24, Stealth: +27, Millinery Lore: +30"
abilityMods: [4, 8, 1, 7, 4, 2]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +20, __Ref__ +27, __Will__ +23"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|+1 Striking Felt Shears (as Dagger)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  The millindemalion can use Hat Toss against the triggering creature instead of making a Strike, making a melee attack roll with a +27 modifier to do so.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Unsettling Mind"
    desc: "  Attempting to touch the frenetic mind of a millindemalion is a dangerous task. When the millindemalion succeeds at a saving throw against a mental effect, the creature originating that effect takes 4d6 mental damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Felt Shears"
    desc: "+27 (agile, finesse, magical, versatile s)\n__Damage__  2d4 + 14 piercing 1d6 mental"

  - name: "**Ranged** `pf2:1` Felt Shears"
    desc: "+27 (agile, magical, thrown 10 ft.)\n__Damage__  2d4 + 10 piercing 1d6 mental"

  - name: "Hat Toss"
    desc: "`pf2:1` (manipulate,mental,primal) The millindemalion quickly crafts a mind-altering hat in combat and tosses it onto a target with a flick of their wrist. The millindemalion chooses one of the effects below and makes a ranged attack roll with a +27 modifier and a range increment of 20 feet.\n\nOn a hit, the target must succeed at a DC 33 Will check saving throw or experience the listed effect for 1d4+1 rounds. If the millindemalion critically succeeds at the ranged Strike, the target takes a -4 circumstance penalty on the save.\n\nA target can only wear one millindemalion hat at a time; a new hat replaces any previous hat. The hat can't be removed before the condition ends, but when the condition ends (or on a successful save), the hat falls to pieces.\n\n*   **Befuddling Bowler** The hat clouds the target's mind; the target becomes [[Conditions/Stupefied|Stupefied 2]].\n*   **Bewitching Beret** The target is infatuated with their new hat and its creator, becoming [[Conditions/Fascinated|Fascinated]] by the millindemalion and the beret.\n*   **Dazzling Deerstalker** The target can barely see with the hat falling down over its eyes and gains the [[Conditions/Dazzled|Dazzled]] condition.\n*   **Fettering Fedora** The target feels a heavy weight pressing down on them from the hat and takes a -10-foot circumstance penalty to their Speeds.\n*   **Tiring Tricorne** The target grows sleepy and becomes [[Conditions/Slowed|Slowed 1]].\n\n[[Bestiary Effects/Effect_ Fettering Fedora|Effect: Fettering Fedora]]"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A millindemalion deals an extra 4d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Millindemalion
creatures:
  - 1: Millindemalion
```



Millindemalion are cruel fey tricksters capable of causing mayhem with their magical, mind-altering hats. Many folk tales from around the world speak of industrious fey who help struggling crafters-cobblers, milliners, tailors, and so on-during the night, creating quality wares in secret for no payment greater than a crumb of bread or a saucer of cream. These stories hold a grain of truth, as gracious fey do occasionally journey from the First World to aid a humble artisan on a whim, for bribes of food, or sometimes even as part of a concerted effort to spread beauty throughout the world. However, when an artisan becomes too reliant on this help, their friendly fey helper might become warped and twisted with resentment and neglect. Eventually, they could transform into a cruel prankster who delights in punishing mortals who dare task a fey with such mundane work. The millindemalion is the result of a kindly, hat-making fey undergoing such a transformation. Some scholars believe this erratic behavior is caused by the preponderance of quicksilver used in most millinery.
