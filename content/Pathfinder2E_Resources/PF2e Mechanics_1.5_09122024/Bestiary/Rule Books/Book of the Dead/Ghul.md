---
title: "Ghul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Iky2uXM3XSbfI13L" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/genie
  - pf2e/creature/type/ghul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Ghul"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ghul"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[genie]]
trait_04: [[ghul]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Necril; one planar language (typically aquan, auran, ignan, or terran)"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Deception: +14, Diplomacy: +12, Intimidation: +12, Stealth: +12, Survival: +11"
abilityMods: [5, 1, 2, 2, 2, 5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +10, __Will__ +13"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 5; __Resistances__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (magical)\n__Damage__  2d8 + 4 piercing 1d4 bleed"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, magical)\n__Damage__  2d8 + 4 slashing plus grab"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The ghul takes on the appearance of a Small or Medium [[Monster Core/Hyena|Hyena]]. This doesn't change its Speed or Strikes. Effects or abilities that detect the presence of undead don't reveal the ghul as an undead while in this form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Devour Flesh"
    desc: "`pf2:2` (manipulate) **Requirements** The ghul has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The ghul attempts to eat a portion of the grabbed creature's flesh. It makes a jaws Strike against the grabbed creature. On a success, the ghul successfully devours some of the flesh and regains 3d6 healing Hit Points. The grabbed creature becomes [[Conditions/Drained|Drained 1]] (or [[Conditions/Drained|Drained 2]] if the jaws Strike was a critical success). The violent consumption requires the ghul to release the creature as it feasts. A ghul can regain Hit Points from consuming the flesh of a given creature only once per hour; it must consume the flesh of a different creature to gain additional Hit Points during this time."

  - name: "Luring Laugh"
    desc: "`pf2:2` (incapacitation,mental,primal) **Requirements** The ghul is in its hyena shape\n* * *\n\n**Effect** The ghul lets out an alluring chitter. Each creature in a 60-foot emanation must succeed at a DC 19 Will check save or become [[Conditions/Fascinated|Fascinated]], [[Conditions/Off-Guard|Off-Guard]], and compelled to move toward the ghul on the creature's turn. The effect lasts until the end of the ghul's next turn, but the ghul can [[Actions/Sustain|Sustain a Spell]] on Luring Laugh. If the ghul attacks, the fascinated condition ends for only the creature that's attacked. On a successful save, a creature is temporarily immune to Luring Laugh for 24 hours."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ghul
creatures:
  - 1: Ghul
```



Legends claim the gods banished a number of evil, greedy, and gluttonous genies to the Material Plane in the early days of creation. There, the genies transformed into the first ghuls, cruel undead that feast on the flesh of the living. The greedy and gluttonous nature of the first ghuls lives on, cursing them with an insatiable need to consume. Ghuls haunt trade routes, cemeteries, and other locations with good hiding places and a regular influx of travelers. From here, ghuls use their abilities to confuse and captivate passersby, luring them toward dens where ghuls can feast on unsuspecting flesh. Unlike a ghoul, a ghul doesn't devour corpses—only live prey.
