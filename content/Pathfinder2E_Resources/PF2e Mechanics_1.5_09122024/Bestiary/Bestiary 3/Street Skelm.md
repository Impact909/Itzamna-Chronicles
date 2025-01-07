---
title: "Street Skelm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.op9Fs6xQBPUNGakq" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/skelm
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Street Skelm"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Street Skelm"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
trait_04: [[skelm]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Scent (Imprecise) 30 Feet"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Deception: +9, Intimidation: +11, Occultism: +8, Stealth: +9"
abilityMods: [4, 2, 3, 3, 1, 4]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +9, __Will__ +8; -1 to all saves vs. emotion effects"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55; __Weaknesses__ cold iron 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|Staff]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+12 (agile, magical)\n__Damage__  1d6 + 6 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+12 (magical)\n__Damage__  1d10 + 6 piercing plus knockdown"

  - name: "**Melee** `pf2:1` Staff"
    desc: "+13 (two-hand d8)\n__Damage__  1d4 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+9 (range increment 20 feet)\n__Damage__  1d6 + 6 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The street skelm can take on the appearance of any Medium male humanoid. This doesn't change his Speed or his attack and damage bonuses with his Strikes but might change the damage type his Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Frightening Rant"
    desc: "`pf2:1` (auditory,concentrate,emotion,fear,linguistic,mental,occult) The skelm rants angrily, filling nearby creatures with shame, fear, and anger. Each creature within 30 feet must succeed at a DC 20 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure).\n\nWhile frightened by this rant, creatures take a -2 status penalty to Strength-based damage rolls against the skelm, but gain a +2 status bonus to those rolls against other creatures."

  - name: "Punishing Strike"
    desc: "`pf2:1`  The skelm unleashes his constant rage in a reckless attack that makes him [[Conditions/Off-Guard|Off-Guard]] until the start of his next turn.\n\nHe Strikes; if he hits, he increases the number of damage dice by one and adds [[Bestiary Ability Glossary/Push|Push]] to the effect. This counts as two attacks for his multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Street Skelm
creatures:
  - 1: Street Skelm
```



Street skelms abuse the deference given to elders and the well-to-do in public spaces, appearing as such so they can verbally or physically punish those who dare defy their cruel sensibilities. To excuse his actions or gather allies, a street skelm might rant about a target, building a pretense of some vague threat the target poses to the community's social order. These rantings can rally a mob to carry out the skelm's violence against his target, some of whom even act out of fear against becoming the skelm's next target. Street skelms have little of the magical talents possessed by their more powerful peers, mostly relying on brute force.

Street skelms typically dress in old-fashioned styles, always including a hat or hood that can cover their distinctive features. They often walk with a cane, walking staff, or other prop suitable for bludgeoning those who offend their delicate egos or challenge their tenuous sense of control.

* * *

Rage-filled skelms are drawn to any settlement with more than a few hundred souls. Using magical disguises and leveraging societal norms to their benefit, these antlered monsters crave fearful respect and brutally punish any who dare disagree with their lofty opinions, even in the slightest degree. Although quite dangerous on their own, skelms are at their deadliest when leading an angry mob. Their cruel and exploitative nature has made their name synonymous with villainy.

An existing skelm can transform any evil humanoid who's overwhelmed with rage into one of their kind. Skelms heap enraging humiliation on potential new brothers as a form of indoctrination, convincing these recruits that some other person or group is responsible for their misery. This practice ensures skelms begin their new existence with sufficient vitriol to plot their revenge.

Many newly forged skelms carry on their lives in the roles they held as mortals; and in fact, these roles often shape the type of skelm they become. Skelms can arise among members of nearly any ancestry, though they're more common among cultures with deeply entrenched gender roles, unjust hierarchies, and those that don't offer healthy ways to experience and process anger.
