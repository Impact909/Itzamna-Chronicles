---
title: "Vanth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yXEqmMO61Tf9gSsI" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Vanth"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vanth"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +17, Intimidation: +15, Occultism: +13, Religion: +13, Stealth: +17, Boneyard Lore: +15"
abilityMods: [6, 4, 2, 2, 4, 2]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +15, __Ref__ +13, __Will__ +17; +1 status to all saves vs. magic"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105; __Immunities__  death effects,  disease; __Resistances__ void 10, poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scythe|+1 Scythe]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 20 feet DC 22 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scythe"
    desc: "+18 (deadly d10, magical, trip)\n__Damage__  1d10 + 8 slashing plus spirit-touch"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (agile)\n__Damage__  1d6 + 8 slashing plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +14; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_; __3rd __  _[[Spells/Holy Light|Holy Light (x3)]]_, _[[Spells/Locate|Locate (x3)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_"

  - name: "Infuse Weapon"
    desc: " (divine) A vanth's scythe is its symbol of office and gains a measure of its personal power. This scythe becomes a _+1 scythe_ and is treated as if it were adamantine while the vanth wields it. A vanth whose scythe is taken or destroyed can infuse a new one with an hour of work."

  - name: "Shepherd's Touch"
    desc: "  A vanth's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 2d6 void damage to living creatures and 2d6 vitality damage to undead."

  - name: "Vanth's Curse"
    desc: "`pf2:2` (curse,divine,misfortune) **Frequency** three times per day\n* * *\n\n**Effect** The vanth bestows a curse on a creature by touching it with its scythe. The creature must attempt a DC 25 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to Vanth's Curse for 24 hours.\n\n**Success** The target feels a momentary shudder of doom and is [[Conditions/Stupefied|Stupefied 1]] for 1 minute by the distracting sensation.\n\n**Failure** The target becomes morose and glum as it accepts its own inevitable fate. For 1 hour, the target is [[Conditions/Stupefied|Stupefied 2]]. Each time the target gains the dying condition, the stupefied condition value increases by 1, to a maximum value of [[Conditions/Stupefied|Stupefied 4]].\n\n**Critical Failure** As failure, but the effect is permanent."
 
```

```encounter-table
name: Vanth
creatures:
  - 1: Vanth
```



Protectors of the Boneyard, the stern and resolute guardians of the dead, vanths are psychopomps who resemble skeletons with raven-like wings and a mask resembling a vulture's skull. Vanths carry black scythes to fight against those who would disturb the natural progression of souls, and they consider any visitor to the Boneyard a potential troublemaker. They rarely speak and even more rarely show any emotion other than a grim adherence to duty.

When the psychopomp armies go to war, vanths serve as front-line soldiers. In particular, daemons continually stage raids on the River of Souls, requiring constant patrol. Implacable warriors, vanths fly in perfect formation. This can backfire, as they often suppress any adaptability they possess as they wage war.

* * *

Psychopomps are guardians and shepherds of the dead in the Boneyard, the vast plane of graves where mortal souls are judged and sent on to their eternal rewards or damnations. Psychopomps ensure that the dead come to terms with their transition from mortality and are properly sorted into the appropriate afterlife. They also protect souls from being preyed upon by supernatural predators. Nearly all psychopomps wear masks, especially when they're likely to be interacting with mortals, although the types of masks they wear are as varied as the psychopomps themselves. The courts of the Boneyard preside in Requian, a somber yet melodic language spoken slowly with various tonal shifts.

Many psychopomps are intimately involved with the Boneyard's massive bureaucracy. Few pursue mercy, justice, or personal gain; their duties to Pharasma and her Boneyard are supreme. Nevertheless, individual psychopomps interpret their duties in different ways, which might put them in conflict with mortals or even with each other.
