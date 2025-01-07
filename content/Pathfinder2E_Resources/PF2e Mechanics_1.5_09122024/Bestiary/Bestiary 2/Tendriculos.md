---
title: "Tendriculos"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tOciekK5ZAiVw5KG" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Tendriculos"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Tendriculos"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[fungus]]
trait_02: [[plant]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: "Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Stealth: +14"
abilityMods: [7, 2, 5, -2, 3, 0]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +12, __Will__ +13"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  acid; __Weaknesses__ fire 5; __Resistances__ piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tentacle Only)]]"
    desc: "`pf2:r`  Tentacle only.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+18 (reach 10 feet)\n__Damage__  2d10 + 11 piercing plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+18 (agile, reach 15 feet)\n__Damage__  2d6 + 11 bludgeoning plus grab"

  - name: "Rampant Growth"
    desc: "`pf2:1`  **Requirements** A creature the tendriculos has Swallowed Whole has taken damage since the end of the tendriculos's last turn, and the tendriculos hasn't used any other actions this turn\n* * *\n\n**Effect** The tendriculos regains 3d8 healing Hit Points and recovers from the [[Conditions/Fatigued|Fatigued]] and [[Conditions/Slowed|Slowed]] conditions. It reduces any [[Conditions/Enfeebled|Enfeebled]] value it has by 2."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d10+7 acid damage plus tendriculos venom, Rupture 14\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Tendriculos Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tendriculos
creatures:
  - 1: Tendriculos
```



These strange amalgams of plant and fungus with animal tendencies form where the natural world is corrupted by foul magic or frayed planar boundaries. Tendriculoses are instinctive ambush predators who seek out lightly traveled forest paths and lie in wait in the undergrowth. A tendriculos swallows its prey as quickly as possible and lets its paralytic digestive juices finish the meal, while swiftly restoring itself with the nourishment provided by the trapped creature. When collected, neutralized, and refined, the digestive fluids of a tendriculos form a lacquer that retains some of the tendriculos's acid resistance.

A tendriculos comes into being with a rudimentary understanding of the Sylvan language, but in some cases it might manifest knowing a different tongue, such as Aklo, Draconic, or even Necril. Regardless, tendriculoses have little patience for chattering from potential meals, though some determined fey and primal spellcasters have been known to form alliances or even closer bonds with tendriculoses. Befriending a tendriculos requires great patience and plentiful food-and these the gifts of food must be alive when handed over.

When it has finished feeding and is out of combat, a tendriculos slips into a quiescent state for a full day, one of the few times it is safe to approach. Upon rousing, it seeks the deep forest to regurgitate the less digestible portions of its meal. These remains may contain valuables that survived digestion and indicate that a tendriculos's hunting grounds lie nearby.

Tendriculoses dwell in deep woods and jungles. Those too near populated areas soon draw unwanted attention with their ravenous appetites. Well-fed tendriculoses develop fruiting bodies that cast forth millions of spores. Spores that happen to alight on carrion grow into new tendriculoses.
