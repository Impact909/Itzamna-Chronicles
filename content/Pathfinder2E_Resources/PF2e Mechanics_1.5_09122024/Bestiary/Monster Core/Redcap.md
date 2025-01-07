---
title: "Redcap"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xQsMDdEa270jMG1V" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Redcap"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Redcap"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[fey]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +15, Deception: +11, Intimidation: +13, Nature: +10, Stealth: +13"
abilityMods: [4, 4, 2, 1, 1, 2]
speed: 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +15, __Will__ +10"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, fast healing 10; __Weaknesses__ cold iron 5, Divine Revulsion 1"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|Halberd]], [[Equipment/Sickle|Sickle]], Iron Boots, Red Cap"
  - name: "Red Cap"
    desc: " (primal) A redcap's woolen hat is dyed with the blood of their victims. If the redcap loses their cap, they no longer benefit from fast healing and take a –4 status penalty to their damage rolls. They can create a new cap in 10 minutes, but that cap doesn't grant them powers until the redcap has turned it red with Blood Soak. A cap has no benefit for creatures other than the redcap who made it.\n\n[[Bestiary Effects/Effect_ Lost Red Cap|Effect: Lost Red Cap]]"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Divine Revulsion"
    desc: " (emotion,fear,mental) If a redcap sees a creature brandish a religious symbol of a deity (which requires an Interact action by that creature) or cast a divine spell while wearing a religious symbol, the redcap must attempt a DC 19 Will check save. They then become temporarily immune to all brandished religious symbols for 10 minutes.\n* * *\n\n**Critical Success** The redcap is unaffected.\n\n**Success** The redcap is [[Conditions/Frightened|Frightened 2]].\n\n**Failure** The redcap gains the [[Conditions/Fleeing|Fleeing]] condition for 1 round and is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Iron Boot"
    desc: "+13 (agile, versatile b)\n__Damage__  1d6 + 8 piercing"

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+15 (reach 10 feet, versatile s)\n__Damage__  1d10 + 10 slashing"

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+15 (agile, finesse, trip)\n__Damage__  1d4 + 10 slashing"

  - name: "Blood Soak"
    desc: "`pf2:1` (manipulate) The redcap dips their cap in the blood of a slain foe. The foe must have died in the last minute, and the redcap must have helped kill it. The redcap gains a +4 status bonus to damage rolls for 1 minute.\n\n[[Bestiary Effects/Effect_ Blood Soak|Effect: Blood Soak]]"

  - name: "Deadly Cleave"
    desc: "`pf2:r`  **Trigger** The redcap reduces a creature to 0 Hit Points with a sickle Strike\n* * *\n\n**Effect** The redcap makes another scythe Strike against a different creature, using the same multiple attack penalty as the sickle Strike that triggered this reaction. This counts toward their multiple attack penalty."

  - name: "Stomp"
    desc: "`pf2:1`  The redcap Strides up to half its Speed and makes a boot Strike at any point during that movement. If the boot Strike hits a [[Conditions/Prone|Prone]] creature, it deals an extra 2d6 bleed."
 
```

```encounter-table
name: Redcap
creatures:
  - 1: Redcap
```



Redcaps are sadistic and capricious fey who thrill in bloodletting and murder. While they are most famous for appearing as wizened, bearded men, redcaps of other genders are no less fearsome or cruel. However, redcaps are ultimately craven bullies, cowed by anything more powerful than themselves, a trait that leads them to fear and despise the symbols of deities.

Many fairy tales explain how the redcaps draw power from dipping the hats for which they are named in fresh blood. Just as iconic to these cruel little fey are their iron-clad boots, and the clanging sound of their metal soles clanking on stone floors is both discordant and disconcerting—especially to those who recognize the sound for what it is. Redcaps typically stand only 3 feet tall, with hunched frames, pointed ears, crooked teeth, and long, white, tangled hair.

Though unlikely to share true affection, redcaps find camaraderie in murder. Small troupes of redcaps travel together, sharing bloody kills and reminiscing on their brutal exploits. They loathe the company of most other creatures, with the notable exception of the feline fey called elananxes.
