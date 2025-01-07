---
title: "Diabolic Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sGUtj8sZbdLqulOh" 
tags:
  - pf2e/creature/type/divine
  - pf2e/creature/type/dragon
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Diabolic Dragon (Ancient, Spellcaster)"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Diabolic Dragon (Ancient, Spellcaster)"
level: "Creature 20"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[divine]]
trait_02: [[dragon]]
trait_03: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Empyrean, Necril, Pyric, Aklo, Chthonian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +38, Deception: +34, Diplomacy: +36, Intimidation: +34, Religion: +35, Society: +33, Thievery: +33, Hell Lore: +33, Legal Lore: +35"
abilityMods: [10, 5, 8, 5, 7, 8]
speed: 70 feet,  fly 180 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +36, __Ref__ +32, __Will__ +32; +2 status to all saves vs. divine"
hp: 390
health:
  - name: ""
  - name: HP
    desc: "390; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair the dragon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet DC 40 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Hell's Sting"
    desc: "`pf2:r` (divine,mental,unholy) **Trigger** The dragon is critically hit with a melee attack\n* * *\n\n**Effect** The dragon channels the rancor of Hell back through the body of their foe, overwhelming it with an infernal assault on the mind. The triggering creature takes 10d6 mental damage with a DC 42 Will check save. Holy creatures use an outcome one degree of success worse than they roll on their saving throw."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (fire, magical, reach 10 feet, unholy)\n__Damage__  2d6 fire 4d12 + 18 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+30 (agile, fire, magical, unholy)\n__Damage__  2d6 fire plus improved-grab 4d8 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+36 (fire, magical, reach 15 feet, unholy)\n__Damage__  4d8 + 18 bludgeoning plus improved-knockdown 2d6 fire plus improved-knockdown"

  - name: "Divine Prepared Spells"
    desc: "DC 42, attack +38; __9th __  _[[Spells/Massacre|Massacre]]_, _[[Spells/Wails of the Damned|Wails of the Damned]]_; __8th __  _[[Spells/Canticle of Everlasting Grief|Canticle of Everlasting Grief]]_, _[[Spells/Pinpoint|Pinpoint]]_; __7th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Execute|Execute]]_, _[[Spells/Planar Seal|Planar Seal]]_; __6th __  _[[Spells/Blessed Boundary|Blessed Boundary]]_, _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Banishment|Banishment]]_, _[[Spells/Sending|Sending]]_, _[[Spells/Truespeech|Truespeech]]_; __4th __  _[[Spells/Dispelling Globe|Dispelling Globe]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Planar Tether|Planar Tether]]_, _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Chilling Darkness|Chilling Darkness]]_; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Darkness|Darkness]]_, _[[Spells/Translate|Translate]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Harm|Harm]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Sigil|Sigil]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Divine Immolation|Divine Immolation (At Will)]]_, _[[Spells/Falling Stars|Falling Stars (Fire Only)]]_, _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_; __8th __  _[[Spells/Summon Fiend|Summon Fiend (Phistophilus Only, At Will)]]_; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (At Will, Self Only)]]_\n__Cantrips__  __(10th)__ _[[Spells/Ignition|Ignition]]_"

  - name: "Diabolic Fire"
    desc: "  Any fire damage that a diabolic dragon deals, including fire damage from spells, is imbued with the unholy power of Hell to scorch the spirit as well. A creature takes spirit damage instead of fire damage if that would be more detrimental to the creature (as determined by the GM). A diabolic dragon is immune to the diabolic fire of other diabolic dragons, the fire from divine immolation, and similar effects."

  - name: "Hellfire Breath"
    desc: "`pf2:2` (divine,fire,unholy) The dragon unleashes a blast of infernal fire that deals 21d6 fire damage in a 60-foot cone (DC 42 Reflex check save).\n\nThe dragon can't use Hellfire Breath again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Diabolic Dragon (Ancient, Spellcaster)
creatures:
  - 1: Diabolic Dragon (Ancient, Spellcaster)
```



Hell, according to some theologians, is a living entity in and of itself. Diabolic dragons, these scholars argue, are just extensions of the plane, living creatures that break off from Hell to enact its will. Whether this is true or whether diabolical dragons are simply the reborn souls of dragons sent to Hell, the fact remains that these dragons are powerful, cunning, and tyrannical. Every diabolic dragon's goal is to further Hell's will, though how this happens can vary. Regardless of their goals, these dragons always approach newcomers with an unsettling calmness.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
