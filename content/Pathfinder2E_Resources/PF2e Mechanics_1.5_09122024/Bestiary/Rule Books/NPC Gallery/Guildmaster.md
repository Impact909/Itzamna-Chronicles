---
title: "Guildmaster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OJaX5CEGWVQpxVQ2" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Guildmaster"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Guildmaster"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Crafting: +25, Diplomacy: +24, Intimidation: +22, Society: +21, Architecture Lore: +25, Bureaucracy Lore: +19"
abilityMods: [3, 1, 1, 4, 2, 3]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +14, __Will__ +17"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Light Hammer|+1 Striking Light Hammer]], [[Equipment/Hide Armor|Guildmaster's Uniform]], [[Equipment/Artisan's Toolkit|Artisan's Tools]], Construction Schematics, [[Equipment/Basic Crafter's Book|Tax Ledgers]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Light Hammer"
    desc: "+16 (agile, magical)\n__Damage__  2d6 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Light Hammer"
    desc: "+14 (agile, magical, thrown 20 ft.)\n__Damage__  2d6 + 5 bludgeoning"

  - name: "Call to Action"
    desc: "`pf2:1` (auditory,concentrate,emotion,mental) The guildmaster gives a speech to inspire themself and all guild-member allies within 60 feet, granting them a +1 status bonus to attack and damage rolls until the start of the guildmaster's next turn.\n\n[[Bestiary Effects/Effect_ Call to Action|Effect: Call to Action]]"

  - name: "Sworn Duty"
    desc: "  While within the guild or presiding over guild business, the guildmaster gains a +2 circumstance bonus to weapon attack rolls and deals an additional 2d6 damage on a successful weapon attack."
 
```

```encounter-table
name: Guildmaster
creatures:
  - 1: Guildmaster
```



In cities, artisans working in a common trade often form guilds to set standards of quality, establish common prices, engage in collective bargaining with business owners, and lobby local governments for favorable laws. The guildmaster-often a master artisan in their own right-also acts as an administrator and politician, advocating for artisans in their trade. The guildmaster is a 12th-level challenge when competing in crafting or their area of expertise (architecture in the example below).

* * *

Every settlement needs tradespeople to create new products, facilitate commerce, and keep the infrastructure from crumbling. Larger cities often have entire guilds dedicated to the creation of specific goods, managing worker conditions, and working with local governments.
