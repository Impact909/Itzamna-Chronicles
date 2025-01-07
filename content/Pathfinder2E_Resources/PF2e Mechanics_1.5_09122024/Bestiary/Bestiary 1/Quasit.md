---
title: "Quasit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2iLL6vno8g3vvrBR" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Quasit"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Quasit"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Chthonian, Common; telepathy (touch)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Arcana: +4, Deception: +7, Intimidation: +5, Religion: +5, Stealth: +7"
abilityMods: [-1, 4, 0, 1, 2, 2]
speed: 15 feet,  fly 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +4, __Ref__ +10, __Will__ +7"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25; __Weaknesses__ cold iron 3, holy 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy (Touch)]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Abyssal Knowledge"
    desc: "  When a quasit offers [[Actions/Aid|Aid]] for an Arcana or Religion check, it gets the critical success result on any success and gets the critical failure result on any failure."

abilities_mid:
  - name: ""
  - name: "Virtue Aversion"
    desc: "  The quasit's link to a mortal soul gave it birth, but it presents a vulnerability. Once per round, a creature can present an object related to something virtuous or good in the life of the quasit's creator (such as a beloved daughter's doll) as an Interact action to automatically deal the quasit 2d6 mental damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (agile, finesse, magical, poison, unholy)\n__Damage__  1d6 - 1 slashing plus quasit-venom 1d4 spirit plus quasit-venom"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Good Only)]]_, _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_; __1st __  _[[Spells/Fear|Fear]]_\n__Cantrips__  __(1st)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Abyssal Healing"
    desc: "`pf2:1` (concentrate,divine,healing) **Frequency** once per round\n* * *\n\n**Effect** The quasit restores 1d6 HP to itself."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) *   **Bat**\n    *   **Senses** Echolocation 40 feet\n    *   **Speed** 15 feet, fly 30 feet\n    *   **Melee** fangs +7, **Damage** 1d4-1 piercing damage\n    *   **Melee** wing +7 (agile), **Damage** 1d4-1 bludgeoning damage\n*   **Centipede**\n    *   **Speed** 10 feet, climb 10 feet\n    *   **Melee** mandibles +7 (poison), **Damage** 1 piercing damage + 1d4 poison damage\n*   **Toad**\n    *   **Senses** [[Bestiary Ability Glossary/Scent|Scent]] (Imprecise) 30 feet\n    *   **Speed** 5 feet\n    *   **Melee** jaws +7, **Damage** 1 bludgeoning damage\n*   **Wolf**\n    *   **Size** Medium\n    *   **Senses** [[Bestiary Ability Glossary/Scent|Scent]] (Imprecise) 30 feet\n    *   **Speed** 40 feet, climb 10 feet\n    *   **Melee** jaws +7, **Damage** 1d10-1 piercing damage plus [[Bestiary Ability Glossary/Knockdown|Knockdown]]\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Quasit Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage (1 round)\n\n**Stage 3** 1d6 poison damage and [[Conditions/Slowed|Slowed 1]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown (Wolf Form)]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Quasit
creatures:
  - 1: Quasit
```



Unlike other demons, quasits are formed when a mortal spellcaster sheds a portion of their own sinful soul to create a familiar or companion. When these quasits outlive their creators, they become free willed and seek methods of returning to the Abyss, a task that requires pledging servitude to more powerful demons, so many quasits instead opt to remain on the Material Plane to promote evil and hope for chance and luck to someday provide them with a method of reaching the Abyss on their own.
