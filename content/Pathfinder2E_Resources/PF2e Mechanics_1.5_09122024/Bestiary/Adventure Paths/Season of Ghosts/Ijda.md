---
title: "Ijda"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GCANvZSp3348WFDk" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/nindoru
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Ijda"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #197: Let the Leaves Fall"
name: "Ijda"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[nindoru]]
trait_05: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Aklo, Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +16"
abilityMods: [4, 3, 1, 0, 3, 3]
speed: 30 feet
sourcebook: "_Pathfinder #197: Let the Leaves Fall_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +13, __Will__ +12"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Immunities__  death effects,  emotion,  fatigued,  sleep; __Weaknesses__ silver 5; __Resistances__ void 5, mental 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Katana|Broken Katana]]"
abilities_mid:
  - name: ""
  - name: "Aura of Forgetfulness"
    desc: " (aura,mental,occult) 30 feet. A creature who begins its turn in the aura must attempt a DC 21 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Aura of Forgetfulness for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Slowed|Slowed 1]] until the end of its next turn, as it has trouble remembering what it intended to do.\n\n**Critical Failure** As failure, but [[Conditions/Slowed|Slowed 2]]."

  - name: "Soul Shred"
    desc: "  Creatures killed by a idja are difficult to bring back to life or animate as undead. The idja automatically attempts to counteract any attempt to resurrect or animate any creature that it has killed (counteract modifier +14, counteract rank 3). If the idja who slew the creature is itself slain, the creature can be brought back from death or become undead normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Broken Katana"
    desc: "+17 (deadly d8, magical, reach 15 feet, two-hand d10, unholy, versatile p)\n__Damage__  2d6 + 8 slashing 1d6 mental"

  - name: "Occult Innate Spells"
    desc: "DC 24, attack +16; __3rd __  _[[Spells/Phantom Pain|Phantom Pain]]_, _[[Spells/Shatter|Shatter]]_; __2nd __  _[[Spells/Item Facade|Item Facade]]_, _[[Spells/Stupefy|Touch of Idiocy]]_; __1st __  _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(3rd)__ _[[Spells/Daze|Daze]]_"

  - name: "Manifest False Memories"
    desc: "`pf2:2` (concentrate,emotion,mental,occult) The ijda releases a cloud of red butterflies from its body, each of which carries a false memory that infects those they brush against. All non-nindoru creatures within 10 feet of the ijda must attempt a DC 21 Will check save. The ijda can't Manifest False Memories for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] until the end of its next turn.\n\n**Failure** The creature is stupefied 1 and [[Conditions/Confused|Confused]] until the end of its next turn.\n\n**Critical Failure** The creature is stupefied 1 and confused for 1 minute. It can attempt a new save at the end of each of its turns to end the effects."

  - name: "[[Actor.TVi4RDeqw7GDsxp0.Item.3mU3jco88GY5GjJy|Ruin Wielder]]"
    desc: "  When a ijda wields a broken non-magical weapon, they do not take any of the disadvantages of the weapon being broken. While the ijda wields it, the weapon becomes a +1 striking weapon that deals an additional 1d6 mental damage on a successful hit."
 
```

```encounter-table
name: Ijda
creatures:
  - 1: Ijda
```



Ijdas are creatures of forgetfulness. Born from souls who were once enlightened but then renounced it and their role in the cycle of reincarnation, they curse the futility of their existence and find pleasure in leading others to the same fate.

Ijdas appear as towering humanoids, their bodies bloated and constantly bursting with small red butterflies that flitter away before melting into mist. Their arms are overly long and so broken as to writhe more like tentacles, affording them an unsettling combat style with greater reach than most large creatures enjoy. They wear clothing and capes made of moldy straw and wield broken swords whose shattered blades still float roughly in place. Their most unsettling features are their complete lack of heads; instead, where a head should be sits a wicker cage filled with a writhing cloud of butterflies. Yet still, they see, hear, and speak without issue, as if their heads remained in place.

Formed without heads or even brains, an idja's mind is shared among the flocks of butterflies in their head cages or bursting from their bodies, and as each of these insects escapes and fades away, these forgetful fiends lose another potential thought. Unable to learn new things, any actions they take stem from memories etched into their souls or directives they blindly follow from other nindorus or creatures they've come to accept as superiors. Their movements, words, and reactions are all conducted via a type of muscle memory based on how their souls believe they should respond to their external stimuli. As a result, most now serve as brutal guardians, since their forgetfulness also prevents them from being able to sleep.

* * *

When an evil mortal soul that has been reincarnated multiple times is wrenched from the cycle of souls and corrupted, it can undergo a horrific transformation into a fiend known as a nindoru. A force for entropy and the breaking of cycles, nindorus are hideous creatures whose bodies often appear distorted, who wield weapons that have been shattered yet still function, and whose true face is often hidden from view. They display traits one might expect to see in an undead creature, such as decaying flesh or exposed bones, yet a nindoru is very much still alive.

Each nindoru epitomizes the fracture of a specific cycle, be it one from the natural world or from societal traditions. To the nindoru, nothing is more delicious than the consumption of a creature who has reincarnated multiple times, with those who are theoretically about to ascend to true enlightenment presenting the tastiest meal. Those slain by a nindoru are themselves torn from the cycle—the lucky ones move on to the Boneyard for judgment, but many are instead corrupted to form more of these horrific fiends.

Followers of Sangpotshi find nindoru to be particularly abhorrent and count them among the greatest threats imaginable. Most commonly found in regions of the world where the reincarnation cycle is strongest, nindorus are, like rakshasas and oni, associated most strongly with the Material Plane.

## Reincarnated Souls

In some cases, you'll know if a creature a nindoru attacks has a reincarnated soul. Ancestries like samsarans are always reincarnated souls, and a PC's backstory or even their background can often indicate the presence of a previous life. All of the PCs in Season of Ghosts qualify as reincarnated souls, as they've relived their lives over and over for decades. If you ever need to determine if a creature's soul is reincarnated for the purpose of adjudicating a nindoru's ability, attempt a DC 11 Flat check—on a success, it has a reincarnated soul.

## Nindoru Demigods

The most powerful nindorus are demigods, although their cults are quite rare. Prone to reincarnation after death, nindoru demigods like Kugaptee are more properly known as "nindoru ascetics."

## Nindoru Traitors

While most nindorus are purely chaotic evil in nature, legends tell of exceptionally rare nindorus who manage to escape their own nature and ascend, reincarnating after death into kami or other more benevolent spirits and shedding the nindoru trait as they do so. Of course, these "traitors" are regarded as the most delicious meals imaginable by the nindorus left behind.

## Nindoru Butterflies

One of the strangest shared traits of the various types of nindoru are the blood-red butterflies that seem to follow them around, nest on their bodies, or periodically emerge from their wounds. These unnerving insects are physical manifestations of the nindorus' thoughts and symbolize the countless past lives they once lived but turned their backs on. Nindoru butterflies never last long once they flutter more than a few feet from their source, fading away into smoke that quickly dissipates into the air.

## Other Nindorus

Many other types of nindorus exist beyond the four presented on these pages. Others include the corpse-copying akashtis (sobbing nindorus), infiltrators of society known as kagekumas (lurking nindorus), the dead defiling shisagishins (crooked nindorus), and the powerful and brutal argyrzeis (headless nindorus).
