---
title: "Chernobue"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tAby3iFYPQIMcsP0" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Chernobue"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Chernobue"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[qlippoth]]
trait_05: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Chthonian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +25, Intimidation: +25, Occultism: +22"
abilityMods: [7, 4, 5, 4, 7, 5]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +18, __Will__ +25"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220; __Immunities__  controlled,  fear effects; __Resistances__ mental 10, physical 10 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Order's Ruin"
    desc: " (aura,occult) 30 feet. A lawful or good creature that begins its turn in this aura's emanation must attempt a DC 29 Will check save or become [[Conditions/Sickened|Sickened 1]] (lawful good creatures instead become [[Conditions/Sickened|Sickened 2]])."

  - name: "Boiled by Light"
    desc: "  A chernobue takes 2d10 fire damage each time it starts its turn in an area of bright light."

  - name: "Recall Venom"
    desc: "`pf2:r`  **Trigger** A creature within 30 feet suffers the effects from stage 2 of rupturing venom\n* * *\n\n**Effect** The chernobue calls out telepathically to the semi-alive toxin, causing it to burst out of the target's body and slither through the air to drain back into one of the chernobue's mouths. The poisoned creature takes 7d6 bludgeoning damage (DC 32 Fortitude check save) as the venom exits its body, but is thereafter cured of rupturing venom, and the chernobue regains an equal number of Hit Points."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (magical, unholy)\n__Damage__  3d10 + 13 piercing plus rupturing-venom 1d6 spirit plus rupturing-venom"

  - name: "**Melee** `pf2:1` Tentacle Mouth"
    desc: "+26 (agile, magical, reach 15 feet, unholy)\n__Damage__  3d6 + 13 piercing 1d6 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 32, attack +22; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (Self only)]]_; __6th __  _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Phantom Pain|Phantom Pain]]_; __5th __  _[[Spells/Subconscious Suggestion|Subconscious Suggestion]]_; __4th __  _[[Spells/Darkness|Darkness (At will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(4th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Paralyzing Display"
    desc: "`pf2:2` (concentrate,emotion,fear,incapacitation,mental,occult,visual) The chernobue's eye pulses and its lid peels back to reveal mind-bending awfulness. Creatures in a 30-foot emanation must attempt a DC 32 Will check save, after which they are temporarily immune to further Paralyzing Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]] for 1d4 rounds. It can attempt a new save to end the effect at the end of each of its turns.\n\n**Critical Failure** As failure, but paralyzed for 1 minute."

  - name: "Rupturing Venom"
    desc: " (poison) The thick, orange venom injected by a chernobue is semi-alive, and as it seethes in a creature's body, it deals poison damage in addition to bludgeoning damage as it ruptures flesh\n\n**Saving Throw** DC 32 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and 2d6 bludgeoning damage (1 round)\n\n**Stage 2** 2d6 poison damage, 2d6 bludgeoning damage, and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"
 
```

```encounter-table
name: Chernobue
creatures:
  - 1: Chernobue
```



The chernobue infects all creatures it encounters with itself, spreading pain and calamity wherever it flops and writhes. It sheds ruin and sups on anguish, but a chernobue can sometimes be persuaded to pause for a few moments of conversation if its partner in discourse can keep its attention by providing enough atrocious details. Resembling a tumor-like growth of oily blackness, this vile monstrosity has numerous muscular tentacles, a single glaring baleful eye, and a drooling, toothy maw in the middle of its body.
