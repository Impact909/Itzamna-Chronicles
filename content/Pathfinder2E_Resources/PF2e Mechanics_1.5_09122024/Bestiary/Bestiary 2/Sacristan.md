---
title: "Sacristan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.clliDCUcLARIr3EN" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Sacristan"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Sacristan"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Greater Darkvision"
languages: "Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +22, Intimidation: +18, Stealth: +21, Torture Lore: +16"
abilityMods: [6, 5, 6, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +19, __Will__ +17; +1 status to all saves vs. magic"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, regeneration 10 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 10, silver 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Staggering Servitude"
    desc: " (aura,divine,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it sees a vision of the sacristan groveling in pitiable servitude. The creature must succeed at a DC 27 Will check save or become [[Conditions/Stunned|Stunned 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Barbed Chain"
    desc: "+22 (magical, reach 10 feet, trip, unholy, versatile s)\n__Damage__  2d8 + 9 piercing 1d6 spirit 2d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +19; __5th __  _[[Spells/Chilling Darkness|Chilling Darkness]]_; __3rd __  _[[Spells/Fear|Fear]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The sacristan stares at a creature they can see within 30 feet. The creature must immediately attempt a Will save against Staggering Servitude. In addition, if the creature was already [[Conditions/Stunned|Stunned]], on a failed save its revulsion toward the sacristan's presence causes it to be [[Conditions/Stupefied|Stupefied 2]] for 1 minute. After attempting this save, the creature is then temporarily immune until the start of the sacristan's next turn."

  - name: "Shadow Scream"
    desc: "`pf2:3` (aura,concentrate,darkness,divine,mental,sonic) **Frequency** once per hour\n* * *\n\n**Effect** The sacristan opens their mouth to unloose the wailing howls and mind-twisting darkness of the Shadow Plane. This creates a 30-foot emanation of darkness and wailing sounds around the sacristan. Creatures with [[Bestiary Ability Glossary/Darkvision|Darkvision]] can't see through this darkness. The sacristan can Sustain Shadow Scream for up to 1 minute. Non-velstrac creatures in the area when the ability is used, as well as those who enter or start their turn in the area, must attempt a DC 28 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is then temporarily immune for 24 hours.\n\n**Success** The creature is [[Conditions/Deafened|Deafened]] for 1 round.\n\n**Failure** The creature is [[Conditions/Confused|Confused]] and deafened for 1 round.\n\n**Critical Failure** The creature takes 20 mental damage, and is confused and deafened for 1 round."
 
```

```encounter-table
name: Sacristan
creatures:
  - 1: Sacristan
```



Sacristans are failures among the velstracs, creatures whose bodies and minds have been utterly broken by the velstracs' torments. These unfortunates are assembled from scrap metal, nerveless flesh, and bits of darkness into loyal agents who take ecstatic pleasure in serving other velstracs. Sacristans are empowered by a miniature gateway to the Shadow Plane deep in their mouths. By distending their jaws, they can howl with the shrieks and windstorms of that plane. Sacristans vary in appearance but are the size of maimed humans. Their features are redundant or absent and they are wrapped in barbed and rusted chains.
