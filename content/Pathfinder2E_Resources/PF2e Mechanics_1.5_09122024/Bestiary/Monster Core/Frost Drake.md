---
title: "Frost Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NntqBlwabuyIkl94" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Frost Drake"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Frost Drake"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[cold]]
trait_02: [[dragon]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Intimidation: +14, Stealth: +15"
abilityMods: [6, 2, 4, -1, 3, 1]
speed: 20 feet,  burrow 20 feet,  climb 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +15, __Will__ +14"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  cold,  paralyzed,  sleep; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "Snow Vision"
    desc: "  Snow doesn't impair a frost drake's vision; they ignore [[Conditions/Concealed|Concealment]] from snowfall."

abilities_mid:
  - name: ""
  - name: "Retaliatory Strike"
    desc: "`pf2:r`  **Trigger** A creature within reach of the frost drake's tail successfully damages the frost drake with a Strike\n* * *\n\n**Effect** The frost drake attempts to Strike with their tail. If the Strike hits, it deals an additional 1d6 damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d12 + 8 piercing 1d6 cold"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+17 (reach 10 feet)\n__Damage__  2d10 + 8 bludgeoning"

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The frost drake makes two Fangs Strikes and one Tail Strike in any order."

  - name: "Freezing Mist Breath"
    desc: "`pf2:2` (cold,primal) The frost drake spits a ball of liquid up to 60 feet that explodes into a 20-foot burst cloud of freezing mist. Those in the burst take 8d6 cold damage (DC 25 Reflex check save).\n\nThe frost drake can't use Freezing Mist Breath again for 1d6 rounds, during which the mist cakes all surfaces in the area with a sheet of slippery ice that turns the area into difficult terrain."

  - name: "Ice Climb"
    desc: "  A frost drake isn't impeded by difficult terrain caused by snow or ice, nor do they need to attempt Acrobatics checks to keep from falling on slippery ice."

  - name: "Speed Surge"
    desc: "`pf2:1` (move) **Frequency** three times per day;\n* * *\n\n**Effect** The frost drake Strides or Flies twice."
 
```

```encounter-table
name: Frost Drake
creatures:
  - 1: Frost Drake
```



Frost drakes pose an immense danger in the frozen reaches they call home, where they roam far and wide to hunt for prey such as caribou, wolves, small bears, tundra-dwelling people, and even lone frost giants. These drakes take advantage of long distances to hide from the repercussions of their actions, as they are usually among the most depraved and openly malicious of the drakes. They are also especially insolent and are less likely to back down from a fight compared to other drakes. Many frost drakes have met their ends trying to enact cruelties beyond their means, such as singly taking on a frost giant clan or well-fortified township.

Frost drakes hunt alone more often than other drakes, due to a scarcity of prey and simple temperament. Although a single frost drake can wreak much destruction on their own, tales of village-dwelling northerners banding together to defend their homes from these rogue menaces are fairly common.

A frost drake's hunting grounds are quite large. Those frost drakes that live upon the permanently frozen peaks of high mountains have been known to swoop down to snatch up prey from the lowlands, leaving frozen swaths of earth from their breath as the only sign of their passing. Their frostcovered scales range from deep royal blue to crisp cyan and sometimes feature sporadic patches of violet. Their hides are thinner than most drakes'; when a frost drake is inhaling in preparation to launch their signature frozen breath, the monster's ice-blue blood can be seen beneath their scales.

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
