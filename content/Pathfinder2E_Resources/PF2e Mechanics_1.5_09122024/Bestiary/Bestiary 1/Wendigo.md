---
title: "Wendigo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y9RoMSyaoZywf3NE" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Wendigo"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Wendigo"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[cold]]
trait_04: [[evil]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Infrared Vision 60 Feet"
languages: "Aklo, Common, Jotun; telepathy 1 mile"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +33, Deception: +29, Intimidation: +33, Nature: +28, Occultism: +29, Religion: +28, Stealth: +30, Survival: +30"
abilityMods: [8, 7, 9, 6, 5, 6]
speed:  fly 100 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +30, __Will__ +26; +1 status to all saves vs. magic"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315, regeneration 30 (deactivated by cold iron); __Immunities__  cold,  fear effects; __Weaknesses__ cold iron 10, fire 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 1 mile]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Heatsight 60 feet"
    desc: " (primal) Heatsight is a precise sense that sees heat signatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 30 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (cold, magical, reach 10 feet)\n__Damage__  3d10 + 12 piercing 2d6 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, cold, magical, reach 10 feet)\n__Damage__  3d8 + 12 slashing plus grab 2d6 cold plus grab"

  - name: "Primal Innate Spells"
    desc: "DC 38, attack +30; __8th __  _[[Spells/Migration|Wind Walk (At Will)]]_; __4th __  _[[Spells/Nightmare|Nightmare (see Dream Haunting)]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Dream Haunting"
    desc: "  A target that fails its save against the wendigo's [[Spells/Nightmare|Nightmare]] is exposed to wendigo torment."

  - name: "Howl"
    desc: "`pf2:3` (auditory,concentrate,fear,incapacitation,mental,primal) **Frequency** Three times per day\n* * *\n\n**Effect** The wendigo unleashes a forlorn howl that can be heard up to 1 mile away. Any creature that hears the howl must succeed at a DC 38 Will check save or be [[Conditions/Frightened|Frightened 1]]. Any creature that critically fails and is within 120 feet of the wendigo is instead [[Conditions/Frightened|Frightened 3]], and is also fleeing for 1d4 rounds (or until it's no longer frightened, whichever comes first).\n\nA creature frightened by a wendigo's howl still naturally recovers from its fright but can't reduce it below frightened 1 in this way until 1 hour has passed or magic is used.\n\nWhether it succeeds or fails its save, a creature is then temporarily immune to that wendigo's Howl for 24 hours."

  - name: "Ride the Wind"
    desc: "`pf2:r` (air,concentrate,primal) **Trigger** The wendigo casts [[Spells/Migration|Migration]] while it has [[Conditions/Grabbed|Grabbed]] a foe.\n* * *\n\n**Effect** The wendigo attempts to turn the grabbed creature into wind and carry it along as part of the action. If the target succeeds at a DC 38 Will check save, it prevents itself from being transformed; in this case, the wendigo still transforms, automatically releasing the victim.\n\nA creature forced to Ride the Wind along with the wendigo is exposed to wendigo torment. The target can attempt a new Will save each round to return to normal, though it immediately becomes corporeal and begins falling if it succeeds."

  - name: "Wendigo Torment"
    desc: " (curse,mental,primal) A creature affected by wendigo torment can't recover beyond stage 1 until it has been restored to full HP.\n\n**Saving Throw** DC 38 Will check\n\n**Stage 1** [[Conditions/Stupefied|Stupefied 4]] (1 day)\n\n**Stage 2** As stage 1 (1 day)\n\n**Stage 3** The creature searches for an individual of its own ancestry to kill and devour. It then becomes affected by [[Spells/Migration|Migration]] and sprints into the sky so fast that its feet burn away into jagged stumps. As the creature wind walks into the sky, it is replaced by a new wendigo over 2d6 minutes.\n\n[[Spells/Wish|Wish]], similar magic, or a 9th-rank [[Spells/Resurrect|Resurrect]] ritual can return the victim to life. The new wendigo remains even if the victim is resurrected."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Wendigo
creatures:
  - 1: Wendigo
```



Wendigos are incarnations of the fears of starvation, loneliness, and fatal exposure to cold weather. They haunt the frozen expanses of the world.
