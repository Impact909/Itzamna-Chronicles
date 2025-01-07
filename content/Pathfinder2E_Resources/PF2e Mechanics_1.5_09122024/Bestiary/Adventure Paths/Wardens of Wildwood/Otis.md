---
title: "Otis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tMPffi8PHRWXuyA2" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troll
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Otis"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Otis"
level: "Creature 5"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
trait_03: [[troll]]
trait_04: [[wood]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +12"
abilityMods: [5, 2, 6, -2, 0, -2]
speed: 30 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +17, __Ref__ +11, __Will__ +7"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, regeneration 20 (deactivated by electricity or fire); __Weaknesses__ fire 10, electricity 10"
abilities_top:
  - name: ""

  - name: "Easily Misled"
    desc: "  The forest troll gets a –4 circumstance penalty to their Perception DC against Deception checks."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Electricity or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Furious Flailing"
    desc: "`pf2:r`  **Trigger** The forest troll takes electricity or fire damage\n* * *\n\n**Effect** The troll makes a claw Strike against a random creature within its reach. If the troll has persistent fire damage, they attempt a DC 15 Flat check to remove it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (reach 10 feet)\n__Damage__  2d10 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile, reach 10 feet)\n__Damage__  2d8 + 5 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 21, attack +13; __3rd __  _[[Spells/One with Plants|One with Plants (x3)]]_"

  - name: "Chase Prey"
    desc: "`pf2:2`  The forest troll rushes forward on all fours, Striding and then making two claw Strikes."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Otis
creatures:
  - 1: Otis
```


Variant troll

Forest trolls are gangly giants who stalk the fringes of civilization. They rely on their incredible strength to overpower foes with their vicious claws and toothy maws. These trolls stand anywhere from 12 to 16 feet tall, though they prefer to hunch for comfort and to lull foes into a false sense of security. Trolls are truly creatures of the forest, deeply linked in flesh and blood to the verdant habitats they consider their territory. In fact, when a forest troll is killed, their flesh turns into blackened lumps of charcoal, often still glowing with coals. Despite that, these creatures roam farther and wider than most of their kin, to the extent that they're the first creatures a common person thinks of when they hear the word "troll."

* * *

Slavering, cruel, invincible brutes: this is the villager's stock description for the dread monsters known as trolls. The roots of these stories are undoubtedly true. Trolls' flesh endlessly regrows, going so far as to sprout aberrant limbs or additional heads if not pruned, and a bottomless hunger is required to feed such unfettered growth. Even in the process of glutting themselves, however, trolls find opportunities to taunt their prey and inflict petty cruelties.

A troll's ability to survive is so strong that they believe even the smallest scrap of flesh will slowly regenerate into a new form, suffering as all the powers of the land are gathered to revive them. Despite the pain, trolls speak of this unassailable vitality as a blessing from their creator. Few trolls have heard the laughter of demons who claim that creator cursed the trolls and cast them down from lofty heights, binding them so they could never rise again.

Trolls prefer to remain solitary, keeping every scrap of food for themselves. In rare instances, an old and powerful troll comes to lead groups of trolls. Such warleaders possess enough cunning to lead their hordes in devastating raids and massacres, and their presence permanently alters the surrounding ecosystem. This link to their environment is an often misunderstood aspect of trollkind, and grows more acute with a troll's age and power. That's not to say trolls are valorous protectors of nature. They're vicious and territorial, and will blight their own territory forever if it means more to eat for a day.
