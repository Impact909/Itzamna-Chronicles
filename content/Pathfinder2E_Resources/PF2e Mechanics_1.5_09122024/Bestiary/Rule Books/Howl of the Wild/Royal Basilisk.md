---
title: "Royal Basilisk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mhWTk1WTNrqgee0Y" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Royal Basilisk"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Royal Basilisk"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +27, Stealth: +24, Survival: +25"
abilityMods: [8, 5, 7, -3, 6, 2]
speed: 30 feet,  climb 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +22, __Will__ +23"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  poison; __Resistances__ acid 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Iron Crown"
abilities_mid:
  - name: ""
  - name: "Crowned Royalty"
    desc: "  The royal basilisk's crown is firmly attached to its head but can be [[Actions/Disarm|Disarmed]] as though it were a held item. Without a crown, the royal basilisk's mastery over poison is weakened enough that it loses its miasmatic shroud. The royal basilisk can equip a crown within its tail's reach as an Interact action. A royal basilisk's crown is normally made of iron and enables the basilisk to use miasmatic shroud, but crowns made of other, more exotic materials might confer different abilities."

  - name: "Miasmatic Shroud"
    desc: " (aura,poison) 15 feet. The poison in the breath of the royal basilisk makes the air around it a haze, concealing it from all creatures outside the aura, but it cannot use this concealment to Hide or [[Actions/Sneak|Sneak]]. When a creature ends its turn within the aura, it is exposed to royal basilisk venom."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 10 feet)\n__Damage__  4d10 + 11 piercing plus improved-grab,royal-basilisk-venom"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+27 (agile, reach 15 feet)\n__Damage__  4d8 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+24 (poison, range 120 feet)\n__Damage__  5d10 poison plus royal-basilisk-venom"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  4d8+3 bludgeoning, DC 32 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Royal Basilisk Venom"
    desc: " (poison) **Saving Throw** DC 36\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d10 poison and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 3d10 poison and [[Conditions/Clumsy|Clumsy 3]] (1 round)\n\n**Stage 3** 4d10 poison, clumsy 3, and [[Conditions/Slowed|Slowed 1]] (1 round)"

  - name: "Stone-Hewing Spit"
    desc: "`pf2:2` (acid) The royal basilisk spits its poison with immense force, dealing 5d10 acid and 5d8 piercing damage (DC 32 Reflex check save) to creatures in a 240-foot line and exposing each creature that took damage to royal basilisk venom. The line penetrates barriers with Hardness of less than 20, ignoring any bonuses they'd provide from cover. The royal basilisk can't use Stone-Hewing Spit again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 5d10 acid, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Wrap in Coils"
    desc: "`pf2:1`  **Requirements** A Large or smaller creature is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in the royal basilisk's jaws\n* * *\n\n**Effect** The royal basilisk moves the creature into its coils, freeing its jaws to make attacks, then uses Greater Constrict against the creature. The royal basilisk's coils can hold as many creatures as will fit in its space."
 
```

```encounter-table
name: Royal Basilisk
creatures:
  - 1: Royal Basilisk
```



The royal basilisk is aptly named, not for only the metal crown upon its head but also for the unique potency of its poison. The creature's poison manifests as a sort of cloying vapor that sticks onto and eats away at anything it touches. Their mastery of poison does appear to come at a cost, as the royal basilisk has no ability to petrify its prey. Although the royal basilisk can painstakingly shape a crown, some made of simple iron and others of rare skymetals, they much prefer to collect crowns crafted by other creatures.
