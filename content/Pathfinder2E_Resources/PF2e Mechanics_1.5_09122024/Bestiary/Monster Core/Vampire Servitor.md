---
title: "Vampire Servitor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sf77y4bokSWVCoIg" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Vampire Servitor"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vampire Servitor"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
trait_03: [[vampire]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common; plus one regional language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +9, Intimidation: +8, Society: +5, Stealth: +12"
abilityMods: [3, 5, 1, -1, 3, 2]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +9, __Ref__ +13, __Will__ +11"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, coffin restoration, fast healing 5, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 5 (except silver)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 5]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Basic) Coffin Restoration|Coffin Restoration]]"
    desc: " (divine,void) Unlike other undead, a vampire isn't destroyed at 0 HP. Instead, it falls [[Conditions/Unconscious|Unconscious]]. If its body rests in its coffin for 1 hour, the vampire gains 1 HP, after which its fast healing begins to function normally."

  - name: "[[Creature Family Ability Glossary/(Vampire, Basic) Vampire Vulnerabilities|Vampire Vulnerabilities]]"
    desc: "  All vampires possess the following vulnerabilities.\n\n*   **Compulsions** Vampires are creatures with strange and unknowable compulsions. A typical vampire can't voluntarily cross running water unless they're transported while they hide within their coffin, nor can they enter a private dwelling unless invited in by someone with the authority to do so. At your discretion, vampires might have different compulsions—a pirate vampire might not be able to set foot on solid ground without being invited, for example. The vampire can still be forced to do these things and might be able to overcome their compulsion just as they do their revulsion.\n*   **Revulsion** A vampire can't voluntarily come within 10 feet of brandished garlic or a brandished religious symbol of a deity with a holy sanctification option. To brandish garlic or a religious symbol, a creature must Interact to do so, and it remains brandished for 1 round (similar to Raising a Shield). If the vampire involuntarily comes within 10 feet of an object of their revulsion, they gain the [[Conditions/Fleeing|Fleeing]] condition, running from the object of their revulsion until they end an action beyond 10 feet. After 1 round of being exposed to the subject of their revulsion, a vampire can attempt a DC 25 Will check save as a single action, which has the concentrate trait. On a success, they overcome their revulsions for 1d6 rounds (or 1 hour on a critical success).\n*   **Stake** A wooden stake driven through a vampire's heart drops the vampire to 0 HP and prevents them from healing above 0 HP, even in their coffin. Staking a vampire requires 3 actions and works only if the vampire is [[Conditions/Unconscious|Unconscious]]. If the stake is removed, the vampire can heal above 0 HP again, and if they're in their coffin, the 1-hour rest period begins once the stake is removed. If the vampire's head is severed and anointed with holy water while the stake is in place, the vampire is destroyed.\n*   **Sunlight** If exposed to direct sunlight, a vampire immediately becomes [[Conditions/Slowed|Slowed 1]]. The slowed value increases by 1 each time the vampire ends their turn in sunlight, and the condition ends when they're no longer in sunlight. If the vampire loses all their actions in this way, they're destroyed. Due to their supernatural aversion to light, vampires don't cast shadows or show a reflection in mirrors"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+14 (agile)\n__Damage__  1d8 + 6 slashing plus grab"

  - name: "[[Creature Family Ability Glossary/(Vampire, Basic) Drink Blood|Drink Blood]]"
    desc: "`pf2:1` (divine) **Requirement** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the vampire's reach.\n* * *\n\n**Effect** The vampire sinks its fangs into that creature to drink its blood. This requires an Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions.\n\nThe victim is [[Conditions/Drained|Drained 1]] and the vampire regains 5 HP, gaining any excess HP as temporary Hit Points. Drinking Blood from a creature that's already drained doesn't restore any HP to the vampire but increases the victim's drained value by 1, killing the victim when it reaches drained 5. A vampire can also consume blood that's been emptied into a vessel for sustenance, but it gains no HP from doing so.\n\nA victim's drained condition decreases by 1 per week. A blood transfusion, which requires a DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drain by 1 after 10 minutes."

  - name: "Sneak Attack"
    desc: "  The servitor deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Vampire Servitor
creatures:
  - 1: Vampire Servitor
```



Vampires use their servitor pawns for infiltration and reconnaissance.

* * *

Vampires are undead creatures that feed on the blood of the living.
