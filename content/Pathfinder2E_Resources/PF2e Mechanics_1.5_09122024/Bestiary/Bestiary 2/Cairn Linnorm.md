---
title: "Cairn Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.T5Yy7MjHflc03ljm" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Cairn Linnorm"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Cairn Linnorm"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +35"
abilityMods: [9, 6, 8, -2, 6, 7]
speed: 35 feet,  climb 40 feet,  fly 100 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +34, __Ref__ +30, __Will__ +26; +1 status to all saves vs. magic"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360, regeneration 15 (deactivated by cold iron); __Immunities__  acid,  curse,  paralyzed,  sleep; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Curse of the Crooked Cane"
    desc: " (curse,primal) When a creature slays a cairn linnorm, it must succeed at a DC 44 Will check save or become permanently [[Conditions/Enfeebled|Enfeebled 2]]. In addition, the victim ages at an accelerated rate, aging 1 year every day, eventually causing it to die of old age if the curse is left untended."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (magical, reach 25 feet)\n__Damage__  3d12 + 17 piercing plus cairn-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, magical, reach 25 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (agile, magical, reach 25 feet)\n__Damage__  3d10 + 17 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +30\n__Constant__  __(8th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_ __(7th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (acid,primal) The cairn linnorm expels a 60-foot cone of void energy-infused acid, dealing 19d6 acid damage to creatures in the area (DC 40 Reflex check save). The acid also saps the life out of affected creatures. At the beginning of the linnorm's next turn, each creature that failed the Reflex save must succeed at a DC 40 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure).\n\nThe cairn linnorm can't use Breath Weapon again for 1d4 rounds."

  - name: "Cairn Linnorm Venom"
    desc: " (acid,poison) **Saving Throw** DC 41 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 6d6 acid damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 8d6 acid damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cairn Linnorm
creatures:
  - 1: Cairn Linnorm
```



Cairn linnorms are disturbing, even by linnorm standards. They make their homes in necropolises, burial grounds, and the sites of immense and gory battles. Some point out that cairn linnorms feast on shambling undead and thus provide a service to the living, but these beasts are not choosy and will happily consume any creature, whether or not it draws breath.

Some tales state that cairn linnorms will not-or cannot-enter a tomb without the permission of a descendant of the deceased (or the permission of the deceased itself, in the instance that it has risen from the dead). Likewise, once a cairn linnorm has entered a tomb, it won't leave until it has secured permission to do so. Whether such legends are true or not is anyone's guess; nevertheless, reports of a cairn linnorm in the vicinity are harrowing enough to dissuade even the most foolhardy grave robber from peeking into too many crypts or mausoleums.
