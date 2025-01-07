---
title: "Bone Prophet"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.X6Oiwp5E8LcBKWGY" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/serpentfolk
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Bone Prophet"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Bone Prophet"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[serpentfolk]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Necril, Sakvroth; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +15, Deception: +18, Intimidation: +16, Occultism: +17, Religion: +19, Society: +15, Stealth: +13"
abilityMods: [3, 3, 2, 5, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +14, __Ref__ +15, __Will__ +19; +4 status to will saves vs. mental, +1 status to all saves vs. magical"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Resistances__ poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|+1 Striking Staff]], [[Equipment/Religious Symbol (Silver)|Religious Symbol of Ydersius]], [[Equipment/Invisibility Potion|Invisibility Potion]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Thin of Blood"
    desc: "  Bone Prophets recover slowly from injuries. When they take physical damage from a critical hit, they gain 2d4 persistent bleed damage. They take a –2 circumstance penalty to flat checks to recover from persistent damage and saving throws against afflictions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+18 (magical, two-hand d8)\n__Damage__  2d4 + 9 bludgeoning"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 (finesse)\n__Damage__  2d6 + 9 piercing plus serpentfolk-venom"

  - name: "Divine Spontaneous Spells"
    desc: "DC 28, attack +20; __4th __ (3 slots) _[[Spells/Fly|Fly]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Read Omens|Read Omens]]_, _[[Spells/Talking Corpse|Talking Corpse]]_; __3rd __ (4 slots) _[[Spells/Bind Undead|Bind Undead]]_, _[[Spells/Blindness|Blindness]]_, _[[Spells/Chilling Darkness|Chilling Darkness]]_, _[[Spells/Vampiric Feast|Vampiric Feast]]_; __2nd __ (4 slots) _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Darkness|Darkness]]_, _[[Spells/Resist Energy|Resist Energy]]_, _[[Spells/See the Unseen|See the Unseen]]_; __1st __ (4 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __6th __  _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_; __2nd __  _[[Spells/Blur|Blur (Self Only, At Will)]]_; __1st __  _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_"

  - name: "Rituals"
    desc: "_Create Undead_"

  - name: "Raise Serpent"
    desc: "`pf2:3` (divine) **Frequency** once per day\n* * *\n\n**Effect** The bone prophet animates corpses of snakes, serpentfolk, or similar serpentine creatures within a 30-foot emanation. Any flesh on the bodies sloughs off, and they rise as skeletons. The bone prophet can raise one Large creature as a [[Monster Core/Skeletal Giant|Skeletal Giant]] or up to three Medium creatures as [[Monster Core/Skeletal Champion|Skeletal Champions]]; the equipment and attacks might be different depending on the corpses' possessions. These skeletons have the minion trait and are under the bone prophet's control; the bone prophet can give all these minions the same command with a single action that has the concentrate trait. Any skeletal minions that still remain after 10 minutes crumble to dust."

  - name: "Serpentfolk Venom"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d4 poison damage and enfeebled 1 (1 round)"
 
```

```encounter-table
name: Bone Prophet
creatures:
  - 1: Bone Prophet
```



The speakers for the dead known as bone prophets hold an esteemed place as voices for their decapitated god. Burial rites, necromantic rituals, and the delivery of cryptic utterances supposedly whispered to them by Ydersius all fall under the dominion of these priests.

* * *

Before their ancient clash with humanity devastated their civilization, serpentfolk were masters of a sprawling underground empire. Their power was shattered and their god Ydersius decapitated (although not quite slain). The cunning, intelligence, and magical abilities of serpentfolk have diminished from their ancient heights, and most are born without these boons. This is partially the result of cruel genetic meddling among serpentfolk—though the ruling class, zyss, are born with an innate spellcasting ability, their blood runs thin, making them susceptible to wounds. Seen as the failures of the serpentfolk's experiments are the aapophs, who are strong but prone to mutation and lack innate spellcasting.

Today, the central realm of the Darklands retains the old name of the serpentfolk empire that once dominated this region—Sekamina. This name is also the source of the serpentfolk's Aklo title, sekmin, which they are often called in ancient texts. Serpentfolk dominion had declined before ghouls, gugs, umbral gnomes, and other forces. Yet their recent ventures have brought them back to a stronger place in the Darklands. Many serpentfolk sleeping in torpor in secluded vaults have awakened.

Zyss serpentfolk tend toward megalomania, with dreams of returning to their place of dominance. Many of their plans hinge on resurrecting Ydersius, their decapitated god. His headless body still thrashes about, mindless, in the Darklands, waiting to be reunited with his lost skull. Serpentfolk numbers are so small that reclaiming their dominance seems a distant dream, especially since their reproduction is slow. Though a parent can birth a dozen young at once, the gestation period lasts up to a decade, and the likelihood that even one will be zyss is low. There's no telling whether a child will be zyss or aapoph, regardless of parentage. A coveted zyss child is just as likely to arise from aapoph parents as from two zyss, and every serpentfolk colony has someone in charge of sorting the young, identifying the earliest signs of magic in them.
