---
title: "Underworld Dragon (Young, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Hkiq9kjGCggoXf2z" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Underworld Dragon (Young, Spellcaster)"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Underworld Dragon (Young, Spellcaster)"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[evil]]
trait_03: [[fire]]
trait_04: [[lawful]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Arcana: +13, Athletics: +17, Crafting: +17, Deception: +10, Intimidation: +12, Nature: +13, Stealth: +13, Survival: +11"
abilityMods: [6, 2, 3, 4, 2, 1]
speed: 40 feet,  burrow 30 feet,  fly 80 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +13, __Will__ +15"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  fire,  paralyzed,  sleep"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair an underworld dragon's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "Countered by Water"
    desc: "  If the underworld dragon takes damage from a spell with the cold or water trait, the elemental magic of fire within them is momentarily dampened.\n\nUntil the end of their next turn, they take a -1 circumstance penalty to attack rolls, and their jaws Strikes don't deal fire damage.\n\nThis limitation ends if the dragon uses Breath Weapon.\n\n[[Bestiary Effects/Effect_ Countered by Water|Effect: Countered by Water]]"

  - name: "Fed by Wood"
    desc: "  When an underworld dragon is struck by a weapon made primarily of wood or affected by a spell with the plant trait, the dragon's internal fiery essences are stoked with the added fuel. Their breath weapon recharges, and the fire damage from the dragon's jaws increases by one die until the end of the dragon's next turn.\n\n[[Bestiary Effects/Effect_ Fed by Wood|Effect: Fed by Wood]]"

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 23 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (reach 10 feet)\n__Damage__  2d8 + 8 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (adamantine, agile)\n__Damage__  2d8 + 8 slashing plus adamantine-claws,grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+18 (reach 20 feet)\n__Damage__  2d8 + 8 bludgeoning plus grab"

  - name: "Arcane Prepared Spells"
    desc: "DC 25, attack +18; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Knock|Knock]]_, _[[Spells/Resist Energy|Resist Energy]]_; __1st __  _[[Spells/Carryall|Floating Disk]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(3rd)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Produce Flame|Produce Flame]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 25, attack +17; __2nd __  _[[Spells/Everlight|Continual Flame]]_\n__Cantrips__  __(2nd)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Adamantine Claws"
    desc: "  The dragon's claws are infused with adamantine. Their claw Strikes ignore half the Hardness of any object hit."

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The dragon breathes a blast of fire that explodes in a 20-foot burst within 40 feet, dealing 7d6 fire damage (DC 25 Reflex check save). Creatures that fail the save also take 1d6 persistent fire.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+4 bludgeoning, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Underworld Dragon (Young, Spellcaster)
creatures:
  - 1: Underworld Dragon (Young, Spellcaster)
```



Underworld dragons embody the pressure between tectonic plates, the heat behind geysers, and flash fires that ignite when the conditions are just right. Natural alchemists, they innately understand reagents and catalysts. While some research the effects of magic on material reactions, the majority of underworld dragons concentrate on building their hoards. They scour the world for carved gemstones and artifacts of precious minerals, both of which they see as distilled essence of earth's bounty.

Underworld dragons appear angular and sharp; their scales glow as if superheated from within, and their hair flickers like tongues of flames. An intense fire glows behind their gazes, suggesting they could ignite item with a mere thought, and their breath ripples the air as a testament to the heat contained within their bodies.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
