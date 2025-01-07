---
title: "Masque Mannequin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7hSskpCIaJolpglF" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/soulbound
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Masque Mannequin"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Masque Mannequin"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[soulbound]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "one spoken in life (typically Common; can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +29, Stealth: +29"
abilityMods: [8, 6, 5, -2, 3, 0]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +26, __Ref__ +29, __Will__ +24"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ fire 15; __Resistances__ bludgeoning 7, slashing 7, piercing 15"
abilities_top:
  - name: ""

  - name: "Soul Mask"
    desc: "  The spark of the soul used to create a masque mannequin is infused into its mask. A creature can break a masque mannequin's soul mask with a DC 40 Athletics check check or steal it with a DC 40 Thievery check check. If its mask is broken or removed, a masque mannequin must attempt a DC 40 Fortitude check save.\n* * *\n\n**Critical Success** The masque mannequin's animating spark shifts to infuse its body; it is unaffected and no longer has a soul mask.\n\n**Success** The masque mannequin takes 2d6 persistent mental damage. If it regains its mask, it can place it back on its face as an Interact action to automatically stop this persistent mental damage.\n\n**Failure** As success, but 4d6 persistent mental damage and [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** As failure, but 8d6 persistent mental damage and [[Conditions/Stunned|Stunned 3]]."

abilities_mid:
  - name: ""
  - name: "Awaken"
    desc: "`pf2:r`  **Requirements** The masque mannequin is in Pose\n\n**Trigger** A creature unaware of the mannequin's true nature approaches within reach\n* * *\n\n**Effect** The mannequin makes a Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (agile)\n__Damage__  3d8 + 16 bludgeoning plus improved-grab"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Spirit Blast|Spirit Blast (x3)]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_"

  - name: "Pose"
    desc: "`pf2:1` (concentrate) Until the next time the masque mannequin acts, it appears to be an inanimate mannequin. It has an automatic result of 45 on Deception checks and DCs to appear as an ordinary mannequin."

  - name: "Refashion"
    desc: "`pf2:1` (incapacitation,occult) **Requirements** The masque mannequin is grappling a living creature\n* * *\n\n**Effect** The [[Conditions/Grabbed|Grabbed]] creature must attempt a DC 36 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round as its body grows more wooden.\n\n**Failure** The creature is petrified for the next 24 hours, but instead of turning to stone, it turns into a wooden mannequin. It can attempt a new save at the end of each of its turns.\n\n**Critical Failure** The creature turns into a wooden mannequin permanently."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Masque Mannequin
creatures:
  - 1: Masque Mannequin
```



Masque mannequins are a type of soulbound construct animated by a fragment of a once-living soul infused into an eerie, nearly featureless mask that's then affixed to a mannequin or dressmaker's dummy. Though similar in process to the creation of a soulbound doll or mannequin, creating a masque mannequin requires conducting ritualistic murder and extracting a soul shard during an unwilling victim's death, and only the vilest of crafters would consider attempting such a deed. Masque mannequins are popular among Norgorberites, especially devotees of Father Skinsaw, as well as Kuthites who take pride in drawing out the ritual to gain the largest possible fragment of the soul.

## Malevolent Mindsets

Masque mannequins, even those crafted from virtuous individuals, tend to have a sadistic sense of malice. If left to their own devices, a masque mannequin enjoys playing cat and mouse games with their chosen victims by freezing and unfreezing in areas with mundane mannequins, slowly driving their unfortunate playthings to paranoia before going for the kill.
