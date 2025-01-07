---
title: "Sporeborn Myceloid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TlnMjSLbYk2GHErk" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2e/creature/type/sporeborn
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Sporeborn Myceloid"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Sporeborn Myceloid"
level: "Creature 4"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[fungus]]
trait_02: [[mindless]]
trait_03: [[sporeborn]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +11, Survival: +10"
abilityMods: [4, 3, 4, -5, 2, -5]
speed: 20 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +9, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Immunities__  mental; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Rancid Spore Pods"
    desc: " (disease,fungus) The sporeborn is covered in spore pods that rupture when it takes any piercing damage or a critical hit. In either case, adjacent creatures are hit with spores, causing them to become [[Conditions/Sickened|Sickened 1]] unless they succeed at a Fortitude save.\n\nDC 18 Fortitude check save."

  - name: "Spore Pop"
    desc: "  If a sporeborn myceloid is reduced to 0 HP by a critical hit, it pops, forcing it to immediately Emit Spores, even if it has already used the ability that day."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, finesse)\n__Damage__  2d6 + 4 bludgeoning plus purple-pox"

  - name: "Emit Spores"
    desc: "`pf2:1`  **Frequency** once per day\n* * *\n\n**Effect** The sporeborn myceloid expels spores in a 10-foot burst centered on a corner of its own space. This cloud lasts until the start of the sporeborn myceloid's next turn. Each creature that is in the cloud or enters it is exposed to purple pox."

  - name: "Purple Pox"
    desc: " (disease) Myceloids are immune\n\n**Saving Throw** DC 22 Fortitude check;\n\n**Onset** 1 minute\n\n**Stage 1** 2d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 day)\n\n**Stage 2** 6d6 poison damage, [[Conditions/Stupefied|Stupefied 3]], and the creature is compelled to seek out the nearest myceloid colony—this compulsion is a mental and emotion effect (1 day)\n\n**Stage 3** The creature dies. Over 24 hours, its corpse becomes bloated and bursts, releasing a new, fully grown myceloid"

  - name: "Spore Domination"
    desc: "`pf2:2` (emotion,incapacitation,mental,primal) The sporeborn myceloid targets one creature affected by purple pox within 60 feet. That creature must attempt a DC 24 Will check save. It is then temporarily immune to spore domination for 10 minutes.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** Until the end of its next turn, the target is helpful to sporeborn myceloids and can't take hostile actions against them.\n\n**Failure** As success, but for 1 minute.\n\n**Critical Failure** As success, but until the purple pox is cured."
 
```

```encounter-table
name: Sporeborn Myceloid
creatures:
  - 1: Sporeborn Myceloid
```



While most sporeborn are created from the flesh of vertebrates or creatures with exoskeletons, fungal and plant creatures serve as a fine host for a sporeborn's parasitic spores. In these cases, the sporeborn mycelial network burrows through the corpse, replacing the original hyphae in fungal creatures and the xylem and pith in plants. This allows the sporeborn to puppet the creature, much as it does in mammals by replacing the tendons with its own rugged mycelium. Fungus and plant hosts are more likely to develop the potent poison sporeborn ability to enhance the hosts' natural abilities.

* * *

When a mindless guardian is needed, but the ethical bounds of creating undead are too uncouth, ritual casters may turn to a more fungal solution by creating a mycoguardian. Using valuable parasitic fungal spores, a ritualist may seed the corpse of a creature and encourage them to grow, sending mycelium tendrils throughout the body. The tendrils bond to mobile tissue such as bones, while replacing tendons with reinforced mycelium. This ritual magically replicates the yellow musk creepers' ability to spread throughout a dead organism then mobilize its body. But rather than a completely mindless fungal carrier, the ritualist has some control over the infested creature's behavior.

The magic of the ritual includes basic instructions and rules that guide the new fungal mycoguardian (in this case, a sporeborn). Simple instructions like "guard this room" or "slay all of the tiny creatures in this basement" should work well enough, but complex commands such as "deliver this letter to the Harbormaster of Caliphas" are doomed to failure.

## Fungel Ristualists

While mycoguardians are rare, several different types of primal spellcasters might create a mycoguardian. Druids might turn the bodies of a poacher's victim against the poacher, seeking to avenge the wrongful death and rebalance the scales of life. Leshy spellcasters create mycoguardians to protect their hidden communities and sacred groves. The fey of Northern Fangwood transform fallen or rotted trees into crustoreal mycoguardians, massive arboreal-looking creatures covered in parasitic lichen. These lumbering sentinels patrol their borders, crushing all non-fey who dare approach. There are rumors of crustoreals being imbued with void energy from the Gravelands and going berserk.

## Creating Mycoguardians

To create a mycoguardian, such as a sporeborn, a ritualist can perform a ritual similar to create undead (Pathfinder Core Rulebook 411) called create mycoguardian, but providing valuable parasitic fungal spores instead of black onyx. This ritual uses Fungus Lore (trained) or Nature (expert) for both the Primary Check and Secondary Checks, and lacks the Evil trait.

## Different Mycoguardians

In addition to the sporeborn presented here, there are many versions of the create mycoguardian ritual for making mycoguardians other than sporeborn, such as for aquatic chytridions and so on. Some forms of mycoguardians, such as mycelial mindbores, come to be using their own unique methods and can't be created with a version of create mycoguardian.
