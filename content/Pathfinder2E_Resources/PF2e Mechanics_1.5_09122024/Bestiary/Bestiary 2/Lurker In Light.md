---
title: "Lurker In Light"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NxVCf7YihjblsI1X" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Lurker In Light"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Lurker In Light"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[fey]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Nature: +11, Occultism: +11, Stealth: +14, Survival: +13"
abilityMods: [0, 5, 2, 2, 4, 2]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +9, __Ref__ +14, __Will__ +13"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72; __Immunities__  blinded; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile, finesse)\n__Damage__  2d6 + 2 slashing"

  - name: "**Ranged** `pf2:1` Mote of Light"
    desc: "+14 (agile, magical, range increment 10 feet)\n__Damage__  2d4 + 2 force plus lurkers-glow"

  - name: "Primal Innate Spells"
    desc: "DC 22, attack +14; __4th __  _[[Spells/Translocate|Dimension Door (Only when in bright light, and only to an area in bright light)]]_, _[[Spells/Summon Fey|Summon Fey]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Holy Light|Searing Light]]_, _[[Spells/Summon Fey|Summon Fey]]_\n__Cantrips__  __(3rd)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Light|Light]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "Blend with Light"
    desc: "`pf2:r` (move) **Trigger** The lurker in light uses a move action\n\n**Requirements** The lurker in light is in an area of bright light\n* * *\n\n**Effect** The lurker in light becomes [[Conditions/Invisible|Invisible]] until it enters an area of dim light or darkness, or until it uses a hostile action."

  - name: "Lurker's Glow"
    desc: " (light,primal) A creature that takes damage from a lurker in light's mote of light must attempt a DC 22 Will check save.\n* * *\n\n**Success** The creature is unaffected and is temporarily immune to lurker's glow for 24 hours.\n\n**Failure** The creature is lined in golden light for 1 minute and can't be [[Conditions/Concealed|Concealed]] during this time. If the creature becomes [[Conditions/Invisible|Invisible]], it is concealed rather than being [[Conditions/Undetected|Undetected]].\n\n**Critical Failure** As failure, but the creature sheds bright light in a 20-foot emanation for the duration of the effect. In addition, the creature is [[Conditions/Dazzled|Dazzled]] on its first turn after failing this save.\n\n[[Bestiary Effects/Effect_ Lurker's Glow (Critical Failure)|Effect: Lurker's Glow (Critical Failure)]]"

  - name: "Ritual Gate"
    desc: "`pf2:1` (primal) **Requirements** The lurker in light has reduced a living creature to 0 Hit Points on this turn or its previous turn and has a [[Spells/Summon Fey|Summon Fey]] innate spell available\n* * *\n\n**Effect** The lurker in light casts _summon fey_ with only a verbal component, using the act of slaughter to replace the normal material and somatic components for the spell. If the fey creature summoned has the same alignment as the lurker in light, the lurker in light can sustain the _summon fey_ spell for up to 1 hour instead of 1 minute."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A lurker in light's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Lurker In Light
creatures:
  - 1: Lurker In Light
```



These malicious and strange fey appear as fairies about 2 feet tall, with insectile wings, large eyes, and bulbous heads. They slaughter and cause mischief in a pattern only their alien intellect understands, but they've been seen to take particular umbrage against dwarves, gnomes, and creatures who live in darkness. With their grudges and pursuit of their own wicked and sadistic whims, lurkers in light deftly overturn the conventional wisdom that creatures associated with light are benign and friendly.

While lurkers in light are fey and have ties to the First World, these creatures are often found elsewhere in the Great Beyond. They are particularly fond of invading the Shadow Plane to bring light to those who dwell there-not to help, but to spread misery and pain among those to whom light is agonizing.
