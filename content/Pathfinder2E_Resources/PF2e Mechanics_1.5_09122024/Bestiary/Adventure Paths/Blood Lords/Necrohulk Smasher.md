---
title: "Necrohulk Smasher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.n4UXxGdxl9KgIr5z" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mutant
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Necrohulk Smasher"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Necrohulk Smasher"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mutant]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +32, Intimidation: +27"
abilityMods: [9, 4, 6, -4, 4, 4]
speed: 30 feet
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +23, __Will__ +26"
hp: 345
health:
  - name: ""
  - name: HP
    desc: "345, void healing, regeneration 15 (deactivated by acid); __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ slashing 15"
abilities_top:
  - name: ""

  - name: "Alchemical Cartridge"
    desc: " (alchemical) Critical hits rupture the necrohulk's alchemical cartridge. The first time the necrohulk takes a critical hit, it loses its regeneration. The second time it takes a critical hit, it takes 15 damage that it can't heal unless the cartridge is stitched back into place."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Acid)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+30 (reach 10 feet)\n__Damage__  4d10 + 15 bludgeoning plus improved-push"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+25 (brutal, range increment 120 feet)\n__Damage__  4d10 + 15 bludgeoning"

  - name: "Alchemical Amplification"
    desc: " (alchemical) **Frequency** once per hour\n* * *\n\n**Effect** The necrohulk draws upon alchemical stores to push its body into overdrive. It becomes [[Conditions/Quickened|Quickened]] for 1d4 rounds. It can use this extra action to Step, Stride, or Strike."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Fist\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Smashing Blow"
    desc: "`pf2:2`  The necrohulk smasher makes a fist Strike. If it hits, the necrohulk smashes the target into the floor or nearby wall. The target takes an additional 6d10 bludgeoning damage, depending on its DC 33 Fortitude check save.\n* * *\n\n**Critical Success** The target takes half of the additional damage.\n\n**Success** The target takes half the additional damage and is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The target takes full additional damage, is [[Conditions/Stunned|Stunned 3]], and knocked [[Conditions/Prone|Prone]].\n\n**Critical Failure** The target takes double the additional damage, is stunned 3, and knocked prone."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Necrohulk Smasher
creatures:
  - 1: Necrohulk Smasher
```



Mutants with incredible strength make the most powerful necrohulks. These necrohulk smashers are so swollen with biological and alchemical muscle enhancements that they can simply pound their way through enemies.

* * *

The strange, terrible energies swirling about on the winds and embedded in the earth of the Mana Wastes have led to unexpected changes and mutations in the bodies of those who dwell there. These mutants usually have little chance to escape their hardscrabble existence, as they're ostracized by other societies. People in the kingdom of Nex to the north look on such folk with suspicion, as do the dwarves of Alkenstar to the west. Surprisingly, the undead nation of Geb to the south is often the best hope for a future among people with unusual appearances.

Those who flee to Geb or are convinced to make it their home frequently find their welcome to be a false promise, however. Necromancers who long ago tired of animating the same humanoids find new potential in mutated flesh, and mutants who aren't careful might find themselves led into laboratories or crypts for experimentation.

Enterprising twilight sages of Yled's Mortuarium have innovated bizarre combinations of alchemy and necromancy that boost their victims' mutations to persist even after reanimation. Although these necrohulks are virtually mindless and require a constant influx of chemicals to retain their might, they're more than powerful enough to make the extremely difficult process worth the effort. The cartridge containing the alchemical formulation that sustains them is perhaps the trickiest part of necrohulk animation, and it's easiest to simply stitch the cartridge right into the necrohulk's flesh.

Yled's armies contain a growing number of necrohulks. This isn't solely because these juggernauts are frightening effective combatants on the field of battle; leveraging the instinctive revulsion that mutants create carries some strategic advantage. Although the occasional necrohulks do run amok in Yled, addled on the chemical cocktails that sustain them, military necromancers generally keep them under control.
