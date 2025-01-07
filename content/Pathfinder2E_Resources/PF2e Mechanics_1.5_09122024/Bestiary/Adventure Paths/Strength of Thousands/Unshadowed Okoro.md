---
title: "Unshadowed Okoro"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Ap2QpV1D8QtHkHkP" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Unshadowed Okoro"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Unshadowed Okoro"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; "
languages: "Common, Draconic, Elven, Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Deception: +35, Diplomacy: +35, Occultism: +35, Performance: +31, Stealth: +29, Academia Lore: +33, Games Lore: +31"
abilityMods: [2, 3, 3, 4, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +27, __Will__ +33"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Resistances__ acid 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+3 Greater Striking Composite Shortbow]], 30x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Shadow's Displeasure"
    desc: "  When Okoro has fewer than 150 Hit Points, his shadow pulls at his essence to show the _Vesicant Egg's_ displeasure. He looks pained and confused, and he becomes [[Conditions/Clumsy|Clumsy 1]] and [[Conditions/Stupefied|Stupefied 1]] until healed to 150 Hit Points or more. These conditions increase to 2 when below 100 Hit Points. When below 50 Hit Points, he falls [[Conditions/Unconscious|Unconscious]]."

  - name: "Vesicated Shadow"
    desc: "  Okoro's shadow has become corrupted via the power of the _Vesicant Egg_. His shredded shadow grants him some control over acid and shadows. He gains a +4 status bonus to resist acid and shadow effects."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+28 (agile, finesse, nonlethal, unarmed)\n__Damage__  3d4 + 6 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+28 (deadly 2d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  3d6 + 22 piercing"

  - name: "Occult Spontaneous Spells"
    desc: "DC 40, attack +32; __9th __ (3 slots) _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Prismatic Sphere|Prismatic Sphere]]_, _[[Spells/Telepathic Demand|Telepathic Demand]]_; __8th __ (3 slots) _[[Spells/Quandary|Maze]]_, _[[Spells/Prismatic Wall|Prismatic Wall]]_, _[[Spells/Spirit Song|Spirit Song]]_; __7th __ (3 slots) _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Prismatic Spray|Prismatic Spray]]_; __6th __ (3 slots) _[[Spells/Collective Transposition|Collective Transposition]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __5th __ (3 slots) _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Synaptic Pulse|Synaptic Pulse]]_; __4th __ (3 slots) _[[Spells/Flicker|Blink]]_, _[[Spells/Fly|Fly]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_; __3rd __ (3 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __ (3 slots) _[[Spells/Blur|Blur]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/Noise Blast|Sound Burst]]_; __1st __ (3 slots) _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Phantasmal Minion|Unseen Servant]]_\n__Cantrips__  __(9th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Occult Innate Spells"
    desc: "DC 40, attack +32; __5th __  _[[Spells/Shadow Blast|Shadow Blast (Acid Only) (x2)]]_, _[[Spells/Shadow Siphon|Shadow Siphon (x2)]]_"

  - name: "Observe Weakness"
    desc: "`pf2:1` (concentrate,fortune,occult) Okoro studies a creature within 30 feet to find an opening to attack. On his next attack roll against the creature this turn, he rolls twice and uses the higher result, and his attack gains the fortune trait. The target becomes temporarily immune for 1d4 rounds."

  - name: "Rupture Shadow"
    desc: "`pf2:2` (acid,occult,shadow) Okoro can create immense blisters on a creature's shadow, which immediately burst, dealing 20d6 acid damage. He targets a creature within 60 feet that is casting a shadow, which must attempt a DC 37 Will check save. Okoro can't use Rupture Shadow again for 1d4 rounds.\n* * *\n\n**Critical Success** The target is unaffected and becomes temporarily immune for 1 day.\n\n**Success** The target takes half damage. The bursting shadow deals 5 acid splash damage to all creatures within 5 feet of the target.\n\n**Failure** The target takes full damage, and the bursting shadow deals 10 acid splash damage.\n\n**Critical Failure** The target takes double damage, the bursting shadow deals 20 acid splash damage, and the target also takes 4d6 persistent acid damage."

  - name: "Push My Luck"
    desc: "`pf2:r`  **Trigger** Okoro targets a creature with an attack\n\n**Requirements** The triggering creature was the target of Observe Weakness this turn\n* * *\n\n**Effect** Okoro draws upon his future luck to guarantee his attack. When he makes his attack roll, if he rolls lower than 10 on the die, he treats that attack roll as a 10 instead. This is in addition to rolling twice and taking the higher result from Observe Weakness. Afterward, Okoro's luck is temporarily spent, and he must roll twice and use the lower result of his next 3 checks; this is a misfortune effect. He can't use Push My Luck again until he's completed these 3 checks."
 
```

```encounter-table
name: Unshadowed Okoro
creatures:
  - 1: Unshadowed Okoro
```




