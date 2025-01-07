---
title: "Zomok"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nf8xqU1ylgoXFdca" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Zomok"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Zomok"
level: "Creature 16"

alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[plant]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Arboreal, Common, Fey, Petran; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +33, Nature: +29, Stealth: +29, Survival: +30"
abilityMods: [9, 5, 9, 3, 6, 6]
speed: 30 feet,  fly 80 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +31, __Ref__ +25, __Will__ +28"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310; __Immunities__  paralyzed,  poison,  sleep,  stunned; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 15 feet)\n__Damage__  3d12 + 17 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 15 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (magical, reach 20 feet)\n__Damage__  3d10 + 17 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 34, attack +26; __8th __  _[[Spells/Charm|Charm (plant creatures only)]]_; __7th __  _[[Spells/Wall of Thorns|Wall of Thorns]]_; __6th __  _[[Spells/Tangling Creepers|Tangling Creepers]]_; __1st __  _[[Spells/Vanishing Tracks|Pass Without Trace]]_\n__Constant__  __(4th)__ _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Rituals"
    desc: "_Blight_, _Plant Growth_, _Primal Call (doesn't require secondary casters)_"

  - name: "Entombing Breath"
    desc: "`pf2:2` (earth,primal) The zomok blasts forth a 60-foot cone of earth and gravel, dealing 17d6 bludgeoning damage (DC 34 Reflex check save); [[Conditions/Prone|Prone]] creatures take a -2 circumstance penalty to this saving throw. Creatures touching the ground that fail their saves take a 10-foot circumstance penalty to their Speeds and are [[Conditions/Restrained|Restrained]] (Escape DC 34) on a critical failure.\n\nThe zomok can't use Entombing Breath again for 1d4 rounds.\n\nThe bodies of creatures slain by Entombing Breath instantly decompose and are destroyed-they can be restored to life only by a 7th-rank or higher spell or ritual that restores life. The creature's equipment is unharmed but buried under 5 feet of earth."

  - name: "Forest Step"
    desc: "`pf2:1` (healing,primal,teleportation) **Frequency** three times per day\n* * *\n\n**Effect** The zomok teleports itself with the effects of a 5th-rank [[Spells/Translocate|Translocate]] spell, but the zomok must begin and end the teleportation effect in forest terrain. The zomok regains 10d10 healing Hit Points during this teleportation. Creatures swallowed by the zomok are left behind.\n\nThe zomok can't use Forest Step again for [[/gmr 1d6+1 #rounds]]{1d6+1 rounds}."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d12+9 bludgeoning damage, Rupture 35\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, tail, DC 32 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zomok
creatures:
  - 1: Zomok
```



Mighty plant-dragons, zomoks prowl the woodlands, defending their homes from destructive forces while healing and restoring the woods following natural disasters and ravaging intruders. Zomoks vary in appearance with the seasons, growing verdant green in the spring and summer, changing to autumnal colors in the fall, and decaying to brown in winter. While zomoks can and often do swallow their foes, they have no real need to eat. Any creature they gulp down is typically left behind as a mangled corpse the next time the zomok travels via their Forest Step ability. Zomoks reach 35 to 40 feet in length and weigh 30 tons.
