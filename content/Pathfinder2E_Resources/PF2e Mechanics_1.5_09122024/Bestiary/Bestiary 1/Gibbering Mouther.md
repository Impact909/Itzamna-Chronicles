---
title: "Gibbering Mouther"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zrNx9R9F4tXjVCeF" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Gibbering Mouther"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Gibbering Mouther"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +13"
abilityMods: [2, 3, 4, -3, 3, 0]
speed: 10 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 21
armorclass:
  - name: AC
    desc: "21 all-around vision; __Fort__ +15, __Ref__ +12, __Will__ +10"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Weaknesses__ bludgeoning 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Gibbering"
    desc: " (auditory,aura,emotion,incapacitation,mental,occult) 60 feet. Each creature that begins its turn within 60 feet of a gibbering mouther must attempt a DC 19 Will check save. On a failure, they are [[Conditions/Confused|Confused]] for 1 round. On a success, they are temporarily immune for 1 minute."

  - name: "Reactive Gnaw"
    desc: "`pf2:r`  **Trigger** An adjacent creature deals the gibbering mouther slashing damage.\n* * *\n\n**Effect** The gibbering mouther's wound opens into another maw. It makes a jaws Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (finesse)\n__Damage__  2d8 + 5 piercing plus grab 1d4 bleed plus grab"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+14 (range 30 feet)\n__Damage__  4d6 acid plus burn-eyes"

  - name: "Burn Eyes"
    desc: "  A creature that takes damage from a gibbering mouther's spittle must succeed at a DC 22 Fortitude check save or be [[Conditions/Dazzled|Dazzled]] for 1 round (or [[Conditions/Blinded|Blinded]] for 1 round on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:1`  DC 22 Reflex check, 3d8 piercing, Escape DC 22, Rupture 8\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Ground Manipulation"
    desc: "`pf2:2` (occult) The gibbering mouther causes stone and earth under its body to grow soft and muddy, remaining so for 1 minute after the mouther moves off the location. A gibbering mouther can move through these areas with ease, but other creatures treat them as difficult terrain."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Gibbering Mouther
creatures:
  - 1: Gibbering Mouther
```



Amorphous blobs of yammering mouths and oozing, fleshy sludge, gibbering mouthers are among the strangest creatures found either aboveground or below. Perpetually ravenous, these aberrations are always seeking their next meals, ever eating but never sated. With a nominal intelligence, gibbering mouthers can understand and even speak Aklo, but they do so in an intelligible manner only rarely. Instead, their innumerable mouths constantly jabber and babble in a stream of sound that disrupts the thought patterns of other creatures in the area.

Where, how, and why gibbering mouthers originated are questions without answers. They share certain similarities with the much more powerful shoggoths, leading to theories that the two creatures share an origin; less charitable scholars have suggested that the gibbering mouther is instead a mortal's attempt to create something akin to a shoggoth-though the question of why remains unanswered. Still others believe gibbering mouthers were sent to the world by the gods as a punishment for some forgotten but surely terrible transgression. Gibbering mouthers themselves have little to say on the matter-at least, not in any sort of sense. Scholars have wasted countless hours in attempts to make sense of gibbering mouthers' noises-studies that put researchers into danger and give results that are contradictory and confusing at best.

Whatever their origin, gibbering mouthers range the entirety of Golarion. Sightings have been recorded in dungeons below ancient cities and ruins as well as many regions of the deeper Darklands layers of Sekamina and Orv. They are somewhat less common in the upper region of Nar-Voth, perhaps due to the prevalence of settlements that don't tolerate gibbering mouthers' presence.
