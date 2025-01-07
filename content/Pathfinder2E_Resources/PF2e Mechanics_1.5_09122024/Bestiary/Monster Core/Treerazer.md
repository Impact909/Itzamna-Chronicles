---
title: "Treerazer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OgqDT0orKK3Vu26h" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/25
  - remaster
statblock: inline
name: "Treerazer"
level: 25
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Treerazer"
level: "Creature 25"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[demon]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 46
perception:
  - name: "Perception"
    desc: "+46; Darkvision, Truesight"
languages: "Chthonian, Common, Elven, Fey; Telepathy 300 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +40, Arcana: +38, Athletics: +45, Intimidation: +46, Nature: +49, Occultism: +38, Religion: +45, Stealth: +40"
abilityMods: [12, 9, 11, 7, 8, 8]
speed: 60 feet,  fly 60 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 54
armorclass:
  - name: AC
    desc: "54; __Fort__ +42, __Ref__ +40, __Will__ +43; +2 status to all saves vs. magic"
hp: 550
health:
  - name: ""
  - name: HP
    desc: "550, Regeneration 50 (deactivated by holy); __Immunities__  death effects,  disease,  mental,  poison; __Weaknesses__ holy 20; __Resistances__ acid 20, cold 15, fire 15, physical 20 (except cold iron)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Blackaxe|Blackaxe]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 300 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Aura of Corruption"
    desc: " (aura,plant,primal) 120 feet.\n\nPlants near Treerazer twist, deform, and transform into thorny or fungoid parodies of their natural shapes. A living creature in this area must succeed at a DC 47 Fortitude check save each round or become partially transformed into plantlike matter. Those who fail this saving throw are treated as if they were plants for the purposes of any effect that particularly harms or inconveniences plant creatures more than other creatures, but do not gain any benefits of being plant creatures.\n\nThis effect lasts as long as the creature remains within the area of corruption and for 1 minute thereafter.\n\n[[Bestiary Effects/Effect_ Aura of Corruption|Effect: Aura of Corruption]]"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blackaxe"
    desc: "+47 (acid, magical, reach 15 feet, sweep, unholy)\n__Damage__  5d12 + 18 slashing 1d6 acid"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+45 (agile, magical, reach 15 feet, unholy)\n__Damage__  5d10 + 20 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 49, attack +43; __10th __  _[[Spells/Desiccate|Desiccate]]_, _[[Spells/Freeze Time|Freeze Time]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_; __9th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_; __6th __  _[[Spells/Tangling Creepers|Tangling Creepers (At Will)]]_; __3rd __  _[[Spells/Earthbind|Earthbind (At Will)]]_; __2nd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(9th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(8th)__ _[[Spells/Truesight|Truesight]]_ __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_, _Planar Servitor_"

  - name: "Blackaxe - Owner's Authority"
    desc: "`pf2:1` (concentrate,scrying) **Requirements** Treerazer isn't wielding _Blackaxe_.\n* * *\n\n**Effect** Treerazer sense the world around Blackaxe as though you were in its location and can use any of your innate spells through the link as if it were the source of the spell. If another creature is wielding Blackaxe, it must succeed at a DC 50 Will check save or be [[Conditions/Slowed|Slowed 2]] until it relinquishes the weapon."

  - name: "Blackaxe - Owner's Reclamation"
    desc: " (concentrate,teleportation) **Requirements** Treerazer isn't wielding _Blackaxe_.\n* * *\n\n**Effect** _Blackaxe_ appears in Treerazer's hands, teleporting instantly from its prior location."

  - name: "Blackaxe - Rejuvenating Deforestation"
    desc: "`pf2:1` (concentrate,death,healing,vitality) **Frequency** once per minute.\n* * *\n\n**Effect** Make a Strike against a living tree with Blackaxe. If it hits, the tree withers to ash and you heal 250 Hit Points and gain the benefit of a 6th-rank [[Spells/Sound Body|Sound Body]] spell."

  - name: "Defoliation"
    desc: "`pf2:2` (plant,primal) Treerazer exudes a pulse of sickly green light in a 30-foot-radius emanation. All plants in the area (including creatures under the effect of his aura of corruption) blacken and wither.\n\nNon-creature plants immediately wither and die. Plant and fungus creatures take 20d8 void damage with a DC 49 Fortitude check save. A creature that fails its save is [[Conditions/Doomed|Doomed 1]] for 1 minute and [[Conditions/Sickened|Sickened 3]].\n\nTreerazer can choose to exclude any number of plants or fungi in the area from this effect, and generally does so to preserve twisted and corrupted plants or fungi, or plant and fungus creatures that are allied to his cause.\n\nTreerazer can't use Defoliation for 1d4 rounds."

  - name: "Dispelling Strike"
    desc: " (primal) **Frequency** once per round\n\n**Trigger** Treerazer hits a creature, object, or spell effect with a weapon Strike or subjects one to Defoliation;\n* * *\n\n**Effect** Treerazer casts his innate [[Spells/Dispel Magic|Dispel Magic]], targeting the creature he hit with his Strike or one spell affecting that creature."

  - name: "Staggering Strike"
    desc: "  When Treerazer scores a critical hit with a melee attack, the target is [[Conditions/Stunned|Stunned 2]]."
 
```

```encounter-table
name: Treerazer
creatures:
  - 1: Treerazer
```



Treerazer, the self-styled Lord of the Blasted Tarn, is a powerful demon on the cusp of ascending to the true power of one of the rulers of the Abyss itself-a demon lord. For now, even as a nascent demon lord, Treerazer is a dangerous foe.

Treerazer rarely leaves his swampy realm of Tanglebriar-a large thicket of tainted foliage and rotting detritus just south of Kyonin's Fierani Forest-but can be encountered anywhere within that toxic mire, often accompanied by a small legion of demons, corrupted fey, and other deadly allies. Certain occult rituals have the power to call him forth from Tanglebriar, granting him the opportunity to directly work his evils beyond the realm to which he has been exiled. Some believe that no eldritch force contains Treerazer and that, were he willing, he could travel Golarion with impunity, spreading the twisted blessings of his touch and the corruption of his presence, yet the Lord of the Blasted Tarn is as cunning and canny as he is deadly, and prefers to work his evils on the world from the safety of his nightmare realm.
