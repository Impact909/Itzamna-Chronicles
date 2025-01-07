---
title: "Gliminal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uGGwrfA533m5JxVD" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/vitality
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Gliminal"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Gliminal"
level: "Creature 9"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[spirit]]
trait_03: [[vitality]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Lifesense 60 Feet"
languages: "Jyoti; telepathy 60 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Arcana: +15, Medicine: +18, Religion: +16, Forge of Creation Lore: +19"
abilityMods: [-5, 6, 4, 2, 3, 5]
speed:  fly 60 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +21, __Will__ +16"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ void 10; __Resistances__ all damage 5 (except force, ghost touch, or void)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 60 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Positive Nature"
    desc: "  A gliminal doesn't gain the automatic or temporary Hit Points from being on a plane with the vitality planar essence."

  - name: "Radiant Mantle"
    desc: " (aura,light,visual,vitality) 30 feet. The gliminal emits bright light in the area, and dim light out to 60 feet. When a creature enters or starts its turn in the area of bright light, it must succeed at a DC 25 Fortitude check save or become [[Conditions/Dazzled|Dazzled]] until the end of its turn.\n\nIf the mantle is counteracted or suppressed, the gliminal loses their resistance and can't use Bond in Light until the mantle returns."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scintillating Claw"
    desc: "+19 (agile, finesse, magical)\n__Damage__  3d8 + 7 vitality"

  - name: "**Ranged** `pf2:1` Radiant Ray"
    desc: "+19 (light, magical, range 30 feet, vitality)\n__Damage__  4d8 vitality"

  - name: "Primal Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Chromatic Wall|Chromatic Wall]]_, _[[Spells/Holy Light|Searing Light (x3)]]_; __3rd __  _[[Spells/Heal|Heal (At Will)]]_\n__Cantrips__  __(5th)__ _[[Spells/Light|Light]]_"

  - name: "Bond in Light"
    desc: "`pf2:1` (healing,primal,vitality) The gliminal magically links to one living creature within the radius of their radiant mantle. This creature glows with bright light in a 20-foot emanation and dim light to 40 feet.\n\nWhile the link is in effect, the target has fast healing 10, and any time the target needs to defend against an attack or attempt a save, the gliminal can substitute their own AC or corresponding save bonus if it's higher than the target's.\n\nAny time the target takes damage, the gliminal can choose to divert any amount of that damage to themself. The damage has the same type and still applies the gliminal's immunities, resistances, and weaknesses.\n\nThe link remains until the target is more than 120 feet away, the gliminal falls unconscious, or the gliminal uses Bond in Light again.\n\n[[Bestiary Effects/Effect_ Bond in Light|Effect: Bond in Light]]"

  - name: "Overpowering Healing"
    desc: " (primal,vitality) When a gliminal grants vitality healing that would heal a living creature above their maximum Hit Points, including the fast healing HP from their Bond in Light ability, the excess is granted as temporary Hit Points.\n\nUnlike normal, these temporary HP combine with each other, and they last for 1 hour. If a creature's temporary HP from a gliminal ever exceeds its maximum HP, it becomes overloaded and explodes in a burst of vitality energy.\n\nA creature with temporary HP from overpowering healing becomes [[Conditions/Sickened|Sickened 1]], or [[Conditions/Sickened|Sickened 2]] if the temporary HP equal half their maximum HP or more. The creature can't reduce this sickened condition unless it has 0 temporary HP.\n\nOverpowering healing doesn't apply to creatures with the vitality trait."
 
```

```encounter-table
name: Gliminal
creatures:
  - 1: Gliminal
```



Beholding the blinding light of a gliminal is akin to staring into the sun, and consequently, only gliminals themselves fully understand what they are or how they truly look. Gliminals exude a constant aura of vitality energy, suffusing everything they encounter without regard for whether a creature's body can withstand these excesses of vitality energy.

On the Forge of Creation they call home, gliminals view outsiders as unfortunate creatures afflicted with the malady called mortality. They seek to suffuse mortals with light and healing until they no longer suffer, and they consider those who explode into vitality energy cured. Gliminals pulled to other planes, whether summoned or through interplanar rifts, find themselves overwhelmed, and usually lash out in increasingly desperate attempts to escape the oppressive onslaught of matter and negative energies.
