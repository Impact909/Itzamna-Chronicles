---
title: "Jungle Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jj80bGiagsIAX25q" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Jungle Drake"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Jungle Drake"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[wood]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +13, Stealth: +13, Survival: +11"
abilityMods: [5, 3, 4, -1, 1, 1]
speed: 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +13, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Twisting Tail"
    desc: "`pf2:r`  **Trigger** A creature within reach of the jungle drake's stinger uses a move action or leaves a square during a move action it's using.\n* * *\n\n**Effect** The jungle drake Strikes the target with its stinger. If it hits, the jungle drake disrupts the creature's action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d10 + 7 piercing plus predatory-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+17 (reach 10 feet)\n__Damage__  2d6 + 7 piercing plus jungle-drake-venom"

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The jungle drake makes one Fangs Strike and two Stinger Strikes in any order."

  - name: "Forest Passage"
    desc: "  The jungle drake ignores difficult terrain caused by plants, such as bushes, vines, and undergrowth. Even plants manipulated by magic don't impede their progress."

  - name: "Jungle Drake Venom"
    desc: " (poison) **Saving Throw** DC 24 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Predatory Grab]]"
    desc: "`pf2:1`  As Grab, but the jungle drake's Grab doesn't end if they move away. Instead, they carry the [[Conditions/Grabbed|Grabbed]] creature with them. A jungle drake can't Fly while grabbing a creature unless that creature can also Fly.\n* * *\n\n**Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "Speed Surge"
    desc: "`pf2:1` (move) **Frequency** three times per day\n* * *\n\n**Effect** The jungle drake Strides or Flies twice."

  - name: "Spit Venom"
    desc: "`pf2:2` (poison) A jungle drake can spit a sticky glob of their venom to a range of 50 feet that explodes in a 10-foot burst. Those in the burst must succeed at a DC 24 Reflex check save or be exposed to jungle drake venom.\n\nThe jungle drake can't use Spit Venom again for 1d6 rounds."
 
```

```encounter-table
name: Jungle Drake
creatures:
  - 1: Jungle Drake
```



Believed to be related to horned dragons, jungle drakes are dangerous hunters equipped with a debilitating venom delivered by a large barbed stinger or their noxious phlegm. Their wings are equipped with vestigial claws that allow them to deftly maneuver through thick jungle foliage both in flight and on foot. Jungle drakes prefer to ambush their prey using hit-and-run tactics, picking off the weakest members of a group and dragging their victims off to finish their meals as they please. Rampages of jungle drakes will often drag prey in many directions to divide pursuit.

* * *

Ravenous, bestial, and driven by instinct, drakes are draconic monsters who bear a fraction of the terrifying might of the primal dragons they share evolutionary roots with. While they're weaker, slower, and less inclined toward reason than dragons, drakes are nonetheless a menace to creatures and settlements around them. Their propensity for forming raiding parties—small social groups fittingly called "rampages"—makes them all the more dangerous; a single rampage of river drakes can quickly lay waste to a waterside village, and roving rampages of desert drakes are a plague to caravan traders.

Drakes share a number of physical characteristics that unite them as one species despite their wide variety of habitats and abilities. For example, drakes lack forearms, leaving them with their formidable jaws and thickscaled tails to use in close combat. Most drakes would rather avoid this, however, preferring to use their magical breath to wreak havoc in wide swaths from comfortable distances while flying overhead. Finally, all drakes have small reservoirs of their ancestral draconic power that they can tap into to perform incredible feats of speed.

Different species of drakes rarely come into conflict. Part of this is their distinct habitats, but drakes are open to negotiating simple agreements between rampages. This courtesy does not extend to dragonets, which drakes happily take as prey. Solitary tamed drakes are also excluded from such agreements and considered free game if their tamer isn't strong enough to protect them.

### Drake Eggs

While drake hides aren't any more valuable than those of similarly sized creatures, drake eggs are prized commodities. They are used as components in powerful spells as well as eaten by various cultures, but the most common use for drake eggs is hatching and rearing drakes to serve as mounts and guardians.

A typical drake lays a clutch of 2d4 eggs every 5 years. Eggs hatch within 3 to 6 weeks, during which time they must be kept in conditions appropriate to their natural environment, perhaps the most difficult aspect of drake husbandry. While it is generally easy for breeders to incubate the eggs of desert or jungle drakes (which require mildly warm temperatures to hatch) or river drakes (which must be submerged in running water), the eggs of flame and frost drakes require extreme temperatures in order to hatch, which can be difficult to replicate safely.

A drake egg is an object with Hardness 3, 5 HP, and no Broken Threshold. The coloration of drake eggs varies only slightly from one species to the next. A creature must succeed at a DC 20 Nature check check, or a relevant DC 20 Lore check, to identify the drake species of a specific egg.

Once a drake hatches, they imprint on the first creature that they see. A creature imprinted on in this way can use Nature to Train and Command that drake. The market price of a drake egg varies depending on the type of drake and the exact legal situation. Because drakes are dangerous and intelligent creatures, many societies do not condone the trade of drake eggs and criminalize those who engage in it.

It takes 2 years for a drake hatchling to grow to full size. A well-trained drake can make a fearsome mount or guardian, but many careless would-be drake trainers are devoured by their charges.
