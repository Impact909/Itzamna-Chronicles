---
title: "Doprillu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.o4Xe10UIEWUkm5eI" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Doprillu"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Doprillu"
level: "Creature 14"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, See the Unseen"
languages: "Aklo, Common, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Athletics: +30, Intimidation: +22, Stealth: +24"
abilityMods: [8, 6, 7, 1, 4, 2]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +28, __Will__ +24; +2 status to all saves vs. fear"
hp: 260
health:
  - name: ""
  - name: HP
    desc: "260, regeneration 20 (deactivated by cold); __Immunities__  enfeebled,  slowed; __Resistances__ fire 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Deflect Arrow"
    desc: "`pf2:r`  **Trigger** The doprillu is the target of a physical ranged attack\n\n**Requirements** The doprillu is aware of the attack, isn't [[Conditions/Off-Guard|Off-Guard]] against it, and has a hand free\n* * *\n\n**Effect** The doprillu gains a +4 circumstance bonus to its AC against the triggering attack."

  - name: "Mask of Power"
    desc: "  A doprillu's unique wooden mask is the source of its power.\n\nA doprillu deprived of its mask loses its regeneration and its immunity to Enfeebled and [[Conditions/Slowed|Slowed]], and it immediately becomes [[Conditions/Enfeebled|Enfeebled 1]]. The Enfeebled value increases by 1 at the start of each of the doprillu's turns, to a maximum of Enfeebled 4. If the mask is put back on, the doprillu immediately regains its abilities and loses the Enfeebled condition.\n\nA creature can pull off the mask with a successful Athletics check to [[Actions/Force Open|Force Open]]."

  - name: "Volcanic Veins"
    desc: " (fire) Fiery magma runs through the doprillu's veins. A creature that starts its turn [[Conditions/Grabbed|Grabbed]] by the doprillu takes 7d6 fire damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+30 (agile, magical)\n__Damage__  3d8 + 16 bludgeoning plus improved-grab 2d6 fire plus improved-grab"

  - name: "**Melee** `pf2:1` Body Strike"
    desc: "+30 (magical, reach 10 feet)\n__Damage__  3d8 + 16 bludgeoning"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +18\n__Constant__  __(6th)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Whirlwind Throw"
    desc: "`pf2:2`  **Requirements** The doprillu has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The doprillu whirls the grabbed creature about, making a Body Strike against each creature in reach. After that Strike, the doprillu can hurl the grabbed creature up to 50 feet as a ranged Strike. This Strike has the same attack modifier and damage as Body Strike, but has the thrown 20 feet weapon trait."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Doprillu
creatures:
  - 1: Doprillu
```



The aberrations known as doprillus are hulks with banded muscles who wear ornate masks at all times that fill their wearers with magical strength and fighting spirit. Doprillus love to battle, especially by grappling, and are eager to start brawls. On neutral ground, a doprillu offers to duel the strongest-looking opponent, but when a doprillu's home turf is invaded, no rules apply to the confrontation. As befits the superheated blood that fuels them, doprillus make their homes in warm locations: hot jungles, sunny deserts, and underground caverns near sulfur vents.