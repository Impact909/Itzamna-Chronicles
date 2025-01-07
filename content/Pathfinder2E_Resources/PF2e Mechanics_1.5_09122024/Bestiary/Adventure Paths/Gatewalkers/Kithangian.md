---
title: "Kithangian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W6iRqAPHRMXjhelj" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Kithangian"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #188: They Watched the Stars"
name: "Kithangian"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Chthonian, Draconic, Empyrean; speak with animals, telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Intimidation: +20, Nature: +21, Stealth: +16"
abilityMods: [6, 3, 5, -2, 4, 3]
speed: 30 feet
sourcebook: "_Pathfinder #188: They Watched the Stars_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +15, __Will__ +19; +1 status to all saves vs. magic"
hp: 205
health:
  - name: ""
  - name: HP
    desc: "205; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Animal Kindness Vulnerability"
    desc: "  Kithangians find kindness to animals revolting. The first time each round that a kithangian sees someone heal or otherwise provide aid to a creature that has the animal trait, the kithangian takes 3d6 mental."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+21 (magical, reach 10 feet, unholy)\n__Damage__  2d12 + 9 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+21 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 9 piercing plus kithangian-venom"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Translocate|Dimension Door]]_; __3rd __  _[[Spells/Paralyze|Paralyze (x2)]]_; __1st __  _[[Spells/Command|Command (At Will, Animals Only)]]_\n__Constant__  __(4th)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Animal Killer"
    desc: "  A kithangian's melee Strikes deal an additional 2d6 damage to animals."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The kithangian can take on the appearance of any Medium or Large animal. This doesn't change its Speed or their attack and damage modif ers with its Strikes, but it might change the damage type its Strikes deal.\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Kithangian Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison (2 rounds)\n\n**Stage 2** 2d6 poison and [[Conditions/Sickened|Sickened 1]] (2 rounds)\n\n**Stage 3** 3d6 poison and [[Conditions/Sickened|Sickened 2]] (2 rounds)"

  - name: "Rasping Tongues"
    desc: "`pf2:1` (attack) **Frequency** once per round\n\n**Requirements** The kithangian has a creature [[Conditions/Grabbed|Grabbed]] in one or both pincers\n* * *\n\n**Effect** Barbed tongues slither out of the faces in the kithangian's pincers. The tongues burrow into grabbed creatures and inject their minds with haunting psychic screams. Each grabbed creature takes 2d8 piercing and 2d8 mental. A creature can try to resist the mental damage by attempting a DC 25 Will check."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kithangian
creatures:
  - 1: Kithangian
```



The kithangian—a horrifying amalgam of horse and scorpion also known as a "beast demon"—is a foul fend born of the souls of mortals who abused and tormented animals in life. Kithangians tend to roam wild areas rife with animals to torture, though humanoid settlements with plenty of pets or livestock also make for tantalizing hunting grounds. Uncontested for too long, a kithangian's presence has a corrupting influence on the local fauna, which birth fiendish monstrosities until the demon is vanquished. If it realizes it's being tracked by vengeful druids or demon slayers, a kithangian assumes the shape of an unassuming animal so it can get the jump on its pursuers.
