---
title: "Balisse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Co0iR2CDkmap1k68" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Balisse"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Balisse"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[holy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Diabolic, Draconic, Empyrean; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Diplomacy: +17, Religion: +18"
abilityMods: [5, 2, 4, 1, 6, 5]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +12, __Will__ +18; +1 status to all saves vs. magic"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Weaknesses__ unholy 10; __Resistances__ fire 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|+1 Striking Scimitar]]"
  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Confessor's Aura"
    desc: " (aura,divine,mental) 20 feet.\n\nCreatures in the balisse's aura are subject to [[Spells/Ring of Truth|Ring of Truth]] (DC 23 Will check). Additionally, if these creatures choose to honestly express their own conflicted feelings, the aura makes it easier for them to put words to those feelings."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+20 (fire, forceful, holy, magical, sweep)\n__Damage__  2d6 + 8 slashing 1d6 fire"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Paralyze|Paralyze]]_; __3rd __  _[[Spells/Clear Mind|Clear Mind (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Angelic Messenger_, _Atone_, _Geas_"

  - name: "Brand of the Impenitent"
    desc: "`pf2:2` (curse,divine) **Frequency** once per day\n* * *\n\n**Effect** The balisse marks a creature within their confessor's aura as irredeemable. They can do so only after a failed attempt to convince the creature to repent. The touched creature takes a –1 status penalty to AC and saves, reduces all its resistances by 2, and gains weakness 2 to holy. The duration depends on the target's DC 26 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The duration is 1 round.\n\n**Failure** The duration is 1 day.\n\n**Critical Failure** The duration is unlimited.\n* * *\n\n[[Bestiary Effects/Effect_ Brand of the Impenitent|Effect: Brand of the Impenitent]]"

  - name: "Guiding Angel"
    desc: "`pf2:1` (concentrate,divine) **Requirements** The balisse is [[Conditions/Invisible|Invisible]]\n* * *\n\n**Effect** The balisse spiritually attaches themself to an adjacent mortal who doesn't have the unholy trait. They merge with the mortal's body and are unable to use any of their spells and abilities other than to interact with the mortal. They can [[Actions/Dismiss|Dismiss]] the effect to leave the mortal. While merged, the balisse can either communicate using a bodiless voice only the mortal can hear or can take a form of their choice that only the mortal can see, such as a small angel on the mortal's shoulder."
 
```

```encounter-table
name: Balisse
creatures:
  - 1: Balisse
```



Balisses, or confessor angels, seek to assist mortals ensnared by moral dilemmas or crises of faith. They prefer to guide people to their own decisions rather than demand obedience to a higher cause, as intrinsic belief is even more powerful than unquestioning obedience. While most balisses are fundamentally honest, they use their guiding angel ability to seem less intimidating and decrease the chance the mortal will simply acquiesce to the opinion of an obviously divine being.

While balisses can spring from any soul with suitable patience and strong counsel, they often form from souls of those who performed evil acts but were redeemed. These souls recognize the struggle and shame of those in similar situations, and can offer advice from the heart rather than from rote sympathy. Many serve the goddess Sarenrae, but they can serve other good deities and empyreal lords as well.

* * *

The celestial hosts of angels are messengers and warriors, divided into choirs based on their abilities and purviews. Angels were one of the first creations of the gods, and many still assist their righteous creators throughout the cosmos. Most angels in modern times are not direct creations of the divine, however, instead consisting of ascended mortal souls drawn from the celestial planes.

The majority of unaffiliated angels live in Nirvana, the plane of virtue and enlightenment. Angels who are affiliated with deities dwell in those deities' domains or other areas where that god holds influence. Regardless of residence or service, angels remain benevolent messengers possessed with magical auras to aid their allies.
