---
title: "Mindmoppet"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pKA9Ng2Uze302eLj" 
tags:
  - pf2e/creature/type/lawful
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Mindmoppet"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #189: Dreamers of the Nameless Spires"
name: "Mindmoppet"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[lawful]]
trait_02: [[ooze]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common; one other language; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Crafting: +14, Deception: +11, Intimidation: +11, Medicine: +10, Occultism: +14, Society: +14, Stealth: +13, Thievery: +13"
abilityMods: [2, 4, 2, 5, 3, 2]
speed:  fly 40 feet
sourcebook: "_Pathfinder #189: Dreamers of the Nameless Spires_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +12, __Will__ +15; +1 status to all saves vs. magic"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  acid,  critical hits,  piercing,  precision,  unconscious,  visual; __Weaknesses__ electricity 5; __Resistances__ slashing 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Shell (Porcelain Doll)"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Mindsense (Precise) 120 feet"
    desc: "  The mindmoppet senses the thoughts of intelligent creatures and builds a perception of reality from this information, allowing the mindmoppet to \"see\" as a precise sense. Invisible intelligent creatures are visible to it."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Prognosticate"
    desc: "  When the mindmoppet uses a reaction, it can Step before or after taking the reaction."

  - name: "Shell"
    desc: "  The mindmoppet believes its shell is an important part of itself. Breaking the mindmoppet's shell (AC 25, Hardness 1, HP 6, BT 3) causes it to become [[Conditions/Fascinated|Fascinated]] with its shell. This condition ends when its shell is repaired."

  - name: "Synapse Glow"
    desc: " (aura,light) 5 feet. The firing of the mindmoppet's synapses create dim light. The range increases to 10 feet if its shell is destroyed."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Telekinetic Slam"
    desc: "+15 (force, occult, range increment 20 feet)\n__Damage__  2d12 force plus improved-push"

  - name: "Occult Innate Spells"
    desc: "DC 22, attack +14; __2nd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (x2)]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Mending|Mending (x3)]]_\n__Cantrips__  __(2nd)__ _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(1st)__ _[[Spells/Mindlink|Mindlink]]_"

  - name: "Anticipate"
    desc: "`pf2:1`  The mindmoppet attempts to anticipate its opponent's actions. Until the end of its next turn, the mindmoppet gains one reaction."

  - name: "Redirect Attack"
    desc: "`pf2:r` (mental) **Trigger** The mindmoppet is targeted by a melee or ranged Strike\n* * *\n\n**Effect** The mindmoppet attempts a Reflex saving throw, using the attack roll as the DC for the check. On a success, it redirects the attack at another target within the attacker's range. On a failure, the attack resolves as normal."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Mindmoppet
creatures:
  - 1: Mindmoppet
```



Mindmoppets are the result of laboratory experimentation that sought to harness telepathic energy within a liquid alchemical concoction. Mindmoppets feed on the latent telepathic energy of creatures. Even those with no apparent gift but with an active mind can sustain a mindmoppet for days. Such feeding is not invasive, and mindmoppets continually "graze" even while inactive.

Mindmoppets are willing servants to anyone who concerns themselves with strenuous mental exercise. Their creator is usually an obvious first choice, and they serve them dutifully. However, they have only an academic understanding of good and evil, of ethics, or mortal limitations. They see service to their master's science as the ultimate standard by which they judge their actions or those of others. This can lead to conflict between them and their creator, especially if the master appears lax in their efforts to further their studies. To a mindmoppet, continuous learning is imperative.

Mindmoppets appear to have some ability to see a short distance into the future, though this might only be that their innate interest for thought and cognition gives them a knack for anticipating the actions of others.

### Scavenged Shell

Being amorphous, mindmoppets are resilient, but they still cling to their shells for protection. You can represent a shell of different material by replacing the Hardness, Hit Points, and Broken Threshold of the porcelain shell listed here with those listed in the Materials section of the Pathfinder Core Rulebook.
