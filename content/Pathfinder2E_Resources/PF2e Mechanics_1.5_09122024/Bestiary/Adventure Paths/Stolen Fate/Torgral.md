---
title: "Torgral"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.glCGiBU9DEBmWPwj" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Torgral"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Torgral"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet, See the Unseen"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Athletics: +27, Intimidation: +30, Religion: +28, Stealth: +24"
abilityMods: [6, 3, 6, 4, 5, 7]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +24, __Will__ +26; +1 status to all saves vs. magic"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/The Uprising|The Uprising]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Defiance Vulnerability"
    desc: "  Defiance causes a ghalzarokh anguish. If a creature scores a critical success on a saving throw to resist the ghalzarokh's [[Spells/Charm|Charm]], [[Spells/Command|Command]], [[Spells/Dominate|Dominate]], or [[Spells/Suggestion|Suggestion]] spells or Project Blame, the demon takes 4d6 mental damage. The demon takes the same damage if it rolls a critical failure on an Intimidation check."

  - name: "Project Blame"
    desc: "`pf2:r` (divine,emotion,mental) **Trigger** A creature succeeds or critically succeeds at a saving throw against one of the ghalzarokh's spells or Abyssal Spew, or the ghalzarokh misses a creature with a melee Strike\n* * *\n\n**Effect** The creature must attempt a DC 36 Will check saving throw.\n* * *\n\n**Critical Success** The creature is temporarily immune to Project Blame for 24 hours, and the ghalzarokh suffers from its defiance vulnerability.\n\n**Success** The creature's [[Conditions/Stupefied|Stupefied]] condition increases by 1 (if they succeeded on a saving throw) or its [[Conditions/Clumsy|Clumsy]] condition increases by 1 (if the demon missed them with a Strike). This increase in value lasts until the end of the creature's next turn but can't increase either condition beyond a value of 3.\n\n**Failure** As success, but the duration changes to 1 minute. A creature can attempt a DC 36 Will check save at the end of its turn to remove the effect early.\n\n**Critical Failure** As failure, but for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical, reach 10 feet, unholy)\n__Damage__  1d6 spirit 3d12 + 14 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet, unholy)\n__Damage__  1d6 spirit 3d8 + 14 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 36, attack +28; __8th __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Suggestion|Suggestion]]_; __6th __  _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Command|Command (At Will)]]_; __4th __  _[[Spells/Charm|Charm (At Will)]]_\n__Constant__  __(8th)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Abyssal Spew"
    desc: "`pf2:2` (acid,divine,fire) The ghalzarokh spews corrosive flame that deals 8d6 acid damage and 8d6 fire damage in a 40-foot cone (DC 36 Reflex check save). The ghalzarokh can't use Abyssal Spew again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Torgral
creatures:
  - 1: Torgral
```


Male ghalzarokh

Ghalzarokh demons, also known as tyranny demons, form from the souls of cruel autocrats. These demons subjugate weaker fiends. After amassing an army, a ghalzarokh begins a chaotic spree of bloody conquest.

## Demon Thralls

Ghalzarokhs are bullies who prefer numerous thralls to allies. These demons loathe owing any other being a favor and serve stronger creatures only with the expectation of rich reward. A ghalzarokh can rarely be found without a fiendish entourage or army (such as a demon throng). They prefer "pacts" with "lesser" demons, usually offering only a feeble guarantee to allow the weaker fiend's continued existence.
