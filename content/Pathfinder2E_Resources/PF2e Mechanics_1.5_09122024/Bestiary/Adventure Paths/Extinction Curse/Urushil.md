---
title: "Urushil"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RabWKyLX3BSREuGE" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Urushil"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Urushil"
level: "Creature 18"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Deception: +30, Diplomacy: +30, Intimidation: +32, Religion: +29, Stealth: +29, Warfare Lore: +31"
abilityMods: [8, 6, 6, 4, 4, 7]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +34, __Ref__ +32, __Will__ +30; +1 status to all saves vs. magic"
hp: 410
health:
  - name: ""
  - name: HP
    desc: "410; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+3 Major Striking Longsword]], [[Equipment/Breastplate|+3 Major Resilient Breastplate]], [[Equipment/Belt of Long Life|Belt of Regeneration]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  A marilith gains 5 extra reactions per round that they can use only to make Attacks of Opportunity. The demon can't use more than one on the same triggering action, even if a creature leaves several squares in the marilith's reach, and the marilith must use a different weapon for each Attack of Opportunity.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Commander's Aura"
    desc: " (aura,divine) 100 feet. Commanded or allied evil creatures in the aura of lower level than the marilith gain a +1 circumstance bonus to attack rolls, damage rolls, AC, saves, and skill checks.\n* * *\n\n[[Bestiary Effects/Effect_ Commander's Aura|Effect: Commander's Aura]]"

  - name: "Failure Vulnerability"
    desc: "  A marilith's pride feeds their strength, so the sting of failure wounds them. If the marilith uses a damaging spell or makes a Strike on their turn but doesn't deal any damage that turn, they take 3d6+10 mental damage at the end of their turn and their commander's aura deactivates until the end of their next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cold Iron Silver Longsword"
    desc: "+38 (magical, reach 10 feet, unholy, versatile p)\n__Damage__  4d8 + 18 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (magical, reach 10 feet, unarmed, unholy)\n__Damage__  3d12 + 18 bludgeoning plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Blade Barrier|Blade Barrier (x2)]]_, _[[Spells/Weapon Storm|Weapon Storm (x2)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_ __(4th)__ _[[Spells/Fly|Fly]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Bladestorm"
    desc: "`pf2:2`  The marilith makes up to six longsword Strikes, each against a different target. These attacks count toward the marilith's multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks."

  - name: "Defensive Assault"
    desc: "`pf2:2`  The marilith makes two Strikes, each with a different weapon, and they use the remaining weapons for protection. The demon gains a circumstance bonus to AC for 1 round equal to the number of weapons not used for attacks. If the marilith later uses any of those weapons to attack (including for an Attack of Opportunity), the bonus to AC decreases by 1 for each weapon used.\n* * *\n\n[[Bestiary Effects/Effect_ Defensive Assault|Effect: Defensive Assault]]"

  - name: "Focused Assault"
    desc: "`pf2:2`  The marilith attacks a single target with all the weapons they wield in their arms, overwhelming the target with multiple attacks and leaving almost nowhere to dodge. The demon makes a longsword Strike. On a successful attack, the marilith deals longsword damage to the target, plus an additional 1d8 slashing damage for every longsword they wield beyond the first (typically 5d8 slashing damage). Even on a failed attack, the marilith deals the damage from one longsword to the target, though they still miss completely on a critical failure. This counts toward the marilith's multiple attack penalty as a number of attacks equal to the number of longswords the pride demon wields.\n* * *\n\n[[Bestiary Effects/Effect_ Focused Assault|Effect: Focused Assault]]"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d12+13 bludgeoning damage, DC 41 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Infuse Weapons"
    desc: " (divine) Any weapon becomes a _+2 [[Equipment/Striking (Greater)|Greater Striking]] weapon_ made of cold iron and silver while a marilith wields it."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Urushil
creatures:
  - 1: Urushil
```


Elite marilith

Mariliths are the generals of the Abyss, formed from the souls of proud evil mortals, often warlords and despots. They appear as tall and powerfully built humans from the waist up with snake tails and six arms. Because of Lamashtu's prominence over other demonic deities, most pride demons encountered by mortals take female form, but they can be of any gender.

Mariliths are among the greatest tacticians in the Abyss, and they have an almost supernatural knack for understanding the ripples of chaos and the unpredictable nature of demonic life. Their ability to command armies rises as much from their commanding presence as it does their ability to read into the potential results of any possible act and a sufficient understanding of the flow of entropy to allow them to predict likely outcomes.

* * *

When a sinful mortal soul is judged and sent on to the Abyss, it can become a deadly fiend-a demon. Demons are living incarnations of sin-be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold-the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Abyss.
