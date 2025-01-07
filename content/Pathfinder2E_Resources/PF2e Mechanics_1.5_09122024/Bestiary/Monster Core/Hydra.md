---
title: "Hydra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bnYGKBZPd7lW98iG" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Hydra"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hydra"
level: "Creature 6"

alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17, Stealth: +12"
abilityMods: [7, 4, 5, -3, 2, -1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23 all-around vision; __Fort__ +15, __Ref__ +12, __Will__ +10"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, hydra regeneration"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Regeneration|Hydra Regeneration]]"
    desc: "  The hydra has regeneration equal to 3 x the number of heads it has. If a hydra's body is missing any heads and the remaining stumps have not been cauterized, the hydra attempts a DC 25 Fortitude check save after it regains Hit Points from regeneration. On a success, one uncauterized stump regrows two heads; on a critical success, two uncauterized stumps regrow into two heads each. The hydra can never grow more than double the number of heads it ordinarily has. The hydra's regeneration only fully deactivates if all its heads are severed and all stumps are cauterized, at which point it dies.\n* * *\n\nThis monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Head Regrowth"
    desc: "  A hydra ordinarily has five heads. A creature can attempt to sever one of the hydra's heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that is not completely severed returns to full Hit Points at the end of any creature's turn.\n\nA hydra can regrow a severed head using hydra regeneration. A creature can prevent this regrowth by dealing acid or fire damage to the stump, cauterizing it. Single-target acid or fire effects need to be targeted at a specific stump, but effects that deal splash damage or affect areas covering the hydra's whole space cauterize all stumps if they deal acid or fire damage. If the attack that severs a head deals any acid or fire damage, the stump is cauterized instantly. If all five heads are cauterized, the hydra dies.\n* * *\n\n**Hydra Head**\n\n*   **Hit Points** 15\n*   **Immunities** Area Damage\n*   **Weaknesses** Slashing 5\n\n[[Bestiary Effects/Effect_ Hydra Heads|Effect: Hydra Heads]]"

  - name: "Reactive Heads"
    desc: "  A hydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the hydra must use a different head for each Reactive Strike it makes. Whenever one of the hydra's heads is severed, the hydra loses 1 of its extra reactions per round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (See Reactive Heads)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+16 (reach 10 feet)\n__Damage__  2d6 + 7 piercing"

  - name: "Focused Assault"
    desc: "`pf2:2`  The hydra attacks a single target with its heads, overwhelming its foe with multiple attacks and leaving almost nowhere to dodge. The hydra Strikes with its fangs. On a successful attack, the hydra deals damage from its fangs Strike to the target, plus an additional 1d6 damage for every head it has beyond the first. On a failure (but not a critical failure), the hydra deals the damage from one fangs Strike to the target creature. This Strike counts as a number of attacks equal to the number of heads the hydra has toward the hydra's multiple attack penalty."

  - name: "Storm of Jaws"
    desc: "`pf2:2`  The hydra makes a number of Strikes up to its number of heads, each against a different target. These attacks count toward the hydra's multiple attack penalty, but the multiple attack penalty doesn't increase until after the hydra makes all its attacks."
 
```

```encounter-table
name: Hydra
creatures:
  - 1: Hydra
```



Hydras are multiheaded, foul-tempered serpentine beasts with voracious appetites, widely feared for their regeneration abilities.
