---
title: "Shoal Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hZjaHXAmraXAwbWN" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Shoal Linnorm"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Shoal Linnorm"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
trait_04: [[evil]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +31, Stealth: +28"
abilityMods: [8, 5, 7, -3, 6, 7]
speed: 35 feet,  fly 100 feet,  swim 100 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +29, __Ref__ +25, __Will__ +22; +1 status to all saves vs. magic"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, regeneration 10 (deactivated by cold iron); __Immunities__  curse,  fire,  paralyzed,  sleep; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Curse of Drowning"
    desc: " (curse,primal,water) When a creature slays a shoal linnorm, it must succeed at a DC 38 Will check save or become cursed. As long as the curse of drowning persists, the character must spend 3 actions when drinking any liquid. Attempting to drink liquid faster causes the victim to begin drowning, immediately running out of air and falling unconscious."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+31 (magical, reach 20 feet)\n__Damage__  3d12 + 16 piercing plus shoal-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+31 (agile, magical, reach 15 feet)\n__Damage__  3d8 + 16 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+31 (magical, reach 25 feet)\n__Damage__  4d6 + 16 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 36, attack +26\n__Constant__  __(7th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_ __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (fire,primal,water) The shoal linnorm exhales scalding steam that deals 12d8 fire damage in a 60-foot cone (DC 36 Reflex check save). The steam lingers until the end of the linnorm's next turn; anyone who enters the area or begins their turn in the area takes 6d8 fire damage (DC 36 Reflex check save negates). During this time, the steam is so thick that it impedes movement as well as sight, turning the area into difficult terrain. All creatures in the steam become [[Conditions/Concealed|Concealed]], and all creatures outside the steam become concealed to creatures within it.\n\nThe shoal linnorm can't use Breath Weapon again for 1d4 rounds."

  - name: "Shoal Linnorm Venom"
    desc: " (fire,poison) **Saving Throw** DC 36 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 4d6 fire damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 6d6 fire damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shoal Linnorm
creatures:
  - 1: Shoal Linnorm
```



Shoal linnorms occupy rocky shoreline shallows and slither along lonely coastlines. While they do not intentionally seek out large settlements, these linnorms nonetheless beleaguer fishers headed out from small coastal towns, and they may even follow skiffs back to their home port to appraise the town's defenses and plan a raid. Shoal linnorms tend to hunt large prey, both underwater and on land. Their preferred quarries includes giant squid and grizzly bears-meals rich in fat, which the linnorms metabolize into the fiery steam that courses through their veins.
