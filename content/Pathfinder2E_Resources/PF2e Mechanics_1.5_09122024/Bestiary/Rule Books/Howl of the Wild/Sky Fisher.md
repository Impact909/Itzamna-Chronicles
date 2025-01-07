---
title: "Sky Fisher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MbkLL37NrCam63WK" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Sky Fisher"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Sky Fisher"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +21, Stealth: +23"
abilityMods: [5, 7, 7, -4, 0, -3]
speed:  fly 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +22, __Will__ +15"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  precision; __Weaknesses__ piercing 7, slashing 7; __Resistances__ bludgeoning 14, poison 14"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Transparency"
    desc: "  Unless it has fed recently, the sky fisher is naturally [[Conditions/Invisible|Invisible]]. Using non-hostile actions does not cause the sky fisher to become [[Conditions/Hidden|Hidden]]. When it takes a hostile action of any kind, the sky fisher is hidden instead of [[Conditions/Undetected|Undetected]] until the start of its next turn, as the vague outline of its many tendrils temporarily becomes faintly visible."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stinging Tentacle"
    desc: "+24 (agile, reach 30 feet)\n__Damage__  2d8 + 8 bludgeoning plus grab,sky-fisher-venom"

  - name: "Abduct"
    desc: "`pf2:1` (attack) The sky fisher reels in a target [[Conditions/Grabbed|Grabbed]] by its tentacles, pulling them into an adjacent space, and then attempts to [[Bestiary Ability Glossary/Swallow Whole|Swallow them Whole]] (Large, 3d8+12 acid, Rupture 25). The sky fisher can only use Swallow Whole when using Abduct."

  - name: "Enzymic Vent"
    desc: "`pf2:2` (poison) The sky fisher vents flesh-eating enzymes into the air, dealing 3d6 persistent acid damage and 3d6 persistent bleed damage in a 20-foot emanation (DC 25 Reflex check save). It can't use Enzymic Vent again for 1d4 rounds."

  - name: "Jet"
    desc: "`pf2:2` (move) The sky fisher quickly expels some of its gases to move swiftly through the air, Flying up to 100 feet in a straight line; this movement doesn't trigger reactions."

  - name: "Sky Fisher Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and can't speak above a whisper (1 round)\n\n**Stage 2** 3d8 poison damage, [[Conditions/Clumsy|Clumsy 2]], and can't speak (1 round)\n\n**Stage 3** 3d10 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sky Fisher
creatures:
  - 1: Sky Fisher
```




