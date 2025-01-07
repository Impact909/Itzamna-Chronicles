---
title: "Coloxus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3SFMQLJyNTLvueh5" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Coloxus"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Coloxus"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Chthonian, Common, Diabolic, Empyrean; Telepathy 100 feet, Tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Arcana: +21, Deception: +23, Diplomacy: +23, Religion: +22, Stealth: +25, Thievery: +23"
abilityMods: [5, 7, 4, 3, 4, 5]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +22, __Ref__ +25, __Will__ +18; +1 status to all saves vs. magic"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  disease; __Weaknesses__ cold iron 10, holy 10; __Resistances__ poison 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Filth Vulnerability"
    desc: "  A coloxus despises contact with filth and dirt. A small amount of filth held in the hand can be used against a coloxus as a Strike that has the thrown 5 feet trait, and that inflicts 2d6 mental damage on a hit. Forcing a coloxus to fall into or become immersed in filth deals 6d6 mental damage per round."

  - name: "Vanishing Words"
    desc: "`pf2:r`  **Trigger** The coloxus rolls initiative with Deception or Diplomacy and can cast [[Spells/Invisibility|Invisibility]]\n* * *\n\n**Effect** The coloxus casts 4th-rank _invisibility_ on itself."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 (finesse, magical, unholy)\n__Damage__  3d8 + 8 piercing plus siphon 1d6 spirit plus siphon"

  - name: "Divine Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Shadow Blast|Shadow Blast]]_, _[[Spells/Summon Animal|Summon Animal (Giant Arthropods Only)]]_; __5th __  _[[Spells/Abyssal Plague|Abyssal Plague]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Suggestion|Suggestion]]_\n__Cantrips__  __(6th)__ _[[Spells/Message|Message]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Droning Wings"
    desc: "`pf2:2` (divine,mental,visual) **Frequency** once per day\n* * *\n\n**Effect** The coloxus flutters its shimmering, gauzy wings and creates a mesmerizing display of color along with a sound-dampening buzzing drone. If the coloxus is [[Conditions/Invisible|Invisible]], that effect ends and it becomes visible. All creatures within a 30-foot emanation must succeed at a DC 29 Will check save or become [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure) until the start of the coloxus's next turn. As long as Droning Wings continues, the coloxus gains immunity to sonic damage. The coloxus can Sustain Droning Wings for up to 1 minute."

  - name: "Siphon"
    desc: "  When a coloxus damages a creature with its jaws Strike, it siphons away the target's physical vitality and drinks from their sense of self-worth and confidence. The coloxus gains 10 temporary Hit Points, and the creature must succeed at a DC 32 Will check save or become [[Conditions/Stupefied|Stupefied 1]]. Further damage dealt by the coloxus increases the stupefied condition by 1 on a failed save to a maximum of [[Conditions/Stupefied|Stupefied 4]]."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The creature's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Coloxus
creatures:
  - 1: Coloxus
```



Although the coloxus has the hideous head of a monstrous fly, these demons are fastidious and clean, always dressing in stylish clothing without a blemish on them. Coloxuses are manipulators and schemers born from destructively vain souls. Evil mortals are fond of conjuring them to serve as emissaries or spies, but they also make excellent assassins. Even in the role of murderer, the demon remains cloyingly polite and formal, reveling in the irony of perpetuating such a horrible crime under the guise of good etiquette, as if it were a delicate bit of diplomacy.

## Enemies Of Filth

Filth is often inescapable in the Abyss, and as a result, coloxus demons are particularly eager to be conjured away from that plane to work their evils in cleaner realities. When one uses _planar ally_ or _planar binding_ to conjure a coloxus, summoning it into a clean environment and promising you won't compel it to serve under filthy conditions may make the demon easier to bargain with. At the GM's discretion, the demon may agree to serve you for longer or at a lower cost than normal.
