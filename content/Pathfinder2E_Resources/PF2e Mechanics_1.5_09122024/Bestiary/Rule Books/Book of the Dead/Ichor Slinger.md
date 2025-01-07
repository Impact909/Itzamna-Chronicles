---
title: "Ichor Slinger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.H3jksir4SCtr2IB7" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Ichor Slinger"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ichor Slinger"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Necril; any one language"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Crafting: +13, Deception: +13, Performance: +11, Stealth: +9"
abilityMods: [3, 1, 4, 3, 2, 5]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +12, __Ref__ +11, __Will__ +10"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Alchemist's Toolkit|Alchemist's Tools]], [[Equipment/Disguise Kit|Disguise Kit]], 7x Infused Reagents, 6x [[Equipment/Snake Oil|Snake Oil]]"
abilities_mid:
  - name: ""
  - name: "Mystery Ingredients"
    desc: " (auditory,aura,occult) 60 feet. Creatures in the aura take a -2 status penalty to checks to Identify Alchemy, Recall Knowledge about alchemical subjects, or examine snake oil effects. When a creature first enters the area, if it hears the ichor slinger talking, it must attempt a secret DC 23 Will check save against the slinger's Deception DC. On a failure, it treats its next failed check to Identify Alchemy or Recall Knowledge about alchemical subjects in the next 24 hours as though it were a critical failure instead. This is an auditory misfortune effect."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile)\n__Damage__  2d6 + 3 bludgeoning plus grab"

  - name: "Brew Tomb Juice"
    desc: "`pf2:1` (manipulate) **Cost** 1 batch of infused reagents\n* * *\n\n**Effect** The ichor slinger creates a vial of tomb juice, an alchemical tonic that has the infused trait and becomes inert after 24 hours. Tomb juice has the effects of [[Equipment/Snake Oil|Snake Oil]], and maybe more depending on the results of the ichor slinger's DC 20 Crafting check check.\n* * *\n\n**Critical Success** The slinger chooses one of the following items and adds its effects to the tomb juice: [[Equipment/Antidote (Moderate)|Antidote (Moderate)]], [[Equipment/Antiplague (Moderate)|Antiplague (Moderate)]], [[Equipment/Elixir of Life (Lesser)|Elixir of Life (Lesser)]], [[Equipment/Giant Scorpion Venom|Giant Scorpion Venom]], or [[Equipment/Juggernaut Mutagen (Moderate)|Juggernaut Mutagen (Moderate)]]. Poisons created in this way gain an onset of 1 round, gain the ingested trait, and lose any contact, inhaled, or injury traits.\n\n**Success** As critical success, but the slinger chooses from [[Equipment/Antidote (Lesser)|Antidote (Lesser)]], [[Equipment/Antiplague (Lesser)|Antiplague (Lesser)]], [[Equipment/Elixir of Life (Minor)|Elixir of Life (Minor)]], [[Equipment/Graveroot|Graveroot]], or [[Equipment/Juggernaut Mutagen (Lesser)|Juggernaut Mutagen (Lesser)]]."

  - name: "Exhume"
    desc: "`pf2:1` (manipulate) **Requirements** The ichor slinger is adjacent to a dead creature that hasn't already been affected by Exhume\n* * *\n\n**Effect** The ichor slinger harvests portions of the corpse to gain 1 dose of infused reagents, or 2 infused reagents if the creature was undead."

  - name: "Force Feed"
    desc: "`pf2:1`  **Requirements** The ichor slinger has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] and is holding tomb juice, an alchemical elixir, or an alchemical poison\n* * *\n\n**Effect** The ichor slinger forces the target to consume the alchemical item."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ichor Slinger
creatures:
  - 1: Ichor Slinger
```



While the typical snake oil salesperson seeks riches, some medical fraudsters become so enamored with the swindler lifestyle they reanimate to keep living the lie. Known as ichor slingers, these cadaverous alchemists disguise themselves to walk among the living. There they gleefully concoct tonics and peddle cure-alls, charismatically convincing bystanders to overlook questionable ingredients and credentials. Ichor slingers feed on others' attention and trust, caring little for clients' health so long as buyers imbibe the offered medicines. Conversely, rejection infuriates ichor slingers. The undead often stalk, subdue, and administer unwanted medicines to those who snub them. When not selling "panaceas," ichor slingers harvest macabre ingredients to make dubious new medicines.
