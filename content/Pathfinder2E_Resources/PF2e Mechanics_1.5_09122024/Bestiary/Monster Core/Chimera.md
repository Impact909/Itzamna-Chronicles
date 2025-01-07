---
title: "Chimera"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nweEIH0UIeYGTwAA" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Chimera"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Chimera"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +18, Stealth: +18"
abilityMods: [6, 2, 4, -3, 2, 0]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +16, __Will__ +14"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Multiple Reactions"
    desc: "  A chimera gains 2 extra reactions each round that it can use only to make Reactive Strikes. It must use a different head for each reaction, and it can't use more than one on the same triggering action. If it loses one of its heads, it also loses one of these extra reactions."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Three Headed"
    desc: "  Any ability that would sever a chimera's head (such as a critical hit with a _[[Equipment/Vorpal|Vorpal Weapon]]_) severs one head at random. Losing a head doesn't kill a chimera (as long as it has one head left), but it does prevent it from making Strikes with the lost head or using the head's Dragon Breath."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dragon Jaws"
    desc: "+20 ()\n__Damage__  2d6 + 9 piercing"

  - name: "**Melee** `pf2:1` Lion Jaws"
    desc: "+20 ()\n__Damage__  2d10 + 9 piercing"

  - name: "**Melee** `pf2:1` Goat Horns"
    desc: "+20 ()\n__Damage__  2d10 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d6 + 9 slashing"

  - name: "Draconic Bite"
    desc: "  A chimera's dragon head deals an extra 2d6 untyped damage of a type matching the damage dealt by its Dragon Breath."

  - name: "Dragon Breath"
    desc: "`pf2:2` (arcane) The chimera breathes a cone or line that deals 9d6 damage to all creatures in the area (DC 26 basic save of a type indicated below). The chimera's dragon head is linked to one of the traditions of magic, which determines the area of its Dragon Breath, the type of damage it deals, and the type of save to avoid it. This ability gains the related traits.\n\nThe chimera can't use Dragon Breath again for 1d4 rounds.\n\n*   **Arcane** 60-foot line of force (DC 26 Reflex check)\n*   **Divine** 60-foot line of spirit (DC 26 Reflex check); this ability can also have the holy or unholy trait\n*   **Occult** 30-foot cone of mental (DC 26 Will check)\n*   **Primal** 30-foot cone of acid, cold, electricity, fire, or sonic (DC 26 Reflex check); or poison (DC 26 Fortitude check)"

  - name: "Three-Headed Strike"
    desc: "`pf2:2`  The chimera makes a Strike with its dragon jaws, lion jaws, and goat horns, each at a -2 penalty and targeting a different creature. These Strikes count as only one attack for the chimera's multiple attack penalty, and the penalty doesn't increase until after it has made all three attacks."
 
```

```encounter-table
name: Chimera
creatures:
  - 1: Chimera
```



The chimera is the archetypal example of an unnatural monster made up of a monstrous mix of wildly different component creatures: in this case, a lion, a dragon, and a goat. Wild, hateful, and hungry, it tries to eat any creature it sees, but sometimes a strong-willed master is able to compel a chimera to serve as a guardian or even a mount. If such an individual ever loses their control over the chimera, they are often the first to be devoured.
