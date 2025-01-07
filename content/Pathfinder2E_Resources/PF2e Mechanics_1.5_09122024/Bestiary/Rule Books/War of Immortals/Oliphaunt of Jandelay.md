---
title: "Oliphaunt of Jandelay"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3LHrbD7q6C9wEHuF" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/mythic
  - pf2eMonster
  - pf2e/creature/level/25
  - remaster
statblock: inline
name: "Oliphaunt of Jandelay"
level: 25
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder War of Immortals"
name: "Oliphaunt of Jandelay"
level: "Creature 25"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[monitor]]
trait_02: [[mythic]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Scent (Imprecise) 120 Feet"
languages: "Aklo; (can’t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +50"
abilityMods: [12, 5, 10, -1, 7, 7]
speed: 60 feet,  fly 40 feet
sourcebook: "_Pathfinder War of Immortals_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +48, __Ref__ +37, __Will__ +39; mythic resilience (all saves)"
hp: 680
health:
  - name: ""
  - name: HP
    desc: "680; __Immunities__  clumsy,  cold,  disease,  drained,  enfeebled,  mental,  paralyzed,  persistent damage,  petrified,  poison,  polymorph,  prone,  slowed,  stunned,  stupefied; __Resistances__ acid 20, fire 20, physical 15"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Mythic) Remove a Condition|Remove a Condition]]"
    desc: "`pf2:1` (concentrate) **Cost** 1 Mythic Point\n* * *\n\n**Effect** The Oliphaunt of Jandelay removes any one condition currently affecting it."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 300 feet DC 46 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Legendary Vigor"
    desc: "  The Oliphaunt of Jandelay is immune to penalties to its Speeds, and it ignores difficult terrain and greater difficult terrain."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Immunity|Mythic Immunity]]"
    desc: "  The Oliphaunt of Jandelay is immune to harmful spells cast by non-mythic creatures, Strikes made with non-mythic weapons, and unarmed Strikes from nonmythic characters."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Resilience|Mythic Resilience]]"
    desc: "  The Oliphaunt treats its saving throws with the associated save as one step better than they actually are (so a critical failure is a failure, a failure is a success, and a success is a critical success). The first time each round that a character rolls a critical hit against the Oliphaunt, they must reroll the attack roll and take the new result."

  - name: "Reactive"
    desc: "  The Oliphaunt of Jandelay gains 3 reactions each round. It can still use only one reaction per trigger."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Creature Family Ability Glossary/(Mythic) Undying Myth|Undying Myth]]"
    desc: "`pf2:0`  **Cost** all the creature's Mythic Points\n\n**Trigger** The creature would die and has at least 1 Mythic Point\n* * *\n\n**Effect** When the Oliphaunt of Jandelay would die, as long as it has at least 1 Mythic Point, it immediately expends all remaining Mythic Points it has, remains standing and conscious, and recovers 50% of its maximum Hit Points."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tusk"
    desc: "+45 (magical, reach 20 feet)\n__Damage__  4d10 + 22 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+45 (agile, magical, reach 15 feet)\n__Damage__  4d6 + 22 bludgeoning plus improved-knockdown"

  - name: "**Melee** `pf2:1` Trunk"
    desc: "+45 (magical, reach 30 feet)\n__Damage__  2d12 + 22 bludgeoning"

  - name: "**Ranged** `pf2:1` Debris Toss"
    desc: "+43 (deadly 2d8, propulsive, range increment 150 feet)\n__Damage__  4d8 + 16 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 46, attack +0; __10th __  _[[Spells/Cataclysm|Cataclysm]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Brutal Drag"
    desc: "  When the Oliphaunt takes a Stride action, any creature [[Conditions/Grabbed|Grabbed]] by the Oliphaunt of Jandelay's tusk is moved along with it to a location within 20 feet of the Oliphaunt's ending location. They remain grabbed and the GM determines which square they end up in."

  - name: "Destructive Frenzy"
    desc: "`pf2:3`  The Oliphaunt of Jandelay makes two tusk Strikes, two foot Strikes, and one trunk Strike in any order."

  - name: "Devastating Launch"
    desc: "`pf2:2`  **Cost** 1 Mythic Point\n* * *\n\n**Effect** The Oliphaunt of Jandelay buries its tusks into the ground in a 15-foot burst centered within 20 feet of it, collecting everything in that area, including any creature currently [[Conditions/Grabbed|Grabbed]] by its tusk attack, and flinging it all up to 120 feet away. Everything lands in a 30-foot burst, dealing 12d6 bludgeoning damage to each creature in the area (DC 51 Reflex check save). This damage also applies to any creatures, vehicles, or objects the Oliphaunt flung as well. A creature in the area being flung that succeeds or critically succeeds on their Reflex save remains in the square they started in. Anything launched by the Oliphaunt lands in a square in the burst as determined by the GM."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Power|Mythic Power]]"
    desc: "  The creature has a pool of 3 Mythic Points, and can spend those Mythic Points for any of the actions it has."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, Reflex check\n\nWhen the Oliphaunt of Jandelay Tramples, it can Stride up to triple its Speed, and any creature that fails or critically fails the Reflex save is knocked [[Conditions/Prone|Prone]].\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Trumpeting Blast"
    desc: "`pf2:2` (sonic) The Oliphaunt of Jandelay emits a cacophonous blast from its trunk in a 120-foot cone. Each creature in the area must attempt a DC 49 Fortitude check save. If the Oliphaunt spends 1 Mythic Point as part of the activity, the DC becomes 51 and the damage dice are increased to d12s. The Oliphaunt of Jandelay can't use Trumpeting Blast again for [[/gmr 1d4 #Recharge Trumpeting Blast]]{1d4 rounds}.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 7d10 sonic damage and is [[Conditions/Deafened|Deafened]] for 1 round.\n\n**Failure** The creature takes 14d10 sonic damage, is [[Conditions/Slowed|Slowed 1]] for 2 rounds, and is deafened for 2 rounds.\n\n**Critical Failure** The creature takes 28d10 sonic damage, is [[Conditions/Slowed|Slowed 2]] for 2 rounds, and is deafened for 4 rounds."
 
```

```encounter-table
name: Oliphaunt of Jandelay
creatures:
  - 1: Oliphaunt of Jandelay
```



### Harbinger of Annihilation

The Oliphaunt of Jandelay is drawn to worlds that are hurtling toward imminent annihilation.
