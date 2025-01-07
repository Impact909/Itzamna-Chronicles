---
title: "Sthira"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JS1oBdSAKftTiKVg" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Sthira"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Sthira"
level: "Creature 20"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[cold]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +39"
abilityMods: [9, 2, 10, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +29, __Ref__ +27, __Will__ +33"
hp: 475
health:
  - name: ""
  - name: HP
    desc: "475, void healing; __Immunities__  paralyzed,  unconscious,  cold,  mental,  poison,  death effects,  disease"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+3 Greater Striking Greatsword]]"
  - name: "Create Sthira"
    desc: " (primal) When a creature dies while it has persistent cold damage from the sthira's frostbite, the creature rises as a sthira in 24 hours. If the creature is grappled by the sthira when it dies, the dying creature becomes permanently fused with the sthira instead. In this case, the sthira immediately recovers a number of Hit Points equal to the half the dead creature's maximum Hit Points."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Frozen to the Touch"
    desc: "`pf2:r` (cold) A creature that damages the sthira with an unarmed attack, tries to Grapple it, or otherwise touches it takes 6d6 cold damage (DC 42 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+38 (magical, reach 10 feet, versatile p)\n__Damage__  3d12 + 15 slashing plus frostbite 2d6 cold plus frostbite"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+38 (magical, reach 10 feet)\n__Damage__  3d8 + 15 bludgeoning plus frostbite,improved-grab 2d6 cold plus frostbite,improved-grab"

  - name: "Innate Primal Spells"
    desc: "DC 39, attack +31; __10th __  _[[Spells/Massacre|Massacre]]_; __9th __  _[[Spells/Polar Ray|Polar Ray (x2)]]_, _[[Spells/Storm of Vengeance|Storm of Vengeance (hail only each round)]]_, _[[Spells/Wall of Ice|Wall of Ice]]_\n__Cantrips__  __(10th)__ _[[Spells/Ray of Frost|Ray of Frost]]_"

  - name: "Freezing Death"
    desc: " (aura,cold,primal) 20 feet. A creature that starts its turn in the aura takes 6d6 cold damage (DC 42 Fortitude check save). If the creature is grabbed or restrained by the sthira, it takes one degree of success worse than it rolled."

  - name: "Frostbite"
    desc: "  A creature that takes cold damage from a sthira's Strikes or aura must attempt a DC 42 Fortitude check save. A creature that already has persistent cold damage from frostbite ignores this effect.\n* * *\n\n**Critical Success** The creature is unaffected, and is temporarily immune to this ability for 1 hour.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature takes 3d6 persistent cold damage.\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Drained|Drained 1]]."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sthira
creatures:
  - 1: Sthira
```



The Wall of Heaven claims many intrepid climbers. Some such travelers come seeking fortune. Others seek enlightenment. Many, however, find only an icy death. With no means for a proper burial, many of these unfortunate souls remain abandoned to the ice, their bodies becoming macabre guideposts along mountain trails.

Through means unknown, the most willful of these frozen travelers reanimate to seek vengeance upon the living for their denied burial. Such creatures, called sthiras, are composed of multiple bodies or body parts frozen together into one horrific monstrosity.
