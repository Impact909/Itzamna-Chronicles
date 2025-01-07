---
title: "Saltborn Stalkers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fgKkAupasdXwuHne" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/troop
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Saltborn Stalkers"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Saltborn Stalkers"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[troop]]
trait_04: [[water]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Intimidation: +22, Nature: +22, Stealth: +26, Plane of Water Lore: +22, Warfare Lore: +22"
abilityMods: [6, 7, 5, 3, 5, 3]
speed: 10 feet,  swim 60 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +22, __Ref__ +26, __Will__ +20"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, troop defenses; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ area damage 15, splash damage 8"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 160 (12 squares), 80 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Lightlure"
    desc: "`pf2:1` (concentrate,incapacitation,mental,primal,visual) **Effect** The saltborn stalkers move their luminescent lures in an entrancing light show, drawing nearby creatures into their grasp. Each creature in a 100-foot emanation must attempt a DC 33 Will check save; regardless of the result of its save, the creature is then temporarily immune to Lightlure for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] with the lures and must spend all its actions on its next turn to move closer to them as expediently as possible, avoiding obvious dangers along its path.\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Dazzled|Dazzled]] for 1d4 rounds."

  - name: "Saline Crust"
    desc: " (aura,water) 20 feet\n* * *\n\n**Requirements** The saltborn stalkers are in a body of water\n* * *\n\n**Effect** Layers of the saltborn's salty skin flake off to foul the water around them. A creature that ends its turn in the aura takes 2d6 acid damage with a DC 30 Reflex check save; creatures with the amphibious or aquatic trait are immune."

  - name: "Salty Clutch"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The stalkers reach out to Grab their foes and drag them underwater. Each enemy in a 5-foot emanation must succeed at a DC 33 Reflex check save or be [[Conditions/Grabbed|Grabbed]] by the stalkers (or [[Conditions/Restrained|Restrained]] on a critical success). For the rest of the current turn, the saltborn stalkers can move toward water or in water without ending the grab, carrying any grabbed or restrained creatures along with them."

  - name: "Scour the Bones"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The saltborn stalkers use their teeth and claws to vivisect each enemy within 5 feet (DC 30 Reflex check save). The damage depends on the number of actions.\n\n`pf2:1` 2d10 slashing damage\n\n`pf2:2` 3d10+8 slashing damage\n\n`pf2:3` 3d10+16 slashing damage"

  - name: "Troop Movement"
    desc: "  Whenever the saltborn stalkers Stride or Swim, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then move. This works just like a Gargantuan creature moving; for instance, if any of the stalkers' squares enter difficult terrain, the extra movement cost applies to the whole troop."
 
```

```encounter-table
name: Saltborn Stalkers
creatures:
  - 1: Saltborn Stalkers
```



The briny depths of the Boundless Sea sometimes twist large groups of merfolk into swarms with vicious rows of teeth and sharp claws known as saltborn stalkers. Saltborn stalkers hunt in groups, using their drooping, tentacle-like appendages as bioluminescent lures, posing them as wisps or bubbles of planar energy to draw unsuspecting prey into clever ambushes.

* * *

THE RITE OF SALT AND STONE

When a merfolk joins the ranks of the saltborn, they undergo a secret rite known only to other saltborn and the brine dragons of Kelizandrika. The recruits are encased in graves of salt and ice and left at the floor of the Boundless Sea to claw themselves free. Those who overcome the trial are never truly rid of the salt from their tombs, which covers the body of every saltborn stalker.
