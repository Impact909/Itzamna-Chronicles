---
title: "Horned Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TFwHJ0xwD4zQTr2t" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/primal
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Horned Dragon (Ancient, Spellcaster)"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Horned Dragon (Ancient, Spellcaster)"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[primal]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Elven, Fey, Chthonian, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Arcana: +32, Athletics: +30, Deception: +27, Diplomacy: +31, Intimidation: +31, Nature: +28, Occultism: +34, Society: +31, Stealth: +29, Forest Lore: +31"
abilityMods: [7, 4, 5, 6, 5, 6]
speed: 50 feet,  fly 200 feet,  swim 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +30, __Ref__ +29, __Will__ +32; +1 status to all saves vs. magic"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315; __Immunities__  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "Camouflage"
    desc: "  The dragon can Hide in natural environments even if they don't have cover."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet DC 37 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Miasma"
    desc: " (aura,poison) 20 feet.\n\nAfter the dragon uses their Poison Breath, a cloud of poison gas continues to emanate from their body for 1 round. Any creature that ends its turn in the miasma takes 4d6 poison damage (DC 37 Fortitude check save).\n\nAny creature in the miasma is [[Conditions/Concealed|Concealed]] and treats other creatures as concealed. The dragon can see through this concealment."

  - name: "Twisting Tail"
    desc: "`pf2:r`  **Trigger** A creature within reach of the dragon's tail uses a move action or leaves a square during a move action it's using\n* * *\n\n**Effect** The dragon makes a tail Strike at the creature with a –2 penalty. If the Strike hits, the dragon disrupts the creature's action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, poison, reach 20 feet)\n__Damage__  3d12 + 15 piercing 4d4 poison"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+31 (magical, reach 25 feet)\n__Damage__  3d10 + 13 bludgeoning"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+31 (magical, reach 20 feet)\n__Damage__  2d10 + 13 piercing"

  - name: "Primal Prepared Spells"
    desc: "DC 39, attack +33; __8th __  _[[Spells/Desiccate|Desiccate]]_, _[[Spells/Punishing Winds|Punishing Winds]]_; __7th __  _[[Spells/Execute|Execute]]_, _[[Spells/Mask of Terror|Mask of Terror]]_; __6th __  _[[Spells/Field of Life|Field of Life]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_, _[[Spells/Truesight|Truesight]]_; __5th __  _[[Spells/Toxic Cloud|Toxic Cloud]]_; __4th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Mountain Resilience|Mountain Resilience]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_; __3rd __  _[[Spells/Slow|Slow]]_, _[[Spells/Veil of Privacy|Veil of Privacy]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Humanoid Form|Humanoid Form]]_, _[[Spells/One with Plants|One with Plants]]_, _[[Spells/Sound Body|Sound Body]]_; __1st __  _[[Spells/Gust of Wind|Gust of Wind]]_, _[[Spells/Vanishing Tracks|Vanishing Tracks]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Primal Innate Spells"
    desc: "DC 39, attack +31; __6th __  _[[Spells/Dominate|Dominate]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Suggestion|Suggestion]]_; __2nd __  _[[Spells/Entangling Flora|Entangling Flora (At Will)]]_"

  - name: "Forest Passage"
    desc: "  The horned dragon ignores any difficult terrain caused by plants, such as bushes, vines, and undergrowth. Even plants manipulated by magic don't impede their progress."

  - name: "Impaling Charge"
    desc: "`pf2:2`  **Requirements** The dragon doesn't have a creature impaled on their horn\n* * *\n\n**Effect** The dragon attempts to gore a foe. They Stride, then attempt a horn Strike. On a hit, the target becomes impaled on the dragon's horn. The creature is [[Conditions/Grabbed|Grabbed]] while on the horn (and can attempt to [[Actions/Escape|Escape]] as normal). The dragon doesn't need to use additional actions to keep the impaled creature grabbed. If the dragon moves, they bring the grabbed creature along with them."

  - name: "Poison Breath"
    desc: "`pf2:2` (poison,primal) The dragon breathes a toxic cloud that deals 18d6 poison damage in a 60-foot cone (DC 37 Fortitude check save).\n\nThey can't use Poison Breath again for 1d4 rounds."

  - name: "Trackless Journey"
    desc: "  The horned dragon always gains the benefits of Cover Tracks in natural surroundings, even while moving at full speed."
 
```

```encounter-table
name: Horned Dragon (Ancient, Spellcaster)
creatures:
  - 1: Horned Dragon (Ancient, Spellcaster)
```



The magic that flows through primal dragons can manifest more animalistic or bestial features in a given type of dragon. Notably among these are the massive paired horns of the horned dragon. While their bulky frames, natural coloration, and prominent ridged scales are all remarkable in their own way, it's the horns that are most obvious and striking at first glance. Horned dragons use their horns to impale their prey in a quick and brutal display of their might. They are generally contemplative and have a fixation on knowledge and self-discipline, traits belied by their bestial appearance. As a result, horned dragons are generally more open to speaking with outsiders.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
