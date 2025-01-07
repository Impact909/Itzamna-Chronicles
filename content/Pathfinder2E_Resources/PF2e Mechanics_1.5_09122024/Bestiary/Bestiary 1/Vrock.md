---
title: "Vrock"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sYcFp6hmDgLLcHmz" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Vrock"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Vrock"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Intimidation: +18, Performance: +18, Religion: +18, Stealth: +18, Survival: +16"
abilityMods: [6, 3, 5, 2, 3, 3]
speed: 25 feet,  fly 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +18, __Will__ +15; +1 status to all saves vs. magic"
hp: 185
health:
  - name: ""
  - name: HP
    desc: "185; __Weaknesses__ cold iron 10, holy 10; __Resistances__ electricity 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  If the vrock is flying and a creature triggers an attack of opportunity, the vrock can make 2 Strikes with its talons against that creature instead of 1 Strike.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Peace Vulnerability"
    desc: "  A vrock's wrath is the heart of their essence, and forcing peace upon them wrenches at their soul. If they fail a save against [[Spells/Calm|Calm]] or a similar effect forcing them to be peaceful, a vrock takes 4d6 mental damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+21 (magical, reach 10 feet, unholy)\n__Damage__  3d8 + 9 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d6 + 9 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+19 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 8 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Dance of Ruin"
    desc: "`pf2:3` (divine,electricity,manipulate,move) The vrock dances in flight and chants to create a ruinous explosion of electricity. If more vrocks within 30 feet want to join the dance, the vrock can delay the dance to wait for more vrocks; in that case, the effect occurs after the last vrock uses Dance of Ruin or one of the vrocks chooses to complete that round of the dance. Each non-demon creature in a 20-foot emanation from any of the dancing vrocks takes 2d12 electricity damage (DC 28 Reflex check save). For each additional vrock that joins the dance, the damage increases by 1d12 and the save DC increases by 1 (to a maximum of four vrocks dealing 5d12 electricity damage with a DC 31 save). The vrocks can continue dancing by using Dance of Ruin each round, for up to 3 rounds in total. The emanation's size increases by 20 feet each round, and the damage increases by 1d12 per vrock each round.\n* * *\n\n*   **1 Vrock Dancing**  \n    \n    | Round | Effect |\n    | --- | --- |\n    | 1 | 20-foot emanation 2d12 electricity damage DC 28 Reflex check |\n    | 2 | 40-foot emanation 3d12 electricity damage DC 28 Reflex check |\n    | 3 | 60-foot emanation 4d12 electricity damage DC 28 Reflex check |\n    \n*   **2 Vrocks Dancing**  \n    \n    | Round | Effect |\n    | --- | --- |\n    | 1 | 20-foot emanation 3d12 electricity damage DC 29 Reflex check |\n    | 2 | 40-foot emanation 5d12 electricity damage DC 29 Reflex check |\n    | 3 | 60-foot emanation 7d12 electricity damage DC 29 Reflex check |\n    \n*   **3 Vrocks Dancing**  \n    \n    | Round | Effect |\n    | --- | --- |\n    | 1 | 20-foot emanation 4d12 electricity damage DC 30 Reflex check |\n    | 2 | 40-foot emanation 7d12 electricity damage DC 30 Reflex check |\n    | 3 | 60-foot emanation 10d12 electricity damage DC 30 Reflex check |\n    \n*   **4 Vrocks Dancing**  \n    \n    | Round | Effect |\n    | --- | --- |\n    | 1 | 20-foot emanation 5d12 electricity damage DC 31 Reflex check |\n    | 2 | 40-foot emanation 9d12 electricity damage DC 31 Reflex check |\n    | 3 | 60-foot emanation 13d12 electricity damage DC 31 Reflex check |"

  - name: "Spore Cloud"
    desc: "`pf2:1` (disease,poison) The vrock emits a cloud of spores from their body, dealing 2d8 poison damage to all adjacent creatures. Each creature damaged this way must succeed at a DC 28 Fortitude check save or take 2d8 persistent piercing damage as the spores penetrate its skin and grow into thick, green vines. The vines cease growing after 10 rounds, and they wither away in 1d4 days if not shaved off before then. The vines can be destroyed if the creature is affected by a good spell or if _[[Equipment/Holy Water|Holy Water]]_ is applied to the vines (with an Interact action).\n\nOnce the vrock uses Spore Cloud, the ability can't be used for 1d6 rounds."

  - name: "Stunning Screech"
    desc: "`pf2:1` (auditory,divine,incapacitation,sonic) **Frequency** once per minute.\n* * *\n\n**Effect** The vrock emits a shrill screech. Each non-demon creature within a 30-foot burst must attempt a DC 28 Fortitude check save. On a failure, the creature is [[Conditions/Stunned|Stunned 2]], and on a critical failure, it's [[Conditions/Stunned|Stunned 3]]."
 
```

```encounter-table
name: Vrock
creatures:
  - 1: Vrock
```



When the gates to the Abyss swing wide, the first demons through are often vrocks, vulture-headed scions of rage who wheel through the air on black wings or dance with the exultation of their fiendish power. Their hatred for mortals is matched only by their desire to inflict suffering through their horrible screech or their devastating dance. Vrocks form from the souls of hateful mortals who are thus given another chance to inflict their rage on the world.

Vrocks often travel in small groups so as to make the best use of their dance of ruin ability, but they rarely appear in groups larger than four. Against small groups and individuals, they swoop down without fear, hoping to play with their prey before going for the kill. Against formidable foes, they are just as happy to fly above, using their dance of ruin to cast a storm of lightning down on them.

* * *

When a sinful mortal soul is judged and sent on to the Abyss, it can become a deadly fiend-a demon. Demons are living incarnations of sin-be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold-the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Abyss.
