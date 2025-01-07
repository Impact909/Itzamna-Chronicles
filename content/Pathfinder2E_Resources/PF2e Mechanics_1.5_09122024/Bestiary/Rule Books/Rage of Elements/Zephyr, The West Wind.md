---
title: "Zephyr, The West Wind"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AXso2v2I4avUmnwQ" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Zephyr, The West Wind"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Zephyr, The West Wind"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision"
languages: "Common, Empyrean, Sussuran; truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +38, Arcana: +31, Nature: +33, Occultism: +31, Performance: +38, Religion: +31, Stealth: +36, Survival: +33, Planar Lore: +33"
abilityMods: [4, 9, 7, 6, 6, 9]
speed: 25 feet,  fly 200 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +29, __Ref__ +33, __Will__ +30"
hp: 310
health:
  - name: ""
  - name: HP
    desc: "310, regeneration 15 (deactivated by earthbane); __Immunities__  bleed,  electricity,  paralyzed,  poison,  sleep; __Resistances__ cold 20"
abilities_top:
  - name: ""

  - name: "Truespeech"
    desc: "  An anemos can speak with and understand any creature that has a language."

  - name: "Wind Orchestra"
    desc: " (air,auditory) An anemos does not require instruments to perform music, instead using their winds to create and carry the sounds of any instruments they wish to duplicate. They can mimic any number of instruments simultaneously, creating and directing their own personal orchestra."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Earthbane)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Blessed by the Winds"
    desc: " (air,aura) 80 feet. The winds grow turbulent for those who would dare to fly in the same space as an anemos, but they take care to never harm or inconvenience their shepherd. Air within the emanation is difficult terrain for Flying creatures that do not have the air trait. While the aura is active, the anemos cannot be affected by environmental air or weather affects unless they choose to be."

  - name: "Earthbane"
    desc: "  An anemos's regeneration is suppressed for 1 round if the anemos is affected by an earth effect, or for as long as they are in contact with the ground and 1 round thereafter. If an anemos is submerged in at least 1 inch of mud, dirt, or stone, the anemos's aura deactivates, and the anemos becomes [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "Redirect Weather"
    desc: "`pf2:r` (divine) **Requirements** The anemos's aura is active\n\n**Trigger** A creature within the anemos's aura uses an air or electricity spell, or an air or electricity spell otherwise comes into effect within the anemos's aura\n* * *\n\n**Effect** The winds and weather of the spell obey the anemos's call. The anemos makes all the choices to determine the targets, destination, or other effects of the spell, as though they were the caster."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Thunderbolt"
    desc: "+35 (electricity, magical)\n__Damage__  3d8 + 12 electricity 3d6 sonic"

  - name: "**Ranged** `pf2:1` Thunderbolt"
    desc: "+35 (electricity, magical, thrown 30 ft.)\n__Damage__  3d8 + 10 electricity 3d6 sonic"

  - name: "**Ranged** `pf2:1` Air Blast"
    desc: "+35 (agile, air, magical, range 100 feet)\n__Damage__  3d10 + 12 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Cleanse Air|Cleanse Air]]_; __8th __  _[[Spells/Field of Life|Field of Life]]_; __7th __  _[[Spells/Humanoid Form|Humanoid Form (At Will)]]_; __4th __  _[[Spells/Airlift|Airlift (At Will)]]_, _[[Spells/Petal Storm|Petal Storm]]_, _[[Spells/Speak with Plants|Speak with Plants]]_, _[[Spells/Vapor Form|Vapor Form (At Will)]]_, _[[Spells/Voice on the Breeze|Voice on the Breeze (At Will)]]_; __1st __  _[[Spells/Air Bubble|Air Bubble (At Will)]]_"

  - name: "Rituals"
    desc: "_Control Weather_, _Sky Signs_"

  - name: "Collect Thunder"
    desc: " (electricity,manipulate) **Requirements** The anemos has a hand free\n* * *\n\n**Effect** The anemos runs a hand through the winds that swirl around them, the sparks from their fingertips coalescing into a thunderbolt. The anemos creates a thunderbolt in their open hand. If the anemos spends an action to Collect Thunder, a bolt instead strikes their open hand, creating a booming peal that deafens all creatures within 20 feet for 1 round unless they succeed at a DC 40 Fortitude check save; this adds the auditory trait to Collect Thunder. Any thunderbolts dissipate after 1 round."

  - name: "Command the Breeze"
    desc: "  When an anemos casts a ritual, they perform all aspects of the ritual themself, commanding their winds to complete all the ritual's components. They must fulfill any requirements for the ritual's additional casters and must attempt the checks normally performed by additional casters. In addition, anemoi can cast rituals faster than usual. If a ritual has a casting time measured in days, they can cast it in an equal number of hours."

  - name: "Storm Strikes Twice"
    desc: "`pf2:2` (air,teleportation) The anemos throws a thunderbolt, then becomes a wind that carries them in an instant to the bolt's location to attack again. They make a ranged thunderbolt Strike against a creature within their first range increment, teleport to the creature's location as a gust of wind, then grasp the thrown thunderbolt and make a melee thunderbolt Strike against a creature within reach. Their multiple attack penalty doesn't increase until they've made both attacks."

  - name: "Swiftness"
    desc: "  The anemos's movement doesn't trigger reactions."
 
```

```encounter-table
name: Zephyr, The West Wind
creatures:
  - 1: Zephyr, The West Wind
```



The truth of life in the Universe is that weather controls the world. The life-giving water that flows across Golarion, the maintenance of healthy forests, and the snows, thaws, and rains that help crops flourish all rely on the weather—weather that's shaped at the whims of the winds. Anemoi are powerful beings from the Plane of Air tasked by ancient gods to guard the skies and shepherd the winds of every world across the planes. They guide the winds along their natural paths, and while neither malevolent nor malicious, an anemos has little regard for how a storm might affect any creature caught in its path.

Anemoi can take several forms and shift between them as easily as they slip between the breezes. They wear humanoid guises to walk among mortals without drawing undue attention, and they transform into great, thunderous horses made of storm clouds and rain when they need to move quickly across the skies. Their true form, however, is wind coalesced into a humanoid shape, often with curling hair and feathery wings made of soft, drifting clouds.

On Golarion, each of the four cardinal winds are created and directed by a quartet of cardinal anemoi. The cold north winds are guided by Boreal, bringer of winter. Austral shepherds hot winds from the south. Eural brings stormy winds from the east. Finally, the gentle winds of spring come at the call of Zephyr, from the west. These four cardinal anemoi, alongside their councils of lesser anemoi, shape and control the winds across all of Golarion. As far as anyone can tell, the cardinal anemoi don't answer to a greater authority. There are even more powerful maximal anemoi living in the Plane of Air, but they seem content to leave the Universe out of their plans.

Though the cardinal anemoi try to keep a degree of separation from mortal affairs, lesser anemoi occasionally take a closer interest. Some monitor a single settlement or county, protecting, nourishing, or even vindictively destroying it. Each one has their own sets of interests. Many are vain or petty. Even more change attitudes just as quickly as the winds they guide. Pleasing an anemoi isn't a matter of following a set formula, but rather repeatedly changing course to give them what they desire for their mercurial current interests or perceived needs.

## The Shape Of The Air

Anemoi on the Plane of Air are typically genderless, while those who spend time in the Universe sometimes experiment with or develop preferences for one of the genders of the mortals they watch or live close to.
