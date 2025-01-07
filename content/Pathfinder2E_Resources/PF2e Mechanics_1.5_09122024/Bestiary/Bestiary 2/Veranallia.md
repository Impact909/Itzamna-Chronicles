---
title: "Veranallia"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.J1L2UCHxpjHaNsCW" 
tags:
  - pf2e/creature/type/azata
  - pf2e/creature/type/celestial
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Veranallia"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Veranallia"
level: "Creature 20"

alignment: ""
size: "Medium"
trait_01: [[azata]]
trait_02: [[celestial]]
trait_03: [[chaotic]]
trait_04: [[good]]
trait_05: [[holy]]
modifier: 38
perception:
  - name: "Perception"
    desc: "+38; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: "Diabolic, Draconic, Empyrean; speak with animals, speak with plants, tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +34, Deception: +36, Diplomacy: +38, Intimidation: +36, Medicine: +36, Nature: +34, Survival: +38, Elysium Lore: +36"
abilityMods: [8, 6, 8, 6, 10, 8]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +36, __Ref__ +34, __Will__ +38"
hp: 475
health:
  - name: ""
  - name: HP
    desc: "475; __Weaknesses__ cold iron 20, unholy 20; __Resistances__ fire 20, cold 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sickle|+3 Greater Striking Sickle]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+39 (agile, finesse, holy, trip)\n__Damage__  3d4 + 16 slashing 4d6 cold 1d6 spirit"

  - name: "**Melee** `pf2:1` Vine"
    desc: "+39 (holy, reach 20 feet)\n__Damage__  4d12 + 16 bludgeoning plus improved-grab 1d6 spirit plus improved-grab"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +32; __10th __  _[[Spells/Cataclysm|Cataclysm]]_, _[[Spells/Primal Phenomenon|Primal Phenomenon (Once per year)]]_, _[[Spells/Revival|Revival]]_; __9th __  _[[Spells/Nature's Enmity|Nature's Enmity]]_, _[[Spells/Regenerate|Regenerate (x3)]]_, _[[Spells/Storm of Vengeance|Storm of Vengeance]]_, _[[Spells/Nature's Pathway|Tree Stride (At will)]]_; __8th __  _[[Spells/Polar Ray|Polar Ray (At will)]]_, _[[Spells/Sunburst|Sunburst (At will)]]_; __6th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph (At will)]]_, _[[Spells/Tangling Creepers|Tangling Creepers (At will)]]_\n__Constant__  __(9th)__ _[[Spells/Environmental Endurance|Endure Elements]]_, _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_, _[[Spells/Truespeech|Tongues]]_"

  - name: "Rituals"
    desc: "_Awaken Animal_, _Blight_, _Commune with Nature_, _Consecrate_, _Plant Growth_, _Primal Call_, _Reincarnate_"

  - name: "Alter Weather"
    desc: "`pf2:3`  **Frequency** three times per day\n* * *\n\n**Effect** The veranallia dramatically alters weather patterns in the surrounding area, producing any of the results of a successful 9th-rank [[Spells/Control Weather|Control Weather]] ritual."

  - name: "Rebirth"
    desc: " (divine) **Frequency** once per day\n* * *\n\n**Effect** The veranallia spends a minute to encase a creature that has been dead for no more than a year in a cocoon. After 24 hours, the creature is restored to life, and the cocoon explodes in a shower of colorful blossoms. If the veranallia's chooses, Rebirth can change the creature's ancestry or heritage, typically into an aasimar."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Veranallia
creatures:
  - 1: Veranallia
```



Veranallias represent the freedom of life to grow, change, and adapt. They rarely interact directly with non-azatas, as most other beings find their nature hard to comprehend, but those who secure their aid find them powerful allies. The lower half of a veranallia's body is made of vegetation that constantly repeats a dizzying cycle of sprouting, blooming, thriving, and wilting. The upper half of their body appears as that of a humanoid of any gender-it is rare for a veranallia to remain consistent in their gender for more than a few seasons at a time.

Veranallias transform the landscape in their wake, bringing creation and destruction alike. The world around them overflows with an abundance of vegetation, with plenty of food for nearby animals, and when they bring destruction, they do so without cruelty, as it is sometimes necessary to make room for new life. They trigger forest fires in woodlands before dry brush piles up to dangerous levels, and bring bitter winters to areas plagued with parasites that thrive in hot weather.
