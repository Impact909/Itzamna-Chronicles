---
title: "Specter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y2A2EXmcaoh8FUFQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Specter"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Specter"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[lawful]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril; telepathy 100 feet (with spectral thralls only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Intimidation: +15, Stealth: +17"
abilityMods: [-5, 6, 4, 0, 4, 4]
speed:  fly 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +17, __Will__ +15"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet (With Spectral Thralls Only)]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 22 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Pain Starvation"
    desc: "  A specter that goes for more than a month without dealing void damage to a living humanoid becomes desperate and almost feral. It changes alignment from lawful evil to chaotic evil, loses control of any corrupted thralls it might have, and becomes [[Conditions/Quickened|Quickened]]. It can use its additional action only to make vile touch Strikes against humanoid targets. At the end of any turn in which it deals any amount of void damage to a living humanoid, it reverts to lawful evil and is no longer quickened, but any thralls it lost control of remain free."

  - name: "Sunlight Powerlessness"
    desc: "  A specter caught in sunlight is [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Slowed|Slowed 2]] for as long as it remains in the sunlight."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vile Touch"
    desc: "+16 (finesse)\n__Damage__  2d8 + 8 void"

  - name: "Spectral Corruption"
    desc: "`pf2:2` (curse,divine,incapacitation,mental) The specter makes a Vile Touch Strike. If it damages a living creature, the specter gains 5 temporary Hit Points and the target creature must attempt a DC 24 Will check save to avoid becoming corrupted.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to spectral corruption for 1 minute.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 2]] for 1 hour.\n\n**Failure** The creature succumbs to the corruption and becomes a spectral thrall temporarily. The creature is [[Conditions/Controlled|Controlled]] by the specter, obeying the specter's telepathic or spoken orders, though a spectral thrall does not obey obviously self-destructive orders. This lasts until the end of the thrall's next turn, at which point it is no longer controlled but becomes stupefied 2 for 1 hour.\n\n**Critical Failure** As failure, but the duration is unlimited. The thrall can attempt a new Will save at the end of each of its turns; on a success, it is no longer controlled by the specter but becomes stupefied 2 for 1 hour."
 
```

```encounter-table
name: Specter
creatures:
  - 1: Specter
```



When an evil mortal creature dies, it sometimes returns to haunt the area of its death as a specter, a hateful remnant, always seeking to slay others-particularly humanoids-in an attempt to distribute its pain among as many souls as it can. A specter maintains a strange semblance of its prior identity, but with a corrupted sense of purpose. It cannot be reasoned with.

A specter denied the opportunity to harm living humanoids grows increasingly agonized and irrational, akin to the mindset of a starving person forever denied a release from agony through death.
