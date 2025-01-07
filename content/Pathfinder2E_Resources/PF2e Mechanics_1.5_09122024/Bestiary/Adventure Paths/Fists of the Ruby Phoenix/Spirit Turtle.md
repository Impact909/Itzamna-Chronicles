---
title: "Spirit Turtle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7518NfsQ2Mzlc22A" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/good
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Spirit Turtle"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Spirit Turtle"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[good]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; "
languages: "Common, Fey; tongues"
skills:
  - name: "Skills"
    desc: "Diplomacy: +36, Medicine: +40, Nature: +36, Occultism: +34, Survival: +40, All Lores: +34"
abilityMods: [8, 6, 11, 6, 10, 7]
speed: 30 feet,  swim 40 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +40, __Ref__ +32, __Will__ +38"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320, regeneration 25 (deactivated by cold iron or unholy); __Weaknesses__ cold iron 20; __Resistances__ fire 20, physical 15"
abilities_top:
  - name: ""

  - name: "Environmental Balance"
    desc: " (primal) **Trigger** The spirit turtle begins their turn\n* * *\n\n**Effect** The spirit turtle harnesses their connection with the world around them to augment their attacks. They choose acid, cold, electricity, or fire. The energy damage dealt by their Strikes and Unbalancing Stomp changes to the selected energy type."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Cold Iron or Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Pacifying Aura"
    desc: " (emotion,primal) 100 feet. A spirit turtle exudes a constant feeling of calm. Creatures within the aura are subjected to a 10th-rank [[Spells/Calm|Calm]] spell (DC 44 Will check save). The effects persist up to 1 hour, even if the creature leaves the aura. Regardless of the result of the saving throw, the creature is temporarily immune for 1 hour."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (magical, reach 20 feet)\n__Damage__  4d12 + 14 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+37 (magical, reach 15 feet)\n__Damage__  4d10 + 14 bludgeoning plus improved-knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 44, attack +0; __10th __  _[[Spells/Primal Phenomenon|Primal Phenomenon]]_, _[[Spells/Revival|Revival]]_; __9th __  _[[Spells/Field of Life|Field of Life (x2)]]_; __8th __  _[[Spells/Moment of Renewal|Moment of Renewal (x2)]]_; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (Self Only)]]_, _[[Spells/Regenerate|Regenerate (x2)]]_; __6th __  _[[Spells/Restoration|Restoration (x2)]]_; __5th __  _[[Spells/Breath of Life|Breath of Life (x3)]]_; __4th __  _[[Spells/Heal|Heal (At Will)]]_, _[[Spells/Vital Beacon|Vital Beacon (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  4d12+7 bludgeoning, DC 41 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Unbalancing Stomp"
    desc: "`pf2:2`  The spirit turtle makes a foot Strike. Whether or not the Strike hits, the stomp creates a shockwave on the ground in a 15-foot burst centered on the target. All creatures in the area other than the spirit turtle take 10d10 bludgeoning and 4d8 energy damage and are knocked [[Conditions/Prone|Prone]] (DC 41 Reflex check save). Creatures that critically succeed at their Reflex save are not knocked prone. The spirit turtle can't use Unbalancing Stomp again for 1d4 rounds.\n\n10d10 bludgeoning + 4d8 acid\n\n10d10 bludgeoning + 4d8 cold\n\n10d10 bludgeoning + 4d8 electricity\n\n10d10 bludgeoning + 4d8 fire"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Spirit Turtle
creatures:
  - 1: Spirit Turtle
```



Spirit turtles are benevolent fey known to heal those in need and confer other powerful gifts. These gentle giants resemble enormous turtles and often bear entire ecosystems on their shells.

In ancient times, so the legend goes, spirit turtles used to grant wishes to many mortals. After millennia of such encounters, the giant creatures grew tired and went into hiding or returned to their home plane, the First World. Those few spirit turtles who remain on Golarion now grant their favors only to the purest and worthiest mortal petitioners.
