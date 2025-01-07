---
title: "Forest Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5sp4mn7KPT95YZP5" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Forest Dragon (Adult, Spellcaster)"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Forest Dragon (Adult, Spellcaster)"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[plant]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +27, Deception: +24, Intimidation: +26, Nature: +25, Stealth: +21, Survival: +23"
abilityMods: [7, 3, 4, 3, 5, 4]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +25, __Ref__ +22, __Will__ +27; +1 status to all saves vs. magic"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  paralyzed,  poison,  sleep; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Countered by Metal"
    desc: "  If the forest dragon takes damage from a metal item, they lose woodland stride and [[Spells/Vanishing Tracks|Vanishing Tracks]] until the end of their next turn."

  - name: "Fed by Water"
    desc: "`pf2:r` (healing,primal) **Frequency** once per hour\n\n**Trigger** The forest dragon is targeted with a water spell or effect\n* * *\n\n**Effect** The forest dragon gains 35 temporary Hit Points."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 32 Will check\n\nAnimals, fungi, and plants take a -2 circumstance penalty to the save.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (magical, reach 15 feet)\n__Damage__  3d10 + 13 piercing 2d6 poison"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, magical, reach 10 feet)\n__Damage__  3d8 + 13 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+29 (magical, reach 25 feet)\n__Damage__  3d8 + 13 bludgeoning plus grab"

  - name: "Primal Prepared Spells"
    desc: "DC 34, attack +28; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_, _[[Spells/Purple Worm Sting|Purple Worm Sting]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Moon Frenzy|Moon Frenzy]]_, _[[Spells/Nature's Pathway|Tree Stride]]_; __4th __  _[[Spells/Vapor Form|Gaseous Form]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Solid Fog|Solid Fog]]_; __3rd __  _[[Spells/Animal Vision|Animal Vision]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __  _[[Spells/Animal Messenger|Animal Messenger]]_, _[[Spells/Darkness|Darkness]]_, _[[Spells/Water Breathing|Water Breathing]]_; __1st __  _[[Spells/Create Water|Create Water]]_, _[[Spells/Goblin Pox|Goblin Pox]]_, _[[Spells/Pest Form|Pest Form]]_\n__Cantrips__  __(6th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Primal Innate Spells"
    desc: "DC 34, attack +26; __4th __  _[[Spells/Entangling Flora|Entangle]]_, _[[Spells/One with Plants|Tree Shape (See Forest Shape)]]_\n__Cantrips__  __(4th)__ _[[Spells/Know the Way|Know Direction]]_\n__Constant__  __(1st)__ _[[Spells/Vanishing Tracks|Pass Without Trace (Forest Terrain Only)]]_"

  - name: "Rituals"
    desc: "_Commune with Nature_, _Plant Growth_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (primal) The dragon unleashes a swarm of insects that deals 14d6 piercing damage in a 40-foot cone (DC 34 Reflex check save) before dispersing.\n\nA creature that critically fails is [[Conditions/Stunned|Stunned 2]] from the insects' venom; this is a poison effect.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "Draining Blight"
    desc: "`pf2:2` (healing,primal,void) **Frequency** once per day\n* * *\n\n**Effect** The dragon draws moisture from the living creatures surrounding them, using the energy to heal their own wounds. Each living creature in a 30-foot emanation takes 7d10 void damage (DC 34 Fortitude check save). Creatures made entirely of water and plant creatures use the outcome one degree of success worse than they rolled. The dragon regains Hit Points equal to half of the highest damage a single creature takes from this effect.\n\nIn addition, all non-creature plant life in the area withers and dies, eliminating non-magical undergrowth and any resulting difficult terrain, cover, and concealment. Water is also consumed in the same way, typically lowering any standing body of water fully within the area by 1 foot."

  - name: "Forest Shape"
    desc: "  When casting [[Spells/One with Plants|One with Plants]], a forest dragon can become a tree of the same size and age as themself."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d8+10 bludgeoning, DC 34 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Woodland Stride"
    desc: "  The forest dragon ignores difficult terrain and greater difficult terrain from non-magical foliage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Forest Dragon (Adult, Spellcaster)
creatures:
  - 1: Forest Dragon (Adult, Spellcaster)
```



Forest dragons oversee the endless growth of nature, protect it from plunder, and reclaim ruins for the wilderness. Some say these dragons jealously hoard nature's bounty for themselves while seeing everyone else who tries to benefit from nature as thieves and poachers. They loathe the progress of technology and civilization, preferring the company of monsters and animals.

Forest dragons are their forests in a literal sense. Over time, their hair becomes mossy, their hide toughens like bark, and small insects or animals live within them.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
