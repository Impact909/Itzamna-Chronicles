---
title: "Vrykolakas Spawn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L7HkrpA3z7H0TXQ5" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Vrykolakas Spawn"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Vrykolakas Spawn"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[vampire]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +15, Stealth: +14, Survival: +11"
abilityMods: [5, 4, 2, -3, 2, 2]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +16, __Will__ +12"
hp: 99
health:
  - name: ""
  - name: HP
    desc: "99, (void healing); __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Feral Possession"
    desc: " (curse,divine,incapacitation,mental,possession) **Trigger** The vrykolakas is reduced to 0 Hit Points, and an animal is within 100 feet\n* * *\n\n**Effect** Unlike most other undead, a vrykolakas isn't destroyed when it reaches 0 HP. Instead, it attempts to cast its spirit into an animal within 100 feet, which must attempt DC 24 Will check save. On a failure, the animal is possessed. This has the effects of the [[Spells/Possession|Possession]] spell, but it lasts a number of days equal to the vrykolakas's level. This possession can't be counteracted with magic (though remove curse works against it normally).\n\nIf the animal succeeds at its save, the vrykolakas can attempt to possess a different animal within 100 feet. If at any point an animal critically succeeds at its save or no animal is within 100 feet, the vrykolakas fails to possess anything and is destroyed.\n\nA vrykolakas possessing an animal seeks out its burial site (see Burial Site Bound below) immediately, burying itself there. While the vrykolakas is in this state of recovery, its animal host is [[Conditions/Paralyzed|Paralyzed]], and beheading it destroys the vrykolakas and kills its host. Removing the curse destroys the vrykolakas and returns the animal to normal.\n\nAfter [[/gmr 1d4 #days]]{1d4 days}, if the vrykolakas hasn't been destroyed, the animal dies and the vrykolakas rises in a new body that's identical to its previous one, formed from the animal's remains."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Vrykolakas Vulnerabilities"
    desc: "  Vrykolakas all have the following vulnerabilities.\n\n*   **Burial Site Bound** A vrykolakas is bound to the place of its death or interment. It must return to this location once per week and bury itself in the earth for 24 hours, during which time it is [[Conditions/Paralyzed|Paralyzed]] and can be beheaded. If it is unable to return to this site, it is reduced to 0 Hit Points and attempts to use Feral Corruption; if this host animal can't return to the burial site before the possession effect ends, the vrykolakas is destroyed and the animal host returns to normal.\n*   **Vulnerable to Decapitation** A vrykolakas that is beheaded can't use its Feral Possession, and a beheaded corpse cannot rise as a vrykolakas."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d8 + 8 piercing plus drink-blood"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  2d6 + 8 slashing"

  - name: "Drink Blood"
    desc: "`pf2:1` (divine) **Requirements** The vrykolakas' last action was a successful fangs Strike\n* * *\n\n**Effect** The vrykolakas sinks its fangs into that creature to drink its blood. This requires an Athletics check check against the creature's Fortitude DC. On a success, the creature becomes [[Conditions/Drained|Drained 1]], and the vrykolakas regains 10 healing HP, gaining any excess HP as temporary Hit Points.\n\nDrinking Blood from a creature that's already drained doesn't restore any HP to the vampire, but it increases the creature's drained condition value by 1. A vrykolakas can also consume blood that's been emptied into a vessel for sustenance, but it gains no HP from doing so.\n\nThe target creature's drained condition value decreases by 1 per week.\n\nA blood transfusion, which requires a successful DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drained value by 1 after 10 minutes."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Vrykolakas Spawn
creatures:
  - 1: Vrykolakas Spawn
```



Vrykolakas unleash their spawn upon the world to spread terror, plague, and suffering and to draw attention away from their masters.
