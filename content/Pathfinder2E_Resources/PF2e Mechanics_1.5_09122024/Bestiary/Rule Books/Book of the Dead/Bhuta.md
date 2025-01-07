---
title: "Bhuta"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cZ1aTmu1FWsI2T6i" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Bhuta"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Bhuta"
level: "Creature 11"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Necril; speak with animals"
skills:
  - name: "Skills"
    desc: "Arcana: +20, Deception: +22, Nature: +24, Survival: +22"
abilityMods: [-5, 7, 3, 5, 5, 7]
speed:  fly 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +18, __Ref__ +24, __Will__ +22"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, void healing; __Immunities__  death effects,  disease,  poison,  precision,  unconscious; __Weaknesses__ cold iron 5; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Bound"
    desc: "  Bhutas are bound to a natural area or feature where they died and must remain within 120 feet of that anchor. A bhuta can only leave if invited to travel with living companions, an invitation bhutas often seek to obtain via trickery. While traveling, the bhuta must remain within 120 feet of at least one of the living creatures who invited them. If all members of the group die, the bhuta must return to their bound area by midnight the same day or be destroyed."

  - name: "Shadowless"
    desc: "  A bhuta casts no shadow."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+24 (finesse, magical)\n__Damage__  2d12 + 13 piercing 1d8 bleed"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, finesse, magical)\n__Damage__  2d10 + 13 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22; __9th __  _[[Spells/Nature's Enmity|Nature's Enmity (Only While Within the Area to Which the Bhuta is Bound)]]_; __6th __  _[[Spells/Summon Animal|Summon Animal]]_; __5th __  _[[Spells/Command|Command (Animals Only)]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __4th __  _[[Spells/Charm|Charm (Animals Only)]]_; __3rd __  _[[Spells/Animal Vision|Animal Vision]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Tangle Vine|Tanglefoot]]_\n__Constant__  __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The bhuta takes the form of a Large, Medium, or Small animal common to their bound area. This doesn't change the bhuta's Speed or attack and damage modifiers with their Strikes but might change the damage type their Strikes deal. No matter what form the bhuta takes, their feet remain backward and they cast no shadow. A bhuta in animal form is still incorporeal, though that isn't obvious just by looking at it.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Possess Animal"
    desc: "`pf2:2`  The bhuta attempts to possess an adjacent animal. They cast 9th-rank heightened [[Spells/Possession|Possession]] with the following changes: since the bhuta has no physical body, they're unaffected by that restriction. On a critical failure, the duration extends to 1 full day. While possessed by a bhuta, the animal casts no shadow."

  - name: "Primal Corruption"
    desc: "  A bhuta corrupts wildlife near their bound area, worming their way into animals' minds. Animals who live within the bound area take a -4 circumstance penalty to saves against the bhuta's Possess Animal ability, the bhuta's [[Spells/Charm|Charm]] innate spell, and the bhuta's [[Spells/Command|Command]] innate spell."
 
```

```encounter-table
name: Bhuta
creatures:
  - 1: Bhuta
```



When sapient creatures die violently in a natural setting or a location infused with primal magic, they sometimes rise as a ghostlike undead called a bhuta. Resembling a translucent version of their mortal form, only shadowless and with backward feet, a bhuta's lust for vengeance or unquenchable desire to complete an unfinished task poisons the natural world, turning animals into agents of the bhuta's corrupted will. However, a bhuta's connection to their mortal life is weak and vague, more a series of compulsions and triggers than the torturous recollections of a ghost. Thus, while a bhuta might start by hunting down and devouring those who slew their mortal form, they find no relief and soon turn to predation through their domain.
