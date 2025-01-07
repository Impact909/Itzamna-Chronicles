---
title: "Formian Queen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EQ5yr9pqMVbNuqVi" 
tags:
  - pf2e/creature/type/formian
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Formian Queen"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Formian Queen"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[formian]]
trait_02: [[lawful]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 60 Feet"
languages: "Akitonian, Formian; telepathy 200 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +30, Athletics: +27, Diplomacy: +33, Intimidation: +33, Medicine: +31, Nature: +31, Society: +30"
abilityMods: [8, 5, 9, 5, 6, 8]
speed: 10 feet
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +34, __Ref__ +26, __Will__ +31"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Resistances__ physical 15, sonic 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 200 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Hive Mind"
    desc: " (primal) Formians operate from a shared hive intelligence that allows them to communicate nearly instantaneously. While within telepathic range of at least one other formian from the same hive mind, a formian worker gains a +2 circumstance bonus to initiative checks, Perception checks, and saving throws against mental effects. If one formian is aware of a combatant, all members of the hive mind within range are aware of it."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 15 feet)\n__Damage__  3d12 + 12 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Never Mind|Feeblemind]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Repulsion|Repulsion]]_, _[[Spells/Teleport|Teleport]]_; __7th __  _[[Spells/Force Barrage|Magic Missile (At Will)]]_"

  - name: "Hive Frenzy"
    desc: "`pf2:1` (mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The formian queen stirs all formians within range of her telepathy into a frenzy. Each affected formian gains the [[Conditions/Quickened|Quickened]] condition for 1 minute, and can use the extra action each round only to Strike or Stride."

  - name: "Possess Formian"
    desc: "`pf2:1` (incapacitation,mental,possession,primal) A formian queen transfers her consciousness to the body of any formian within range of her telepathy to whom she has a line of effect. As long as the queen's consciousness is outside her body, her body is [[Conditions/Unconscious|Unconscious]] (though she is aware if any damage is dealt to it).\n\nAn unwilling target can attempt a DC 38 Will check saving throw to resist being possessed, but the queen's offspring are part of her hive mind and thus are almost always willing. The queen receives all sensory input from the target creature; she can speak through it, and she can use her own modifier for Intelligence-, Wisdom-, and Charisma-based skill checks.\n\nIf the target creature is slain or moves to a different plane from the queen's body, the queen returns to her own body immediately and is [[Conditions/Stunned|Stunned 1]]; otherwise, she can return to her own body as a free action, ending the possession effect."

  - name: "Telepathic Feedback"
    desc: "`pf2:2` (mental,primal) The formian queen unleashes a blast of debilitating telepathic feedback, targeting as many creatures as she wishes within range of her telepathy and to whom she has a line of effect. Targeted creatures must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Telepathic Feedback for 24 hours.\n\n**Success** The creature takes 3d6 mental damage, 1d6 persistent mental, and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes 6d6 mental damage, 1d6 persistent mental damage, and is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature takes 12d6 mental damage, 1d6 persistent mental damage, and is [[Conditions/Stunned|Stunned 3]]. Upon recovering from the stunned condition, the creature becomes sickened 2."
 
```

```encounter-table
name: Formian Queen
creatures:
  - 1: Formian Queen
```



The formian queen is the center of the formian hive. The queen identifies and attends to the hive's needs, laying egg clusters that vary from a single formian born to a particular task to hundreds of workers at a time. All formians are born with an instinctive deference for the queen that borders on slavish devotion, though this urge can be corrupted, as with the King of Biting Ants' mutant mageslayers.

* * *

Formians resemble unusually large ants with an insectile humanoid's upper torso. More powerful or influential formians are physically larger; common formian workers are roughly the height of a gnome, while the largest formians, such as taskmasters and queens, rival a giant in size.

Formian society is a strict matriarchy. Though each hive's queen is theoretically independent and her rule absolute, allegiances are common, and less powerful hives often (grudgingly) defer to more powerful matriarchs.
