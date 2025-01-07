---
title: "Shui Gui"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lhPMKttpBXbxCnxU" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Shui Gui"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Shui Gui"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[aquatic]]
trait_02: [[ghost]]
trait_03: [[incorporeal]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[water]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Tien"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Deception: +13, Diplomacy: +11, Religion: +12, Stealth: +16, Ghost Lore: +15"
abilityMods: [0, 5, 0, 4, 3, 4]
speed: 10 feet,  swim 40 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +14, __Will__ +10"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ fire 10; __Resistances__ PF2E.Damage.IWR.CompositeLabel.Exceptions5DoubleVs1"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Water-Bound Curse"
    desc: "  The shui gui is bound to the body of water in which it died. It's unable to move further than 120 feet from the edge of the water."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When the shui gui is destroyed, it reforms after 2d4 days within the body of water it's bound to, fully healing. It can be permanently destroyed if the body of the shui gui who originally died in the water can be found and laid to rest."

  - name: "Ti Shõn"
    desc: "`pf2:r` (death,divine) **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the shui gui dies of suffocation\n* * *\n\n**Effect** Ripping the spirit of its drowned victim out of the target's body, the shui gui enters the corpse to take the original owner's place. The shui gui then returns to life at the edge of its body of water as if it had been the target of a successful resurrect ritual, except it has the appearance of the target rather than its original body. After a week, the spirit of the drowned creature becomes a shui gui. The new spirit can't be raised from the dead by normal magical means until they've been destroyed as a shui gui."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+14 (agile, finesse, magical)\n__Damage__  2d6 + 4 void plus grab"

  - name: "Drag Under"
    desc: "`pf2:1`  The shui gui Swims at half Speed, along with any creature it has [[Conditions/Grabbed|Grabbed]]."

  - name: "Drown the Living"
    desc: "`pf2:1`  **Requirements** The target must be holding its breath and be [[Conditions/Grabbed|Grabbed]] by the shui gui\n* * *\n\n**Effect** The shui gui tightens its grip. The target must succeed at a DC 24 Fortitude check save or immediately lose 1d4 actions worth of air (or twice that on a critical failure)."

  - name: "Ghostly Grasp"
    desc: "  A shui gui can [[Actions/Grapple|Grapple]] corporeal creatures despite being incorporeal. The shui gui uses its Athletics check to Grapple as normal but can't use Athletics for other actions that require corporeal contact, like [[Actions/Force Open|Force Open]] or [[Actions/Trip|Trip]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shui Gui
creatures:
  - 1: Shui Gui
```




