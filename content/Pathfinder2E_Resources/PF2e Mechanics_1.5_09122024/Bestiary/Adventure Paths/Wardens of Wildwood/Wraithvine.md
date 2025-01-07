---
title: "Wraithvine"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vmlmaBcnr8ThgFkW" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/plant
  - pf2e/creature/type/wraithvine
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Wraithvine"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Wraithvine"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[fungus]]
trait_02: [[plant]]
trait_03: [[wraithvine]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Lifesense (Imprecise) 30 Feet"
languages: "Fey; (Can&#x27;t Speak any Language); Telepathy 120 feet (Wraithvines Only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Stealth: +16"
abilityMods: [7, 2, 5, -2, 3, 0]
speed: 20 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +12, __Will__ +13"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  poison; __Weaknesses__ fire 5; __Resistances__ piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 120 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tentacle Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+18 (reach 10 feet)\n__Damage__  2d10 + 11 piercing plus wraithvine-venom"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+18 (agile, reach 15 feet)\n__Damage__  2d6 + 11 bludgeoning plus grab"

  - name: "Light Vulnerability"
    desc: "  Whenever a wraithvine begins its turn in an area of magical light, it is [[Conditions/Slowed|Slowed 1]] on that turn."

  - name: "Parasitic Rejuvenation"
    desc: "`pf2:1`  **Requirements** A creature the wraithvine has [[Conditions/Grabbed|Grabbed]] took damage from wraithvine venom (either from itself, or from a wraithvine child's venom) on its last turn, and the wraithvine hasn't used any other actions this turn\n* * *\n\n**Effect** The wraithvine regains 3d8 healing HP and recovers from the [[Conditions/Fatigued|Fatigued]] and slowed conditions. It reduces any [[Conditions/Enfeebled|Enfeebled]] value it has by 2."

  - name: "Wraithvine Venom"
    desc: "  **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 1d6 poison damage, [[Conditions/Confused|Confused]], and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Confused|Confused]], and [[Conditions/Stupefied|Stupefied 1]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Wraithvine
creatures:
  - 1: Wraithvine
```




