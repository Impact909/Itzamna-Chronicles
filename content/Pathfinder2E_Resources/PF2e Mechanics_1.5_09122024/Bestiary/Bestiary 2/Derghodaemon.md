---
title: "Derghodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AIcMcsdvcIErQfj6" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Derghodaemon"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Derghodaemon"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +25, Intimidation: +24, Stealth: +24"
abilityMods: [7, 6, 5, 1, 6, 6]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +21, __Ref__ +24, __Will__ +22; +1 status to all saves vs. magic"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240; __Immunities__  death effects,  swarm attacks,  confused; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (deadly d12, magical, reach 10 feet, unholy)\n__Damage__  3d8 + 10 slashing 1d6 spirit"

  - name: "**Ranged** `pf2:1` Swarm Spit"
    desc: "+25 (magical, range increment 60 feet, unholy)\n__Damage__  2d6 + 13 piercing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 32, attack +22; __6th __  _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Never Mind|Feeblemind (x3)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Good only)]]_"

  - name: "Derghodaemon's Stare"
    desc: "`pf2:1` (divine,emotion,incapacitation,mental,visual) A non-evil target must succeed at a DC 32 Will check save or become [[Conditions/Confused|Confused]] for 1 round, or 1 minute on a critical failure. It is temporarily immune for 10 minutes."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Savage Assault"
    desc: "`pf2:2`  The derghodaemon makes up to five claw Strikes, each against a different target. These attacks count toward the derghodaemon's multiple attack penalty, but the penalty doesn't increase until after all the attacks."

  - name: "Swarming Infestation"
    desc: "`pf2:2` (auditory,emotion,mental) The derghodaemon spews a large swarm, making a swarm spit Strike against up to two adjacent targets within range. Whether or not the targets are hit, each must attempt a DC 31 Reflex check save (at a -2 circumstance penalty if it was actually hit by the swarm spit).\n\n[[Conditions/Persistent Damage|Persistent Piercing Damage]] caused by the swarming infestation ends as soon as the creature takes any amount of damage from an area effect.\n\nThe derghodaemon can't use this ability for 1d4 rounds.\n* * *\n\n**Critical Success** The swarm disperses as soon as it deals its swarm spit Strike damage.\n\n**Success** The swarm clings to the target and infests it, dealing 1d6 persistent piercing damage.\n\n**Failure** The swarm clings to the target and infests it, dealing 2d6 persistent piercing damage.\n\n**Critical Failure** As failure, but the hissing sounds caused by the infestation also cause the target to become [[Conditions/Confused|Confused]] for 1 round; this additional effect has the auditory, emotion, and mental traits."
 
```

```encounter-table
name: Derghodaemon
creatures:
  - 1: Derghodaemon
```



Derghodaemons represent death through unfathomable violence and being eaten alive. Whether in life a ravenous murderer hacked them to bits for stew, a werewolf tore them limb from limb, or they simply succumbed to the elements and became worm meat, derghodaemons seek to inflict the same twisted and bloody ends upon any they come across. Unlike some daemons, derghodaemons derive little pleasure from prolonged deaths-to these fiends, the quicker they can enact a gory demise, the sooner they can turn their attentions to their next victim and repeat the violent cycle.

Derghodaemons look like walking masses of razor-sharp insect claws connected to equally menacing chitinous limbs, but few linger on their appearance for long- the gaze of a derghodaemon is enough to cause others in the vicinity to experience severe visual warping. The derghodaemon's appearance becomes more and more twisted as those who stare at it experience vicious hallucinations and ravenous urges to inflict harm on and devour others. Perhaps the most horrific attack derghodaemons can unleash upon their victims, though, is their swarming infestation-the daemons cough up a crawling, buzzing cloud of ravenous insects that cling to those targeted and chew them to death, provided the mind-numbing, half-whispered threats made by the rasp of the insects' bodies don't drive them to violent fury first!
