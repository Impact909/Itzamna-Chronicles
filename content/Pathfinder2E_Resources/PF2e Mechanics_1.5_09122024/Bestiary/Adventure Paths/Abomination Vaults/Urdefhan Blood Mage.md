---
title: "Urdefhan Blood Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sGgS6ShBTZZCuKsC" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/urdefhan
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Urdefhan Blood Mage"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Urdefhan Blood Mage"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[urdefhan]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Greater Darkvision"
languages: "Aklo, Daemonic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Arcana: +16, Athletics: +16, Intimidation: +16, Occultism: +18, Religion: +16"
abilityMods: [4, 2, 4, 6, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +18, __Ref__ +14, __Will__ +17"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140, void healing; __Immunities__  death effects,  disease,  fear effects; __Weaknesses__ vitality 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Kukri|+1 Striking Kukri]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Necrotic Decay"
    desc: " (divine,void) When an urdefhan dies, its invisible flesh quickly rots away and sublimates into a foul-smelling gas that fills a 5-foot emanation around the body.\n\nThis gas deals 8d6 void damage to creatures in this area as their flesh curdles and rots as well (DC 24 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Kukri"
    desc: "+16 (agile, trip)\n__Damage__  2d6 + 8 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 ()\n__Damage__  2d6 + 8 piercing plus wicked-bite"

  - name: "Occult Spontaneous Spells"
    desc: "DC 26, attack +18; __4th __ (4 slots) _[[Spells/Call The Blood|Call The Blood]]_, _[[Spells/Confusion|Confusion]]_, _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_; __3rd __ (4 slots) _[[Spells/Haste|Haste]]_, _[[Spells/Levitate|Levitate]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __ (4 slots) _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Ghoulish Cravings|Ghoulish Cravings]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Stupefy|Touch of Idiocy]]_; __1st __ (4 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(4th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __3rd __  _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Death Knell|Death Knell]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall (At Will) (Self Only)]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_"

  - name: "Blood Offering"
    desc: "`pf2:1` (occult,spellshape) **Frequency** once per round\n* * *\n\n**Effect** The blood mage cuts themself and takes 8 slashing damage. If the blood mage's next action is to Cast a Spell, the action can't be disrupted, and if the spell has a range, the blood mage can increase that spell's range by 30 feet."

  - name: "Wicked Bite"
    desc: "`pf2:1`  **Requirements** The urdefhan damaged a creature with a jaws Strike on its last action\n* * *\n\n**Effect** The urdefhan maintains contact, turning the creature's flesh translucent around the site of the injury. The urdefhan chooses one of two options, each of which requires a fortitude save. If the jaws Strike was a critical hit, the creature suffers both effects, using the same save result for both.\n\n*   **Drain Blood** DC 26 Fortitude check The urdefhan drinks some of the creature's blood. On a failed save, the creature is [[Conditions/Drained|Drained 1]] and the urdefhan regains 10 healing HP (or, on a critical failure, it's [[Conditions/Drained|Drained 2]] and the urdefhan regains 20 healing HP).\n*   **Drain Vitality** (necromancy) DC 26 Fortitude check The urdefhan draws out some of the creature's vital essence. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] for 1 hour on a failed save (or [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour on a critical failure)."
 
```

```encounter-table
name: Urdefhan Blood Mage
creatures:
  - 1: Urdefhan Blood Mage
```



Hardened masters of occult power, urdefhan blood mages trade their blood for magical might. A heavily scarred blood mage is held in esteem by their fellow urdefhans, as it shows they have survived many bargains with eerie occult patrons.

* * *

Translucent-skinned scourges of the Darklands, urdefhans are remorseless killers and foot soldiers of the world's end.
