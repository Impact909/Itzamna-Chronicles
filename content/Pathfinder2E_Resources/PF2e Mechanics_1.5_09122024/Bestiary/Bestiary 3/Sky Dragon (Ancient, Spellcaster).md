---
title: "Sky Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CCkNTzfMbGDuoAsb" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/electricity
  - pf2e/creature/type/good
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Sky Dragon (Ancient, Spellcaster)"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sky Dragon (Ancient, Spellcaster)"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[electricity]]
trait_03: [[good]]
trait_04: [[lawful]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Elven, Empyrean, Fey, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +35, Deception: +28, Intimidation: +32, Religion: +34, Society: +26, Stealth: +28, Survival: +28"
abilityMods: [8, 4, 5, 4, 6, 6]
speed: 60 feet,  fly 160 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +31, __Ref__ +28, __Will__ +32; +1 status to all saves vs. magic"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "Mist Vision"
    desc: "  Fog and mist don't impair a sky dragon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from fog and mist."

abilities_mid:
  - name: ""
  - name: "Countered by Fire"
    desc: "  If the sky dragon takes fire damage, the elemental magic of metal within them is tempered. Until the end of their next turn, they take a -1 circumstance penalty to attack rolls and AC, and their jaws Strikes don't deal electricity damage. This limitation ends if the dragon uses Breath Weapon.\n\n[[Bestiary Effects/Effect_ Countered by Fire|Effect: Countered by Fire]]"

  - name: "Fed by Earth"
    desc: " (divine) When a sky dragon is targeted by an earth spell or effect, they leave a cloud of pulverized dust and gravel that swirls in the eddies of the dragon's flight. For 1 minute, the dragon is [[Conditions/Concealed|Concealed]] while flying."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 38 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (magical, reach 20 feet)\n__Damage__  3d10 + 16 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+36 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 16 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+36 (magical, reach 30 feet)\n__Damage__  3d10 + 16 bludgeoning plus grab"

  - name: "Divine Prepared Spells"
    desc: "DC 42, attack +36; __8th __  _[[Spells/Pinpoint|Discern Location]]_, _[[Spells/Divine Aura|Divine Aura]]_; __7th __  _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/Sunburst|Sunburst]]_; __6th __  _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Sacred Form|Righteous Might]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Banishment|Banishment]]_, _[[Spells/Scouting Eye|Prying Eye]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Discern Lies|Discern Lies]]_, _[[Spells/Divine Wrath|Divine Wrath]]_; __3rd __  _[[Spells/Heroism|Heroism]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Wanderer's Guide|Wanderer's Guide]]_; __2nd __  _[[Spells/Augury|Augury]]_, _[[Spells/Translate|Comprehend Language]]_, _[[Spells/Create Food|Create Food]]_, _[[Spells/Dispel Magic|Dispel Magic]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Bless|Bless]]_, _[[Spells/Detect Alignment|Detect Alignment (At Will) (Evil Only)]]_, _[[Spells/Sanctuary|Sanctuary]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +34; __4th __  _[[Spells/Vapor Form|Gaseous Form]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall]]_, _[[Spells/Gust of Wind|Gust of Wind]]_"

  - name: "Rituals"
    desc: "_Atone_, _Consecrate_, _Legend Lore_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,electricity) The dragon shoots a ball of electricity that deals 9d12 electricity damage and 2d12 sonic damage in a 30-foot burst within 60 feet (DC 40 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds.\n* * *\n\nSee divine lightning.\n\n9d12 spirit damage and 2d12 sonic damage (DC 40 Reflex check save) against fiends.\n\n9d12 vitality damage and 2d12 sonic damage (DC 40 Reflex check save) against undead."

  - name: "Divine Lightning"
    desc: " (divine) A good sky dragon who worships a deity channels divine power through its attacks, making them more effective against fiends and undead. Any electricity damage it deals becomes spirit damage against fiends or vitality damage against undead."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d10+11 bludgeoning, DC 40 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Perfected Flight"
    desc: "  A sky dragon can hover in place without spending an action, and they automatically succeed at all Acrobatics checks to [[Actions/Maneuver in Flight|Maneuver in Flight]]."

  - name: "Stunning Electricity"
    desc: "`pf2:2` (divine,electricity,incapacitation) The dragon rapidly coils, then unleashes crackling lightning that deals 5d12 electricity damage in a 60-foot emanation. Each creature in the area must attempt a DC 40 Fortitude check save; regardless of the outcome, the creature then becomes temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** Half damage, and the creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** Full damage, and the creature is [[Conditions/Stunned|Stunned]] for 1 round and can't fly for 4 rounds.\n\n**Critical Failure** Double damage, and the creature is stunned for 2 rounds and can't fly for 1 minute.\n* * *\n\nSee divine lightning.\n\n5d12 spirit damage (DC 40 Reflex check save) against fiends.\n\n5d12 vitality damage (DC 40 Reflex check save) against undead."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sky Dragon (Ancient, Spellcaster)
creatures:
  - 1: Sky Dragon (Ancient, Spellcaster)
```



Sky dragons live above the clouds near the summits of mountains. They maintain a strong religious tradition, a unique practice among imperial dragons that sets them apart as much as their wings do. Desperate souls risk steep cliffs and loose snow to seek these dragons' counsel, and most sky dragons gladly help those who make the journey, but they expel any express hostilities or badger without hesitation.

The sky dragon's wings aren't true wings, but long fins fused to their forearms; their scales also form only very slowly. Young dragons coil tightly in their lairs as they absorb minerals that color and harden their scales. Even adults often wrap around pillars out of habit.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
