---
title: "Blisterwell Oathrisen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.S9GxoQOmLs7Ei57C" 
tags:
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Blisterwell Oathrisen"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Blisterwell Oathrisen"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Deception: +15, Intimidation: +15, Warfare Lore: +11"
abilityMods: [6, 1, 5, 0, 4, 4]
speed: 20 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +18, __Ref__ +14, __Will__ +15"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110, void healing; __Immunities__  death effects,  paralyzed,  disease,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Falchion|+1 Falchion]], [[Equipment/Full Plate|Full Plate]]"
abilities_mid:
  - name: ""
  - name: "Armored Disguise"
    desc: "  A Blisterwell oathrisen's undead nature is not obvious. While wearing armor, an oathrisen gains a +4 circumstance bonus to its Deception checks to Impersonate a living orc and does not require a disguise kit to do so. Creatures that don't notice the disguise are not subject to the oathrisen's Frightful Presence. An oathrisen can abandon its disguise as a free action with the manipulate trait when it attempts to [[Actions/Demoralize|Demoralize]] a creature."

  - name: "Drop the Mask"
    desc: "  Once a Blisterwell oathrisen is reduced to less than half its Hit Points, portions of its armor break off. This reduces its AC by 2, increases its Speed by 5 feet, and gives it weakness 5 to vitality damage. This also immediately exposes nearby creatures to the oathrisen's frightful presence."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet DC 25 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Falchion"
    desc: "+18 (forceful, sweep)\n__Damage__  1d10 + 9 slashing 1d6 bleed"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 (agile, free-hand)\n__Damage__  1d6 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Whisper"
    desc: "+15 (range 60 feet, sonic)\n__Damage__  4d6 sonic plus curse-of-whispers"

  - name: "Curse of Whispers"
    desc: " (curse,divine) A creature muffled by this curse cannot speak above a whisper. The creature must succeed at a DC 25 Fortitude check save to use actions with the auditory trait\n\n**Saving Throw** DC 25 Will check\n\n**Stage 1** muffled for 1 minute (1 minute)\n\n**Stage 2** muffled for 1 minute (1 minute)\n\n**Stage 3** muffled for 1 day (1 day)"

  - name: "Wound Ripper"
    desc: "  A Blisterwell oathrisen's Strikes against creatures with the [[Conditions/Wounded|Wounded]] condition or taking persistent bleed damage deal 1d6 additional precision damage."
 
```

```encounter-table
name: Blisterwell Oathrisen
creatures:
  - 1: Blisterwell Oathrisen
```



Most undead are reanimated without consent, but those known as oathrisen arise willingly—at least at first. These loyal subordinates swear themselves to a cause or leader, vowing to assist even in death. Within days of their death, their oath reanimates them and restores most of their memories. In theory, an oathrisen's existence lasts no more than a year. In practice, the cause's leader might demand their service indefinitely. If denied their afterlife too long, some oathrisen turn on their former masters, afterward either becoming independent or destroying themselves.

The oathrisen presented here is a variant that frequents Blisterwell during the events of this Adventure Path. Other regions and traditions might create oathrisen with different abilities.

## Knight By Another Name

An oathrisen resembles a graveknight—both being heavily armored, corporeal, undead warriors. Yet a graveknight arises through its own unholy ambitions and is inextricably bound to its armor. By comparison, an oathrisen reanimates out of loyalty and is not intrinsically malicious. Some oathrisen even resent graveknights, taking special joy in destroying these unholy copycats.
