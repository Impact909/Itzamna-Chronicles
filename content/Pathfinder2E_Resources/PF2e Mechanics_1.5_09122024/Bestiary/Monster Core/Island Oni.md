---
title: "Island Oni"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.m0DYchO7Riz2siC6" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oni
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Island Oni"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Island Oni"
level: "Creature 17"

alignment: ""
size: "huge"
trait_01: [[giant]]
trait_02: [[humanoid]]
trait_03: [[oni]]
trait_04: [[water]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Greater Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +33, Deception: +32, Intimidation: +32, Nature: +29"
abilityMods: [9, 6, 6, 2, 9, 6]
speed: 40 feet,  fly 40 feet,  swim 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +26, __Ref__ +28, __Will__ +34; +1 status to all saves vs. water"
hp: 390
health:
  - name: ""
  - name: HP
    desc: "390; __Immunities__  electricity; __Weaknesses__ spirit 20, Bean Panic 1"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|+2 Greater Striking Longspear]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Mist Vision"
    desc: "  The island oni ignores the [[Conditions/Concealed|Concealed]] condition from fog and mist."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Bean Panic"
    desc: "  Oni are curiously afraid of beans, especially as the seasons begin to change. If a creature Interacts to throw a handful of beans at the oni, the oni becomes [[Conditions/Frightened|Frightened 2]]. While frightened this way, their weakness to spirit damage is increased by 5. The oni then becomes immune to bean panic for 24 hours."

  - name: "Lost Oni Island"
    desc: " (aura,primal) An island oni can claim an island of up to 1-mile radius in a process that takes 1 week, during which the oni must defeat any who come to challenge its claim. If successful, the oni can freely control the weather on its island and in a 1-mile radius from the shore, with the effect of a successful [[Spells/Control Weather|Control Weather]] ritual.\n\nThis altered weather surrounds the island in thick fog, seaborne mirages, or other phenomena that increase the DC of checks to locate and navigate to the island (Such as Sailing Lore or Survival) to 40, though the oni can allow allies to pass freely. If the oni dies or leaves the island, the weather returns to normal immediately."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+35 (magical, reach 20 feet)\n__Damage__  3d8 + 10 piercing 2d6 electricity"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 15 feet)\n__Damage__  3d6 + 10 piercing plus improved-grab 2d6 electricity plus improved-grab"

  - name: "**Ranged** `pf2:1` Thunderbolt"
    desc: "+30 (electricity, magical, range increment 60 feet)\n__Damage__  3d12 + 12 electricity"

  - name: "Primal Innate Spells"
    desc: "DC 37, attack +29; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_\n__Constant__  __(9th)__ _[[Spells/Water Walk|Water Walk]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) The island oni can take on the appearance of any Medium or Large humanoid creature. This doesn't change their Speed or their attack and damage bonuses with their Strikes but might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Conductive Downpour"
    desc: "`pf2:2` (electricity,primal,water) The island oni fires a bolt of lightning into the air, which immediately roils with dark clouds. Rain falls in a 60-foot radius emanation, centered on the oni, for 1 minute, filling the air and pooling on the ground.\n\nCreatures in the aura gain weakness 10 to electricity, and the entire area is greater difficult terrain for Flying creatures, and difficult terrain for creatures on the ground or Climbing, unless they also have a swim Speed.\n\n[[Bestiary Effects/Effect_ Conductive Downpour|Effect: Conductive Downpour]]"

  - name: "Electrifying Pierce"
    desc: "`pf2:1` (electricity,primal) **Requirements** The island oni's last action was a successful longspear Strike against a Medium or smaller target\n* * *\n\n**Effect** The island oni drives the spear through the target and calls lightning to strike the spear. The target takes 6d6 electricity damage with a DC 37 Fortitude check save. On a failure, the creature is also impaled on the spear. It's [[Conditions/Grabbed|Grabbed]], and if the oni moves, they bring the grabbed creature along with them.\n\nThe island oni doesn't need to use additional actions to keep the creature grabbed; the creature remains grabbed as long as it's impaled. The grabbed creature can attempt to [[Actions/Escape|Escape]] as normal. The island oni can only have one creature impaled this way at a time."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 3d8+10 bludgeoning, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Tripping Tide"
    desc: "`pf2:2` (water) The island oni sweeps their spear in a full circle, releasing waves of seawater. All creatures in a 20-foot emanation must succeed a DC 37 Reflex check saving throw or fall [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Island Oni
creatures:
  - 1: Island Oni
```



Island oni are those powerful enough to claim small coastal islands, often creating makeshift armies of lesser oni who pillage surrounding lands and waters. Island oni hoard this material wealth, garbing themselves in luxurious clothing and adorning their monstrous faces with all manner of jewelry.

Island oni typically scavenge sunken shipwrecks for weapons, armor, and treasure. This can also bring them into contact with undead sailors, which island oni have been known to press into service.

* * *

Oni are large, brutal creatures originating in Tian Xia who resemble humanoids with brightly colored skin, tusks, and horns. Though commonly mistaken for fiends, the first oni were originally kami, tutelary nature spirits. These kami suffered a terrible trauma, losing their sacred wards to dramatic disasters or the callousness of others, and as a result transformed into the violent creatures they are today. While some believe that oni can be spiritually placated through proper ritual worship that transforms them back into kami, many of these would-be saviors fall to oni's notorious brute strength, flesh-rending teeth, and command of storms.

Oni possess the ability to disguise themselves as other humanoids. They are rarely creative in their disguises, often choosing a specific appearance similar to their oni form and sticking with it. This simplicity catches many by surprise, however, as people assume oni are limited to a single alternate form, which is by no means the case.
