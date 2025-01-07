---
title: "Thulgant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w03nK2tQpcOEi5py" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Thulgant"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Thulgant"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[fiend]]
trait_02: [[qlippoth]]
trait_03: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Truesight"
languages: "Chthonian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +35, Occultism: +33, Stealth: +32"
abilityMods: [9, 6, 6, 5, 6, 9]
speed: 30 feet,  climb 30 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +30, __Ref__ +28, __Will__ +32"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305, fast healing 10; __Immunities__  controlled,  fear effects; __Resistances__ mental 15, physical 15 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+35 (reach 10 feet, unholy)\n__Damage__  3d12 + 17 piercing plus thulgant-venom 4d6 mental plus thulgant-venom"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+35 (agile, magical, reach 10 feet, unholy)\n__Damage__  3d8 + 17 bludgeoning plus grab 3d6 acid plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Petrify|Petrify (x3)]]_, _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_; __8th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Phantom Pain|Phantom Pain (x3)]]_, _[[Spells/Quandary|Quandary]]_; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport]]_\n__Cantrips__  __(9th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_ __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Rituals"
    desc: "_Imprisonment_"

  - name: "Demon Hunter"
    desc: "`pf2:1` (occult) The thulgant causes a demon within 30 feet to suffer the effect of its sinful vulnerability."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d6+17 bludgeoning + 1d6 acid, DC 40 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Mind-Rending Sting"
    desc: "`pf2:1` (virulent) **Requirements** The thulgant hits the same enemy with two consecutive sting Strikes in the same round\n* * *\n\n**Effect** The thulgant deals 3d12+17 mental damage to the enemy. If the enemy is affected by thulgant venom, that poison gains the virulent trait."

  - name: "Stunning Display"
    desc: "`pf2:2` (concentrate,emotion,fear,incapacitation,mental,occult,visual) The thulgant rises up on its twitching limbs and presents its numerous tentacles and stingers in a horrifying display of awfulness. Creatures in a 30-foot emanation must attempt a DC 40 Will check save, after which they are temporarily immune to further Stunning Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 4]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 8]]."

  - name: "Thulgant Venom"
    desc: " (poison) **Saving Throw** DC 40 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage and the victim gains one of the following at random: [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Enfeebled|Enfeebled 1]], or [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 6d6 poison damage and the victim gains two of the following at random: [[Conditions/Clumsy|Clumsy 2]], [[Conditions/Enfeebled|Enfeebled 2]], or [[Conditions/Stupefied|Stupefied 2]] (1 round)\n\n**Stage 3** 9d6 poison damage and the victim gains all three of the following: [[Conditions/Clumsy|Clumsy 3]], [[Conditions/Enfeebled|Enfeebled 3]], and [[Conditions/Stupefied|Stupefied 3]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Thulgant
creatures:
  - 1: Thulgant
```



Thulgants are powerful and intelligent qlippoths created from the cannibalistic feeding frenzies of augnagars. Although they spend most of their time hunting and battling demons for control of the Outer Rifts, thulgants amuse themselves with a variety of diversions, such as maintaining galleries of petrified mortals or building massive, hive-like lairs filled with enslaved minions. Each thulgant is a horrific tangle of limbs, with spiderlike legs, writhing tentacles emerging from the top of its head, and three scorpion-like stingers.

* * *

Long before the creatures known as demons came to be the dominant force in the Outer Rifts, qlippoth ruled the innumerable cracks of the Outer Sphere. These inimical creatures are a form of primordial and alien evil that predates mortal life, and most immortal life as well. Since the rise of mortal sin and the associated expansion of demonic life through the Outer Rifts, qlippoth have been driven to their deepest reaches, and they seethe with rancor at the loss of their realms. Yet, rather than directly oppose demons, qlippoth instead turn to the source—mortal sin—and wage an endless war to eradicate all creatures capable of sinful acts so that the demonic tide might be turned back. To ensure they do not bolster their foe's ranks, they enact horrific transformations on their targets, converting their victims into beings incapable of discerning right from wrong; this renders them unable to be judged by Pharasma's courts and thus incapable of becoming fiends. Most mortals consider the ministrations of a qlippoth to be far worse than any fate awaiting them in the afterlife.
