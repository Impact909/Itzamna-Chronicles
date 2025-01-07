---
title: "Kobold Cavern Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BHESkWRERy2kTbtc" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Kobold Cavern Mage"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Kobold Cavern Mage"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[humanoid]]
trait_02: [[kobold]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Common, Fey, Petran, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Deception: +8, Diplomacy: +8, Intimidation: +8, Nature: +5, Stealth: +6"
abilityMods: [2, 2, -1, 0, 1, 4]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +6, __Will__ +7"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Resistances__ cold 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Light Hammer|Light Hammer]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+6 (agile, finesse)\n__Damage__  1d6 + 2 slashing"

  - name: "**Melee** `pf2:1` Light Hammer"
    desc: "+6 (agile)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Light Hammer"
    desc: "+6 (agile, thrown 20 ft.)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "Primal Spontaneous Spells"
    desc: "DC 18, attack +10; __1st __ (4 slots) _[[Spells/Fleet Step|Fleet Step]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Pummeling Rubble|Pummeling Rubble]]_, _[[Spells/Runic Weapon|Runic Weapon]]_\n__Cantrips__  __(1st)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Inspiring Display"
    desc: "`pf2:1` (auditory,emotion,linguistic,mental) **Requirements** The cavern mage's previous action was to Cast a Spell\n* * *\n\n**Effect** The cavern mage uses their magical display to inspire another kobold within 30 feet. That kobold gains 4 temporary Hit Points that last until the start of the cavern mage's next turn.\n\n[[Bestiary Effects/Effect_ Inspiring Display|Effect: Inspiring Display]]"

  - name: "Scamper"
    desc: "`pf2:1`  **Requirements** The kobold cavern mage is adjacent to at least one enemy\n* * *\n\n**Effect** The kobold cavern mage Strides up to their Speed plus 5 feet and gains a +2 circumstance bonus to AC against reactions triggered by this movement. They must end this movement in a space that's not adjacent to any enemy."
 
```

```encounter-table
name: Kobold Cavern Mage
creatures:
  - 1: Kobold Cavern Mage
```



Kobold cavern mages are born more than trained, hatching from eggs that absorbed particularly large amounts of primal earth energy. Although there are many elementals and even natural terrain features that can give rise to cavern mages, most are related to the cavern-dwelling earth nymphs known as lampads. These lonely and capricious fey are as enthusiastic to receive the company of a kobold tribe as the kobolds are for the protection they receive in return.

* * *

Kobolds are small reptilian humanoids. They lurk in dark spaces, usually tunnels and mines beneath the earth, in either warrens of their own design or complexes discovered and colonized after the original builders have moved on. Though kobolds are far more pragmatic than courageous, they use every inch of their cunning to even the playing field between themselves and other, stronger creatures. They attack from the darkness and at range, and kobold artificers and engineers master the art of simple but effective traps, which they use to protect their lairs. Kobolds are skilled at working together by necessity, and they often set up ambushes or hit-and-run assaults that allow them to do the most damage possible without being harmed in return.

Kobolds are diligent and hardworking creatures. While some kobolds live in communal collectives that maintain neutral relations with the creatures around them, they can be easily swayed into serving malevolent powers or megalomaniacal leaders. This is in part due to kobolds' innate pragmatism, as they would rather concede to servitude than risk being killed, but it is also in part due to a reverence for the power they generally lack. Notably, kobold eggs left in the proximity of magical creatures or places tend to absorb similar traits from the exposure. The resulting physical changes mark the appearance of each tribe, but a few lucky kobolds are also born with magical power that reflects their tribe's patron.
