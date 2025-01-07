---
title: "Horde Lich"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XboylQC7cDV3NlQN" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Horde Lich"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Horde Lich"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Draconic, Dwarven, Jotun, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Arcana: +31, Crafting: +29, Intimidation: +27, Religion: +25, Stealth: +27, Thievery: +27"
abilityMods: [2, 6, 0, 8, 4, 6]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +21, __Ref__ +27, __Will__ +27; +1 status to all saves vs. vitality"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 10, physical 10 (except magical bludgeoning)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scroll of 6th-rank Spell|Scroll of Teleport (Level 6)]], [[Equipment/Magic Wand (6th-Rank Spell)|Wand of Dispel Magic (Level 6)]]"
abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Lich) Rejuvenation|Rejuvenation]]"
    desc: " (arcane) When a lich is destroyed, its soul immediately transfers to its _[[Equipment/Lich Soul Cage|Soul Cage]]_. A lich can be permanently destroyed only if its _soul cage_ is found and destroyed."

  - name: "Shatter Block"
    desc: "`pf2:r`  **Trigger** A creature scores a critical hit on the horde lich\n\n**Requirements** The horde lich has at least one servitor attached (see Servitor Assembly)\n* * *\n\n**Effect** The critical hit is a normal hit instead. One of the horde lich's servitors detaches from them and is placed in an open, adjacent space, [[Conditions/Prone|Prone]]. The servitor takes the damage from the triggering attack."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hand"
    desc: "+27 (finesse, magical)\n__Damage__  5d8 void"

  - name: "Arcane Prepared Spells"
    desc: "DC 39, attack +31; __8th __  _[[Spells/Desiccate|Horrid Wilting]]_, _[[Spells/Power Word Stun|Power Word Stun]]_, _[[Spells/Uncontrollable Dance|Uncontrollable Dance]]_; __7th __  _[[Spells/Power Word Blind|Power Word Blind]]_, _[[Spells/Project Image|Project Image]]_, _[[Spells/Spell Turning|Spell Turning]]_, _[[Spells/True Target|True Target]]_; __6th __  _[[Spells/Disintegrate|Disintegrate]]_, _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Repulsion|Repulsion]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Wave of Despair|Crushing Despair]]_, _[[Spells/Hallucination|Hallucination]]_; __4th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Fly|Fly]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Compendium.pf2e.spells-srd.Item.hkfH9Z53hPzcOwNB|Veil]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Mirror Image|Mirror Image]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Command|Command]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Phantasmal Minion|Unseen Servant]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Shield|Shield]]_"

  - name: "Servitor Assembly"
    desc: "`pf2:1` (manipulate) A horde lich has three servitor bodies folded up and attached to themself, usually in the ribcage, on the arms, and around the legs. The lich detaches one of these servitors and places it in any open, adjacent space. The lich can alternatively take this action to reattach an adjacent servitor.\n\nThe lich and their servitors share actions and Hit Points, and the servitors use the same statistics as the lich. Spells and effects that target the lich or their servitors affect all of them equally, but they're still treated as just one creature when targeted by spells and attacks. The horde lich attempts only one save against such effects, but they take a -2 circumstance penalty to defend against effects that target both the lich and one or more detached servitors. Whenever the horde lich Casts a Spell, they can choose to have the spell originate from themself or from any one of their detached servitors. If the horde lich is destroyed, all attached servitors are destroyed as well. If a servitor is dealt a critical hit, it's destroyed (and the horde lich takes the damage as normal)."

  - name: "Servitor Attack"
    desc: "`pf2:2` (concentrate) Each of the horde lich's detached servitors Strike, with a -2 circumstance penalty on the attack roll. Each of these Strikes counts toward the lich's multiple attack penalty, but the penalty doesn't increase until after all the attacks."

  - name: "Servitor Lunge"
    desc: "`pf2:1`  **Requirements** The horde lich's last action was a critical hit with a melee Strike, and the horde lich has at least one servitor attached\n* * *\n\n**Effect** One of the lich's attached servitors detaches adjacent to the target, and the target is [[Conditions/Grabbed|Grabbed]] by that servitor."

  - name: "Servitor Realignment"
    desc: "`pf2:1` (concentrate) Each of the horde lich's detached servitors can either Interact or take a basic action with the move trait. The lich chooses which action each of them takes."

  - name: "Steady Spellcasting"
    desc: "  If a reaction would disrupt the horde lich's spellcasting action, the lich attempts a DC 15 Flat check. On a success, the action isn't disrupted."
 
```

```encounter-table
name: Horde Lich
creatures:
  - 1: Horde Lich
```



At first glance, a horde lich looks like a skeleton packed with too many bones. In combat, the true purpose of these extra parts becomes clear as limbs peel off, expanding and reassembling into another nimble skeletal form. Regardless of the number, the single lich mind controls them all, and if any of them survive an encounter, they can rebuild the whole given enough time and raw materials.

* * *

A desire to live eternally motivates a spellcaster to become a lich, and necromantic knowledge makes the desire real. The typical lich takes the most direct path, keeping their undead form fairly close to their appearance in life. But undeath can also bring greater freedom for those with a less conventional view of what they can become. The horde lich and runecarved lich reshape themselves entirely.
