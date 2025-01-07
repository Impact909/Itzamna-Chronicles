---
title: "Dweomercat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0G2TPyOogLNq9Ypb" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Dweomercat"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Dweomercat"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[chaotic]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Arcana: +16, Nature: +15, Stealth: +17, Survival: +15"
abilityMods: [4, 4, 3, 3, 4, 5]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +12, __Ref__ +17, __Will__ +17; +1 status to all saves vs. magic"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Alter Dweomer"
    desc: "`pf2:r` (arcane) **Trigger** The dweomercat is targeted by a spell or is within the area of a spell as it is cast\n* * *\n\n**Effect** The dweomercat gains an effect related to the school of the triggering spell. This effect occurs before the dweomercat is affected by the triggering spell. The effect lasts for 1 minute, until the dweomercat uses this ability again, or until the dweomercat Dismisses the effect, whichever comes first.\n\n*   **Abjuration** The dweomercat gains a +1 status bonus to AC.\n*   **Conjuration** A cloud of fog appears in a 5-foot burst centered on a corner of the dweomercat's space. Anything in the cloud is [[Conditions/Concealed|Concealed]].\n*   **Divination** The dweomercat gains a +1 status bonus to all skill checks.\n*   **Enchantment** The dweomercat gains a +1 status bonus to all saves.\n*   **Evocation** Magical feedback deals 4d6 force damage to the triggering spellcaster (DC 22 Reflex check save).\n*   **Illusion** The dweomercat becomes [[Conditions/Invisible|Invisible]]. This effect ends if the dweomercat uses a hostile action, in addition to the normal end conditions.\n*   **Necromancy** The dweomercat gains 10 temporary HP.\n*   **Transmutation** The dweomercat gains a +1 status bonus to all attack rolls."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (magical)\n__Damage__  2d10 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile, magical)\n__Damage__  2d8 + 7 slashing"

  - name: "Arcane Innate Spells"
    desc: "DC 26, attack +16; __4th __  _[[Spells/Translocate|Dimension Door (x3)]]_, _[[Spells/Dispel Magic|Dispel Magic (At will)]]_, _[[Spells/Dispelling Globe|Globe of Invulnerability]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Dweomer Leap"
    desc: "`pf2:2` (arcane,teleportation) **Prerequisites** The dweomercat has at least one [[Spells/Translocate|Translocate]] spell remaining\n* * *\n\n**Effect** The dweomercat casts _dimension door_, then can make a melee Strike against one creature adjacent to it at the end of its teleport. If the dweomercat ends its teleport adjacent to a creature under an ongoing spell effect or who cast a spell since the dweomercat's last turn, this does not expend a casting of _dimension door_."

  - name: "Pounce"
    desc: "`pf2:1`  The dweomercat Strides and makes a Strike at the end of that movement. If the dweomercat began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Dweomercat
creatures:
  - 1: Dweomercat
```



Dweomercats are magically gifted felines from the First World, where they prey upon other creatures and feed upon their primal energy. They are sometimes encountered in areas of the Material Plane where the veil to the First World is thin, or in regions where magic has been irreparably warped. Dweomercats are famous for their ability to twist the metaphorical strings of spells cast on or near them, which they can transform into their own defensive magic or tap into to instantly teleport across the battlefield.
