---
title: "Reborn Sun Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.h9YEWwcfvBgWOWEJ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Reborn Sun Warrior"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Reborn Sun Warrior"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fire]]
trait_03: [[lawful]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +23, Intimidation: +16, Religion: +19, Stealth: +21"
abilityMods: [5, 4, 5, 1, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +21, __Will__ +18"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ fire 10, mental 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|Flame Spike]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol of Walkena]]"
abilities_mid:
  - name: ""
  - name: "Burning Sacrifice"
    desc: " (divine,fire) When the sun warrior is destroyed, they explode in a blast of flame that deals 6d6 fire damage in a 10-foot emanation (DC 27 Reflex check save). Creatures that critically fail their saves are marked with Walkena's religious symbol on a visible area of their body, which remains for 1 day. This mark allows Walkena to treat the creature as if he knew the creature's identity but not having met them for the purposes of [[Spells/Scrying|Scrying]], lowering the spell's DC by 2. The sun warrior's gear and treasure are unaffected by the explosion and left in a pile where they die."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+24 (magical)\n__Damage__  3d8 + 11 piercing 1d6 fire"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 11 bludgeoning plus grab 1d6 fire plus grab"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+23 (magical, thrown 20 ft.)\n__Damage__  3d8 + 11 piercing 1d6 fire"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +19; __5th __ (1 slots) _[[Spells/Breathe Fire|Burning Hands]]_\n__Cantrips__  __(6th)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d4+9 bludgeoning plus 2d6 fire damage, DC 27 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Knocking Sweep"
    desc: "`pf2:2`  **Frequency** once per round\n* * *\n\n**Effect** The sun warrior swings their weapon with a sweeping spin. They attempt separate Athletics checks to [[Actions/Trip|Trip]] any number of creatures within their reach. Each attempt counts toward the sun warrior's multiple attack penalty, but the multiple attack penalty doesn't increase until after they make all the attacks."

  - name: "Pinning Thrust"
    desc: "`pf2:2`  The sun warrior attempts to drive their spear through a foe to pin them in place. The sun warrior makes a spear Strike. On a hit, the target's clothes, armor, or other piece of equipment becomes pinned to the ground. The sun warrior Releases the spear, and the target is [[Conditions/Immobilized|Immobilized]] until they can remove the spear (Escape DC 27). If the Strike was a critical hit, the DC increases by 2."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Reborn Sun Warrior
creatures:
  - 1: Reborn Sun Warrior
```




