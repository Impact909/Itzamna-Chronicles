---
title: "Sun Warrior Brigade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Q7yKZL6zPCbnI1ZE" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Sun Warrior Brigade"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Sun Warrior Brigade"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
trait_04: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; "
languages: "Common, Mzunu"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +22, Religion: +23"
abilityMods: [7, 2, 6, 2, 5, 4]
speed: 25 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +18, __Will__ +23"
hp: 216
health:
  - name: ""
  - name: HP
    desc: "216, 16 squares (144 &#x3D; 12 squares, 72 &#x3D; 8 squares); __Weaknesses__ area damage 15, splash damage 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Divine Spontaneous Spells"
    desc: "DC 29, attack +21; __6th __ (3 slots) _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_, _[[Spells/Wall of Fire|Wall of Fire]]_; __5th __ (4 slots) _[[Spells/Breathe Fire|Burning Hands]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Flame Strike|Flame Strike]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Divine Lance|Divine Lance]]_"

  - name: "Frenetic Assault"
    desc: "`pf2:1`  `pf2:1` to `pf2:3` actions\n\n**Frequency** once per round\n* * *\n\n**Effect** The members of the brigade wildly swing their weapons-primarily spears-in a frenzied attack at each enemy adjacent to the troop (DC 29 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d12+1 piercing damage\n\n`pf2:2` 2d12+11 piercing damage\n\n`pf2:3` 3d12+11 piercing damage"

  - name: "Troop Movement"
    desc: "  Whenever the troop Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Troop Spellcasting"
    desc: "  When the sun warrior brigade Casts a Spell, its constituent members combine their efforts into casting a more powerful version of the spell than any one member could achieve alone. When Casting a Spell that has an area of a burst, cone, or line and doesn't have a duration, increase the area of that spell. Add 5 feet to the radius of a burst that normally has a radius of at least 10 feet (a burst with a smaller radius is not affected). Add 5 feet to the length of a cone or line that is normally 15 feet long or smaller, and add 10 feet to the length of a larger cone or line."

  - name: "Walkena's Radiance"
    desc: "`pf2:2` (divine,fire,light) The brigade calls upon Walkena to burn and blind their foes. The sun warriors present their religious symbols and create a white-hot flash of light in a 45-foot cone. Creatures in the cone take 10d8 fire damage (DC 29 Fortitude check save). Creatures that fail their save become [[Conditions/Dazzled|Dazzled]] for 1 round. Creatures that critically fail become [[Conditions/Blinded|Blinded]] for 1 round instead. When the troop is reduced to 8 or fewer squares, this area decreases to a 20-foot cone."
 
```

```encounter-table
name: Sun Warrior Brigade
creatures:
  - 1: Sun Warrior Brigade
```




