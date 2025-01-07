---
title: "Catrina"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ccI3GgJYxc4pRBDn" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Catrina"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Catrina"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 120 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Diplomacy: +14, Intimidation: +14, Medicine: +12, Occultism: +11, Religion: +12, Boneyard Lore: +11"
abilityMods: [0, 5, 4, 2, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +12, __Will__ +13; +1 status to all saves vs. magic"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  death effects,  disease; __Resistances__ void 5, poison 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 120 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Calming Presence"
    desc: " (aura,divine,emotion,incapacitation) 30 feet. A creature that begins its turn within the area must attempt a DC 18 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to calming presence for 24 hours.\n\n**Success** The creature's attack rolls take a -1 status penalty for 1 round.\n\n**Failure** Any emotion effects that would affect the creature are suppressed and the creature can't use hostile actions. If the creature is subjected to hostility from any other creature, it ceases to be affected by calming presence and is temporarily immune to calming presence for 24 hours.\n\n**Critical Failure** As failure, but hostility doesn't end the effect."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (agile, finesse)\n__Damage__  2d8 + 2 bludgeoning plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 22, attack +12; __4th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Talking Corpse|Talking Corpse (At will)]]_; __3rd __  _[[Spells/Illusory Disguise|Illusory Disguise]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At will) (Self only)]]_\n__Cantrips__  __(3rd)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Compel Condemned"
    desc: "`pf2:1` (divine,incapacitation,mental) The catrina telepathically compels a creature within 30 feet to approach and allow the catrina to kiss them, in preparation for using Kiss of Death. The target must attempt a DC 22 Will check save.\n\n**Success** The creature is unaffected and is temporarily immune to Compel Condemned for 24 hours.\n\n**Failure** The creature must spend each of its actions to move closer to the catrina as quickly as possible, while avoiding obvious dangers. If the compelled creature is adjacent to the catrina, it stays still and doesn't act. If the creature takes any damage, the effect ends and the creature is temporarily immune to Compel Condemned for 24 hours. This effect lasts for 1 round, but if the catrina uses this ability again on subsequent rounds, it extend the duration by 1 round for all affected creatures.\n\n**Critical Failure** As failure, but damage does not end the effect."

  - name: "Kiss of Death"
    desc: "`pf2:2` (death,divine,manipulate) The catrina gives a long, passionate kiss to an [[Conditions/Unconscious|Unconscious]] or willing creature, dealing 3d6 void damage.\n\nAny creature damaged by the same catrina's Kiss of Death for 3 consecutive rounds becomes unconscious and is [[Conditions/Dying|Dying 1]]."

  - name: "Spirit Touch"
    desc: " (incorporeal) A catrina's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 1d6 void damage to living creatures and 1d6 vitality damage to undead."
 
```

```encounter-table
name: Catrina
creatures:
  - 1: Catrina
```



Not all spirits who enter the Boneyard realize they have died. Catrinas meet these souls, helping to convince them of the finality of their fate to ease a spirit's passing. Catrinas are more likely to intervene when a mortal can't accept their death. They perform their task to keep the afterlife calm, rather than out of true compassion for a mortal's grief. Catrinas only rarely visit the Material Plane, typically to help an extremely important mortal pass on.

Catrinas resemble skeletons dressed in bright flowers and colorful dresses, giving them a simultaneously festive and macabre appearance. Though most catrinas present as feminine, masculine catrinas still dress in bright colors and carry garlands of flowers.
