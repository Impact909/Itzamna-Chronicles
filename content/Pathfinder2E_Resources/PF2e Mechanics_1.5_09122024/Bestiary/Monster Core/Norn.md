---
title: "Norn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LmsU5LBxjgHLuHGP" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Norn"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Norn"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[fey]]
modifier: 41
perception:
  - name: "Perception"
    desc: "+41; Greater Darkvision, Lifesense 120 Feet, Truesight"
languages: "Common, Fey, Jotun; Truespeech"
skills:
  - name: "Skills"
    desc: "Crafting: +36, Deception: +35, Intimidation: +37, Medicine: +38, Occultism: +34, Performance: +31, Religion: +34, Lore (All): +28"
abilityMods: [7, 6, 6, 6, 10, 7]
speed: 35 feet,  fly 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +34, __Ref__ +30, __Will__ +38; +1 status to all saves vs. magic"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375, regeneration 20 (deactivated by cold iron); __Immunities__  off-guard,  void; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shears|Shears]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "Sense Fate"
    desc: " (fortune) A norn automatically rolls a 20 when she rolls initiative."

  - name: "Triumvirate"
    desc: "  This functions as the [[Bestiary Ability Glossary/Coven|Coven]] ability, except only norns can join a triumvirate, and it functions only as long as exactly three norns are part of the triumvirate. A triumvirate grants the following spells: [[Spells/Cataclysm|Cataclysm]], [[Spells/Foresight|Foresight]], [[Spells/Manifestation|Manifestation]](once per day), [[Spells/Pinpoint|Pinpoint]], and [[Spells/Revival|Revival]]."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Norn Shears"
    desc: "+38 (deadly 2d8, magical, reach 10 feet, versatile p)\n__Damage__  4d4 + 15 slashing plus sever-fate 6d6 void plus sever-fate"

  - name: "**Melee** `pf2:1` Hand Of Fate"
    desc: "+38 (agile, magical, reach 10 feet)\n__Damage__  4d10 + 15 void plus sever-fate"

  - name: "Occult Innate Spells"
    desc: "DC 42, attack +34; __10th __  _[[Spells/Freeze Time|Freeze Time]]_; __9th __  _[[Spells/Execute|Execute]]_, _[[Spells/Phantasmagoria|Phantasmagoria]]_, _[[Spells/Retrocognition|Retrocognition]]_; __8th __  _[[Spells/Migration|Migration]]_, _[[Spells/Quandary|Quandary]]_; __7th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Read Omens|Read Omens]]_, _[[Spells/Spellwrack|Spellwrack]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(10th)__ _[[Spells/Hidden Mind|Hidden Mind]]_, _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Triumvirate Spells"
    desc: "DC 42, attack +34; __10th __  _[[Spells/Cataclysm|Cataclysm]]_, _[[Spells/Manifestation|Manifestation]]_, _[[Spells/Revival|Revival]]_; __9th __  _[[Spells/Foresight|Foresight]]_; __8th __  _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_, _[[Spells/Pinpoint|Pinpoint]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_"

  - name: "Rituals"
    desc: "_Collective Memories_, _Control Weather_, _Geas_"

  - name: "Fated"
    desc: " (fortune,misfortune) When a creature is subject to a fortune effect from a norn and a misfortune effect from any source other than a norn (or vice versa), the norn's effect automatically counteracts the other effect and then takes place normally, rather than the two effects canceling each other out. If both the fortune and misfortune effect are from a norn, then the two cancel each other out as normal. At the GM's discretion, powerful entities related to fate or luck, like Desna, Magdh, or Pharasma, can't have their effects negated by this ability."

  - name: "Sever Fate"
    desc: " (occult) When a norn deals void damage with a Strike, she regains 10 Hit Points. The target must succeed at a DC 39 Fortitude check save or become [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical failure).\n\nFurther void damage dealt by the norn increases the drained condition value by 1 on a failed save (or by 2 on a critical failure), to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Shift Fate"
    desc: "`pf2:r` (occult) **Trigger** A creature within 120 feet attempts a saving throw\n* * *\n\n**Effect** The creature rolls the saving throw twice, and then the norn decides which result applies. If the norn chooses the lower roll, this is a misfortune effect; if she chooses the higher roll, it's a fortune effect; if they're the same, she decides which trait to apply."

  - name: "Snip Thread"
    desc: "`pf2:2` (death,manipulate,occult) **Frequency** three times per day\n* * *\n\n**Effect** The norn produces a golden thread linked to the fate of a creature within 100 feet of her, then snips it short with her shears. The target takes 100 void damage (DC 42 Fortitude check save). If the target is reduced to 0 Hit Points from this damage, the thread is completely severed and the creature dies immediately.\n\nA creature slain by Snip Thread can't be restored to life except by a [[Spells/Wish|Wish]] ritual or similarly powerful magic; or by divine intervention. Regardless of the outcome of their saving throw, a creature targeted by Snip Thread then becomes temporarily immune for 24 hours.\n\nThe norn can't use Snip Thread again for 1d4 rounds."
 
```

```encounter-table
name: Norn
creatures:
  - 1: Norn
```



Ancient beyond imagining, norns are powerful fey women who hold in their hands the physical manifestation of fate and destiny in the form of golden thread. They watch over all life, intervening with reluctance when called upon—or with a vengeance when the strands of fate are twisted and abused by lesser beings. They cut imposing figures, standing 14 feet tall and weighing 800 pounds.

Norns' relationship with the Eldest of the First World is complex. Many among norns serve Magdh the Three, the triune Eldest who some norns believe to be the first norn triumvirate bound together into one entity, as Magdh has three bodies: a Maiden, a Mother, and a Matriarch. Magdh claims to be watching the threads of fate for some ominous prophesied cataclysm, and in addition to assisting in her divinations, Magdh expects the norns who serve her to follow her cryptic commands to help nudge the future away from the brink. However, norns are powerful beings in their own right, themselves capable of granting divine power, and many balk at serving the enigmatic demigod. These norns find the other Eldest even more alien and challenging to interact with, for they believe that while the Eldest wield great power, even these powerful beings should not be granted leave to meddle with fate as much as they desire.

While even the weakest of the Eldest could destroy an unaffiliated norn with ease, they tend to obey the proclamations and judgments of norns when they are spoken. These norns, for their part, use their perceived neutrality judiciously. They know better than to issue too many demands to the Eldest, lest the capricious demigods grow frustrated. And so the balance of power remains tenuous between unaffiliated norns and the Eldest, as it has for eons. Norns know that it's merely a matter of time before the Eldest lose their respect for this tradition and start acting entirely as they please, despite norns' best efforts to rein in their most disruptive actions.

## Followers of Fate

In the mortal Universe, some mortals worship norns as deities, while others, especially witches and bards, admire them as patrons or muses. Those who uphold norns as deities are known as Followers of Fate. Norns neither discourage this veneration nor go out of their way to support such worship. Clerics who venerate norns might worship a specific norn or norn triumvirate, or all norns as a whole, but they gain the same benefits regardless of their choice. The religious symbol of Followers of Fate is a pair of shears cutting a golden thread, and their areas of concern are destiny, fate, and the aging process.
