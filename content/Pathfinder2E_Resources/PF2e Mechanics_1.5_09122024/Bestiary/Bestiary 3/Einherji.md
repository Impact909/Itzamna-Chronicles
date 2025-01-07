---
title: "Einherji"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UtLRP0c3ODUHPv81" 
tags:
  - pf2e/creature/type/aesir
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Einherji"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Einherji"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[aesir]]
trait_02: [[chaotic]]
trait_03: [[monitor]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Hallit, Jotun"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Crafting: +16, Intimidation: +21"
abilityMods: [7, 4, 6, 0, 1, 3]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +18, __Will__ +17; +4 to will saves vs. fear"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Resistances__ piercing 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|+1 Striking Returning Dagger]], [[Equipment/Longsword|+1 Striking Longsword]], [[Equipment/Wooden Shield|Duskwood Shield]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+24 (versatile p)\n__Damage__  2d8 + 13 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (agile)\n__Damage__  2d6 + 13 bludgeoning"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+24 (agile, versatile s)\n__Damage__  2d4 + 13 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+21 (agile, thrown 10 ft., versatile s)\n__Damage__  2d4 + 13 piercing"

  - name: "Champion Devotion Spells"
    desc: "2 Focus Points, DC 29, attack +21; __5th __  _[[Spells/Weapon Surge|Weapon Surge]]_, _[[Spells/Word of Freedom|Word of Freedom]]_"

  - name: "Challenge Foe"
    desc: "`pf2:1`  The einherji challenges one creature they can see to single combat, attempting to [[Actions/Demoralize|Demoralize]] that target.\n\nThis target remains the einherji's foe until it's defeated, it flees, or the encounter ends. The einherji gains a circumstance bonus to damage equal to their number of weapon damage dice against their designated foe but takes an equivalent circumstance penalty to damage against any other creature.\n\nIf the einherji is defeated by their challenged foe, the shame causes them to lose use of their champion devotion spells for 1 week or until they challenge the same foe again and emerge victorious, whichever comes first."

  - name: "Instant Repair"
    desc: "`pf2:1`  The einherji [[Actions/Repair|Repairs]] their shield. They can't use this ability if the shield is completely destroyed."

  - name: "Jotun Slayer"
    desc: "  The einherji has a +4 circumstance bonus to damage rolls made against giants and creatures that are at least two sizes larger than the einherji."
 
```

```encounter-table
name: Einherji
creatures:
  - 1: Einherji
```



Einherjar are mighty warriors chosen by valkyries from the ranks of those slain in terrible and legendary battles. Forged from the souls of the greatest warriors, the implacable einherjar serve as the foot soldiers of pantheons, skilled in handto-hand combat and slaying giants.

Einherjar often come from warrior cultures, including Ulfen vikings (like the einherji represented in this entry), particularly fierce pirates from the Shackles, and even Osirian conquerors. They can be chosen from wherever war and might hold sway; many deities who hold the call of battle and the pursuit of physical power more sacred than concepts of good and evil might count einherjar warriors and valkyrie choosers of the slain among their chosen servitors. For example, Gorum, Besmara, and Sekhmet have all elevated fallen worshippers as einherjar. Einherjar dedicated to different deities often wield weapons or possess varying cosmetic appearances based on their deity's preferred weapon and their place of death; however, they're universally stalwart, implacable, and efficiently deadly. Einherjar with two-handed weapons or who arise from other backgrounds often have different abilities in place of Jotun Slayer and Instant Repair.
