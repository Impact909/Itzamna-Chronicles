---
title: "Somnalu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.agwUYx3YiuTGy2G6" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/dream
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Somnalu"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Somnalu"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[dream]]
trait_03: [[evil]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Aklo; can&#x27;t speak any language; telepathy 60 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Athletics: +27, Occultism: +30, Survival: +25, Dreamlands Lore: +33"
abilityMods: [9, 6, 6, 8, 8, 4]
speed: 30 feet,  burrow 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +25, __Ref__ +25, __Will__ +29"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  acid; __Weaknesses__ cold 15; __Resistances__ mental 10, poison 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Baleful Gaze"
    desc: "`pf2:r`  **Trigger** A creature within 100 feet makes a ranged attack or uses an action that has the concentrate trait\n* * *\n\n**Effect** Somnalu fixes its central eye upon the triggering creature in an attempt to frighten it, jolting it and disrupting its action. The creature must attempt a DC 36 Will check save; on a failure, Somnalu disrupts the triggering action and the creature is [[Conditions/Frightened|Frightened 1]]."

  - name: "Corrosive Wounds"
    desc: "  The acid that coats the skin of Somnalu eats away at a weapon that Strikes it. As long as Digestive Secretions is active on Somnalu, whenever a creature hits Somnalu with a metal or wooden weapon, the creature must succeed at a DC 33 Reflex check save or else the weapon takes 2d8 acid damage (after dealing damage to Somnalu as normal). Thrown weapons and ammunition take this damage automatically with no saving throw."

  - name: "Frightful Presence"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 33 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Sleep Scent (Imprecise) 60 feet"
    desc: "  Somnalu can smell creatures that are asleep, as the scent ability.\n* * *\n\nScent involves sensing creatures or objects by smell, and is usually a vague sense. The range is listed in the ability, and it functions only if the creature or object being detected emits an aroma (for instance, incorporeal creatures usually do not exude an aroma).\n\nIf a creature emits a heavy aroma or is upwind, the GM can double or even triple the range of scent abilities used to detect that creature, and the GM can reduce the range if a creature is downwind."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (reach 10 feet)\n__Damage__  3d12 + 17 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail Barbs"
    desc: "+30 (agile, reach 20 feet)\n__Damage__  3d8 + 17 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +28; __8th __ (1 slots) _[[Spells/Hypnopompic Terrors|Hypnopompic Terrors]]_; __6th __ (4 slots) _[[Spells/Vibrant Pattern|Vibrant Pattern (x2)]]_; __5th __ (1 slots) _[[Spells/Strange Geometry|Strange Geometry (x3)]]_; __4th __ (3 slots) _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Silence|Silence (At Will)]]_, _[[Spells/Sleep|Sleep (At Will)]]_"

  - name: "Acid Spew"
    desc: "`pf2:2`  Somnalu jets acid from its skin, dousing all creatures in a 15-foot-wide, 60-foot-long line. Each creature in this area takes 10d8 acid damage (DC 33 Reflex check save). It can't use this ability again for 1d4 rounds."

  - name: "Caustic Trench"
    desc: "`pf2:3`  Somnalu Burrows three times. It digs a trench along its path, filling the trench with acid pumped from its skin. The trench is hazardous terrain, and any creature that moves into it takes 4d6 persistent acid damage. While Burrowing, if Somnalu would move through a space occupied by another creature, that creature must attempt a DC 36 Reflex check save to avoid falling into the trench and taking the acid damage. The acid remains for 1 minute."

  - name: "Digestive Secretions"
    desc: "`pf2:1`  Somnalu secretes acid for 1 round. Whenever it makes a melee Strike, it deals an additional 2d8 acid splash damage. Like most splash damage, this damage applies to the target and adjacent creatures and applies even on a failure, though not on a critical failure."

  - name: "Drain Nutrients"
    desc: "`pf2:2`  Somnalu targets a creature with a claw Strike. On a success, Somnalu drains the creature's life through its skin. The creature must succeed at a DC 36 Fortitude check save or become [[Conditions/Drained|Drained 2]] ([[Conditions/Drained|Drained 1]] on a success, no effect on a critical success). Somnalu gains temporary Hit Points equal to the amount of Hit Points the creature loses from this Strike."

  - name: "Vent Fumes"
    desc: "`pf2:3`  Somnalu blasts poison gas in a 30-foot radius. The gas lingers for 1 round, and all creatures that begin their turn in the gas or enter the gas take 4d8 poison damage (DC 36 Fortitude check save). Any creature in the gas is [[Conditions/Concealed|Concealed]], and other creatures are concealed to all creatures in the gas. However, Somnalu can see through this concealment."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Somnalu
creatures:
  - 1: Somnalu
```



With its lithe, sinuous body and a flexible, twisting spine, Somnalu bears a resemblance to a giant lizard, save for its striking visage. Spiny frills run down the creature's mottled black back, interlaced with dull red stripes that streak from head to tail. Its two sets of forelimbs are bound to each other by small webs of skin. Its distinctive face lacks any visible mouth, nose, or ears, instead possessing only a huge red eye surrounded by six smaller, secondary eyes.
