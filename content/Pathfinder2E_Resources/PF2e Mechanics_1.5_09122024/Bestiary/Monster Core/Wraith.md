---
title: "Wraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PzokG9vFZ4A1TGi2" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Wraith"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Wraith"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[wraith]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Lifesense 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Diplomacy: +13, Intimidation: +15, Stealth: +16"
abilityMods: [-5, 4, 0, 2, 2, 5]
speed:  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +8, __Ref__ +14, __Will__ +14"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Sunlight Powerlessness"
    desc: "  While in sunlight, a wraith is [[Conditions/Blinded|Blinded]] and [[Conditions/Slowed|Slowed 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wraith Touch"
    desc: "+17 (agile, divine, finesse, void)\n__Damage__  3d8 void"

  - name: "Grip of Fear"
    desc: "`pf2:2` (emotion,fear,mental,nonlethal) The wraith reaches into an adjacent creature's chest, gripping their heart. The target takes 6d6 mental damage with a DC 24 Will check save. On a critical failure, the creature is also [[Conditions/Paralyzed|Paralyzed]] until the start of the wraith's next turn."

  - name: "Robes of Welcome"
    desc: "`pf2:1` (divine,void) **Frequency** once per round\n* * *\n\n**Effect** The wraith wraps its robes around an adjacent living creature, exposing it to void's embrace. If any creature is cursed by the wraith's void's embrace, the wraith can't impose void's embrace on another creature."

  - name: "Void's Embrace"
    desc: " (curse,death,divine,void) If the victim succeeds at a saving throw against this curse while in sunlight, the curse ends. While you have this curse, you bypass the resistance of the wraith that cursed you;\n\n**Saving Throw** DC 24 Will check\n* * *\n\n**Stage 1** the victim is [[Conditions/Dazzled|Dazzled]] in any light (1 hour)\n\n**Stage 2** the victim gains lifesense 30 feet but is [[Conditions/Blinded|Blinded]] in any light (1 hour)\n\n**Stage 3** as stage 2, but the creature also has [[Bestiary Ability Glossary/Void Healing|Void Healing]] (1 hour)\n\n**Stage 4** the victim becomes [[Conditions/Unconscious|Unconscious]] and can't awaken (1 day)\n\n**Stage 5** the creature dies and becomes a wraith, its body crumbling to ash"
 
```

```encounter-table
name: Wraith
creatures:
  - 1: Wraith
```



Wraiths are malevolent undead who drain life and shun light. Their shadowy forms are covered by insubstantial robes that they wear like a badge of office and marked with peering eyes that reflect their judgment of the living. A wraith can be created by foul magic or direct exposure to the Void, but more often they are the result of death on a tragic scale. When a tragedy is too great for even reality to witness, a temporary manifestation of the Void can leave behind countless wraiths in a horde of darkness. A wraith's existence is one of emptiness and need, with a desire to call others to the same emptiness exemplified by the Void.

Wraiths can haunt any location where they can safely interact with the living, looking for those worthy to become new wraiths and disposing of the rest, though their vulnerability to sunlight confines them to the shadowy places of the world—places where they can blend in seamlessly with their dark surroundings before silently engulfing their prey. Wraiths' opinions on who is worthy vary, but they typically choose those closest to the Void already, whether from a metaphysical connection or exposure to countless deaths. A new wraith created this way carries these aspects, with the rest of their personality warped or scoured away by exposure to the Void.

Wraiths gather with others of their kind in places where death and mayhem are commonplace—countrysides ravaged by war, metropolitan underworlds run by criminal overlords, or sites of fiendish rituals. In these places, the living do well to keep to the light. Wraiths are smart enough to take advantage of their incorporeality in combat, so they keep to tortuous caverns or structures with hallways, and avoid open areas.
