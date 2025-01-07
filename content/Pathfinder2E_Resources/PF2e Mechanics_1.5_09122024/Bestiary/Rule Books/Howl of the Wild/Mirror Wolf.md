---
title: "Mirror Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Qmj6xgeykMeoILrj" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Mirror Wolf"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Mirror Wolf"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +12, Intimidation: +11, Stealth: +19, Survival: +17"
abilityMods: [3, 6, 2, 1, 3, -2]
speed: 35 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +19, __Will__ +15"
hp: 117
health:
  - name: ""
  - name: HP
    desc: "117; __Immunities__  disease,  paralyzed,  poison,  precision; __Resistances__ all damage 7 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Visage Strike"
    desc: "`pf2:r`  **Trigger** A creature adjacent to the mirror wolf's visages damages mirror wolf's ally\n* * *\n\n**Effect** The mirror wolf teleports to the visage's spot, destroying the visage, and makes a jaws Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (magical)\n__Damage__  2d8 + 8 force plus knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 22, attack +0; __3rd __  _[[Spells/Revealing Light|Revealing Light]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Bond with Mortal"
    desc: " (mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The spirit guide spends 10 minutes to form a bond with a mortal creature. While the bond exists, the spirit guide increases their current and maximum Hit Points by 14, gains a +2 status bonus to their attack and damage rolls, and can communicate telepathically with the bonded mortal as long as the two beings are on the same plane. The spirit guide can only be bonded with one mortal at a time, and they can take this action again to end the bond or to form a new bond (which also ends the old bond). The bond also ends if the spirit guide or the mortal dies.\n\nThis bond strengthens the spirit guide's connection to the Universe. While bonded, the spirit guide loses the incorporeal and spirit traits, loses their immunity to disease, paralysis, and poison, along with their resistance to all damage, and changes their Strikes to deal the appropriate amount of physical damage (typically piercing or slashing) instead of force damage."

  - name: "Bonded Strike"
    desc: "`pf2:2`  **Requirements** The mirror wolf is currently Bonded with a Mortal\n* * *\n\n**Effect** The mirror wolf makes a jaws Strike. If this attack hits, the bonded mortal can spend their reaction to Strike the same target."

  - name: "Lingering Assailant"
    desc: " (illusion,visual) The mirror wolf attacks with such speed it leaves a visage of itself behind. When the mirror wolf Strikes, they leave behind a visage in an adjacent square. The visage is treated as an ally for effects such as flanking and pack attack. A visage has AC 10 and 1 HP and lasts for 1 round."

  - name: "Pack Attack"
    desc: "  The mirror wolf's Strikes deal 1d8 extra damage to creatures within reach of at least two of the mirror wolf's allies."

  - name: "Strafing Strike"
    desc: "`pf2:2`  The mirror wolf makes a jaws Strike against a creature within range. The mirror wolf can then Stride and make a second jaws Strike against the same creature."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Mirror Wolf
creatures:
  - 1: Mirror Wolf
```




