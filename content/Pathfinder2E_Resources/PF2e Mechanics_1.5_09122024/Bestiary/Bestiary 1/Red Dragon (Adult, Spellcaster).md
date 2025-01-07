---
title: "Red Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9dBH6f7tKrm4oAtS" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Red Dragon (Adult, Spellcaster)"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Red Dragon (Adult, Spellcaster)"
level: "Creature 14"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Arcana: +25, Athletics: +29, Deception: +25, Diplomacy: +25, Intimidation: +27, Stealth: +23"
abilityMods: [7, 3, 6, 3, 4, 5]
speed: 50 feet,  fly 150 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +28, __Ref__ +25, __Will__ +26; +1 status to all saves vs. magic"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a red dragon's vision; it ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Dragon Heat"
    desc: " (arcane,aura,fire) 5 feet. 3d6 fire damage (DC 30 Reflex check save)"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 33 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (fire, magical, reach 15 feet)\n__Damage__  3d12 + 15 piercing 2d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+27 (magical, reach 20 feet)\n__Damage__  3d12 + 13 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+27 (agile, magical, reach 15 feet)\n__Damage__  2d10 + 13 slashing"

  - name: "Arcane Prepared Spells"
    desc: "DC 35, attack +29; __6th __  _[[Spells/Teleport|Teleport]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __  _[[Spells/Cloak of Colors|Cloak of Colors]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Mountain Resilience|Stoneskin]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Mind Reading|Mind Reading]]_; __2nd __  _[[Spells/Translate|Comprehend Language]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Resist Energy|Resist Energy]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Command|Command]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(6th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Message|Message]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 35, attack +27; __4th __  _[[Spells/Suggestion|Suggestion]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The dragon breathes a blast of flame that deals 15d6 fire damage in a 50-foot cone (DC 36 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."
 
```

```encounter-table
name: Red Dragon (Adult, Spellcaster)
creatures:
  - 1: Red Dragon (Adult, Spellcaster)
```



The largest and most powerful of the chromatic dragons, red dragons are a menace to civilizations everywhere, and their strength is rivaled only by their arrogance. Red dragons see themselves as regents and overlords of all dragonkind. With their crowns of crimson spikes and their command of blistering frame, this is no haughty boast in their eyes-only unquestioned fact.

Red dragons don't deign to speak with lesser creatures; they simply dominate and burn, enslaving weaker creatures to act as servants and to look after their lairs while the dragons slumber away. They take pleasure in dominating these creatures, and they demand tribute from their supplicants. Those who anger or disappoint end up eaten or reduced to ash. They command their enslaved minions to constantly build onto their lairs, carving out new tunnels and designing cunning traps that ensure the dragon's security.

Driven by their arrogance, red dragons are the most likely of the chromatic dragons to ravage settlements. They want the world to see them in their rightful place as powerful tyrants, and they delight in threatening all other creatures. They have no qualms about bullying, manipulating, or killing to complete their goals-or simply intimidating others through a public display of brutality and dominance.

As legendary as the brutishness of red dragons is the magnificence of their hoards of gold. Their lairs are often situated in dangerous places, with volcanoes being a favorite spot, as they find them foreboding and the constant warmth is comfortable. No matter the locale, red dragons sleep on a litter of coins and other treasures, which they zealously guard. Sometimes, the dragon's internal heat causes these precious metals to fuse together.

* * *

While there are many types of dragons, from the powerful planar dragons to the strange esoteric dragons, few dragon varieties are as well-known and as rightly feared as the chromatic dragons. Differentiated by the hue of their scales, each color of dragon unleashes its own flavor of murderous cruelty-be it by claw, tooth, or breath-and unlike most creatures, dragons only become more powerful as they age. Their lust for treasure, food, bloodshed, and control are legendary. Physically powerful with egos to match, these dragons are often morally depraved and act as criminal masterminds, vicious tyrants, or voracious raiders.
