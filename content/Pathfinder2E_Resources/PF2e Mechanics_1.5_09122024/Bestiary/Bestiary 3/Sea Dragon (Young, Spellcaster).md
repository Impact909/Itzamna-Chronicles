---
title: "Sea Dragon (Young, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FBtFcN6irQFo2pZT" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Sea Dragon (Young, Spellcaster)"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sea Dragon (Young, Spellcaster)"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
trait_04: [[good]]
trait_05: [[water]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Common, Draconic, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +14, Athletics: +19, Deception: +14, Intimidation: +16, Nature: +15, Society: +14, Stealth: +16, Survival: +13"
abilityMods: [5, 4, 3, 2, 3, 2]
speed: 30 feet,  fly 100 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27 fed by metal; __Fort__ +17, __Ref__ +18, __Will__ +15"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Countered by Earth"
    desc: "  If the sea dragon is targeted with an earth spell or [[Spells/Petrify|Petrify]], they lose Liquefy until the end of their next turn."

  - name: "Fed by Metal"
    desc: " (arcane) When a sea dragon is struck by a weapon made primarily of metal or affected by a spell that uses metal, many of the dragon's scales transform to mimic the metal. This grants the dragon a +1 item bonus to AC until the start of their next turn.\n\n[[Bestiary Effects/Effect_ Fed by Metal|Effect: Fed by Metal]]"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 24 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Liquefy"
    desc: "`pf2:r` (arcane,water) **Trigger** The dragon is targeted by a Strike or spell that could deal fire or physical damage to them\n* * *\n\n**Effect** The dragon liquefies, turning entirely to water while maintaining their shape, for a split second. Against the triggering effect, they gain resistance 15 to fire and to all physical damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (reach 10 feet)\n__Damage__  2d10 + 11 piercing plus hyponatremia"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d8 + 11 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+20 (reach 20 feet)\n__Damage__  2d8 + 11 bludgeoning plus grab"

  - name: "Arcane Prepared Spells"
    desc: "DC 26, attack +19; __3rd __  _[[Spells/Feet to Fins|Feet to Fins]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/Resist Energy|Resist Energy]]_, _[[Spells/Water Breathing|Water Breathing]]_; __1st __  _[[Spells/Air Bubble|Air Bubble]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_\n__Cantrips__  __(3rd)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Message|Message]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 26, attack +18; __2nd __  _[[Spells/Environmental Endurance|Endure Elements (Self Only)]]_; __1st __  _[[Spells/Create Water|Create Water (At Will)]]_\n__Constant__  __(2nd)__ _[[Spells/Water Walk|Water Walk]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,water) The dragon shoots a ball of water that deals 9d6 bludgeoning damage in a 20-foot burst within 40 feet (DC 26 Reflex check save). All non-magical fire in the radius is extinguished.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+6 bludgeoning, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Hyponatremia"
    desc: " (water) A living creature that takes damage from the sea dragon's jaws Strike must succeed at a DC 26 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] as a surge of excess water floods its body."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sea Dragon (Young, Spellcaster)
creatures:
  - 1: Sea Dragon (Young, Spellcaster)
```



Sea dragons' affinity with water grants them mastery over rain, storms, and floods. Those whose livelihoods are at the mercy of the weather and waves frequently venerate these great aquatic creatures. Most sea dragons respond kindly to requests, but, like the sea, they can be unpredictable and fickle.

Sea dragons have disk-shaped scales like fish and webbed claws as well as large back and tail fins to aid in swimming. They appear in vivid and vibrant colors, like aquatic wildlife. Underwater flora and fauna grow and thrive upon older sea dragons, and ancient sea dragons often have a head of coral around their antlers, giving them the image of being crowned royalty.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
