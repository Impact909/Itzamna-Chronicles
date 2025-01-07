---
title: "Ice Mummy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t6Iaddld0zSCemso" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Ice Mummy"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ice Mummy"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[cold]]
trait_02: [[evil]]
trait_03: [[mummy]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Necril; plus any two languages they knew while alive"
skills:
  - name: "Skills"
    desc: "Deception: +18, Intimidation: +16, Occultism: +17, Stealth: +17"
abilityMods: [5, 3, 2, 5, 4, 6]
speed: 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +13, __Will__ +18"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 10; __Resistances__ cold 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|+1 Striking Staff]]"
abilities_mid:
  - name: ""
  - name: "Great Despair"
    desc: " (aura,emotion,fear,incapacitation,mental,occult) 30 feet. Living creatures are [[Conditions/Frightened|Frightened 1]] while in an ice mummy's great despair aura. They can't naturally recover from this fear while in the area but recover instantly once they leave it. When a creature first enters the area, it must succeed at a DC 24 Will check save (after taking the penalty from being frightened) or be [[Conditions/Paralyzed|Paralyzed]] for 1d4 rounds. The creature is then temporarily immune for 24 hours.\n\n[[Bestiary Effects/Effect_ Despair|Effect: Despair]]"

  - name: "Snow Vision"
    desc: "  The ice mummy ignores the [[Conditions/Concealed|Concealed]] condition from falling snow."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+20 (magical, two-hand d8)\n__Damage__  2d4 + 7 bludgeoning plus cold-rot 1d6 cold plus cold-rot"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+19 (agile, magical)\n__Damage__  2d6 + 7 bludgeoning plus cold-rot 1d6 cold plus cold-rot"

  - name: "Channel Rot"
    desc: " (occult) The ice mummy can deliver cold rot through melee weapons they wield."

  - name: "Cold Rot"
    desc: " (cold,curse,disease,divine) This affliction can't be reduced below stage 1, nor can damage from it be healed, until successfully treated with [[Spells/Cleanse Affliction|Cleanse Affliction]] or a similar effect. The affliction can then be removed as normal for a disease. A creature killed by cold rot turns to ice crystals and can't be resurrected except by a 7th-rank [[Spells/Resurrect|Resurrect]] ritual or similar magic\n\n**Saving Throw** DC 24 Fortitude check\n* * *\n\n**Stage 1** [[Conditions/Slowed|Slowed 1]] for 1 round, then carrier with no ill effect (1 minute)\n\n**Stage 2** 5d6 void damage plus 2d6 cold damage and [[Conditions/Stupefied|Stupefied 2]] (1 day)"

  - name: "Frozen Breath"
    desc: "`pf2:2` (cold,concentrate,divine) The ice mummy exhales a 60-foot cone of razor-sharp ice that deals 5d6 cold and 4d6 slashing damage (DC 26 Reflex check).\n\nThe ice mummy can't use Frozen Breath again for 1d4 rounds."
 
```

```encounter-table
name: Ice Mummy
creatures:
  - 1: Ice Mummy
```



The cold of high places coupled with strong winds and less oxygen creates an effect that can preserve bodies, mummifying them through natural processes. Many are created deliberately by cults, and a rare few voluntarily transform.

* * *

The versatility of mummification allows the creation of mummies through a wide range of methods—nature, ritual, alchemy, and combinations of all these.
