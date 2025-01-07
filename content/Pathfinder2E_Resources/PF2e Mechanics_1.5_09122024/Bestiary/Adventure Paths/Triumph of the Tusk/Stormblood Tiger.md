---
title: "Stormblood Tiger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.snzofTr1NkgCTq22" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Stormblood Tiger"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Stormblood Tiger"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[humanoid]]
trait_03: [[orc]]
trait_04: [[werecreature]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Orcish; Tiger empathy"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Stealth: +17, Survival: +15"
abilityMods: [6, 5, 4, 2, 3, 3]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +18, __Will__ +12"
hp: 114
health:
  - name: ""
  - name: HP
    desc: "114; __Weaknesses__ silver 7"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+1 Battle Axe, Hide Armor"
  - name: "Tiger Empathy"
    desc: "  The stormblood tiger can communicate with felines."

abilities_mid:
  - name: ""
  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+17 (magical, sweep)\n__Damage__  1d8 + 12 slashing"

  - name: "Change Shape"
    desc: "`pf2:1` (concentrate,polymorph) Orc with fist +16 for 1d4+12 bludgeoning, or tiger with Speed 30 feet and Wrestle.\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Curse of the Stormblood Tiger"
    desc: " (curse,primal) This curse only affects humanoids.\n\n**Saving Throw** DC 22 Fortitude check. Each night of flood season, the cursed creature must succeed at another Fortitude save or transform into a stormblood tiger until dawn. The creature is under the GM's control and goes on a rampage for half the night before falling [[Conditions/Unconscious|Unconscious]] until dawn."

  - name: "Flood Frenzy"
    desc: " (polymorph,primal) As the night falls in flood season, the stormblood tiger must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws Strike by 2. When the sun rises or the lands dry again, the stormblood tiger returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 24 hours."

  - name: "Rend"
    desc: "`pf2:1`  Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Sudden Pounce"
    desc: "`pf2:2`  Imbued with an insatiable predatory instinct, stormblood tiger Leaps up to 15 feet and makes a claw Strike at the end of that movement. If the attack hits, the stormblood tiger can immediately Rend."

  - name: "Wrestle"
    desc: "`pf2:1`  The tiger makes a claw Strike against a creature it is [[Conditions/Grabbed|Grabbing]]. If the attack hits, that creature is knocked [[Conditions/Prone|Prone]]."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Stormblood Tiger
creatures:
  - 1: Stormblood Tiger
```



Whereas most werecreatures follow the monthly rhythms of the full moon, the stormblood tiger's change is connected to the floods brought by annual rainfall. In parts of the world where flooding or heavy rains are both regular and predictable, such as during the Deluge in Belkzen, these lycanthropes stalk the land hunting for prey. Every night after the floods begin, a stormblood tiger is forced into its hybrid form until sun rises or the waters recede, usually 2–3 months later. The remainder of the year, stormblood tigers walk undetected among the population, often mistaken for hunters or scouts.

## Sought Out

Because of the stormblood tiger's fearsome reputation and powerful abilities, some foolhardy orc warriors view becoming a stormblood tiger as a path to greatness—a blessing instead of a curse. In their minds, it's more important to have this power at hand during times of conflict than worry about disrupting peace during the Flood Truce. Wiser voices argue that too many stormblood tigers roaming about during the Flood Truce risks ending the accord altogether.
