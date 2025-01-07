---
title: "Sootsoldiers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AaEF48JZmBHolbps" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Sootsoldiers"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Sootsoldiers"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[elemental]]
trait_02: [[fire]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Pyric"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +21, Nature: +18, Plane of Fire Lore: +18, Warfare Lore: +18"
abilityMods: [7, 5, 6, 2, 4, 0]
speed: 40 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +21, __Will__ +18"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165, (16 squares); Thresholds 110 (12 squares), 55 (8 squares);; __Immunities__  bleed,  paralyzed,  fire,  sleep,  poison; __Weaknesses__ area damage 12, cold 12, splash damage 7"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "Ashen Smoke"
    desc: "  When the sootsoldiers are reduced by an HP Threshold or are reduced to 0 HP, the destroyed soldiers crumble to a cloud of ash-laden smoke in 20-foot burst centered on the sootsoldiers. All creatures within the cloud are [[Conditions/Concealed|Concealed]], and all creatures outside it are concealed to those inside. The smoke lasts for 1 minute or until dispersed by a strong wind."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Incinerating Grasp"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The sootsoldiers reach to constrain each enemy within 5 feet in their fiery clutches (DC 26 Reflex check save). The damage and additional effects depend on the number of actions.\n\n`pf2:1` 2d8 fire damage\n\n`pf2:2` 3d8+7 fire damage plus [[Conditions/Grabbed|Grabbed]]\n\n`pf2:3` 4d8+7 fire damage plus grabbed"

  - name: "Seething Flash"
    desc: "`pf2:1` (fire,primal) The sootsoldiers reignite and rush across the battlefield, Forming Up and Striding twice. At the end of this movement, a wave of flame and heat pours off the sootsoldiers, dealing 4d8 fire damage to other creatures in a 10-foot emanation, with a DC 29 Reflex check save. A creature that critically fails its save is also knocked [[Conditions/Prone|Prone]]."

  - name: "Smoke Vision"
    desc: "  Sootsoldiers ignore the [[Conditions/Concealed|Concealed]] condition from smoke."

  - name: "Troop Movement"
    desc: "  Whenever the sootsoldiers Stride, they first Form Up as a free action to condense into a 20-foot-by-20- foot area (minus any missing squares), then move up to their Speed. This works just like a Gargantuan creature moving; for instance, if any of the sootsoldiers' squares enters difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Sootsoldiers
creatures:
  - 1: Sootsoldiers
```



Powerful deities and warlords strive for dominance over the Plane of Fire and the rest of the Inner Sphere in order to prove fire's supremacy. Armies of flaming soldiers go to war against each other on battlefields of smoke and smoldering char, all unable to bring their full power to bear. Ymeri, the vicious and victorious Queen of the Inferno, commands legions of sootsoldiers: elementals capable of battling the armies of her foes and, even when destroyed, rising from the ashes of the Eternal Furnace, scorched and triumphant.
