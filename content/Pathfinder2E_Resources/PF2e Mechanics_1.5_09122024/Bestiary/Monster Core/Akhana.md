---
title: "Akhana"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RoxyZ9oFMDNN8dqU" 
tags:
  - pf2e/creature/type/aeon
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Akhana"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Akhana"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[aeon]]
trait_02: [[monitor]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Lifesense 120 Feet"
languages: "Envisioning"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +24, Medicine: +23, Occultism: +21, Religion: +23, Axis Lore: +23"
abilityMods: [6, 6, 7, 3, 5, 4]
speed:  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +23, __Ref__ +22, __Will__ +23; +1 status to all saves vs. magic"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  vitality,  void; __Weaknesses__ spirit 10"
abilities_top:
  - name: ""

  - name: "Envisioning"
    desc: " (aura,divine,mental) 100 feet\n* * *\n\nAn akhana can communicate mentally with any creatures in the aura using wordless psychic projections. They don't need to share a language, though the aeon's meaning to non-aeons can be vague and is often mysterious. An aeon can use this ability to communicate flawlessly with any other aeon on the same plane as itself."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/At-Will Spells|At-Will Spells]]"
    desc: "  The monster can cast its at-will spells any number of times without using up spell slots."

abilities_mid:
  - name: ""
  - name: "Balance Life"
    desc: "`pf2:r` (divine) **Trigger** A creature within 100 feet is about to attempt a recovery check\n* * *\n\n**Effect** The akhana chooses to make the result a success or failure (but not a critical success or failure). This effect gains the fortune trait if the akhana chooses success or misfortune for failure."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+24 (magical, void)\n__Damage__  5d10 void plus grab"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (agile, magical)\n__Damage__  3d6 + 12 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 32, attack +24; __4th __  _[[Spells/Harm|Harm (At Will)]]_, _[[Spells/Heal|Heal (At Will)]]_; __2nd __  _[[Spells/Peaceful Rest|Peaceful Rest]]_\n__Cantrips__  __(6th)__ _[[Spells/Stabilize|Stabilize]]_, _[[Spells/Vitality Lash|Vitality Lash]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Flying Fists"
    desc: "`pf2:2`  The akhana Flies and makes up to four fist Strikes against different targets at any points during this movement. The attacks count toward its multiple attack penalty normally, but the penalty does not increase until after Flying Fists is complete."

  - name: "Reclaim Life"
    desc: "`pf2:1` (divine,void) **Requirements** The akhana has a living creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] with its tail\n* * *\n\n**Effect** The creature takes 4d10 void damage with a DC 32 Fortitude check save. On a failed save, it's also [[Conditions/Doomed|Doomed 1]]. If the creature dies while doomed and held in the akhana's tail, its soul is trapped in the akhana (as [[Spells/Seize Soul|Seize Soul]]), and its remains are preserved as peaceful rest. The soul returns to the body with 1 Hit Point if the akhana [[Actions/Dismiss|Dismisses]] the effect, if the akhana is slain, or if a [[Spells/Wish|Wish]] ritual or similarly powerful magic frees it."

  - name: "Sprout Life"
    desc: "`pf2:2` (concentrate,divine,plant,vitality) A 5-foot burst within 100 feet fills with simple life appropriate to the environment. The newly forged animals bite those in the area for 7d6 piercing damage with a DC 32 Reflex check save. The akhana can also have fungus or plants choke the area, even floating ones in the sky, creating difficult terrain. The created life lives or dies normally after its creation."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Akhana
creatures:
  - 1: Akhana
```



Akhanas are massive eyes formed of cosmic matter that monitor the balance of birth and death. They understand the profound influence living things have on the cosmos and silently perform their duties of supporting and pruning life. Akhanas seem utterly unconcerned by the fate of souls after death, often leaving undead in their wake or attracting daemon scavengers. Psychopomps often despair over akhanas' cryptic actions, forced to clear out sudden backlogs of souls or even battle the aeons directly. Their "tail" is a twisting column of cosmic energy that can drain vitality from creatures and seal their fate.

* * *

Aeons have always been the caretakers of reality and defenders of the natural order of balance. Each type of aeon takes on some form of duality in its manifestation and works either to shape the multiverse within the aspects of this duality in some way, or to correct imbalances to the perfect order of existence. Aeons' machinations can raise a nation, raze it, or restore it from ruin. Their reasons are their own, and they rarely share their motivations with others—through their strange envisioning mode of communication, they simply create the results they insist are necessary to maintain the balance of the multiverse.

As a result of recent shifts in reality, aeons have begun to reassert a presence in the perfect planar city of Axis. To aeons, this is merely the latest in a recurring cycle, albeit one that mortals have not yet borne witness to. Aeons have a name for this cyclic return, in which they welcome their industrious axiomite brethren back to their fold: the Convergence. At the onset of the Convergence, a council of pleroma aeons appeared in the Eternal City of Axis, where they revealed that axiomites were wayward aeons, split off long ago to pursue the act of creation. With the latest cycle of change, it was time for axiomites—and their mortal creations and kin—to rejoin the aeon cause. While most axiomites fell in line, realizing perhaps on a fundamental level of reality that what the aeons said was the truth, some refused to heed the call and waited for the wrath of the aeons. That wrath has yet to come. The dual-natured aeons have responded to those who have declined in confusing ways. With some they treat and even bargain, while a handful of others they have destroyed, and a few have been exterminated by the axiomites. But most of these quiet insurgents they leave alone, allowing these axiomites to continue to create in peace. How—or if—this Convergence will end is as little understood as aeons themselves.
