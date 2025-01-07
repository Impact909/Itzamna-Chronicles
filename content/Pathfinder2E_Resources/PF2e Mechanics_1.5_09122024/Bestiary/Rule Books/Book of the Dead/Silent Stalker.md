---
title: "Silent Stalker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.s6xzSHzsSvLBcEpW" 
tags:
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Silent Stalker"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Silent Stalker"
level: "Creature 13"

alignment: ""
size: "Small"
trait_01: [[lawful]]
trait_02: [[undead]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "any one spoken in life by their murderer (typically common; can&#x27;t speak)"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Intimidation: +24, Stealth: +28"
abilityMods: [8, 5, 3, 0, 5, 3]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +22, __Ref__ +24, __Will__ +22"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 15 (except slashing)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Self-Loathing"
    desc: "  If a silent stalker sees their own reflection or any object important to them in life, they must attempt a DC 33 Will check save.\n* * *\n\n**Critical Success** The pale stranger is unaffected and can no longer be affected by that reflection or object in this way.\n\n**Success** The silent stalker is distracted by self-loathing and is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The silent stalker becomes [[Conditions/Fascinated|Fascinated]] by the source of their self-loathing and does everything they can to destroy it until the end of their next turn.\n\n**Critical Failure** The silent stalker becomes [[Conditions/Immobilized|Immobilized]] as long as the source of their self-loathing is apparent, until they're attacked, or until they see their murderer."

  - name: "Sense Murderer"
    desc: "  A silent stalker knows the direction of their murderer (as long as both are on the same plane), but not the distance."

  - name: "Silent Aura"
    desc: " (aura,illusion,occult) 10 feet. A silent stalker makes no sound, preventing creatures from noticing them using hearing or a similar sense alone. This silence stops all sound within it or passing through. The silent stalker and all creatures in the aura can't use sonic attacks or actions that have the auditory trait; this prevents creatures from casting spells with verbal components or activating items with command components.\n\n[[Bestiary Effects/Effect_ Silent Aura|Effect: Silent Aura]]"

  - name: "Undying Vendetta"
    desc: "  If the silent stalker's murderer dies, the pale stranger is immediately destroyed. A pale stranger that can't sense their murderer must attempt a DC 11 Flat check once every 24 hours to avoid becoming [[Conditions/Immobilized|Immobilized]] and [[Conditions/Prone|Prone]]; they immediately rise again once they can sense their murderer. A murderer who becomes undead does not trigger the silent stalker's destruction until the murderer is finally destroyed. The silent stalker gains a +2 status bonus to checks and DCs against their murderer."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile)\n__Damage__  3d8 + 14 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d8+7 bludgeoning, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Implacable Advance"
    desc: "`pf2:2`  The silent stalker Strides twice and makes a claw Strike; they can ignore difficult terrain during these Strides if they advance toward their murderer. If they Strike and Grab their murderer this turn, they can Constrict as a free action immediately after the Grab."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Silent Stalker
creatures:
  - 1: Silent Stalker
```



When a person is betrayed and killed in a way that their voice was silenced (such as through strangulation by a lover or close confidante), they might come back as a silent stalker. A silent stalker is a horrifying, twisted likeness of the person they were in life, with one obvious difference: the silent stalker has no mouth, simply a smooth patch of flesh where a mouth should be. Sound is suppressed in an area around a silent stalker, but once someone notices the quiet, it's often too late.

* * *

A revenant is a vengeful undead who stalks the one who killed them in life. They're relentless in the pursuit of their murderer, seeking a final justice.
