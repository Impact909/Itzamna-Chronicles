---
title: "Vidileth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xHfaDfEtMwWu7X3K" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Vidileth"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vidileth"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[aquatic]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Aklo, Alghollthu, Common, Sakvroth, Thalassic; Truespeech"
skills:
  - name: "Skills"
    desc: "Arcana: +27, Athletics: +24, Deception: +28, Intimidation: +26, Occultism: +29, Society: +27, Stealth: +24, Lore (any one subcategory): +29"
abilityMods: [6, 6, 8, 7, 5, 6]
speed: 10 feet,  swim 80 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +22, __Will__ +24; +2 status to all saves vs. magic"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  controlled,  electricity,  mental; __Resistances__ cold 20"
abilities_top:
  - name: ""

  - name: "Numbing Lights"
    desc: " (aura,light,visual) 30 feet.\n\nThe vidileth exudes dim light. Creatures within the light must attempt a DC 34 Will check save each round, becoming [[Conditions/Stupefied|Stupefied 1]] on a failure (or increase their stupefied value from numbing lights by 1, to a maximum of 4)."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile, magical, reach 20 feet)\n__Damage__  3d10 + 12 slashing plus shape-flesh"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+28 (magical, reach 10 feet, versatile s)\n__Damage__  3d8 + 12 piercing plus consume-memories"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+28 (agile, electricity, magical, reach 20 feet)\n__Damage__  7d6 electricity plus thoughtlance"

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __9th __  _[[Spells/Project Image|Project Image (At Will)]]_; __8th __  _[[Spells/Illusory Scene|Illusory Scene (At Will)]]_, _[[Spells/Suggestion|Suggestion (x3)]]_; __7th __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_; __6th __  _[[Spells/Dominate|Dominate (x3)]]_; __5th __  _[[Spells/Illusory Object|Illusory Object (At Will)]]_, _[[Spells/Mirage|Mirage (At Will)]]_, _[[Spells/Sending|Sending (At Will)]]_, _[[Spells/Translocate|Translocate (x3)]]_; __3rd __  _[[Spells/Hypnotize|Hypnotize (At Will)]]_, _[[Spells/Levitate|Levitate (At Will)]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_, _[[Spells/Water Breathing|Water Breathing (At Will)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Geas_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: " (concentrate,occult,polymorph) **Frequency** once per round\n* * *\n\n**Effect** A vidileth takes on the appearance of a humanoid of Large, Medium, or Small size or resumes its true form. While in humanoid form, the vidileth's Speed is 30 feet, and it loses its numbing lights aura and swim Speed. If the humanoid form assumed lacks the aquatic trait, the vidileth loses its own aquatic trait as well. In humanoid form, the vidileth can use weapons or make Strikes that work like its tentacle attack but use the reach of its current form. If the form has fangs or claws, the vidileth can also make such Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Consume Memories"
    desc: " (mental,occult) When the vidileth hits with a fangs Strike, the target must succeed at a DC 34 Will check save or take 3d6 mental damage. The vidileth gains temporary Hit Points equal to the damage dealt and learns some of the creature's memories (subject to the GM's discretion)."

  - name: "Delayed Suggestion"
    desc: " (occult) When a vidileth successfully casts [[Spells/Dominate|Dominate]] on a creature, a [[Spells/Suggestion|Suggestion]] spell triggers when the _dominate_ spell ends. This _suggestion_ usually causes the target to return to the vidileth, so the creature can cast _dominate_ again, but a vidileth can set the _suggestion_ to different orders if it wishes."

  - name: "Shape Flesh"
    desc: "`pf2:1` (curse,manipulate,occult) **Requirements** The vidileth's last action was a success with a claw Strike\n* * *\n\n**Effect** The vidileth sloppily modifies the target's flesh. They must succeed at a DC 34 Fortitude check save or permanently receive the veiled master's choice of [[Conditions/Clumsy|Clumsy 2]], [[Conditions/Enfeebled|Enfeebled 2]], or a –10 status penalty to Speed."

  - name: "Tentacle Flurry"
    desc: "`pf2:2`  The vidileth makes a tentacle Strike against each creature within its reach. Make only one attack roll, and roll damage once for all targets."

  - name: "Thoughtlance"
    desc: " (curse,occult) A creature touched by the vidileth's tentacles must attempt a DC 34 Will check save, becoming [[Conditions/Slowed|Slowed 1]] on a failure or [[Conditions/Slowed|Slowed 2]] on a critical failure. Each time the affected creature ends its turn, its slowed value decreases by 1."
 
```

```encounter-table
name: Vidileth
creatures:
  - 1: Vidileth
```



The powerful vidileths are the insidious veiled masters of the alghollthus. These manipulators of mind and body alike lead their species in the open, using their ability to change form to walk among and deceive humans and other sapient species. Many veiled masters are even more powerful than the typical specimen presented here and can use a wide range of arcane or occult spells and rituals. While veiled masters command significant combat prowess and impressive magical skills, the greatest danger they pose to others is their uncanny ability to infiltrate into societies much different than their own. The most paranoid of adventurers and conspiracy scholars worry that every major city has been infested by secret cabals of vidileths, while others dismiss this as hogwash and fearmongering. The truth is likely somewhere in between, but it doesn't take many veiled masters pulling the strings behind the scenes to wreak havoc upon an entire nation!

* * *

In bygone millennia, aquatic monsters known as alghollthus used their occult powers to conquer and rule vast parts of the world. Their empires contained countless mortal slaves treated as little more than cattle. Alghollthus shaped their slaves and other creatures using mental manipulation and physically transformative magic. Aberrant horrors from faceless stalkers to mimics can be traced back to this meddling. The rulers of the alghollthu race, the so-called veiled masters, further shaped entire societies by assuming the forms of those they controlled. From the heights of power to the shadows of poverty, the veiled masters manipulated these societies according to their own dark designs, enslaving, killing, or horrifically transforming those who discovered their plans or acted against them.

In time, the alghollthus grew frustrated with their increasingly upstart slave societies and sought to wipe the slate clean-both starting anew and punishing those who had become too willful and rebellious. They used incredible magical power to call forth a cataclysm, hoping to destroy the rebellious societies they'd manipulated. Yet they miscalculated the strength of faith and will to survive of their pawns and slaves, and in time the world and its empires recovered and grew strong once again-this time without alghollthu influence.

Today, the alghollthus have retreated from their mass-scale manipulation of the surface world, and they have mostly remained within the deep aquatic realms where they still rule without question. Yet they have not abandoned their plots entirely, and the reemergence of servitor races like ugothols points to a frightening possibility-that the alghollthus have turned their hateful eyes to the surface once again.
