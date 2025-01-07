---
title: "The Keeper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w7KMmmJ0TLyK2Vsj" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "The Keeper"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #192: Worst of All Possible Worlds"
name: "The Keeper"
level: "Creature 21"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fey]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Greater Darkvision, Truesight"
languages: "Aklo, Common, Diabolic, Fey; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Athletics: +39, Deception: +39, Society: +36, Stealth: +35, Heraldry Lore: +34, Warfare Lore: +36"
abilityMods: [8, 6, 6, 5, 5, 8]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder #192: Worst of All Possible Worlds_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +37, __Ref__ +35, __Will__ +32"
hp: 385
health:
  - name: ""
  - name: HP
    desc: "385; __Immunities__  curse,  death effects,  drained,  fear effects; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+3 Greater Striking Greatsword]], [[Equipment/Full Plate|+2 Greater Resilient Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Aura of Disquietude]]"
    desc: " (emotion,fear,mental) 30 feet. DC 41 Will check\n\nAs [[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]], plus a creature frightened by the aura becomes suspicious: it doesn't count any other creature as its ally and can't [[Actions/Aid|Aid]] or flank. On a critical failure, the creature also can't be a willing target for harmless or helpful magic.\n\n[[Bestiary Effects/Effect_ Aura of Disquietude|Effect: Aura of Disquietude]]\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Maintain Fate"
    desc: "`pf2:r` (occult) **Trigger** The Keeper would be subjected to a misfortune effect, become [[Conditions/Slowed|Slowed]], or become [[Conditions/Stunned|Stunned]].\n* * *\n\n**Effect** The Keeper manipulates reality to maintain control of her own destiny and twists the fate of those that dared tamper with her own. The Keeper disrupts the triggering effect and becomes [[Conditions/Quickened|Quickened]] until the end of her next turn. She can use the extra action to Fly, Step, Stride, or Strike. If the effect originated from a creature, such as an enemy casting slow on the Keeper, that creature is targeted with an ill omen spell. The creature must attempt a DC 44 Will check save to determine the effects of the spell."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+40 (magical, versatile p)\n__Damage__  4d12 + 16 slashing plus bloodbird"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (magical)\n__Damage__  4d6 + 16 piercing plus bloodbird"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+37 (agile, magical)\n__Damage__  4d6 + 16 slashing plus bloodbird"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +0; __9th __  _[[Spells/Ethereal Jaunt|Ethereal Jaunt]]_, _[[Spells/Suggestion|Suggestion]]_; __8th __  _[[Spells/Wave of Despair|Crushing Despair (At Will)]]_, _[[Spells/Rewrite Memory|Modify Memory]]_; __7th __  _[[Spells/Outcast's Curse|Outcast's Curse (At Will)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Constant__  __(9th)__ _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Bloodbird"
    desc: " (curse,occult) A creature hit by a vilderavn's melee attack becomes cursed. It takes 2d6 bleed that's difficult to stanch. The DC to stop the bleeding using [[Actions/Administer First Aid|Administer First Aid]] is 41, and healing the creature to full HP doesn't automatically end the bleeding. Removing the curse ends the bleeding."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The vilderavn takes on the appearance of a Small or Medium humanoid, wolf, dire wolf, or hybrid with both raven and wolf parts. The vilderavn can only use their jaws attack when in a form with a wolf's head, and their talon attack in a form with raven qualities. They can instead assume their raven knight form: a Medium humanoid in black full plate carrying a greatsword. They can use their jaws or talon Strikes only in a form that has that body part, and their greatsword only in knight form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Souleater"
    desc: " (occult) If the vilderavn kills a humanoid target with a critical hit using their Jaws Strike, they rip out and devour the target's heart and soul as part of the attack. While the target is dead, the vilderavn can Change Shape into the target's form, gaining a +4 status bonus to Deception checks to impersonate the target. If magic would resurrect the creature, the caster must succeed at a DC 44 counteract check to extract the target's soul from the vilderavn; otherwise, the spell fails."
 
```

```encounter-table
name: The Keeper
creatures:
  - 1: The Keeper
```


Variant female vilderavn

In their true form, a vilderavn is a great raven with a wingspan of 6-8 feet. Adaptable shapeshifters, they can change to the fighting forms of a snarling wolf, a hybrid of both wolf and raven, and a tall humanoid in black armor with a massive greatsword. More sinister is their ability to assume a humanoid guise suited to insinuate themselves into the retinues of boastful mortal rulers. With historical knowledge and clever rumor-mongering, they goad the proud into squabbles, feuds, and ultimately wars. The vilderavn stays at the ruler's side until victory is within grasp, the war almost won, then exacts the cruel stroke of betrayal. Their magic turns the mortals against each other, and the vilderavn's sword falls swiftly.
