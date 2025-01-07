---
title: "Blue Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6qlqXNJeRimhVcrY" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/electricity
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Blue Dragon (Ancient, Spellcaster)"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Blue Dragon (Ancient, Spellcaster)"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[electricity]]
trait_03: [[evil]]
trait_04: [[lawful]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Jotun, Pyric, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Arcana: +33, Deception: +35, Diplomacy: +35, Intimidation: +33, Society: +35, Stealth: +28, Survival: +29"
abilityMods: [7, 4, 6, 7, 5, 7]
speed: 50 feet,  burrow 30 feet,  fly 200 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +32, __Ref__ +30, __Will__ +33; +1 status to all saves vs. magic"
hp: 370
health:
  - name: ""
  - name: HP
    desc: "370; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "Sound Imitation"
    desc: "  The dragon can mimic any sound it has heard. To do so, it must succeed at a Deception check with a +4 circumstance bonus."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 39 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** The dragon is targeted with an attack\n* * *\n\n**Effect** The dragon raises its wing, gaining a +2 circumstance bonus to AC against the triggering attack. If the dragon is Flying, it descends 10 feet after the attack is complete."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (electricity, magical, reach 20 feet)\n__Damage__  3d10 + 15 piercing 2d12 electricity"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (magical, reach 25 feet)\n__Damage__  3d10 + 13 bludgeoning"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+33 (magical, reach 20 feet)\n__Damage__  2d10 + 13 piercing"

  - name: "Arcane Prepared Spells"
    desc: "DC 41, attack +35; __8th __  _[[Spells/Disappearance|Disappearance]]_, _[[Spells/Quandary|Maze]]_, _[[Spells/Hidden Mind|Mind Blank]]_; __7th __  _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/Spell Turning|Spell Turning]]_; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_, _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Mislead|Mislead]]_; __5th __  _[[Spells/Chromatic Wall|Chromatic Wall]]_, _[[Spells/False Vision|False Vision]]_, _[[Spells/Illusory Scene|Illusory Scene]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_; __3rd __  _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Hypnotize|Hypnotic Pattern]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Mirror Image|Mirror Image]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Phantasmal Minion|Unseen Servant]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 43, attack +35; __8th __  _[[Spells/Mirage|Hallucinatory Terrain (At Will)]]_, _[[Spells/Illusory Creature|Illusory Creature (At Will)]]_, _[[Spells/Illusory Object|Illusory Object (At Will)]]_, _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_; __7th __  _[[Spells/Project Image|Project Image (See Mirage)]]_; __1st __  _[[Spells/Create Water|Create Water (At Will) (See Desert Thirst)]]_\n__Cantrips__  __(9th)__ _[[Spells/Ghost Sound|Ghost Sound]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,electricity) The dragon breathes lightning that deals 12d12 electricity damage in a 120-foot line (DC 40 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds.\n* * *\n\nEach time the dragon uses Breath Weapon, a 20-foot-radius storm cloud appears 80 feet above a point of the dragon's choosing along the Breath Weapon's path. Clouds last for 10 minutes and allow the dragon to use Storm Breath."

  - name: "Desert Thirst"
    desc: " (arcane) When casting [[Spells/Create Water|Create Water]], the dragon can attempt to destroy liquid instead of creating it, turning an equal amount of liquid into sand. This destroys liquid magic or alchemical items if they're of a lower level than the dragon (a creature can attempt a DC 37 Will check save to protect all liquids in its possession). This doesn't affect the liquids in a creature's body."

  - name: "Mirage"
    desc: "  Whenever the dragon uses Breath Weapon while the illusory image from its innate [[Spells/Project Image|Project Image]] spell persists, it can cause the Breath Weapon to originate from itself or the image."

  - name: "Storm Breath"
    desc: "`pf2:1` (arcane,concentrate,electricity) **Frequency** Once per round\n\n**Requirements** A storm cloud created by Breath Weapon is within 500 feet, and the dragon can see the cloud.\n* * *\n\n**Effect** The dragon calls down a lightning bolt from a storm cloud created by its Breath Weapon. This creates a vertical line of lightning to the ground that deal 6d12 electricity damage to all enemies in its path (DC 40 Reflex check save)."
 
```

```encounter-table
name: Blue Dragon (Ancient, Spellcaster)
creatures:
  - 1: Blue Dragon (Ancient, Spellcaster)
```



Blue dragons are the sleek and poised cosmopolitans of the chromatic dragons. Their brand of evil is organized, manipulative, and regal. Blue dragons often lair near or within cities and set out to bend the population to their will and gather hordes of servants. These dragons love spinning webs of conspiracy. A blue dragon's lackeys typically don't even realize that they serve a dragon, but instead think the protection money, tariffs, or taxes they are amassing is treasure for a cruel but legitimate master. In some ways, blue dragons even see their servants as a living hoard and value them like treasure. These dragons have been known to use these tactics even with their own chromatic cousins.

Not all blue dragons work clandestinely. Some lord over desert tribes and hill people like vengeful gods, demanding both tribute and worship. No matter how blue dragons manage their underlings, their bearing is regal and their lairs palatial; they're universally intolerant of insubordination, incompetence, and embezzlement, and punish perpetrators with murderous efficiency.

Blue dragons are also known for their use and mastery of illusion magic. They make use of illusions to augment their manipulations and bewilder their foes in battle. Blue dragons also have some control over water, but use this ability to destroy water, something quite dangerous for those who encounter them in their desert lairs.

The ideal lair for a blue dragon contains multiple passages, rooms, and secret chambers. As social creatures, blue dragons prefer to host guests in comfort-but their dwellings should not be so public that just anyone can come calling. A force of guards keeps out intruders, and clever illusions conceal the edifice from prying eyes. Rather than a pile of coins or gems, a blue dragon's true hoard is the rich furnishings in its citadel- expensive art, ornate furniture, and architectural marvels.

* * *

While there are many types of dragons, from the powerful planar dragons to the strange esoteric dragons, few dragon varieties are as well-known and as rightly feared as the chromatic dragons. Differentiated by the hue of their scales, each color of dragon unleashes its own flavor of murderous cruelty-be it by claw, tooth, or breath-and unlike most creatures, dragons only become more powerful as they age. Their lust for treasure, food, bloodshed, and control are legendary. Physically powerful with egos to match, these dragons are often morally depraved and act as criminal masterminds, vicious tyrants, or voracious raiders.
