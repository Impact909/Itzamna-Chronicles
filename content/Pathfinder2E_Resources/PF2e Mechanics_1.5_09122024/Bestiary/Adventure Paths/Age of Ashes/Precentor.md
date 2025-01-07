---
title: "Precentor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CZuk9OCCcB9MwDK9" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Precentor"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Precentor"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Truesight"
languages: "Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +28, Deception: +32, Diplomacy: +34, Intimidation: +32, Performance: +34, Religion: +30, Stealth: +29, Torture Lore: +26"
abilityMods: [6, 7, 3, 6, 6, 8]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +29, __Will__ +30; +1 status to all saves vs. magic"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, regeneration 25 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 20, silver 20"
abilities_top:
  - name: ""

  - name: "Painsight"
    desc: " (divine) A precentor automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Unnerving Gaze"
    desc: " (aura,divine,mental,visual) 30 feet. When a creature ends its turn in the aura, it must succeed at a DC 38 Will check save or become [[Conditions/Doomed|Doomed 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+31 (agile, finesse, reach 10 feet, unholy)\n__Damage__  4d10 + 6 slashing 1d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Wails of the Damned|Wail of the Banshee]]_; __8th __  _[[Spells/Harm|Harm]]_, _[[Spells/Interplanar Teleport|Plane Shift (At Will) (Self Only) (to the Universe or Netherworld only)]]_; __5th __  _[[Spells/Noise Blast|Sound Burst (At Will)]]_, _[[Spells/Synesthesia|Synesthesia (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Sigil|Sigil]]_\n__Constant__  __(8th)__ _[[Spells/Hidden Mind|Mind Blank]]_ __(6th)__ _[[Spells/Fly|Fly]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Assemble Choir"
    desc: "`pf2:2`  The precentor adds a creature that is affected by its Tormenting Touch and is within 100 feet to its choir of screams. A precentor can have any number of creatures in its choir, although a creature no longer affected by Tormenting Touch leaves the choir immediately. Creatures in a precentor's choir of screams are [[Conditions/Fascinated|Fascinated]] by each other and the precentor, and they can't use hostile actions toward each other or the precentor. When the precentor casts an innate divine spell, it can cause the effect to originate from any member of its choir instead of itself, using the precentor's saving throw DC and attack bonus."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,mental,visual) The precentor stares at a creature it can see within 30 feet. The target must immediately attempt a DC 38 Will check save against the precentor's unnerving gaze.\n\nIn addition, if the creature was already [[Conditions/Doomed|Doomed]], on a failed save, it sees the skin of its own body peel back, making it [[Conditions/Confused|Confused]] for as long as it remains [[Conditions/Doomed|Doomed]]. After attempting this save, the creature is then temporarily immune until the start of the precentor's next turn."

  - name: "Tormenting Touch"
    desc: "`pf2:1` (divine,emotion,mental) The precentor touches a creature within 10 feet, causing it to constantly scream in agony. The target must attempt a DC 38 Will check save.\n\nWhile the target is stupefied by this effect, its continual screams cause it to automatically fail Stealth checks.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Stupefied|Stupefied 1]].\n\n**Failure** The target is [[Conditions/Stupefied|Stupefied 3]].\n\n**Critical Failure** The target is [[Conditions/Stupefied|Stupefied 4]].\n\nThe target can attempt a new Will save at the start of each of its turns, reducing the stupefied condition by 1 on each successful save. If the target reduces its stupefied condition to 0 in this way, the target is no longer affected."
 
```

```encounter-table
name: Precentor
creatures:
  - 1: Precentor
```



Velstracs are horrific, shadow-dwelling fiends who seek ultimate sensation through self-mutilation. They transcend their stoic detachment only when inflicting pain and terror upon their victims, practicing new forms of debasement and torture before then turning their knives on themselves. Although velstracs consider themselves beyond such limitations as morality or mortal taboos, their victims know them as emotionless tormentors who inflict debased, sadistic suffering. They claim to seek perfection in thought, form, and action, although they don't recognize any refinement that doesn't require the painful excision of the flesh or spirit.

Velstracs manifest from the souls of masochistic or sadistic mortals that are diverted into the Shadow Plane and then forged into forms that suit their vile predilections, ranging from the low-ranking augurs to the aesthetics-obsessed interlocutors.

Some mortals refer to velstracs as "kytons," a misattribution that the velstracs tolerate with cold amusement. The term "kyton" denotes a master or virtuoso among their kind, and these fiends enjoy being labeled masters of their horrid paths to perfection through agony.

Velstrac storytellers and historians are known as precentors. Trailed by horrific choirs, precentors perform in the courts of the velstrac demagogues.
