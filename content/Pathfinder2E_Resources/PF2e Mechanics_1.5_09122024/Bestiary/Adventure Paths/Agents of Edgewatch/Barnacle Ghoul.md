---
title: "Barnacle Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2PQGXlSJDdV3qE3d" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Barnacle Ghoul"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Barnacle Ghoul"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ghoul]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Necril, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +19"
abilityMods: [6, 6, 3, 1, 4, 4]
speed: 25 feet,  climb 10 feet,  swim 40 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +16, __Ref__ +21, __Will__ +17"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Tear Flesh"
    desc: "`pf2:r`  **Trigger** A creature grabbed by the barnacle ghoul critically fails a skill check to Escape\n* * *\n\n**Effect** The barnacle ghoul makes a claw Strike against the triggering creature."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (finesse)\n__Damage__  2d10 + 10 piercing plus fill-lungs,paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, finesse)\n__Damage__  2d6 + 10 slashing plus grab,paralysis"

  - name: "**Ranged** `pf2:1` [Two Actions] Water Jet"
    desc: "+21 (range increment 10 feet)\n__Damage__  2d6 + 10 acid plus fill-lungs"

  - name: "Consume Flesh"
    desc: "`pf2:1` (manipulate) **Requirements** The barnacle ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The barnacle ghoul devours a chunk of the corpse and regains 5d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "Fill Lungs"
    desc: " (curse) **Saving Throw** DC 26 Fortitude check\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** [[Conditions/Sickened|Sickened 2]] (1 round)\n\n**Stage 3** [[Conditions/Sickened|Sickened 3]] (1 round)\n\n**Stage 4** drowning and cannot reduce below stage 4 until the water is purged; purging the water requires a successful DC 26 Medicine check check to [[Actions/Administer First Aid|Administer First Aid]] (which stops the creature from drowning and returns the creature to stage 3; stage 2 on a critical success) or a magical effect that removes curses or the sickened condition (which stops the creature from drowning and ends the curse).\n\nIf the creature dies from drowning, it rises as a barnacle ghoul the next midnight."

  - name: "Nimble Swim"
    desc: "`pf2:1` (move) The barnacle ghoul Swims up to 20 feet. This movement doesn't trigger reactions."

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 26 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]].\n\nIt can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Barnacle Ghoul
creatures:
  - 1: Barnacle Ghoul
```




