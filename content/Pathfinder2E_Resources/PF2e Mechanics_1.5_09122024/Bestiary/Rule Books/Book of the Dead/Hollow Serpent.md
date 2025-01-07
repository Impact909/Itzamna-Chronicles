---
title: "Hollow Serpent"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gBuQfX3DNa4IRHXu" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Hollow Serpent"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Hollow Serpent"
level: "Creature 15"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Lifesense 60 Feet, Scent (Imprecise) 60 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +30, Stealth: +29"
abilityMods: [7, 8, 6, -2, 4, 3]
speed: 50 feet,  climb 50 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +26, __Ref__ +30, __Will__ +24"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, void healing; __Immunities__  disease,  paralyzed,  poison,  polymorph,  unconscious"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Desiccation Aura"
    desc: " (aura,divine) 30 feet. A cloud of choking, acrid dust swirls about the hollow serpent, draining moisture from any enemy within. A creature entering the aura or starting its turn in the aura must succeed at a DC 34 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Slowed|Slowed 1]] for 1d4 rounds (2d4 rounds on a critical failure). A creature that succeeds is temporarily immune for 24 hours."

  - name: "Divine Guardian"
    desc: "`pf2:r`  **Trigger** An ally within the hollow serpent's reach is attacked\n* * *\n\n**Effect** The hollow serpent interposes a coil of its body or tail between the ally and attacker. The triggering attack targets the hollow serpent instead of the original target."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (reach 10 feet)\n__Damage__  4d10 + 15 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (agile, reach 15 feet)\n__Damage__  3d10 + 15 bludgeoning plus improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 35, attack +27; __7th __  _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination (Drawing in Moisture Rather than Blood)]]_\n__Constant__  __(7th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d10+7 bludgeoning plus [[Conditions/Drained|Drained 1]], DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Slithering Strike"
    desc: "`pf2:1`  The hollow serpent Strides or Climbs and makes a jaws Strike at the end of that movement. If the hollow serpent began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 4d6 void plus [[Conditions/Drained|Drained 1]], Rupture 32\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Hollow Serpent
creatures:
  - 1: Hollow Serpent
```



A hollow serpent is the dried and shriveled husk of an enormous constrictor snake, animated by fell magic to serve its masters. According to the oldest holy books of serpentfolk, the first hollow serpents were raised by Ydersius. The god took the cast-off skins of great snakes and filled them with hunger and hatred, a bottomless yearning for mortal life that could never be filled. In due course, the priests of the serpentfolk learned to replicate their lord's trick, and in the millennia since the serpentfolk's fall, the knowledge has slithered into the libraries of other necromancers and sorcerers.

Despite their menacing reputation and great power, hollow serpents are a relatively uncomplicated creation. They were designed first and foremost as guardians, and serpentfolk liches of a suitable level of power are sometimes accompanied by hollow serpents. A few have struck out on their own over the years, usually due to outliving their original creators. Driven by their hunger and dim intellect, they take up residence in remote ruins or deep caverns. Those that study such things believe at least one serpent, perhaps one of the original creatures made by Ydersius, survives in the mountains west of Geb.
