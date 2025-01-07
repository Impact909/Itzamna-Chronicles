---
title: "Festrog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.taMPhpSXTFCgy6co" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Festrog"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Festrog"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +7, Stealth: +7, Survival: +5"
abilityMods: [4, 2, 2, 0, 1, 1]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +7, __Ref__ +7, __Will__ +6"
hp: 24
health:
  - name: ""
  - name: HP
    desc: "24, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Diseased Pustules"
    desc: " (disease,poison) Whenever the festrog takes piercing or slashing damage, creatures adjacent to the festrog take 1d4 poison damage (DC 14 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d6 + 4 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (agile)\n__Damage__  1d4 + 4 slashing"

  - name: "Feast"
    desc: "`pf2:1` (manipulate) **Requirements** The festrog's last action was a jaws Strike that damaged a living creature\n* * *\n\n**Effect** The festrog tears into the creature's flesh and gulps it down voraciously, dealing 1d4 slashing damage to the creature and gaining temporary Hit Points equal to the damage dealt. These temporary HP last for 1 minute."

  - name: "On All Fours"
    desc: "`pf2:1`  **Requirements** The festrog has nothing in their hands\n* * *\n\n**Effect** The festrog Strides with a +10-foot circumstance bonus to their Speed."
 
```

```encounter-table
name: Festrog
creatures:
  - 1: Festrog
```



Spawned from corpses of those who died of illness or starvation and twisted by void energy, festrogs display a visciousness that rivals other undead. They resemble decaying humanoids, but with elongated arms, teeth, and bone-like spikes protruding from their upper backs. Festrogs' tendency to run on all fours has led to them gaining the moniker dog-ghouls, causing the unwary to mistake them for mindless predators.

Festrogs are in fact intelligent, stalking victims in packs and choosing hunting grounds that suit their abilities. They can often be found roaming farmlands, open forests, or wide plains, anywhere they can use their quadrupedal speed to overtake quarry. Belying their mindless appearance, festrogs use tactics similar to those of hunters with hounds: the leader of the pack often flushes prey from cover so that the victim can be brought down by the pack.

Researchers of the necromantic processes that creates risen corpses have found that festrogs spawn more often from slow demises than sudden deaths. Festrogs typically animate from corpses afflicted with disease, while victims of violence are more likely to become more common undead, such as zombies. One documented way to create a festrog is to have scavengers feed on the dead flesh before animating it. This potentially explains why festrogs most often arise in remote areas stricken with famine and desperate predators.

Though most festrogs arise from humans and other prevalent humanoids, other creatures that die in the same circumstances can rise as festrogs. Festrogs that were once larger humanoids such as ogres, hill giants, or trolls behave similarly to other humanoid festrogs and are simply larger and more powerful. More peculiar are the beastkin festrogs formed of quadrupedal animals, which typically have feet or hooves instead of hands, travel on all fours at all times, and have only animal intelligence. In fact, some humanoid festrogs capture and starve beastkin in hopes of the creatures rising as grotesque festrog pets.
