---
title: "Alethsia"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.U7cdt9TRDG2EIZ5o" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Alethsia"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Alethsia"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Deception: +18, Diplomacy: +16, Stealth: +18"
abilityMods: [2, 5, 4, 2, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 27
armorclass:
  - name: AC
    desc: "27 all-around vision; __Fort__ +17, __Ref__ +18, __Will__ +16"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+1 Composite Shortbow]], [[Equipment/Shortsword|Shortsword]], 60x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Biting Snakes"
    desc: "`pf2:r`  **Trigger** A creature ends its turn adjacent to the medusa.\n* * *\n\n**Effect** The medusa makes a snake fangs Strike against the creature."

  - name: "Glass Gaze"
    desc: " (arcane,aura,visual) 30 feet. When a creature ends its turn in the aura, it must attempt a DC 25 Fortitude check save. If the creature fails, it becomes [[Conditions/Slowed|Slowed 1]] for 1 minute. The medusa can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+18 (agile, finesse, versatile s)\n__Damage__  1d6 + 10 piercing plus serpent-venom"

  - name: "**Melee** `pf2:1` Snake Fangs"
    desc: "+16 (agile, finesse)\n__Damage__  1d4 + 10 piercing plus serpent-venom"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+19 (deadly d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  1d6 + 9 piercing plus serpent-venom"

  - name: "Focus Gaze"
    desc: "`pf2:1` (arcane,concentrate,incapacitation,visual) The medusa fixes their glare at a creature they can see within 30 feet. The target must immediately attempt a DC 25 Fortitude check save against the medusa's glass gaze. If the creature was already [[Conditions/Slowed|Slowed]] by glass gaze before attempting its save, a failed save causes it to be [[Conditions/Petrified|Petrified]] permanently.\n\nAfter attempting its save, the creature is then temporarily immune until the start of the medusa's next turn."

  - name: "Serpent Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"
 
```

```encounter-table
name: Alethsia
creatures:
  - 1: Alethsia
```


Variant elite medusa

Monstrous humanoids that resemble humans with snakes instead of hair, medusas are best known for their petrifying gazes that-if lingered upon-can permanently transform mortals to stone. Medusas are shrewd and manipulative adversaries who collect and covet secrets, and who use threats and guile to exploit the fears of weaker creatures. A medusa may seek out powerful magic items, use divination magic to discover secret knowledge and unlock forbidden power, or infiltrate a society to beguile influential politicians. Their ability to worm their way into powerful organizations makes them natural leaders of criminal outfits and thieves' guilds, and their interest in magical phenomena leads some to pursue careers as oracles who offer to help adventurers find what they seek-for a price. Of course, if wit and deception proves insufficient, a medusa can always simply turn rivals into ornate stone decorations with little more than a glare.

Exceptionally agile and surprisingly hardy, a medusa rarely backs down from a conflict even when cornered. Many adventurers who thought themselves readied to resist the effects of a medusa's gaze have nevertheless fallen to a medusa, as these creatures are also often deadly archers able to riddle their foes with venom-coated arrows from a distance. Still, a medusa may barter for their life if no alternatives remain, and the secrets carried by these powerful villains often make it more than worth sparing the monster's life.
