---
title: "Smog Wraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XJA2uIpHXeG2IqHF" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Smog Wraith"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Smog Wraith"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[wraith]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision, Lifesense 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Deception: +20, Nature: +19, Stealth: +19"
abilityMods: [-5, 4, 6, 3, 6, 4]
speed:  fly 60 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 27
armorclass:
  - name: AC
    desc: "27 void healing; __Fort__ +17, __Ref__ +17, __Will__ +21; +1 status to all saves vs. vitality"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Floating Corpses"
    desc: "  A smog wraith's victims are imbued with an eerie buoyancy; corpses of such creatures float up to 30 feet in the air while inside the wraith's noxious smog aura, though the wraith has no control over the corpse's movement."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Noxious Smog"
    desc: " (aura,poison) 30 feet. Creatures within the aura are [[Conditions/Concealed|Concealed]], and creatures outside the aura are concealed to creatures within it. A creature that ends its turn within the aura must attempt a DC 25 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is sickened 1 and [[Conditions/Slowed|Slowed 1]] while within the cloud.\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 2]] and slowed 1 while within the cloud."

  - name: "Sunlight Powerlessness"
    desc: "  A smog wraith caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Noxious Hand"
    desc: "+21 (finesse)\n__Damage__  3d6 + 9 poison"

  - name: "Smog Wraith Spawn"
    desc: "  A living humanoid slain by a smog wraith's noxious hand Strike rises as a smog wraith spawn after 1d4 rounds. This spawn is under the command of the smog wraith that killed it. It doesn't have noxious smog or smog wraith spawn and becomes [[Conditions/Clumsy|Clumsy 2]] for as long as it's a smog wraith spawn. If the creator of the spawn dies, the spawn becomes a full-fledged, autonomous smog wraith; it regains its free will, gains smog wraith spawn and noxious smog, and is no longer clumsy."
 
```

```encounter-table
name: Smog Wraith
creatures:
  - 1: Smog Wraith
```



Clouds of choking fumes and toxic smog continuously shroud these potent undead. They constantly belch forth noxious vapors and find great humor in the death of creatures too weak to resist their vile fumes. These fetid vapors are so dense the corpses of a smog wraith's victims can float among them.

Though it's possible to create smog wraiths through necromancy, most are the result of industrialists, inventors, and polluters who in life relished opportunities to exploit nature for profit, power, or prestige. In death, these wretched souls can rise as smog wraiths to continue their spoliation.
