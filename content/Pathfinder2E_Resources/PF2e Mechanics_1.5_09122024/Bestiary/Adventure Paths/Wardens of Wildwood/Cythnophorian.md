---
title: "Cythnophorian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mL0rxTDbOWjB2aS3" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Cythnophorian"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Cythnophorian"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "tiny"
trait_01: [[fungus]]
trait_02: [[plant]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Lifesense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +15"
abilityMods: [4, 3, 6, -2, 2, 1]
speed: 15 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +14, __Will__ +12"
hp: 161
health:
  - name: ""
  - name: HP
    desc: "161; __Immunities__  mental; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Horrifying Display"
    desc: "`pf2:0` (emotion,fear,mental,visual) **Trigger** The cythnophorian uses Fungal Possession\n* * *\n\n**Effect** All creatures in a 10-foot emanation must attempt a DC 26 Will check save or become [[Conditions/Sickened|Sickened 1]], or [[Conditions/Sickened|Sickened 2]] on a critical failure. Affected creatures are [[Conditions/Off-Guard|Off-Guard]] for as long as they're sickened. Once a creature attempts this save, it's temporarily immune for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+18 ()\n__Damage__  2d10 + 10 piercing plus creeping-death,fungal-possession"

  - name: "Creeping Death"
    desc: " (contact,poison) **Saving Throw** DC 22 Fortitude check\n\n**Onset** 1 round\n\n**Stage 1** 2d6 poison damage and [[Conditions/Stunned|Stunned 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Confused|Confused]] (1 round)\n\n**Stage 4** 6d6 poison damage and [[Conditions/Controlled|Controlled]] (1 round). A creature that dies while infected with creeping death immediately releases a burst of spores as if using the cythnophorian's Spore Cloud ability. If the corpse is not burned, it rises as the host of a new cythnophorian 12 hours later."

  - name: "Fungal Possession"
    desc: "`pf2:2` (concentrate,manipulate,move,possession) **Requirements** The cythnophorian's last action was a Strike that killed a target of size Medium or smaller\n* * *\n\n**Effect** The cythnophorian rips itself out of its current host and burrows its way into the corpse of its latest victim, regaining 3d4 healing Hit Points and taking control of the corpse as its new host. The cythnophorian enters the space of its new host, and its former host's corpse falls to the ground in its previous space. Moving to a new host doesn't change the cythnophorian's abilities or movement Speeds."

  - name: "Spore Cloud"
    desc: "`pf2:1` (incapacitation,poison) The cythnophorian emits a cloud of toxic spores, exposing all creatures within a 15-foot emanation to creeping death. The cythnophorian can't use Spore Cloud again for 1d4 rounds."
 
```

```encounter-table
name: Cythnophorian
creatures:
  - 1: Cythnophorian
```



In its natural state, a fully grown cythnophorian resembles a wriggling mass of tendrils and fibrous growths approximately the size of a house cat. Although fully capable of locomotion in this form, a cythnophorian is rarely encountered outside a host, typically a humanoid or animal corpse, which the creature burrows into and animates from within like a grisly flesh puppet. Once so ensconced, the cythnophorian seeks out new victims to infect with its noxious spores, seizing control of their bodies for its own ends until they succumb to the deadly toxin and become incubators for new cythnophorians.

A Medium-sized corpse is typically sufficient to sustain a cythnophorian for two weeks before it must seek out a fresh one. If unable to locate a new host in that time, the creature enters a dormant state, withdrawing into an unremarkable seed pod roughly the size of a child's fist, where it can lie in wait for years until a suitable victim presents itself.

## Unknown Origins

Opinions vary as to the exact nature of these creatures, with many scholars citing their similarities to the fungal parasites known as cythnigots as evidence of some qlippoth connection. Still others theorize that they began as a natural form of plant life that gradually became twisted and corrupted, deliberately or otherwise, by prolonged exposure to the foul energies of Cyth-V'sug, demon lord of fungus and rot.
