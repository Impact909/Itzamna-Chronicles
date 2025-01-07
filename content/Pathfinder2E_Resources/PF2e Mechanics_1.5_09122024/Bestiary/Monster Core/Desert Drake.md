---
title: "Desert Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BS817ZE468e0arlO" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Desert Drake"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Desert Drake"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[earth]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Intimidation: +13, Stealth: +15, Survival: +15"
abilityMods: [6, 3, 5, -1, 3, 1]
speed: 20 feet,  burrow 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +15, __Will__ +13"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  paralyzed,  sleep; __Resistances__ cold 10, fire 10"
abilities_top:
  - name: ""

  - name: "Sandstorm Sight"
    desc: "  Sandstorms don't impair a desert drake's vision; they ignore [[Conditions/Concealed|Concealment]] from sandstorms. They also are immune to being [[Conditions/Dazzled|Dazzled]] or [[Conditions/Blinded|Blinded]] by sand or other grit."

abilities_mid:
  - name: ""
  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** The desert drake is targeted with an attack\n* * *\n\n**Effect** The desert drake raises their wing, gaining a +2 circumstance bonus to AC against the triggering attack. If the desert drake is flying at the time they're attacked, they descend 10 feet after the attack is complete."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+19 ()\n__Damage__  2d12 + 10 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 (reach 10 feet)\n__Damage__  2d10 + 10 bludgeoning plus push"

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The desert drake makes two Fangs Strikes and one Tail Strike in any order."

  - name: "Sandstorm Breath"
    desc: "`pf2:2` (earth,primal) The desert drake spits a ball of abrasive sand with a range of 60 feet that explodes into a cloud with a 15-foot burst. Creatures in the area take 9d6 slashing damage (DC 27 Reflex check save).\n\nThe desert drake can't use Sandstorm Breath again for 1d6 rounds, during which the sandstorm lingers in the area. This lingering sandstorm grants [[Conditions/Concealed|Concealment]] to everything within it and conceals everything outside from them."

  - name: "Speed Surge"
    desc: "`pf2:1` (move) **Frequency** three times per day\n* * *\n\n**Effect** The desert drake Strides or Flies twice."

  - name: "Surprise Attacker"
    desc: "  On the first round of combat, creatures that haven't acted yet are [[Conditions/Off-Guard|Off-Guard]] to the desert drake."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Desert Drake
creatures:
  - 1: Desert Drake
```



These distant cousins of creatures like adamantine dragons are a pale echo that lacks their relatives' power and intelligence. Desert drakes are nonetheless dangerous ambush predators, preying upon isolated desert travelers and outposts for food and supplies. Desert drakes' scales range in coloration from rust-brown to light tan and ocher shades, mimicking the colors of the dunes they call home.

Like frost drakes, a rampage of desert drakes often claims a huge span of territory, watching over an expanse of desert from a perch in nearby mountains or a nest among weathered ruins. Any creature visible on the surface is liable to be targeted by the drakes, especially humanoid caravans. Rampages along trade routes quickly learn to leave a member watching over each oasis for new prey. During especially lean times, the drakes will even dig out subterranean prey like ankhravs, giant scorpions, or entire nests of giant ants.

Desert drakes are among the lightest and most compact of the drakes, though this shouldn't be mistaken for frailty. Their swooped-back horns and feather-thin wings are adapted to make burrowing as easy as possible. Indeed, a desert drake's powerful neck makes wriggling through sand and other loose scree as easy as walking for it.

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
