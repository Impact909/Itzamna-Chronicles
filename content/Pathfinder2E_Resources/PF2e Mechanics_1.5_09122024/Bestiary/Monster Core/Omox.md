---
title: "Omox"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4NYq5dyzEkVO5EAV" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/ooze
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Omox"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Omox"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[ooze]]
trait_04: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Chthonian, Draconic, Empyrean; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +23, Religion: +20, Stealth: +24"
abilityMods: [7, 6, 7, 2, 4, 4]
speed: 40 feet,  climb 20 feet,  swim 80 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +23, __Ref__ +21, __Will__ +20; +1 status to all saves vs. magic"
hp: 395
health:
  - name: ""
  - name: HP
    desc: "395; __Immunities__  acid,  critical hits,  disease,  poison,  precision; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Cleanly Vulnerability"
    desc: "  An omox embodies filth, and they find the concept of cleanliness abhorrent. An omox subjected to an effect that cleans them, such as the tidy command of [[Spells/Prestidigitation|Prestidigitation]], takes 2d6 mental damage. They also take this damage the first time each round a creature hit by one of the omox's attacks spends actions cleaning off the filth."

abilities_mid:
  - name: ""
  - name: "Absorb Weapon"
    desc: "`pf2:r` (concentrate) **Trigger** A creature hits the omox with a melee weapon\n* * *\n\n**Effect** The omox attempts to [[Actions/Disarm|Disarm]] the creature. On a critical success, the weapon becomes subsumed within the omox's body rather than falling to the ground. Retrieving the weapon requires Disarming the omox of it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sludge Tendril"
    desc: "+25 (acid, unholy)\n__Damage__  2d6 + 13 bludgeoning plus grab 2d6 acid plus grab"

  - name: "**Ranged** `pf2:1` Slime Ball"
    desc: "+23 (acid, brutal, range increment 30 feet, unholy)\n__Damage__  2d4 + 11 bludgeoning plus slime-trap 2d6 acid plus slime-trap"

  - name: "Divine Innate Spells"
    desc: "DC 32, attack +24; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Create Water|Create Water (At Will)]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Liquid Leap"
    desc: "`pf2:2` (concentrate,teleportation) **Requirements** The omox is in a space of liquid.\n* * *\n\n**Effect** The omox teleports from its current space to any unoccupied space of liquid within 120 feet."

  - name: "Slime Trap"
    desc: "  A creature hit by an omox's slime ball must succeed at a DC 32 Reflex check save or take a –10-foot circumstance penalty to its Speeds for 1 minute or until it [[/act escape dc=35]]{Escapes (DC 35)}. On a critical failure, the creature is also [[Conditions/Clumsy|Clumsy 1]] for the same duration.\n\n[[Bestiary Effects/Effect_ Slime Trap|Effect: Slime Trap]]"

  - name: "Smother"
    desc: "`pf2:1`  **Requirements** The omox has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The demon flows over the creature, covering it in oozing acidic slime. The creature must succeed at a DC 32 Fortitude check save or it becomes [[Conditions/Blinded|Blinded]] and must hold its breath or begin suffocating. These effects lasts as long as the omox has the creature grabbed or restrained."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Omox
creatures:
  - 1: Omox
```



Seemingly made from living, animated filth, omoxes have no true anatomy, although they generally spend most of their time in roughly humanoid shapes, resembling some grim caricatures of half-melted humanoids. While scholars once believed these foul demons to be a pure, concentrated form of the corruption that suffuses the Outer Rifts and its inhabitants, in truth these demons arise from the souls of those who routinely befouled and polluted their surroundings in life.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
