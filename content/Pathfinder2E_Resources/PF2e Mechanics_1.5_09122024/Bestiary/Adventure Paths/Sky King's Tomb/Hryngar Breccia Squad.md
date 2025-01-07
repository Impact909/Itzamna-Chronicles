---
title: "Hryngar Breccia Squad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IW5eTaGMP46qG2tP" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/hryngar
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Hryngar Breccia Squad"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Hryngar Breccia Squad"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[hryngar]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
trait_06: [[troop]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Crafting: +18, Intimidation: +16, Religion: +18, Survival: +18"
abilityMods: [6, 2, 4, 2, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +15, __Will__ +18; +2 status to all saves vs. magic"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, Thresholds 100 (12 squares), 50 (8 squares); ; __Weaknesses__ area damage 12, splash damage 6"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Steel Shield|Steel Shield]]"
  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Bolt Barrage"
    desc: "`pf2:2`  The hryngar breccia squad draws or reloads its crossbows, then launches a ranged attack in the form of a volley. This volley is a 10-foot burst within 120 feet that deals 4d8 piercing damage (DC 28 Reflex check save). When the hryngar breccia squad is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "General Melee"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The hryngar breccia squad engages in a coordinated attack with its melee weapons against each enemy within 5 feet (DC 28 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 1d8+6 bludgeoning damage\n\n`pf2:2` 2d8+10 bludgeoning damage\n\n`pf2:3` 3d8+14 bludgeoning damage"

  - name: "Raise Shields"
    desc: "`pf2:1`  The hryngar breccia squad raises steel shields, with the effects of Raise a Shield.\n* * *\n\n[[Equipment Effects/Effect_ Raise a Shield|Effect: Raise a Shield]]"

  - name: "Troop Movement"
    desc: "  Whenever the hryngar breccia squad Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the hryngar breccia squad enters difficult terrain, the extra movement cost applies to the entire hryngar breccia squad."

  - name: "Push Back"
    desc: "`pf2:1`  **Requirements** The hryngar breccia squad has its shields raised\n* * *\n\n**Effect** The hryngar breccia squad pushes against adjacent foes, knocking them back. The hryngar breccia squad attempts an Athletics check to [[Actions/Shove|Shove]], comparing the result to the Fortitude DC of each enemy within 5 feet of the hryngar breccia squad. The hryngar breccia squad is not knocked [[Conditions/Prone|Prone]] on a critical failure."
 
```

```encounter-table
name: Hryngar Breccia Squad
creatures:
  - 1: Hryngar Breccia Squad
```



A hryngar breccia squad is a group of hryngar martial combatants armed with melee weapons and steel shields. Though more likely to be encountered near large hryngar settlements, these strike forces see wide use throughout the Darklands. Hryngar breccia squads often serve as military units, mercenary companies, city patrols, and caravan guards. Like all warriors, the favored combat methods of a hryngar breccia squad change by location, often due to surrounding environment and popular equipment.

* * *

Deep under the surface of Golarion, dwarves still dwell in the darkness. Once abandoned by their kin who were obsessed with reaching the surface, these dwarves have found that by working harder than their brethren, they can build a society far greater than anything under the sun. Droskar, Master of the Dark Furnace, teaches them that toiling for their masters, who in turn toil for their masters above, will lead all of them to become stronger than ever. Every hryngar knows that their labor defines them, and brings them glory in the eyes of Droskar and their peers. Exhaustion at the end of the work day is an honor, proof of their worth in society.

## Rift Jumpers

Hryngar breccia squads that specialize in spelunking are known as Rift Jumpers, named for their reckless leaps into perilous chasms. They swap their shields and warhammers for light picks and train with their climbing equipment until it serves as an extension of their body. Rift Jumpers lose the Raise Shields, Shield Block, and Push Back actions, and gain a climb Speed of 20 feet.
