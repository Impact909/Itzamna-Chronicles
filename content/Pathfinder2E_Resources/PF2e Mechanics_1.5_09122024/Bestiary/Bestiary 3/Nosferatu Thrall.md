---
title: "Nosferatu Thrall"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zQLRu7AmVQh53MxM" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Nosferatu Thrall"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Nosferatu Thrall"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +14, Deception: +15, Religion: +14"
abilityMods: [4, 3, 2, 2, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +17, __Will__ +14"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, fast healing 5; __Weaknesses__ mental 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|+1 Striking Greatclub]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 5]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu Thrall) Mindbound|Mindbound]]"
    desc: "  A nosferatu master exerts a fierce hold over their thrall's mind. If any creature other than the thrall's master targets them with an effect that would give them the [[Conditions/Controlled|Controlled]] condition, the thrall's master rolls a counteract check against it using their Dominate DC - 10 as the counteract check modifier."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu Thrall) Mortal Shield|Mortal Shield]]"
    desc: "`pf2:r`  **Trigger** The thrall's master would take damage from a Strike or spell attack and is in an adjacent square\n* * *\n\n**Effect** The thrall throws themself in front of their master, taking half the damage of the attack (before applying any weaknesses or resistances). The thrall's master takes the remaining damage, applying any weaknesses or resistances as normal."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu Thrall) Rally|Rally]]"
    desc: "`pf2:r`  **Trigger** The thrall ends their turn more than 30 feet away from their master\n* * *\n\n**Effect** The thrall Strides up to their Speed toward their master."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+19 (backswing, magical, shove)\n__Damage__  2d10 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, nonlethal)\n__Damage__  2d6 + 10 bludgeoning"

  - name: "Swing Back"
    desc: "`pf2:1`  **Frequency** once per round\n\n**Requirements** The nosferatu thrall's last action was a greatclub Strike that missed\n* * *\n\n**Effect** The nosferatu thrall makes another greatclub Strike against the same target, using the previous Strike's multiple attack penalty."
 
```

```encounter-table
name: Nosferatu Thrall
creatures:
  - 1: Nosferatu Thrall
```



Nosferatu thralls are mortals bound to a nosferatu's will. While thralls aren't undead, they stay alive through unnatural means: feeding on the blood of their masters.

* * *

Among the most ancient of vampires are the nosferatus, twisted remnants of mortals who died in great plagues of old. Perhaps because of their age, nosferatus can no longer create more of their kind. Yet they still lurk among the living, manipulating the hearts and minds of their prey to either serve them beyond the limits of natural life or to become sustenance for the nosferatu like so many others before.
