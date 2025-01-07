---
title: "Caldera Oni"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V16L7TZiOeEelBRq" 
tags:
  - pf2e/creature/type/fire
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oni
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Caldera Oni"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Caldera Oni"
level: "Creature 14"

alignment: ""
size: "Large"
trait_01: [[fire]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[oni]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +27, Crafting: +25, Deception: +27, Intimidation: +27"
abilityMods: [8, 6, 6, 0, 6, 8]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +28, __Ref__ +25, __Will__ +23"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315; __Immunities__  fire; __Weaknesses__ spirit 15, Bean Panic 1"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Katana|+2 Striking Katana]], [[Equipment/Breastplate|+1 Resilient Breastplate]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Bean Panic"
    desc: "  Oni are curiously afraid of beans, especially as the seasons begin to change. If a creature Interacts to throw a handful of beans at the oni, the oni becomes [[Conditions/Frightened|Frightened 2]]. While frightened this way, their weakness to spirit damage is increased by 5. The oni then becomes immune to bean panic for 24 hours."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Stoke the Volcano"
    desc: "  When the caldera oni is critically hit, the flames of anger grow within them. They recharge their choice of Ash Form or Dance of Burning War."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Katana"
    desc: "+30 (deadly d8, magical, two-hand d10, versatile p)\n__Damage__  2d6 + 14 slashing 2d6 fire"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (magical, reach 10 feet)\n__Damage__  2d6 + 14 piercing 1d8 bleed"

  - name: "Primal Innate Spells"
    desc: "DC 34, attack +26; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_"

  - name: "Ash Form"
    desc: "`pf2:2` (polymorph,primal) **Frequency** once per minute\n* * *\n\n**Effect** The caldera oni transforms into a cloud of sparking volcanic ash and then Flies. This movement doesn't trigger reactions, and the caldera oni can move through small gaps and spaces occupied by other creatures.\n\nThe caldera oni then returns to its physical form, affected by a 4th-rank [[Spells/Enlarge|Enlarge]] spell with a duration of 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) The caldera oni can take on the appearance of any Medium or Large humanoid creature. This doesn't change their Speed or their attack and damage bonuses with their Strikes but might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Dance of Burning War"
    desc: "`pf2:3`  **Frequency** once per minute\n* * *\n\n**Effect** The oni's heat becomes overwhelming, causing them to breathe out superheated ash and dance across the battlefield. The caldera oni Strides, then makes a melee Strike. If the Strike hits, the oni can Stride again and Strike again, repeating this until they have either missed with a Strike or made three Strikes total.\n\nThe oni then finishes the dance by calling down volcanic lightning through the cloud of ash. Each creature hit by a Strike during the dance takes 3d6 fire damage and 3d6 electricity damage with a DC 34 Reflex check save."
 
```

```encounter-table
name: Caldera Oni
creatures:
  - 1: Caldera Oni
```



As hot-blooded as the lava that floods their homes, caldera oni have an incredible appetite for the thrill of war. While they engage in battle to conquer and control others, fire oni also love the thrill of combat, fighting for the sheer joy of it. Presenting a caldera oni with a true challenge can potentially earn their mercy and an offer to serve at their side.

* * *

Oni are large, brutal creatures originating in Tian Xia who resemble humanoids with brightly colored skin, tusks, and horns. Though commonly mistaken for fiends, the first oni were originally kami, tutelary nature spirits. These kami suffered a terrible trauma, losing their sacred wards to dramatic disasters or the callousness of others, and as a result transformed into the violent creatures they are today. While some believe that oni can be spiritually placated through proper ritual worship that transforms them back into kami, many of these would-be saviors fall to oni's notorious brute strength, flesh-rending teeth, and command of storms.

Oni possess the ability to disguise themselves as other humanoids. They are rarely creative in their disguises, often choosing a specific appearance similar to their oni form and sticking with it. This simplicity catches many by surprise, however, as people assume oni are limited to a single alternate form, which is by no means the case.
