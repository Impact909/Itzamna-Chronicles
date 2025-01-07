---
title: "Elder Sphinx"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GgHGZAUNavEzADAN" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Elder Sphinx"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Elder Sphinx"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Truesight"
languages: "Common, Draconic, Sphinx; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Deception: +28, Diplomacy: +30, Intimidation: +28, Occultism: +30, Bardic Lore: +32"
abilityMods: [8, 5, 6, 8, 9, 6]
speed: 40 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +28, __Ref__ +25, __Will__ +31"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300"
abilities_top:
  - name: ""

  - name: "Bardic Lore"
    desc: "  Sphinxes are naturally curious, and their love of puzzles and mysteries leads them to gather information on a broad range of topics. Sphinxes have the [[Feats/Bardic Lore|Bardic Lore]] bard feat, allowing them to [[Actions/Recall Knowledge|Recall Knowledge]] on any topic."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile)\n__Damage__  3d8 + 16 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Clairaudience|Clairaudience (At Will)]]_, _[[Spells/Clairvoyance|Clairvoyance (At Will)]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Read Omens|Read Omens (At Will)]]_, _[[Compendium.pf2e.spells-srd.Item.OyFCwQuw8XRazsNr|Remove Curse (At Will)]]_, _[[Spells/Shape Stone|Shape Stone (See Idols of Stone)]]_, _[[Spells/Truesight|True Seeing]]_, _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Commune_, _Legend Lore_"

  - name: "Guardian Monolith"
    desc: "`pf2:2`  The elder sphinx transforms their body into stone or back to flesh.\n\nIn stone form, the sphinx is [[Conditions/Paralyzed|Paralyzed]] but has Hardness 14 and gains immunity to bleed, clumsy, disease, drained, enfeebled, fatigued, petrified, poison, sickened, void damage, and wounded. They don't age or require food, water, or sleep. They can perceive their surroundings and cast their innate spells.\n\n[[Spells/Stone to Flesh|Stone to Flesh]] turns the elder sphinx from stone form back to flesh, and [[Spells/Petrify|Petrify]] turns it from flesh form to stone form."

  - name: "Idols of Stone"
    desc: "  When the sphinx casts [[Spells/Shape Stone|Shape Stone]], they can shape the stone into a magical duplicate of themself.\n\nWhen they cast [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Locate|Locate]], or [[Spells/Ventriloquism|Ventriloquism]], they can make the effect come from any duplicate, instead of themself.\n\nThe elder sphinx can concentrate for 1 minute to transfer their consciousness to any duplicate; the sphinx is then in their stone form from Guardian Monolith in that statue.The sphinx can have no more than four duplicate statues at a time. Casting _shape stone_ at that point causes the oldest duplicate to crumble to dust."

  - name: "Pose a Riddle"
    desc: "`pf2:2` (incapacitation,linguistic,mental,occult) **Frequency** once per 10 minutes\n* * *\n\nThe sphinx recites a riddle and compels up to 10 creatures within 30 feet to answer (DC 37 Will check save). The GM either runs the riddle out of character by timing the players' attempts, or picks an appropriate associated skill for the riddle, such as Religion for a riddle involving divine mysteries.\n\nThe sphinx gains a +2 circumstance bonus to attack rolls and damage rolls against any creature that answers incorrectly even once. This bonus lasts for 1 day.\n* * *\n\n**Critical Success** The creature is unaffected, but it can choose to try to help solve the riddle.\n\n**Success** The creature attempts to answer the riddle, each round spending at least one action attempting a [[Actions/Recall Knowledge|Recall Knowledge]] check with the chosen skill (or working on the answer, if using an out of game riddle). This lasts for 1 minute, until the creature successfully answers the riddle, or until an enemy takes a hostile action against the creature, whichever comes first.\n\n**Failure** As success but the creature must spend at least two actions each round attempting to answer.\n\n**Critical Failure** As failure, but up to 1 hour."

  - name: "Pounce"
    desc: "`pf2:1`  The elder sphinx Strides and makes a Strike at the end of that movement. If they began this action [[Conditions/Hidden|Hidden]], they remain hidden until after the attack."

  - name: "Warding Glyph"
    desc: "  Once per day, an elder sphinx can create a magical symbol as though casting a heightened [[Spells/Rune Trap|Rune Trap]]. The sphinx usually shapes it to the form of a riddle and sets the password to the answer.\n\nA creature that doesn't speak the password must succeed at a DC 37 Will check save or be affected by one of the following spells, chosen by the sphinx when creating the symbol:\n\n*   [[Spells/Visions of Danger|Visions of Danger]] (7th)\n*   [[Spells/Spirit Blast|Spirit Blast]] (6th)\n*   [[Spells/Synaptic Pulse|Synaptic Pulse]] (5th)\n*   [[Spells/Charm|Charm]] (4th)\n*   [[Spells/Fear|Fear]] (3rd)\n*   [[Spells/Phantom Pain|Phantom Pain]] (3rd)\n*   [[Spells/Sleep|Sleep]] (3rd)\n\nThe sphinx learns the identity of any creature that answers the riddle and tends to be friendly to them."
 
```

```encounter-table
name: Elder Sphinx
creatures:
  - 1: Elder Sphinx
```



Towering over their kin, elder sphinxes are the pharaonic masters of their kind. They crave solitude in eternal vigil over sacred spaces, where they honor ancient pacts.

* * *

Sphinxes are a family of mystical beings that combine leonine, avian, and usually humanoid features. Though the most common sphinxes are famous on their own merits, the family includes other types of sphinxes as well.
