---
title: "Mocking Chorus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CQl8ssRD0mYkN50p" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Mocking Chorus"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Mocking Chorus"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Scent (Imprecise) 60 Feet"
languages: "all (see uncanny mimicry)"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Deception: +36, Performance: +35"
abilityMods: [9, 4, 6, -2, 2, 4]
speed: 35 feet,  swim 35 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 41
armorclass:
  - name: AC
    desc: "41 all-around vision; __Fort__ +33, __Ref__ +30, __Will__ +30"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340, hydra regeneration; __Immunities__  auditory,  sonic"
abilities_top:
  - name: ""

  - name: "Uncanny Mimicry"
    desc: "  While unable to communicate for prolonged periods, a mocking chorus can precisely imitate a humanoid voice. If a creature speaks within audible range of the mocking chorus, the mocking chorus can speak using the creature's voice, even if it says different words than what were spoken. Creatures that hear the mocking chorus speak this way can attempt a DC 40 Will check save to recognize the source. On a success, creatures gain a +1 circumstance bonus to all saving throws against the mocking chorus' abilities for 1 minute."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Actor.FUnnTzkARhfNi5cP.Item.TowRcjxa5ZN7kGUP|Hydra Regeneration]]"
    desc: "  The hydra has regeneration equal to 3 × the number of heads it has. If a hydra's body is missing any heads and the remaining stumps have not been cauterized, the hydra attempts a DC 43 Fortitude check save after it regains Hit Points from regeneration. On a success, one uncauterized stump regrows two heads; on a critical success, two uncauterized stumps regrow into two heads each. The hydra can never grow more than double the number of heads it ordinarily has. The hydra's regeneration only fully deactivates if all its heads are severed and all stumps are cauterized, at which point it dies."

  - name: "[[Actor.FUnnTzkARhfNi5cP.Item.tHcAM0IJtyMBlTXA|Head Regrowth]]"
    desc: "  A mocking chorus ordinarily has ten heads. A creature can attempt to sever one of the hydra's heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that is not completely severed returns to full Hit Points at the end of any creature's turn. A hydra can regrow a severed head using hydra regeneration. A creature can prevent this regrowth by dealing acid or fire damage to the stump, cauterizing it. Single-target acid or fire effects need to be targeted at a specific stump, but effects that deal splash damage or affect areas covering the hydra's whole space cauterize all stumps if they deal acid or fire damage. If the attack that severs a head deals any acid or fire damage, the stump is cauterized instantly. If all ten heads are cauterized, the hydra dies.\n\n[[Bestiary Effects/Effect_ Hydra Heads|Effect: Hydra Heads]]"

  - name: "Mocking Chorus Head"
    desc: "  **HP** (head) 35, head regrowth\n\n**Immunities** area damage\n\n**Weakness** slashing 10"

  - name: "[[Actor.FUnnTzkARhfNi5cP.Item.PjV6SBjIY1Ge7WUB|Reactive Heads]]"
    desc: "  A hydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the hydra must use a different head for each Reactive Strike it makes. Whenever one of the hydra's heads is severed, the hydra loses 1 of its extra reactions per round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (reach 15 feet)\n__Damage__  4d12 + 14 piercing"

  - name: "**Ranged** `pf2:1` Harsh Language"
    desc: "+35 (auditory, range increment 90 feet)\n__Damage__  4d10 + 14 sonic"

  - name: "Petty Whispers"
    desc: "`pf2:1` (auditory,mental) The mocking chorus adopts the voices of its enemies, spreading lies and jeers among would-be allies and tearing apart trusted friends. Creatures in a 60-foot emanation of the mocking chorus must attempt a DC 37 Will check save. The mocking chorus can't use petty whispers again for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune for 1 day.\n\n**Success** As failure, but the creature takes half damage and is not [[Conditions/Confused|Confused]].\n\n**Failure** The creature takes 12d10 mental damage and is confused for 1 minute. It can attempt a new save at the end of each of its turns to end the confusion.\n\n**Critical Failure** The creature takes 15d10 mental damage and is confused for 1 minute, with no save to end early."
 
```

```encounter-table
name: Mocking Chorus
creatures:
  - 1: Mocking Chorus
```




