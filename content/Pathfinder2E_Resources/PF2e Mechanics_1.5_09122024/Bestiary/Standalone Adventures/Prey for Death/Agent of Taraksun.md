---
title: "Agent of Taraksun"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kzrCJqbTZtyUhMQV" 
tags:
  - pf2e/creature/type/asura
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Agent of Taraksun"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Agent of Taraksun"
level: "Creature 14"

alignment: ""
size: "Large"
trait_01: [[asura]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, See the Unseen"
languages: "Common, Diabolic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Deception: +28, Religion: +25, Stealth: +25"
abilityMods: [8, 3, 2, 1, 5, 8]
speed: 50 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +22, __Ref__ +25, __Will__ +27; +1 status to all saves vs. magic"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315; __Immunities__  curse; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Pervert Miracle"
    desc: "`pf2:r` (curse,divine) **Trigger** A foe within 60 feet casts [[Spells/Bless|Bless]] or a beneficial spell that the nikaramsa could cast to remove an affliction or condition (such as [[Spells/Cleanse Affliction|Cleanse Affliction]])\n* * *\n\n**Effect** The nikaramsa attempts to counteract the enemy's spell (counteract modifier +24 and counteract rank 7). If the nikaramsa succeeds, the triggering creature is subjected to the effects of a [[Spells/Bane|Bane]] spell or the effect it was trying to remove."

  - name: "Towering Stance"
    desc: " (divine,illusion) A nikaramsa is in fact a Medium creature, but appears as a Large creature due to the force of their personality. A creature interacting with the nikaramsa can attempt a DC 36 Will check save to see the nikaramsa as they truly are. If the creature succeeds, the reach of nikaramsa's attacks against that foe decrease to 5 feet (10 feet for their tongue).\n\nIf all creatures in the nikaramsa's vicinity successfully disbelieve this illusion, the nikaramsa becomes Medium and [[Conditions/Enfeebled|Enfeebled 2]] for as long as everyone sees their true form.\n\n[[Bestiary Effects/Effect_ Towering Stance (Disbelieved)|Effect: Towering Stance (Disbelieved)]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (reach 10 feet, unholy)\n__Damage__  3d10 + 14 piercing 2d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, reach 10 feet, unholy)\n__Damage__  3d6 + 14 slashing 2d6 spirit"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+29 (reach 20 feet, unholy)\n__Damage__  3d6 + 14 bludgeoning plus improved-knockdown 2d6 spirit plus improved-knockdown"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Bane|Bane]]_, _[[Spells/Bless|Bless]]_, _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Disguise Magic|Disguise Magic (Constant, Self Only)]]_, _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Heal|Heal (x3)]]_, _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_, _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_, _[[Spells/Mind Reading|Mind Reading]]_, _[[Spells/Sound Body|Sound Body]]_, _[[Spells/Translocate|Translocate]]_, _[[Spells/Veil of Privacy|Veil of Privacy (Constant, Self Only)]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/See the Unseen|See the Unseen]]_"

  - name: "Sap Mind"
    desc: "`pf2:1` (divine,mental) The nikaramsa focuses their gaze on one creature within 60 feet. That target must attempt a DC 34 Will check save. Regardless of the outcome of the saving throw, the target then becomes temporarily immune for 1 day.\n* * *\n\n**Critical Success** The nikaramsa is caught off guard by the strength of the target's resistance and becomes [[Conditions/Stupefied|Stupefied 2]] until the end of their next turn.\n\n**Success** The target resists the nikaramsa's influence.\n\n**Failure** The target's focus and willpower drain away; it becomes [[Conditions/Stupefied|Stupefied 2]] for 1 minute.\n\n**Critical Failure** As failure, but the target becomes [[Conditions/Stupefied|Stupefied 3]] for 1 hour."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Agent of Taraksun
creatures:
  - 1: Agent of Taraksun
```


Variant nikaramsa

Lies, knowledge, and deception are a nikaramsa's stock and trade. They are outstanding scholars, with deep and nuanced understanding of religion, philosophy, astrology, and similar subjects. They take particular delight in exploiting the greed and hubris of gullible worshippers, using them to desecrate and destroy their own faith. Even in their goal of undermining the holy, nikaramsas' twisted humor knows few bounds, and they prefer to take on the guise of divine messengers with boons to share. Once they find a likely victim or set of victims, they use their vast knowledge of religion to impart contradictory wisdom, leading to the eventual implosion of the faith from heresies of the clergy and congregation themselves.

* * *

Asuras are, above all, proof that the gods are not infallible. These fiends arose as physical manifestations of divine accidents, taking form when the gods themselves stumbled and blasphemed on a cosmic scale. As a result of their own divine genesis, an asura loves above all to undo the workings of the divine. They eagerly travel to the Material Plane, seeking out temples, congregations of faithful worshippers, and religious orders of all stripes to sow doubt and destroy what the gods seek to build.
