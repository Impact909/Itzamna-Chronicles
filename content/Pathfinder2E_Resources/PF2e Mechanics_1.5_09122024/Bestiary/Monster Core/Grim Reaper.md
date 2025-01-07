---
title: "Grim Reaper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.s7dgvnAj6dwaX47a" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/21
  - remaster
statblock: inline
name: "Grim Reaper"
level: 21
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Grim Reaper"
level: "Creature 21"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 41
perception:
  - name: "Perception"
    desc: "+41; Darkvision, Truesight, See the Unseen"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +43, Athletics: +38, Deception: +40, Intimidation: +43, Religion: +39, Society: +36, Stealth: +43"
abilityMods: [8, 10, 8, 5, 7, 8]
speed: 50 feet,  fly 75 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +37, __Ref__ +41, __Will__ +38; +1 status to all saves vs. magic"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320, death&#x27;s grace, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed; __Resistances__ all damage 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scythe|Scythe]]"
  - name: "Death's Grace"
    desc: "  The Grim Reaper can choose whether or not it counts as undead for effects that affect undead differently. Even if it does not count as undead, the Grim Reaper still never counts as a living creature."

  - name: "Status Sight"
    desc: "  The Grim Reaper automatically knows the Hit Points, conditions, afflictions, and emotions of all creatures it can see."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Misfortune"
    desc: " (aura,divine,misfortune) 20 feet.\n\nLiving creatures in the aura must roll twice on all d20 rolls and use the lower result.\n\n[[Bestiary Effects/Effect_ Aura of Misfortune|Effect: Aura of Misfortune]]"

  - name: "Lurking Death"
    desc: "`pf2:r` (divine,teleportation) **Trigger** A creature within 100 feet makes a ranged attack or uses an action that has the concentrate, manipulate, or move trait\n* * *\n\n**Effect** The Grim Reaper teleports to a square adjacent to the triggering creature and makes a melee Strike against it. If the Strike hits, the Grim Reaper disrupts the triggering action."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  The Grim Reaper can choose whether or not it takes vitality damage.\n* * *\n\nA creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Keen Scythe"
    desc: "+40 (agile, deadly 3d10, magical, reach 10 feet, trip)\n__Damage__  4d10 + 23 slashing plus death-strike,energy-drain"

  - name: "Divine Innate Spells"
    desc: "DC 47, attack +37; __10th __  _[[Spells/Execute|Execute (x4)]]_; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_ __(3rd)__ _[[Spells/Haste|Haste]]_ __(2nd)__ _[[Spells/See the Unseen|See the Unseen]]_"

  - name: "Death Strike"
    desc: " (death) A creature critically hit by any of the grim reaper's attacks or that critically fails against any of its spells must succeed at a DC 47 Fortitude check save or die."

  - name: "Energy Drain"
    desc: "  When the Grim Reaper hits and deals damage with its scythe, it regains 20 healing Hit Points, and the target must succeed at a DC 43 Fortitude check save or become [[Conditions/Doomed|Doomed 1]]. If the target is already doomed, the doomed value increases by 1 (to a maximum of [[Conditions/Doomed|Doomed 3]])."

  - name: "Final Death"
    desc: "  A creature killed by the Grim Reaper can't be brought back to life by any means short of divine intervention."

  - name: "Infuse Weapon"
    desc: " (divine) Any scythe gains the agile trait, can't be disarmed, and becomes a _+3 major striking keen scythe_ while the Grim Reaper wields it.\n\nIf the Grim Reaper Strikes a creature with a weakness to any specific type of damage, the scythe's damage counts as that type of damage, in addition to slashing."
 
```

```encounter-table
name: Grim Reaper
creatures:
  - 1: Grim Reaper
```



The Grim Reaper is the unflinching personification of death. Silent as the grave and as inevitable as time itself, this legendary being hunts down and finishes creatures that have evaded death for far too long. Sometimes the Grim Reaper comes without warning, while at others it comes to finish the work that other creatures could not. The Grim Reaper serves no god, fiend, or aeon. It is both despised and feared by psychopomps and celestials, but few-if any-dare to stand in its way. Like some eternal plague, it kills those who try to cure the multiverse of its presence. It stands alone and holds only its own council, and the pleading and reasoning of mortals and immortals alike fall on deaf ears once the Grim Reaper closes on its quarry. Its own reasoning is silent to mortal ears and inscrutable to the mortal mind, but no matter the reason, the result is unyielding and final.

While some legends hold that the Grim Reaper appears before everyone as they die, the truth is quite a bit more disturbing. Such vigils in fact lie within the providence of the psychopomps, a race of immortals charged with the protection and guidance of mortal souls through the afterlife. The Grim Reaper has little interest in protecting souls or guiding them. It is instead compelled by sinister agendas arising within the nighted realm of Abaddon, where the Horsemen of the Apocalypse rule. Indeed there are many similarities in shape and form between the Grim Reaper and Charon, the Horseman of Death, but no recorded instance exists of these two powerful entities working together. Instead, the Grim Reaper serves as something of a manifestation of Abaddon itself, and in this regard is believed by some to be an incarnation of the mysterious First Horseman. When the Grim Reaper comes to a world, it does so not as an angel of mercy, but as a relentless harvester of life. Those who fall to the Grim Reaper were not destined to die as much as they were selected, hunted, and murdered.

Perhaps the most frightening legends surrounding the Grim Reaper concern its nature as a singular entity, for some believe that more than one grim reaper exists in the Great Beyond. These whispers tell of a cabal of at least nine of these creatures that stalk reality, culling the living as inexplicable servants of true entropy. According to the teaching of some death cults, the final goal of the Grim Reaper is to end the entire cycle of life and death and serve as a silent lord of an empty universe.
