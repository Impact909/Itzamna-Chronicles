---
title: "Leshy Mob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GcWRXtJz2p1rNxoz" 
tags:
  - pf2e/creature/type/leshy
  - pf2e/creature/type/plant
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Leshy Mob"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Leshy Mob"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[leshy]]
trait_02: [[plant]]
trait_03: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Low-Light Vision"
languages: "Common, Fey; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +22, Nature: +22, Stealth: +19"
abilityMods: [5, 4, 7, 3, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +23, __Ref__ +19, __Will__ +21"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195, Thresholds 130 (12 squares), 65 (8 squares); __Weaknesses__ area damage 12, fire 8, splash damage 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 130 (12 squares), 65 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

  - name: "Verdant Burst"
    desc: " (healing,primal,vitality) When a leshy mob's Hit Points reach a threshold that would reduce its size, a burst of primal energy explodes from the fallen leshies and empowers the surviving fighters. The leshy mob gains 4d8 temporary Hit Points that last for 10 minutes. In addition, all squares within 5 feet of the troop become filled with various plants, becoming difficult terrain. If the environment is not a viable environment for these plants, they wither after 24 hours."

attacks:
  - name: ""

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22; __5th __  _[[Spells/Wall of Thorns|Wall of Thorns]]_\n__Constant__  __(3rd)__ _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The leshies can transform into an assortment of Small plants that fills a 15-foot burst centered on any one square the leshy mob occupies, creating difficult terrain. When the leshies return to their natural form, they Form Up anywhere within the burst. This otherwise uses the effects of [[Spells/One with Plants|One with Plants]].\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "One with the Foliage"
    desc: "  The leshy mob ignores difficult terrain caused by plants and fungi, and it treats greater difficult terrain from such sources as difficult terrain."

  - name: "Rain of Seeds"
    desc: "`pf2:2`  The leshies grab and hurl an assortment of stones, spores, and explosive seeds, launching a ranged attack in the form of a volley. This volley is a 10-foot burst within 60 feet that deals 4d8 bludgeoning or 4d8 poison damage (DC 30 Reflex check save).\n\nWhen the leshies are reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Troop Movement"
    desc: "  Whenever the leshy mob Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to their Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters difficult terrain, the extra movement cost applies to the whole troop."

  - name: "Veggielante Justice"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The leshies assault each enemy creature within 5 feet, with a DC 30 Reflex check save. The damage depends on the number of actions.\n\n`pf2:1` 3d8 bludgeoning or 3d8 slashing damage\n\n`pf2:2` 3d8+11 bludgeoning or 3d8+11 slashing damage\n\n`pf2:3` 3d8+16 bludgeoning or 3d8+16 slashing damage"
 
```

```encounter-table
name: Leshy Mob
creatures:
  - 1: Leshy Mob
```



A single leshy is a nuisance. A horde of leshies is a natural disaster. When confronted by existential threats or malicious ecological devastation, charismatic leshy leaders can rally their kin into a mob. These bands often include several kinds of leshy, creating a ragtag host that can communicate with and draw power from nearly any plant in its path. The farther they travel, the greater the mob's sense of cohesion becomes, gradually awakening an empathic hive mind, coordinated shapeshifting, and communal spellcasting far beyond what any individual could accomplish.

Leshy mobs rarely outlast whatever rallied them in the first place. After pillaging a lumber camp or liberating a greenhouse's contents, the leshies gradually shake off their mob mentality—often with some shock or sheepishness at recognizing whatever crimes they just committed. Though the leshies scatter, they often retain a faint sense of camaraderie with their old comrades, making it easier for them to gather again to confront future threats.

* * *

For all their cute appearances and harmless pretenses, leshies can become a formidable force when riled. What's more, leshies can grow larger, stronger, and more aggressive in regions rich in primal energy. The following presents several higher-level leshy threats that grow in primordial forests.
