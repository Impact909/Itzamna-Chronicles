---
title: "Vampire Count"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sm5MzWo8OKDYezKY" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Vampire Count"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vampire Count"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
trait_03: [[vampire]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Necril; plus one regional language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +13, Deception: +14, Diplomacy: +14, Intimidation: +16, Society: +14, Stealth: +13"
abilityMods: [5, 3, 2, 2, 4, 4]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +11, __Ref__ +14, __Will__ +17"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65, coffin restoration, fast healing 7, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 7 (except magical silver)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Rapier|+1 Rapier]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "[[Creature Family Ability Glossary/(Vampire, True) Children of the Night|Children of the Night]]"
    desc: " (divine,mental) The vampire's presence brings forth creatures of the night to do the master's bidding. These typically include [[Monster Core/Rat Swarm|Rat Swarms]], [[Monster Core/Vampire Bat Swarm|Bat Swarms]], and [[Monster Core/Wolf|Wolves]], but can include other creatures.\n\nThe vampire can give telepathic orders to these creatures as long as they are within 100 feet, but they can't communicate back."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 7]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Basic) Coffin Restoration|Coffin Restoration]]"
    desc: " (divine,void) Unlike other undead, a vampire isn't destroyed at 0 HP. Instead, it falls [[Conditions/Unconscious|Unconscious]]. If its body rests in its coffin for 1 hour, the vampire gains 1 HP, after which its fast healing begins to function normally."

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Mist Escape|Mist Escape]]"
    desc: "`pf2:0`  **Trigger** The vampire is reduced to 0 HP.\n* * *\n\n**Effect** The vampire uses Turn to Mist. They can take move actions to move toward its coffin even though it's at 0 HP. While at 0 HP in this form, the vampire is unaffected by further damage.\n\nThey automatically returns to its corporeal form, unconscious, if they reaches their coffin or after 2 hours, whichever comes first."

  - name: "[[Creature Family Ability Glossary/(Vampire, Basic) Vampire Vulnerabilities|Vampire Vulnerabilities]]"
    desc: "  All vampires possess the following vulnerabilities.\n\n*   **Compulsions** Vampires are creatures with strange and unknowable compulsions. A typical vampire can't voluntarily cross running water unless they're transported while they hide within their coffin, nor can they enter a private dwelling unless invited in by someone with the authority to do so. At your discretion, vampires might have different compulsions—a pirate vampire might not be able to set foot on solid ground without being invited, for example. The vampire can still be forced to do these things and might be able to overcome their compulsion just as they do their revulsion.\n*   **Revulsion** A vampire can't voluntarily come within 10 feet of brandished garlic or a brandished religious symbol of a deity with a holy sanctification option. To brandish garlic or a religious symbol, a creature must Interact to do so, and it remains brandished for 1 round (similar to Raising a Shield). If the vampire involuntarily comes within 10 feet of an object of their revulsion, they gain the [[Conditions/Fleeing|Fleeing]] condition, running from the object of their revulsion until they end an action beyond 10 feet. After 1 round of being exposed to the subject of their revulsion, a vampire can attempt a DC 25 Will check save as a single action, which has the concentrate trait. On a success, they overcome their revulsions for 1d6 rounds (or 1 hour on a critical success).\n*   **Stake** A wooden stake driven through a vampire's heart drops the vampire to 0 HP and prevents them from healing above 0 HP, even in their coffin. Staking a vampire requires 3 actions and works only if the vampire is [[Conditions/Unconscious|Unconscious]]. If the stake is removed, the vampire can heal above 0 HP again, and if they're in their coffin, the 1-hour rest period begins once the stake is removed. If the vampire's head is severed and anointed with holy water while the stake is in place, the vampire is destroyed.\n*   **Sunlight** If exposed to direct sunlight, a vampire immediately becomes [[Conditions/Slowed|Slowed 1]]. The slowed value increases by 1 each time the vampire ends their turn in sunlight, and the condition ends when they're no longer in sunlight. If the vampire loses all their actions in this way, they're destroyed. Due to their supernatural aversion to light, vampires don't cast shadows or show a reflection in mirrors"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+17 (deadly d8, disarm)\n__Damage__  1d6 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  1d8 + 8 slashing plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +14; __6th __  _[[Spells/Dominate|Dominate (At Will) (See Dominate)]]_"

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The vampire transforms into one of its animal forms or back into its normal form. Most vampires can turn into a bat, but some can turn into a different creature, such as a rat or a wolf.\n\n*   **Giant Bat**\n    *   **Senses** echolocation 40 feet,\n    *   **Speed** 20 feet, fly 30 feet,\n    *   **Melee** fangs +15 **Damage** 1d8+9 piercing\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Create Servitor|Create Servitor]]"
    desc: " (divine,downtime) If a creature dies after being reduced to 0 HP by Drink Blood, the vampire can turn this victim into a vampire servitor by donating some of their own blood to the victim and burying the victim in earth for 3 nights.\n\nA vampiric servitor is compelled to obey its creator, but if a vampire controls too many vampiric servitors at once (as determined by the GM), or if the servitor is a higher level than the vampire that created it, strongwilled servitors can free themselves by succeeding at a Will check saving throw against the vampire's Will DC."

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Dominate|Dominate]]"
    desc: "`pf2:2` (divine,incapacitation,mental,visual) The vampire can cast [[Spells/Dominate|Dominate]] at will as a divine innate spell. Casting it requires staring into the target's eyes, giving the spell the visual trait (DC 22 Will check). The save DC uses the high spell DC of the vampire's level, and a creature that succeeds is temporarily immune to that vampire's Dominate for 24 hours.\n\nFully destroying the vampire ends the domination, but merely reducing the vampire to 0 HP is insufficient to break the spell."

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Drink Blood|Drink Blood]]"
    desc: "`pf2:1` (divine) **Requirement** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the vampire's reach.\n* * *\n\n**Effect** The vampire sinks its fangs into that creature to drink its blood. This requires an Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions.\n\nThe victim is [[Conditions/Drained|Drained 2]] and the vampire regains 10 HP, gaining any excess HP as temporary Hit Points. Drinking Blood from a creature that's already drained doesn't restore any HP to the vampire but increases the victim's drained value by 1, killing the victim when it reaches drained 5. A vampire can also consume blood that's been emptied into a vessel for sustenance, but it gains no HP from doing so.\n\nA victim's drained condition decreases by 1 per week. A blood transfusion, which requires a DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drain by 1 after 10 minutes."

  - name: "[[Creature Family Ability Glossary/(Vampire, True) Turn to Mist|Turn to Mist]]"
    desc: "`pf2:1` (air,concentrate,divine,polymorph) The vampire turns into a cloud of vapor, as the [[Spells/Vapor Form|Vapor Form]] spell, or back to its normal form. The vampire loses fast healing while in gaseous form.\n\nThe vampire can remain in this form indefinitely."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Vampire Count
creatures:
  - 1: Vampire Count
```



Vampire counts rule their demesnes and subjects through a mix of fear and cruelty.

* * *

Vampires are undead creatures that feed on the blood of the living.
