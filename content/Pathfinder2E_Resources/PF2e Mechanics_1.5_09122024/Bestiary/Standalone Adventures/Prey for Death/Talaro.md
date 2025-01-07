---
title: "Talaro"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hc7UP2hTcwJQbdms" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kitsune
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Talaro"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Talaro"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[kitsune]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Low-Light Vision"
languages: "Common, Elven, Mwangi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +27, Deception: +26, Religion: +23, Society: +23, Stealth: +26, Thievery: +26, Achaekek Lore: +25"
abilityMods: [4, 5, 2, 2, 2, 3]
speed: 30 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +25, __Ref__ +30, __Will__ +24"
hp: 272
health:
  - name: ""
  - name: HP
    desc: "272"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sawtooth Saber|+2 Greater Striking Extending Sawtooth Saber]], [[Equipment/Sawtooth Saber|+2 Striking Wounding Sawtooth Saber]], 5x [[Equipment/Shuriken|Shuriken (With Blightburn Resin)]], [[Equipment/Assassin's Skin|Assassin's Skin]], Assassination Contract, [[Equipment/Explorer's Yurt|Explorer's Yurt]], [[Equipment/Mask of the Mantis (Greater)|Mask of the Mantis (Greater)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Nimble Dodge|Prescient Dodge]]"
    desc: "`pf2:r`  **Trigger** A creature attempts to Strike Talaro and he's not [[Conditions/Off-Guard|Off-Guard]]\n* * *\n\n**Effect** Talaro anticipates the Strike and gains a +2 circumstance bonus to AC against the triggering attack. He can use this once the results of the attack are known. If the attack misses, Talaro can do a quick backflip as a free action to Step."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Extending Sawtooth Saber"
    desc: "+28 (agile, finesse, magical, twin)\n__Damage__  3d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Wounding Sawtooth Saber"
    desc: "+28 (agile, finesse, magical, twin)\n__Damage__  2d6 + 12 slashing 1d6 bleed"

  - name: "**Ranged** `pf2:1` Shuriken"
    desc: "+26 (agile, monk, reload 0, thrown 20 ft.)\n__Damage__  1d4 + 10 piercing plus blightburn-resin"

  - name: "Divine Prepared Spells"
    desc: "DC 33, attack +25; __4th __  _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Mist|Mist]]_; __1st __  _[[Spells/Sure Strike|Sure Strike]]_\n__Cantrips__  __(8th)__ _[[Spells/Figment|Figment]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Red Mantis Focus Spells"
    desc: "1 Focus Point, DC 33, attack +25; __8th __  _[[Spells/Achaekek's Clutch|Achaekek's Clutch]]_"

  - name: "Blightburn Resin"
    desc: " (alchemical,contact,poison) **Saving Throw** DC 30 Fortitude check\n\n**Onset** 1 minute\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 6d6 poison damage (1 round)\n\n**Stage 2** 7d6 poison damage (1 round)\n\n**Stage 3** 9d6 poison damage (1 round)"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) You transform into a specific alternate form determined by your heritage. If your heritage doesn't list a form, your alternate form is a tailless form, which is a common Medium humanoid ancestry prevalent where you grew up (typically human). This form is the same age and body type as your true form and has roughly analogous physical traits, such as hair color. Using Change Shape counts as creating a disguise for the Impersonate use of Deception. You lose any unarmed Strikes you gained from a kitsune heritage or ancestry feat in this form. You can remain in your alternate form indefinitely, and you can shift back to your true kitsune form by using this action again.\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Crimson Shroud"
    desc: "`pf2:1` (healing,magical) **Frequency** five times per day\n* * *\n\n**Effect** Talaro shrouds himself in a veil of red mist for 1 minute. While the shroud is active, he gains fast healing 7. He can Interact with his shroud, swirling it around himself to gain a +1 circumstance bonus to AC until the beginning of his next turn. If he dies while the shroud is active, his entire body vanishes into red mist, leaving behind only his gear."

  - name: "Prayer Attack"
    desc: "`pf2:1` (concentrate) **Requirements** Talaro wields a sawtooth saber in each hand\n* * *\n\n**Effect** Talaro attempts to [[Actions/Feint|Feint]] an enemy within 30 feet. If the Feint is successful, his next successful Strike with a sawtooth saber in that same turn deals 2d6 persistent bleed damage to the target. In addition, provided he remains visible to that target and that target remains within 30 feet of him, additional Prayer Attacks against that target automatically cause them to become [[Conditions/Off-Guard|Off-Guard]] against Talaro's attacks until the end of their turn."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  Talaro deals an extra 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Surprise Attack"
    desc: "  On the first round of combat, creatures that haven't acted yet are [[Conditions/Off-Guard|Off-Guard]] to Talaro."
 
```

```encounter-table
name: Talaro
creatures:
  - 1: Talaro
```


Male kitsune assassin


