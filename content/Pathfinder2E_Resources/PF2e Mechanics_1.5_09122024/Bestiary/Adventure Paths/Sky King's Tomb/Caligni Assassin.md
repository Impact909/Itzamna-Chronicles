---
title: "Caligni Assassin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Z7b5lmed3v0id9HS" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Caligni Assassin"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Caligni Assassin"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[caligni]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[shadow]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Greater Darkvision"
languages: "Caligni, Sakvroth, Shadowtongue, Shae"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +15, Deception: +13, Intimidation: +15, Occultism: +13, Stealth: +20"
abilityMods: [3, 6, 4, 3, 2, 1]
speed: 40 feet
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +18, __Will__ +12"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Gauntlet|+1 Striking Spiked Gauntlet]], 4x [[Equipment/Throwing Knife|Throwing Knife]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Shadow Shift"
    desc: "  Caligni assassins are [[Conditions/Concealed|Concealed]] in dim light or darkness even to creatures that can see clearly in those light levels."

  - name: "Swift Sneak"
    desc: "  The assassin can move their full speed while Sneaking."

abilities_mid:
  - name: ""
  - name: "Countershadow"
    desc: "`pf2:r` (darkness,occult) **Trigger** A creature within 60 feet casts a light spell\n* * *\n\n**Effect** The caligni assassin attempts to counteract the triggering spell. Caligni assassins automatically recognize light spells."

  - name: "Death Umbral Shroud"
    desc: " (darkness,occult) When a caligni assassin dies, their body disintegrates into a veil of supernatural darkness for 1 round. A 4th-rank [[Spells/Darkness|Darkness]] spell appears, centered on the assassin's location, with a counteract DC of 23."

  - name: "Deny Advantage"
    desc: "  The assassin isn't [[Conditions/Off-Guard|Off-Guard]] to creatures of 8th level or lower that are [[Conditions/Hidden|Hidden]], undetected, flanking, or using surprise attack."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Gauntlet"
    desc: "+21 (agile, finesse, magical, versatile s)\n__Damage__  2d4 + 9 piercing plus umbral-veil"

  - name: "**Ranged** `pf2:1` Throwing Knife"
    desc: "+19 (agile, finesse, thrown 20 ft.)\n__Damage__  1d4 + 9 piercing"

  - name: "Quick Draw"
    desc: "`pf2:1`  You draw your weapon and attack with the same motion. You Interact to draw a weapon, then Strike with that weapon."

  - name: "Shadow Leap"
    desc: "`pf2:3` (darkness,occult,teleportation) **Requirements** The assassin is in dim light or darkness\n* * *\n\n**Effect** The assassin vanishes into shadow, appearing in a square of dim light or darkness within 60 feet. If the assassin appears adjacent to a creature, they can Strike that creature, otherwise the assassin can Hide."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The assassin deals an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Umbral Veil"
    desc: "`pf2:1` (darkness) **Requirements** The assassin's last action was a successful melee Strike\n* * *\n\n**Effect** The assassin extends a tendril of shadow to obscure the target's vision, [[Conditions/Blinded|blinding]] them for 1 round (DC 23 Will check negates). On a critical failure, they're blind for 1 minute. Creatures with greater darkvision are immune to this ability."
 
```

```encounter-table
name: Caligni Assassin
creatures:
  - 1: Caligni Assassin
```



Lauded and shunned, caligni assassins often become unwitting pawns in clashes between caligni settlements or between rival factions of caligni society.

* * *

Calignis often get stereotyped as murderers, but the title of assassin is one of the rarest in their society. Caligni settlements go decades without having offspring born with enough potential. However, once a child shows they have "the gift"; the settlements leaders might give the babe to the owb, who mold and shape the child into an instrument of shadows and death.

## Shadowfade

Caligni assassins gain their power from an infusion of planar essence directly from the Netherworld, which the owb help them develop into powerful abilities. This comes at a cost: all caligni assassins eventually succumb to an affliction known as shadowfade. This magical malady causes the caligni's body to painfully warp when concealed in shadows, as the plane's ability to create twisted reflections of reality changes their physical form directly.

Sometimes a caligni assassin will flee home and strike out on their own to avoid becoming a twisted tool for their greedy leaders. Such freelancers are in high demand for those seeking a fatal solution to their own political problems.
