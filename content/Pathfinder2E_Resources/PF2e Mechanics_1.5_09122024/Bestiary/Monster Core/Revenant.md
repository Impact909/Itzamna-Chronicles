---
title: "Revenant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ybj1UP43YamldbPE" 
tags:
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Revenant"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Revenant"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[undead]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "any one spoken in life by their murderer (typically Common)"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Intimidation: +14"
abilityMods: [5, 3, 4, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +13, __Will__ +17"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 5 (except slashing)"
abilities_top:
  - name: ""

  - name: "Sense Murderer"
    desc: " (occult,scrying) A revenant knows the direction of their murderer (as long as both are on the same plane), but not the distance."

abilities_mid:
  - name: ""
  - name: "Self-Loathing"
    desc: " (emotion,mental,visual) If a revenant sees their own reflection or any object that was important to them in life, they must attempt a DC 25 Will check save.\n* * *\n\n**Critical Success** The revenant is unaffected and can no longer be affected by that reflection or object in this way.\n\n**Success** The revenant is distracted by self-loathing and becomes [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The revenant becomes [[Conditions/Fascinated|Fascinated]] by the source that triggered their self-loathing and does everything they can to destroy it until the end of the revenant's next turn.\n\n**Critical Failure** The revenant becomes [[Conditions/Immobilized|Immobilized]] as long as the source of their self-loathing is apparent, until they're attacked, or until they see their murderer."

  - name: "Undying Vendetta"
    desc: " (emotion,occult) If the revenant's murderer dies, the revenant is immediately destroyed. A revenant that can't sense their murderer must attempt a DC 11 Flat check check once every 24 hours to avoid becoming [[Conditions/Immobilized|Immobilized]] and [[Conditions/Prone|Prone]]; they immediately rise again once they can sense their murderer. A murderer who becomes undead does not trigger the revenant's destruction until the murderer is finally destroyed. The revenant gains a +2 status bonus to checks and DCs against their murderer."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  2d8 + 5 slashing plus grab"

  - name: "Baleful Shriek"
    desc: "`pf2:2` (auditory,emotion,fear,incapacitation,mental) The revenant wails horribly. Each creature within a 60-foot burst must attempt a DC 23 Will check save. Regardless of the outcome of their saving throw, affected creatures are then immune to Baleful Shriek for 1 hour. The revenant's murderer never improves their degree of success due to this ability's incapacitation trait.\n\nThe revenant can't use Baleful Shriek again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Failure** The creature is frightened 2 and [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]] and paralyzed for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+5 bludgeoning, DC 24 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Revenant
creatures:
  - 1: Revenant
```



Revenants are obsessed, undead stalkers who arise from their own murders and are driven by only one thing: revenge against their killers. The common wisdom is that revenants arise only from individuals who have been utterly betrayed or abandoned to die a grueling death, but even then, such victims might not rise from their graves. In other cases, revenants might even rise from what might legitimately be considered an accident if the revenant doesn't understand the full circumstances of their demise. In such cases, it doesn't matter that the "murderer" may not have intended to kill, for revenants understands no pity and can never forgive. Revenants have little memory of their lives other than anything they might need to recall in order to achieve their goal of vengeance.
