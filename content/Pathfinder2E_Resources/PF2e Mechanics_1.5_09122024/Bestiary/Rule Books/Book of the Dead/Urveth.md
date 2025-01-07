---
title: "Urveth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rUeRlPvE9ws3RTdm" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/darvakka
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Urveth"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Urveth"
level: "Creature 18"

alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[darvakka]]
trait_03: [[evil]]
trait_04: [[shadow]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Greater Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common, Diabolic, Necril; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +29, Athletics: +35, Religion: +32, Stealth: +31, Shadow Plane Lore: +31, The Void Lore: +31"
abilityMods: [10, 5, 8, 5, 6, 6]
speed: 25 feet,  burrow 60 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +29, __Will__ +34"
hp: 460
health:
  - name: ""
  - name: HP
    desc: "460, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 15, silver 15; __Resistances__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  Claw only. An urveth gains 3 extra reactions each round that they can use only to make Attacks of Opportunity.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Entropy's Shadow"
    desc: " (aura,divine,void) 60 feet. Urveths leak entropy and corruption from their very being. A living creature entering or starting its turn in the aura takes 5d6 void damage with a DC 38 Fortitude check. If it fails, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute and pulled 10 feet toward the urveth."

  - name: "Sunlight Powerlessness"
    desc: "  A urveth caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (magical, reach 15 feet)\n__Damage__  3d10 + 14 slashing plus improved-grab 2d10 cold plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+36 (agile, magical, reach 15 feet)\n__Damage__  3d6 + 14 slashing 2d10 cold"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+36 (magical, poison, reach 20 feet)\n__Damage__  3d6 + 14 piercing plus urveth-venom 2d10 cold plus urveth-venom"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __8th __  _[[Spells/Harm|Harm (x3)]]_; __7th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Interplanar Teleport|Plane Shift (to the Universe, Void, or Netherworld only)]]_, _[[Spells/Truesight|True Seeing]]_; __4th __  _[[Spells/Darkness|Darkness (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(9th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Frenzy"
    desc: "`pf2:2`  The urveth makes two claw Strikes and one stinger Strike in any order."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 2d10+5 bludgeoning, Rupture 35\n\nA living creature that ends its turn swallowed whole by an urveth becomes [[Conditions/Drained|Drained 1]] or increases its drained condition by 1, and the urveth gains 10 temporary Hit Points. A creature whose drained condition increases to 5 in this way dies.\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Urveth Venom"
    desc: " (poison) **Saving Throw** DC 37 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 void damage and 2d6 poison damage (1 round)\n\n**Stage 2** 3d6 void damage and 2d6 poison damage, and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 3d6 void damage and 2d6 poison damage, and [[Conditions/Enfeebled|Enfeebled 4]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Urveth
creatures:
  - 1: Urveth
```



An urveth is a massive, four-armed burrowing terror with a wormlike body and gaping maw that devours everything it can. Urveths burrow deep underground to hide from the sun, emerging under the cover of darkness to kill and consume.

* * *

Darvakkas, also called nightshades, are a ravenous evil made up of equal parts darkness and malice. Originally creatures of the Outer Planes who travel to the convergence of the Shadow Plane and the Void—where the power of nothingness obliterates them—these undead abominations are the physical embodiment of entropy. They burn with an intense hatred for all life, working to bring a final, dark night to the Material Plane where nothing but ash and ice remain.

As creatures twisted by darkness and shadow, darvakkas have a great aversion to sunlight and all sources of vitality energy. On the Material Plane, they spend the hours of daylight hidden below ground, amid ruins, or submerged deep in the ocean's darkest chasms beyond the reach of the sun's rays, emerging when darkness shelters them overhead.

Darvakkas have an aura of entropy that attracts undead thralls to serve as warriors and heralds. They rarely seek alliances with each other or other creatures, existing in solitude as the heads of individual armies of the dead.
