---
title: "Agyra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IdC8APNVxuuR0shb" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/kaiju
  - pf2e/creature/type/mythic
  - pf2eMonster
  - pf2e/creature/level/23
  - remaster
statblock: inline
name: "Agyra"
level: 23
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder War of Immortals"
name: "Agyra"
level: "Creature 23"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[kaiju]]
trait_03: [[mythic]]
modifier: 38
perception:
  - name: "Perception"
    desc: "+38; Darkvision"
languages: "Tien; (can’t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +43, Athletics: +41"
abilityMods: [10, 11, 9, -2, 6, 6]
speed: 40 feet
sourcebook: "_Pathfinder War of Immortals_"
ac: 49
armorclass:
  - name: AC
    desc: "49; __Fort__ +37, __Ref__ +40, __Will__ +34; mythic resilience (Fort and Ref)"
hp: 475
health:
  - name: ""
  - name: HP
    desc: "475; __Immunities__  death effects,  disease,  drained,  electricity,  fear effects,  paralyzed; __Resistances__ acid 20, fire 20, sonic 20"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Mythic) Remove a Condition|Remove a Condition]]"
    desc: "`pf2:1` (concentrate) **Cost** 1 Mythic Point\n* * *\n\n**Effect** Agyra removes any one condition currently affecting her."

  - name: "Stormsight"
    desc: "  Wind, precipitation, and clouds don't impair Agyra's vision; she ignores the [[Conditions/Concealed|Concealed]] condition from storms, mist, precipitation, and the like."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Electrified Rebirth"
    desc: " (electricity,primal) **Frequency** once per year\n* * *\n\n**Effect** When Agyra dies, her corpse crackles and sparks with electrical energy. Any creature that touches Agyra's body within 1 hour of her death takes 11d6 electricity damage (basic DC 43 Reflex check save). After being dead for 1 minute, Agyra is immediately resurrected in the same place, at full health, with all abilities fully restored. She normally takes advantage of this rebirth to flee to safety, using Thunderous Departure to retreat. If Agyra has already died and been reborn in the same year, she remains permanently dead upon being slain a second time."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Immunity|Mythic Immunity]]"
    desc: "  Strikes\n* * *\n\nThe creature is immune to either harmful spells cast by non-mythic creatures, or Strikes made with non-mythic weapons and unarmed Strikes from non-mythic characters. Only the most powerful creatures (typically level 25) should be immune to both."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Resilience|Mythic Resilience]]"
    desc: "  Agyra treats her saving throws with Fortitude and Reflex saves as one step better than they actually are (so a critical failure is a failure, a failure is a success, and a success is a critical success). Whenever a character rolls a critical hit against Agyra, they must reroll the attack roll and take the new result."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Talon"
    desc: "+40 (agile, magical, reach 15 feet)\n__Damage__  4d10 + 14 slashing 2d8 electricity"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+40 (magical, reach 10 feet)\n__Damage__  3d12 + 14 piercing 2d8 electricity"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+40 (deadly d10, magical, reach 20 feet)\n__Damage__  4d8 + 14 bludgeoning 2d6 bleed"

  - name: "**Ranged** `pf2:1` Spike"
    desc: "+42 (magical, range increment 60 feet)\n__Damage__  7d6 + 10 piercing"

  - name: "Blinding Flash"
    desc: "`pf2:3` (light,manipulate,primal,visual) **Cost** 1 Mythic Point\n* * *\n\n**Effect** By spreading her wings while she stands upon the ground, Agyra can create a blinding flash of light that targets all creatures within 100 feet. Affected creatures must succeed at a DC 43 Fortitude check check.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Dazzled|Dazzled]] and [[Conditions/Stupefied|Stupefied 1]] for [[/gmr 1d4 #rounds]]{1d4 rounds}.\n\n**Failure** The target is [[Conditions/Blinded|Blinded]] and [[Conditions/Stupefied|Stupefied 2]] for 1 minute.\n\n**Critical Failure** The target is blinded and stupefied 2 for 10 minutes."

  - name: "Conjure Hurricane"
    desc: "`pf2:3` (air,manipulate,primal) **Frequency** once per day\n\n**Cost** 1 Mythic Point\n* * *\n\n**Effect** Agyra generates a hurricane that spreads across a 4-mile radius and lasts 24 hours, with a 500-foot calm eye of the storm at its center. Agyra is at the center of this hurricane when it is formed, but it moves normally (according to surrounding weather conditions and the GM's discretion) afterward."

  - name: "Lightning Breath"
    desc: "`pf2:2` (electricity,primal) Agyra exhales a line of electricity from each of her two heads. Each line is 120 feet long and 10 feet wide, and the two lines may be pointed in different directions. A creature in a line takes 22d6 electricity damage (basic DC 44 Reflex check save). On a failed save, the target is also [[Conditions/Slowed|Slowed 1]] for [[/gmr 1d4 #rounds]]{1d4 rounds}. A creature can be affected only once by a line, even if they are in an overlapping area. A character slain by Agyra's Lightning Breath remains electrified for [[/gmr 2d4 #rounds]]{2d4 rounds} after death. A creature touching such a corpse takes 3d6 electricity damage (no save). Agyra can't use Lightning Breath for [[/gmr 1d4 #rounds]]{1d4 rounds}."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Power|Mythic Power]]"
    desc: "  The creature has a pool of 3 Mythic Points, and can spend those Mythic Points for any of the actions it has."

  - name: "[[Creature Family Ability Glossary/(Mythic) Recharge|Recharge Ability]]"
    desc: "`pf2:1` (concentrate) **Cost** 1 Mythic Point\n* * *\n\n**Effect** Agyra gains an additional use of lightning breath."

  - name: "Stormflight"
    desc: "  Agyra can move in strong winds with ease. She doesn't treat wind as difficult terrain or need to Maneuver in Flight in high winds."

  - name: "Thunderous Departure"
    desc: " (primal,sonic) **Frequency** once per day\n* * *\n\n**Effect** Agyra Flies in a straight line at incredible speed, moving at least 120 feet but up to 1 mile. This movement doesn't provoke reactions. Her departure leaves behind a thunderous sonic boom, creating a 100-foot burst centered on her point of departure. All creatures in the area take 15d10 sonic damage (basic DC 46 Fortitude check save). A creature who fails is also knocked [[Conditions/Prone|Prone]], and a creature who critically fails is knocked prone and [[Conditions/Deafened|Deafened]] permanently."
 
```

```encounter-table
name: Agyra
creatures:
  - 1: Agyra
```



### The Forever Storm

Agyra is a massive kaiju who protects Spinescar Island and its inhabitants.
