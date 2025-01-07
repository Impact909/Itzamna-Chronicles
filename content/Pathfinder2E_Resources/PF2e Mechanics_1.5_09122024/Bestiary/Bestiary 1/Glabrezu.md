---
title: "Glabrezu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DeGKUagi8if2e3wx" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Glabrezu"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Glabrezu"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Deception: +28, Diplomacy: +26, Intimidation: +26, Religion: +22, Society: +22, Stealth: +21"
abilityMods: [7, 2, 7, 3, 3, 7]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +19, __Will__ +24; +1 status to all saves vs. magic"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280; __Weaknesses__ cold iron 10, holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Truth Vulnerability"
    desc: "  A glabrezu's lies sustain them, and the truth can destroy them. Whenever a revelation effect counteracts or reveals the glabrezu's illusions or the glabrezu fails a save against an effect that would prevent them from lying (such as [[Spells/Ring of Truth|Ring of Truth]]), the demon takes 3d6 mental damage. They take this damage only once per effect, even if the effect reveals multiple illusions or prevents multiple lies."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+27 (deadly 2d10, magical, reach 15 feet, unholy)\n__Damage__  3d10 + 13 bludgeoning plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d6 + 13 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (magical, reach 10 feet, unholy)\n__Damage__  3d12 + 13 piercing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_, _[[Spells/Reverse Gravity|Reverse Gravity]]_; __6th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Confusion|Confusion (At Will)]]_, _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_ __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Captive Rake"
    desc: "`pf2:1`  **Requirements** A creature is [[Conditions/Grabbed|Grabbed]] in the glabrezu's pincer.\n* * *\n\n**Effect** The glabrezu pulls the grabbed creature up to 5 feet closer, then makes two claw Strikes against it. Those Strikes count as one attack when determining a treachery demon's multiple attack penalty, and the penalty doesn't increase until after both Strikes."

  - name: "Steady Spellcasting"
    desc: "  When a reaction would disrupt a glabrezu's spell, the demon can attempt a DC 15 Flat check check, avoiding the disruption on a success."

  - name: "Sudden Betrayal"
    desc: "  A glabrezu can always use Deception when rolling initiative as long as they're aware of at least one opponent before initiative is rolled. When using Deception for initiative, the demon gains a +2 circumstance bonus to Deception."

  - name: "Treacherous Veil"
    desc: "  A glabrezu's [[Spells/Illusory Disguise|Illusory Disguise]] can allow it to appear as a creature of any size."

  - name: "Twisted Desires"
    desc: " (divine) Once per month, a glabrezu can grant a mortal humanoid the effects of a [[Spells/Miracle|Miracle]] spell granted by an Abyssal patron, though the glabrezu always perverts the _miracle_ according to their own treacherous nature."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Glabrezu
creatures:
  - 1: Glabrezu
```



Glabrezus are looming behemoths who revel in the act of twisting mortal desires into their ultimate ruin, betraying and manipulating as easily as they breathe. Desires granted by a glabrezu always come to fruition in the most destructive way possible, turning a wish or hope into a potent and devastating act of betrayal-although the long-term repercussions are not always immediately apparent. For example, a struggling weapon smith might wish for fame and skill at their craft, only to find that their best patron is a cruel and sadistic murderer who uses the weapons in bloody sprees. Or a lonely widower might have his desire granted in the form of a lost love returned to "life" as a vampire. Glabrezus are nothing if not creative in addressing a mortal's needs.

These massive demons have enormous pincers and a pair of smaller humanoid arms sprouting from their chests, but their size belies their skill at magic, and they possess formidable innate spells. Treachery demons arise from the souls of mortals engaged in treason and deception.

* * *

When a sinful mortal soul is judged and sent on to the Abyss, it can become a deadly fiend-a demon. Demons are living incarnations of sin-be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold-the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Abyss.
