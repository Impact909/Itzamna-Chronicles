---
title: "Runkrunk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DoULYRSC4gTMILbl" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Runkrunk"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Runkrunk"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Dwarven; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Nature: +16"
abilityMods: [6, -1, 6, -2, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +23, __Ref__ +16, __Will__ +17"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  acid,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Awakened"
    desc: "  Runkrunk has an Intelligence modifier of -2, a Nature skill of +16, and knows Common and Dwarven (but can't speak any language)."

  - name: "Berserk"
    desc: "  A severely damaged clay golem has a chance of going berserk. If it has 50 or fewer Hit Points at the start of its turn, the golem must succeed at a DC 5 Flat check check or go berserk. A berserk golem wildly attacks the nearest living creature, or the nearest object if no creatures are nearby."

  - name: "[[Creature Family Ability Glossary/(Golem) Golem Antimagic|Golem Antimagic]]"
    desc: "  *   **Harmed By** cold and water (5d10 untyped damage, 2d6 untyped damage from areas or persistent damage)\n*   **Healed By** acid (area 2d6 healing Hit Points)\n*   **Slowed By** earth\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. These exceptions are listed in shortened form in the golem's stat block, with the full rules appearing here. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n*   **Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n*   **Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n*   **Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's slowed 1 for that round.\n*   **Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Quicken"
    desc: "`pf2:0` (divine) **Frequency** Once per day.\n\n**Trigger** The clay golem's turn begins. It can't trigger this free action on the first turn of combat.\n* * *\n\n**Effect** The clay golem becomes [[Conditions/Quickened|Quickened]] for 1 minute."

  - name: "Vulnerable to Disintegrate"
    desc: "  A [[Spells/Disintegrate|Disintegrate]] spell affects the golem but deals half the normal amount of damage and causes the golem to become [[Conditions/Slowed|Slowed 2]] for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (magical, reach 10 feet)\n__Damage__  2d10 + 12 bludgeoning plus cursed-wound"

  - name: "Berserk Slam"
    desc: "`pf2:1`  **Requirements** The golem is berserk.\n* * *\n\n**Effect** The clay golem Strikes with its fist at a -1 circumstance penalty. If it hits, it deals an additional 1d8 bludgeoning damage and knocks the target [[Conditions/Prone|Prone]]."

  - name: "Cursed Wound"
    desc: " (curse,divine) A creature hit by the clay golem's fist must succeed at a DC 29 Fortitude check save or be cursed until healed to its maximum HP. The cursed creature can't regain HP except via magic, and anyone [[Actions/Cast a Spell|Casting a Spell]] to heal the creature must succeed at a DC 29 counteract check or the healing has no effect. The golem's counteract rank is equal to its creature level."
 
```

```encounter-table
name: Runkrunk
creatures:
  - 1: Runkrunk
```



Traditionally, clay golems are crafted in the image of a deity and used as guardians of tombs or sacred crypts. Clay golems have the power to lay curses upon their victims as punishment for intrusion, leading many to believe that these oft-ancient constructs have a touch of the divine to them. While this idea has little basis in reality, superstitious folk still tread lightly around statues that resemble clay golems even in the slightest.

The animating force within a clay golem is unusually unstable, making the golem prone to entering a berserk frenzy when damaged. Entire treasuries have been totally ruined as a result of a rampaging clay golem, so crafters do well to make sure their golems are maintained and in good working order-or otherwise place them on the other side of the door from the treasures they wish to protect.
