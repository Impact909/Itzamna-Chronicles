---
title: "Gongorinan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GqSZxGItpRIl3ljM" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Gongorinan"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gongorinan"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[fiend]]
trait_02: [[qlippoth]]
trait_03: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Chthonian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +23, Intimidation: +21, Stealth: +21"
abilityMods: [6, 6, 7, 1, 3, 4]
speed: 40 feet,  climb 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +21, __Will__ +20"
hp: 205
health:
  - name: ""
  - name: HP
    desc: "205; __Immunities__  controlled,  fear effects; __Resistances__ mental 10, physical 10 (except cold iron)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Club|+1 Striking Club]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+24 ()\n__Damage__  2d6 + 9 bludgeoning plus reject-tools"

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+23 (magical, unholy)\n__Damage__  2d6 mental plus grab 2d10 + 9 slashing plus grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+23 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 9 bludgeoning 2d6 mental"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+23 (magical, unholy)\n__Damage__  2d6 + 9 piercing plus gongorinan-venom"

  - name: "Occult Innate Spells"
    desc: "DC 30, attack +22; __6th __  _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_, _[[Spells/Petrify|Petrify]]_; __3rd __  _[[Spells/One with Stone|One with Stone (At Will)]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Disquieting Display"
    desc: "`pf2:2` (concentrate,mental,occult,visual) The gongorinan opens its maw to reveal the forms [[Conditions/Hidden|Hidden]] there, making observers question their own bodies. Creatures in a 30-foot emanation must attempt a DC 30 Will check save, after which they are temporarily immune to further Disquieting Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Clumsy|Clumsy 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Critical Failure** As failure, but for 1 minute."

  - name: "Gongorinan Venom"
    desc: " (poison,polymorph) **Saving Throw** DC 30 Fortitude check\n* * *\n\n**Stage 1** [[Conditions/Stupefied|Stupefied 1]] and cosmetic signs appear of turning into an animal, fungus, or plant (1 round)\n\n**Stage 2** [[Conditions/Stupefied|Stupefied 2]] and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** [[Conditions/Stupefied|Stupefied 4]] and [[Conditions/Clumsy|Clumsy 4]] (1 round)\n\n**Stage 4** [[Conditions/Paralyzed|Paralyzed]] as changes completely overtake the body (1 round)\n\n**Stage 5** the victim permanently transforms into an animal, fungus, or plant in mind and body as a permanent curse, and the affliction ends"

  - name: "Painful Limbs"
    desc: "`pf2:2`  The gongorinan makes up to four Strikes against different targets, each using a different limb. All four Strikes count toward its multiple attack penalty, but the penalty doesn't increase until after the gongorinan has made all the attacks."

  - name: "Reject Tools"
    desc: " (mental,occult) A creature hit by the gongorinan's club must succeed at a DC 30 Will check save or [[Actions/Release|Release]] any manufactured items it's holding."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Gongorinan
creatures:
  - 1: Gongorinan
```



While most qlippoths focus on wiping mortals from existence, gongorinans follow the divergent plan of trapping mortals in forms incapable of understanding their actions and performing any sin meriting condemnation to the Outer Rifts. What may seem as a mercy to some is a matter of dire necessity to the gongorinans, who see killing sinful mortals as tantamount to helping their foes.

* * *

Long before the creatures known as demons came to be the dominant force in the Outer Rifts, qlippoth ruled the innumerable cracks of the Outer Sphere. These inimical creatures are a form of primordial and alien evil that predates mortal life, and most immortal life as well. Since the rise of mortal sin and the associated expansion of demonic life through the Outer Rifts, qlippoth have been driven to their deepest reaches, and they seethe with rancor at the loss of their realms. Yet, rather than directly oppose demons, qlippoth instead turn to the source—mortal sin—and wage an endless war to eradicate all creatures capable of sinful acts so that the demonic tide might be turned back. To ensure they do not bolster their foe's ranks, they enact horrific transformations on their targets, converting their victims into beings incapable of discerning right from wrong; this renders them unable to be judged by Pharasma's courts and thus incapable of becoming fiends. Most mortals consider the ministrations of a qlippoth to be far worse than any fate awaiting them in the afterlife.
