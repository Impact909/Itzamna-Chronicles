---
title: "Vanth Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8QuwYHWBXe9cbNKj" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Vanth Warrior"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Vanth Warrior"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +28, Intimidation: +25, Occultism: +23, Religion: +23, Stealth: +28, Boneyard Lore: +25"
abilityMods: [8, 5, 4, 4, 5, 4]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +25, __Ref__ +22, __Will__ +28; +1 status to all saves vs. magic"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Immunities__  death effects,  disease; __Resistances__ void 10, poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scythe|Scythe]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 20 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scythe"
    desc: "+29 (deadly d10, magical, trip)\n__Damage__  3d12 + 14 slashing plus spirit-touch"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (agile)\n__Damage__  3d8 + 14 slashing plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __3rd __  _[[Spells/Locate|Locate (x3)]]_, _[[Spells/Holy Light|Searing Light (x3)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_"

  - name: "Infuse Weapon"
    desc: " (divine) A vanth's scythe is their symbol of office and gains a measure of their personal power. This scythe becomes a _+2 striking scythe_ and is treated as if it were adamantine while the vanth wields it. A vanth whose scythe is taken or destroyed can infuse a new one with an hour of work."

  - name: "Reaping Scythe"
    desc: "`pf2:2`  The vanth throws their scythe, which flies in a 60-foot line, dealing 6d8 slashing damage to all creatures in the area (DC 34 Reflex check) and returns to the vanth's hand."

  - name: "Spirit Touch"
    desc: " (incorporeal) A vanth's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 3d6 void damage to living creatures and 3d6 vitality damage to undead."

  - name: "Vanth's Curse"
    desc: "`pf2:2` (curse,divine,misfortune) **Frequency** three times per day\n* * *\n\n**Effect** The vanth bestows a curse on a creature by touching it with their scythe. The creature must attempt a DC 34 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to Vanth's Curse for 24 hours.\n\n**Success** The target feels a momentary shudder of doom and is [[Conditions/Stupefied|Stupefied 2]] for 1 minute by the distracting sensation.\n\n**Failure** The target becomes morose and glum as it accepts its own inevitable fate. For 1 hour, the target is [[Conditions/Stupefied|Stupefied 3]]. Each time the target gains the dying condition, the stupefied value increases by 1, to a maximum value of stupefied 6.\n\n**Critical Failure** As failure, but the effect is permanent."
 
```

```encounter-table
name: Vanth Warrior
creatures:
  - 1: Vanth Warrior
```


Variant vanth

Protecting the Boneyard are the stern and resolute guardians of the dead known as vanths, psychopomps who resemble skeletons with raven-like wings and a mask resembling a vulture's skull. Vanths carry black scythes to fight against those who would disturb the natural progression of souls, and they consider any visitor to the Boneyard a potential troublemaker. When the psychopomp armies go to war, vanths serve as front-line soldiers. They rarely speak and even more rarely show any emotion other than a grim adherence to duty.
