---
title: "Akuzhail"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.42WhoW6QeOZ10VCG" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/mutant
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Akuzhail"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Akuzhail"
level: "Creature 10"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[mutant]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Chthonian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +21"
abilityMods: [7, 3, 5, -3, 5, 0]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +17, __Will__ +19"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Resistances__ acid 10, poison 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Life Bloom"
    desc: " (death,primal) When Akuzhail dies, its body explodes in a riot of seething vegetation and raw life. All living creatures within a 60-foot radius are restored 12d6 Hit Points from this energy. A fully grown bloom of Lamashtu emerges from the carcass, but it can take no actions on this round. Next round, this bloom of Lamashtu enters combat at the same point in the turn during which Akuzhail perished on the previous round, but the bloom is [[Conditions/Slowed|Slowed 1]]. At the end of the bloom's turn, it attempts a DC 11 Flat check; on a success it loses the slowed 1 condition at the start of its next turn."

  - name: "Of Three Minds"
    desc: "`pf2:r`  **Trigger** Akuzhail fails or critically fails a Will save\n* * *\n\n**Effect** Akuzhail rerolls the Will save with a -4 penalty. If it fails this second save, it may make a third attempt but with a -8 penalty. It cannot make a third attempt if its second attempt was a critical failure."

  - name: "Three Headed"
    desc: "  Any ability that would sever a chimera's head (such as a critical hit with a _[[Equipment/Vorpal|Vorpal Weapon]]_) severs one head at random. Losing a head doesn't kill a chimera (as long as it has one head left), but it does prevent it from making Strikes with the lost head or using the head's Breath Weapon."

  - name: "Triple Opportunity"
    desc: "  A chimera gains 2 extra reactions each round that it can use only to make Attacks of Opportunity. It must use a different head for each reaction, and it can't use more than one on the same triggering action. If it loses one of its heads, it also loses one of these extra reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vulture Beak"
    desc: "+23 ()\n__Damage__  2d8 + 11 slashing 1d8 bleed"

  - name: "**Melee** `pf2:1` Snake Fangs"
    desc: "+23 ()\n__Damage__  2d12 + 11 piercing plus bloom-venom"

  - name: "**Melee** `pf2:1` Centipede Mandibles"
    desc: "+23 ()\n__Damage__  2d6 acid 2d6 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile)\n__Damage__  2d8 + 11 slashing"

  - name: "Bloom Venom"
    desc: " (poison,primal) **Saving Throw** DC 29 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison and [[Conditions/Enfeebled|Enfeebled 1]]\n\n**Stage 2** 2d6 poison and [[Conditions/Enfeebled|Enfeebled 2]]\n\n**Stage 3** 2d10 poison, enfeebled 2, and exposure to Lamashtu's bloom."

  - name: "Breath Weapon"
    desc: "`pf2:2` (primal) Akuzhail breathes a 60-foot line of venom from its snake mouth that deals 11d6 poison damage (DC 29 Fortitude check). Akuzhail can't use Breath Weapon for 1d4 rounds."

  - name: "Frightening Rattle"
    desc: "`pf2:1` (emotion,fear,mental,primal,sonic) Akuzhail shakes the rattle at the end of its tail to distract and frighten its enemies. Any creature within 30 feet must succeed at a DC 29 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure). On a critical success, a creature is temporarily immune to Akuzhail's Frightening Rattle for 24 hours."

  - name: "Lamashtu's Bloom"
    desc: " (curse,disease,magical) While some NPCs become afflicted by Lamashtu's bloom curse during Parts 1 and 2 of this chapter, during Part 3 the PCs may be exposed to it as well. While the bloom is itself a curse, it functions mechanically more like a disease, and as such features both of these affliction traits. As long as the curse persists, a creature cannot recover from the disease, and removing the curse does not automatically remove the disease element of the affliction. Both elements must be dealt with individually before a victim suffering from Lamashtu's Bloom is safe. As with all elements of this curse, slaying the bloom of Lamashtu in area **C10** automatically removes this affliction.\n* * *\n\n**Saving Throw** DC 23 Fortitude check\n\n**Onset** 1 week\n\n**Stage 1** no ill effects (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** enfeebled 1 and 2d6 poison damage (8 hours)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] and 4d6 poison damage (10 minutes)\n\n**Stage 5** death; Special a creature that dies from Lamashtu's bloom explodes in a blast of First World foliage, releasing a monster. This creature is typically a low-intelligence beast or dragon between 7th and 9th level, depending on the GM's whim."

  - name: "Three-Headed Strike"
    desc: "`pf2:2`  Akuzhail makes a Strike with its vulture beak, snake fangs, and centipede mandibles, each at a -2 penalty and targeting a different creature. These Strikes count as only one attack for its multiple attack penalty, and the penalty doesn't increase until it has made all three attacks."
 
```

```encounter-table
name: Akuzhail
creatures:
  - 1: Akuzhail
```


Variant chimera


