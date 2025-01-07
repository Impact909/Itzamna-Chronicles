---
title: "Rusalka"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y75ILg8eAxLZzBy8" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Rusalka"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Rusalka"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[aquatic]]
trait_02: [[evil]]
trait_03: [[fey]]
trait_04: [[water]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +22, Deception: +25, Diplomacy: +21, Nature: +21, Performance: +23, Stealth: +25"
abilityMods: [4, 5, 3, 1, 3, 7]
speed: 25 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +21, __Ref__ +25, __Will__ +21"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Weaknesses__ cold iron 15; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Blurred Form"
    desc: "  A rusalka is [[Conditions/Concealed|Concealed]] while underwater."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tresses"
    desc: "+24 (agile, finesse, reach 15 feet)\n__Damage__  3d8 + 10 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 35, attack +25; __5th __  _[[Spells/Charm|Charm (At will)]]_, _[[Spells/Control Water|Control Water (At will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At will)]]_, _[[Spells/Mist|Obscuring Mist (At will)]]_\n__Constant__  __(6th)__ _[[Spells/Water Walk|Water Walk]]_"

  - name: "Beckoning Call"
    desc: "`pf2:1` (auditory,concentrate,incapacitation,mental,primal) The rusalka cries out a compelling invitation. Each non-fey creature within a 300-foot emanation must attempt a DC 27 Will check save. The effect lasts for 1 round, but if the rusalka uses Beckoning Call again on subsequent rounds, the duration extends by 1 round for all affected creatures. Once a creature succeeds at any save against Beckoning Call, that creature is temporarily immune for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] and must spend each of its actions to move closer to the rusalka, avoiding obvious dangers. If a beckoned creature is adjacent to the rusalka, it stays still and doesn't act. If attacked by the rusalka, the creature is freed from captivation at the end of the rusalka's turn.\n\n**Critical Failure** As failure, but if attacked by the rusalka, the creature can attempt a new save only at the start of its next turn, rather than being freed at the end of the rusalka's turn."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+10 bludgeoning, DC 32 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Entangling Tresses"
    desc: "  A rusalka can have up to eight creatures grabbed within their tresses at a time."

  - name: "Flowing Hair"
    desc: "`pf2:1`  The rusalka attempts an Athletics check check against each [[Conditions/Grabbed|Grabbed]] creature's Fortitude DC. The rusalka moves each creature they succeed against up to 10 feet and each creature they critically succeed against up to 20 feet. This movement must all be within reach of its tresses."

  - name: "Shameful Touch"
    desc: "`pf2:1` (emotion,mental,primal) The rusalka touches a creature within 5 feet using their hand, stirring up memories of regret and shame. The target must attempt a DC 35 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 1]] and [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 1]] and [[Conditions/Stunned|Stunned 1]], and it must use its first action on its next turn to Strike itself, automatically hitting."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Rusalka
creatures:
  - 1: Rusalka
```



These androgynous, river-dwelling fey delight in manipulating the emotions of those unfortunate enough to fall into their grasp, using humiliation to break their victims' wills. Rusalkas enjoy keeping their broken toys nearby, both for continuing entertainment and to aid in the rusalkas' defense, as the shame their captives feel often drives them to become obsessively loyal to these fey.
