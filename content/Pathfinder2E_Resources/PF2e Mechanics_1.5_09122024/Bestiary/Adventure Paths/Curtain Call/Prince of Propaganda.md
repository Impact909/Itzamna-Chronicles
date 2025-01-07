---
title: "Prince of Propaganda"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.btNoFRpk41ppsrPW" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Prince of Propaganda"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Prince of Propaganda"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[fey]]
trait_02: [[unholy]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Greater Darkvision, Truesight"
languages: "Common, Diabolic; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Athletics: +36, Deception: +40, Diplomacy: +38, Religion: +35, Society: +36, Stealth: +38, Thievery: +36, Norgorber Lore: +38, Warfare Lore: +38"
abilityMods: [9, 7, 7, 7, 6, 9]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +36, __Ref__ +39, __Will__ +33"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  curse,  death effects,  drained,  fear effects; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+3 Greater Striking Returning Club, +3 Greater Striking Shortsword"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Aura of Disquietude]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 41 Will check\n\nAs [[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]], plus a creature frightened by the aura becomes suspicious; it doesn't count any other creature as its ally and can't [[Actions/Aid|Aid]] or flank. On a critical failure, the creature also can't be a willing target for harmless or helpful magic.\n\n[[Bestiary Effects/Effect_ Aura of Disquietude|Effect: Aura of Disquietude]]\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+40 (magical)\n__Damage__  3d6 + 19 bludgeoning plus princes-curse"

  - name: "**Ranged** `pf2:1` Club"
    desc: "+38 (magical, thrown 20 ft.)\n__Damage__  3d6 + 14 bludgeoning plus princes-curse"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+40 (agile, finesse, magical, versatile s)\n__Damage__  3d6 + 19 piercing plus princes-curse"

  - name: "**Melee** `pf2:1` Manacle"
    desc: "+40 (magical, reach 10 feet)\n__Damage__ "

  - name: "Occult Innate Spells"
    desc: "DC 44, attack +36; __10th __  _[[Spells/Fabricated Truth|Fabricated Truth]]_; __9th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Rewrite Memory|Rewrite Memory]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_; __5th __  _[[Spells/Mind Probe|Mind Probe (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Inscribe Propaganda"
    desc: "`pf2:1` (curse,divine,incapacitation,mental) **Frequency** once per turn\n* * *\n\n**Effect** The Prince lifts the writer's quill he carries, points its nib at a target he can see that's within 120 feet, and then writes [[Conditions/Invisible|Invisible]] text in the air. The target hears the sound of the quill nib scratching words into parchment and must attempt a DC 44 Will check save. The target then becomes temporarily immune to Inscribe Propaganda for 24 hours.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target's worldview shifts, causing it to momentarily lose track of who its allies and enemies are. It becomes [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The Prince's propaganda influences the target, causing it to believe lies about allies or foes and to take a course of action chosen by the Prince of Propaganda. The target is affected as if by subconscious suggestion, but with a duration of 1 hour, and the suggestion must arise logically from the target's temporary belief in the lie or conspiracy.\n\n**Critical Failure** As failure, but with an unlimited duration."

  - name: "Prince's Curse"
    desc: " (curse,occult) A creature hit by the Prince's melee attack becomes cursed. It becomes [[Conditions/Off-Guard|Off-Guard]] and takes 2d6 persistent bleed damage that's difficult to stanch. The DC to stop the bleeding using [[Actions/Administer First Aid|Administer First Aid]] is 40, and healing the creature to full HP doesn't automatically end the bleeding. Removing the curse ends the bleeding and off-guard condition."

  - name: "Shed Manacle"
    desc: "`pf2:r`  **Trigger** The Prince has grappled a creature with his manacle\n* * *\n\n**Effect** The manacle clasps drop away from the chain the Prince holds. The creature remains grappled until they [[Actions/Escape|Escape]] (DC 44), at which point its manacles vanish. The Prince can't make manacle Strikes again until his next turn when his chain creates a new set of manacles at its end."

  - name: "Sneak Attack"
    desc: "  The Prince deals an additional 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Improved Grab"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Prince of Propaganda
creatures:
  - 1: Prince of Propaganda
```


Variant vilderavn

In their true form, a vilderavn is a great raven with a wingspan of 6–8 feet. Adaptable shapeshifters, they can change to the fighting forms of a snarling wolf, a hybrid of both wolf and raven, and a tall humanoid in black armor with a massive greatsword. More sinister is their ability to assume a humanoid guise suited to insinuating themselves into the retinues of boastful mortal rulers. With historical knowledge and clever rumormongering, they goad the proud into squabbles, feuds, and ultimately wars. The vilderavn stays at the ruler's side until victory is within grasp, the war almost won, then exacts the cruel stroke of betrayal. Their magic turns the mortals against each other, and the vilderavn's sword falls swiftly.
