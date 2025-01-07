---
title: "Ordulf Bladecaller"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zUXcEz1O0FYsWvyH" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Ordulf Bladecaller"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Ordulf Bladecaller"
level: "Creature 16"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Common, Jotun, Skald"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +29, Crafting: +24, Intimidation: +31, Religion: +28, Survival: +28, Fishing Lore: +24, Warfare Lore: +26"
abilityMods: [5, 1, 4, 0, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +30, __Ref__ +25, __Will__ +28"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Resistances__ cold 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|+2 Greater Striking Animated Greataxe]], [[Equipment/Greatsword|+2 Greater Striking Greater Frost Greatsword]], [[Equipment/Full Plate|+2 Greater Resilient Greater Cold-Resistant Full Plate]], 3x [[Equipment/Potion of Flying (Greater)|Potion of Flying (Greater)]]"
abilities_mid:
  - name: ""
  - name: "Battle Arrogance"
    desc: "  Ordulf hasn't met a significant combat challenge in ages, and even when facing deadly foes like the PCs his arrogance can be used against him. If a PC successfully [[Actions/Disarm|Disarms]], [[Actions/Feint|Feints]], [[Conditions/Frightened|Frightens]], or [[Actions/Trip|Trips]] Ordulf, his arrogance gets the better of him and he grows sloppy in his tactics, reducing his AC to 34 until the start of his next turn. A PC can also attempt to issue a more debilitating insult to Ordulf.\n\n## Insult Ordulf `pf2:2`\n\nThe PC spends several seconds issuing insults and taunts to Ordulf, then attempts a DC 38 Deception check, DC 38 Intimidation check, or DC 38 Performance check check. If the insults include challenges to Ordulf's bravery, compare him to a troll or a chicken, insult his skill at fishing, or liken him to a witch or national of Irrisen, this becomes a DC 33 check.\n* * *\n\n**Critical Success** You strike a nerve. Not only does Ordulf become [[Conditions/Sickened|Sickened 2]] with anger, he is also [[Conditions/Stunned|Stunned 1]] from the shock of your words.\n\n**Success** Your insults cause Ordulf to become sickened 2 with anger.\n\n**Failure** Your insult only has a brief effect, causing Ordulf to become [[Conditions/Sickened|Sickened 1]]. He automatically recovers from this sickened condition at the end of his next turn.\n\n**Critical Failure** Your attempt to insult Ordulf fails so spectacularly that he becomes temporarily immune to Insult Ordulf activities from you for 24 hours."

  - name: "Gorum's Major Boon"
    desc: " (healing) When Ordulf is reduced to 0 Hit Points, Gorum feeds him the zeal of his Aesir, allowing Ordulf to draw upon his own life force to fight on and on without falling. He is healed to 150 Hit Points and becomes [[Conditions/Doomed|Doomed 1]] (or increases his doomed condition by 1), causing his features to look progressively more gaunt and scarred. Once he reaches [[Conditions/Doomed|Doomed 4]], he dies."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+32 (magical, versatile p)\n__Damage__  3d12 + 11 slashing 1d6 cold"

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+32 (magical, sweep)\n__Damage__  3d12 + 11 slashing 1d6 bleed"

  - name: "Battle Cry"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** Ordulf rolls initiative\n* * *\n\n**Effect** Ordulf attempts to [[Actions/Demoralize|Demoralize]] an observed foe."

  - name: "Cleaving Blow"
    desc: "`pf2:2`  Ordulf Strikes two adjacent creatures within his reach. Both attacks count against his multiple attack penalty, but do not increase his penalty until he has made both attacks."

  - name: "Crushing Insult"
    desc: "`pf2:1` (auditory,linguistic,mental) **Frequency** once per round\n* * *\n\n**Effect** Ordulf issues a devastating and humiliating insult to a creature within 30 feet that he can see. Ordulf attempts an Intimidation check check against the target's Will DC. That character is then temporarily immune to Crushing Insult for 24 hours.\n* * *\n\n**Critical Success** The insult is distracting and humiliating; the target is [[Conditions/Stupefied|Stupefied 1]] and [[Conditions/Off-Guard|Off-Guard]] for 1 minute.\n\n**Success** The insult is distracting, but its effects pass quickly; the target is stupefied 1 and off-guard until the start of Ordulf's next turn.\n\n**Failure** The insult barely cuts, but is distracting enough that the target is off-guard until the end of Ordulf's turn.\n\n**Critical Failure** Ordulf's attempted insult fails spectacularly, and the PC who he was attempting to insult can instantly insult him back, using Insult Ordulf as a free action."

  - name: "Deadly Display"
    desc: "`pf2:2`  **Requirements** Ordulf is wielding a melee weapon\n* * *\n\n**Effect** Ordulf brandishes his weapon in a threatening display. He [[Actions/Demoralize|Demoralizes]] all enemies within 30 feet, rolling once and comparing the result to each target's Will DC."

  - name: "Whirlwind Strike"
    desc: "`pf2:3`  Ordulf Strikes each enemy within his reach. Each attack counts toward his multiple attack penalty, but do not increase his penalty until he has made all his attacks."
 
```

```encounter-table
name: Ordulf Bladecaller
creatures:
  - 1: Ordulf Bladecaller
```


Male human warlord


