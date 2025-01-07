---
title: "Waldgeist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Ud8NDmIcXcp2jjzC" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/incorporeal
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Waldgeist"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Waldgeist"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[spirit]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[incorporeal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Arboreal, Common, Fey; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Intimidation: +16, Nature: +18, Stealth: +18, Woodland Lore (Applies Only to the Woodland the Waldgeist is Bonded To): +21"
abilityMods: [-5, 6, 3, 3, 6, 4]
speed:  fly 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +16, __Will__ +18"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Forest Guardian"
    desc: "  A waldgeist is compelled to investigate the sound of wood or trees being damaged, such as by being burned or chopped down. A waldgeist that hears such a sound must succeed at a DC 26 Will check save or spend all their actions moving toward the sound until they identify the cause. This can't be used to compel a waldgeist to leave their bonded woodland. A waldgeist that succeeds at their saving throw is temporarily immune for 10 minutes."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Woodland Dependent"
    desc: "  A waldgeist is mystically bonded to a single forest, jungle, orchard, grove, or other similar large, wooded area and must remain within it. If the waldgeist moves outside their bonded woodland, they're immediately destroyed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Lignifying Hand"
    desc: "+18 (finesse, magical)\n__Damage__  2d8 + 7 void plus lignify"

  - name: "Primal Innate Spells"
    desc: "DC 24, attack +16; __5th __  _[[Spells/Nature's Pathway|Tree Stride]]_; __3rd __  _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __  _[[Spells/Entangling Flora|Entangle (At-Will)]]_\n__Cantrips__  __(4th)__ _[[Spells/Tangle Vine|Tanglefoot]]_\n__Constant__  __(4th)__ _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Lignify"
    desc: " (incapacitation,primal) The touch of a waldgeist transforms flesh into wood. A living creature damaged by the waldgeist's lignifying hand Strike must succeed at a DC 24 Fortitude check save or become [[Conditions/Slowed|Slowed 1]] (or [[Conditions/Slowed|Slowed 2]] on a critical failure). Further failed saves against lignify increases the slowed condition. Once a creature's actions are reduced to 0 by lignify, that creature becomes [[Conditions/Petrified|Petrified]], except they're transformed into wood instead of stone."

  - name: "Possess Tree"
    desc: "`pf2:2` (primal) **Frequency** once per 10 minutes\n* * *\n\n**Effect** The waldgeist touches a tree to merge with it, possessing it for up to 1 minute. They can end this possession early as a free action at the start of their turn. While the waldgeist possesses a tree, they lose the incorporeal trait, fly Speed, all resistances, their non-constant spells, and their lignifying hand Strike. Additionally, their size increases to Huge, they gain resistance 5 to bludgeoning and piercing damage, weakness 10 to fire, Speed 20 feet, and the following branch Strike.\n\n**Melee** `pf2:1` branch (reach 15 feet) +20, **Damage** 2d12+9 bludgeoning.\n\nWhile a waldgeist possesses a tree, any damage that would be dealt to the waldgeist is instead dealt to the tree. The tree has 60 Hit Points. When the tree is reduced to 0 Hit Points, the waldgeist is immediately ejected, and the tree is destroyed."
 
```

```encounter-table
name: Waldgeist
creatures:
  - 1: Waldgeist
```



Waldgeists act as avatars of nature that seek vengeance for environmental abuse, such as pollution and deforestation. These undead spirits of destroyed trees form at the site of their destruction or in a nearby woodland, if the original location was entirely razed. They become guardians of the forest, possessing power over the plants within its boundaries. Waldgeists show no mercy to anyone caught damaging their bonded woodland, attacking loggers, fey, travelers, and invasive species with equal prejudice.

* * *

When disaster befalls the natural world, a different kind of undead may rise, entirely unlike risen humanoids. Most plants, fish, insects, and other animals don't possess a psychology complex enough to experience the emotional catharsis required to return as undead without intervention from an outside force. Mass extinction can serve as that outside force.

Humanoids clear-cutting an entire forest or a seaside community wiping out a species critical to their ecosystem can spawn a verdorite. The collective spiritual energy and emotional distress of a dying biome powers these undead, formed as conglomerates or representatives.
