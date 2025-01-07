---
title: "Common Eurypterid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.00xq66zAvMBKqa0M" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Common Eurypterid"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Common Eurypterid"
level: "Creature -1"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 2
perception:
  - name: "Perception"
    desc: "+2; Low-Light Vision, Wavesense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +4, Stealth: +4"
abilityMods: [2, 0, 3, -5, 0, -3]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +7, __Ref__ +4, __Will__ +2"
hp: 9
health:
  - name: ""
  - name: HP
    desc: "9"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 30 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Stinger Only)]]"
    desc: "`pf2:r`  Stinger only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+6 ()\n__Damage__  1d6 + 2 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+6 ()\n__Damage__  1d4 + 2 piercing plus eurypterid-venom"

  - name: "Eurypterid Venom"
    desc: " (poison) **Saving Throw** DC 14 Fortitude check\n* * *\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d4 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage (1 round)\n\n**Stage 3** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Common Eurypterid
creatures:
  - 1: Common Eurypterid
```



The smallest of the giant eurypterids can grow to about the size of a large dog. These eurypterids are a staple food for people living in marshlands, who add the meat to heavily spiced stews, but they're otherwise considered dangerous pests.

* * *

Fearsome predators and durable pests, eurypterids are hard-carapaced arthropods sometimes referred to as sea scorpions. Though aquatic creatures, they have robust respiratory systems that allow them to survive indefinitely on land. All eurypterids possess claws as well as stingers that can inject venom.
