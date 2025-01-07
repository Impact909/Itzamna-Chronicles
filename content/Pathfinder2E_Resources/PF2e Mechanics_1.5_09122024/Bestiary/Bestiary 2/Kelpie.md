---
title: "Kelpie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qM3RGAAcizh79y2X" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Kelpie"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Kelpie"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[fey]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Low-Light Vision"
languages: "Common, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Deception: +14, Stealth: +10"
abilityMods: [5, 2, 3, -1, 3, 4]
speed: 35 feet,  swim 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +12, __Will__ +14"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Weaknesses__ cold iron 5; __Resistances__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d6 + 7 bludgeoning plus grab"

  - name: "Captivating Lure"
    desc: "`pf2:2` (concentrate,emotion,incapacitation,mental,primal) The kelpie instills an overwhelming attraction to itself within the mind of a single creature within 60 feet. The target perceives the kelpie as a desirable person (if the kelpie is in humanoid form) or a valuable steed (if the kelpie is in equine form) and must attempt a DC 23 Will check saving throw.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Captivating Lure for 24 hours.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round and is then temporarily immune to Captivating Lure for 24 hours.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]], and it must spend each of its actions to move closer to the kelpie as expediently as possible while avoiding obvious dangers. If a captivated creature is adjacent to the kelpie, it either attempts to mount the kelpie (if the kelpie is in equine form) or stays still and doesn't act. If the creature is attacked by the kelpie, or if it can't breathe water and enters an area of water, the creature is freed from captivation at the end of the kelpie's turn.\n\n**Critical Failure** As failure, but the target doesn't consider water a danger and will enter an area of water even if it can't swim or breathe water. If it is attacked by the kelpie or starts to drown, it can attempt a new save at the start of its next turn, but it isn't freed automatically."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The kelpie can take on the appearance of any Medium or Large animal of an equine nature (such as a [[Monster Core/Riding Horse|Horse]], [[Monster Core/Hippocampus|Hippocampus]], or [[Monster Core/Riding Pony|Pony]]), or any Small or Medium humanoid. This doesn't change its Speeds or its attack and damage modifiers with its Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kelpie
creatures:
  - 1: Kelpie
```



Kelpies are malevolent amphibious fey shapechangers intent on luring mortals to their doom. These cruel predators lurk in and around areas of water, slightly preferring freshwater over saltwater. Kelpies lure or drag their prey underwater then drown and devour them, leaving behind only the victim's heart and liver- the only parts of a meal kelpies find unpleasant. Kelpies are fond of magically disguising itself as fine steeds or attractive strangers to draw in victims, but its true appearance takes the form of a hideous equine with slimy, green flesh resembling aquatic plants.
