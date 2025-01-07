---
title: "Shambler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7El4w410X3qd8NDr" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Shambler"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Shambler"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[plant]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Elven, Fey; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Stealth: +12"
abilityMods: [6, 1, 5, -2, 2, -1]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +17, __Ref__ +11, __Will__ +14"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  electricity; __Resistances__ fire 5"
abilities_top:
  - name: ""

  - name: "Mound"
    desc: "  When it's not in danger, the shambler spends 1 minute settling into a pile that looks like a lump of loose vegetation. While it is in this form, creatures must actively [[Actions/Seek|Seek]] and succeed at a DC 22 Perception check check (DC 28 Perception check in forests or swamps) to detect the shambler's true nature."

abilities_mid:
  - name: ""
  - name: "Electric Surge"
    desc: "  Whenever the shambler would take electricity damage or is targeted with an electricity effect, it gains 12 temporary HP and is [[Conditions/Quickened|Quickened]] until the end of its next turn. It can use its extra action to Stride, Strike, or Swim.\n\n[[Bestiary Effects/Effect_ Electric Surge|Effect: Electric Surge]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+17 (reach 10 feet)\n__Damage__  2d8 + 8 bludgeoning plus grab"

  - name: "Centipede Swarm Venom"
    desc: " (poison) **Saving Throw** DC 20 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d8 poison damage, [[Conditions/Clumsy|Clumsy 1]], and off-guard (1 round)"

  - name: "Shamble"
    desc: "`pf2:r`  **Requirements** The shambler is in mound form\n\n**Trigger** A creature unaware of the shambler's true nature comes within 10 feet.\n* * *\n\n**Effect** The shambler makes a vine Strike against the creature. Then roll initiative."

  - name: "Symbiotic Swarm"
    desc: "`pf2:r`  **Trigger** A creature is [[Conditions/Grabbed|Grabbed]] by the shambler.\n* * *\n\n**Effect** The creature is dealt 1d8 piercing damage (DC 20 Reflex check) and is exposed to centipede swarm venom."

  - name: "Vine Lash"
    desc: "`pf2:2`  The shambler makes a vine Strike against each creature within reach. Its multiple attack penalty increases only after all the attacks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shambler
creatures:
  - 1: Shambler
```



Shamblers are cunning carnivorous plants that resemble heaps of wet, rotting vegetation. Even when standing erect on their stumpy legs, shamblers don't have much in the way of identifiable anatomy; they are tangles of parasitic vines that lash out at prey with their longest creepers, entwined together to deliver powerful blows. Sometimes called "shambling mounds," these ambush predators have a particular fondness for flesh, and are most well known for their ability to hunker down and hide in plain sight. A shambler can draw nutrients from plant matter or soil, but won't do so if it suspects meat might soon wander near, and indeed may lie in wait for days in anticipation of such a meal.

Shamblers are usually solitary creatures. Fierce thunderstorms are among the few events that bring numerous shamblers together. During such gatherings, the plants gather around strange but seemingly sacred earthen mounds in remote jungles and swamps and cavort and caper excitedly, stretching their tendrils toward the sky to hope for-or perhaps to summon-intense lightning strikes. Not only are these strange plants unharmed by even the most powerful electrical strikes, but they seem to become supernaturally empowered by such bursts of raw energy. Shamblers consider being struck by lightning a sign of divine favor, and those shamblers frequently blasted by bolts of electricity become respected elders among their kind. Shambler elders are few and far between and may possess a wide array of abilities; some can cast primal spells, others can empathically call upon the aid of other shamblers in the area, and still others wield awesome powers over electricity.

Other types of shamblers exist, including those composed not of plant matter but fungal growth. These creatures, known as "spore mounds," discharge clouds of toxic spores from their bodies when struck in combat. In semiarid deserts, shambler-like plants called tanglethorns dwell amid sagebrush and rock formations; they resemble bunches of tumbleweeds and cacti and inflict deep, bloody lacerations with their attacks.
