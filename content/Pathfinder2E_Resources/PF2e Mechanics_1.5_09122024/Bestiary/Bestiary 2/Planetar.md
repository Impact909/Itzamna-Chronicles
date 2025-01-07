---
title: "Planetar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NIjelavPe3AY4WJC" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Planetar"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Planetar"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Truesight"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Intimidation: +32, Religion: +32"
abilityMods: [8, 3, 6, 5, 6, 6]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +28, __Ref__ +25, __Will__ +28; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, regeneration 15 (deactivated by unholy); __Weaknesses__ unholy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+2 Greater Striking Greatsword]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Aura of Righteousness"
    desc: " (aura,divine) 20 feet. Allies in the planetar's aura gain a +2 status bonus to AC against evil creatures and a +2 status bonus to damage rolls against evil creatures. The area in the aura is difficult terrain for evil creatures.\n\n[[Bestiary Effects/Effect_ Aura of Righteousness (Planetar)|Effect: Aura of Righteousness (Planetar)]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Holy Greatsword"
    desc: "+32 (holy, magical, versatile p)\n__Damage__  3d12 + 16 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Earthquake|Earthquake]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Power Word Stun|Power Word Stun]]_, _[[Spells/Sunburst|Sunburst]]_; __7th __  _[[Spells/Charm|Charm]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Power Word Blind|Power Word Blind]]_, _[[Spells/Clear Mind|Remove Fear (At will)]]_; __6th __  _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Dispel Magic|Dispel Magic (At will)]]_; __5th __  _[[Spells/Breath of Life|Breath of Life]]_, _[[Spells/Death Ward|Death Ward]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Restoration|Restoration (x3)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At will) (Self only)]]_, _[[Spells/Sure Footing|Remove Paralysis]]_\n__Constant__  __(5th)__ _[[Spells/Detect Alignment|Detect Alignment (Evil only)]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Angelic Messenger_, _Call Spirit_, _Resurrect_"

  - name: "Blade of Justice"
    desc: "`pf2:2` (holy) The planetar makes a greatsword Strike against a target it detects as evil. If the target is evil, the Strike deals three extra weapon damage dice and deals 1d6 persistent spirit damage to the target. The planetar can convert all the physical damage from the attack into spirit damage."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The planetar can take on the appearance of any Small or Medium humanoid. This doesn't change their Speed or Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Holy Armaments"
    desc: " (divine) Any weapon gains the effect of a _[[Equipment/Holy|Holy]]_ property rune while a planetar wields it."
 
```

```encounter-table
name: Planetar
creatures:
  - 1: Planetar
```



The beings of righteous fury known as planetars are known to be the least patient of angels. They exist to destroy evil that cannot be redeemed, and they often leave prolonged dialogue to other angels. Of course, no planetar ignores the importance of diplomacy, but they know that others among the angelic hosts are better suited to that task, while they focus on the larger picture. In angelic armies, planetars serve as commanders or generals. They stand at least 9 feet tall and weigh over 500 pounds.
