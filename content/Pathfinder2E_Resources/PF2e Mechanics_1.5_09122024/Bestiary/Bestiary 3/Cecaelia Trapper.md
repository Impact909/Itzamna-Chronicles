---
title: "Cecaelia Trapper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6LZoCM5HhFWCs6Xb" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Cecaelia Trapper"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Cecaelia Trapper"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision, Wavesense (Imprecise) 10 Feet"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +11, Stealth: +13, Survival: +9"
abilityMods: [4, 4, 3, -1, 2, 0]
speed: 20 feet,  swim 35 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +10, __Ref__ +15, __Will__ +11"
hp: 53
health:
  - name: ""
  - name: HP
    desc: "53"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|Longspear]], 2x [[Equipment/Net|Net]]"
  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 10 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+15 (magical, reach 10 feet)\n__Damage__  2d8 + 7 piercing"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+15 (agile, reach 10 feet)\n__Damage__  2d4 + 7 bludgeoning plus grab"

  - name: "Cecaelia Jet"
    desc: "`pf2:2` (move) The cecaelia moves up to 140 feet in a straight line through the water."

  - name: "Hurl Net"
    desc: "`pf2:1`  **Requirements** The cecaelia is holding a net in two appendages.\n* * *\n\n**Effect** The cecaelia hurls their net, attempting to hamper a foe. The cecaelia makes a ranged Strike (with a +15 modifier) against a Medium or smaller creature within 20 feet.\n\nOn a hit, the target is [[Conditions/Off-Guard|Off-Guard]] and takes a -10-foot circumstance penalty to its Speeds. On a critical hit, the creature is [[Conditions/Restrained|Restrained]]. The DC to [[Actions/Escape|Escape]] the net is 16. A creature adjacent to the target can Interact with the net to remove it from the target.\n\n[[Bestiary Effects/Effect_ Hurl Net|Effect: Hurl Net]]"

  - name: "Ink Cloud"
    desc: "`pf2:1`  The cecaelia emits a cloud of black ink in a 10-foot emanation. This ink cloud has no effect outside of water. Creatures inside the cloud are [[Conditions/Undetected|Undetected]] by creatures using sight or smell, and they can't see or smell while inside the cloud. The cloud dissipates after 1 minute.\n\nThe cecaelia can't use Ink Cloud again for 2d6 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cecaelia Trapper
creatures:
  - 1: Cecaelia Trapper
```



Cecaelias resemble humans with octopus tentacles instead of legs. These oceanic hunters are agile and intelligent creatures, but proud. Their inquisitiveness often brings them into contact with strangers, where a poor turn of phrase or an unintended insult can quickly spark their legendary tempers.

Cecaelias live nomadic lives, hunting and scavenging along coastlines for food and tradeable trinkets. They engage in frequent trade with terrestrial communities, offering anything from seafood to treasures retrieved from sunken vessels in exchange for goods not readily available underwater. Some take to piracy or hire themselves out as mercenaries, but their quarrelsome disposition invariably leads to them going their own way again before too long. The only non-cecaelia communities that maintain long-lasting relationships with cecaelias are those of the remarkably laid-back locathahs, who coexist with cecaelias in the city of Xidao.

Cecaelias live in warm waters along verdant ocean reefs or coastlines, often near humanoid settlements. Able to adapt rapidly over a few generations, cecaelias adopt the physical features of their closest humanoid neighbors, which sages liken to an octopus's natural camouflage.
