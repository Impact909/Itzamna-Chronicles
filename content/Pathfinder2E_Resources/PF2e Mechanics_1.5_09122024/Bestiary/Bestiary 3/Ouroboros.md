---
title: "Ouroboros"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.I8siD2QFb3XaBqnI" 
tags:
  - pf2e/creature/type/astral
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Ouroboros"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Ouroboros"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[astral]]
trait_02: [[beast]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision"
languages: "Aklo; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Athletics: +41"
abilityMods: [10, 5, 7, -4, 4, 8]
speed: 100 feet,  fly 100 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +38, __Ref__ +34, __Will__ +33; +1 status to all saves vs. magic"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500, regeneration 50 (deactivated by fire); __Immunities__  acid,  death effects,  disease,  void,  poison,  precision; __Weaknesses__ piercing 15, slashing 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 50 (Deactivated by Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:0`  Incalculable Fangs Only\n\nBecause the ouroboros contains an infinite number of snakes that act independently, its Attack of Opportunity is a free action (though it can still use only one per trigger).\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Sanguine Spray"
    desc: "  When the ouroboros takes slashing or piercing damage, or when Devour Tail ends, blood gushes from the wound in a 15-foot cone. Each creature in the area takes 5d6 acid damage (DC 41 Reflex check save). A creature that takes any damage is exposed to the ouroboros's regenerative blood.\n\nWhere the blood falls upon ground, it coagulates into magical snakes that bite at anyone who passes. This is hazardous terrain deals 17 piercing damage and 5 poison damage to any non-ouroboros creature that moves through the square or ends its turn there. A creature that avoids all the piercing damage doesn't take the poison damage. After 1 hour, a blood patch permanently becomes a living snake, typically an [[Bestiary 2/Emperor Cobra|Emperor Cobra]]."

  - name: "Unfathomable Infinity"
    desc: " (aura,incapacitation,mental,visual) 100 feet. The ouroboros is the embodiment of perfect infinity, and this concept pulls at the threads of mortal minds, desperately straining the limits of their comprehension. When a creature ends its turn in the aura, it must attempt a DC 41 Will check save.\n\nThe creature is then temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Success** The creature is stupefied 1 for 1 minute.\n\n**Failure** The creature is stupefied 1 for 1 minute and [[Conditions/Stunned|Stunned 3]].\n\n**Critical Failure** The creature is [[Conditions/Stupefied|Stupefied 3]] and [[Conditions/Stunned|Stunned]], both for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maw"
    desc: "+39 (magical, reach 30 feet)\n__Damage__  4d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Body"
    desc: "+39 (magical, reach 20 feet)\n__Damage__  4d10 + 18 bludgeoning"

  - name: "**Melee** `pf2:1` Incalculable Fangs"
    desc: "+37 (agile, magical, reach 10 feet)\n__Damage__  3d6 + 16 piercing 2d8 poison"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+39 (magical, reach 30 feet)\n__Damage__  4d12 + 18 bludgeoning"

  - name: "Devour Tail"
    desc: "`pf2:1`  An ouroboros spend most of its life eating its own tail, which perpetually regrows at the same rate it's consumed. The ouroboros places its maw around the end of its tail and begins devouring its own body.\n\nWhile the ouroboros is consuming itself, its regeneration can't be suppressed, and it is immune to [[Conditions/Drained|Drained]], [[Conditions/Enfeebled|Enfeebled]], [[Conditions/Fatigued|Fatigued]], [[Conditions/Persistent Damage|Persistent Damage]], and [[Conditions/Sickened|Sickened]] conditions. If any of these conditions is in effect when the ouroboros takes this action, the condition immediately ends.\n\nWhile eating its tail, the ouroboros can't make maw or tail strikes, and its Speeds are 50 feet. It continues devouring its tail even while [[Conditions/Dying|Dying]], [[Conditions/Unconscious|Unconscious]], [[Conditions/Stunned|Stunned]], or otherwise unable to act.\n\nTo end this effect, the ouroboros must first be [[Conditions/Immobilized|Immobilized]], then a creature must successfully [[Actions/Grapple|Grapple]] it, which tears the maw free in addition to its normal effects. The ouroboros can also cease Devouring its Tail with a single action. Either of these tears the maw free of the tail, causing the stump to spill blood as described in sanguine spray."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The ouroboros [[Conditions/Grabbed|Grabs]] a creature with their maw\n* * *\n\n**Effect** The ouroboros uses Swallow Whole."

  - name: "[[Bestiary Ability Glossary/Trample|Flying Wheel]]"
    desc: "`pf2:2`  **Requirements** The ouroboros is eating its own tail (see Devour Tail)\n* * *\n\n**Effect** As Trample, except the ouroboros can Fly up to double its Speed instead of Striding.\n\nHuge or smaller, body, DC 45 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Regenerative Blood"
    desc: " (contact,curse,incapacitation,poison,polymorph,primal) The regenerative and transmutative properties of ouroboros blood regenerate and mutate a creature's body into ouroboros-like snakes. A creature already affected by regenerative blood is immune to additional exposure.\n\n**Saving Throw** DC 42 Fortitude check\n* * *\n\n**Maximum Duration** 24 hours\n\n**Stage 1** regeneration 5 (deactivated by fire), [[Conditions/Slowed|Slowed 1]], and [[Conditions/Clumsy|Clumsy 2]] (12 hours)\n\n**Stage 2** regeneration 5 (deactivated by fire), [[Conditions/Slowed|Slowed 2]] and [[Conditions/Clumsy|Clumsy 4]] (12 hours)\n\n**Stage 3** The creature's body transmutes into a mass of writhing snakes, with the effects an 8th-rank [[Spells/Animal Form|Animal Form]] spell but with an unlimited duration."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 4d10+9 acid, Rupture 50\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ouroboros
creatures:
  - 1: Ouroboros
```



Ouroboros are the embodiment of eternity. Though they're prevalent as a symbol, often scrawled across the margins of alchemical tomes, few know that the beasts actually exist in the Astral Plane, where they fly through the silvery-gray void like a serpentine wheel. The ouroboros is usually depicted as a snake devouring its tail. This circular symbol is synonymous with infinity, self-sufficiency, and eternal unity.

An ouroboros' form exemplifies the unfathomable concepts of forever. Its undulating body is composed of smaller serpents, who are in turn composed of ever smaller serpents, continuing indefinitely. These smaller components are recycled as the ouroboros devours its tail, existing in a perpetual, cyclical process of creation and destruction. It is a massive creature, forming a loop roughly 50 feet in diameter and weighing hundreds of tons.

An ouroboros's most striking feature is its ability to almost instantly grow new flesh and heal from nearly any wound. This profound regenerative ability comes in part from an ouroboros's magical blood, which is rumored to have many miraculous properties.

Through their inscrutable behavior suggests that an ouroboros is mindless, the creatures boast crude intellects and can understand speech, though they have no way to speak. They possess an instinctive, almost obsessive will to survive and defend themselves ferociously if threatened in even the slightest way. Often these perceived threats take the form of another creature simply existing within the ouroboros's line of sight, leading other Astral creatures to give these powerful beings a wide berth. The only creature an ouroboros reliably ignores is another ouroboros, but they're so incredibly rare that these meetings occur only once an age.

Being entirely self-sustaining, an ouroboros rarely deigns to emerge from its consumption to engage with the Material Plane. Yet, the creature remains capable of inflicting tremendous devastation that far surpasses what it could wreak leveraging only its massive size alone. Left to its own devices, an ouroboros is likely to simply roam the Astral Plane in eon-spanning cycles, following some pattern too long and large for any mortal to even chart, much less fully comprehend. When conjured to the Material Plane, however, an ouroboros eagerly begins to initiate the cycle of renewal for which it is best known, beginning with that cycle's first step: destruction.
