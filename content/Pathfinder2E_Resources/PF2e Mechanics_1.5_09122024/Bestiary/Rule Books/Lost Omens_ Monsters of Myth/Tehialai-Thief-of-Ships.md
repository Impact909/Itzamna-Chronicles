---
title: "Tehialai-Thief-of-Ships"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7MaoyN337sCXa0Wu" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Tehialai-Thief-of-Ships"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Tehialai-Thief-of-Ships"
level: "Creature 13"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[aquatic]]
trait_03: [[beast]]
trait_04: [[chaotic]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Okaiyan, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +28, Stealth: +24, Survival: +27, Ocean Lore: +30"
abilityMods: [8, 5, 4, 4, 6, 4]
speed: 30 feet,  swim 60 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +26, __Ref__ +20, __Will__ +23; +2 status to all saves vs. water"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200, Hardness 10 (Ship Armor)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "Exoskeletal Armory"
    desc: "  At the beginning of each day, Tehialai can molt to change the morph of her two massive striking claws. She chooses two morphs and adds their Strikes and Release Claw effects to the stat block presented here. Tehialai can molt two different claws or two copies of the same claw."

  - name: "Ship Armor"
    desc: "  Tehialai hides within a shell made of all the ships she has stolen. This ship armor reduces any damage Tehialai takes by an amount equal to its Hardness. Once Tehialai is reduced to fewer than half her Hit Points, or immediately upon being damaged by a critical hit, her ship armor breaks, removing her Hardness and reducing her Armor Class to 32."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+27 (magical, reach 10 feet)\n__Damage__  4d8 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Barbed Spear"
    desc: "+27 (magical, reach 15 feet)\n__Damage__  4d8 + 12 piercing plus exoskeletal-armory"

  - name: "**Melee** `pf2:1` Boiling Club"
    desc: "+25 (magical)\n__Damage__  4d12 + 12 bludgeoning plus exoskeletal-armory 1d6 fire plus exoskeletal-armory"

  - name: "**Melee** `pf2:1` Toothed Shredder"
    desc: "+27 (fatal d10, magical, reach 15 feet)\n__Damage__  4d6 + 12 slashing plus exoskeletal-armory"

  - name: "**Ranged** `pf2:1` Tidal Gourd"
    desc: "+36 (magical, thrown 60 ft., water)\n__Damage__  2d8 + 4 bludgeoning plus exoskeletal-armory 2d8 cold plus exoskeletal-armory"

  - name: "**Ranged** `pf2:1` Water Spit"
    desc: "+25 (magical, range 120 feet, water)\n__Damage__  4d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Salt Darts"
    desc: "+26 (magical, range 120 feet)\n__Damage__  2d8 + 12 piercing plus exoskeletal-armory 2d8 acid plus exoskeletal-armory"

  - name: "Capsize"
    desc: "`pf2:1` (attack) Tehialai attempts to capsize an aquatic vessel of her size or smaller that she's adjacent to. She must succeed at a DC 33 Athletics check check (reduced by 5 for each size smaller the vessel is) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Move Home"
    desc: "`pf2:3` (manipulate) **Requirements** Tehialai is adjacent to a broken ship, and her ship armor is broken\n* * *\n\n**Effect** Tehialai claims nearby ship pieces to rebuild her home. She destroys the adjacent ship and rebuilds her ship armor, restoring her Hardness and increasing her AC back to 36."

  - name: "Pressurize Claw"
    desc: "`pf2:1`  **Requirements** Tehialai's claw isn't currently Pressurized\n* * *\n\n**Effect** Tehialai draws water into the base of one of her claws, building immense hydraulic pressure as she prepares to attack. The claw remains loaded until she Releases that Claw or 1 minute has passed, whichever comes first. While the claw is Pressurized, Tehialai can't use that claw to Strike. If Tehialai isn't at least partially within a body of water when she Pressurizes her Claw, she takes a -2 penalty to any attack rolls and DCs when she Releases that Claw."

  - name: "Release Claw"
    desc: "`pf2:1`  **Requirements** Tehialai has Pressurized a Claw\n* * *\n\n**Effect** Tehialai lashes out with the force of the sea. See each claw for its released effect; the DC for any effect is 33. After Releasing a Claw, the claw depressurizes."

  - name: "Release Claw (Barbed Spear)"
    desc: "`pf2:1`  **Requirements** Tehialai has Pressurized a Claw\n* * *\n\nTehialai's spear shoots out, impaling prey and reeling them back. All creatures in a 40-foot line take 8d6 piercing damage (DC 33 Reflex check save); creatures that critically fail are [[Conditions/Grabbed|Grabbed]] until the end of Tehialai's next turn.\n* * *\n\nAfter Releasing a Claw, the claw depressurizes."

  - name: "Release Claw (Boiling Club)"
    desc: "`pf2:1` (fire,sonic) **Requirements** Tehialai has Pressurized a Claw\n* * *\n\nThe impact of Tehialai's claw begets a burning vacuum. Tehialai makes a boiling club Strike against one target within 15 feet. If she hits, a shock wave booms out, dealing 3d6 fire damage and 3d6 sonic damage to all creatures except her within 15 feet of the target, including the target itself (DC 33 Fortitude check save). If the Strike was a critical hit, the target uses the degree of success one lower than it rolled on its save. Unlike most fire abilities, this ability can be used underwater, and the typical 5 fire resistance for being underwater doesn't apply.\n* * *\n\nAfter Releasing a Claw, the claw depressurizes."

  - name: "Release Claw (Salt Darts)"
    desc: "`pf2:1`  Tehialai launches a flurry of darts. She makes two salt dart Strikes against two different creatures. Both attacks count towards her multiple attack penalty, but she doesn't increase her penalty until after she has made both attacks."

  - name: "Release Claw (Tidal Gourd)"
    desc: "`pf2:1` (water) Tehialai atomizes the water in her claw to create a mist that fills a 40-foot emanation centered on her and that lasts until the end of her next turn or until dispersed by a strong wind. All creatures within the mist become [[Conditions/Concealed|Concealed]], and all creatures outside the mist become concealed to creatures within it. Wavesense functions through the mist and ignores the concealment."

  - name: "Release Claw (Toothed Shredder)"
    desc: "`pf2:1`  Tehialai's claw whirs and spins to cut through armor and ship hulls. Tehialai makes a toothed shredder Strike. On a hit, the target becomes [[Conditions/Off-Guard|Off-Guard]] until the end of Tehialai's next turn and takes 2d12 bleed."
 
```

```encounter-table
name: Tehialai-Thief-of-Ships
creatures:
  - 1: Tehialai-Thief-of-Ships
```



Though her current form is but a small and pale shell of her former glory, Tehialai is a legend even in her waning days. The titanic crustacean wears the hulls of ruined ships as her shell, ripped into shape by vessel-rending claws, as nothing else in Golarion's oceans is large enough to shield her body-or perhaps nothing else will satisfy her. Few ships can withstand her might, and fewer still are prepared for her appearance. Those who don't know of the thief of ships won't know to watch for her coming, and those who do know Tehialai offer her tribute to ward off her predation.
