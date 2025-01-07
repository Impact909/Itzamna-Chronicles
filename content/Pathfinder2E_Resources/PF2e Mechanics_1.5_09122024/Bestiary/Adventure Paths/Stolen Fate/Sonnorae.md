---
title: "Sonnorae"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xhgK4Fl8trqbh8nC" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Sonnorae"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Sonnorae"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Truesight"
languages: "Aklo, Common, Diabolic, Draconic, Fey, Goblin, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +31, Deception: +36, Diplomacy: +34, Intimidation: +36, Performance: +34, Religion: +31, Stealth: +34, Torture Lore: +32"
abilityMods: [7, 8, 5, 6, 7, 8]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +27, __Ref__ +32, __Will__ +31; +1 status to all saves vs. magic"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335, regeneration 25 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 20, silver 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/The Tyrant|The Tyrant]], [[Equipment/The Lens of the Outreaching Eye|The Lens of the Outreaching Eye]]"
  - name: "Painsight"
    desc: " (divine) A precentor automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Final Spite"
    desc: "`pf2:r`  **Trigger** Sonnorae is reduced to 0 Hit Points\n* * *\n\n**Effect** Sonnorae casts [[Spells/Wails of the Damned|Wails of the Damned]], if it's available, before dying. Otherwise, she makes one Strike."

  - name: "Unnerving Gaze"
    desc: " (aura,divine,mental,visual) 30 feet. When a creature ends its turn in the aura, it must succeed at a DC 37 Will check save or become [[Conditions/Doomed|Doomed 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, finesse, reach 10 feet, unholy)\n__Damage__  3d6 + 15 slashing 2d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Synesthesia|Synesthesia]]_, _[[Spells/Wails of the Damned|Wail of the Banshee]]_; __8th __  _[[Spells/Hidden Mind|Mind Blank]]_, _[[Spells/Interplanar Teleport|Plane Shift (At Will, to the Harrowed Realm, Universe, or Netherworld only)]]_, _[[Spells/Spiritual Epidemic|Spiritual Epidemic]]_; __7th __  _[[Spells/Command|Command]]_, _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Noise Blast|Sound Burst]]_; __4th __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_\n__Cantrips__  __(9th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Sigil|Sigil]]_\n__Constant__  __(8th)__ _[[Spells/Fly|Fly]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Assemble Choir"
    desc: "`pf2:2`  Sonnorae adds a creature that is affected by her Spirit-Flensing Touch and is within 100 feet to her choir of screams. Sonnorae can have any number of creatures in her choir, although a creature no longer affected by Spirit-Flensing Touch leaves the choir immediately. Creatures in Sonnorae's choir of screams are [[Conditions/Fascinated|Fascinated]] by each other and Sonnorae, and they can't use hostile actions toward each other or Sonnorae. If Sonnorae uses a hostile action toward a creature in her choir, it immediately leaves the choir. When Sonnorae casts an innate divine spell, she can cause the effect to originate from any member of her choir instead of herself, using her saving throw DC and attack bonus."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,mental,visual) Sonnorae stares at a creature she can see within 30 feet. The target must attempt a Will save against Sonnorae's unnerving gaze. In addition, if the creature was already [[Conditions/Doomed|Doomed]], on a failed save, it sees the skin of its body peel back, making it [[Conditions/Confused|Confused]] for as long as it remains doomed. After attempting this save, the creature is then temporarily immune until the start of Sonnorae's next turn."

  - name: "Spirit-Flensing Touch"
    desc: "`pf2:2` (divine,mental) Sonnorae touches a creature within 10 feet. The target's spirit tears through its organs and flesh and must attempt a DC 40 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected, and is temporarily immune for 24 hours.\n\n**Success** The creature takes 4d6 slashing damage.\n\n**Failure** The creature takes 9d6 slashing damage and is [[Conditions/Sickened|Sickened 1]] and [[Conditions/Stupefied|Stupefied 1]]. As long as the creature remains sickened, it must use one action on its turn to scream in agony.\n\n**Critical Failure** The creature takes 18d6 slashing damage and is [[Conditions/Sickened|Sickened 2]] and [[Conditions/Stupefied|Stupefied 2]]. As long as the creature remains sickened, it must use two actions on its turn to scream in agony."
 
```

```encounter-table
name: Sonnorae
creatures:
  - 1: Sonnorae
```


Female velstrac precentor

Velstracs are horrific, shadow-dwelling fiends who seek ultimate sensation through self-mutilation. They transcend their stoic detachment only when inflicting pain and terror upon their victims, practicing new forms of debasement and torture before then turning their knives on themselves. Although velstracs consider themselves beyond such limitations as morality or mortal taboos, their victims know them as emotionless tormentors who inflict debased, sadistic suffering. They claim to seek perfection in thought, form, and action, although they don't recognize any refinement that doesn't require the painful excision of the flesh or spirit.

Velstracs manifest from the souls of masochistic or sadistic mortals that are diverted into the Shadow Plane and then forged into forms that suit their vile predilections, ranging from the low-ranking augurs to the aesthetics-obsessed interlocutors.

Some mortals refer to velstracs as "kytons," a misattribution that the velstracs tolerate with cold amusement. The term "kyton" denotes a master or virtuoso among their kind, and these fiends enjoy being labeled masters of their horrid paths to perfection through agony.

Velstrac storytellers and historians are known as precentors. Trailed by horrific choirs, precentors perform in the courts of the velstrac demagogues.
