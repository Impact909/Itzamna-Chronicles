---
title: "Girtablilu Seer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rUIHnXdMIJFRvF8g" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Girtablilu Seer"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Girtablilu Seer"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Common, Girtablilu"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Intimidation: +23, Religion: +25, Survival: +23"
abilityMods: [6, 5, 6, 3, 7, 3]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +22, __Ref__ +19, __Will__ +25"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hide Armor|+1 Resilient Hide Armor]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Divine Aegis"
    desc: "`pf2:r` (divine) **Trigger** The girtablilu seer attempts a saving throw against a magical effect but hasn't rolled yet\n* * *\n\n**Effect** The seer summons divine energy to protect themself at the cost of their other magical defenses. Until the start of their next turn, they gain a +1 circumstance bonus to saving throws against non-divine magical effects and a -1 circumstance penalty to saves against divine effects.\n\n[[Bestiary Effects/Effect_ Divine Aegis|Effect: Divine Aegis]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+24 (agile)\n__Damage__  3d8 + 12 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+24 (reach 10 feet)\n__Damage__  3d6 + 12 piercing plus girtablilu-venom"

  - name: "Divine Spontaneous Spells"
    desc: "DC 33, attack +25; __6th __ (3 slots) _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Spirit Blast|Spirit Blast]]_; __5th __ (3 slots) _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Harm|Harm]]_, _[[Compendium.pf2e.spells-srd.Item.OyFCwQuw8XRazsNr|Remove Curse]]_; __4th __ (3 slots) _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Cleanse Affliction|Neutralize Poison]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_; __3rd __ (3 slots) _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Rune Trap|Glyph of Warding]]_, _[[Spells/Anointed Ground|Sanctified Ground]]_; __2nd __ (3 slots) _[[Spells/Augury|Augury]]_, _[[Spells/Calm|Calm Emotions]]_, _[[Spells/Create Food|Create Food]]_; __1st __ (3 slots) _[[Spells/Create Water|Create Water]]_, _[[Spells/Cleanse Cuisine|Purify Food and Drink]]_, _[[Spells/Sanctuary|Sanctuary]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d8+6 bludgeoning, DC 24 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Desert Stride"
    desc: "  A girtablilu ignores natural difficult terrain in the desert."

  - name: "Girtablilu Venom"
    desc: " (poison) **Saving Throw** DC 30 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and enfeebled 1 (1 round)\n\n**Stage 3** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Girtablilu Seer
creatures:
  - 1: Girtablilu Seer
```



The highest position of authority in a girtablilu community is the group's religious leader. This sacred duty requires years of study, meditation, and dedication to awaken a mystical font of divine magic within the girtablilu. These seers ensure that every action taken by the community falls in line with even the most obscure dogma of their tradition, and they don't hesitate to turn their fury on members of their own community who violate their mandates.

* * *

Girtablilus are desert-dwelling guardians with the upper bodies of muscular humanoids and the lower bodies of massive scorpions. They are most often found defending ancient temples and religious artifacts with zealous fervor. Some believe they were created by a long-dead god millennia ago to act as guardians, but girtablilus consider the subject of their origin taboo and refuse to address the theory.

Because girtablilus accept a wide range of religions and belief systems, some outsiders believe they also worship their own ancient pantheon. Instead, girtablilus exclusively revere and protect sites dedicated to deities considered lost to civilization. In this way, they act as preservers of holy practices that have otherwise been forgotten beneath the desert's shifting sands.

Though girtablilus are used to explorers seeking entrance to the sites they defend, they might welcome those who earnestly wish to learn or offer reverence. A few even proudly share their beliefs with others, eager for the opportunity to preach to someone new. But girtablilus show no mercy to those who attempt to desecrate the sites and objects of their worship, or to those who would violate the tenets of their faith.

Girtablilus are skilled fighters who keep trained giant scorpions as pets, and they remain unmatched when it comes to fighting in the desert. They require relatively little food or water, and they rely on their stamina to outlast their enemies. When necessary, they can stalk their quarry for days or even weeks, coordinating with their pets to drive their prey in circles. Once exhausted, few foes can stand up to a girtablilu's physical prowess-or their deadly venom.
