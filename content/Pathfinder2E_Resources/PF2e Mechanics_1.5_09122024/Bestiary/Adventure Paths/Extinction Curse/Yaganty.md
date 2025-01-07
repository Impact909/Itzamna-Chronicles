---
title: "Yaganty"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NHJe5u4ixFWYLNmQ" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Yaganty"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Yaganty"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[fey]]
trait_02: [[lawful]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Greater Darkvision"
languages: "Common, Diabolic, Fey"
skills:
  - name: "Skills"
    desc: "Deception: +23, Nature: +21, Occultism: +18, Stealth: +23"
abilityMods: [6, 5, 5, 2, 5, 7]
speed: 20 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +23, __Ref__ +17, __Will__ +21"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Weaknesses__ cold iron 10; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Light in the Darkness"
    desc: " (aura,light,mental,primal,visual) 60 feet. The flames from a yaganty's fingers shed bright light in a 10-foot radius and are visible even in areas affected by magical darkness, but they do not shed dim light beyond that radius. Any creature within 60 feet in an area of darkness or dim light that sees the yaganty's candle fingers must succeed at a DC 27 Will check save or become [[Conditions/Fascinated|Fascinated]] by the yaganty for 1 minute or until the yaganty uses a hostile action against the creature, whichever comes first."

  - name: "Vulnerability to Extinguishing"
    desc: "  A yaganty who is doused with water or otherwise has their candle fingers extinguished takes 3d6 persistent mental, becomes [[Conditions/Quickened|Quickened 1]], and screams in agony until they reignite their candles (typically by casting [[Spells/Produce Flame|Produce Flame]] and lighting their fingers with an Interact action)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Candle Fingers"
    desc: "+20 (fire, magical, reach 10 feet)\n__Damage__  3d10 + 5 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile, magical, reach 10 feet)\n__Damage__  2d8 + 9 slashing plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 29, attack +23; __5th __ (1 slots) _[[Spells/Translocate|Dimension Door]]_; __4th __ (1 slots) _[[Spells/Darkness|Darkness]]_; __3rd __ (2 slots) _[[Spells/Breathe Fire|Burning Hands (x2)]]_\n__Cantrips__  __(5th)__ _[[Spells/Produce Flame|Produce Flame]]_"

  - name: "Fling Wax"
    desc: "`pf2:2` (fire) The yaganty whips a stream of scalding wax in a 30-foot line. Each glob deals 1d6 persistent fire damage. An affected creature or adjacent ally can remove one glob of wax by spending an Interact action to scrape it off. The yaganty can't use Fling Wax again for 1d4 rounds. Creatures in the area must attempt a DC 27 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is splattered with 1d2+1 globs of wax.\n\n**Failure** The creature is splattered with 1d4+2 globs of wax.\n\n**Critical Failure** As failure, and the creature is [[Conditions/Blinded|Blinded]] until it removes the globs of wax."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Yaganty
creatures:
  - 1: Yaganty
```



Yaganties are lean, hairy humanoids with lanky torsos, horned heads, and bulbous black eyes. The elongated fingers of one their hands are made of candlestick wax, and their fingertips, which have wicks instead of nails, burn endlessly. In the dead of night, the flickering light of a yaganty's fingertips casts dramatic shadows across their face and highlights their trollish visage.

Yaganty fables follow a common formula. A wayward pedestrian, traveling at night and usually in a forest, follows distant lights with the hope that the lights belong to a fellow wayfarer, only to come face-to-face with a gangly monster. The story ends in one of three ways: the traveler appeals to the yaganty with a gift of gold (the exact sum necessary varies wildly by the telling), the yaganty slays the traveler over some incomprehensible transgression, or, even more inexplicably, the yaganty offers the lost traveler five candles in simple charity so that the light might guide them home.
