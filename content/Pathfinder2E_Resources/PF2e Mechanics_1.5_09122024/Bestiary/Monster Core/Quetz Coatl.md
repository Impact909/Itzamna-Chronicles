---
title: "Quetz Coatl"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9BydkfbP7oxXFY5k" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/couatl
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Quetz Coatl"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Quetz Coatl"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[couatl]]
trait_03: [[holy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Empyrean, Sussuran, Utopian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +19, Athletics: +19, Diplomacy: +22, Nature: +22, Occultism: +19, Religion: +22, Survival: +16"
abilityMods: [7, 3, 5, 6, 5, 5]
speed: 15 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +19, __Ref__ +19, __Will__ +21"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (holy, magical)\n__Damage__  2d10 + 13 piercing plus grab,quetz-couatl-venom"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +21; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (Self Only)]]_; __5th __  _[[Spells/Breath of Life|Breath of Life]]_, _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Divine Wrath|Divine Wrath]]_; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Vapor Form|Vapor Form]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Light|Light]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Vitality Lash|Vitality Lash]]_"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d10+7 bludgeoning, DC 29 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Quetz Couatl Venom"
    desc: " (holy,poison) To unholy creatures, this is a curse instead of a poison and deals spirit damage instead of poison damage\n* * *\n\n**Saving Throw** DC 29 Fortitude check;\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d8 poison damage, enfeebled 1, and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** 2d10 poison damage, [[Conditions/Enfeebled|Enfeebled 2]], and off-guard (1 round)"

  - name: "Radiant Wings"
    desc: "`pf2:2` (divine,incapacitation,light,mental,visual) The quetz coatl spreads their multicolored wings and radiant plumage. Each enemy in a 30-foot emanation must attempt a DC 29 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Radiant Wings for 24 hours.\n\n**Success** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Failure** The creature is dazzled for 1 minute.\n\n**Critical Failure** As failure, plus if the creature is unholy, it is also [[Conditions/Stunned|Stunned 3]]."

  - name: "Wrap in Coils"
    desc: "`pf2:1`  **Requirements** The quetz couatl has a Medium or smaller creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its jaws\n* * *\n\n**Effect** The quetz couatl moves the creature into its coils, freeing its fangs to make attacks, then uses [[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]] against the creature. The quetz couatl can hold as many creatures in its coils as will fit in its space."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Quetz Coatl
creatures:
  - 1: Quetz Coatl
```



These sacred feathered serpents tirelessly serve the powers of knowledge and justice. Some operate directly as messengers and intermediaries of the deities, while others operate independently in aiding the cause of righteousness. Either way, they watch over mortals and try to influence and aid them from the shadows, shifting from plane to plane to spread wisdom and healing where they are needed. Some quetz coatls are worshipped as divinities in remote or isolated societies, and while they do not encourage such veneration, they use the trust placed in them to foster peace and cooperation with others.

Quetz coatls are typically 10 to 20 feet long and weigh nearly a ton, with iridescent blue and green scales. Their glorious wings of rainbow-hued feathers span 15 feet. They are carnivorous, feeding on birds, mammals, and even the occasional malicious humanoid.
