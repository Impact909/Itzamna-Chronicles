---
title: "Bronze Dragon (Young)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bo0JR0R6HlzDxp9y" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/lawful
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Bronze Dragon (Young)"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Bronze Dragon (Young)"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[good]]
trait_04: [[lawful]]
trait_05: [[water]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven, Elven, Thalassic; speak with animals"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +20, Athletics: +18, Diplomacy: +18, Intimidation: +18, Occultism: +18, Society: +16, Stealth: +16"
abilityMods: [5, 1, 3, 3, 3, 3]
speed: 30 feet,  fly 120 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +17, __Will__ +19; +1 status to all saves vs. magic"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 26 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (electricity, reach 10 feet)\n__Damage__  2d8 + 11 piercing 1d12 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile)\n__Damage__  2d8 + 11 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 (reach 10 feet)\n__Damage__  1d8 + 9 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 28, attack +20\n__Constant__  __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,electricity,incapacitation,mental) The bronze dragon breathes in one of two ways.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds.\n\n*   **Lightning** The dragon breathes lightning in a 60-foot line that deals 6d12 electricity damage (DC 28 Reflex check save).\n*   **Repulsion Gas** The dragon breathes a 60-foot line of repulsive gas. Each creature in the area must succeed at a DC 28 Will check save or become [[Conditions/Fleeing|Fleeing]] from the dragon for 1 round (or 2 rounds on a critical failure)."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  When the dragon scores a critical hit with a Strike, it recharges its Breath Weapon."

  - name: "Water Mastery"
    desc: " (arcane,water) For up to 30 minutes per day, the dragon, along with allied creatures and vessels within 50 feet, can move at double their normal Speed in water."
 
```

```encounter-table
name: Bronze Dragon (Young)
creatures:
  - 1: Bronze Dragon (Young)
```



Bronze dragons are among the most common of metallic dragons and the most likely to ally with mortals on worthy quests. However, they are naturally scholarly creatures who would rather remain in their lairs studying esoteric lore than go off on a wild adventure. These aloof and stoic dragons also act as preservationists, guarding storehouses of ancient lore from destruction or perversion. Bronze dragons are principled and protective, but while their silver cousins are quick to crusade for justice, bronze dragons prefer to find an important location worthy of their protection and guard it against any attack or unwelcome intrusion.

Bronze dragons' mastery over water and affinity for electricity means they are a boon to sailors caught in thunderstorms. A bronze dragon's enemies quickly discover neither cloudy sky nor turbulent sea provides shelter from their wrath. Bronze dragons lair along shorelines, often in partially submerged sea caves.

While all dragons keep hoards of treasure, the hoard of a bronze dragon more resembles a vast library-with the shelves kept carefully above the waterline, of course. In addition to their collections of esoteric lore, bronze dragons keep treasures associated with the sea, such as beautiful scrimshaw, flawless pearls, and equipment inlaid with mother-of-pearl and abalone shell.

* * *

Paragons of virtue, nobility, and grace, metallic dragons are benevolent entities revered as mythic beings akin to gods in both their power and majesty. Few have ever seen a metallic dragon firsthand, but tales of their intervention in mortals' lives-and of their passing-always spread far and wide. Named for the way their scales resemble the shining metals humanoids use in commerce, warfare, and industry, these immense beings are diverse in their interests and abilities, and they don't seem to mind being associated with such mundane materials. After all, to compare a gold dragon to a gold coin is like comparing an ocean to a glass of water-though they may seem similar at first glance, the raw power, breadth, and grandeur of one simply overwhelms the other.

In addition to metallic dragons and their chromatic counterparts, other types of dragons roam the world and the rest of the multiverse. In the legendary lands of Tian Xia on the other side of the globe are the imperial dragons, serpentine beings who protect the cosmic balance and defend their ancient homeland. Outside the Material Plane, primal dragons such as the domineering brine dragon and reclusive cloud dragon shape the nature and goings-on of the Elemental Planes. Countless other types of dragons are sure to exist, including dragons on far-flung planes of existence and, it is rumored, primeval dragons who soar between the stars.
