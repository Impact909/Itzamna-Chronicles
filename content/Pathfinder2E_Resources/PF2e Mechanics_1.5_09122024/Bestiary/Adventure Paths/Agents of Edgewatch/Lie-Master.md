---
title: "Lie-Master"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YoBGynIfcFOSdEt1" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Lie-Master"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Lie-Master"
level: "Creature 15"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Truesight"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Deception: +30, Diplomacy: +28, Intimidation: +28, Religion: +24, Society: +24, Stealth: +23"
abilityMods: [7, 2, 7, 3, 3, 7]
speed: 35 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +21, __Will__ +26; +1 status to all saves vs. magic"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Black Dragon's Breath Potion (Wyrm)|Black Dragon's Breath Potion (Wyrm)]]"
abilities_mid:
  - name: ""
  - name: "Truth Vulnerability"
    desc: "  A glabrezu's lies sustain them, and the truth can destroy them. Whenever a revelation effect counteracts or reveals the glabrezu's illusions or the glabrezu fails a save against an effect that would prevent them from lying (such as zone of truth), the demon takes 3d6+4 mental damage. They take this damage only once per effect, even if the effect reveals multiple illusions or prevents multiple lies."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+29 (deadly 2d10, magical, reach 15 feet, unholy)\n__Damage__  3d10 + 17 bludgeoning plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d6 + 17 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (magical, reach 10 feet, unholy)\n__Damage__  3d12 + 17 piercing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 36, attack +26; __7th __  _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Reverse Gravity|Reverse Gravity]]_; __6th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Translocate|Dimension Door (x2)]]_, _[[Spells/Truespeech|Tongues]]_; __4th __  _[[Spells/Confusion|Confusion]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image]]_\n__Cantrips__  __(8th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Divine Rituals"
    desc: "DC 36, attack +26"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Captive Rake"
    desc: "`pf2:1`  **Requirements** A creature is grabbed in the glabrezu's pincer.\n* * *\n\n**Effect** The glabrezu pulls the grabbed creature up to 5 feet closer, then makes two claw Strikes against it. Those Strikes count as one attack when determining a treachery demon's multiple attack penalty, and the penalty doesn't increase until after both Strikes."

  - name: "Steady Spellcasting"
    desc: "  When a reaction would disrupt a glabrezu's spell, the demon can attempt a DC 17 Flat check check, avoiding the disruption on a success."

  - name: "Sudden Betrayal"
    desc: "  A glabrezu can always use Deception when rolling initiative as long as they're aware of at least one opponent before initiative is rolled. When using Deception for initiative, the demon gains a +2 circumstance bonus to Deception."

  - name: "Tentacle Trip"
    desc: "`pf2:r`  **Trigger** A creature within 15 feet of the lie-master uses a manipulate or move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The creature must succeed at a DC 34 Reflex check save or be knocked prone by the lie-master's clockwork tentacles."

  - name: "Treacherous Veil"
    desc: "  A glabrezu's [[Spells/Illusory Disguise|Illusory Disguise]] can allow it to appear as a creature of any size."

  - name: "Twisted Desires"
    desc: " (divine) Once per month, a glabrezu can grant a mortal humanoid the effects of a [[Spells/Miracle|Miracle]] spell granted by an Abyssal patron, though the glabrezu always perverts the [[Spells/Miracle|Miracle]] according to their own treacherous nature."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a success with a Strike that lists Grab in its damage entry, or it has a creature grabbed using this action.\n* * *\n\n**Effect** The monster automatically Grabs the target until the end of the monster's next turn. The creature is grabbed by whichever body part the monster attacked with, and that body part can't be used to Strike creatures until the grab is ended. Using Grab extends the duration of the monster's Grab until the end of its next turn for all creatures grabbed by it. A grabbed creature can use the Escape action to get out of the grab, and the Grab ends for a grabbed creatures if the monster moves away from it."
 
```

```encounter-table
name: Lie-Master
creatures:
  - 1: Lie-Master
```



Glabrezus are looming behemoths who revel in the act of twisting mortal desires into their ultimate ruin, betraying and manipulating as easily as they breathe. Desires granted by a glabrezu always come to fruition in the most destructive way possible, turning a wish or hope into a potent and devastating act of betrayal-although the long-term repercussions are not always immediately apparent. For example, a struggling weapon smith might wish for fame and skill at their craft, only to find that their best patron is a cruel and sadistic murderer who uses the weapons in bloody sprees. Or a lonely widower might have his desire granted in the form of a lost love returned to "life" as a vampire. Glabrezus are nothing if not creative in addressing a mortal's needs.

These massive demons have enormous pincers and a pair of smaller humanoid arms sprouting from their chests, but their size belies their skill at magic, and they possess formidable innate spells. Treachery demons arise from the souls of mortals engaged in treason and deception.
