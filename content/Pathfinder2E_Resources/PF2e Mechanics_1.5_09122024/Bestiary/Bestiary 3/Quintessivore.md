---
title: "Quintessivore"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5FMylgMZ0T9p5kwD" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Quintessivore"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Quintessivore"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[evil]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Arcana: +25, Athletics: +17, Intimidation: +19, Stealth: +20"
abilityMods: [3, 6, 6, 7, 3, 3]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +20, __Will__ +21"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scroll of 4th-rank Spell|Scroll of Dimensional Anchor (Level 4)]], [[Equipment/Scroll of 4th-rank Spell|Scroll of Fly (Level 4)]]"
abilities_mid:
  - name: ""
  - name: "Instant Suspension"
    desc: "`pf2:r`  **Trigger** The quintessivore reduces a creature within 15 feet of it to 0 Hit Points\n* * *\n\n**Effect** The quintessivore uses Suspend Soul, targeting the creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blade-Leg"
    desc: "+22 (finesse, magical)\n__Damage__  1d10 + 9 slashing plus tattered-soul 1d10 void plus tattered-soul"

  - name: "Arcane Prepared Spells"
    desc: "DC 29, attack +21; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Magic Passage|Passwall]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Enervation|Enervation]]_; __3rd __  _[[Spells/Slow|Slow]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Translate|Comprehend Language]]_, _[[Spells/See the Unseen|See Invisibility]]_, _[[Spells/Web|Web]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall]]_, _[[Spells/Fleet Step|Fleet Step]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Feed on Quintessence"
    desc: " (arcane,exploration,manipulate) Over the course of 1 hour, the quintessivore removes and deconstructs the soul of a creature. The creature must either be captive or have been dead for no more than 2 hours before the start of the process. At the end of the hour, the quintessivore consumes the quintessence of the creature's soul.\n\nFor the next month, it gains a +1 status bonus to its spell DC and spell attack roll, and it adds 6th-rank [[Spells/Never Mind|Never Mind]] and [[Spells/Vampiric Exsanguination|Vampiric Exsanguination]] to its arcane prepared spells.\n\nDeconstructing a soul maps the unique properties of the creature's soul into the quintessivore's blade-legs. The soul can be reconstructed by binding it to quintessence. A dead quintessivore's soul flees its body as pure quintessence suitable for this purpose."

  - name: "Suspend Soul"
    desc: "`pf2:1` (arcane) The quintessivore suspends the life processes of a dying creature within 15 feet of it. The creature can't decrease or increase its HP or dying value for 10 minutes. The creature can attempt a DC 29 Will check save to avoid this effect. If the creature receives magical healing, it can attempt a new save, ending the effect and being healed normally on a success.\n\nThe effect ends if the quintessivore uses Suspend Soul again."

  - name: "Tattered Soul"
    desc: "  A creature hit by the quintessivore's blade-leg Strike must succeed at a DC 29 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure). If the creature is already drained, it's immune to this effect."
 
```

```encounter-table
name: Quintessivore
creatures:
  - 1: Quintessivore
```



Quintessivores are cunning creatures that wield arcane magic and scalpel-sharp spider limbs that can rend one's soul just as easily as flesh. A quintessivore doesn't immediately kill its prey-it drags the creature to its lair and separates the victim's soul from their body with its bladed limbs. The flicking blades then pull out the creature's individuality, reducing the soul down to pure soul-stuff called quintessence, which the quintessivore then consumes.
