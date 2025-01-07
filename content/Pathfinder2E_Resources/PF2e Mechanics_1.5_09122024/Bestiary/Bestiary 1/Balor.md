---
title: "Balor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.trXcIXw1IfE37xFn" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Balor"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Balor"
level: "Creature 20"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +37, Deception: +36, Diplomacy: +32, Intimidation: +38, Religion: +32, Society: +32, Stealth: +33"
abilityMods: [9, 7, 9, 6, 6, 8]
speed: 35 feet,  fly 70 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +39, __Ref__ +35, __Will__ +34; +1 status to all saves vs. magic"
hp: 480
health:
  - name: ""
  - name: HP
    desc: "480; __Immunities__  fire; __Weaknesses__ cold 20, cold iron 20, holy 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|Longsword]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  The balor can use Attack of Opportunity when a creature within their reach uses a concentrate action, in addition to its normal trigger. They can disrupt triggering concentrate actions, and they disrupt actions on any hit, not just a critical hit.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Aura of Flame"
    desc: " (aura,divine,fire) 20 feet. A foe that starts its turn in the aura takes 3d6+10 fire damage, or 6d6+20 fire damage if the balor has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] it. A creature that hits a balor with an unarmed Strike takes 3d6+10 fire damage, and weapons that hit a balor take 3d6+10 fire damage."

  - name: "Death Throes"
    desc: " (death,divine,fire) When a balor dies, their body explodes in a 100-Foot Aura of intense demonic flame. All creatures and objects in range take 16d10 fire damage (DC 45 Reflex check save). Because the flame is infused with Abyssal energy, creatures in the area apply only half their usual fire resistance. Creatures with immunity to fire use an outcome one degree of success better than what they rolled, instead of gaining the usual benefit of immunity. The bodies of creatures reduced to 0 Hit Points by a balor's death throes are completely incinerated into fine ash."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vorpal Cold Iron Silver Longsword"
    desc: "+40 (magical, reach 10 feet, unholy, versatile p)\n__Damage__  4d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Cold Iron Silver Flame Whip"
    desc: "+40 (disarm, fire, magical, reach 20 feet, trip, unholy)\n__Damage__  4d6 + 17 fire plus improved-grab,whip-reposition"

  - name: "Divine Innate Spells"
    desc: "DC 44, attack +36; __10th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Divine Decree|Divine Decree (x2)]]_; __8th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_; __6th __  _[[Spells/Dominate|Dominate (At Will)]]_; __5th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Cantrips__  __(10th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Dimensional Dervish"
    desc: "  A balor can cast their 5th-rank innate [[Spells/Translocate|Translocate]] with only a single action."

  - name: "Dispelling Strike"
    desc: "  **Frequency** once per round.\n\n**Trigger** The balor hits a creature, object, or spell effect with a weapon Strike.\n* * *\n\n**Effect** The balor casts an innate [[Spells/Dispel Magic|Dispel Magic]] on the target of the triggering Strike."

  - name: "Infuse Weapons"
    desc: " (divine) Any weapon a balor wields becomes a _+3 [[Equipment/Striking (Major)|Major Striking]] [[Equipment/Vorpal|Vorpal]] weapon_ made of cold iron and silver while the demon holds it. A weapon that isn't eligible for the vorpal rune doesn't gain its effects. The demon can conjure a whip made of flames with an Interact action. This whip gains the same benefits as other weapons the balor wields."

  - name: "Lifedrinker"
    desc: " (divine,healing) **Trigger** The balor kills a living creature that is at least 15th level.\n* * *\n\n**Effect** The balor drinks the triggering creature's life force and regains 10d8+80 Hit Points."

  - name: "Whip Reposition"
    desc: "  When a balor [[Conditions/Grabbed|Grabs]] a creature with a whip Strike, they can move the creature to any space in the whip's reach. The balor can move without ending the grab as long as the creature remains within the whip's reach, and the balor can move the creature to any other space in the whip's reach with an Interact action."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Balor
creatures:
  - 1: Balor
```



When folk whisper frightened tales of the demonic, what most envision is the balor-a towering figure of fire and flesh, a horned nightmare armed with a flaming whip and a sword flying through the night in search of its latest victim. On the Abyss, balors serve demon lords as generals or captains, and they typically command vast legions of demons. Standing at 14 feet in height, only the cruelest mortal souls-those who devoted entire lives to sins too numerous to count-can fuel the formation of a balor. More often, a balor forms from a mass of dozens of mortal souls who shared debased ideologies in life.

#### Balor Lords

Those rare few balors who form from single souls are the ones most likely to eventually transcend the notable power they already wield, becoming a nascent demon lord. These balor lords are each unique creatures of 21st to 25th level in power who rule their own realm in the Abyss. In time, a balor lord can further develop into a unique creature with wildly different powers, even ascending to the role of a true demon lord.

* * *

When a sinful mortal soul is judged and sent on to the Abyss, it can become a deadly fiend-a demon. Demons are living incarnations of sin-be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold-the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Abyss.
