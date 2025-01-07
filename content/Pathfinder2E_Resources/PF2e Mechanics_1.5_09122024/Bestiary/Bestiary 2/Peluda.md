---
title: "Peluda"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QmzRsmqb1n5jD8ar" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Peluda"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Peluda"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[evil]]
trait_03: [[fire]]
trait_04: [[lawful]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +19"
abilityMods: [7, 3, 5, -2, 5, 3]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +17, __Will__ +19; +1 status to all saves vs. magic"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  fire,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Quill Thrust"
    desc: "`pf2:r`  **Trigger** A creature within 10 feet attempts a melee Strike against the peluda\n* * *\n\n**Effect** The peluda shifts their position and makes a quill Strike against the attacking creature. This Strike doesn't count toward the peluda's multiple attack penalty, and the peluda's multiple attack penalty doesn't apply to this Strike."

  - name: "Vulnerable Tail"
    desc: "  If the peluda takes 30 or more slashing damage from a critical hit, the attacker severs the peluda's tail. The peluda takes 2d6 bleed and can't make tail attacks until their tail grows back (in about 1 week)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (reach 10 feet)\n__Damage__  2d12 + 13 piercing"

  - name: "**Melee** `pf2:1` Quill"
    desc: "+23 (agile, reach 10 feet)\n__Damage__  2d6 piercing plus peluda-venom"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+23 (reach 15 feet, versatile p)\n__Damage__  2d6 + 13 bludgeoning plus improved-knockdown"

  - name: "Breath Weapon"
    desc: "`pf2:2` (fire,primal) The peluda breathes a torrent of flames that deals 7d10 fire damage in a 60-foot line (DC 29 Reflex check save).\n\nThey can't use their Breath Weapon again for 1d4 rounds."

  - name: "Peluda Venom"
    desc: " (poison) **Saving Throw** DC 29 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 2d6 poison damage, [[Conditions/Enfeebled|Enfeebled 1]], and off-guard (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Enfeebled|Enfeebled 2]], and off-guard (1 round)"

  - name: "Quill Barrage"
    desc: "`pf2:2`  The peluda bristles their quills and shakes, sending dozens of spear-like barbs in every direction. All creatures within 30 feet take 11d6 piercing damage (DC 29 Reflex check save) and are exposed to peluda venom if they take any damage.\n\nThe peluda can't use Quill Barrage again for 1 minute."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Peluda
creatures:
  - 1: Peluda
```



Peludas are wild and savage dragons that favor reedy marshlands, sparsely forested bogs, and river valleys for lairs. A single peluda typically claims a stretch of waterways a few miles in length, then systematically drives off any potential rivals so that the peluda can despoil the land as they please, leaving clawed footprints on muddy riverbanks, toppling trees, and impaling half-eaten corpses on their quills as trophies left to rot. They venture beyond their domains to hunt, roasting prey with their breath or pulverizing them with their tails, burning and killing for cruel sport before slithering, sated, back to their mucky lairs.

Peludas despise weakness and loathe creatures smaller than themselves, especially humanoids, whom they see as fragile and soft, good only for eating or breaking. In contrast, peludas have a massive inferiority complex regarding more impressive creatures-especially larger and stronger dragons. Peludas will try anything to become stronger, including ingesting shiny coins, gems, and jewelry, which old folk tales claim will strengthen their quills and fire breath.
