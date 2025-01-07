---
title: "Nasurgeth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3qFnUcZiGkS7aYii" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/darvakka
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Nasurgeth"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Nasurgeth"
level: "Creature 20"

alignment: ""
size: "grg"
trait_01: [[aquatic]]
trait_02: [[chaotic]]
trait_03: [[darvakka]]
trait_04: [[evil]]
trait_05: [[shadow]]
trait_06: [[undead]]
trait_07: [[unholy]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Greater Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common, Diabolic, Necril; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +36, Athletics: +39, Religion: +36, Stealth: +34, Shadow Plane Lore: +36, The Void Lore: +36"
abilityMods: [11, 6, 7, 8, 8, 7]
speed:  fly 60 feet,  swim 80 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +35, __Ref__ +32, __Will__ +36"
hp: 510
health:
  - name: ""
  - name: HP
    desc: "510, void healing; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 15, silver 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Midnight Depths"
    desc: " (aura,cold,darkness,divine,void) 60 feet. A nasurgeth's entropy grows even stronger underwater. All water within the aura is completely dark (as 4th-rank [[Spells/Darkness|Darkness]]). Magical light with a counteract rank of 4th level or lower, along with magical light cantrips, are suppressed. A living creature entering or starting its turn in the aura takes 4d6 void damage, and the creature also takes an additional 2d10 cold damage if it's in water (DC 39 Fortitude check). If it fails, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute and pulled 10 feet toward the nasurgeth."

  - name: "Spray Black Bile"
    desc: "`pf2:r`  **Trigger** The nasurgeth takes slashing or piercing damage from a critical hit, or a swallowed creature cuts itself free\n* * *\n\n**Effect** Darkness and void energy spill out from the nasurgeth's wound, dealing 8d8 void damage to creatures within 20 feet (DC 40 Fortitude check)."

  - name: "Sunlight Powerlessness"
    desc: "  A nasurgeth caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (magical, reach 15 feet)\n__Damage__  3d10 + 19 piercing plus improved-grab 2d10 cold plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+39 (agile, magical, reach 20 feet)\n__Damage__  3d6 + 19 bludgeoning 2d10 cold"

  - name: "Divine Innate Spells"
    desc: "DC 43, attack +35; __8th __  _[[Spells/Eclipse Burst|Eclipse Burst (x3)]]_, _[[Spells/Harm|Harm (x3)]]_; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (to the Universe, Void, or Netherworld only)]]_, _[[Spells/Truesight|True Seeing]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Broken Barb"
    desc: "`pf2:1`  **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in the nasurgeth's jaws\n* * *\n\n**Effect** The nasurgeth breaks a tooth off in the target, who takes 3d10 bleed and is no longer grabbed or restrained. If the target is adjacent to a surface, the tooth also pins it in place, making it [[Conditions/Immobilized|Immobilized]] ([[Actions/Escape|Escape]] DC 45)."

  - name: "Ravenous Void"
    desc: "`pf2:3`  The nasurgeth barrels forward with their mouth open, Swimming twice in a straight line and moving through the spaces of Huge or smaller creatures. The nasurgeth deals the damage of their jaws Strike to each creature whose space they enter (DC 45 Reflex check). Any creature that critically fails is automatically Swallowed Whole."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 2d10+9 bludgeoning, Rupture 40\n\nA living creature that ends its turn swallowed whole by a nasurgeth becomes [[Conditions/Drained|Drained 1]] or increases its drained condition by 1, and the nasurgeth gains 20 temporary Hit Points. A creature whose drained condition increases to 5 in this way dies.\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Nasurgeth
creatures:
  - 1: Nasurgeth
```



Nasurgeths are hungry voids with glowing eyestalks and thousands of teeth. They lurk deep beneath the waves where the sunlight doesn't reach. At night, they ascend to the skies and rain destruction and ruin down on all the living.

* * *

Darvakkas, also called nightshades, are a ravenous evil made up of equal parts darkness and malice. Originally creatures of the Outer Planes who travel to the convergence of the Shadow Plane and the Void—where the power of nothingness obliterates them—these undead abominations are the physical embodiment of entropy. They burn with an intense hatred for all life, working to bring a final, dark night to the Material Plane where nothing but ash and ice remain.

As creatures twisted by darkness and shadow, darvakkas have a great aversion to sunlight and all sources of vitality energy. On the Material Plane, they spend the hours of daylight hidden below ground, amid ruins, or submerged deep in the ocean's darkest chasms beyond the reach of the sun's rays, emerging when darkness shelters them overhead.

Darvakkas have an aura of entropy that attracts undead thralls to serve as warriors and heralds. They rarely seek alliances with each other or other creatures, existing in solitude as the heads of individual armies of the dead.
