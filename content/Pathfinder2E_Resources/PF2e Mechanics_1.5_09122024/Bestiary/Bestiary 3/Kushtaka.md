---
title: "Kushtaka"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sqGAbLJR9aSRxQf7" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Kushtaka"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Kushtaka"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[amphibious]]
trait_02: [[beast]]
trait_03: [[evil]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +9, Deception: +11, Stealth: +11"
abilityMods: [3, 5, 2, 0, 4, 3]
speed: 25 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +8, __Ref__ +13, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Resistances__ physical 5"
abilities_top:
  - name: ""

  - name: "Canine Vulnerability"
    desc: "  Dogs and other canines are natural enemies of kushtaka. Canine animals, including creatures transformed into a canine using [[Spells/Animal Form|Animal Form]] or a similar effect, ignore the kushtaka's resistance to physical attacks.\n\nIn addition, a canine with imprecise scent can use it as a precise sense when detecting a kushtaka."

  - name: "Null Spirit"
    desc: "  Kushtaka exist completely separated from their mortal souls, making them immune to the effects of haunts and most effects from incorporeal spirits and undead, but also unaware of their presence; incorporeal undead are both [[Conditions/Invisible|Invisible]] and inaudible to them. Incorporeal spirits and undead can affect a kushtaka only with effects that manifest in the physical world.\n\nFor instance, a ghost mage casting a [[Spells/Fireball|Fireball]] or a poltergeist throwing objects could harm the kushtaka, but a ghost commoner's Frightful Moan and ghostly hand Strike would not."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Persuasive Rebuttal"
    desc: "`pf2:r`  **Trigger** A creature fails a check to Strike or Demoralize the kushtaka\n\n**Requirements** The kushtaka has a _charm_ spell available\n* * *\n\n**Effect** The kushtaka casts [[Spells/Charm|Charm]] on the target."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (finesse)\n__Damage__  2d8 + 5 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile, finesse)\n__Damage__  2d6 + 5 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Charm|Charm (x2)]]_, _[[Spells/Invisibility|Invisibility (x2)]]_, _[[Spells/Sleep|Sleep]]_\n__Cantrips__  __(2nd)__ _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(2nd)__ _[[Compendium.pf2e.spells-srd.Item.FzAtX8yXBjTaisJK|Undetectable Alignment]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The kushtaka takes on the specific appearance of a unique Small or Medium humanoid. Every time the kushtaka uses this ability, it takes on the same chosen form, though it can use non-magical disguises to further alter its appearance. This doesn't change the kushtaka's Speed or its attack and damage bonuses with its Strikes, though it does change the damage to an appropriate type, typically bludgeoning.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kushtaka
creatures:
  - 1: Kushtaka
```



Kushtaka, or "land otters" as they are sometimes known, are devious shapeshifters. They propagate by luring a humanoid away from the shelter of their home and slowly transforming the kidnapped creature into a new kushtaka. Kushtaka have an easier time transforming willing prey, so they prefer to use their shapeshifting ability and innate magical powers to convince their chosen targets to follow them away to a kushtaka village.

Once a humanoid has been lured to a kushtaka village, they slowly begin to change, a bit at a time, until their body transforms fully into that of a kushtaka and ejects their mortal soul. These ejected souls often linger before giving rise to ghosts or haunts, though the kushtaka themselves are unaware of the souls' presence, having completely forgotten who they once were due to the magic that transformed them.

Kushtaka can be a scourge to small human villages, slowly pilfering villagers away one person at a time. This might mean the kushtaka village displaces the human one, or leaves the human village unable to survive with too small a population to hunt, fish, defend against threats, or raise the next generation.
