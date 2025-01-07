---
title: "Skinskitter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lS0ZyS1LXubmIJls" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Skinskitter"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Impossible Lands"
name: "Skinskitter"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[amphibious]]
trait_03: [[chaotic]]
trait_04: [[mindless]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +5, Stealth: +7"
abilityMods: [2, 4, 1, -5, 0, -5]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Lost Omens: Impossible Lands_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +6, __Ref__ +9, __Will__ +5"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  mental; __Weaknesses__ cold iron 2"
abilities_top:
  - name: ""

  - name: "A Taste for Skin"
    desc: "  A skinskitter tastes skin (including leather), hair, claws, and nails within 60 feet."

abilities_mid:
  - name: ""
  - name: "Shuddering Skitter"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The skinskitter is reduced to 0 HP\n* * *\n\n**Effect** The fear of death agitates the skinskitter, precipitating a sudden existential awakening of consciousness. The skinskitter is reduced to 1 HP, loses the mindless trait and immunity to mental effects for the next 24 hours, gains the ability to speak one language (typically Osiriani or Vudrani), and takes two of the following actions in any order: Hide, [[Actions/Sneak|Sneak]], Step, Stride, or [[Actions/Take Cover|Take Cover]]. In addition, the square occupied by the skinskitter before using Shuddering Skitter becomes difficult terrain, as they disgorge a shower of half-digested calluses, chewed nails, and entangled hair in their skittering wake."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Nail"
    desc: "+9 (finesse)\n__Damage__  1d8 + 1 piercing plus grab"

  - name: "Share the Skin"
    desc: "`pf2:1`  **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the skinskitter's reach\n* * *\n\n**Effect** The skinskitter scrapes and shears away large sheets of the victim's skin. This requires an Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions. The massive pain causes the victim to become [[Conditions/Clumsy|Clumsy 1]] for 1 minute, and the skinskitter drapes itself in the flapping skin, granting it 10 temporary Hit Points for 1 minute."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Skinskitter
creatures:
  - 1: Skinskitter
```



These elusive oddments resemble discarded hides of butchered animals and fleshwarping experiments, floating like so much meaty detritus in the bloody filth of Ecanus's charnel-clogged sewers. Skinskitters, named for their fluid, erratic movements, scavenge the city for leavings of fleshy waste. They prefer discreet, non-violent ways of procuring these biological materials and shy from combat, seemingly possessed of a nervous temperament. Nexian fleshforgers quip this is entirely reasonable, as skinskitters are little more than nervous systems wrapped in dying skin. Nexian guards who actually have to hunt these fleshforged pests aren't quite as jocular; confronted by the oddly childlike pleas of these cornered puddles of flesh, hair, and eyes, many recruits simply choose to leave the city watch.

On occasion, curious scholars or soldiers have questioned why skinskitters pursue organic tissue, and whether this is a simple instinct or in pursuit of a grander purpose. Most fleshforgers assume that skinskitters consume organic matter to repair themselves in a process similar to eating, and give the matter no further thought, showing no more interest in the creatures than a smith might show in a bead of melted slag. The most paranoid Nexians claim that skinskitters are attempting to build something out of their collections of cast-off skin, perhaps even reconstructing themselves into fleshforged conformers. There is no recorded evidence of this ever occurring, however—if the creatures have any awareness at all, it's more likely that skinskitters are driven by the basest of instincts to better themselves through the same methods used in their creation but lack the understanding and self-direction to ever succeed.
