---
title: "Muckish Creep"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.txPlpe6cUSwrcbNm" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Muckish Creep"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Muckish Creep"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +18, Stealth: +17"
abilityMods: [6, 3, 4, 0, 0, 1]
speed: 25 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +15, __Will__ +12"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160, darkvision; __Weaknesses__ fire 8; __Resistances__ bludgeoning 8"
abilities_top:
  - name: ""

  - name: "Compression"
    desc: "  A muckish creep can move through a gap at least 6 inches wide without Squeezing and can [[Actions/Squeeze|Squeeze]] through any gap at least 1 inch wide."

  - name: "Mud Trail"
    desc: "  When a muckish creep Strides or Steps, it leaves behind a slimy mud trail that coats the traversed area. All traversed squares are covered in [[Spells/Grease|Grease]] (DC 26 Reflex check or DC 26 Acrobatics check) until the start of the muckish creep's next turn."

  - name: "Slippery Body"
    desc: "  A muckish creep's body allows it to slip away from most restraints. It gains a +4 status bonus to checks to Escape. On a success, it gets a critical success instead. On a critical failure, it gets a failure instead."

abilities_mid:
  - name: ""
  - name: "Elude Grasp"
    desc: "`pf2:r`  **Trigger** A creature succeeds at an attempt to [[Actions/Grapple|Grapple]] the muckish creep.\n* * *\n\n**Effect** The muckish creep attempts an Athletics check to [[Actions/Escape|Escape]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 ()\n__Damage__  2d10 + 10 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Mud Ball"
    desc: "+18 (thrown 30 ft.)\n__Damage__  2d6 + 10 bludgeoning plus blinding-mud"

  - name: "Blinding Mud"
    desc: "  When a muckish creep hits a creature with a mud ball Strike, that creature becomes [[Conditions/Dazzled|Dazzled]] (or [[Conditions/Blinded|Blinded]] on a critical hit). The creature can use an Interact action to wipe away the mud and remove the dazzled or blinded condition."

  - name: "Overwhelm"
    desc: "`pf2:1` (incapacitation) **Requirements** The muckish creep has a creature grabbed.\n* * *\n\n**Effect** The muckish creep fills the grabbed creature's mouth and nose with mud. The creature begins to suffocate unless it succeeds at a DC 23 Fortitude check save. The suffocating creature or any adjacent creatures can clear the suffocating creature's airway with an Interact action."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Muckish Creep
creatures:
  - 1: Muckish Creep
```



Legends say that the first muckish creeps were born at the site of a mass grave where the souls of murdered prisoners coalesced into the surrounding soil. Another myth tells that muckish creeps were elementals so vile that their kin banished them from the Plane of Earth. Regardless of their true origins, muckish creeps are wicked creatures that resemble mud given a humanoid shape. The mud is no ordinary mixture of earth and water, however, for muckish creeps feed on the blood of the living, and they use this blood to keep their own forms moist and malleable.

Muckish creeps are particularly tenacious and single-minded when it comes to choosing prey. Once a muckish creep selects its next victim, there is little one can do to stop it, since it can seep through even the smallest cracks between doors, walls, and windows. A muckish creep typically waits until its target falls asleep before pressing itself into the creature's home, intent to kill. For all its tenacity during the hunt, the muckish creep is pragmatic when it comes to the actual kill, using its body to fill the victim's airways with mud and suffocate them.
