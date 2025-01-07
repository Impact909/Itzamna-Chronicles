---
title: "Troll Warleader"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.39Rh4FXtzyi33LT5" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troll
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Troll Warleader"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Troll Warleader"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
trait_03: [[troll]]
trait_04: [[wood]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Crafting: +15, Intimidation: +22, Nature: +17, Survival: +17"
abilityMods: [7, 3, 7, -1, 1, 4]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 29
armorclass:
  - name: AC
    desc: "29 (26 plus all-around vision after Shed Armor); __Fort__ +23, __Ref__ +17, __Will__ +15"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, regeneration 30 (deactivated by acid or fire); __Weaknesses__ fire 10, electricity 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Battle Axe|+1 Striking Battle Axe]], [[Equipment/Half Plate|Half Plate]]"
  - name: "Easily Misled"
    desc: "  The forest troll gets a –4 circumstance penalty to their Perception DC against Deception checks."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Electricity or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Furious Roar"
    desc: "`pf2:r`  **Trigger** The troll warleader takes electricity or fire damage\n* * *\n\n**Effect** The warleader uses their Primordial Roar and, if they're aware of the damage's source, can Stride toward it. If the warleader has persistent fire damage, they attempt a DC 15 Flat check to remove it."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (reach 10 feet)\n__Damage__  2d12 + 13 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, reach 10 feet)\n__Damage__  2d8 + 13 slashing"

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+24 (magical, reach 10 feet, sweep)\n__Damage__  2d8 + 13 slashing"

  - name: "Primordial Roar"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The troll warleader unleashes a bestial roar. Each non-troll creature in a 100-foot emanation must attempt a DC 29 Will check save. The creature is then temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]]."

  - name: "Shed Armor"
    desc: "`pf2:1` (manipulate) The warleader cuts their armor loose from their flesh. They immediately heal 60 Hit Points in a surge of regeneration as they grow twisted limbs and malformed faces.\n\nWithout their armor, the warleader's AC drops to 26 but they gain [[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]] from the new faces.\n\nPutting the armor back on takes 10 minutes, and this ability can't be used again until 1 hour has passed."

  - name: "Sweeping Axes"
    desc: "`pf2:3`  **Requirements** The troll warleader is wielding two battle axes\n* * *\n\n**Effect** The warleader makes a battle axe Strike against each creature in their reach and the bonus from sweep applies to each attack. These attacks count against their multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks."
 
```

```encounter-table
name: Troll Warleader
creatures:
  - 1: Troll Warleader
```



Long-lived trolls sometimes force their way through the twin distractions of hunger and pain to learn more about the world around them. To manage their regeneration, they learn to cover themselves in crude armor that slowly becomes integrated with the top layer of their flesh. Marked by this armor and aided by their superior wits, these warleaders gather a variety of trolls to serve them in raiding parties.

The warleader presented here is a forest troll, but warleaders can be other types of trolls as well. Many of them are adapted to battle tactics that are best suited to their home environments.

* * *

Slavering, cruel, invincible brutes: this is the villager's stock description for the dread monsters known as trolls. The roots of these stories are undoubtedly true. Trolls' flesh endlessly regrows, going so far as to sprout aberrant limbs or additional heads if not pruned, and a bottomless hunger is required to feed such unfettered growth. Even in the process of glutting themselves, however, trolls find opportunities to taunt their prey and inflict petty cruelties.

A troll's ability to survive is so strong that they believe even the smallest scrap of flesh will slowly regenerate into a new form, suffering as all the powers of the land are gathered to revive them. Despite the pain, trolls speak of this unassailable vitality as a blessing from their creator. Few trolls have heard the laughter of demons who claim that creator cursed the trolls and cast them down from lofty heights, binding them so they could never rise again.

Trolls prefer to remain solitary, keeping every scrap of food for themselves. In rare instances, an old and powerful troll comes to lead groups of trolls. Such warleaders possess enough cunning to lead their hordes in devastating raids and massacres, and their presence permanently alters the surrounding ecosystem. This link to their environment is an often misunderstood aspect of trollkind, and grows more acute with a troll's age and power. That's not to say trolls are valorous protectors of nature. They're vicious and territorial, and will blight their own territory forever if it means more to eat for a day.
