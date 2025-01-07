---
title: "Necrohulk Flailer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.APVLOBGyZYil78SA" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mutant
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Necrohulk Flailer"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Necrohulk Flailer"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mutant]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +26"
abilityMods: [7, 8, 5, -4, 4, 0]
speed: 30 feet,  climb 25 feet
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +23, __Ref__ +26, __Will__ +20"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, void healing, regeneration 15 (deactivated by acid); __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ slashing 15"
abilities_top:
  - name: ""

  - name: "Alchemical Cartridge"
    desc: " (alchemical) Critical hits rupture the necrohulk's alchemical cartridge. The first time the necrohulk takes a critical hit, it loses its regeneration. The second time it takes a critical hit, it takes 15 damage that it can't heal unless the cartridge is stitched back into place."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Acid)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+27 (agile, reach 15 feet)\n__Damage__  3d8 + 13 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (reach 10 feet)\n__Damage__  3d12 + 13 bludgeoning"

  - name: "Alchemical Amplification"
    desc: " (alchemical) **Frequency** once per hour\n* * *\n\n**Effect** The necrohulk draws upon alchemical stores to push its body into overdrive. It becomes [[Conditions/Quickened|Quickened]] for 1d4 rounds. It can use this extra action to Step, Stride, or Strike."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  6d6 bludgeoning, DC 32 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Tentacle Storm"
    desc: "`pf2:2`  The necrohulk flailer makes up to four tentacle Strikes, each against a different target. These attacks count toward its multiple attack penalty, but the penalty doesn't increase until after the necrohulk makes all of these attacks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Necrohulk Flailer
creatures:
  - 1: Necrohulk Flailer
```



Additional limbs, failing tentacles, and rubbery bodies are common among Mana Wastes mutants, and aspiring necrohulk creators like to combine flesh from more than one of these kinds of mutants to create gangly but powerful warriors.

* * *

The strange, terrible energies swirling about on the winds and embedded in the earth of the Mana Wastes have led to unexpected changes and mutations in the bodies of those who dwell there. These mutants usually have little chance to escape their hardscrabble existence, as they're ostracized by other societies. People in the kingdom of Nex to the north look on such folk with suspicion, as do the dwarves of Alkenstar to the west. Surprisingly, the undead nation of Geb to the south is often the best hope for a future among people with unusual appearances.

Those who flee to Geb or are convinced to make it their home frequently find their welcome to be a false promise, however. Necromancers who long ago tired of animating the same humanoids find new potential in mutated flesh, and mutants who aren't careful might find themselves led into laboratories or crypts for experimentation.

Enterprising twilight sages of Yled's Mortuarium have innovated bizarre combinations of alchemy and necromancy that boost their victims' mutations to persist even after reanimation. Although these necrohulks are virtually mindless and require a constant influx of chemicals to retain their might, they're more than powerful enough to make the extremely difficult process worth the effort. The cartridge containing the alchemical formulation that sustains them is perhaps the trickiest part of necrohulk animation, and it's easiest to simply stitch the cartridge right into the necrohulk's flesh.

Yled's armies contain a growing number of necrohulks. This isn't solely because these juggernauts are frightening effective combatants on the field of battle; leveraging the instinctive revulsion that mutants create carries some strategic advantage. Although the occasional necrohulks do run amok in Yled, addled on the chemical cocktails that sustain them, military necromancers generally keep them under control.
