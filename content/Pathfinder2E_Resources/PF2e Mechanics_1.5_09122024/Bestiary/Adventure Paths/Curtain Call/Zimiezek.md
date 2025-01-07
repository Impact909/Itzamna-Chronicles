---
title: "Zimiezek"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7srqTYMjednE7hX5" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Zimiezek"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Zimiezek"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Greater Darkvision"
languages: "Chthonian, Common, Daemonic, Diabolic, Utopian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +32, Deception: +34, Society: +31, Stealth: +35, Survival: +33, Duskfathom Lore: +31"
abilityMods: [6, 7, 6, 5, 9, 6]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +28, __Ref__ +31, __Will__ +33"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335; __Immunities__  poison"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+2 Greater Striking Astral Corrosive Shortsword"
abilities_mid:
  - name: ""
  - name: "Darting Legs"
    desc: "`pf2:r`  **Trigger** The zimiezek is targeted with an attack\n* * *\n\n**Effect** The Zimiezek gains a +2 circumstance bonus to AC against the triggering attack."

  - name: "Reactive Strike"
    desc: "`pf2:r`  The zimiezek gains two extra reactions on their turn that they can only use to make Reactive Strikes.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+35 (agile, finesse, magical, reach 10 feet, versatile s)\n__Damage__  1d6 acid 3d6 + 14 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Bite"
    desc: "+33 (finesse, magical)\n__Damage__  3d6 poison plus zimiezek-infection 3d10 + 14 piercing plus zimiezek-infection"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+33 (range 60 feet)\n__Damage__ "

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __9th __  _[[Spells/Web|Web (x3)]]_; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Web Restraints"
    desc: "  A creature hit by the zimiezek's web Strike is [[Conditions/Restrained|Restrained]] either to a surface or tethered to the zimiezek until it Escapes (DC 40). The zimiezek gains a +2 circumstance bonus to [[Actions/Trip|Trip]] a tethered target and can Interact with the tether to pull a target 15 feet toward them."

  - name: "Zimiezek Infection"
    desc: " (disease,virulent) Anadis are immune\n\n**Saving Throw** DC 37 Fortitude check\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 day)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] (eight spider legs start to grow out of your back; 1 day)\n\n**Stage 3** clumsy 2, [[Conditions/Drained|Drained 1]] (venomous fangs grow from your mouth, 1 day)\n\n**Stage 4** clumsy 2, drained 1, [[Conditions/Slowed|Slowed 1]] (sticky webbing exudes from your flesh, 1 day)\n\n**Stage 5** [[Conditions/Unconscious|Unconscious]] (you become cocooned in webbing, during which you have no need for food and water, 1 week)\n\n**Stage 6** death (and a brand new zimiezek emerges from your cocooned body)"
 
```

```encounter-table
name: Zimiezek
creatures:
  - 1: Zimiezek
```



The zimiezeks, also known as those-that-weave-secrets, are one of many creatures native to Duskfathom. They resemble large spiders with humanoid hands instead of spidery feet and possess vaguely humanoid heads with multiple eyes and spider fangs for jaws. Their faces are often shrouded by a veil, mask, or webbing to both hide their identity and as a gesture of peace, for a zimiezek's bite can turn other humanoids into them.

Unlike the karumzeks, Norgorber's more common divine servitors, zimiezeks almost never leave Duskfathom. Most are average citizens who revere Norgorber as both deity and prince. Only a few serve the god of secrets directly as the city's security and elite strike force.

## Uncertain Origins

The zimiezeks believe the first of them arose from souls who were once Norgorber's allies in life who stumbled upon the god's greatest secret and were slain to conceal his identity. Some doubt this claim, given Norgorber's anathema on showing mercy. Nevertheless, a connection exists between Norgorber and both zimiezeks and karumzeks that lets the god automatically know the creatures' names and identities.
