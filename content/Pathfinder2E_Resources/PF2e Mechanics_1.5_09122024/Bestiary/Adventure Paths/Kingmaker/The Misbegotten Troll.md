---
title: "The Misbegotten Troll"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wqZ5gazXxJnZLy8k" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/troll
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "The Misbegotten Troll"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "The Misbegotten Troll"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[giant]]
trait_04: [[troll]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision"
languages: "Aklo, Fey, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Intimidation: +35"
abilityMods: [9, 4, 8, 0, 3, 6]
speed: 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +36, __Ref__ +27, __Will__ +27; +2 status to all saves vs. fear effects"
hp: 430
health:
  - name: ""
  - name: HP
    desc: "430, regeneration 45 (deactivated by acid or fire); __Weaknesses__ fire 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|+2 Greater Striking Glaive]], [[Equipment/Full Plate|+2 Greater Resilient Full Plate]], Chain of Lovelies"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 45 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Vigorous Shake"
    desc: "`pf2:r`  **Trigger** The troll king takes [[Conditions/Persistent Damage|Persistent]] acid or fire damage.\n* * *\n\n**Effect** The troll king shakes itself to remove persistent acid or fire effects. The troll king immediately attempts a DC 15 Flat check check to end the persistent damage that triggered this reaction. If the troll king succeeds at this check, it can immediately use Primordial Roar as part of this reaction."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (reach 10 feet)\n__Damage__  2d12 + 23 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, reach 10 feet)\n__Damage__  2d8 + 23 slashing"

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+35 (deadly d8, forceful, magical, reach 15 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "Forced Regeneration"
    desc: "`pf2:1` (concentrate) **Requirements** The troll king's regeneration is not currently deactivated.\n* * *\n\n**Effect** The troll king regains 25 healing HP."

  - name: "Jangle the Chain"
    desc: "`pf2:1` (auditory,emotion,manipulate,mental,primal) The Misbegotten Troll shakes his chain of caged sprites, causing the supernatural cages to amplify their despair. All creatures other than the Misbegotten Troll or his smilodon pets within 30 feet must attempt a DC 40 Will check save. The Misbegotten Troll can't Jangle the Chain again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Jangle the Chain for 24 hours.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]] by despair.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 1]] by sadness, and then sickened 1 by despair once the stun effect ends.\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 3]] by sadness, and then [[Conditions/Sickened|Sickened 2]] by despair once the stun effect ends."

  - name: "Primordial Roar"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The troll king unleashes a bestial roar. Each non-troll creature within 100 feet must attempt a DC 40 Will check save. The creature is then temporarily immune for 10 minutes.\n\nThis ability doesn't affect his pet black smilodons.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]]\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]]\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]]"

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Unstoppable Charge"
    desc: "`pf2:3`  The troll king Strides twice in a straight line. It can make up to two claw Strikes during this movement and one jaws Strike at the end of its movement. It can't Strike the same creature more than once."

  - name: "Vicious Ranseur"
    desc: "  When the Misbegotten Troll attacks with his glaive, it manifests dozens of hooks and spikes along its length and blade. He deals an additional 3d8 piercing damage to any creature he strikes but inflicts 1d8 piercing damage to himself with each glaive Strike."
 
```

```encounter-table
name: The Misbegotten Troll
creatures:
  - 1: The Misbegotten Troll
```


Variant troll king

Some trolls have learned the skills necessary to survive well beyond the typical life expectancy for their kind and rally others to follow their lead. These champions develop a number of talents that make them worthy leaders and potent hunters-namely their abilities to willingly boost the rate of their regeneration and to shake off the acid and fire that would hinder it, not to mention a bestial roar that can send would-be predators scurrying off. Troll kings possess a cunning far beyond their younger kin- they know to keep their allies close, and their enemies even closer. If a troll king so much as suspects that one of its followers is plotting to usurp it, retribution is swift and fatal.

* * *

Slavering, cruel, practically invincible brutes: this is the villager's stock description for the dread monsters known as trolls. But words hardly do justice to trolls' capacity for destruction. They are as bloodthirsty as orcs but lacking the discipline, as massive as giants but capable of regenerating wounded flesh in an instant, and as reprobate as ogres but with twice the strength. The only way to really understand the wanton violence of a troll is to experience it firsthand-a fate few would wish even upon their worst enemies.

The first thing that comes to mind when most think of trolls is the creatures' power of bodily regeneration. So potent is this regeneration that the only way to overcome it is to exploit the troll's vulnerability to acid and fire. It is not enough to slay the troll with caustic or flaming weapons, though-even the smallest scrap of a troll's flesh can regenerate into a full-size troll given enough time. The only sure way to eradicate a troll menace is to burn the monster's entire body until nothing remains.

Trolls are solitary hunters, for their wickedness is anathema even to other giants. They occasionally roam in small gangs of two to four, but only when prey is plentiful or a particularly strong counterforce has broached their hunting grounds. In rare instances, an old and powerful troll comes to lead small tribes of trolls. Such "troll kings" possess enough cunning to lead their hordes in devastating raids and massacres, and their presence permanently alters the surrounding ecosystem. A wide variety of trolls exist, from the terrible monster traditionally associated with the name to the water-dwelling scrag and hybrid flood troll. Regional variations exist as well-mountain trolls among stony peaks, for instance, or moss trolls in swampy bayous-but all share the same trademark regenerative powers and insatiable thirst for blood.
