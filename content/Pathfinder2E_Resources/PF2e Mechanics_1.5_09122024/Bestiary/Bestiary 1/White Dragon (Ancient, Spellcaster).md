---
title: "White Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LbCVcHSkU4okZaOI" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "White Dragon (Ancient, Spellcaster)"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "White Dragon (Ancient, Spellcaster)"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[dragon]]
trait_04: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Arcana: +23, Athletics: +31, Intimidation: +28, Stealth: +26"
abilityMods: [8, 3, 7, 2, 3, 3]
speed: 40 feet,  climb 40 feet,  fly 160 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +30, __Ref__ +26, __Will__ +24; +1 status to all saves vs. magic"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Immunities__  cold,  paralyzed,  sleep; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

  - name: "Snow Vision"
    desc: "  Snow doesn't impair a white dragon's vision; it ignores concealment from snowfall."

abilities_mid:
  - name: ""
  - name: "Blizzard"
    desc: " (arcane,aura,cold) 50 feet. After the dragon uses its Breath Weapon, a fierce blizzard of blinding snow surrounds its body for 1 round. Everything in the aura is difficult terrain for other creatures that are on the ground, climbing, or flying. The blowing snow also makes all creatures in the area [[Conditions/Concealed|Concealed]]. While the blizzard rages, the dragon's dragon chill extends to the full area of the blizzard.\n\n[[Bestiary Effects/Effect_ Draconic Breath Weapon Aura|Effect: Draconic Breath Weapon Aura]]"

  - name: "Dragon Chill"
    desc: " (arcane,aura,cold) 10 feet. 3d6 cold damage (DC 34 Reflex check save)"

  - name: "Freezing Blood"
    desc: "`pf2:r` (arcane,cold) **Trigger** An adjacent creature deals piercing or slashing damage to the dragon.\n* * *\n\n**Effect** The dragon's blood sprays on the creature, dealing 3d6 cold damage. A creature that takes cold damage in this way is [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+31 (cold, magical, reach 15 feet)\n__Damage__  3d12 + 16 piercing 3d6 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+31 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 16 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+29 (magical, reach 20 feet)\n__Damage__  2d10 + 14 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 36, attack +28; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_, _[[Spells/Dominate|Dominate]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Chromatic Wall|Chromatic Wall]]_, _[[Spells/Magic Passage|Passwall]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Resist Energy|Resist Energy]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 36, attack +28; __6th __  _[[Spells/Wall of Ice|Wall of Ice (At Will)]]_; __2nd __  _[[Spells/Mist|Obscuring Mist (At Will)]]_; __1st __  _[[Spells/Gust of Wind|Gust of Wind (At Will)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,cold) The dragon breathes a cloud of frost that deals 16d6 cold damage in a 50-foot cone (DC 36 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Ground Slam"
    desc: "`pf2:1`  The dragon slams into the ground. It can do this if it's on the ground or Flying within 10 feet of the ground. Each creature on the ground within 10 feet must succeed at a DC 37 Reflex check save or fall [[Conditions/Prone|Prone]] and take 5d6 bludgeoning damage.\n\nThe dragon can then Step."

  - name: "Ice Climb"
    desc: "  A white dragon can climb on ice as though it had the listed climb Speed. It ignores difficult terrain and greater difficult terrain from ice and snow and doesn't risk falling when crossing ice."

  - name: "Shape Ice"
    desc: "`pf2:2` (arcane,water) The dragon reshapes a cube of ice or snow it touches, up to 10 feet across. Any creature standing atop the ice must succeed at a DC 15 Reflex check save or DC 15 Acrobatics check check.\n\nOn a failure, the creature falls [[Conditions/Prone|Prone]] atop the ice; on a critical failure, it falls off the ice entirely and is also prone."
 
```

```encounter-table
name: White Dragon (Ancient, Spellcaster)
creatures:
  - 1: White Dragon (Ancient, Spellcaster)
```



The most feral and least intelligent of all the chromatic dragons, white dragons are brutish, predatory, and chiefly motivated by self-preservation. Nearly all other dragons look down on white dragons as hopelessly hotheaded and dull, though this does not make them any less dangerous-in fact, it may mean the opposite. It's nearly impossible to treat with white dragons, not because they lack the capacity to do so, but because they just don't care to. They are as difficult to deal with as they are quick to anger, and they become incensed at almost anything. When a white dragon does speak, it spews threats, inane jokes, and incoherent babbling as a prelude to attacking-and when the attack comes, it's bloody and relentless.

Thankfully, white dragons prefer very cold, remote locations that are far from people. Dwelling on glacial mountaintops or in ice caverns beneath forbidding tundra, they treat the lands around them as their own personal hunting grounds. They fly out to feed or terrorize other creatures, especially those who trespass near the dragon's territory, then bring any treasure back to be displayed in icy niches in their lairs. They collect all kinds of valuables, with a slight preference for items with high utility-such as tools, trade goods, and fine food-over coins or jewels. The ability to shape ice lets white dragons rearrange their lairs exactly to their specifications, and they take great pride in how they've decorated their homes over the years.

* * *

While there are many types of dragons, from the powerful planar dragons to the strange esoteric dragons, few dragon varieties are as well-known and as rightly feared as the chromatic dragons. Differentiated by the hue of their scales, each color of dragon unleashes its own flavor of murderous cruelty-be it by claw, tooth, or breath-and unlike most creatures, dragons only become more powerful as they age. Their lust for treasure, food, bloodshed, and control are legendary. Physically powerful with egos to match, these dragons are often morally depraved and act as criminal masterminds, vicious tyrants, or voracious raiders.
