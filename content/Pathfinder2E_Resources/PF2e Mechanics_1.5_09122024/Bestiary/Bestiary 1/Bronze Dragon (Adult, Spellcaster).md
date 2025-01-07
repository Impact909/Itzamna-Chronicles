---
title: "Bronze Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vGFdAZgPD3CsfRwv" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/lawful
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Bronze Dragon (Adult, Spellcaster)"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Bronze Dragon (Adult, Spellcaster)"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[good]]
trait_04: [[lawful]]
trait_05: [[water]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven, Elven, Gnomish, Thalassic; speak with animals"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Arcana: +28, Athletics: +24, Diplomacy: +23, Intimidation: +23, Occultism: +24, Stealth: +22"
abilityMods: [7, 3, 4, 5, 4, 4]
speed: 40 feet,  fly 140 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +23, __Will__ +26; +1 status to all saves vs. magic"
hp: 260
health:
  - name: ""
  - name: HP
    desc: "260; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Electricity Aura"
    desc: " (aura,electricity) 10 feet. 1d12 electricity damage\n\nThe bronze dragon can turn this aura on or off using a single action, which has the concentrate trait, and it can choose to not affect allies with the aura."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 31 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (electricity, magical, reach 15 feet)\n__Damage__  2d12 + 15 piercing 1d12 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile, magical, reach 10 feet)\n__Damage__  2d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+26 (magical, reach 15 feet)\n__Damage__  1d10 + 13 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 33, attack +27; __6th __  _[[Spells/Mislead|Mislead]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Solid Fog|Solid Fog]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Translate|Comprehend Language]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Mirror Image|Mirror Image]]_, _[[Spells/Resist Energy|Resist Energy]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Hydraulic Push|Hydraulic Push]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 33, attack +25; __2nd __  _[[Spells/Mist|Obscuring Mist (At Will)]]_\n__Constant__  __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,electricity,incapacitation,mental) The bronze dragon breathes in one of two ways.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds.\n\n*   **Lightning** The dragon breathes lightning in a 80-foot line that deals 8d12 electricity damage (DC 33 Reflex check save).\n*   **Repulsion Gas** The dragon breathes a 80-foot line of repulsive gas. Each creature in the area must succeed at a DC 33 Will check save or become [[Conditions/Fleeing|Fleeing]] from the dragon for 1 round (or 2 rounds on a critical failure)."

  - name: "Water Mastery"
    desc: " (arcane,water) For up to 60 minutes per day, the dragon, along with allied creatures and vessels within 50 feet, can move at double their normal Speed in water."
 
```

```encounter-table
name: Bronze Dragon (Adult, Spellcaster)
creatures:
  - 1: Bronze Dragon (Adult, Spellcaster)
```



Bronze dragons are among the most common of metallic dragons and the most likely to ally with mortals on worthy quests. However, they are naturally scholarly creatures who would rather remain in their lairs studying esoteric lore than go off on a wild adventure. These aloof and stoic dragons also act as preservationists, guarding storehouses of ancient lore from destruction or perversion. Bronze dragons are principled and protective, but while their silver cousins are quick to crusade for justice, bronze dragons prefer to find an important location worthy of their protection and guard it against any attack or unwelcome intrusion.

Bronze dragons' mastery over water and affinity for electricity means they are a boon to sailors caught in thunderstorms. A bronze dragon's enemies quickly discover neither cloudy sky nor turbulent sea provides shelter from their wrath. Bronze dragons lair along shorelines, often in partially submerged sea caves.

While all dragons keep hoards of treasure, the hoard of a bronze dragon more resembles a vast library-with the shelves kept carefully above the waterline, of course. In addition to their collections of esoteric lore, bronze dragons keep treasures associated with the sea, such as beautiful scrimshaw, flawless pearls, and equipment inlaid with mother-of-pearl and abalone shell.

* * *

Paragons of virtue, nobility, and grace, metallic dragons are benevolent entities revered as mythic beings akin to gods in both their power and majesty. Few have ever seen a metallic dragon firsthand, but tales of their intervention in mortals' lives-and of their passing-always spread far and wide. Named for the way their scales resemble the shining metals humanoids use in commerce, warfare, and industry, these immense beings are diverse in their interests and abilities, and they don't seem to mind being associated with such mundane materials. After all, to compare a gold dragon to a gold coin is like comparing an ocean to a glass of water-though they may seem similar at first glance, the raw power, breadth, and grandeur of one simply overwhelms the other.

In addition to metallic dragons and their chromatic counterparts, other types of dragons roam the world and the rest of the multiverse. In the legendary lands of Tian Xia on the other side of the globe are the imperial dragons, serpentine beings who protect the cosmic balance and defend their ancient homeland. Outside the Material Plane, primal dragons such as the domineering brine dragon and reclusive cloud dragon shape the nature and goings-on of the Elemental Planes. Countless other types of dragons are sure to exist, including dragons on far-flung planes of existence and, it is rumored, primeval dragons who soar between the stars.
