---
title: "Tyrafdir"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dJjXpLDOfeH4kqG1" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Tyrafdir"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Tyrafdir"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[fey]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23, Deception: +21, Survival: +22"
abilityMods: [6, 4, 6, -3, 3, -1]
speed: 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 30
armorclass:
  - name: AC
    desc: "30 all-around vision; __Fort__ +24, __Ref__ +21, __Will__ +18"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190, hydra regeneration; __Immunities__  mental; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Actor.FUnnTzkARhfNi5cP.Item.TowRcjxa5ZN7kGUP|Hydra Regeneration]]"
    desc: "  On a failure the tyrafdir grows two illusory heads.\n\nThe hydra has regeneration equal to 3 × the number of heads it has. If a hydra's body is missing any heads and the remaining stumps have not been cauterized, the hydra attempts a DC 31 Fortitude check save after it regains Hit Points from regeneration. On a success, one uncauterized stump regrows two heads; on a critical success, two uncauterized stumps regrow into two heads each. The hydra can never grow more than double the number of heads it ordinarily has. The hydra's regeneration only fully deactivates if all its heads are severed and all stumps are cauterized, at which point it dies.\n* * *\n\nThis monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Deceptive Heads"
    desc: " (illusion) A tyrafdir is cunning, if unintelligent, using illusions of regrown heads to confuse and harry opponents. When a tyrafdir fails, but does not critically fail, its Fortitude save to regrow a head, a phantasm materializes to mimic the regrowth. This creates two deceptive heads that function differently than real heads. The tyrafdir gains a deceptive jaws Strike as long as it has at least one deceptive head. Any creature that attacks a deceptive head or uses the [[Actions/Seek|Seek]] action to examine it can attempt to disbelieve the illusion (DC 27 Will check save).\n\n[[Bestiary Effects/Effect_ Deceptive Heads|Effect: Deceptive Heads]]"

  - name: "Deceptive Regrowth"
    desc: "  A tyrafdir ordinarily has six heads. A creature can attempt to sever one of the tyrafdir's heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that is not completely severed returns to full Hit Points at the end of any creature's turn. A tyrafdir can regrow a severed head using Hydra Regeneration. A creature can prevent this regrowth by dealing fire damage to the stump, cauterizing it. Single-target fire effects need to be targeted at a specific stump, but effects that deal splash damage or affect areas covering the hydra's whole space cauterize all stumps if they deal fire damage. If the attack that severs a head deals any fire damage or is dealt by a cold-iron weapon, the stump is cauterized instantly. If all six heads are cauterized, the hydra dies.\n\n[[Bestiary Effects/Effect_ Hydra Heads|Effect: Hydra Heads]]"

  - name: "[[Actor.FUnnTzkARhfNi5cP.Item.PjV6SBjIY1Ge7WUB|Reactive Heads]]"
    desc: "  A hydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the hydra must use a different head for each Reactive Strike it makes. Whenever one of the hydra's heads is severed, the hydra loses 1 of its extra reactions per round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Tyrafdir Heads"
    desc: "  **HP** (head) 30, deceptive regrowth\n\n**Immunities** area damage\n\n**Weakness** cold iron 10, slashing 10"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (reach 15 feet)\n__Damage__  2d10 + 9 piercing"

  - name: "Noxious Exhalation"
    desc: "`pf2:2`  The tyrafdir breathes out a noxious mist from all of its mouths, spreading in a 20-foot emanation that deals 4d10 poison damage to creatures within the area (DC 24 Reflex check save). Any creature that fails its save must attempt a DC 24 Will check save or gain weakness to mental 10 and a –1 status penalty to Will saves for 24 hours. The tyrafdir can't use Noxious Exhalation again for 1d4 rounds.\n\n[[Bestiary Effects/Effect_ Noxious Exhalation|Effect: Noxious Exhalation]]"
 
```

```encounter-table
name: Tyrafdir
creatures:
  - 1: Tyrafdir
```




