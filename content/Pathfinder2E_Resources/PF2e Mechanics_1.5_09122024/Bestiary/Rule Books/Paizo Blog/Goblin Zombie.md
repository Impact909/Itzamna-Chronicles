---
title: "Goblin Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5APpCC9bVpv7M9d3" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Goblin Zombie"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog"
name: "Goblin Zombie"
level: "Creature 1"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 0
perception:
  - name: "Perception"
    desc: "+0; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +3, Athletics: +4"
abilityMods: [3, 2, 0, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Blog_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +5, __Ref__ +3, __Will__ +3"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Alchemical Rupture"
    desc: "  When the goblin zombie is reduced to 0 Hit Points, an alchemical device jammed in its belly ruptures. Roll 1d4 and consult the following for the effect:\n\n  \n\n| 1d4 | Alchemical Effect |\n| --- | --- |\n| 1 | creatures in a 5-foot emanation take 1d3 persistent acid damage |\n| 2 | creatures in a 5-foot emanation take 1d4 fire damage (DC 16 Reflex check save) |\n| 3 | creatures in a 5-foot emanation take 1d4 poison damage (DC 16 Fortitude check save) |\n| 4 | smoke billows out in a 5-foot emanation for 1 round (creatures in that area are [[Conditions/Concealed\\|Concealed]], and all other creatures are concealed to them) |"

  - name: "Slow"
    desc: "  A goblin zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 ()\n__Damage__  1d6 + 3 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 ()\n__Damage__  1d8 + 3 piercing"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Goblin Zombie
creatures:
  - 1: Goblin Zombie
```




