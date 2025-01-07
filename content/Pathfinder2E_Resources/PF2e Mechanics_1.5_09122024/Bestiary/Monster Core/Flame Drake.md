---
title: "Flame Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZBWtsVUpC40vEFWR" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Flame Drake"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Flame Drake"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[fire]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +12, Stealth: +9, Survival: +10"
abilityMods: [5, 1, 3, -1, 3, 0]
speed: 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +12, __Ref__ +10, __Will__ +10"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ cold 10"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a flame drake's vision; they ignore [[Conditions/Concealed|Concealment]] from smoke."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Fangs Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+14 ()\n__Damage__  2d8 + 5 piercing 1d6 fire"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+14 (reach 10 feet)\n__Damage__  2d6 + 5 bludgeoning"

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The flame drake makes two Fangs Strikes and one Tail Strike in any order."

  - name: "Fireball Breath"
    desc: "`pf2:2` (fire,primal) The flame drake expels a ball of flame to a range of 180 feet that explodes in a 20-foot burst. Creatures in the burst take 6d6 fire damage (DC 22 Reflex check save).\n\nThe flame drake can't use Fireball Breath again for 1d6 rounds."

  - name: "Speed Surge"
    desc: "`pf2:1` (move) **Frequency** three times per day\n* * *\n\n**Effect** The flame drake Strides or Flies twice."
 
```

```encounter-table
name: Flame Drake
creatures:
  - 1: Flame Drake
```



Flame drakes dwell near volcanoes and magma, but it's not unheard of for one to drift into nearby areas like forests or wooded hills. Their scales are usually some shade of red, occasionally fading to smoky blacks and grays along the edges of their wings and the tips of their tails.

Rampages of flame drakes often grudgingly live alongside clans of fire giants, rather than be forced from their volcanic homes.

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
