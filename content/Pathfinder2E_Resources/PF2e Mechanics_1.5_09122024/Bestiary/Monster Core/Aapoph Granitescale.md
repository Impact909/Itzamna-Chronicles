---
title: "Aapoph Granitescale"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qI1hU9JPn1OKMm6i" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mutant
  - pf2e/creature/type/serpentfolk
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Aapoph Granitescale"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Aapoph Granitescale"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[mutant]]
trait_03: [[serpentfolk]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Sakvroth; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +15, Intimidation: +15"
abilityMods: [5, 4, 4, -1, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24 (22 with shed scales); __Fort__ +16, __Ref__ +14, __Will__ +11; +2 status to Will vs. mental"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "5x [[Equipment/Javelin|Javelin]], [[Equipment/Longspear|Longspear]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Chipping Scales"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The granitescale is about to take piercing or slashing damage\n* * *\n\n**Effect** The granitescale twists to take the blow on their hardest scales, which they shed to reduce the incoming force. The granitescale gains resistance 15 to the damage, but their AC is reduced by 2 for 1 day, when the shed scales regrow."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+17 (reach)\n__Damage__  1d8 + 11 piercing"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  1d8 + 11 piercing plus serpentfolk-venom"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+16 (range increment 30 feet)\n__Damage__  1d6 + 11 piercing"

  - name: "Rattling Spear"
    desc: "`pf2:1` (auditory,emotion,mental) **Requirements** The granitescale's last action was a successful longspear Strike\n* * *\n\n**Effect** The granitescale rattles the base of their spear, attempting an Intimidation check to [[Actions/Demoralize|Demoralize]] all enemies within 30 feet (compare the check result to the targets' Will DCs individually)."

  - name: "Serpentfolk Venom"
    desc: " (poison) **Saving Throw** DC 22 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d4 poison damage and enfeebled 1 (1 round)"
 
```

```encounter-table
name: Aapoph Granitescale
creatures:
  - 1: Aapoph Granitescale
```



The mutated aapophs dubbed granitescales have bulky frames covered in hard gray plates. These scales offer protection but shed when struck with too much force. Granitescales like to carve their shed scales into small chips and attach them as rattles to their spears.

Many an unsuspecting victim has heard the hiss of a granitescale's rattle too late.

* * *

Before their ancient clash with humanity devastated their civilization, serpentfolk were masters of a sprawling underground empire. Their power was shattered and their god Ydersius decapitated (although not quite slain). The cunning, intelligence, and magical abilities of serpentfolk have diminished from their ancient heights, and most are born without these boons. This is partially the result of cruel genetic meddling among serpentfolk—though the ruling class, zyss, are born with an innate spellcasting ability, their blood runs thin, making them susceptible to wounds. Seen as the failures of the serpentfolk's experiments are the aapophs, who are strong but prone to mutation and lack innate spellcasting.

Today, the central realm of the Darklands retains the old name of the serpentfolk empire that once dominated this region—Sekamina. This name is also the source of the serpentfolk's Aklo title, sekmin, which they are often called in ancient texts. Serpentfolk dominion had declined before ghouls, gugs, umbral gnomes, and other forces. Yet their recent ventures have brought them back to a stronger place in the Darklands. Many serpentfolk sleeping in torpor in secluded vaults have awakened.

Zyss serpentfolk tend toward megalomania, with dreams of returning to their place of dominance. Many of their plans hinge on resurrecting Ydersius, their decapitated god. His headless body still thrashes about, mindless, in the Darklands, waiting to be reunited with his lost skull. Serpentfolk numbers are so small that reclaiming their dominance seems a distant dream, especially since their reproduction is slow. Though a parent can birth a dozen young at once, the gestation period lasts up to a decade, and the likelihood that even one will be zyss is low. There's no telling whether a child will be zyss or aapoph, regardless of parentage. A coveted zyss child is just as likely to arise from aapoph parents as from two zyss, and every serpentfolk colony has someone in charge of sorting the young, identifying the earliest signs of magic in them.
