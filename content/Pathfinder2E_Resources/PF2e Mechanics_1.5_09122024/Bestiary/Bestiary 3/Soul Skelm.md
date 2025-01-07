---
title: "Soul Skelm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Jk0B0u93KpSXI6RY" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/skelm
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Soul Skelm"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Soul Skelm"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
trait_05: [[skelm]]
trait_06: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Deception: +21, Occultism: +19, Society: +19, Stealth: +17"
abilityMods: [6, 3, 5, 3, 5, 7]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +17, __Will__ +21; -2 to all saves vs. emotion effects"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  possession; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+1 Striking Ghost Touch Spiked Chain]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+22 (agile, magical, unholy)\n__Damage__  2d8 + 12 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+22 (magical, unholy)\n__Damage__  2d12 + 12 piercing plus knockdown"

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+23 (disarm, magical, trip, unholy)\n__Damage__  2d8 + 12 slashing plus knockdown"

  - name: "Occult Innate Spells"
    desc: "DC 29, attack +21; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (Self Only) (Astral or Material Plane Only)]]_; __5th __  _[[Spells/Harm|Harm]]_, _[[Spells/Illusory Creature|Illusory Creature]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Rewrite Memory|Modify Memory]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will)]]_, _[[Spells/Silence|Silence (At Will)]]_"

  - name: "Bully the Departed"
    desc: "`pf2:1` (auditory,emotion,mental,occult,unholy) The skelm draws upon the spirit of one of his deceased victims, tormenting their soul beyond the grave. Until the end of his next turn, the soul skelm gains regeneration 15 (deactivated by force or good), and he deals an extra 1d8 spirit damage on his Strikes.\n\n[[Bestiary Effects/Effect_ Bully the Departed|Effect: Bully the Departed]]"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The soul skelm can take on the appearance of any Medium male humanoid. This doesn't change his Speed or his attack and damage bonuses with his Strikes but might change the damage type his Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Isolating Lash"
    desc: "`pf2:2` (illusion,occult) The soul skelm makes a melee Strike trailing a wave of shadowy illusions. The skelm is [[Conditions/Off-Guard|Off-Guard]] until the start of his next turn. If the Strike is successful, the skelm increases the number of damage dice by one, and the target must attempt a DC 29 Will check save.\n\nOn a failure, the target becomes [[Conditions/Invisible|Invisible]], inaudible, and otherwise imperceptible to its allies for 4 rounds, and it likewise can't see, hear, or otherwise perceive those allies.\n\nRegardless of the outcome, the creature is temporarily immune to Isolating Lash for 24 hours."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Soul Skelm
creatures:
  - 1: Soul Skelm
```



Soul skelms arise not from mortal men but from other skelms, as their long-held wrath slowly twists them and replaces lingering fragments of their mortality with even more fiendish aspects. These skelms bully and exploit the souls of the dead, binding souls and undead to keep themselves indefinitely young. They bully living victims as well, stoking regret and shame even from inconsequential minutiae or outright fabrications until these feelings become unbreakable ties that the skelm can leverage from beyond the grave. A soul skelm's attentions can leave a victim isolated from friends and allies, making them all the more susceptible to the skelm's manipulations.

Ambitious soul skelms-often those who arise from palace skelms-search out powerful, high-strung mortals and trick them into bringing ridicule or shame on themselves. After their victim's death, the skelms gleefully remind them of their mortal failings, feeding on their despair.

* * *

Rage-filled skelms are drawn to any settlement with more than a few hundred souls. Using magical disguises and leveraging societal norms to their benefit, these antlered monsters crave fearful respect and brutally punish any who dare disagree with their lofty opinions, even in the slightest degree. Although quite dangerous on their own, skelms are at their deadliest when leading an angry mob. Their cruel and exploitative nature has made their name synonymous with villainy.

An existing skelm can transform any evil humanoid who's overwhelmed with rage into one of their kind. Skelms heap enraging humiliation on potential new brothers as a form of indoctrination, convincing these recruits that some other person or group is responsible for their misery. This practice ensures skelms begin their new existence with sufficient vitriol to plot their revenge.

Many newly forged skelms carry on their lives in the roles they held as mortals; and in fact, these roles often shape the type of skelm they become. Skelms can arise among members of nearly any ancestry, though they're more common among cultures with deeply entrenched gender roles, unjust hierarchies, and those that don't offer healthy ways to experience and process anger.
