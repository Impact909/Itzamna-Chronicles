---
title: "Marid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kqWMfcGXIynY9Yzb" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/genie
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Marid"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Marid"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[elemental]]
trait_03: [[genie]]
trait_04: [[water]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Crafting: +16, Diplomacy: +19, Nature: +18, Performance: +16, Society: +14, Stealth: +18"
abilityMods: [5, 5, 4, 1, 3, 3]
speed: 20 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +21, __Will__ +17"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Resistances__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|+1 Striking Trident]]"
  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Vortex"
    desc: " (aura,water) 40 feet. Water in the aura that is also in the same body of water as the marid is difficult terrain for Swimming creatures. Creatures with the water trait are immune."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Trident"
    desc: "+21 (magical, reach 10 feet)\n__Damage__  2d8 + 11 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, magical, nonlethal, reach 10 feet)\n__Damage__  1d4 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+21 (magical, thrown 20 ft.)\n__Damage__  2d8 + 11 piercing"

  - name: "Arcane Innate Spells"
    desc: "DC 28, attack +20; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (At Will) (to Astral Plane, Elemental Planes, or Material Plane Only)]]_; __5th __  _[[Spells/Control Water|Control Water (At Will)]]_, _[[Spells/Mirage|Hallucinatory Terrain]]_; __4th __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Solid Fog|Solid Fog]]_; __2nd __  _[[Spells/Blur|Blur (At Will)]]_, _[[Spells/Illusory Object|Illusory Object]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(1st)__ _[[Spells/Detect Alignment|Detect Alignment (Good or Evil Only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The marid can take on the appearance of any water elemental or humanoid. This ability doesn't change the marid's Speed or its attack and damage bonuses with its Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Rush of Water"
    desc: "`pf2:2` (arcane,water) The marid releases a jet of water in a 60-foot line, dealing 9d6 bludgeoning damage (DC 28 Reflex check save). A creature that fails its save is also pushed 10 feet (20 feet on a critical failure).\n\nThe marid can't use Rush of Water again for 1d4 rounds."

  - name: "Skewer"
    desc: "`pf2:1`  The marid makes a trident Strike, dealing an extra 2d6 bleed on a hit (4d6 bleed on a critical hit)."
 
```

```encounter-table
name: Marid
creatures:
  - 1: Marid
```



Marids are capricious but powerful genies from the Plane of Water; among geniekind, they are rivaled in power only by the fiery efreet. Marids embody the strength of the ocean's waves and currents, but they also have a gentler side, loving performance and art such as dancing, music, and storytelling.

Marids regard efreet with hostility but rarely encounter them in their native environment. They get along with djinn, jann, and shaitans, although the latter consider marids flighty and annoying, associating only long enough to close trade deals. Marid society has strict rules of hospitality, and many marid cities have a magically sealed foreign quarter where marid shahzadas conduct business with air-breathers.

* * *

A unique type of genie exists for each Elemental Plane, and the bodies of genies are formed out of elemental matter corresponding to their native plane: djinn are formed from wind, clouds, and storms; efreet are fire made flesh; marids are beings of water; and shaitans are composed of metal, gems, and stone. Lastly, the jann are formed out of all four elements, and are the weakest of geniekind.
