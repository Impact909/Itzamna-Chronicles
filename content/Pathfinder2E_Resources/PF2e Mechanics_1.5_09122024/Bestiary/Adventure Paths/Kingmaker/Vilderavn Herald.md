---
title: "Vilderavn Herald"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gp0M7Qj8EowDP6AK" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Vilderavn Herald"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Vilderavn Herald"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fey]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Greater Darkvision, Truesight"
languages: "Aklo, Common, Diabolic, Fey; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +36, Deception: +35, Intimidation: +37, Society: +33, Stealth: +36, Heraldry Lore: +33, Warfare Lore: +33"
abilityMods: [10, 7, 6, 6, 6, 8]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +31, __Ref__ +36, __Will__ +33"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375; __Immunities__  curse,  death effects,  drained,  fear effects; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Aura of Disquietude"
    desc: " (emotion,fear,mental) 30 feet. DC 35 Will check\n\nAs [[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]], plus a creature frightened by the aura becomes suspicious: it doesn't count any other creature as its ally, and it can't [[Actions/Aid|Aid]] or flank. On a critical failure, the creature also can't be a willing target for harmless or helpful magic. The vilderavn can activate or deactivate this aura using a single action, which has the concentrate trait.\n\n[[Bestiary Effects/Effect_ Aura of Disquietude|Effect: Aura of Disquietude]]\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+36 (magical, versatile p)\n__Damage__  4d12 + 16 slashing plus bloodbird"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (magical)\n__Damage__  4d8 + 16 piercing plus bloodbird"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+36 (agile, magical)\n__Damage__  4d8 + 16 slashing plus bloodbird"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __8th __  _[[Spells/Ethereal Jaunt|Ethereal Jaunt]]_, _[[Spells/Suggestion|Suggestion]]_; __5th __  _[[Spells/Wave of Despair|Crushing Despair (At Will)]]_, _[[Spells/Rewrite Memory|Modify Memory]]_, _[[Spells/Outcast's Curse|Outcast's Curse (At Will)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Bloodbird"
    desc: " (curse,occult) A creature hit by a vilderavn's melee attack becomes cursed, taking 2d6 bleed damage that's difficult to stanch: the DC to stop the bleeding using Administer First Aid is 35, and healing the creature to full HP doesn't automatically end the bleeding. Removing the curse ends the bleeding."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The vilderavn takes on the shape of a wolf or dire wolf, a wolf-raven hybrid, or its raven knight form: a Small or Medium humanoid in black full plate carrying a greatsword. The vilderavn can use its jaws attack only in a form that has a wolf's head, its talon attack only in a form that has raven talons, and its greatsword only in raven knight form."

  - name: "Souleater"
    desc: " (occult) If the vilderavn kills a humanoid target with a critical hit using its jaws Strike, it rips out and devours the target's heart and soul as part of the attack. While the target is dead, the vilderavn can Change Shape into the target's form, gaining a +4 status bonus to Deception checks to impersonate the target. If magic would resurrect the creature, the caster must succeed at a DC 38 counteract check to extract the target's soul from the vilderavn; otherwise the spell fails."
 
```

```encounter-table
name: Vilderavn Herald
creatures:
  - 1: Vilderavn Herald
```



In its true form, a vilderavn herald is a human-sized raven. Its ability to assume a humanoid guise suits it to insinuate itself into the retinue of a mortal ruler or to travel without too much concern, but more often these deadly fey directly serve more powerful rulers, such as the Eldest.
