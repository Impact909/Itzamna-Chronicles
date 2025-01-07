---
title: "Vilderavn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TUBmXvjHdpiYuKOy" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Vilderavn"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vilderavn"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[fey]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Greater Darkvision, Truesight"
languages: "Aklo, Common, Diabolic, Fey; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +32, Deception: +29, Society: +24, Stealth: +32, Heraldry Lore: +26, Warfare Lore: +26"
abilityMods: [8, 6, 5, 4, 4, 7]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +25, __Ref__ +30, __Will__ +28"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  curse,  death effects,  drained,  fear effects; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Aura of Disquietude]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 35 Will check\n\nAs [[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]], plus a creature frightened by the aura becomes suspicious; it doesn't count any other creature as its ally and can't [[Actions/Aid|Aid]] or flank. On a critical failure, the creature also can't be a willing target for harmless or helpful magic.\n\n[[Bestiary Effects/Effect_ Aura of Disquietude|Effect: Aura of Disquietude]]\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+34 (magical, versatile p)\n__Damage__  3d12 + 16 slashing plus bloodbird"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (magical)\n__Damage__  3d8 + 16 piercing plus bloodbird"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+32 (agile, magical)\n__Damage__  3d8 + 16 slashing plus bloodbird"

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Suggestion|Suggestion]]_; __5th __  _[[Spells/Outcast's Curse|Outcast's Curse (At will)]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_, _[[Spells/Suggestion|Suggestion (At will)]]_, _[[Spells/Translocate|Translocate]]_, _[[Spells/Wave of Despair|Wave of Despair (At will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Bloodbird"
    desc: " (curse,occult) A creature hit by a vilderavn's melee attack becomes cursed. It takes 2d6 persistent bleed damage that's difficult to stanch.\n\nThe DC to stop the bleeding using [[Actions/Administer First Aid|Administer First Aid]] is 35, and healing the creature to full HP doesn't automatically end the bleeding.\n\nRemoving the curse ends the bleeding."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The vilderavn takes on the appearance of a Small or Medium humanoid, wolf, dire wolf, or hybrid with both raven and wolf parts. The vilderavn can only use their jaws attack when in a form with a wolf's head, and their talon attack in a form with raven qualities. They can instead assume their raven knight form: a Medium humanoid in black full plate carrying a greatsword. They can use their jaws or talon Strikes only in a form that has that body part, and their greatsword only in knight form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Souleater"
    desc: " (occult) If the vilderavn kills a humanoid with a critical hit using their jaws Strike, they rip out and devour the target's heart and soul as part of the attack.\n\nWhile the target is dead, the vilderavn can Change Shape into the target's form, gaining a +4 status bonus to Deception checks to impersonate the target.\n\nIf magic would resurrect the creature, the caster must succeed at a DC 34 counteract check to extract the target's soul from the vilderavn; otherwise, the spell fails."
 
```

```encounter-table
name: Vilderavn
creatures:
  - 1: Vilderavn
```



In their true form, a vilderavn is a great raven with a wingspan of 6–8 feet. Adaptable shapeshifters, they can change to the fighting forms of a snarling wolf, a hybrid of both wolf and raven, and a tall humanoid in black armor with a massive greatsword. More sinister is their ability to assume a humanoid guise suited to insinuating themselves into the retinues of boastful mortal rulers. With historical knowledge and clever rumormongering, they goad the proud into squabbles, feuds, and ultimately wars. The vilderavn stays at the ruler's side until victory is within grasp, the war almost won, then exacts the cruel stroke of betrayal. Their magic turns the mortals against each other, and the vilderavn's sword falls swiftly.
