---
title: "Quai Dau To"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iD1GHwK9qGGmWWOA" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Quai Dau To"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Quai Dau To"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Scent (Imprecise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27, Stealth: +25, Survival: +24"
abilityMods: [8, 4, 8, -3, 5, -1]
speed: 40 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +26, __Ref__ +19, __Will__ +21"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  blinded,  dazzled; __Weaknesses__ sonic 15"
abilities_top:
  - name: ""

  - name: "Mist Vision"
    desc: "  The quai dau to ignores the [[Conditions/Concealed|Concealed]] condition from mist and fog."

abilities_mid:
  - name: ""
  - name: "Frightful Sight"
    desc: " (aura,emotion,fear,mental,visual) 60 feet.\n\nThis aura functions as a DC 32 Will check frightful presence aura, but a creature doesn't attempt its save until it sees the quai dau to.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Reflective Scales"
    desc: "`pf2:r`  **Trigger** A creature within 30 feet casts a spell with the light trait or uses an ability with the light trait\n* * *\n\n**Effect** The quai dau to adjusts its position to reflect the light off their scales in a blinding display. All creatures in a 30-foot emanation must succeed at a DC 33 Fortitude check saving throw or become [[Conditions/Blinded|Blinded]] for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 10 feet)\n__Damage__  3d12 + 14 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+27 (reach 20 feet)\n__Damage__  3d8 + 14 bludgeoning"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+27 (agile)\n__Damage__  3d8 + 14 bludgeoning"

  - name: "Drain Water"
    desc: "`pf2:1` (manipulate) **Requirements** The quai dau to is within 10 feet of a body of water that's at least 10 feet deep and their water sac is empty\n* * *\n\n**Effect** The quai dau to sucks water through their trunk to fill their water sac, lowering the level in the body of water by 10 feet. All creatures in the water within a 30-foot emanation are [[Conditions/Off-Guard|Off-Guard]] until the start of the quai dau to's next turn."

  - name: "Inflate"
    desc: "`pf2:1`  The quai dau to inflates their body. They become Gargantuan, gain a fly Speed of 30 feet until the end of their next turn, and then Fly. They deflate if they fall [[Conditions/Unconscious|Unconscious]] or Dismiss this effect."

  - name: "Mist Breath"
    desc: "`pf2:1` (primal,water) **Requirements** The quai dau to's water sac is full\n* * *\n\n**Effect** The quai dau to empties their water sac to breathe out mist in a 10-foot emanation. All creatures within the mist become [[Conditions/Concealed|Concealed]], and all creatures outside the mist become concealed to creatures within it. The mist dissipates after 1 round."

  - name: "Spout Water"
    desc: "`pf2:2` (primal,water) **Requirements** The quai dau to's water sac is full\n* * *\n\n**Effect** The quai dau to empties its water sac to blast water from its trunk, dealing 9d10 bludgeoning damage to all creatures in a 90-foot line, with a DC 33 Reflex check save. A creature that fails is pushed 10 feet (or 20 feet on a critical failure)."
 
```

```encounter-table
name: Quai Dau To
creatures:
  - 1: Quai Dau To
```



This big-headed beast is covered in glittering scales; its eyes are like large copper pots, and its mouth is full of sharp teeth. Despite its fish-like appearance, a quai dau to spends most of its time on land hunting along riversides or lakes. It uses its trunk to drain the nearby water before using it with deadly skill. A quai dau to can expel the water with a force strong enough to knock a knight off a horse, or gently enough to surround themself in a veil of mist.

A quai dau to is extremely sensitive to sound. If they hear too much ruckus near their hunting grounds, they violently attack. Their silent movement allows them to sneak up on such distracted prey despite their massive size. Researchers have discovered, after much study, that quai dau tos don't have ears in the traditional sense. They have an organ in the upper part of their skulls that inflates to hold the water they use in their attacks. This organ is extremely sensitive to vibrations in the air and is used as a pseudo ear.
