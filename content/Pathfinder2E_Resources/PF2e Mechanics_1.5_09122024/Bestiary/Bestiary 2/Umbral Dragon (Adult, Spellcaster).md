---
title: "Umbral Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tomSe4PmmgEK3im3" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Umbral Dragon (Adult, Spellcaster)"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Umbral Dragon (Adult, Spellcaster)"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[evil]]
trait_03: [[shadow]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Necril, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +31, Deception: +28, Intimidation: +28, Nature: +25, Stealth: +27, Survival: +28"
abilityMods: [8, 4, 6, 4, 6, 5]
speed: 50 feet,  fly 180 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +25, __Will__ +27; +1 status to all saves vs. magic"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  void,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (reach 15 feet, void)\n__Damage__  3d10 + 14 piercing plus ghost-bane 3d6 void plus ghost-bane"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 14 slashing plus ghost-bane"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+28 (magical, reach 20 feet)\n__Damage__  3d12 + 14 slashing plus ghost-bane"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+28 (agile, magical, reach 15 feet)\n__Damage__  2d10 + 14 slashing plus ghost-bane"

  - name: "Primal Prepared Spells"
    desc: "DC 35, attack +30; __6th __  _[[Spells/Dominate|Dominate]]_, _[[Spells/Truesight|True Seeing]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Shadow Blast|Shadow Blast]]_, _[[Spells/Shadow Siphon|Shadow Siphon]]_; __4th __  _[[Spells/Vapor Form|Gaseous Form]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Nightmare|Nightmare]]_; __3rd __  _[[Spells/Bind Undead|Bind Undead]]_, _[[Spells/Blindness|Blindness]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Death Knell|Death Knell]]_, _[[Spells/Peaceful Rest|Gentle Repose]]_, _[[Spells/Humanoid Form|Humanoid Form]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Item Facade|Item Facade]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(6th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Primal Innate Spells"
    desc: "DC 36, attack +28; __7th __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Umbral Journey|Shadow Walk]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Jaws Only)]]"
    desc: "`pf2:r`  Jaws only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Breath Weapon"
    desc: "`pf2:2` (primal,shadow,void) The umbral dragon breathes in one of two ways. They can't use Breath Weapon again for 1d4 rounds.\n\n*   **Void** The dragon breathes a blast of darkness in a 40-foot cone that deals 16d6 void damage (DC 36 Reflex check save). Undead creatures take 19d6 force damage instead of the void damage.\n*   **Shadows** The dragon breathes a blast of shadows in a 40-foot cone. Each creature within the cone must attempt a DC 36 Fortitude check save.\n    \n    **Critical Success** The creature is unaffected.\n    \n    **Success** The creature is [[Conditions/Enfeebled|Enfeebled 2]] for 1 round.\n    \n    **Failure** The creature is [[Conditions/Enfeebled|Enfeebled 2]] for 1 minute.\n    \n    **Critical Failure** The creature is [[Conditions/Enfeebled|Enfeebled 2]] for 1 minute and [[Conditions/Blinded|Blinded]] for 1 round."

  - name: "Ghost Bane"
    desc: " (incorporeal) An umbral dragon's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune, and an umbral dragon's jaws deal an additional 6d6 force damage to undead."
 
```

```encounter-table
name: Umbral Dragon (Adult, Spellcaster)
creatures:
  - 1: Umbral Dragon (Adult, Spellcaster)
```



While the other primal dragons hail from the Elemental Planes, the cruel and unceasingly malicious umbral dragons originate in the depths of the Shadow Plane. Their sleek black scales and serpentine grace allow them to strike from hiding, and they are known for playing with their prey before finally finishing it. These creatures of shadowy energy and unwholesome appetites prefer the necrotic flesh of undead creatures to any other meal. This strange hunger can be of accidental benefit to nearby humanoid societies, but ultimately they hunt and kill undead creatures for the taste, rather than out of any desire to protect others from the undead. The benefit is always short-lived, however. When umbral dragons exhaust their preferred prey, they turn on whatever living creatures happen to be nearby. Umbral dragons sometimes go to great lengths to obtain their favorite meals, even creating undead creatures that they then feast upon.

For all their power, umbral dragons are uninterested in fair battles. When faced with foes that pose any kind of actual danger to them, umbral dragons flee into the shadows and seek to strike back through pawns or minions rather than risk their own lives. Their treasure hoards are varied and diverse, often augmented by loot stolen from crypts the dragons have turned into feeding grounds. They have a strong respect for and interest in traditions and heirlooms, and they often seek to augment their hoards with items of great value that have been handed down through the generations of those whose corpses and ghosts they've fed upon.
