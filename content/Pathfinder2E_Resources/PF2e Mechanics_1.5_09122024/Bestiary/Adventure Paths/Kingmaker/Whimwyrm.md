---
title: "Whimwyrm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ieJPGjRdgCRkpg66" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Whimwyrm"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Whimwyrm"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +30, Deception: +32, Intimidation: +30, Nature: +30, Performance: +35, Stealth: +34, Survival: +29"
abilityMods: [5, 9, 6, 5, 6, 7]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +29, __Ref__ +34, __Will__ +29"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280; __Immunities__  confused,  controlled,  paralyzed,  petrified,  unconscious; __Weaknesses__ cold iron 15; __Resistances__ mental 15"
abilities_top:
  - name: ""

  - name: "Fog Vision"
    desc: "  Fog and mist doesn't impair a whimwyrm's vision; it ignores the [[Conditions/Concealed|Concealed]] condition from fog and mist."

  - name: "Insult Challenges"
    desc: "  When a whimwyrm's insults result in combat, it rolls Performance for initiative. A PC who engaged in the insults can roll Performance as well, and if they insulted the whimwyrm, it begins the combat [[Conditions/Stunned|Stunned 1]] as it sputters in indignation if the Performance check also exceeds the Whimwyrm's Will DC of 39."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Fangs Only)]]"
    desc: "`pf2:r`  Fangs only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Frenzied Fangs"
    desc: "+35 (finesse)\n__Damage__  3d12 + 12 piercing"

  - name: "**Melee** `pf2:1` Whiplashing Tail"
    desc: "+35 (agile, finesse, reach 10 feet)\n__Damage__  3d8 + 12 slashing"

  - name: "Arcane Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Duplicate Foe|Duplicate Foe]]_; __8th __  _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Confusing Colors|Scintillating Pattern]]_; __7th __  _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/Warp Mind|Warp Mind]]_\n__Cantrips__  __(8th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Message|Message]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Meddling Tail"
    desc: "`pf2:r`  **Trigger** The whimwyrm damages a creature with its whiplashing tail Strike\n\n**Effect** The whimwyrm can attempt to [[Actions/Disarm|Disarm]], [[Actions/Shove|Shove]], or [[Actions/Trip|Trip]] the damaged creature."

  - name: "Mind-Numbing Breath"
    desc: "`pf2:2` (arcane,mental) The whimwyrm exhales a 40-foot cone of sparkling magenta mist. Creatures within the area must attempt a DC 38 Will check save as their minds are overwhelmed by a sudden riot of false (and typically unpleasant) memories, taking 10d12 mental damage depending on their save. The whimwyrm can't use mind-numbing breath for 1d4 rounds.\n* * *\n\n**Critical Success** The creature becomes outlined in sparkling dust, negating any [[Spells/Invisibility|Invisibility]] it has in effect for 1 round and takes no damage.\n\n**Success** The creature takes half damage, and its invisibility is negated for 2 rounds.\n\n**Failure** The creature takes full damage, is [[Conditions/Dazzled|Dazzled]] for 1 minute, and its invisibility is negated for 1 minute.\n\n**Critical Failure** The creature takes double damage, is [[Conditions/Blinded|Blinded]] for 1 round, dazzled for 1 minute, and its invisibility is negated for 1 minute."
 
```

```encounter-table
name: Whimwyrm
creatures:
  - 1: Whimwyrm
```



Whimwyrms are unpredictable dragons native to the whimsically dangerous First World. While their coloration and appearance might evoke reactions of adoration, their moods shift quickly from one extreme to the other. Many who have assumed that their adorability and relatively small size equates to safety have met swift and grisly ends on a whimwyrm's fangs or magic.

A whimwyrm is a slender, sleek dragon, not much longer than seven feet from snout to tail, but its speed in combat is unnerving. When a whimwyrm attacks, be it with its fanged mouth or its long tail, it makes several quick, darting snaps or lashes at once. While stylistically, these attacks consist of multiple bites or lashings, they still resolve as a single Strike.
