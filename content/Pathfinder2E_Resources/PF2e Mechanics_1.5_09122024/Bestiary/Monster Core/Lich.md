---
title: "Lich"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.R78EBKIgVymICX2K" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Lich"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Lich"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Draconic, Elven, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Arcana: +28, Crafting: +24, Deception: +17, Diplomacy: +19, Religion: +22, Stealth: +20"
abilityMods: [0, 4, 0, 6, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +17, __Ref__ +21, __Will__ +23; +1 status to all saves vs. vitality"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed; __Resistances__ cold 10, physical 10 (except magical bludgeoning)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff of Fire (Greater)|Staff of Fire (Greater)]], [[Equipment/Invisibility Potion|Invisibility Potion]], [[Equipment/Scroll of 6th-rank Spell|Scroll of Teleport (Rank 6)]]"
abilities_mid:
  - name: ""
  - name: "Counterspell"
    desc: "`pf2:r`  **Trigger** A creature casts a spell the lich has prepared.\n* * *\n\n**Effect** The lich expends a prepared spell to counter the triggering creature's casting of that same spell. The lich loses its spell slot as if it had cast the triggering spell. The lich then attempts to counteract the triggering spell."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet DC 29 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Creature Family Ability Glossary/(Lich) Rejuvenation|Rejuvenation]]"
    desc: " (arcane) When a lich is destroyed, its soul immediately transfers to their _[[Equipment/Lich Soul Cage|Lich Soul Cage]]_. A lich can be permanently destroyed only if their _soul cage_ is found and destroyed."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hand"
    desc: "+24 (finesse, magical)\n__Damage__  4d8 void plus lich-siphon-life"

  - name: "Arcane Prepared Spells"
    desc: "DC 36, attack +26; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Dominate|Dominate]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __5th __  _[[Spells/Howling Blizzard|Howling Blizzard]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_, _[[Spells/Wall of Ice|Wall of Ice]]_; __4th __  _[[Spells/Fire Shield|Fire Shield]]_, _[[Spells/Fly|Fly]]_, _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Vampiric Feast|Vampiric Feast]]_; __2nd __  _[[Spells/Blur|Blur]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/False Vitality|False Vitality]]_, _[[Spells/Resist Energy|Resist Energy]]_, _[[Spells/See the Unseen|See the Unseen]]_; __1st __  _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fleet Step|Fleet Step]]_, _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Sure Strike|Sure Strike]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Frostbite|Frostbite]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "[[Creature Family Ability Glossary/(Lich) Drain Soul Cage|Drain Soul Cage]]"
    desc: "  6th rank\n* * *\n\n**Frequency** once per day\n* * *\n\n**Effect** The lich taps into their _[[Equipment/Soul Cage|Soul Cage]]_'s power to cast any arcane spell up to the highest rank the lich can cast, even if the spell being cast is not one of the lich's prepared spells. The lich's soul cage doesn't need to be present for the lich to use this ability."

  - name: "[[Creature Family Ability Glossary/(Lich) Siphon Life|Siphon Life]]"
    desc: "  A lich's form draws forth life from those who come into contact with it. When the lich damages a living creature with an unarmed attack, the lich gains 5 temporary Hit Points and the creature must succeed at a DC 34 Fortitude check save or become [[Conditions/Drained|Drained 1]].\n\nIf the lich is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] at the start of its turn, each creature grabbing or restraining it must succeed at a Fortitude save or become drained 1. If the lich siphons a creature's life again, the drained value increase by 1, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Steady Spellcasting"
    desc: "  If a reaction would disrupt the lich's spellcasting action, the lich attempts a DC 15 Flat check check. On a success, the action isn't disrupted."
 
```

```encounter-table
name: Lich
creatures:
  - 1: Lich
```



A wizard whose insatiable desire for arcane power eclipsed their mortal life, the lich is a truly devious and versatile spellcaster.

* * *

To gain more time to complete their goals, some desperate spellcasters pursue immortality by embracing undeath. After long years of research and the creation of a special container called a phylactery, a spellcaster takes the final step by imbibing a deadly concoction or casting dreadful incantations that transform them into a lich. While most undertake this drastic plan to continue their work or fulfill some long-term plan, others become liches because they fear death or to fulfill some malevolent purpose, such as long-sworn revenge. Regardless, the result is permanent and carries with it the potential to alter history-both that of those who transform themselves and of the countless mortals that will inevitably suffer as a result of a lich's new power.

After its metamorphosis, a lich often finds some quiet place to dwell, typically protected by a variety of guardians and traps, for two primary purposes. First, a lich requires solitude in order to plan its elaborate schemes, and second, few mortals (if any) deign to interact with these legendarily corrupt necromancers. One reason begets the other, as the self-imposed isolation of a lich often drives the lich insane, further solidifying its separation from civilization. The longer a lich lives, the more meticulous a planner it becomes, secreting itself within a labyrinth of deadly puzzles, misdirection, and monsters. A lich's servants and guardians are absolutely loyal, either due to their nature (such as constructs or other undead) or as a result of compulsion using powerful magic. Many liches go mad, in time, and the nature of a lich's lair is a good indicator of the undead's current mental state.

For all the protections it arrays around itself, a lich will go to greater lengths to guard its phylactery, as it knows that the destruction of this magical container spells doom for the lich. A lich is notoriously difficult to bargain with, though the threat of damaging its phylactery is a sure way to gain the upper hand in such a negotiation.
