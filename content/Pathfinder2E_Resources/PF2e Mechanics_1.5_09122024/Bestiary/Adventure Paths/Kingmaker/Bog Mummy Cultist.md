---
title: "Bog Mummy Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.o5G13g0oPQqV0OCV" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Bog Mummy Cultist"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Bog Mummy Cultist"
level: "Creature 9"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[mummy]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Stealth: +18"
abilityMods: [6, 3, 4, 0, 6, 3]
speed: 20 feet,  burrow 15 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +16, __Will__ +21"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ cold 10; __Resistances__ cold 5, fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Leather Armor|+1 Cold-Resistant Leather Armor]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Breath of the Bog"
    desc: " (aura,divine,mental) 30 feet. A creature that begins its turn within the area feels as if its lungs were filling with water and must succeed at a DC 25 Fortitude check save or be unable to speak or breathe. The creature can still hold its breath and can attempt a new saving throw at the end of its turn.\n\nA creature that succeeds is temporarily immune to breath of the bog for 24 hours."

  - name: "Rejuvenation"
    desc: " (divine) Unless the damage that destroys a bog mummy cultist is vitality damage, necromantic energies rebuild its body from swamp muck 1 week later. If the uncompleted body is destroyed during that time, the process starts anew. Anyone who succeeds at a DC 26 Religion check check to Recall Knowledge realizes that a consecrate ritual performed on the site that a bog mummy cultist was destroyed prevents its rejuvenation, the way vitality damage prevents the rejuvenation from occurring."

  - name: "Rise Up"
    desc: "`pf2:r`  **Trigger** A creature walks on top of a bog mummy cultist that lies buried in the mud or peat below\n\n**Requirements** Initiative has not yet been rolled\n* * *\n\n**Effect** The bog mummy automatically notices the creature and [[Actions/Burrow|Burrows]] before rolling initiative."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+19 (agile)\n__Damage__  2d8 + 10 bludgeoning plus bog-rot"

  - name: "Divine Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Crisis of Faith|Crisis of Faith]]_; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_\n__Cantrips__  __(5th)__ _[[Spells/Divine Lance|Divine Lance]]_"

  - name: "Bog Rot"
    desc: " (curse,disease,divine,void) This affliction can't be reduced below stage 1, nor can the damage from it be healed, until it's successfully treated with remove curse or a similar effect; the affliction can then be removed as normal for a disease. A creature killed by bog rot melts into a noxious sludge and can't be brought back to life except by a 7th-rank [[Spells/Resurrect|Resurrect]] ritual or similar magic\n\n**Saving Throw** DC 28 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 minute)\n\n**Stage 2** 3d6 void damage and [[Conditions/Clumsy|Clumsy 1]] (1 day)"
 
```

```encounter-table
name: Bog Mummy Cultist
creatures:
  - 1: Bog Mummy Cultist
```


Variant bog mummy

The cultural practice of mummifying the dead is not the only way a body can become preserved, nor is it the only route that gives rise to these disease-spreading undead monstrosities.

Bog mummies (also called peat mummies or mire mummies) rarely, if ever, leave their marshy realms. Less powerful than their more notorious artificially preserved kin, bog mummies are preserved not by agents introduced during rituals but by the natural elements present in the airless, acidic morass of a peat bog or muddy swamp. While corpses preserved in this manner can certainly rise from the mire as bog mummies as the result of a curse by fell powers or the directed influence of a necromancer, the vast majority of them animate from a seething need for vengeance or to pursue some dire agenda left unfinished at the time of death-often because the creature was slain or otherwise betrayed. The nature of tthis emotional tie to life and the emotional power of the deceased compel unlife beyond death, while the preservative qualities of the bog within which the body was disposed of does the rest.

Although most bog mummies are motivated by vengeance, many fulfill their dark yearnings with general violence. Filled with wrath and hatred for the living, they mercilessly attack any living creatures that dare to venture into their dismal domains. Their agonized moans echo over their putrid homes, driving away most natural life dwelling therein and often alerting travelers to the potential danger that lies beneath the surface.
