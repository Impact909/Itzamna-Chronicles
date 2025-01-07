---
title: "Sumbreiva"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.U9W1oIvpRyVVcPyR" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/void
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Sumbreiva"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sumbreiva"
level: "Creature 16"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
trait_04: [[void]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Intimidation: +30, Stealth: +35, Survival: +29"
abilityMods: [8, 9, 3, 6, 5, 4]
speed: 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +33, __Will__ +27"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290, void healing; __Immunities__  death effects,  drained"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Hunter's Triumph"
    desc: "`pf2:r` (auditory,emotion,fear,mental) **Trigger** The sumbreiva kills a creature\n* * *\n\n**Effect** The sumbreiva lets out a triumphant, bone-chilling howl. Every enemy in a 30-foot emanation must succeed at a DC 36 Will check save or become [[Conditions/Frightened|Frightened 3]] (and [[Conditions/Fleeing|Fleeing]] as long as it's frightened on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sumbreiva Huntblade"
    desc: "+33 (agile, death, finesse, magical, versatile s)\n__Damage__  3d8 + 16 piercing plus huntblade-brutality"

  - name: "**Melee** `pf2:1` Shadow Whip"
    desc: "+33 (agile, death, disarm, finesse, magical, reach 10 feet, trip)\n__Damage__  3d4 + 16 bludgeoning plus improved-grab"

  - name: "**Ranged** `pf2:1` Sumbreiva Huntblade"
    desc: "+33 (agile, death, magical, thrown 30 ft., versatile s)\n__Damage__  3d8 + 16 piercing plus huntblade-brutality"

  - name: "Arcane Innate Spells"
    desc: "DC 36, attack +28; __4th __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Earthbind|Earthbind]]_"

  - name: "Claim Trophy"
    desc: "`pf2:1`  The sumbreiva claims the soul of a creature they killed within the last minute. This works like [[Spells/Seize Soul|Seize Soul]], except that no black sapphire is required and the soul is turned into a glowing blue light called a _soul trophy_. Anyone who kills the sumbreiva can then free the soul from any _soul trophy_ by touching it and speaking the word for \"freedom\" in any language."

  - name: "Huntblade Brutality"
    desc: "  The sumbreiva's huntblade deals an additional 2d8 damage to [[Conditions/Drained|Drained]], [[Conditions/Off-Guard|Off-Guard]], or [[Conditions/Frightened|Frightened]] creatures."

  - name: "Whip Drain"
    desc: "`pf2:1` (arcane,death) **Requirements** The sumbreiva has a creature [[Conditions/Grabbed|Grabbed]] with their shadow whip\n* * *\n\n**Effect** The grabbed creature must succeed at a DC 38 Fortitude check save or become [[Conditions/Drained|Drained 2]] ([[Conditions/Drained|Drained 3]] on a critical failure). If the creature is already drained, this increases its drained value instead, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sumbreiva
creatures:
  - 1: Sumbreiva
```



Sumbreivas are the Void's unstoppable hunters, tracking down and destroying other creatures on their plane for sport and practice. Occasionally they pass through a rift or are brought to the Material Plane via planar binding, where they collect living souls to display as trophies.

Sumbreivas gather at Night Lodges, where they train and display their soul trophies, which appear as floating wisps of blue energy. The more formidable the soul, the more intense the blue glow that emanates from it. Sumbreivas in lodges periodically raid the Material Plane on a Night Hunt. Over the course of one night, the sumbreivas from that lodge split up and compete to see who can capture the most brilliant souls as trophies. The winner of the Night Hunt leads the lodge until the next hunt.

Night Lodges are ranked against each other by the accomplishments of the hunters within. All sumbreivas have the ultimate goal of capturing a soul worthy of being placed in the Twilight Lodge, reserved for the truly elite souls and hunters.
