---
title: "Black Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LXcKYcW0xITkdoIF" 
tags:
  - pf2e/creature/type/acid
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Black Dragon (Adult, Spellcaster)"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Black Dragon (Adult, Spellcaster)"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[acid]]
trait_02: [[amphibious]]
trait_03: [[chaotic]]
trait_04: [[dragon]]
trait_05: [[evil]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Arcana: +19, Athletics: +24, Deception: +20, Intimidation: +20, Stealth: +20"
abilityMods: [7, 3, 5, 2, 3, 3]
speed: 50 feet,  fly 120 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +18, __Will__ +21; +1 status to all saves vs. magic"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  acid,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 28 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Tail Lash"
    desc: "`pf2:r`  **Trigger** A creature within reach of the dragon's tail takes an action to Strike or attempt a skill check\n* * *\n\n**Effect** The dragon Strikes with its tail at the triggering creature at a -2 penalty. If it hits, the creature takes a -2 circumstance penalty to the triggering roll.\n\n[[Bestiary Effects/Effect_ Tail Lash|Effect: Tail Lash]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (acid, magical, reach 10 feet)\n__Damage__  2d12 + 13 piercing 2d6 acid"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile, magical)\n__Damage__  2d10 + 13 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+23 (magical, reach 15 feet)\n__Damage__  2d12 + 11 bludgeoning"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+23 (magical, reach 10 feet)\n__Damage__  1d10 + 11 piercing"

  - name: "Arcane Prepared Spells"
    desc: "DC 30, attack +24; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Mariner's Curse|Mariner's Curse]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Blur|Blur]]_, _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Invisibility|Invisibility]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(5th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 30, attack +24; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (acid,arcane) The dragon breathes a spray of acid that deals 12d6 acid damage in an 80-foot line (DC 30 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Corrupt Water"
    desc: "`pf2:1` (arcane,concentrate) **Frequency** Once per day\n* * *\n\n**Effect** The dragon permanently befouls 10 cubic feet of liquid within 90 feet. The liquid becomes undrinkable and unable to support water-breathing life.\n\nThis destroys liquid magic or alchemical items if they're of a lower level than the dragon (a creature can attempt a DC 28 Will check save to protect liquids in its possession). This doesn't affect liquids in a creature's body."
 
```

```encounter-table
name: Black Dragon (Adult, Spellcaster)
creatures:
  - 1: Black Dragon (Adult, Spellcaster)
```



Murderous tyrants of marshes, swamps, bogs, and fens, black dragons terrorize their domains with intense fervor. Gleefully sadistic, they rule their fetid principalities from a deep cave or otherwise isolated part of the swamp with a mix of lightning-quick raids and subterfuge. Their hatred for other creatures is as acidic as their breath weapons, and they rarely tolerate even other dragons of their kind-except perhaps to mate or temporarily collaborate to take down a mutual enemy.

Black dragons are amphibious-although they breathe air, their gills also allow them to breathe water. Their frills and fins make them accomplished swimmers, well suited to their wetland environments and submerged lairs. They're immune to the fetid water that comes as a result of their magical ability to corrupt water.

Black dragon lairs are as foul as their souls. The floors are littered with rotting meat, and plundered treasures line the muck and slime of their dank caves amid twisted roots and creepers. Such places are often crawling with pests, snakes, and slimes. Though they claim natural caverns when they can, they make do with areas of dense, twisted vegetation within a swamp. Black dragon treasure hoards primarily consist of gems and expensive glass work, as valuables of softer substance can't survive the dragon's acidic presence.

* * *

While there are many types of dragons, from the powerful planar dragons to the strange esoteric dragons, few dragon varieties are as well-known and as rightly feared as the chromatic dragons. Differentiated by the hue of their scales, each color of dragon unleashes its own flavor of murderous cruelty-be it by claw, tooth, or breath-and unlike most creatures, dragons only become more powerful as they age. Their lust for treasure, food, bloodshed, and control are legendary. Physically powerful with egos to match, these dragons are often morally depraved and act as criminal masterminds, vicious tyrants, or voracious raiders.
