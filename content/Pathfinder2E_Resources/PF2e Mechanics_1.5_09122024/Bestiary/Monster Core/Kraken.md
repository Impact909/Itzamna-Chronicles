---
title: "Kraken"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sTEbIQoUZDB9ijfe" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Kraken"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Kraken"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aquatic]]
trait_02: [[beast]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +38, Intimidation: +32, Nature: +35, Stealth: +33"
abilityMods: [9, 4, 9, 5, 6, 5]
speed: 10 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +35, __Ref__ +28, __Will__ +32"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360; __Immunities__  controlled,  emotion; __Resistances__ cold 10, poison 20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Altered Weather"
    desc: " (aura,primal) A kraken reshapes the weather within 2 miles of it, with the effect of the [[Spells/Control Weather|Control Weather]] ritual centered on the kraken and based on its emotional state, at the GM's discretion. If the kraken dies, the weather returns to normal immediately."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm"
    desc: "+37 (magical, reach 40 feet)\n__Damage__  4d10 + 17 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+37 (agile, magical, reach 60 feet)\n__Damage__  3d10 + 17 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+37 (magical, reach 20 feet)\n__Damage__  3d10 + 17 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __10th __  _[[Spells/Dominate|Dominate (Animals Only)]]_; __8th __  _[[Spells/Punishing Winds|Punishing Winds]]_; __7th __  _[[Spells/Resist Energy|Resist Energy]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+17 bludgeoning, DC 40 Fortitude check. On a failed save, a creature that is holding its breath loses 1d4 rounds worth of air.\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Double Attack"
    desc: "`pf2:1`  The kraken makes two Strikes with two different arms or tentacles, each limb targeting a different creature. Double Attack counts as two attacks toward the kraken's multiple attack penalty, but the penalty doesn't increase until after both attacks are made.\n\nIf the kraken subsequently uses the Grab action, it Grabs any number of creatures it hit with Double Attack."

  - name: "Ink Cloud"
    desc: "`pf2:1`  The kraken releases a cloud of black, venomous ink in an 80-foot emanation. This cloud has no effect outside water.\n\nCreatures inside the ink cloud are exposed to kraken ink poison and are [[Conditions/Undetected|Undetected]] while inside the cloud.\n\nThe kraken can't use Ink Cloud again for 2d6 rounds, and the cloud dissipates after 1 minute."

  - name: "Jet"
    desc: "`pf2:1` (move) The kraken moves through the water up to 280 feet in a straight line without triggering reactions."

  - name: "Kraken Ink"
    desc: " (poison) Krakens are immune to this poison\n\n**Saving Throw** DC 39 Fortitude check;\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 4d6 poison damage and [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** 5d6 poison damage and [[Conditions/Sickened|Sickened 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kraken
creatures:
  - 1: Kraken
```



A kraken is an enormous, squid-like leviathan with a cruel intelligence. It hunts ships, whales, and heroes alike. The hatred and envy krakens hold for alghollthus, their rivals, has led many krakens to make their lairs in sunken cities, where they can sift through ancient lore and uncover long-lost arcane secrets.
