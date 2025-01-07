---
title: "Cauthooj"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Bji3jRUadRGciSpI" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Cauthooj"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cauthooj"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Thoughtsense (Imprecise) 60 Feet"
languages: "Fey; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Stealth: +25"
abilityMods: [6, 4, 7, -3, 2, 0]
speed: 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +20, __Will__ +18"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Resistances__ sonic 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Thoughtsense|Thoughtsense (Imprecise) 60 feet]]"
    desc: " (mental,occult) The cauthooj senses all non-mindless creatures at the listed range."

abilities_mid:
  - name: ""
  - name: "Hop-Dodge"
    desc: "`pf2:r` (move) **Trigger** The cauthooj is the target of a melee Strike and is adjacent to another enemy that is also within the reach of the melee Strike.\n* * *\n\n**Effect** The cauthooj nimbly hops aside, redirecting the triggering Strike against the adjacent enemy. The cauthooj Strides up to half its Speed, and this movement does not trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+26 (agile, deadly d12, reach 10 feet)\n__Damage__  2d12 + 12 piercing"

  - name: "Staccato Strike"
    desc: "`pf2:1` (mental,primal,sonic) With subtle alterations in the pitch and tone of its song, the cauthooj directs one creature [[Conditions/Confused|Confused]] by its Warbling Song to make a Strike. This works like other Strikes made by confused creatures, except that the cauthooj chooses the target. If no target is in reach or range, or the creature is unable to Strike for any other reason, this ability has no effect."

  - name: "Warbling Song"
    desc: "`pf2:2` (auditory,incapacitation,mental,primal) The cauthooj gives a strange, ululating cry that causes nearby creatures to lash out violently and without control. Each creature within 120-foot emanation that can hear the cauthooj must attempt a DC 32 Will check save to resist the effect.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune for 1 minute.\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The target is [[Conditions/Confused|Confused]] for 1 round and immediately attacks itself (in the normal fashion for attacking oneself while confused). This Strike doesn't give the creature a flat check to recover from the confusion."
 
```

```encounter-table
name: Cauthooj
creatures:
  - 1: Cauthooj
```



These large, flightless birds are deceptively agile, considering their long bodies and awkward, hopping gait. Solitary predators, they use their hypnotic warbling song to drive prey into a wild frenzy, manipulating them into attacking one another so that the cauthooj can then feast on the remains.

Known to some scholars as the puppet master bird, and to others as the shrill shrike, cauthoojs are widely reviled by most intelligent humanoids, in part because they seem to prefer humanoids as prey. Sightings typically lead to the creation of hunting parties to track the creature down before it can kill again, with would-be hunters typically stuffing their ears full of wax in an effort to avoid being affected by its cry. Those who have survived the creature's song report that the experience is uniquely unnerving, and almost all accounts agree that there is no other sound as terrible.

While one might assume the cauthooj is an unintelligent animal, these creatures are smarter than they look. Cauthoojs stalk the perimeter of remote settlements in hopes of finding a lone traveler they can feast upon. They can even understand a few rudimentary words in Fey, although they are incapable of clearly speaking themselves. This doesn't stop the cauthooj from attempting to mimic the sounds it hears, but when it does so, its eerie primal nature enhances the attempt, leading to the bird's signature ability to manipulate minds and encourage conflict, a trait the cauthooj is just barely smart enough to understand—and enjoy
