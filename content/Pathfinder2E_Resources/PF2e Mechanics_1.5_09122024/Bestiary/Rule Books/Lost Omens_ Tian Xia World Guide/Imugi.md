---
title: "Imugi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oy2ZvtSmoCZKVvGZ" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Imugi"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Tian Xia World Guide"
name: "Imugi"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[water]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; "
languages: "Draconic, Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Intimidation: +15, Stealth: +15"
abilityMods: [6, 4, 4, 2, 1, 2]
speed: 40 feet,  swim 60 feet
sourcebook: "_Pathfinder Lost Omens: Tian Xia World Guide_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +19, __Will__ +14"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  paralyzed,  sleep; __Weaknesses__ poison 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Scent|Scent (Imprecise) 60 feet]]"
    desc: "  Scent involves sensing creatures or objects by smell, and is usually a vague sense. The range is listed in the ability, and it functions only if the creature or object being detected emits an aroma (for instance, incorporeal creatures usually do not exude an aroma).\n\nIf a creature emits a heavy aroma or is upwind, the GM can double or even triple the range of scent abilities used to detect that creature, and the GM can reduce the range if a creature is downwind."

  - name: "[[Bestiary Ability Glossary/Darkvision|Darkvision]]"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank _[[Spells/Darkness|Darkness]]_ spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Nesting"
    desc: "  By coiling around a butterfly koi egg for 1 minute, the imugi designates it as their chosen heir, which grants the imugi the effects of a constant status spell on that egg. If the egg is destroyed or otherwise made nonviable, the imugi can choose a new koi egg with this ability after 1 week."

abilities_mid:
  - name: ""
  - name: "Parental Wrath"
    desc: "`pf2:r`  **Trigger** A creature damages the imugi's chosen koi egg or ends its turn within 40 feet of the egg\n* * *\n\n**Effect** The imugi Strides or Swims toward the triggering creature. If they end their movement within reach of the creature, they can attempt a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 (reach 10 feet)\n__Damage__  2d10 + 8 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+17 (agile)\n__Damage__  2d6 + 8 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+17 (reach 15 feet)\n__Damage__  2d4 + 8 bludgeoning plus grab"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Fly|Fly]]_, _[[Spells/Water Breathing|Water Breathing]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+4 bludgeoning, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Floodwaters"
    desc: "`pf2:2` (primal,water) Waters rush forth in a 60-foot line, dealing 4d6 bludgeoning damage (DC 25 Reflex check save). Creatures that fail the save and aren't [[Conditions/Grabbed|Grabbed]] by the imugi are pushed 10 feet away."

  - name: "Storm Veil"
    desc: "  The imugi twists any nearby precipitation into a swirling veil of sleet and wind. They gain concealment when in any form of mist or rain."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Imugi
creatures:
  - 1: Imugi
```



Imugi (ee-moo-ghee) are dragon-like serpents with great mystic potential, including that of ascension into another form. While some imperial dragons are born to their birthright, many that currently roam Tian Xia are ascended imugi—though they would strike down anyone who claimed such.

To become an imperial dragon, imugi must care for a koi egg for a thousand years. The power from the nurtured egg hatching is enough to power a draconic ascension ritual, and whatever power lingers transforms the koi into an imugi to continue the cycle. The kind of imperial dragon that the imugi becomes depends on where it chooses to nurture the koi egg. Imugi strongly prefer long-finned koi, and Tian koi farmers have learned to keep a separate pool of these butterfly koi away from the others they tend, as imugi tend to displace quite a bit of water—and koi—when swooping down to snatch an egg they want.

Though imugi have some power over rain and storms, most aren't powerful enough to exact a true sense of weather control. Many are known for their benevolence, and some villages even rely on imugi's forays out of streams or lakes, bringing rains during the growing season. Imugi have as wide a range of temperaments as the dragons they become, and some are notorious for how their impatience twists into a foul temper or an arrogance that flicks people aside as if they were bugs. While some might consider mean-spirited imugi corrupted and claim they can be purified somehow, imugi simply hold themselves higher than the average creature and see no reason to conceal their true nature from someone they see as beneath them.
