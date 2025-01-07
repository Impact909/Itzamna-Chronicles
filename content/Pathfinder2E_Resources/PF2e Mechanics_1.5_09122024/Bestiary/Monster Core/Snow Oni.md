---
title: "Snow Oni"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0bXbQz6jw7QlP0Sj" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oni
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Snow Oni"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Snow Oni"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[cold]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[oni]]
trait_05: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +25, Deception: +27"
abilityMods: [8, 5, 5, 0, 5, 8]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +25, __Will__ +21"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  cold; __Weaknesses__ spirit 15, Bean Panic 1"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Snow Vision"
    desc: "  Snow doesn't impair the snow oni's vision; they ignore concealment from snowfall."

abilities_mid:
  - name: ""
  - name: "Bean Panic"
    desc: "  Oni are curiously afraid of beans, especially as the seasons begin to change. If a creature Interacts to throw a handful of beans at the oni, the oni becomes [[Conditions/Frightened|Frightened 2]]. While frightened this way, their weakness to spirit damage is increased by 5. The oni then becomes immune to bean panic for 24 hours."

  - name: "Icy Deflection"
    desc: "`pf2:r`  **Trigger** The snow oni is targeted by a ranged Strike or spell attack roll that doesn't have the fire trait\n* * *\n\n**Effect** The snow oni creates a reflective blockade of ice, gaining a +4 circumstance bonus to AC against the triggering attack roll. If the attack misses, the snow oni redirects the attack to another creature within 20 feet of the snow oni. The attacker rerolls the attack roll against the new target."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+27 (agile, magical, reach 10 feet)\n__Damage__  2d8 + 16 bludgeoning 2d6 cold"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (magical, reach 10 feet)\n__Damage__  2d6 + 16 piercing 1d6 bleed"

  - name: "**Ranged** `pf2:1` Ice Dart"
    desc: "+25 (cold, magical, range increment 60 feet)\n__Damage__  3d10 + 4 cold 1d6 spirit"

  - name: "Primal Innate Spells"
    desc: "DC 31, attack +23; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) The snow oni can take on the appearance of any Medium or Large humanoid creature. This doesn't change their Speed or their attack and damage bonuses with their Strikes but might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Chilling Combo"
    desc: "`pf2:1` (cold) The snow oni makes two fist Strikes targeting the same creature. If they both hit, the target becomes [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "Falling Frozen Lightning"
    desc: "`pf2:2` (cold,primal) The snow oni calls down a bolt of icy lightning, white as fallen snow. The bolt strikes a location within 60 feet, freezing the air into a cloud of snow that fills a 20-foot burst and lasts for 1 minute.\n\nAll creatures within the snow become [[Conditions/Concealed|Concealed]], and all creatures outside the snow become concealed to creatures within it. A creature that enters the snow or begins its turn there takes 15 cold damage, with a DC 33 Fortitude check save."
 
```

```encounter-table
name: Snow Oni
creatures:
  - 1: Snow Oni
```



Snow oni maintain their seething temperaments even in their icy homes. The isolation of their environment gives them trappings of asceticism, and many snow oni pursue physical perfection, reveling in the process of turning their bodies into powerful fighting machines. They are just as hedonistic and brutal as any of their brethren, however, and eager to indulge in warm baths, strong drink, and humanoid flesh.

Like many oni, snow oni possess a third eye in the center of their forehead. This eye gives snow oni a mystical sense that allows them to peer through even the thickest flurries of snow.

* * *

Oni are large, brutal creatures originating in Tian Xia who resemble humanoids with brightly colored skin, tusks, and horns. Though commonly mistaken for fiends, the first oni were originally kami, tutelary nature spirits. These kami suffered a terrible trauma, losing their sacred wards to dramatic disasters or the callousness of others, and as a result transformed into the violent creatures they are today. While some believe that oni can be spiritually placated through proper ritual worship that transforms them back into kami, many of these would-be saviors fall to oni's notorious brute strength, flesh-rending teeth, and command of storms.

Oni possess the ability to disguise themselves as other humanoids. They are rarely creative in their disguises, often choosing a specific appearance similar to their oni form and sticking with it. This simplicity catches many by surprise, however, as people assume oni are limited to a single alternate form, which is by no means the case.
