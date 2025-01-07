---
title: "Xilvirek"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zwsSfndPUewXluy6" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Xilvirek"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Xilvirek"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 120 Feet"
languages: "Chthonian"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Intimidation: +22, Stealth: +23, Survival: +25"
abilityMods: [7, 5, 6, 0, 5, 4]
speed: 40 feet,  swim 30 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +21, __Will__ +19"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "Psionic Scent (Imprecise) 120 feet"
    desc: "  A xilvirek can sense the presence of creatures with an Intelligence of at least -3. Creatures that have silenced their thoughts through magic or other means can potentially counteract this sense at the GM's discretion."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Hypnotic Stench"
    desc: " (aura,emotion,incapacitation,mental) 30 feet. A creature that begins its turn in the area must succeed at a DC 32 Will check save or become [[Conditions/Fascinated|Fascinated]] with the xilvirek. If the creature is already fascinated by the xilvirek and fails its save, the creature is compelled to approach the xilvirek and allow itself to be [[Conditions/Grabbed|Grabbed]], which ends the fascination."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (magical, unholy)\n__Damage__  3d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 13 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+25 (magical, reach 15 feet, unholy, versatile p)\n__Damage__  3d6 + 13 bludgeoning plus knockdown"

  - name: "Divine Innate Spells"
    desc: "DC 28, attack +20; __6th __ (1 slots) _[[Spells/Teleport|Teleport (Self Only)]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __ (1 slots) _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Disgorge Bile"
    desc: "`pf2:2` (acid,inhaled) The xilvirek retches a small pool of debilitating, acrid bile onto itself. All creatures within 30 feet take 4d6 acid damage as they inhale the bile's noxious fumes (DC 32 Fortitude check save; on a failure, the creature is [[Conditions/Sickened|Sickened 1]], or [[Conditions/Sickened|Sickened 2]] on a critical failure). The xilvirek can't Disgorge Bile again for 1d4 rounds."

  - name: "Feasting Tentacles"
    desc: "  The xilvirek has two tentacles on its back that it can use to suck the life from its prey. A creature that starts its turn [[Conditions/Grabbed|Grabbed]] by the xilvirek becomes [[Conditions/Drained|Drained 1]], and the xilvirek regains 20 healing HP. The drained value increases by 1 on each subsequent round that the creature starts its turn grabbed, but the xilvirek doesn't regain additional HP from draining the same creature more than once per day."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Xilvirek
creatures:
  - 1: Xilvirek
```



Xilvireks are the result of the strange evolution that takes place in Zevgavizeb's Abyssal realm. These fiends resemble their dread demon lord and claim to be living embodiments of the Lord of Reptiles's snapping jaws.
