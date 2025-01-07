---
title: "Gray Master"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qx5Y6fQ9W6xRpiv6" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Gray Master"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Gray Master"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Greater Darkvision"
languages: "Common, Diabolic; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Deception: +36, Intimidation: +38, Society: +34, Stealth: +37, Thievery: +35, Norgorber Lore: +34, Vyre Lore: +36"
abilityMods: [-5, 7, 0, 6, 6, 7]
speed:  fly 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +28, __Ref__ +37, __Will__ +34"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  confused; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Glide Aside"
    desc: "`pf2:r` (move) **Trigger** A Strike targeting Gray Master fails or critically fails\n* * *\n\n**Effect** Gray Master dodges and redirects the attack to a creature adjacent to him and within reach of the triggering Strike. The attacker rerolls the Strike's attack roll against the new target."

  - name: "Ignore Gauntlet Traps"
    desc: "  Gray Master does not trigger any of the traps in his Gauntlet, and cannot be damaged by them."

  - name: "Power of the Trap"
    desc: "  As long as there's at least one trap in Gray Master's Gauntlet that isn't disabled or destroyed, Gray Master gains a +2 status bonus to AC and saving throws and deals an additional 1d6 spirit damage with his bite Strikes. Gray Master is automatically aware of any trap in his Gauntlet as soon as it is triggered, and also as soon as it is disabled or destroyed."

  - name: "Scry Trap"
    desc: "`pf2:r` (divine) **Frequency** once per minute\n\n**Trigger** Gray Master senses a trap activate in his Gauntlet via Power of the Trap\n* * *\n\n**Effect** Gray Master casts scouting eye, but instead of creating an invisible, floating eye, he uses the triggering trap as the eye, and can see in all directions from it. He can Sustain the spell normally, and can continue to view through the trap even if it deactivates without being disabled or destroyed, but can't move his point of view away from it. If the trap is destroyed or disabled while Gray Master is observing through it, the spell ends and Gray Master takes 4d6 mental damage (DC 40 Will check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+37 (agile, finesse, magical)\n__Damage__  4d10 + 10 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __10th __  _[[Spells/Collective Transposition|Collective Transposition]]_; __9th __  _[[Spells/Possession|Possession]]_, _[[Spells/Seize Soul|Seize Soul]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_; __5th __  _[[Spells/Scouting Eye|Scouting Eye (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Brushed by Death"
    desc: "`pf2:2`  Gray Master Flies once and makes a Strike against up to three targets he passes through at his current attack modifier. Each attack counts toward his multiple attack penalty, but he does not increase his penalty until he has made all three attacks. Gray Master cannot use Brushed by Death again for 1d4 rounds."

  - name: "Infectious Delirium"
    desc: "`pf2:1` (divine,emotion,fear,mental) **Frequency** once per minute\n* * *\n\n**Effect** Gray Master unleashes a blast of stilted laughter in a 20-foot emanation, lasting until the beginning of his next turn. Any creature in the area or entering it must succeed at a DC 39 Will check save or be overcome with conflicting thoughts, becoming [[Conditions/Stupefied|Stupefied 3]] (and also [[Conditions/Confused|Confused]] for 1 minute on a critical failure). A creature attempts only one save per Infectious Delirium, and a creature that succeeds on its saving throw is temporarily immune for 24 hours."

  - name: "Sneak Attack"
    desc: "  Gray Master deals 3d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."

  - name: "Wrath of the Trap"
    desc: "`pf2:2` (divine) **Frequency** once per round\n\n**Requirements** Gray Master is within 100 feet of an active complex trap\n* * *\n\n**Effect** Gray Master absorbs the power of the complex trap. It becomes inactive until the end of his next turn, and Power of the Trap deactivates until the complex trap becomes active again. The edges of Gray Master's cloak transform into knife-like blades that stab out at all nearby creatures. Any living creature within 10 feet of Gray Master takes 8d10 slashing damage and 8d6 void damage (DC 40 Reflex check save)."
 
```

```encounter-table
name: Gray Master
creatures:
  - 1: Gray Master
```


Male variant geist

A geist is an ever-shifting mass of black sack cloth, teeth, and mouths, folding in and out of itself and cackling like a thousand frenzied and doomed souls. Created when a haunt kills an evil person, a geist rises from a soul trapped on the plane of their demise, now connected to the dark energy radiating from haunts everywhere. They wander the world, looking for solace and never finding it. In frustration, they turn their malice back onto the living, antagonizing any nearby creatures, hoping to fatally lure their victims into the clutches of a haunt to be turned into another geist and share the torment.

Geists are occasionally mistaken for other incorporeal undead, such as wraiths and ghosts, but their proximity to haunts is one of the surest ways to determine the nature of the undead being encountered.
