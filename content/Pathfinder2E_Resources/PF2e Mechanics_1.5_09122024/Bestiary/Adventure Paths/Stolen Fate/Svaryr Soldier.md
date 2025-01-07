---
title: "Svaryr Soldier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KJH6IApAIW41uFFp" 
tags:
  - pf2e/creature/type/aesir
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Svaryr Soldier"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #192: Worst of All Possible Worlds"
name: "Svaryr Soldier"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aesir]]
trait_02: [[chaotic]]
trait_03: [[monitor]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "Common, Jotun, Skald; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Crafting: +25, Intimidation: +29"
abilityMods: [8, 5, 7, 1, 3, 5]
speed: 40 feet
sourcebook: "_Pathfinder #192: Worst of All Possible Worlds_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +31, __Ref__ +27, __Will__ +25; +4 to will saves vs. fear"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Resistances__ piercing 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|+2 Greater Striking Returning Dagger]], [[Equipment/Longsword|+2 Greater Striking Longsword]], [[Equipment/Sturdy Shield (Greater)|Sturdy Shield (Greater)]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+34 (magical, versatile p)\n__Damage__  3d8 + 16 slashing 2d6 mental"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+32 (agile)\n__Damage__  3d6 + 16 bludgeoning"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+31 (agile, magical, versatile s)\n__Damage__  3d4 + 16 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+31 (agile, magical, thrown 10 ft., versatile s)\n__Damage__  3d4 + 16 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Champion Devotion Spells"
    desc: "3 Focus Points, DC 34, attack +26; __8th __  _[[Spells/Lay on Hands|Lay on Hands]]_, _[[Spells/Weapon Surge|Weapon Surge]]_, _[[Spells/Word of Freedom|Word of Freedom]]_, _[[Spells/Zeal for Battle|Zeal for Battle]]_"

  - name: "Challenge Foe"
    desc: "`pf2:1`  The soldier challenges one creature they can see to single combat, attempting to [[Actions/Demoralize|Demoralize]] that target. This target remains the soldier's foe until it's defeated, it flees, or the encounter ends. The soldier gains a circumstance bonus to damage equal to their number of weapon damage dice against their designated foe but takes an equivalent circumstance penalty to damage against any other creature. If the soldier is defeated by their challenged foe, the shame causes them to lose use of their champion devotion spells for 1 week or until they challenge the same foe again and emerge victorious, whichever comes first."

  - name: "Defender of Svaryr"
    desc: "  The soldier's melee Strikes with a longsword become infused with the convictions of their duty, and deal an additional 2d6 mental damage against foes they fight while in Svarýr (Already included)."

  - name: "Instant Repair"
    desc: "`pf2:1`  The soldier [[Actions/Repair|Repairs]] their shield. They can't use this ability if the shield is completely destroyed."
 
```

```encounter-table
name: Svaryr Soldier
creatures:
  - 1: Svaryr Soldier
```


Variant einherji

Einherjar are mighty warriors chosen by valkyries from the ranks of those slain in terrible and legendary battles. Forged from the souls of the greatest warriors, the implacable einherjar serve as the foot soldiers of pantheons, skilled in handto-hand combat and slaying giants.

Einherjar often come from warrior cultures, including Ulfen vikings (like the einherji represented in this entry), particularly fierce pirates from the Shackles, and even Osirian conquerors. They can be chosen from wherever war and might hold sway; many deities who hold the call of battle and the pursuit of physical power more sacred than concepts of good and evil might count einherjar warriors and valkyrie choosers of the slain among their chosen servitors. For example, Gorum, Besmara, and Sekhmet have all elevated fallen worshippers as einherjar. Einherjar dedicated to different deities often wield weapons or possess varying cosmetic appearances based on their deity's preferred weapon and their place of death; however, they're universally stalwart, implacable, and efficiently deadly. Einherjar with two-handed weapons or who arise from other backgrounds often have different abilities in place of Jotun Slayer and Instant Repair.
