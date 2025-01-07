---
title: "Morrigna"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xn0z7LIOCHCI1V0H" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Morrigna"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Morrigna"
level: "Creature 15"

alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Necril, Requian; Speak with Animals, Truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Diplomacy: +27, Intimidation: +29, Religion: +29, Society: +24, Stealth: +27, Boneyard Lore: +28"
abilityMods: [8, 4, 4, 3, 6, 4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +25, __Ref__ +27, __Will__ +29; +1 status to all saves vs. magic"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, regeneration 20 (deactivated by acid or fire); __Immunities__  death effects,  disease; __Resistances__ void 15, poison 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bo Staff|+2 Striking Bo Staff]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bo Staff"
    desc: "+31 (magical, parry, reach 10 feet, trip)\n__Damage__  2d8 + 14 bludgeoning plus spirit-touch"

  - name: "**Melee** `pf2:1` Web Wrappings"
    desc: "+29 (magical, reach 10 feet)\n__Damage__  3d12 + 14 bludgeoning plus grab,spirit-touch"

  - name: "Divine Spontaneous Spells"
    desc: "DC 35, attack +30; __6th __ (4 slots) _[[Spells/Field of Life|Field of Life]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Spirit Blast|Spirit Blast]]_; __5th __ (4 slots) _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Sending|Sending]]_; __4th __ (4 slots) _[[Spells/Dispelling Globe|Dispelling Globe]]_, _[[Spells/Read Omens|Read Omens]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_; __3rd __ (4 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Dream Message|Dream Message]]_; __2nd __ (4 slots) _[[Spells/Calm|Calm]]_, _[[Spells/See the Unseen|See the Unseen]]_, _[[Spells/Silence|Silence]]_; __1st __ (4 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Bless|Bless]]_, _[[Spells/Enfeeble|Enfeeble]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Stabilize|Stabilize]]_, _[[Spells/Vitality Lash|Vitality Lash]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __4th __  _[[Spells/Talking Corpse|Talking Corpse]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_ __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Rituals"
    desc: "_Call Spirit_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) A morrigna can take the appearance of any Small or Medium animal or humanoid. This doesn't change their Speed or their attack and damage modifiers with their Strikes, but it might change the damage type their Strikes deal. Unless they choose to manifest their web wrappings in their new form, they cannot make web wrappings Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Shepherd's Touch"
    desc: "  A morrigna's Strikes affect incorporeal creatures as though etched with a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 4d6 void damage to living creatures or 4d6 vitality damage to undead."

  - name: "Spider Minions"
    desc: "`pf2:3` (divine,summon) The morrigna summons a [[Monster Core/Giant Tarantula|Giant Tarantula]] or [[Monster Core/Spider Swarm|Spider Swarm]]. These spiders have the summoned trait and remain for 10 minutes or until reduced to 0 Hit Points, whichever comes first. The morrigna does not need to Sustain the Spell to direct these summoned creatures, and the morrigna can have any number of summoned spiders in existence at once. The morrigna can see through the eyes of any of their summoned spiders at any time."

  - name: "Wrappings Lash"
    desc: "`pf2:r`  **Trigger** A creature within reach of the morrigna's web wrappings uses an action to Strike or attempt a skill check\n* * *\n\n**Effect** The morrigna makes a web wrappings Strike against the triggering creature. If the strike is a critical hit, the triggering action is disrupted."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Morrigna
creatures:
  - 1: Morrigna
```



Bounty hunters and investigators, morrignas seek out creatures who thwart death or interfere with the natural flow of souls. Morrignas dress in flowing spider silk and wear masks reminiscent of webs, as they consider patient and watchful spiders to be their spiritual kin.

* * *

Psychopomps are guardians and shepherds of the dead in the Boneyard, the vast plane of graves where mortal souls are judged and sent on to their eternal rewards or damnations. Psychopomps ensure that the dead come to terms with their transition from mortality and are properly sorted into the appropriate afterlife. They also protect souls from being preyed upon by supernatural predators. Nearly all psychopomps wear masks, especially when they're likely to be interacting with mortals, although the types of masks they wear are as varied as the psychopomps themselves. The courts of the Boneyard preside in Requian, a somber yet melodic language spoken slowly with various tonal shifts.

Many psychopomps are intimately involved with the Boneyard's massive bureaucracy. Few pursue mercy, justice, or personal gain; their duties to Pharasma and her Boneyard are supreme. Nevertheless, individual psychopomps interpret their duties in different ways, which might put them in conflict with mortals or even with each other.
