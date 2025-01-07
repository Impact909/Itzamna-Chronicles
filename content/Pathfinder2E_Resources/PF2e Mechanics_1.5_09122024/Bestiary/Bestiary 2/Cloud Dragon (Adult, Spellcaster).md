---
title: "Cloud Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CZ0A2MNBZPXFE3bz" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/dragon
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Cloud Dragon (Adult, Spellcaster)"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Cloud Dragon (Adult, Spellcaster)"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[dragon]]
trait_03: [[elemental]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Jotun, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +28, Deception: +26, Diplomacy: +26, Intimidation: +28, Nature: +24, Stealth: +23, Survival: +26"
abilityMods: [7, 3, 5, 4, 6, 6]
speed: 50 feet,  fly 160 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +23, __Will__ +26; +1 status to all saves vs. magic"
hp: 254
health:
  - name: ""
  - name: HP
    desc: "254; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "Mist Vision"
    desc: "  Fog and mist don't impair a cloud dragon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from fog and mist."

abilities_mid:
  - name: ""
  - name: "Deflecting Cloud"
    desc: "`pf2:r`  **Trigger** The dragon is the target of a ranged attack\n\n**Requirements** The dragon is aware of the attack and has a free wing\n* * *\n\n**Effect** The cloud dragon flexes a wing and creates a billowing cloud of mist. The dragon is treated as if they were [[Conditions/Hidden|Hidden]] for the purposes of resolving the triggering attack, so normally the attacker must succeed at a DC 11 Flat check to target them. The dragon also gains a +4 circumstance bonus to AC against the triggering attack."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 32 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (electricity, magical, reach 15 feet)\n__Damage__  3d10 + 15 piercing 2d12 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+27 (magical, reach 20 feet)\n__Damage__  3d12 + 15 bludgeoning"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+27 (deadly d10, magical, reach 15 feet)\n__Damage__  2d12 + 13 piercing"

  - name: "Primal Prepared Spells"
    desc: "DC 34, attack +29; __6th __  _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Banishment|Banishment]]_, _[[Spells/Death Ward|Death Ward]]_, _[[Spells/Magic Passage|Passwall]]_; __4th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Speak with Plants|Speak with Plants]]_; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Animal Messenger|Animal Messenger]]_, _[[Spells/Faerie Fire|Faerie Fire]]_, _[[Spells/Speak with Animals|Speak with Animals]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Negate Aroma|Negate Aroma]]_, _[[Spells/Shocking Grasp|Shocking Grasp]]_\n__Cantrips__  __(6th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Primal Innate Spells"
    desc: "DC 36, attack +28; __3rd __  _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Gust of Wind|Gust of Wind (At Will)]]_, _[[Spells/Mist|Obscuring Mist]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (electricity,primal) The dragon breathes a thundercloud that deals 15d6 electricity damage in a 50-foot cone (DC 35 Reflex check save). They can't use Breath Weapon again for 1d4 rounds."

  - name: "Cloud Form"
    desc: "`pf2:1` (polymorph,primal) The cloud dragon's body becomes vaporous and misty. They gain the effects of [[Spells/Vapor Form|Vapor Form]], except their fly Speed remains unchanged. The cloud dragon can use this action again to return to physical form."

  - name: "Cloud Walk"
    desc: "  The cloud dragon can tread on clouds or fog as though on solid ground."
 
```

```encounter-table
name: Cloud Dragon (Adult, Spellcaster)
creatures:
  - 1: Cloud Dragon (Adult, Spellcaster)
```



At heart, cloud dragons are wanderers, explorers, and travelers who enjoy nothing more than seeing new lands and meeting unusual creatures. Cloud dragons range in color from light blue to a pale, milky white and have thick, curling horns and rather short snouts. They keep lairs among the extreme altitudes of the highest mountain peaks but are away on their many journeys as often as they're at home. Cloud dragons spend long hours surveying the lands they fly over from great heights, but they are creatures of whim, making it hard to predict what will pique their curiosity and bring them winging down to converse or investigate something on the ground. Cloud dragons seldom perform acts of outright malice, but they are not often charitable either. A cloud dragon is as likely to simply pluck something they desire off the ground and fly away with it as they are to bargain fairly.

A cloud dragon's ever-changing interests never seem to stray toward the complicated schemes and long-term plans of other dragons. These rovers are creatures of the moment, and although they are as mentally gifted as other true dragons, their interests remain in the here and now. Yet the cloud dragon's penchant for living in the moment is not a personality flaw-they're more than capable of anticipating long-term results of their actions and won't make foolish choices simply to pursue a current interest. At the same time, cloud dragons have little interest in worrying about the future and are as confident in their ability to handle tomorrow's problems as they are today's.

Cloud dragon hoards tend to be well-guarded or well-hidden, as a natural result of their roving habits often taking them away from their lairs for extended periods. Their treasuries include a wide variety of items-they are driven to gather a broad range of prizes rather than collecting one type of item intensively. To a cloud dragon, a diversified hoard is a perfect hoard.
