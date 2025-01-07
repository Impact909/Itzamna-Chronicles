---
title: "Brass Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hYMJ6CbN84b60bFb" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/fire
  - pf2e/creature/type/good
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Brass Dragon (Adult, Spellcaster)"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Brass Dragon (Adult, Spellcaster)"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[fire]]
trait_04: [[good]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 30 Feet"
languages: "Common, Draconic, Fey, Gnomish, Halfling, Sussuran; speak with animals"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +23, Deception: +20, Diplomacy: +20, Society: +19"
abilityMods: [6, 3, 5, 2, 4, 3]
speed: 50 feet,  burrow 30 feet,  fly 120 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +22, __Ref__ +20, __Will__ +21; +1 status to all saves vs. magic"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  fire,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 28 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** The dragon is targeted with an attack\n* * *\n\n**Effect** The dragon raises its wing, gaining a +2 circumstance bonus to AC against the triggering attack. If the dragon is flying, it descends 10 feet after the attack is complete."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (fire, magical, reach 10 feet)\n__Damage__  2d10 + 12 piercing 2d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, magical)\n__Damage__  2d10 + 12 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+22 (magical, reach 10 feet)\n__Damage__  1d12 + 10 slashing"

  - name: "Arcane Prepared Spells"
    desc: "DC 30, attack +24; __5th __  _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Planar Tether|Dimensional Anchor]]_; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Humanoid Form|Humanoid Form]]_, _[[Spells/Mirror Image|Mirror Image]]_, _[[Spells/Resist Energy|Resist Energy]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Sleep|Sleep]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(5th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 30, attack +22\n__Constant__  __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The brass dragon breathes fire in a 80-foot line that deals 12d6 fire damage (DC 32 Reflex check save).\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "Desert Wind"
    desc: "`pf2:2` (air,arcane,concentrate) **Frequency** three times per day\n* * *\n\n**Effect** The dragon calls upon the desert wind. This has the same effect as [[Spells/Gust of Wind|Gust of Wind]] (DC 30 Fortitude check) but in a 60-foot cone.\n\nA creature that fails its save is also [[Conditions/Blinded|Blinded]] until the end of its next turn (or for 1 minute on a critical failure)."
 
```

```encounter-table
name: Brass Dragon (Adult, Spellcaster)
creatures:
  - 1: Brass Dragon (Adult, Spellcaster)
```



Brass dragons are whimsical tricksters who delight in humor and play. They particularly enjoy conversations with humans and other civilized humanoids, delighting in the naive customs of these diminutive races without showing them haughtiness or scorn. While they may seem merely curious, brass dragons engage in this sort of conversation with the goal of keeping up to date on regional politics so they can anticipate future conflicts. Along the way, they create extensive information networks that begin with their own allies but stretch across all levels of humanoid society-networks which the brass dragon then uses to subtly assist settlements near their lair. Unlike the schemes and manipulations of blue dragons, brass dragons use their informant networks to establish justice and equality.

These carefree dragons value independence and feel that all creatures deserve to live as they please, provided they don't harm others. They are emotional creatures and tend to have short attention spans, sometimes falling victim to depression in their twilight years. To combat this, some brass dragons keep pets and houseplants that they can care for.

Though they may seem childlike in their curiosity concerning mortal affairs, a brass dragon's prowess in battle is no laughing matter. A brass dragon whose territory or allies are threatened is a terrifying foe indeed, quick to shed their innocent guise and unleash their terrifying might upon evildoers.

Most brass dragons live in desert climates, and while they keep their lairs hidden, they often build near humanoid settlements.

* * *

Paragons of virtue, nobility, and grace, metallic dragons are benevolent entities revered as mythic beings akin to gods in both their power and majesty. Few have ever seen a metallic dragon firsthand, but tales of their intervention in mortals' lives-and of their passing-always spread far and wide. Named for the way their scales resemble the shining metals humanoids use in commerce, warfare, and industry, these immense beings are diverse in their interests and abilities, and they don't seem to mind being associated with such mundane materials. After all, to compare a gold dragon to a gold coin is like comparing an ocean to a glass of water-though they may seem similar at first glance, the raw power, breadth, and grandeur of one simply overwhelms the other. In addition to metallic dragons and their chromatic counterparts, other types of dragons roam the world and the rest of the multiverse. In the legendary lands of Tian Xia on the other side of the globe are the imperial dragons, serpentine beings who protect the cosmic balance and defend their ancient homeland. Outside the Material Plane, primal dragons such as the domineering brine dragon and reclusive cloud dragon shape the nature and goings-on of the Elemental Planes. Countless other types of dragons are sure to exist, including dragons on far-flung planes of existence and, it is rumored, primeval dragons who soar between the stars.
