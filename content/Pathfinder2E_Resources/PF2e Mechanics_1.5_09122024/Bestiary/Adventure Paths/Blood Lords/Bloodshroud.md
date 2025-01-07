---
title: "Bloodshroud"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6xmQMKEnC6ZzLVNz" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Bloodshroud"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Bloodshroud"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common, Draconic, Empyrean, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Arcana: +27, Athletics: +22, Occultism: +27, Stealth: +24"
abilityMods: [5, 8, 2, 5, 5, 4]
speed:  fly 30 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +20, __Ref__ +26, __Will__ +23"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 10, electricity 10, fire 10, piercing 10, slashing 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+1 Striking Greatsword]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Bloodshift"
    desc: "`pf2:r` (teleportation) **Trigger** A creature within 30 feet of the bloodshroud takes damage\n* * *\n\n**Effect** The bloodshroud transports itself and any items it's carrying to any unoccupied space adjacent to the triggering creature."

  - name: "Sanguine Shroud"
    desc: " (death,occult) The bloodshroud is enveloped by a shroud of flowing blood. If a creature deals damage to a bloodshroud with a melee Strike or touches the bloodshroud, the creature must attempt a DC 30 Fortitude check save. Any temporary Hit Points the bloodshroud gains from Sanguine Shroud fade after 1 hour.\n* * *\n\n**Critical Success** As success, but the creature becomes temporarily immune to Sanguine Shroud for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature becomes [[Conditions/Drained|Drained 1]] and takes 2d6 bleed damage. The bloodshroud gains 15 temporary Hit Points.\n\n**Critical Failure** As failure, but the creature becomes [[Conditions/Drained|Drained 2]], and the bloodshroud gains 25 temporary Hit Points."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+26 (magical, versatile p)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile, finesse)\n__Damage__  3d8 + 14 slashing"

  - name: "Arcane Innate Spells"
    desc: "DC 33, attack +25; __8th __  _[[Spells/Polar Ray|Polar Ray (x3)]]_; __7th __  _[[Spells/Disintegrate|Disintegrate]]_; __6th __  _[[Spells/Acid Arrow|Acid Arrow (x3)]]_, _[[Spells/Chromatic Ray|Chromatic Ray (x3)]]_, _[[Spells/Blazing Bolt|Scorching Ray (x3)]]_, _[[Spells/Shocking Grasp|Shocking Grasp (x3)]]_"

  - name: "Spellstrike"
    desc: "`pf2:2`  **Frequency** until recharged\n* * *\n\n**Effect** The bloodshroud channels a spell that takes 1 or 2 actions to cast and requires a spell attack roll into a claw or greatsword Strike. The effects of the spell don't occur immediately but are imbued into the bloodshroud's attack instead. The bloodshroud makes a melee Strike with a weapon or claw. The spell is coupled with the bloodshroud's attack, using the attack roll result to determine the effects of both the Strike and the spell. This counts as two attacks for the purposes of determining the bloodshroud's multiple attack penalty, but the penalty is not applied until after the Spellstrike. Using Bloodshift automatically recharges the bloodshroud's Spellstrike."
 
```

```encounter-table
name: Bloodshroud
creatures:
  - 1: Bloodshroud
```



During the war between Geb and Nex, necromancers conducted dangerous magical experiments to gain every possible advantage over their enemies. One such endeavor attempted to distill the essence of vampiric mists to create a protective shroud for an army of undead maguses.
