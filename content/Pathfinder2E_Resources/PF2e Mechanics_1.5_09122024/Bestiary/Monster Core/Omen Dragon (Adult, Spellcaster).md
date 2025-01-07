---
title: "Omen Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.R6YMaYRoTjjcNTCL" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/occult
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Omen Dragon (Adult, Spellcaster)"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Omen Dragon (Adult, Spellcaster)"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[occult]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +22, Diplomacy: +20, Occultism: +24, Society: +22, Fortune-Telling Lore: +26, Lore (any one subcategory): +24"
abilityMods: [7, 4, 5, 7, 6, 3]
speed: 50 feet,  fly 130 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +19, __Will__ +23; +2 status to all saves vs. occult"
hp: 185
health:
  - name: ""
  - name: HP
    desc: "185; __Immunities__  confused,  doomed,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Challenge Fate"
    desc: "`pf2:r`  **Trigger** The dragon is targeted by an attack;\n* * *\n\n**Effect** This fate is not set in stone. The attacker rolls the triggering attack twice and uses the worse result."

  - name: "Untethered to Fate"
    desc: "  The dragon can choose to negate any fortune or misfortune effects that would affect them; other creatures remain affected normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 (magical, reach 10 feet)\n__Damage__  1d8 mental 2d8 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile, magical)\n__Damage__  2d6 + 11 slashing 1d8 mental"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+20 (magical, reach 15 feet)\n__Damage__  2d8 + 11 bludgeoning 1d8 mental"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+20 (agile, magical, reach 10 feet)\n__Damage__  1d8 mental 1d8 + 11 slashing"

  - name: "Occult Prepared Spells"
    desc: "DC 30, attack +22; __5th __  _[[Spells/Wave of Despair|Wave of Despair]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Confusion|Confusion]]_, _[[Spells/Read Omens|Read Omens]]_; __3rd __  _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Hypercognition|Hypercognition]]_, _[[Spells/Locate|Locate]]_; __2nd __  _[[Spells/Clear Mind|Clear Mind]]_, _[[Spells/Status|Status]]_, _[[Spells/Stupefy|Stupefy]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Protection|Protection]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Occult Innate Spells"
    desc: "DC 30, attack +22; __5th __  _[[Spells/Ill Omen|Ill Omen (At Will)]]_, _[[Spells/Mindlink|Mindlink (At Will)]]_, _[[Spells/Sure Strike|Sure Strike (x2)]]_\n__Cantrips__  __(6th)__ _[[Spells/Guidance|Guidance]]_"

  - name: "Destiny Breath"
    desc: "`pf2:2` (mental,occult) The dragon breathes a translucent mist of potentialities that overwhelms creatures with visions of possible features, dealing 10d6 mental damage in a 30-foot cone (DC 30 Will check save). A creature that fails its save is [[Conditions/Slowed|Slowed 1]] for 1 round (or [[Conditions/Slowed|Slowed 2]] on a critical failure) as it struggles with the visions.\n\nThe dragon can't use Destiny Breath again for 1d4 rounds."

  - name: "Prophetic Wings"
    desc: "  The dragon or any ally can glimpse into the future through the dragon's wings in a process that requires 10 minutes of concentration. This casts a 6th-rank [[Spells/Augury|Augury]] spell, except that the wings can predict results up to 1 month into the future and the dragon always speaks a few cryptic words related to the result of the prediction.\n\nThe dragon can use their wings in this way only once per day, and a given creature can seek a future in the wings only once per week."

  - name: "Walk the Timelines"
    desc: "`pf2:2` (occult) **Frequency** once per hour\n* * *\n\n**Effect** The dragon splits themself into two versions with different fates. Each copy Strides or Flies from the dragon's current space, then takes a single action. If the actions are both attacks, they use the same multiple attack penalty and count as one attack toward the dragon's multiple attack penalty.\n\nAfter both actions, the dragon chooses one of the two locations as their actual destination and the other version of themself disappears."
 
```

```encounter-table
name: Omen Dragon (Adult, Spellcaster)
creatures:
  - 1: Omen Dragon (Adult, Spellcaster)
```



Fate is a fickle matter on Golarion. Even with prophecy broken on the world, there are ways to look to the immediate future or acquire a vague sense of long-term events. Omen dragons are bound to see the future—nebulous though it might be—at all times. Visions of the future hound them like a quiet song that never stops playing in their minds. While an omen dragon can focus on or ignore the music of fate at any time, the song plays all the same. At a glance, omen dragons resemble other occult dragons in appearance, save for the mirror-like interior membrane of their wings. An omen dragon's wings offer glimpses into the future. These glimpses are cloudy and vague, but generally correct, if only technically. Omen dragons have a natural compulsion to share the futures they see. These dragons have no compunctions about what the visions show and share their knowledge equally with innocent villagers as they do with wicked tyrants.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.
