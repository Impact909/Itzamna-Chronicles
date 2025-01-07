---
title: "The Stabbing Beast"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GpM2zfP1bRcDaqCp" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/herald
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "The Stabbing Beast"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "The Stabbing Beast"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[herald]]
trait_04: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Greater Darkvision, Truesight"
languages: "Chthonian, Common, Diabolic, Empyrean, Protean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +25, Crafting: +24, Deception: +26, Intimidation: +26, Religion: +24, Society: +26, Stealth: +29, Norgorber Lore: +28"
abilityMods: [6, 8, 4, 3, 4, 3]
speed: 40 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +27, __Ref__ +29, __Will__ +27; +2 to all saves vs. mental"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  poison; __Weaknesses__ holy 15; __Resistances__ acid 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 Feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Stinger Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "True Appearance"
    desc: "`pf2:r`  **Trigger** The Stabbing Beast is transformed with Change Shape and rolls for initiative\n* * *\n\n**Effect** The Stabbing Beast ends Change Shape."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+29 (agile, finesse, magical, reach 15 feet, unholy)\n__Damage__  2d8 + 10 slashing plus improved-grab 2d8 bleed plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+29 (fatal d12, finesse, magical, reach 15 feet, unholy)\n__Damage__  4d8 + 14 piercing plus stabbing-beast-venom"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+30 (agile, finesse, magical, unholy, versatile s)\n__Damage__  3d6 + 10 piercing 2d8 bleed"

  - name: "**Ranged** `pf2:1` Venom Stream"
    desc: "+29 (range increment 60 feet, unholy)\n__Damage__  5d10 poison plus blinding-stream"

  - name: "Innate Divine Spells"
    desc: "DC 36, attack +28; __6th __  _[[Spells/Rewrite Memory|Modify Memory (x3)]]_; __5th __  _[[Spells/Translocate|Dimension Door (x3)]]_, _[[Spells/Summon Animal|Summon Animal (Scorpions Only) (x3)]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Invisibility|Invisibility (x3)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Blinding Stream"
    desc: " (poison) A creature hit by the Stabbing Beast's venom stream must succeed at a DC 33 Fortitude check save or become [[Conditions/Blinded|Blinded]] for 1d4 rounds."

  - name: "Change Shape"
    desc: "`pf2:1` (concentrate,divine,polymorph) The Stabbing Beast takes on the appearance of a Medium humanoid with a scorpion's tail and chitinous, full-body plate armor. This doesn't change their Speed or Strikes, except that their reach becomes 5 feet and they can't make pincer Strikes."

  - name: "Conjure Swords"
    desc: "`pf2:1` (concentrate,divine) **Requirements** The Stabbing Beast is using Change Shape\n* * *\n\n**Effect** The Stabbing Beast summons one or two _+2 greater striking keen shortswords_ into their hands. These weapons disappear if they leave the Stabbing Beast's grasp or if the Stabbing Beast ends Change Shape."

  - name: "Stabbing Beast Venom"
    desc: " (poison) While a creature is enfeebled from this poison, it is [[Conditions/Doomed|Doomed 1]]\n\n**Saving Throw** DC 36 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 2** 4d6 poison damage and enfeebled 2 (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: The Stabbing Beast
creatures:
  - 1: The Stabbing Beast
```




