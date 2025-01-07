---
title: "Sea Dragon (Adult)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.b5AvIH66kUePCJOX" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Sea Dragon (Adult)"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sea Dragon (Adult)"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
trait_04: [[good]]
trait_05: [[water]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Common, Draconic, Elven, Sussuran, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Arcana: +18, Athletics: +26, Deception: +19, Intimidation: +21, Nature: +22, Society: +18, Stealth: +21, Survival: +20"
abilityMods: [6, 5, 4, 2, 4, 3]
speed: 30 feet,  fly 100 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 33
armorclass:
  - name: AC
    desc: "33 fed by metal; __Fort__ +22, __Ref__ +25, __Will__ +20; +1 status to all saves vs. magic"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  paralyzed,  sleep"
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
    desc: " (aura,emotion,fear,mental) 90 feet. DC 30 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Liquefy"
    desc: "`pf2:r` (arcane,water) **Trigger** The dragon is targeted by a Strike or spell that could deal fire or physical damage to them\n* * *\n\n**Effect** The dragon liquefies, turning entirely to water while maintaining their shape, for a split second. Against the triggering effect, they gain resistance 20 to fire and to all physical damage."

  - name: "Vortex"
    desc: " (aura,water) 40 feet. Water in the aura that's also in the same body of water as the dragon is difficult terrain for Swimming creatures which don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (magical, reach 15 feet)\n__Damage__  3d10 + 12 piercing plus hyponatremia"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile, magical, reach 10 feet)\n__Damage__  3d8 + 12 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+26 (magical, reach 25 feet)\n__Damage__  3d8 + 12 bludgeoning plus grab"

  - name: "Arcane Innate Spells"
    desc: "DC 32, attack +24; __2nd __  _[[Spells/Create Water|Create Water (At Will)]]_, _[[Spells/Environmental Endurance|Endure Elements (Self Only)]]_\n__Constant__  __(2nd)__ _[[Spells/Water Walk|Water Walk]]_"

  - name: "Rituals"
    desc: "_Control Weather (No Secondary Caster Required)_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,water) The dragon shoots a ball of water that deals 13d6 bludgeoning damage in a 25-foot burst within 50 feet (DC 32 Reflex check save). All non-magical fire in the radius is extinguished.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "Coiling Frenzy"
    desc: "`pf2:2`  The dragon makes one claw Strike and one tail Strike in either order, each against the same target. If either Strike hits, the dragon automatically [[Conditions/Grabbed|Grabs]] the target."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Breath Weapon whenever they score a critical hit with a Strike."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d8+6 bludgeoning, DC 30 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Hyponatremia"
    desc: " (water) A living creature that takes damage from the sea dragon's jaws Strike must succeed at a DC 32 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] as a surge of excess water floods its body."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sea Dragon (Adult)
creatures:
  - 1: Sea Dragon (Adult)
```



Sea dragons' affinity with water grants them mastery over rain, storms, and floods. Those whose livelihoods are at the mercy of the weather and waves frequently venerate these great aquatic creatures. Most sea dragons respond kindly to requests, but, like the sea, they can be unpredictable and fickle.

Sea dragons have disk-shaped scales like fish and webbed claws as well as large back and tail fins to aid in swimming. They appear in vivid and vibrant colors, like aquatic wildlife. Underwater flora and fauna grow and thrive upon older sea dragons, and ancient sea dragons often have a head of coral around their antlers, giving them the image of being crowned royalty.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
