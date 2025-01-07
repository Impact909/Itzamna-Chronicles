---
title: "Vanyver"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UeWMgEn4bSAv2YVN" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/darvakka
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Vanyver"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Vanyver"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[darvakka]]
trait_03: [[evil]]
trait_04: [[shadow]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common, Diabolic, Necril; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Arcana: +23, Athletics: +27, Religion: +24, Stealth: +25, Shadow Plane Lore: +25, The Void Lore: +25"
abilityMods: [8, 4, 6, 4, 5, 5]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +29, __Ref__ +23, __Will__ +22"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 10, silver 10; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Catching Bite"
    desc: "`pf2:r`  **Trigger** A creature within reach of the vanyver's jaws makes a melee Strike against the vanyver with a weapon\n* * *\n\n**Effect** The vanyver chooses to be hit. If the attack would've missed, it hits. The vanyver catches the weapon in their jaws and uses Drain Magic on it without fulfilling Drain Magic's requirements."

  - name: "Drain Magic"
    desc: "`pf2:1`  **Requirements** The vanyver's last action was a successful jaws Strike against a creature, object, or spell effect\n* * *\n\n**Effect** The vanyver casts an innate [[Spells/Dispel Magic|Dispel Magic]] on the same target; if the target was a creature, the vanyver can target a spell affecting the creature instead. If a spell effect or item is successfully counteracted, the vanyver gains temporary Hit Points equal to double the counteract rank of the effect that was counteracted."

  - name: "Entropy's Shadow"
    desc: " (aura,divine,void) 40 feet. Vanyvers leak entropy and corruption from their very being. A living creature entering or starting its turn in the aura takes 3d6 void damage with a DC 30 Fortitude check. If it fails, it's also [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute and pulled 10 feet toward the vanyver."

  - name: "Snatch"
    desc: "  The vanyver can Fly at half Speed while they have a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in either or both of their talons, carrying that creature along with them."

  - name: "Sunlight Powerlessness"
    desc: "  A vanyver caught in sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Talon"
    desc: "+27 (magical, reach 10 feet)\n__Damage__  3d10 + 11 bludgeoning plus grab 1d10 cold plus grab"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+27 (agile, magical, reach 15 feet)\n__Damage__  3d6 + 11 bludgeoning 1d10 cold"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (magical, reach 10 feet)\n__Damage__  3d10 + 11 piercing plus drain-magic 1d10 cold plus drain-magic"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (to the Universe, Void, or Netherworld only)]]_; __6th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Harm|Harm (x3)]]_; __4th __  _[[Spells/Darkness|Darkness]]_, _[[Spells/See the Unseen|See Invisibility]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d10+5 piercing DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Vanyver
creatures:
  - 1: Vanyver
```



Vanyvers are large, humanoid bats shaped from void and shadowstuff, their red eyes glowing like tiny stars in an otherwise lightless night. Though powerful, they're the least of the darvakkas, and the most likely to submit to a master, either another of their kind or a mortal with a reputation for being especially murderous and destructive. Vanyvers agree to follow their masters as a temporary means of maximizing the death and destruction they can enact but will quickly turn on any master they feel falters in this goal.

* * *

Darvakkas, also called nightshades, are a ravenous evil made up of equal parts darkness and malice. Originally creatures of the Outer Planes who travel to the convergence of the Shadow Plane and the Void—where the power of nothingness obliterates them—these undead abominations are the physical embodiment of entropy. They burn with an intense hatred for all life, working to bring a final, dark night to the Material Plane where nothing but ash and ice remain.

As creatures twisted by darkness and shadow, darvakkas have a great aversion to sunlight and all sources of vitality energy. On the Material Plane, they spend the hours of daylight hidden below ground, amid ruins, or submerged deep in the ocean's darkest chasms beyond the reach of the sun's rays, emerging when darkness shelters them overhead.

Darvakkas have an aura of entropy that attracts undead thralls to serve as warriors and heralds. They rarely seek alliances with each other or other creatures, existing in solitude as the heads of individual armies of the dead.
