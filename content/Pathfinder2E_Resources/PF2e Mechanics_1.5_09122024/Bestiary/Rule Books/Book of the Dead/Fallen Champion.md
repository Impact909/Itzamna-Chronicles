---
title: "Fallen Champion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gQkcDMingvFx9XeJ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Fallen Champion"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Fallen Champion"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +19, Intimidation: +19, Religion: +17, Kazutal Lore: +16"
abilityMods: [5, 2, 5, 2, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +14, __Will__ +17"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Machete|+1 Striking Machete]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Scale Mail|+1 Scale Mail]], [[Equipment/Religious Symbol (Wooden)|Defiled Religious Symbol of Kazutal]]"
abilities_mid:
  - name: ""
  - name: "Agent of Despair"
    desc: " (aura,divine,emotion,fear,mental) 15 feet. A fallen champion emanates an aura of utter despair. Living creatures are [[Conditions/Frightened|Frightened 1]] while in a fallen champion's aura. They can't naturally recover from this fear while in the area but recover instantly once they leave the aura.\n\n[[Bestiary Effects/Effect_ Despair|Effect: Despair]]"

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Final Blasphemy"
    desc: " (divine,void) When the herexen is destroyed, it explodes in a wave of void energy with the effects of a 4th-rank, 3-action [[Spells/Harm|Harm]] spell (DC 26 Fortitude check). The herexen is destroyed, so it doesn't gain any Hit Points from this use of _harm_, and it doesn't need to have any _harm_ spells remaining to use this ability."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Machete"
    desc: "+20 (deadly d8, magical, sweep)\n__Damage__  2d6 + 11 slashing plus heretics-smite"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Harm|Harm (x2)]]_"

  - name: "Champion Devotion Spells"
    desc: "2 Focus Points, DC 25, attack +17; __4th __  _[[Spells/Touch of the Void|Touch of Corruption]]_, _[[Spells/Unimpeded Stride|Unimpeded Stride]]_"

  - name: "Heretic's Armaments"
    desc: " (divine) While the fallen champion wields the favored weapon of its former deity, that weapon gains the effect of a _[[Equipment/Fearsome|Fearsome]]_ property rune."

  - name: "Heretic's Smite"
    desc: " (divine) While wielding the favored weapon of its former deity (such as a machete for an ex-Kazutal herexen), the herexen's Strikes deal an additional 2d6 spirit damage against creatures that can cast divine spells. This damages divine spellcasters who follow the herexen's former faith regardless of their alignment."

  - name: "Reap Faith"
    desc: "`pf2:1` (divine) **Requirements** The fallen champion's last action was a Strike that dealt damage to a living creature\n* * *\n\n**Effect** The fallen champion saps the hope and faith from that creature. It takes 3d6 void damage with a DC 25 Will check. Regardless of the result of the save, the creature becomes [[Conditions/Frightened|Frightened 1]] or increases the value of its frightened condition by 1."
 
```

```encounter-table
name: Fallen Champion
creatures:
  - 1: Fallen Champion
```



While most herexens were clerics or clergy in life, fallen champions were holy crusaders that upheld the ideals of their deity while fighting enemies of the church and defending its congregants. Fallen champions are direct in their actions and wage their divine war on a grand scale. This fallen champion once worshiped the Arcadian goddess [[Deities/Kazutal|Kazutal]], also called Mother Jaguar.

* * *

A herexen is an undead heretic, driven by hate to destroy the deity they once served. Herexens choose their faith willingly in life, rising to become respected religious figures within their church. Shortly before or during their death, they lose faith in their chosen deity so completely they become a full heretic, blaspheming, committing atrocities, and cursing their god. These anathemic acts bind their soul to their flesh, causing them to rise as cursed beings. To a herexen, faith is the ultimate lie.

Although the circumstances that drive a pious worshipper to break with their faith are varied, herexens are unified in purpose. Herexens spend their existence fighting their former god in every manner they can, destroying iconography and temples, slaying worshippers, banding together with other herexens who oppose the same deity, conscripting lesser undead, and hiring living proxies to wreak havoc or spread misinformation. A particularly motivated herexen may even plot to kill or unseat the deity they once revered. Curiously, herexens maintain a corrupted form of their divine powers after death, wielding the weapons and magic of their past faith to tear it down.
