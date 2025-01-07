---
title: "Bloom of Lamashtu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7bp410QQmRSbDDkm" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/plant
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Bloom of Lamashtu"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Bloom of Lamashtu"
level: "Creature 10"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[plant]]
trait_05: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Low-Light Vision, Tremorsense (Precise) 30 Feet"
languages: "Chthonian; (cannot speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Stealth: +18"
abilityMods: [7, 2, 5, 0, 5, 3]
speed: 5 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +16, __Will__ +19"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, regeneration 30 (deactivated by fire or holy); __Immunities__  acid,  curse; __Weaknesses__ holy 10, slashing 10; __Resistances__ bludgeoning 10, piercing 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Precise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 30 (Deactivated by Fire or Holy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Defensive Burst"
    desc: "`pf2:r`  **Trigger** The bloom takes slashing damage.\n\n**Effect** The bloom of Lamashtu sprays a gout of acid against an adjacent creature, inflicting 9d6 acid damage (DC 26 Reflex check). The bloom can't use Defensive Burst for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Thorny Vine"
    desc: "+23 (reach 15 feet, unholy)\n__Damage__  2d8 + 10 slashing 2d6 poison"

  - name: "**Ranged** `pf2:1` Thorn"
    desc: "+19 (range 50 feet, unholy)\n__Damage__  2d6 piercing 1d6 poison"

  - name: "Bloom Curse"
    desc: " (curse,primal) A living creature is exposed to the bloom curse if it eats any portion of a bloom of Lamashtu, fails a save against the bloom's seed pod, or is critically hit by the bloom's thorny vine Strike. Unlike the bloom curse contracted from secondary sources, there is no onset time for this version of the curse, and the creature spawned by the victim's death may be much more powerful and is always chaotic evil.\n* * *\n\n**Saving Throw** DC 29 Fortitude check\n\n**Stage 1** no ill effects (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** enfeebled 1 and 2d6 poison damage (8 hours)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] and 4d6 poison damage (10 minutes)\n\n**Stage 5** death;\n\n**Special** A creature that dies from the bloom curse explodes in a blast of First World foliage and releases a monster into the world. This creature is a chaotic evil low-intelligence beast or dragon (chosen by the GM) of the same level as the dead creature."

  - name: "Spew Seed Pod"
    desc: "`pf2:2` (poison,primal) The bloom of Lamashtu's central stalk disgorges a pulsing seed pod from its flower, spitting it at a range of up to 60 feet and creating a 20-foot burst when the seed pod explodes into a spray of supernatural acidic poison. All creatures in this area must attempt a DC 29 Reflex check save. The bloom of Lamashtu can't Spew Seed Pod for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 3d6 acid damage and 3d6 poison damage.\n\n**Failure** The creature takes 5d6 acid damage and 5d6 poison damage and is exposed to the bloom curse.\n\n**Critical Failure** As failure, but 10d6 acid damage and 10d6 poison damage, plus knocked [[Conditions/Prone|Prone]] by the force of the blast."
 
```

```encounter-table
name: Bloom of Lamashtu
creatures:
  - 1: Bloom of Lamashtu
```



A thick, green stalk with spiraling rows of thorns stands at the center of this enormous flowering plant. Each flower has a growing seed pod at its center, surrounded by vibrant petals in a wide variety of colors. Crafted after consecutive seasons of experimentation, prayer, and ritual, the bloom of Lamashtu is the triumph of the cultist Darivan and his Cult of the Bloom. The fiendish plant aids their effort to infect the humanoid population of the Stolen Lands and replace them with monstrous predators. While the Bloom of Lamashtu is intelligent and is capable of understanding Abyssal, it has very little interest in anything other than spreading its curse.

Cultivated to spread misery and violence, the bloom is quietly malevolent, growing its seeds as rapidly as it can. It is 12 feet tall and weighs 600 pounds.
