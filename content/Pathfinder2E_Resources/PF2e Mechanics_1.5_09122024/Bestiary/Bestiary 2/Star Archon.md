---
title: "Star Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fvKm7LnCytm4ii07" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Star Archon"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Star Archon"
level: "Creature 19"

alignment: ""
size: "Medium"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Truesight"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Arcana: +33, Athletics: +37, Diplomacy: +33, Intimidation: +33, Occultism: +33, Religion: +37, Society: +33, Warfare Lore: +39"
abilityMods: [8, 9, 6, 9, 9, 6]
speed: 35 feet,  fly 75 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +31, __Ref__ +34, __Will__ +34; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Weaknesses__ unholy 15; __Resistances__ fire 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Starknife|+2 Greater Striking Starknife]], [[Equipment/Full Plate|+2 Greater Resilient Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Blinding Soul"
    desc: " (divine,light,visual) Whenever the star archon takes slashing damage, bright light pours from their wounds. Non-archons within 10 feet must attempt a DC 38 Fortitude check save.\n\nOn a failure, a creature is [[Conditions/Dazzled|Dazzled]] for 1 round. On a critical failure, the creature is [[Conditions/Blinded|Blinded]] for 1d4 rounds instead.\n\nThe creature is then temporarily immune for 1 round."

  - name: "Explosive Rebirth"
    desc: " (death,divine,fire) When killed, the star archon explodes in a blinding flash of holy energy that deals 12d6 fire damage and 12d6 spirit damage to anything in a 100-foot emanation, with a DC 40 Reflex check save.\n\nA non-archon creature that sees the explosion and critically fails its save is permanently [[Conditions/Blinded|Blinded]] as well.\n\nThe slain star archon reincarnates 1d4 rounds later as a shield archon."

  - name: "[[Bestiary Ability Glossary/Retributive Strike|Retributive Strike]]"
    desc: "`pf2:r`  **Damage Reduction** 21\n\nA star archon can also make a Retributive Strike by throwing its starknife, and the enemy and ally can be within 60 feet instead of 15 feet.\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Returning Starknife"
    desc: "+38 (agile, deadly d8, finesse, holy, magical, reach 10 feet, versatile s)\n__Damage__  3d4 + 16 piercing 2d6 spirit 3d6 fire"

  - name: "**Ranged** `pf2:1` Starknife"
    desc: "+38 (agile, deadly d8, holy, magical, thrown 60 ft., versatile s)\n__Damage__  3d4 + 16 piercing 2d6 spirit 3d6 fire"

  - name: "Divine Innate Spells"
    desc: "DC 43, attack +33; __9th __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Implosion|Implosion]]_, _[[Spells/Sunburst|Sunburst]]_; __7th __  _[[Spells/Heal|Heal]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_; __5th __  _[[Spells/Sending|Sending]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_ __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Archon's Door"
    desc: "  Once per day, if an archon sees another creature cast dimension door, the archon can use [[Spells/Translocate|Translocate]] (heightened to 5th level) within 1 round to attempt to follow that creature to the maximum distance of the archon's dimension door. If the archon's dimension door has enough distance, the archon appears the same distance and direction from the creature as before either creature used dimension door."

  - name: "Prudent Asterism"
    desc: "`pf2:2`  The star archon calculates a celestial constellation and sends their starknife flying along that path from one foe to the next. It makes a starknife Strike against a target within 60 feet. If the Strike hits, it can make another Strike at a different target within 60 feet of the first target, and so on, until it misses with a Strike or runs out of targets it hasn't attacked within range of the most recent target.\n\nThe star archon can attack a given target only once per use of this ability. These attacks don't apply any range increment penalty, and the star archon resolves all the attacks before increasing the multiple attack penalty."
 
```

```encounter-table
name: Star Archon
creatures:
  - 1: Star Archon
```



Embodiments of the virtue of prudence, star archons serve as philosophers and administrators, and in times of war as the tacticians, strategists, and generals of archon armies. Star archons burn with the glory and intensity of a sun, and their sense of duty and desire to defeat evil are as indefatigable as the light of the stars. While their dazzling intellects and unmatched strategic cunning make them most useful in war rooms rather than on battlefields, star archons are fierce opponents when motivated to enter the fray. Those who witness the self-sacrifice of a star archon and live to tell the tale describe the experience in terms that might befit the sight of a supernova at the instant the star collapses in on itself.
