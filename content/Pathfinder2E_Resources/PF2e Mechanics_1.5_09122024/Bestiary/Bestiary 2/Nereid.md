---
title: "Nereid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.x157OC9N25DAhUjz" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Nereid"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Nereid"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[aquatic]]
trait_02: [[chaotic]]
trait_03: [[fey]]
trait_04: [[water]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Low-Light Vision"
languages: "Common, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Deception: +20, Diplomacy: +22, Stealth: +22"
abilityMods: [0, 7, 5, 3, 5, 7]
speed: 25 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +16, __Ref__ +22, __Will__ +18"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  poison; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Watery Transparency"
    desc: " (primal,water) When underwater, the nereid's body is [[Conditions/Invisible|Invisible]]. The nereid can dismiss or resume this transparency as an action that has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Poisonous Touch"
    desc: "+23 (agile, finesse, magical)\n__Damage__  6d6 poison"

  - name: "Primal Innate Spells"
    desc: "DC 29, attack +19; __6th __ (1 slots) _[[Spells/Summon Elemental|Summon Elemental (Water Elementals only)]]_; __5th __ (4 slots) _[[Spells/Control Water|Control Water]]_, _[[Spells/Elemental Form|Elemental Form (Water Only) (x3)]]_; __4th __ (1 slots) _[[Spells/Suggestion|Suggestion]]_"

  - name: "Drowning Touch"
    desc: "`pf2:2` (incapacitation,primal,water) The nereid touches a creature and causes water from its own body to flow into the creature's lungs. If the creature cannot breathe water, it must attempt a DC 29 Fortitude check save.\n\n**Success** The creature is unaffected and is temporarily immune to for 24 hours.\n\n**Failure** The creature becomes [[Conditions/Sickened|Sickened 3]] as it chokes on the water.\n\n**Critical Failure** The creature chokes on the water and runs out of air. It falls unconscious and starts drowning. If the creature is above water, it recovers from drowning as soon as it succeeds at a saving throw against suffocation."

  - name: "Manifest Shawl"
    desc: "`pf2:3` (primal) The nereid divests themself of part of their connection to the First World and imbues this essence into a flowing shawl that enables them to function on land. The nereid can Dismiss this effect as long as they are touching the shawl. As long as the shawl exists, the nereid gains the amphibious trait. A non-nereid who carries the shawl also gains the amphibious trait.\n\nIf a nereid's shawl is destroyed rather than Dismissed, the nereid can't Manifest a Shawl for 24 hours."
 
```

```encounter-table
name: Nereid
creatures:
  - 1: Nereid
```



Nereids are aquatic fey with deep ties to water. They share some similarities with naiads, but they are not guardians and do not bind themselves to a specific body of water. Although they are primarily aquatic creatures, their unique ability to imbue their vitality into a supernatural shawl allows them to travel on land as well. A nereid must be careful when manifesting a shawl, however, as their life essence is bound to it, so it can be stolen or destroyed to threaten the nereid.

Nereids prefer to exist in isolation. Left to their own devices, they avoid combat, but when forced to fight, their ability to transform the natural waters in their flesh into poison serves them as well as any weapon.

Often, ignorant sailors lump all water-dwelling fey into a single category of "aquatic tempters", regardless of the fey's type or gender, using these creatures' names interchangeably to represent the concept of a beautiful figure who exists to lure mortals to a drowning death. Whereas naiads have more patience and often seek to educate the ignorant regarding the harm that stereotypes can cause, nereids and rusalkas have little patience for such methods. Rusalkas are the primary source for the legends of fey preying upon sailors, and nereids loathe them for that, as they prefer to live apart from humanity and enjoy the beauty of the natural world in peace.

When a nereid learns of a rusalka's increased activity, it often seeks out the rusalka to route them-not so much out of an urge to protect humanoids (in whom nereids traditionally have little interest), but to prevent the rusalka from inadvertently riling up violent responses from humanoids who can't be bothered to note the difference between a murderous fey and one who just wants to be left alone.
