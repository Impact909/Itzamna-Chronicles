---
title: "Wrath Riot"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZBrcJScRaOzbCfWO" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/troop
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Wrath Riot"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Wrath Riot"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[troop]]
trait_06: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Intimidation: +30"
abilityMods: [8, 5, 6, 5, 6, 6]
speed: 25 feet,  fly 35 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +27, __Will__ +26; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, Thresholds 200 (12 squares), 100 (8 squares); __Weaknesses__ area damage 20, cold iron 15, holy 15, splash damage 15; __Resistances__ electricity 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Serenity Vulnerability"
    desc: "  A wrath riot thrives on mayhem, and when members of the throng find themselves facing moments of calm, however brief or temporary, the throng suffers. Whenever the wrath riot fails a saving throw against an affect that would normally [[Conditions/Fascinated|Fascinate]], [[Conditions/Fatigued|Fatigue]], [[Conditions/Paralyzed|Paralyze]], [[Conditions/Restrained|Restrain]], or [[Conditions/Slowed|Slow]] at least four creatures, the troop takes 3d6+10 mental damage."

  - name: "Spores of Wrath"
    desc: " (aura,disease,poison) 5 feet. Non-demons that start their turn in the aura take 4d8 poison damage. Each creature damaged this way must succeed at a DC 34 Fortitude check save or take 2d8 persistent piercing damage as the spores penetrate its skin and grow into thick, green vines. The vines cease growing after 10 rounds, and they wither away in 1d4 days if not shaved off before then. The vines can be destroyed if the creature is affected by a good spell or if holy water is applied to the vines (with an Interact action)."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

attacks:
  - name: ""

  - name: "Beaks, Claws, and Talons"
    desc: "`pf2:1` (unholy) **Frequency** once per round\n* * *\n\n**Effect** The throng furiously tears at each enemy within its squares and within 5 feet (DC 37 Reflex check save). Damage depends on the number of actions.\n\n`pf2:1` Damage 1d12+14 slashing plus 1d6 spirit\n\n`pf2:2` Damage 2d12+14 slashing plus 1d6 spirit\n\n`pf2:3` Damage 3d12+14 slashing plus 1d6 spirit"

  - name: "Demonic Tide"
    desc: "  A wrath riot is less organized and more vicious than most troops. They can move into other creatures' spaces, and other creatures can move into their spaces. Their spaces are difficult terrain to non-demon creatures. The first time during a turn that a creature hostile to the throng willingly moves into their space, that creature is subjected to the one-action version of Beaks, Claws, and Talons."

  - name: "Festival of Ruin"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Each non-demon creature in the throng or within a 20-foot emanation from it takes damage based on the number of actions used (DC 37 Reflex check save). Damage depends on the number of actions.\n\n`pf2:1` Damage 4d6 electricity\n\n`pf2:2` Damage 8d6 electricity\n\n`pf2:3` Damage 12d6 electricity"

  - name: "Troop Movement"
    desc: "  Whenever the riot Strides, they first Form Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to their Speed."
 
```

```encounter-table
name: Wrath Riot
creatures:
  - 1: Wrath Riot
```



Wrath demons are among the most well-known and feared of the Abyss's fiends, but sometimes a wrath demon becomes stunted in size as the result of too many failed rampages, a punishment inflicted by an angry demonic commander or simple ill fortune. These smaller wrath demons, not much larger than humans, are typically slaughtered quickly by their larger kin, but rarely a group of undersized vrocks can gather in numbers large enough to form a wrath riot.

* * *

Demons are legion. Countless examples crowd the Abyss, many of which have yet to be categorized by mortal scholars. In the Abyss, might very much makes right, and so despite their chaotic nature, weaker demons often gather together to enjoy safety in numbers.

## Throng Abilities

Demon throngs are troops, as defined in Pathfinder Bestiary 3. They have the Troop Defenses, Troop Movement, and Form-Up abilities. They also have the demonic tide ability, which allows them to occupy the same space as other creatures, which is unusual for troops, and Serenity Vulnerability—a result of the troop's demonic nature.

## Other Throngs

Wrath riots form because vrocks have an intrinsic quality of cooperation in their dance of ruin, but other types of demons might form into throngs as well. The more notorious forms of demon throngs found in the various tales and historical records include demonic press gangs of babaus, who abduct hapless victims to serve on nightmarish ships, and firestorms of brimoraks, who caper and swoop above eldritch volcanoes.
