---
title: "Demilich"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MWEytEb3bVbEOM55" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Demilich"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Demilich"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Draconic, Elven, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Arcana: +32, Deception: +26, Occultism: +30, Religion: +21, Stealth: +25"
abilityMods: [-3, 4, 0, 7, -2, 5]
speed:  fly 30 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +23, __Ref__ +27, __Will__ +23; +1 status to all saves vs. vitality"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, void healing; __Immunities__  disease,  paralyzed,  poison,  polymorph,  unconscious; __Resistances__ cold 5, electricity 5, fire 5, physical 5 (except bludgeoning)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Demilich Eye Gem|Demilich Eye Gem]]"
  - name: "Torpor"
    desc: "  Typically, a demilich is inert when encountered and doesn't take actions until its [[Spells/Contingency|Contingency]] reaction has been triggered."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Contingency"
    desc: "`pf2:r`  A demilich has one permanent 8th-rank [[Spells/Contingency|Contingency]] spell in effect with one of its arcane innate spells of 5th level or lower as the companion spell-typically [[Spells/Translocate|Translocate]].\n\n**Trigger** While the lich is in torpor, a creature disturbs the demilich's remains, touches its treasure, or casts a spell that would affect the demilich.\n* * *\n\n**Effect** The demilich ends torpor, rolls initiative, and gains the effect of its contingency's companion spell. The contingency resets after 24 hours."

  - name: "Countermeasures"
    desc: "`pf2:0`  **Trigger** The demilich's turn begins.\n* * *\n\n**Effect** The demilich casts [[Spells/Flicker|Flicker]], [[Spells/Fly|Fly]], [[Spells/Spell Turning|Spell Turning]], or [[Spells/Truesight|Truesight]] on itself. It usually chooses _spell turning_ unless it already has that spell in effect."

  - name: "Telekinetic Whirlwind"
    desc: " (arcane,aura) 20 feet. Telekinetic whirlwind activates when the demilich ends torpor. Loose debris in the area whip up into a whirling storm. This obscures vision, making any creature in the area concealed, and causes creatures in its area (except the demilich) to treat all creatures as [[Conditions/Concealed|Concealed]]. Any creature other than the demilich that enters or begins its turn in the aura takes 2d12 bludgeoning damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (finesse, magical, reach 0 feet)\n__Damage__  1d4 - 3 piercing 6d6 void"

  - name: "Arcane Innate Spells"
    desc: "DC 40, attack +30; __9th __  _[[Spells/Wails of the Damned|Wail of the Banshee]]_; __7th __  _[[Spells/Spell Turning|Spell Turning (At Will)]]_; __4th __  _[[Spells/Flicker|Blink (At Will)]]_, _[[Spells/Translocate|Dimension Door (At Will)]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Demilich Eye Gems (Arcane)"
    desc: "DC 40, attack +30; __8th __  _[[Spells/Polar Ray|Polar Ray]]_, _[[Spells/Quandary|Quandary]]_"

  - name: "Demilich Eye Gems"
    desc: " (arcane) A demilich has gemstone eyes that glow when the demilich is active. Each eye contains an 8th-rank spell that targets one creature (usually one eye has [[Spells/Quandary|Quandary]] and the other [[Spells/Polar Ray|Polar Ray]]). The demilich can Activate an eye. This uses the number of spellcasting actions the spell requires, and also requires command and envision components. When the demilich casts a spell from a gemstone eye, that eye stops glowing for 1d4 rounds, during which time that eye's spell can't be used. Occasionally, one or both of the two _[[Equipment/Demilich Eye Gem|Demilich Eye Gems]]_ can be harvested from a destroyed demilich as magic items."

  - name: "Devour Soul"
    desc: "`pf2:1` (arcane,void) **Requirements** A soul has been trapped in one of the demilich's blight quartz gems for 24 hours.\n* * *\n\n**Effect** The demilich consumes the soul. The soul is utterly destroyed, and the demilich regains HP equal to double the creature's level."

  - name: "Mental Magic"
    desc: "  A demilich can replace all material and somatic components for casting spells with verbal components, and can replace all Interact components for activating magic items with envision components."

  - name: "Staff Gems"
    desc: "  A demilich long ago absorbed the spells from a staff into gemstone nodules embedded in its skull, with larger nodules representing higher-rank spells. It can cast any of the spells as though it were Activating the staff, and regains 1 charge per 4 hours spent in torpor, to a maximum of 8 charges. A typical demilich has the spells from a _[[Equipment/Staff of the Dead (Greater)|Greater Staff of the Dead]]_, but it could have spells from another staff of 8th level or lower instead."

  - name: "Trap Soul"
    desc: "`pf2:1`  **Frequency** once per day per gem\n* * *\n\n**Effect** Ten blight quartz gemstones on the demilich's skull can trap the souls of the living. The Activated gem casts [[Spells/Seize Soul|Seize Soul]]. This bind soul can target and affect a dying creature instead of a corpse. The dying creature can attempt a DC 38 Fortitude check save; if it succeeds, it doesn't die and its soul is not trapped but it's [[Conditions/Drained|Drained 2]] (or is unaffected entirely on a critical success). When the soul of a creature gets trapped, the creature's body swiftly turns to dust.\n\nThe gemstones work like the black sapphires used in _bind soul_, except that they can hold creatures of up to 17th level and have a value of 200 gp apiece. The demilich can Devour a Soul it has trapped."
 
```

```encounter-table
name: Demilich
creatures:
  - 1: Demilich
```



Demiliches are formed when a lich, through carelessness or by accident, loses its phylactery. As years pass, the lich's body crumbles to dust, leaving only the skull as the seat of its necromantic power. The lich enters a sort of torpor, its mind left wandering the planes in search of ever greater mysteries. The lich gradually loses the ability to cast spells and its magic items slowly subsume into its new form. Void energy concentrates around the skull, causing some of its bones and teeth to petrify with power and turn into blight crystals. The resulting lich skull, embedded with arcane gemstones and suffused with palpably powerful magic, forms a creature called a demilich.

Despite its near-constant state of inactivity, a demilich grows restless from time to time, especially when living creatures draw near. Only then does the demilich's hunger for life stir once more, causing it to lash out with terrifying bursts of power in attempts to consume vital energy. Unlike an ordinary lich, should the demilich's skull be destroyed, its bond to the world is permanently severed, although some theorize that even then it is not truly slain. Rather, some think that once the demilich is destroyed, its foul and tormented mind is finally free to wander the planes and find new ways to enact its will. For the short-lived common folk of the Material Plane, this is good enough, though eons later a demilich may reappear in the region it once inhabited with a new—and even more insidious—agenda.

* * *

To gain more time to complete their goals, some desperate spellcasters pursue immortality by embracing undeath. After long years of research and the creation of a special container called a phylactery, a spellcaster takes the final step by imbibing a deadly concoction or casting dreadful incantations that transform them into a lich. While most undertake this drastic plan to continue their work or fulfill some long-term plan, others become liches because they fear death or to fulfill some malevolent purpose, such as long-sworn revenge. Regardless, the result is permanent and carries with it the potential to alter history—both that of those who transform themselves and of the countless mortals that will inevitably suffer as a result of a lich's new power.

After its metamorphosis, a lich often finds some quiet place to dwell, typically protected by a variety of guardians and traps, for two primary purposes. First, a lich requires solitude in order to plan its elaborate schemes, and second, few mortals (if any) deign to interact with these legendarily corrupt necromancers. One reason begets the other, as the self-imposed isolation of a lich often drives the lich insane, further solidifying its separation from civilization. The longer a lich lives, the more meticulous a planner it becomes, secreting itself within a labyrinth of deadly puzzles, misdirection, and monsters. A lich's servants and guardians are absolutely loyal, either due to their nature (such as constructs or other undead) or as a result of compulsion using powerful magic. Many liches go mad, in time, and the nature of a lich's lair is a good indicator of the undead's current mental state.

For all the protections it arrays around itself, a lich will go to greater lengths to guard its phylactery, as it knows that the destruction of this magical container spells doom for the lich. A lich is notoriously difficult to bargain with, though the threat of damaging its phylactery is a sure way to gain the upper hand in such a negotiation.
