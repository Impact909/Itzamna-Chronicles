---
title: "Ockomlire"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kzApRAsDa1FMbUvG" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Ockomlire"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Ockomlire"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Aklo, Common, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Occultism: +24, Survival: +23"
abilityMods: [8, 4, 5, 5, 4, 0]
speed: 20 feet,  climb 10 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +21, __Will__ +23; +1 status to all saves vs emotion effects"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235; __Resistances__ mental 15"
abilities_top:
  - name: ""

  - name: "Emotion Vulnerability"
    desc: "  If an ockomlire fails a saving throw against an emotion effect, they loses their resistance to mental damage and gains an equal amount of weakness to mental damage (weakness to mental 15 for the typical ockomlire) until the end of their next turn.\n\n[[Bestiary Effects/Effect_ Emotion Vulnerability|Effect: Emotion Vulnerability]]"

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (forceful)\n__Damage__  3d10 + 14 piercing plus improved-grab"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Calm|Calm (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Devour Magic"
    desc: "`pf2:2` (occult) The ockomlire attempts to devour a spell effect from a creature they've [[Conditions/Grabbed|Grabbed]]. To successfully do so, they must counteract that effect with an Occultism check. If the spell effect is an emotion effect, the ockomlire gains a +2 circumstance bonus to this check.\n* * *\n\n**Critical Success** The spell is countered, the ockomlire gains temporary Hit Points equal to twice the spell's rank for 1 minute, and the grabbed creature becomes [[Conditions/Stupefied|Stupefied 2]] for 1 minute.\n\n**Success** As success but [[Conditions/Stupefied|Stupefied 1]].\n\n**Critical Failure** The attempt backfires, and the ockomlire becomes overwhelmed; their emotion vulnerability becomes active until the end of their turn."

  - name: "Haze of Despair"
    desc: "`pf2:2` (emotion,mental,occult) **Requirements** The ockomlire has temporary hit points gained from Devour Magic\n* * *\n\n**Effect** s The ockomlire digests the magic and releases mist that stings the eyes and heart alike. The ockomlire loses any temporary Hit Points they have and all non-ockomlire creatures in a 30-foot emanation take 9d10 mental damage (DC 33 Will check save)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ockomlire
creatures:
  - 1: Ockomlire
```



With its mottled green-and-tan rubbery flesh, six short legs ending in two-clawed feet, and three circular mouths arrayed equidistantly around a disk-shaped head crowned by multiple bulbous eyes, the bizarre Darklands-dwelling ockomlire's strange appearance blurs the line between aberration and fungus.

Ockomlires eat magic, and their specialized organs process and release that magic in the form of a mist that saps the willpower of those it touches. Originally created by sekmin occultists as a potent weapon against Azlanti wizards, since the serpentfolk empire's collapse thousands of years ago, ockomlires have spread upward through the Darklands. They often lair in sewers or abandoned basements in urban areas, drawn to society's use (and waste) of magical energy.

Ockomlires are quite intelligent but tend to have bland personalities. They're fond of verbalizing their observations and experiences, speaking in unsettling piping voices through three mouths; they have a curious penchant for referring to themselves in the third person. They've little interest in having personal names and tend to refer to those they encounter by ancestry instead of name as well.

## Ockomlire Apathy

Because they exude feelings of hopelessness and despair as "waste" from their magical feeding, the ockomlire has become a creature of apathetic detachment. While this affords the ockomlire protection from emotion-based effects, those that do affect them tend to hit hard and actually cause mental anguish. There are thrilling legends of ockomlires laid low by a single bard whose gripping performance simply stirred up enough emotions within the normally distant creatures to cause them rip themselves apart from the inside.
