---
title: "Mirage Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rjbC1gfWqTNyZIdS" 
tags:
  - pf2e/creature/type/arcane
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Mirage Dragon (Adult, Spellcaster)"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Mirage Dragon (Adult, Spellcaster)"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[arcane]]
trait_02: [[dragon]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Arcana: +24, Athletics: +25, Crafting: +24, Deception: +29, Diplomacy: +27, Performance: +27, Stealth: +27, Thievery: +25, Illusion Lore: +26"
abilityMods: [6, 6, 5, 5, 6, 8]
speed: 50 feet,  climb 30 feet,  fly 150 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +22, __Ref__ +23, __Will__ +25; +2 status to all saves vs. arcane"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235; __Immunities__  fascinated,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "Camouflage"
    desc: "  The dragon can Hide in natural environments even if they don't have cover."

  - name: "Illusion Sense"
    desc: "  When the dragon moves within 30 feet of an illusion that can be disbelieved, they automatically attempt a secret check to disbelieve, even if they didn't spend an action to Interact."

abilities_mid:
  - name: ""
  - name: "Scintillating Defense"
    desc: "`pf2:r` (visual) **Trigger** The dragon is targeted with an attack\n* * *\n\n**Effect** The dragon flashes their iridescent scales at the triggering creature to throw off the attack. The dragon gains [[Conditions/Concealed|Concealment]] against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (magical, reach 15 feet)\n__Damage__  3d10 + 12 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+25 (agile, magical, reach 10 feet)\n__Damage__  3d6 + 12 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+23 (magical, reach 20 feet)\n__Damage__  3d8 + 12 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 35, attack +27; __6th __  _[[Spells/Mislead|Mislead]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_; __5th __  _[[Spells/False Vision|False Vision]]_, _[[Spells/Sending|Sending]]_, _[[Spells/Telekinetic Haul|Telekinetic Haul]]_; __4th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Vapor Form|Vapor Form]]_, _[[Spells/Vision of Death|Vision of Death]]_; __3rd __  _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Hypnotize|Hypnotize]]_; __2nd __  _[[Spells/Embed Message|Embed Message]]_, _[[Spells/Revealing Light|Revealing Light]]_, _[[Spells/See the Unseen|See the Unseen]]_; __1st __  _[[Spells/Disguise Magic|Disguise Magic]]_, _[[Spells/Item Facade|Item Facade]]_, _[[Spells/Phantasmal Minion|Phantasmal Minion]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(6th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 35, attack +27; __6th __  _[[Spells/Illusory Creature|Illusory Creature]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Mirage|Mirage]]_, _[[Spells/Vibrant Pattern|Vibrant Pattern]]_; __4th __  _[[Spells/Illusory Object|Illusory Object (At Will)]]_, _[[Spells/Invisibility|Invisibility]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Figment|Figment]]_, _[[Spells/Message|Message]]_"

  - name: "Captivating Display"
    desc: "`pf2:1` (arcane,visual) **Frequency** once per 10 minutes\n* * *\n\n**Effect** The dragon opens the fins on their head, creating a radiant display of enthralling colors. Each creature in a 30-foot emanation must succeed at a DC 33 Will check save or be [[Conditions/Dazzled|Dazzled]] and [[Conditions/Slowed|Slowed 1]] (or [[Conditions/Slowed|Slowed 2]] on a critical failure) for 1 round. Regardless of the result, a creature is then temporarily immune to Captivating Display for 1 minute."

  - name: "Hallucinatory Breath"
    desc: "`pf2:2` (arcane,emotion,mental) The dragon breathes a cloud that assaults the senses and deals 12d6 mental damage in a 40-foot cone (DC 33 Will check save). A creature that fails its save is also [[Conditions/Confused|Confused]] for 1 round (1 minute on a critical failure) and is then temporarily immune to being confused by Hallucinatory Breath for 1 hour.\n\nThe dragon can't use Hallucinatory Breath again for 1d4 rounds."

  - name: "Lunging Bite"
    desc: "`pf2:2`  The dragon lunges their head forward, making a jaws Strike with an extended reach of 25 feet."

  - name: "Sneak Attack"
    desc: "  The dragon's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] targets."
 
```

```encounter-table
name: Mirage Dragon (Adult, Spellcaster)
creatures:
  - 1: Mirage Dragon (Adult, Spellcaster)
```



Mirage dragons are masters of illusion magic and use their powers to deceive others and further their own agendas. In addition to their magical prowess, mirage dragons possess a number of additional features to help them on hunts or mislead attackers, such as their camouflaging scales and a hallucinatory breath that can confound multiple foes at once. Mirage dragons are vain and egotistical figures. They ultimately care more about themselves than others.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
