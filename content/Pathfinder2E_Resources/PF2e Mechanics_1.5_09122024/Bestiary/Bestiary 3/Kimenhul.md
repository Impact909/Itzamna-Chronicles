---
title: "Kimenhul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3aSlqjuKeo7lu3TT" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/sahkil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Kimenhul"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Kimenhul"
level: "Creature 20"

alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[sahkil]]
trait_04: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Arcana: +33, Athletics: +38, Deception: +38, Occultism: +33, Religion: +35, Stealth: +36"
abilityMods: [10, 8, 9, 5, 7, 7]
speed: 45 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 45
armorclass:
  - name: AC
    desc: "45 all-around vision; __Fort__ +33, __Ref__ +32, __Will__ +35"
hp: 425
health:
  - name: ""
  - name: HP
    desc: "425; __Immunities__  death effects,  fear effects; __Weaknesses__ holy 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Easy to Call"
    desc: "  A kimenhul's level is considered 2 lower for the purpose of being conjured by the [[Spells/Binding Circle|Binding Circle]] ritual (and potentially other rituals, at the GM's discretion), but it is always free to attack or leave instead of negotiate unless the primary caster's check is a critical success."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  If the triggering creature is subject to an effect with the fear trait, the kimenhul can make two claw Strikes against the creature instead of one Strike.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Feed on Fear"
    desc: "  The kimenhul regains 30 healing Hit Points at the start of its turn as long as any [[Conditions/Frightened|Frightened]] creature is within 100 feet of it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 15 feet, unholy)\n__Damage__  4d12 + 18 piercing 3d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 15 feet, unholy)\n__Damage__  4d8 + 18 slashing plus improved-grab 3d6 spirit plus improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +34; __9th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Fear|Fear (At Will)]]_, _[[Spells/Mask of Terror|Mask of Terror (At Will)]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_, _[[Spells/Warp Mind|Warp Mind]]_, _[[Spells/Weird|Weird]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(9th)__ _[[Spells/Hidden Mind|Mind Blank]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Eternal Fear"
    desc: "`pf2:2` (divine,emotion,fear,incapacitation,mental) The kimenhul contorts its faces and presents itself to its enemies in a terrifying and traumatic display that causes lingering fear. Each creature within 100 feet that can observe the kimenhul must make a DC 42 Will check save.\n\nThey are then temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target becomes [[Conditions/Frightened|Frightened 3]].\n\n**Failure** The target becomes [[Conditions/Frightened|Frightened 3]] and is [[Conditions/Fleeing|Fleeing]] as long as it's frightened. Even after recovering from the initial experience, the trauma is lodged in the target's mind for 1 year. Once per day, the kimenhul can communicate telepathically with the target for 1 minute as long as both creatures are on the same plane. Any time a creature under the effect of Eternal Fear is in a stressful situation (such as combat or intense social pressure), they must succeed at a DC 11 Flat check check or become [[Conditions/Frightened|Frightened 2]]. While Eternal Fear lasts, the target always becomes fleeing as long as it's frightened, regardless of the source of the fear. The target can attempt a new saving throw each week to remove these effects, but they can otherwise be removed only by powerful magic such as [[Spells/Wish|Wish]].\n\n**Critical Failure** As failure, but the effects are permanent and the target doesn't get to attempt a weekly save to end the effect."

  - name: "Frightening Flurry"
    desc: "`pf2:2`  The kimenhul makes one jaws Strike and two claw Strikes against a single target, in any order. The target becomes [[Conditions/Frightened|Frightened]] with a condition value equal to the number of Strikes that hit it, to a maximum of frightened 3 if all three Strikes hit."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Skip Between"
    desc: "`pf2:1` (divine,teleportation) The kimenhul moves from the Material Plane to the Ethereal Plane or vice-versa, with the effects of [[Spells/Ethereal Jaunt|Ethereal Jaunt]] except that the effect has an unlimited duration and can be Dismissed.\n\nA summoned kimenhul can't use Skip Between."

  - name: "Snatch Between"
    desc: "  When using Skip Between, the kimenhul can bring along any creatures it has [[Conditions/Grabbed|Grabbed]]."

  - name: "Unsettled Mind"
    desc: "  Any creature affected by any of a kimenhul's mental spells or abilities becomes [[Conditions/Stupefied|Stupefied 3]] for the duration of that effect and for 1d4 rounds thereafter."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kimenhul
creatures:
  - 1: Kimenhul
```



Among the strongest of their kind aside from the sahkil tormentors, kimenhuls work their craft to foment despair in those who fear failure, forming cycles of self-loathing. These powerful sahkils focus their attention on mortals who are seemingly at the peak of their ability yet harbor secret fears of inadequacy. A kimenhul's predations can leave an indelible mark on its victims. The kimenhul whispers threats and sends fears of crushing failure to its prey, seemingly originating from their own minds, a trauma that can be difficult to bear without help. These sahkils torment their prey as long as the hapless victims live, using their Eternal Fear ability every day to psychically remind their previous victims of their failings.

Some unique kimenhuls find themselves in a position of leadership in Xibalba, where they carve out their own small kingdoms and direct groups of sahkils to help them find mortals to torment. They rule these nightmare kingdoms through terror, often delighting in tormenting new petitioners or scheming ways to work against their immortal foes.

* * *

Ages ago, when this cycle of the multiverse was still adolescent, a cabal of psychopomps who already felt bored and restrained in their role of ushering souls to their ultimate resting place rebelled against their station. It was this corruption of the cycle of souls that spawned the first sahkils.

Ambivalent to the prescribed order of the multiverse and spiteful of mortals, sahkils delight in spreading fear and unease to all beings, clogging up the metaphysical cycle with anxiety-ridden mortals too scared to achieve their potential. These fiends have drastically changed from their dedicated psychopomp predecessors. They are creatures of spite and torment, fear and disgust. They exploit the most common and rare fears for their own perverse satisfaction, and they want nothing more than to frighten mortals and make them question their reason for existence.

Most sahkils lurk on the Ethereal Plane, but they frequently invade the Material Plane to torment mortals and spread terror. They use their innate ability to slip between the veils of the Ethereal and Material effortlessly, often stalking their targets for days or weeks before enacting their devious plots.
