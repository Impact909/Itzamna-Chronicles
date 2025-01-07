---
title: "Decapod Dinghy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.X9xJVAYWVudncsZH" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Decapod Dinghy"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Decapod Dinghy"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[beast]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Thalassic; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +18, Nature: +17, Stealth: +15"
abilityMods: [7, 3, 4, -2, 3, 0]
speed: 30 feet,  climb 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +15, __Will__ +15"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  poison; __Weaknesses__ bludgeoning 5"
abilities_top:
  - name: ""

  - name: "All Aboard"
    desc: "  A decapod dinghy can carry up to 30 Bulk of creatures or unattended items on their back, such as five Medium creatures. The anemones' gentle hold on the passengers is sufficient in most situations, but while in combat, those passengers are [[Conditions/Slowed|Slowed 1]] if they want to take other actions while remaining on the decapod dinghy's back."

  - name: "Anemone Transport"
    desc: "`pf2:3` (primal,teleportation) The decapod dinghy and all their willing passengers teleport to a patch of anemones within 10 miles large enough for the decapod dinghy to stand among them. Although the decapod dinghy doesn't need to see the location, they must have been there before. All creatures transported are temporarily immune to this ability for 24 hours."

abilities_mid:
  - name: ""
  - name: "Inflate Anemones"
    desc: "`pf2:1`  The anemones on the decapod dinghy's back inflate, enveloping all passengers and giving each passenger a +2 circumstance bonus to AC until the beginning of the decapod dinghy's next turn."

  - name: "Protect Passenger"
    desc: "`pf2:r`  **Trigger** An enemy within 20 feet damages one of the decapod dinghy's passengers\n* * *\n\n**Effect** The decapod dinghy's anemones lash out for a tentacle Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (reach 10 feet)\n__Damage__  2d8 + 7 slashing 2d6 poison"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+19 (poison, reach 20 feet)\n__Damage__  5d6 poison plus grab"

  - name: "Stinging Anemones"
    desc: "`pf2:1` (poison) The decapod dinghy's anemones sting any number of creatures they choose among passengers and those the decapod dinghy has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]. The stings deal 5d6 poison damage (DC 26 Fortitude check). On a failed save, that creature is also [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour."
 
```

```encounter-table
name: Decapod Dinghy
creatures:
  - 1: Decapod Dinghy
```



Decapod dinghies are massive crabs indigenous to the Okaiyo Ocean that often assist the local humanoids with transportation. They can understand Thalassic and are instantly recognizable by the colorful anemones they carry on their backs and in their front claws. Athamarus and merfolk are common sights atop decapod dinghies, lounging comfortably amidst the anemones and sharing food with their hosts.

This peaceful cooperation is indirectly caused by the legendary crustacean Tehialai-Thief-Of-Ships. Since Tehialai's rampages are a constant threat in the Okaiyo, the ancestors of the decapod dinghies bonded with other marine life to survive. Decapod dinghies' relationship with anemones is particularly tight, using the small creatures as poisonous extensions of their own bodies and using their response to movements in the water to compensate for the decapod dinghy's otherwise poor vision. In a region wracked by Tehialai's storms, everyone needs to band together, after all.
