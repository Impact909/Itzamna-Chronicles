---
title: "Harrow Doll"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oA6ipEbdMn0k4AdI" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Harrow Doll"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Harrow Doll"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Lore: +16"
abilityMods: [3, 4, 2, 0, 5, 5]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +16, __Will__ +17"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ physical 5 (except adamantine)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Harrow Deck (Simple)|Harrow Deck (Metal)]]"
  - name: "Uncanny Divination"
    desc: "  A harrow doll can cast [[Spells/Augury|Augury]] as part of a harrow reading, which takes the usual 10 minutes.\n\nWhen casting [[Spells/Locate|Locate]], the harrow doll doesn't need to have previously observed a specific object to learn its direction, but instead can detail the direction only vaguely, using such phrases as \"beside a weeping mound\" or \"beneath the lost sky.\"\n\nWhen the harrow doll casts [[Spells/Mind Reading|Mind Reading]], there is no effect if the target critically succeeds its save.\n\nEach time a harrow doll makes a harrow reading, it also changes which saving throw is affected by its fortune's favor ability."

abilities_mid:
  - name: ""
  - name: "Fortune's Favor"
    desc: " (fortune) Whenever the harrow doll attempts a specific type of saving throw, it rolls twice and takes the higher result. The type of saving throw is determined by the suit that featured most prominently in the doll's most recent harrow reading: Fortitude (Hammers or Shields), Reflex (Keys or Books), or Will (Stars or Crowns). If the suit of its latest harrow reading is unknown, roll 1d6 at the beginning of combat to randomly determine it.\n\n[[Bestiary Effects/Effect_ Fortune's Favor|Effect: Fortune's Favor]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 (agile, magical)\n__Damage__  2d12 + 6 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Harrow Card"
    desc: "+18 (magical, range increment 60 feet)\n__Damage__  2d8 + 6 slashing plus harrowing-misfortune"

  - name: "Arcane Innate Spells"
    desc: "DC 27, attack +17; __3rd __ (2 slots) _[[Spells/Locate|Locate]]_, _[[Spells/Mind Reading|Mind Reading]]_; __2nd __ (1 slots) _[[Spells/Augury|Augury (At Will)]]_"

  - name: "Harrowing Misfortune"
    desc: " (curse,misfortune) A creature struck by one of the harrow doll's cards must attempt a DC 25 Will check save or be cursed with misfortune, which forces the creature to roll twice and take the lower result on its next roll of a specific type, determined by the card's suit (roll 1d6 to randomly determine the suit). A creature can be cursed with only one effect from harrowing misfortune at a time, with a new curse overriding any previous curse. The curse ends after 1 minute or after the specified roll is made, whichever comes first. The suits and their effects are: Hammers (melee attack roll), Keys (Reflex save), Shields (Fortitude save), Books (skill check), Stars (Will save), and Crowns (spell attack roll).\n\n[[Bestiary Effects/Effect_ Harrowing Misfortune|Effect: Harrowing Misfortune]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Harrow Doll
creatures:
  - 1: Harrow Doll
```



Harrow dolls are unique constructs that can make predictions about the future. The more elite circuses and traveling shows frequently feature a harrow doll, and many use the doll's abilities to learn more about locals to better customize shows to their tastes-or to find easy marks for later cons. Upset patrons that try to harm a harrow doll or reclaim their payment quickly learn that the construct is more than capable of defending itself.
