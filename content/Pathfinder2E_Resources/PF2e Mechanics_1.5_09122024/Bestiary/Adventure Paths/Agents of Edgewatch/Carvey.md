---
title: "Carvey"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aYtGFu9xgBDtoBNX" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Carvey"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Carvey"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[golem]]
trait_03: [[mindless]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +19"
abilityMods: [5, -1, 3, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +18, __Ref__ +14, __Will__ +15"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  electricity,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 5 (except adamantine)"
abilities_top:
  - name: ""

  - name: "Suicidal Obedience"
    desc: "  Carvey is unerringly loyal to the Skinsaw cult and to Mobana especially. When Carvey goes berserk, she doesn't attack the nearest living creature or object but instead moves adjacent to the creature nearest the balcony (or similar falling hazard, if the battle is taking place elsewhere) and attempts to [[Actions/Shove|Shove]] the creature over the cliff's edge.\n\nThe number of feet Carvey can Shove a creature is doubled as long as Carvey has 40 or fewer HP (thus, she pushes a creature 10 feet on a sucessful check and 20 feet on a critical success), but she must move the same distance and in the same direction as the pushed creature.\n\nIf the shoved creature falls over the cliff's edge, so does Carvey."

abilities_mid:
  - name: ""
  - name: "Berserk"
    desc: "  A severely damaged flesh golem has a chance of going berserk.\n\nIf it has 40 or fewer HP at the start of its turn, the golem must succeed at a DC 5 Flat check check or go berserk. A berserk golem wildly attacks the nearest living creature, or the nearest object if no creatures are nearby."

  - name: "Electric Reflexes"
    desc: "`pf2:r`  **Trigger** The golem takes electricity damage and a creature is adjacent to it.\n* * *\n\n**Effect** The golem lashes out and tries to grab a nearby creature. The golem attempts an Athletics check to [[/act grapple]] an adjacent creature. The creature also takes 3d6 electricity damage on a success, or 6d6 electricity damage on a critical success."

  - name: "Golem Antimagic"
    desc: "  harmed by fire (5d8 untyped, 3d4 untyped from areas or persistent damage); healed by electricity (area 2d4 healing Hit Points); slowed by cold\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Vulnerable to Flesh to Stone"
    desc: "  Casting a flesh to stone spell on the flesh golem affects the golem normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (magical, reach 10 feet)\n__Damage__  2d10 + 7 bludgeoning"

  - name: "Berserk Slam"
    desc: "`pf2:1`  **Requirement** The flesh golem is berserk.\n* * *\n\n**Effect** The flesh golem Strikes with its fist at a -1 circumstance penalty. If it hits, it deals 1d6 extra damage and knocks the target [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Carvey
creatures:
  - 1: Carvey
```



Made of odd scraps of skin and muscle, a flesh golem is a grotesque parody of life. Though it has no mind, it can still go into a berserk rage when harmed, giving it a faint semblance of emotion. Flesh golems guard the laboratories and charnel houses of fleshwarpers and necromancers who feel no compunctions about desecrating corpses for their own ends. Though the first flesh golem is believed to have been a misguided attempt to create from simple base elements, these monstrosities are far from human. In isolated cases, echoes of a personality might rise in a flesh golem if the brain used as part of its construction belonged to a particularly powerful personality, but such tragic instances are rare in the extreme.
