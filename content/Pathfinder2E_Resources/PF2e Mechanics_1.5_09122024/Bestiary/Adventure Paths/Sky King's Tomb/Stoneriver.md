---
title: "Stoneriver"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.B2fdfifAiMaeb3DY" 
tags:
  - pf2e/creature/type/celestial
  - pf2e/creature/type/fire
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Stoneriver"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Stoneriver"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[celestial]]
trait_02: [[fire]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +26, Diplomacy: +21, Intimidation: +21, Stealth: +20, Survival: +23, Torag Lore: +24"
abilityMods: [8, 4, 7, 4, 5, 5]
speed: 30 feet,  burrow 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +25, __Ref__ +20, __Will__ +21; +2 status to all saves vs. magic"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, regeneration 30 (deactivated by cold or unholy); __Immunities__  fear effects,  fire; __Weaknesses__ cold 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 30 (Deactivated by Cold or Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Bolster Torag's Chosen"
    desc: " (aura,divine) 20 feet. Dwarves and creatures that worship Torag in the area gain a +1 status bonus to AC and Will saves."

  - name: "[[Bestiary Ability Glossary/Retributive Strike|Retributive Strike]]"
    desc: "`pf2:r`  **Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+26 (disarm, holy, magical, reach 30 feet)\n__Damage__  3d6 + 11 bludgeoning plus improved-grab 1d6 spirit plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile, holy, magical, reach 20 feet)\n__Damage__  1d6 fire 3d8 + 11 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+26 (backswing, fatal d12, holy, magical, reach 20 feet)\n__Damage__  1d6 fire 3d8 + 11 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +21; __5th __  _[[Spells/Blazing Fissure|Blazing Fissure]]_, _[[Spells/Flame Strike|Flame Strike]]_; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Holy Light|Searing Light (x2)]]_; __3rd __  _[[Spells/Heal|Heal (x2)]]_; __2nd __  _[[Spells/Clear Mind|Remove Fear (At Will)]]_, _[[Spells/Restoration|Restoration]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will, Evil Only)]]_\n__Cantrips__  __(6th)__ _[[Spells/Light|Light]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Devour Magic"
    desc: " (divine) Whenever Stoneriver deals damage with Swallow Whole, he consumes one of the swallowed creature's magical effects, as [[Spells/Dispel Magic|Dispel Magic]] with a +21 counteract modifier."

  - name: "Measure Soul"
    desc: "`pf2:1` (concentrate,divine,mental) Stoneriver mentally pries through the mind of a creature within 60 feet, dealing 10d8 mental damage (DC 29 Will check save). Stoneriver can choose to make this damage nonlethal or choose not to damage the creature at all. For 1 minute, Stoneriver gains a +1 circumstance bonus to attack rolls, damage rolls, and Perception checks against that creature. If the creature is evil and it failed its save, the creature is additionally [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 4]] on a critical failure). Stoneriver can't use Measure Soul again for 1d4 rounds."

  - name: "Rock Tunneler"
    desc: "  Stoneriver can burrow through solid stone, leaving behind a tunnel if he desires."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 6d6 bludgeoning plus 2d6 fire and devour magic, Rupture 40\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Stoneriver
creatures:
  - 1: Stoneriver
```



A servant of Torag, Stoneriver resembles a pangolin with glowing blue eyes and brassy, rune-covered scales. Stoneriver burrows through Golarion's mantle and crust as he hunts down subterranean fiends, aids virtuous communities, and defends sacred sites, often collaborating with dwarves.

## Forgeheart Five

Stoneriver has fathered numerous children through the years, each clever, brave, and bold. Among these, five have joined together to combat evil as a team. Calling themselves the Forgeheart Five, these overly optimistic and bombastic creatures strive to be as virtuous and heroic as their father. Thus far, their methods have been more flashy than effective.
