---
title: "Sea Serpent"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8glLKP9lvQ6Hw7DH" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Sea Serpent"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sea Serpent"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +26, Stealth: +28"
abilityMods: [8, 4, 6, -4, 2, 0]
speed: 20 feet,  swim 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +25, __Ref__ +21, __Will__ +21"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210"
abilities_top:
  - name: ""

  - name: "Undetectable"
    desc: " (primal) A sea serpent automatically tries to counteract any detection, revelation, or scrying divination attempted against it, using its Stealth check modifler for its counteract modifier."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 20 feet)\n__Damage__  3d10 + 14 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+27 (agile, reach 30 feet)\n__Damage__  2d10 + 14 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Water Spout"
    desc: "+25 (brutal, range increment 100 feet, water)\n__Damage__  2d6 + 12 bludgeoning plus sea-serpent-algae"

  - name: "Capsize"
    desc: "`pf2:1` (attack) The sea serpent attempts to capsize an aquatic vessel of its size or smaller that it's adjacent to. It must succeed at an DC 35 Athletics check check with a DC of 35 (reduced by 5 for each size smaller than the sea serpent) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d10+14 bludgeoning, DC 32 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Sea Serpent Algae"
    desc: " (incapacitation,poison) The water in the ballast organs around the sea serpent's neck is full of psychotropic algae.\n\n**Saving Throw** DC 34 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Confused|Confused]] and, if flying, spends its first action each turn to descend 20 feet (1 round)\n\n**Stage 2** confused and, if flying, descends until reaching the ground or water below (1 round)"

  - name: "Spine Rake"
    desc: "`pf2:2` (attack,move) The sea serpent extends the spines along its back and Swims or Strides. Each creature the serpent is adjacent to at any point during its movement takes 4d6+8 slashing damage (DC 32 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 2d10+6 bludgeoning, Rupture 20\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sea Serpent
creatures:
  - 1: Sea Serpent
```



These fabled beasts resemble massive snakes with long rows of finned spines down their back. Temperamental and territorial, sea serpents can capsize a boat with ease, and most won't hesitate to do so when hungry or threatened. Stories abound of aggrieved captains who spend their entire lives hunting down the elusive monster that sunk their ships and took their livelihoods. These hunts rely on rumors and glimpses of the beasts, as few survive the catastrophes wrought by sea serpents.

While many fishermen's tales paint sea serpents as divinely appointed guardians of the ocean or as evil and demonic agents, the truth is that most sea serpents are simply very large beasts with a knack for avoiding magical detection.
