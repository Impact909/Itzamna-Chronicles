---
title: "Barghest"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7gJbkcpYRPA3vCt1" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Barghest"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Barghest"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Goblin, Fey, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Deception: +11, Diplomacy: +9, Intimidation: +11, Stealth: +10, Survival: +12"
abilityMods: [5, 2, 3, 2, 2, 3]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +12, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Weaknesses__ holy 5; __Resistances__ physical 5 (except cold iron)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Primal Hunt"
    desc: "`pf2:r` (primal,teleportation) **Trigger** A creature within the barghest's reach takes a move or teleportation action\n* * *\n\n**Effect** After the triggering action, the barghest can teleport up to 60 feet to a space adjacent to that creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile, unholy)\n__Damage__  2d6 + 5 slashing plus unhealing-wound"

  - name: "Divine Innate Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Mist|Mist]]_\n__Cantrips__  __(2nd)__ _[[Spells/Figment|Figment]]_, _[[Spells/Light|Light]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The barghest takes on the shape of a humanoid, a dog, or its true form. Their size changes to match the new form. When the barghest is a humanoid, their claw Strike deals bludgeoning damage and they lose their jaws Strike. When the barghest is a dog, their Speed changes to 35 feet. Each individual barghest has only one humanoid form and one dog form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Unhealing Wound"
    desc: " (curse,primal) A creature damaged by the barghest's claws must succeed at a DC 21 Fortitude check save or be cursed. The cursed creature can't regain Hit Points except via magic until it returns to maximum Hit Points. The creature can attempt a new saving throw against the curse every 24 hours."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Barghest
creatures:
  - 1: Barghest
```



Barghests are canine beasts that take great joy in the hunt, often lurking near humanoid settlements to find prey that can provide a suitable challenge. Even in the deepest wilderness, barghests choose the most clever or difficult prey, searching endlessly for challenges like giants, nymphs, and unicorns.

More than victory or even the possibility of a meal at the end, barghests enjoy the thrill of the chase and the fear they create within their prey. Particularly terrified targets of a hunting barghest might even be allowed to escape, spreading the terror and enticing hunters who can become the barghest's next victims. A handful of barghests resort to learning magical methods of causing fear directly, though they find such fear hollow and unsatisfying.

Although they rarely tolerate the competition of another barghest's presence, these hunters will happily work with anyone who helps them find prey to torment and kill. This often involves enforcing the will of hags or particularly cruel fey, but a bored barghest might also force a family of weaker humanoids to work as scouts and bait.

Typical barghests often make use of their shapechanging abilities to hide in plain sight, only taking their true forms to frighten their prey and exult in the hunt. However, they are often still exposed by their trail of victims or the curiously unhealing wounds they inflict, even in humanoid form. Tales of powerful barghests with invisible heads are sometimes told in remote and dwindling villages. These barghests generally dispense with hiding as a humanoid or dog, instead terrifying entire communities and openly hunting increasingly dangerous prey. Some also extend this pride to their intellect, insisting on matching wits with their prey or even with those who believe they're hunting the barghest.
