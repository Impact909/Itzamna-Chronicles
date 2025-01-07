---
title: "Soulbound Ruin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VGcG6Cr3XA6OSs23" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Soulbound Ruin"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Soulbound Ruin"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Common; other languages typical to the region"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Deception: +26"
abilityMods: [10, 0, 6, 4, 4, 3]
speed: 
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +29, __Ref__ +21, __Will__ +27"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310, void healing; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  unconscious; __Weaknesses__ vitality 15; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Impede"
    desc: "`pf2:r`  **Frequency** once per turn\n\n**Trigger** A creature within the soulbound ruin uses an action with the move trait.\n* * *\n\n**Effect** The soulbound ruin reacts violently to stop the creature's movement, shooting spikes, throwing bricks, or otherwise impeding the target. The target must succeed at a DC 35 Reflex check save or fall [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Vulnerability to Exorcism"
    desc: "  When a soulbound ruin fails a saving throw against a spell that would banish tormented spirits or manipulate souls, such as [[Spells/Banishment|Banishment]] or [[Spells/Seize Soul|Seize Soul]], instead of experiencing the listed effects, it takes 10 damage per spell rank."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Edifice"
    desc: "+30 ()\n__Damage__  4d10 + 9 bludgeoning"

  - name: "Collapse Ceiling"
    desc: "`pf2:3`  The ruin collapses up to three 10-foot by 10-foot sections of its ceiling. The ruin takes 10 damage per section it collapses, and it can't collapse the same section until it has been repaired.\n\nEach creature in one of these areas takes 8d10 bludgeoning damage with a DC 35 Reflex check save. On a failed save, the creature is also [[Conditions/Restrained|Restrained]] under the rubble until it Escapes (DC 33)."

  - name: "Pervasive Attacks"
    desc: "  A soulbound ruin's edifice Strikes can target any creature inside the ruin."

  - name: "Self-Repair"
    desc: "  The ruin can spend 10 minutes repairing itself to regain up to 30 healing Hit Points. If the ruin is interrupted during this time, it loses its focus and the repair fails.\n\nThis ability functions even if the ruin is reduced to 0 HP, unless a [[Spells/Consecrate|Consecrate]] ritual has been performed to purify the building, in which case the soulbound ruin is destroyed. This ritual must be dedicated to a good deity or a deity with a strong opposition to undead, such as Pharasma."
 
```

```encounter-table
name: Soulbound Ruin
creatures:
  - 1: Soulbound Ruin
```



Those who tread in ruined places sometimes speak of a sense that a supernatural presence is there alongside them, as if the spirits of the dead were watching intently. Such presences can be very real, often taking the form of ghosts or other shades of undead that cannot let go of their attachment to the Material Plane. But sometimes, instead of manifesting as distinct spirits, the souls of the dead infuse the very stone and mortar around them. When enough souls attach themselves to a single place-be it a home, crypt, or castle-it can take on a life of its own, becoming a soulbound ruin.
