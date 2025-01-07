---
title: "Zinba"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KspRJFT8Zm4oNleC" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Zinba"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: The Mwangi Expanse"
name: "Zinba"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[beast]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: "Fey; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +25, Stealth: +18, Survival: +18"
abilityMods: [8, 3, 7, -3, 3, 0]
speed: 30 feet,  burrow 10 feet,  climb 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Lost Omens: The Mwangi Expanse_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +23, __Ref__ +20, __Will__ +18"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Tighten Coils"
    desc: "`pf2:r`  **Trigger** A creature grabbed or restrained by the zinba attempts to Escape\n* * *\n\n**Effect** The DC of the Escape check is increased by 2."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 ()\n__Damage__  2d10 + 11 piercing plus grab,zinba-venom"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+21 (agile, reach 10 feet)\n__Damage__  2d8 + 9 bludgeoning plus push"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d10+6 bludgeoning damage, DC 29 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Slither"
    desc: "`pf2:1`  The zinba Strides, Climbs, or Swims up to half its Speed, pulling any creatures it has grabbed with it."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d10+6 bludgeoning damage, Rupture 23\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Zinba Restoration"
    desc: "`pf2:1` (vitality) The zinba bites a creature within reach and delivers a restorative healing remedy instead of its venom. The creature takes 1 piercing damage, but then gains fast healing 5 for 1 minute.\n\nIn addition, the restorative attempts a counteract check against any poison or disease affecting the creature with a counteract modifier of +22.\n\nA creature that receives the restorative is temporarily immune to the zinba's restorative for 24 hours.\n\n[[Bestiary Effects/Effect_ Zinba Restoration|Effect: Zinba Restoration]]"

  - name: "Zinba Venom"
    desc: " (poison) **Saving Throw** DC 29 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Drained|Drained 1]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Zinba
creatures:
  - 1: Zinba
```



Commonly known as ghost serpents, zinbas are rare, amphibious snakes with healing abilities. They're of similar size to other large snakes, such as pythons, but have a distinct bright blue coloring with red-and-black patterned stripes along their backs. This distinct coloration is easy to spot, but zinbas can swim through the wet mud and soft earth of their homes to avoid being tracked by all but the most skilled pursuers. This elusiveness inspires their "ghost serpent" moniker.

A zinba can metabolize a unique additive for its venom that converts it from a deadly poison to a healing agent, which makes zinbas particularly valuable in the eyes of healers and poachers. There is a high demand for zinbas in many markets; live serpents fetch a hefty sum, but zinba eggs are especially valuable, as zinbas reared in captivity are less willful and more likely to eat in confinement. Their elusiveness, however, leads many to search for their dens instead, which are large pools of water among remote wetlands or underground hollows near bodies of water. The water of a zinba's pool also has minor but valuable healing qualities, but removing water from a den causes it to lose its healing properties after a few hours, so most who find a den attempt to immediately make use of it.

Even finding dens is a difficult prospect, since zinbas are particularly intelligent for animals and can recognize signs of travelers near their favored hiding places. When there are signs of danger, a zinba collapses its lair and flees to create another den elsewhere.
