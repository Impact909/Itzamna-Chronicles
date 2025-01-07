---
title: "Niallana"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kAaaQvblOgabCg16" 
tags:
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Niallana"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Niallana"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Common; Can&#x27;t Speak"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Performance: +29, Stealth: +28"
abilityMods: [8, 5, 3, 0, 3, 6]
speed: 25 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +28, __Will__ +26"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 15 (except slashing)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Self-Loathing"
    desc: "  If a silent stalker sees their own reflection or any object important to them in life, they must attempt a DC 40 Will check save.\n* * *\n\n**Critical Success** The pale stranger is unaffected and can no longer be affected by that reflection or object in this way.\n\n**Success** The silent stalker is distracted by self-loathing and is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The silent stalker becomes [[Conditions/Fascinated|Fascinated]] by the source of their self-loathing and does everything they can to destroy it until the end of their next turn.\n\n**Critical Failure** The silent stalker becomes [[Conditions/Immobilized|Immobilized]] as long as the source of their self-loathing is apparent, until they're attacked, or until they see their murderer."

  - name: "Sense Murderer"
    desc: " (detection,occult) A silent stalker knows the direction of their murderer (as long as both are on the same plane), but not the distance."

  - name: "Silent Aura"
    desc: " (aura,illusion,occult) 10 feet. A silent stalker makes no sound, preventing creatures from noticing them using hearing or a similar sense alone. This silence stops all sound within it or passing through. The silent stalker and all creatures in the aura can't use sonic attacks or actions that have the auditory trait; this prevents creatures from casting spells with verbal components or activating items with command components.\n\n[[Bestiary Effects/Effect_ Silent Aura|Effect: Silent Aura]]"

  - name: "Undying Vendetta"
    desc: "  If the silent stalker's murderer dies, the pale stranger is immediately destroyed. A pale stranger that can't sense their murderer must attempt a DC 11 Flat check once every 24 hours to avoid becoming [[Conditions/Immobilized|Immobilized]] and [[Conditions/Prone|Prone]]; they immediately rise again once they can sense their murderer. A murderer who becomes undead does not trigger the silent stalker's destruction until the murderer is finally destroyed. The silent stalker gains a +2 status bonus to checks and DCs against their murderer."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile)\n__Damage__  3d8 + 16 slashing plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d8+8 bludgeoning, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Siphon Voice"
    desc: "`pf2:2` (curse,occult) Niallana attempts to steal the voice of a living creature within 30 feet. The target must attempt a DC 36 Fortitude check save. As long as a creature is voiceless due to this effect, Niallana's silent aura is suppressed, and she can speak in the voice of the affected creature.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The target becomes voiceless until the end of Niallana's next turn. A voiceless creature can't speak, create vocal sounds, or take auditory actions (including supplying verbal or command components).\n\n**Failure** As success, but the duration is 1 minute.\n\n**Critical Failure** As success, but the curse duration is permanent."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Niallana
creatures:
  - 1: Niallana
```


Variant silent stalker

When a person is betrayed and killed in a way that their voice was silenced (such as through strangulation by a lover or close confidante), they might come back as a silent stalker. A silent stalker is a horrifying, twisted likeness of the person they were in life, with one obvious difference: the silent stalker has no mouth, simply a smooth patch of flesh where a mouth should be. Sound is suppressed in an area around a silent stalker, but once someone notices the quiet, it's often too late.

* * *

A revenant is a vengeful undead who stalks the one who killed them in life. They're relentless in the pursuit of their murderer, seeking a final justice.
