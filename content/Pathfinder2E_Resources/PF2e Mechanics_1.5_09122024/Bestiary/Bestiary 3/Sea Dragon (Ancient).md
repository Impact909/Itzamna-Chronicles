---
title: "Sea Dragon (Ancient)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YpXChq6ZICXGillN" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Sea Dragon (Ancient)"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sea Dragon (Ancient)"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[dragon]]
trait_04: [[good]]
trait_05: [[water]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Common, Draconic, Elven, Empyrean, Sussuran, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Arcana: +26, Athletics: +33, Deception: +25, Intimidation: +27, Nature: +28, Society: +26, Stealth: +32, Survival: +26"
abilityMods: [8, 7, 5, 3, 5, 4]
speed: 50 feet,  fly 140 feet,  swim 70 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 41
armorclass:
  - name: AC
    desc: "41 fed by metal; __Fort__ +29, __Ref__ +32, __Will__ +27; +1 status to all saves vs. magic"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Immunities__  paralyzed,  sleep"
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
    desc: " (aura,emotion,fear,mental) 90 feet. DC 36 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Liquefy"
    desc: "`pf2:r` (arcane,water) **Trigger** The dragon is targeted by a Strike or spell that could deal fire or physical damage to them\n* * *\n\n**Effect** The dragon liquefies, turning entirely to water while maintaining their shape, for a split second. Against the triggering effect, they gain resistance 25 to fire and to all physical damage."

  - name: "Vortex"
    desc: " (aura,water) 60 feet. Water in the aura that's also in the same body of water as the dragon is difficult terrain for Swimming creatures which don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 20 feet)\n__Damage__  3d12 + 16 piercing plus hyponatremia"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 16 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+34 (magical, reach 25 feet)\n__Damage__  3d10 + 16 bludgeoning plus grab"

  - name: "Arcane Innate Spells"
    desc: "DC 38, attack +30; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Create Water|Create Water (At Will)]]_; __3rd __  _[[Spells/Environmental Endurance|Endure Elements (Self Only)]]_\n__Constant__  __(2nd)__ _[[Spells/Water Walk|Water Walk]]_"

  - name: "Rituals"
    desc: "_Control Weather (No Secondary Caster Required)_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,water) The dragon shoots a ball of water that deals 18d6 bludgeoning damage in a 30-foot burst within 60 feet (DC 38 Reflex check save). All non-magical fire in the radius is extinguished.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "Coiling Frenzy"
    desc: "`pf2:2`  The dragon makes one claw Strike and one tail Strike in either order, each against the same target. If either Strike hits, the dragon automatically [[Conditions/Grabbed|Grabs]] the target."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Breath Weapon whenever they score a critical hit with a Strike."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d10+8 bludgeoning, DC 38 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Hyponatremia"
    desc: " (water) A living creature that takes damage from the sea dragon's jaws Strike must succeed at a DC 38 Fortitude check save or become [[Conditions/Sickened|Sickened 2]] as a surge of excess water floods its body."

  - name: "Tidal Wave"
    desc: "`pf2:3` (arcane,manipulate,water) **Frequency** once per 10 minutes\n\n**Requirements** The dragon is in a body of water at least as large as they are\n* * *\n\n**Effect** The dragon slams their body down, sending a towering wave outward. This wave deals 10d12 bludgeoning damage in a 90-foot emanation. Each creature in the area must attempt a DC 38 Reflex check save. Structures and unattended objects in the area take the full amount of damage with no saving throw.\n* * *\n\n**Critical Success** The creature takes no damage but is pushed 30 feet from the dragon.\n\n**Success** The creature takes half damage and is pushed 60 feet from the dragon.\n\n**Failure** The creature takes full damage, is pushed 120 feet from the dragon, and falls [[Conditions/Prone|Prone]].\n\n**Critical Failure** As failure, but double damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sea Dragon (Ancient)
creatures:
  - 1: Sea Dragon (Ancient)
```



Sea dragons' affinity with water grants them mastery over rain, storms, and floods. Those whose livelihoods are at the mercy of the weather and waves frequently venerate these great aquatic creatures. Most sea dragons respond kindly to requests, but, like the sea, they can be unpredictable and fickle.

Sea dragons have disk-shaped scales like fish and webbed claws as well as large back and tail fins to aid in swimming. They appear in vivid and vibrant colors, like aquatic wildlife. Underwater flora and fauna grow and thrive upon older sea dragons, and ancient sea dragons often have a head of coral around their antlers, giving them the image of being crowned royalty.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
