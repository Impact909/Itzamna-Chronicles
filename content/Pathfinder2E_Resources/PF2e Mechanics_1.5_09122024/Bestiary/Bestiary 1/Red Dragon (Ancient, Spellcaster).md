---
title: "Red Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aoUaoqbvEme2BDAf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Red Dragon (Ancient, Spellcaster)"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Red Dragon (Ancient, Spellcaster)"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Common, Draconic, Dwarven, Jotun, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Arcana: +35, Athletics: +37, Deception: +35, Diplomacy: +35, Intimidation: +37, Stealth: +33"
abilityMods: [9, 5, 8, 5, 6, 7]
speed: 60 feet,  fly 180 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +35, __Ref__ +32, __Will__ +35; +1 status to all saves vs. magic"
hp: 425
health:
  - name: ""
  - name: HP
    desc: "425; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ cold 20"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a red dragon's vision; it ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Dragon Heat"
    desc: " (arcane,aura,fire) 10 feet. 4d6 fire damage (DC 39 Reflex check save)"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 40 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Redirect Fire"
    desc: "`pf2:r` (arcane) **Trigger** A creature within 100 feet casts a fire spell, or a fire spell otherwise comes into effect from a source within 100 feet.\n* * *\n\n**Effect** The dragon makes all the choices to determine the targets, destination, or other effects of the spell, as though it were the caster."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (fire, magical, reach 20 feet)\n__Damage__  4d10 + 17 piercing 3d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+37 (agile, magical, reach 15 feet)\n__Damage__  4d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (magical, reach 25 feet)\n__Damage__  4d10 + 15 slashing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+35 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 15 slashing"

  - name: "Arcane Prepared Spells"
    desc: "DC 42, attack +36; __9th __  _[[Spells/Prismatic Sphere|Prismatic Sphere]]_; __8th __  _[[Spells/Pinpoint|Discern Location]]_, _[[Spells/Hidden Mind|Mind Blank]]_, _[[Spells/Prismatic Wall|Prismatic Wall]]_; __7th __  _[[Spells/Fiery Body|Fiery Body]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_, _[[Spells/Reverse Gravity|Reverse Gravity]]_; __6th __  _[[Spells/Teleport|Teleport]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __  _[[Spells/Cloak of Colors|Cloak of Colors]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Mountain Resilience|Stoneskin]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Mind Reading|Mind Reading]]_; __2nd __  _[[Spells/Translate|Comprehend Language]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Resist Energy|Resist Energy]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Command|Command]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(9th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Message|Message]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 42, attack +34; __8th __  _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_; __4th __  _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The dragon breathes a blast of flame that deals 20d6 fire damage in a 60-foot cone (DC 42 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Manipulate Flames"
    desc: "`pf2:1` (arcane,concentrate) The red dragon attempts to take control of a magical fire or a fire spell within 100 feet.\n\nIf it succeeds at a counteract check (counteract rank 10, counteract modifier +32), the original caster loses control of the spell or magic fire, control is transferred to the dragon, and the dragon counts as having [[Actions/Sustain|Sustained the Spell]] with this action (if applicable). The dragon can choose to end the spell instead of taking control, if it chooses."
 
```

```encounter-table
name: Red Dragon (Ancient, Spellcaster)
creatures:
  - 1: Red Dragon (Ancient, Spellcaster)
```



The largest and most powerful of the chromatic dragons, red dragons are a menace to civilizations everywhere, and their strength is rivaled only by their arrogance. Red dragons see themselves as regents and overlords of all dragonkind. With their crowns of crimson spikes and their command of blistering frame, this is no haughty boast in their eyes-only unquestioned fact.

Red dragons don't deign to speak with lesser creatures; they simply dominate and burn, enslaving weaker creatures to act as servants and to look after their lairs while the dragons slumber away. They take pleasure in dominating these creatures, and they demand tribute from their supplicants. Those who anger or disappoint end up eaten or reduced to ash. They command their enslaved minions to constantly build onto their lairs, carving out new tunnels and designing cunning traps that ensure the dragon's security.

Driven by their arrogance, red dragons are the most likely of the chromatic dragons to ravage settlements. They want the world to see them in their rightful place as powerful tyrants, and they delight in threatening all other creatures. They have no qualms about bullying, manipulating, or killing to complete their goals-or simply intimidating others through a public display of brutality and dominance.

As legendary as the brutishness of red dragons is the magnificence of their hoards of gold. Their lairs are often situated in dangerous places, with volcanoes being a favorite spot, as they find them foreboding and the constant warmth is comfortable. No matter the locale, red dragons sleep on a litter of coins and other treasures, which they zealously guard. Sometimes, the dragon's internal heat causes these precious metals to fuse together.

* * *

While there are many types of dragons, from the powerful planar dragons to the strange esoteric dragons, few dragon varieties are as well-known and as rightly feared as the chromatic dragons. Differentiated by the hue of their scales, each color of dragon unleashes its own flavor of murderous cruelty-be it by claw, tooth, or breath-and unlike most creatures, dragons only become more powerful as they age. Their lust for treasure, food, bloodshed, and control are legendary. Physically powerful with egos to match, these dragons are often morally depraved and act as criminal masterminds, vicious tyrants, or voracious raiders.
