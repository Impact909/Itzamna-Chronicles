---
title: "Kanker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DJiafn94wJoV5JQo" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Kanker"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Kanker"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Aklo, Chthonian, Common, Necril, Sakvroth, Thassilonian, Varisian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Arcana: +25, Crafting: +25, Deception: +23, Intimidation: +23, Occultism: +23, Religion: +22, Stealth: +24"
abilityMods: [5, 6, 5, 7, 4, 5]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +24, __Will__ +22"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "8x [[Equipment/Acid Flask (Greater)|Acid Flask (Greater)]], 8x [[Equipment/Alchemist's Fire (Greater)|Alchemist's Fire (Greater)]], 8x [[Equipment/Blasting Stone (Greater)|Thunderstone (Greater)]], [[Equipment/Flail|+2 Striking Nightmare Flail]], [[Equipment/Studded Leather Armor|+1 Resilient Studded Leather Armor]], [[Equipment/Alchemist's Toolkit|Alchemist's Toolkit]], [[Equipment/Formula Book (Blank)|Formula Book]], [[Equipment/Blightburn Resin|Blightburn Resin]], 2x [[Equipment/Cheetah's Elixir (Greater)|Cheetah's Elixir (Greater)]], 5x [[Equipment/Midnight Milk (Refined)|Midnight Milk (Refined)]], [[Equipment/Mistform Elixir (Greater)|Mistform Elixir (Greater)]], 5x [[Equipment/Nethershade|Shadow Essence]], Pouch of Black Onyx, Incense and Offerings for Planar Ally"
  - name: "Infused Items"
    desc: "  Kanker carries the following infused items, which last for 24 hours or until the next time he makes his daily preparations: [[Equipment/Acid Flask (Greater)|Acid Flask (Greater)]] (8), [[Equipment/Alchemist's Fire (Greater)|Alchemist's Fire (Greater)]] (8), [[Equipment/Blightburn Resin|Blightburn Resin]], [[Equipment/Cheetah's Elixir (Greater)|Cheetah's Elixir (Greater)]] (2), [[Equipment/Midnight Milk (Refined)|Midnight Milk (Refined)]] (5), [[Equipment/Mistform Elixir (Greater)|Mistform Elixir (Greater)]], [[Equipment/Nethershade|Shadow Essence]] (5), [[Equipment/Blasting Stone (Greater)|Thunderstone (Greater)]] (8)"

abilities_mid:
  - name: ""
  - name: "Evasion"
    desc: "  When Kanker rolls a success on a Reflex save, he gets a critical success instead."

  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 29 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flail"
    desc: "+25 (disarm, magical, sweep, trip)\n__Damage__  2d6 + 11 bludgeoning 1d6 mental"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (finesse)\n__Damage__  3d6 + 11 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, finesse)\n__Damage__  3d4 + 11 slashing plus ghast-paralysis"

  - name: "**Ranged** `pf2:1` Greater Acid Flask"
    desc: "+26 (range increment 30 feet)\n__Damage__  7 acid 1 acid 3d6 acid"

  - name: "**Ranged** `pf2:1` Greater Alchemist&#x27;s Fire"
    desc: "+26 (range increment 30 feet)\n__Damage__  7 fire 3 fire 3d8 fire"

  - name: "**Ranged** `pf2:1` Greater Thunderstone"
    desc: "+26 (range increment 30 feet)\n__Damage__  3d4 sonic 7 sonic"

  - name: "Rituals"
    desc: "_Create Undead_, _Planar Servitor_"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghast is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghast devours a chunk of the corpse and regains 7d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once.\n\nKanker can Consume Flesh from the trough of gore in the northern alcove of his laboratory (area **J12**) if he's adjacent to it."

  - name: "Expanded Splash"
    desc: "  When Kanker throws a bomb, he can maximize the bomb's explosive potential, allowing him to cause the bomb to deal 7 splash damage rather than the normal amount, and the splash damage affects every creature within 10 feet of the target."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease) **Saving Throw** DC 32 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 32 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Quick Bomber"
    desc: "`pf2:1`  Kanker draws an alchemical bomb with an Interact action and throws it as a ranged Strike."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghast jumps up to half its Speed. This movement doesn't trigger reactions."

  - name: "Toxic Effluvium"
    desc: "`pf2:1` (occult,poison) Kanker has exposed himself to so many toxins and poisons over the years that it's all seeped into his undead flesh. When he activates Toxic Effluvium, these foul-smelling fluids seep from his flesh, causing his jaws and claws to secrete drooling rivulets of foul green venom that coat his teeth and talons, as well as any weapon he wields. Until the start of his next turn, Kanker's melee Strikes deal an additional 2d6 poison damage."
 
```

```encounter-table
name: Kanker
creatures:
  - 1: Kanker
```


Male ghast alchemist


