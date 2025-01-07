---
title: "Froghemoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nQbk0mba8TIouIbg" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/amphibious
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Froghemoth"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Froghemoth"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[amphibious]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +27, Stealth: +27"
abilityMods: [8, 6, 7, -4, 6, 4]
speed: 20 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 32
armorclass:
  - name: AC
    desc: "32 all-around vision; __Fort__ +26, __Ref__ +21, __Will__ +23"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Immunities__  electricity"
abilities_top:
  - name: ""

  - name: "Otherworldly Vision"
    desc: " (visual) A froghemoth's alien eyes allow it to perceive creatures within 30 feet, even if they are [[Conditions/Invisible|Invisible]] or ethereal. It can still be fooled by successful Stealth checks to [[Actions/Hide|Hide]], but it has Perception DC 38 in such cases. It also sees through and is unaffected by illusions with the visual trait if they are within 30 feet."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Electric Torpor"
    desc: "  Though a froghemoth is immune to electricity damage, it is [[Conditions/Slowed|Slowed 1]] for 1 round whenever it would have otherwise taken electricity damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 10 feet)\n__Damage__  3d12 + 14 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+27 (agile, reach 15 feet)\n__Damage__  3d8 + 14 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+27 (agile, reach 30 feet)\n__Damage__  2d10 + 14 piercing plus barbed-tongue"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  40 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Barbed Tongue"
    desc: "  A creature hit by the froghemoth's tongue becomes [[Conditions/Grabbed|Grabbed]] by the froghemoth. The creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the froghemoth's tongue. A creature can sever the tongue with a successful Strike against AC 31 that deals at least 15 slashing damage.\n\nThis deals no damage to the froghemoth but prevents it from using its tongue Strike until it regrows its tongue, which takes 1 minute."

  - name: "Flailing Tentacles"
    desc: "`pf2:2`  The froghemoth makes up to four tentacle Strikes, each against a different target. These count toward the froghemoth's multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d6+12 bludgeoning damage, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Retract Tongue"
    desc: "`pf2:2`  The froghemoth pulls a creature grabbed by its tongue toward itself. The froghemoth rolls an Athletics check check against the creature's Fortitude DC. On a success, the froghemoth pulls the creature into an adjacent space, and if it critically succeeds it can also make a bite Strike against the creature after the pull."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d6+9 bludgeoning damage, Rupture 24\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Froghemoth
creatures:
  - 1: Froghemoth
```



A terrifying abomination of teeth, tentacles, and unbridled rage, the froghemoth is thankfully rarely encountered even in the deepest swamplands or most remote Darklands caverns. Capable of devouring dinosaurs and even dragons, it is a frighteningly effective ambush hunter, immersing itself in the mire with only its eyestalk protruding and watching in every direction at once with uncanny precision.
