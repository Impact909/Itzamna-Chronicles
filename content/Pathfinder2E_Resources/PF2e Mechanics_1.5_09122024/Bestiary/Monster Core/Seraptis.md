---
title: "Seraptis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.I7gvmgGy0GuJkQDb" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Seraptis"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Seraptis"
level: "Creature 15"

alignment: ""
size: "Medium"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Truesight"
languages: "Chthonian, Draconic, Empyrean; Telepathy 100 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +31, Deception: +29, Religion: +27, Stealth: +28"
abilityMods: [8, 7, 6, 3, 4, 6]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +28, __Will__ +25; +1 status to all saves vs. magic"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340, blood healing; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Scimitar|+1 Striking Wounding Scimitar]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Blood Healing"
    desc: " (aura,healing,vitality) 30 feet.\n\nWhenever a humanoid within the aura takes bleed damage, the blood flows through the air to the seraptis's mouths and the seraptis heals by the same amount."

  - name: "Recovery Vulnerability"
    desc: "  When a creature within the seraptis's blood healing aura recovers from persistent damage, the seraptis takes 3d6 mental damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wounding Scimitar"
    desc: "+32 (forceful, magical, sweep, unholy)\n__Damage__  1d6 bleed 2d6 + 16 slashing 2d6 mental"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+31 (agile, magical, unholy)\n__Damage__  2d4 + 16 slashing plus grab 2d6 mental plus grab"

  - name: "**Melee** `pf2:1` Caustic Blood"
    desc: "+30 (acid, magical, unholy)\n__Damage__  7d6 acid"

  - name: "Divine Innate Spells"
    desc: "DC 35, attack +27; __8th __  _[[Spells/Dominate|Dominate]]_; __6th __  _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Wave of Despair|Wave of Despair]]_; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_; __3rd __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_\n__Constant__  __(8th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Bloody Dance"
    desc: "`pf2:2`  The seraptis makes a Strike with up to four arms, each against a different target and using a claw or scimitar as appropriate. These attacks count toward the seraptis's multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks. The seraptis can use Grab following this activity, separately attempting to [[Actions/Grapple|Grapple]] each creature hit by a claw."

  - name: "Gnawing Arms"
    desc: "`pf2:1` (unholy) **Requirements** The seraptis has at least one creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The seraptis's arm mouths gnaw on those creatures, dealing each of them 2d6+8 piercing damage with a DC 37 Fortitude check save. Creatures that fail the save also take 2d6 persistent bleed damage."

  - name: "Isolating Words"
    desc: "`pf2:1` (curse,linguistic,mental) The seraptis telepathically explains a plausible secret to a creature within 30 feet. That creature must succeed at a DC 37 Will check save or be mentally cut off from those around them for 1 minute (or permanently on a critical failure). The affected creature treats no one as an ally and any speech they hear is warped, encouraging conflict, and negating any linguistic ability from creatures that aren't unholy.\n\nRegardless of the results of the saving throw, the creature is immune to Isolating Words for 24 hours."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Seraptis
creatures:
  - 1: Seraptis
```



Four-armed seraptis demons are radical nihilists at heart, despising other creatures out of bitter entitlement and laughing hysterically when others die or suffer. They arise from souls that engaged in dedicated campaigns of misery, driving their victims toward despair and suicide. After their awakening as a seraptis, the hungry mouths carved into their arms devour others' suffering, bringing a lively hue to the demon's cold skin.

These demons seek to drag mortals down to their level, luring pawns into deepseated resentment. Feeding their targets an unending stream of half-truths and propaganda, they often drive these mortals to vent their rage into unforgivable deeds against innocents. Although thrilled by the misery their mortal pawns inflict, the demons' true comfort is to harvest the souls of those pawns as more of their kind.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
