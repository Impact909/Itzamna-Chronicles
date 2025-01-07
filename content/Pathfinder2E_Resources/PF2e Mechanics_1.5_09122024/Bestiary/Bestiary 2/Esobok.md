---
title: "Esobok"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FlFh31d0SWN1a7QC" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Esobok"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Esobok"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Lifesense 60 Feet, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +10, Intimidation: +9, Religion: +4, Stealth: +8, Survival: +10"
abilityMods: [3, 3, 4, -3, 3, 2]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +8, __Will__ +8"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55; __Immunities__  death effects,  disease; __Resistances__ void 5, poison 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (magical)\n__Damage__  1d10 + 3 piercing plus grab,spirit-touch"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile, magical)\n__Damage__  1d6 + 3 slashing plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +7; __2nd __  _[[Spells/Invisibility|Invisibility (Self only) (x3)]]_"

  - name: "Pounce"
    desc: "`pf2:1`  The esobok Strides and then makes a Strike. If it began this action [[Conditions/Hidden|Hidden]], it remains hidden until after the Strike."

  - name: "Spirit Touch"
    desc: " (incorporeal) An esobok's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 1d6 void damage to living creatures and 1d6 vitality damage to undead."

  - name: "Wrench Spirit"
    desc: "`pf2:1` (attack,divine,incapacitation) **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] by the esobok's jaws\n* * *\n\n**Effect** The esobok releases the target from the Grab but wrenches its spirit free as it does so. The creature must attempt a DC 20 Will check save. Creatures without souls (such as most constructs) and creatures whose bodies and souls are one (such as most celestials, fiends, and monitors) that roll a failure or critical failure on the save get a success instead.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The target is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The esobok wrenches the target's soul from its body into its jaws. mindless undead creatures of level 2 or lower are destroyed, other undead creatures are [[Conditions/Stunned|Stunned]] for 1 round, and all other creatures are [[Conditions/Paralyzed|Paralyzed]]. At the end of each of its turns, a creature paralyzed by this effect can attempt a new save to end the effect. The paralysis ends automatically if the esobok attempts a jaws Strike or speaks.\n\n**Critical Failure** As failure, but as long as a creature is stunned or paralyzed, it is also [[Conditions/Stupefied|Stupefied 2]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Esobok
creatures:
  - 1: Esobok
```



Esoboks are brute hunters and pugnacious sentinels that serve as the guard dogs of the Boneyard. These squat, powerful quadrupeds have a frill of dark feathers around their distinctive heads which resemble a crocodile skull. Esoboks rarely bother with those who are truly dead, allowing the dead of the Boneyard to go about their business while remaining watchful for danger. Though cunning when sniffing out threats to the Boneyard or to their psychopomp handlers, they're among the least intelligent of the psychopomps and rarely speak except to utter growling threats. The wise listen when an esobok makes a threat, as it won't do so twice.
