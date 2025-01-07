---
title: "Soul Eater"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.eZfeRUxIJUNG6EHd" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Soul Eater"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Soul Eater"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Greater Darkvision"
languages: "Daemonic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Intimidation: +15, Stealth: +17, Abaddon Lore: +12"
abilityMods: [0, 6, 4, -1, 4, 4]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +19, __Will__ +15"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  critical hits,  disease,  paralyzed,  poison,  precision,  sleep; __Weaknesses__ holy 10; __Resistances__ physical 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Caster Link"
    desc: " (detection,divine) A conjured soul eater forms a mental link with its conjurer. While both are on the same plane, the soul eater knows the location of its conjurer per its find target ability. If the soul eater's target dies before the soul eater can drain its soul, or if the soul eater is defeated (but not destroyed) by the target, the soul eater returns to its conjurer and tries to kill them."

  - name: "Find Target"
    desc: " (detection,divine) When a soul eater is conjured to the Material Plane to find a specific creature, it gains the benefits of a 5th-rank [[Spells/Locate|Locate]] spell that isn't blocked by lead or running water. The conjurer must have seen the target and must speak the target's name while conjuring the soul eater in order to grant this ability."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile, finesse, unholy)\n__Damage__  2d6 + 3 slashing plus mind-numbing-touch 2d6 void plus mind-numbing-touch"

  - name: "Drain Soul"
    desc: "`pf2:3` (death,divine,manipulate) **Requirements** The soul eater is adjacent to a [[Conditions/Dying|Dying]] creature\n* * *\n\n**Effect** The soul eater attempts to devour the dying creature's soul. The creature must attempt a DC 25 Will check save. A creature that dies as a result of Drain Soul can't be restored to life except by a spell or ritual of 8th rank or higher. If the soul eater that used Drain Soul on a creature is slain within 100 feet of that creature's corpse and the creature has been dead no longer than 1 minute, the creature's soul returns to its body and is restored to life, leaving the creature [[Conditions/Unconscious|Unconscious]] and dying 1 but no longer [[Conditions/Doomed|Doomed]].\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Doomed|Doomed 1]], or increases its doomed value by 1 if it was already doomed.\n\n**Failure** As success, but [[Conditions/Doomed|Doomed 2]].\n\n**Critical Failure** As success, but [[Conditions/Doomed|Doomed 3]]."

  - name: "Mind-Numbing Touch"
    desc: " (curse,divine) When a soul eater hits a creature with its claw Strike, the creature must succeed at a DC 23 Fortitude check save or become [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Stupefied|Stupefied 2]] on a critical failure).\n\nFurther damage dealt by the soul eater increases the stupefied value by 1 on a failed save, to a maximum of stupefied 4. This condition value decreases by 1 each time the creature gets a full night's rest. As long as the creature is stupefied by a soul eater, rest does not decrease any [[Conditions/Doomed|Doomed]] value that creature might have."
 
```

```encounter-table
name: Soul Eater
creatures:
  - 1: Soul Eater
```



Only the most desperate or foolhardy conjurers call upon the aid of these strange fiends from the inky swamps of Abaddon.
