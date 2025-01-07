---
title: "Queen Sluagh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RKjMMmcryIuVAKq7" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Queen Sluagh"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Queen Sluagh"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fey]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Greater Darkvision, Scent (Imprecise) 200 Feet"
languages: "Aklo, Common, Fey, Necril; voice of the soul"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +35, Deception: +30, Intimidation: +32, Stealth: +29, Survival: +31"
abilityMods: [9, 5, 9, 7, 7, 4]
speed: 30 feet,  fly 80 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +35, __Ref__ +27, __Will__ +33"
hp: 417
health:
  - name: ""
  - name: HP
    desc: "417, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Weaknesses__ cold iron 15, vitality 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 120 feet. DC 37 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Soulscent (Imprecise) 200 feet"
    desc: " (occult) The sluagh is aware of all doomed creatures, dying creatures, and creatures that died within the last hour within the listed range."

  - name: "Voice of the Soul"
    desc: "  A sluagh queen knows any language of a creature whose soul they've devoured and can perfectly mimic its voice by attempting a Deception check to Lie, with a +4 circumstance bonus."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Proboscis"
    desc: "+35 (reach 20 feet)\n__Damage__  3d10 + 17 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, magical)\n__Damage__  3d10 + 17 slashing"

  - name: "**Ranged** `pf2:1` Negative Ray"
    desc: "+31 (magical, range increment 100 feet, void)\n__Damage__  7d8 void"

  - name: "Primal Innate Spells"
    desc: "DC 41, attack +33; __9th __  _[[Spells/Overwhelming Presence|Overwhelming Presence]]_; __7th __  _[[Spells/Visions of Danger|Visions of Danger (A Swarm of Sluagh Reapers)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Ghost Sound|Ghost Sound]]_"

  - name: "Call of the Damned"
    desc: "`pf2:2` (auditory) The queen sends out shriek to all sluagh within 1 mile, summoning them to her. This typically calls 2d4 [[Book of the Dead/Sluagh Reaper|Sluagh Reapers]]. If the queen is facing foes strong enough to threaten her, these are likely too weak to pose a threat but can assist by fetching items or getting in enemies' way."

  - name: "Eat Soul"
    desc: "`pf2:2` (occult) The queen touches a dying creature or a creature that died within the past 1 hour with her proboscis. If the target is dying, it must attempt a DC 41 Fortitude check save; on a failure, its dying value increases by 2 (3 on a critical failure). If the target is dead, the queen devours the soul. Unless the queen is destroyed, the target can't be returned to life through any means, even powerful magic such as [[Spells/Wish|Wish]]."

  - name: "Ghostly Swoop"
    desc: "`pf2:1`  The queen sluagh becomes incorporeal until the start of their next turn, and Flies up to their fly Speed. While incorporeal, they are immune to precision damage, and have resistance 10 to all damage (except force, ghost touch, or vitality); this resistance is doubled against non-magical damage.\n\nAfter using Ghostly Swoop, the queen sluagh can't use it again for 1d4 rounds."

  - name: "Soul Theft"
    desc: "`pf2:1` (occult,void) **Requirements** The queen has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] with her proboscis\n* * *\n\n**Effect** The queen devours a portion of the creature's soul and steals some of its ability. The creature takes 5d8 void damage (DC 41 Fortitude check save). The queen gains temporary HP equal to the total amount of HP the target loses, including any HP lost from being drained.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is [[Conditions/Drained|Drained 1]].\n\n**Failure** The creature takes full damage and is drained 1 and [[Conditions/Doomed|Doomed 1]]. The queen steals a spell slot or training. If she steals a spell from a prepared caster, she transfers the spell to herself; if she steals from a spontaneous caster, she gains a prepared spell of the appropriate rank and expends one of the creature's spell slots of that rank. If she steals training, she chooses Perception, attack modifier, or any skill. For 24 hours, she gains a +2 status bonus to that statistic and the creature takes a -2 status penalty. The queen can have any number of stolen abilities, but only one from each creature.\n\n**Critical Failure** As failure, but double damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Queen Sluagh
creatures:
  - 1: Queen Sluagh
```



A queen sluagh grows more powerful by devouring souls collected from underlings or drained directly through her proboscis. The muscular tongue inside is tipped with a cartilaginous, barbed quill that feeds the queen not only the soul, but the strengths of its owner. A queen conceals her nest deep in a secluded area, such as a forest or graveyard.

* * *

A soul about to leave its physical body gives off a peculiar scent, usually unnoticed by mortal creatures. But the undead fey called sluagh can smell and track down its location with frightening ease. Unlike most fey, sluagh are undead, possessing strong connections to void energy and mortal souls. Sluagh collect the souls of those close to death and bring them to feed their queen.

Most sluagh appear bald-headed, with rounded ears, sharp teeth, glossy black eyes, and scrawny bodies. Their rib cages show through their skin, which is translucent and soft as velvet.

Sluagh can become ghostly and incorporeal for brief periods. They use this power to stalk their prey to great effect. Sometimes the glimpse of a sluagh is mistaken for a ghost sighting.
