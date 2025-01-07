---
title: "Vincuvicar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q0bIMtwiNZtDn9QQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Vincuvicar"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Vincuvicar"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Greater Darkvision, Truesight"
languages: "Common, Diabolic, Shadowtongue; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +35, Crafting: +29, Deception: +32, Intimidation: +34, Medicine: +32, Religion: +30, Stealth: +31, Survival: +30, Torture Lore: +31"
abilityMods: [9, 6, 6, 5, 6, 6]
speed: 25 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +32, __Ref__ +28, __Will__ +30; +1 status to all saves vs. magic"
hp: 333
health:
  - name: ""
  - name: HP
    desc: "333, regeneration 25 (deactivated by holy or silver); __Immunities__  cold,  fear effects; __Weaknesses__ holy 20, silver 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/War Flail|+2 Greater Striking War Flail]], [[Equipment/Full Plate|+2 Greater Resilient Full Plate]], 6x [[Equipment/Manacles (Average)|Manacles (Average)]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Painsight"
    desc: "  A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Alone and Forgotten"
    desc: " (aura,divine,fear,mental) 30 feet. When a creature ends its turn in the aura, it feels imprisoned and must succeed at a DC 37 Will check save or become [[Conditions/Enfeebled|Enfeebled 1]] and [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` War Flail"
    desc: "+35 (disarm, magical, sweep, trip, unholy)\n__Damage__  2d6 bleed 3d10 + 17 bludgeoning"

  - name: "**Ranged** `pf2:1` Animated Manacles"
    desc: "+32 (magical, range increment 20 feet, unholy)\n__Damage__  3d8 + 8 piercing 2d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Scouting Eye|Prying Eye]]_; __8th __  _[[Spells/Command|Command]]_, _[[Spells/Hidden Mind|Mind Blank]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Teleport|Teleport]]_\n__Cantrips__  __(9th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Sigil|Sigil]]_\n__Constant__  __(9th)__ _[[Spells/Discern Lies|Discern Lies]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Imprisonment_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The vincuvicar stares at a creature they can see within 30 feet. The creature must attempt a Will save against the alone and forgotten aura. If the creature was already enfeebled and slowed, on a failed save, its hopelessness causes it to be [[Conditions/Enfeebled|Enfeebled 2]] and unable to take the [[Actions/Escape|Escape]] action as long as they remain enfeebled. After attempting this save, the creature is then temporarily immune until the start of the vincuvicar's next turn."

  - name: "Institutionalized"
    desc: "  A vincuvicar forms a bond with an institution that holds prisoners. This takes 1 day and ends any previous bond the vincuvicar had. While within the area of the prison, the vincuvicar gains a +2 status bonus to skill checks and Perception checks."

  - name: "Shackle"
    desc: "`pf2:r`  **Trigger** A creature within 60 feet is damaged by the vincuvicar's animated manacles Strike\n* * *\n\n**Effect** The creature must attempt a DC 40 Reflex check save.\n* * *\n\n**Critical Success** The creature avoids being manacled.\n\n**Success** The manacles distract the creature, causing it to become [[Conditions/Off-Guard|Off-Guard]] until the end of its next turn.\n\n**Failure** The manacles fuse in place and bind the creature's legs and arms until it [[Actions/Escape|Escapes]] (DC 40) or the manacles are destroyed.\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Restrained|Restrained]]."
 
```

```encounter-table
name: Vincuvicar
creatures:
  - 1: Vincuvicar
```



Prison keepers among velstracs, vincuvicar velstracs thrive on depriving others of freedom.

## Vincuvicar Thrones

Each vincuvicar possesses a personal, spiked iron throne—a symbol of authority. This iron throne is an object with Hardness 20 and 500 Hit Points. If a vincuvicar's throne is destroyed, the velstrac must return to the Shadow Plane to acquire or construct a replacement.
