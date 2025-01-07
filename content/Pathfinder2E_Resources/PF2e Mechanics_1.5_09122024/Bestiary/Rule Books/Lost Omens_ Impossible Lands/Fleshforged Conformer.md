---
title: "Fleshforged Conformer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w1YIAzukOrVQGWXx" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Fleshforged Conformer"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Impossible Lands"
name: "Fleshforged Conformer"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[chaotic]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Aklo, Common; two other languages"
skills:
  - name: "Skills"
    desc: "Arcana: +15, Deception: +17, Medicine: +17, Occultism: +15, Society: +15, Stealth: +18, Fleshwarp Lore: +170"
abilityMods: [0, 6, 3, 3, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens: Impossible Lands_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +17, __Ref__ +18, __Will__ +13"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145, regeneration 10 (deactivated by cold iron); __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fanged-Maw Finger"
    desc: "+20 (agile, finesse)\n__Damage__  2d10 + 3 piercing 1d8 bleed"

  - name: "Occult Innate Spells"
    desc: "DC 25, attack +17; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Charitable Urge|Charitable Urge]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Conformance"
    desc: "`pf2:1` (concentrate,occult,polymorph) The conformer contorts and reshapes their body into a desired form. The conformer takes on the specific appearance of any Small, Medium, or Large humanoid or animal that they've observed and whose appearance they remember. This doesn't change the conformer's Speed or their attack and damage bonus with their Strikes, but might change the damage type their Strikes deal."

  - name: "Surgical Detachment"
    desc: "`pf2:1` (concentrate,manipulate,morph,occult) The conformer detaches part of their body to serve them as an autonomous organism. For the next 24 hours, the conformer gains the loyal service of a fleshforged [[Lost Omens: Impossible Lands/Skinskitter|Skinskitter]]. As long as they remain within 1 mile of each other, the conformer can use the Surgical Detachment action again to empathically direct the actions of their skinskitter servant as well as perceive through its senses. Due to how taxing this process is, the conformer can have only one skinskitter servant at a time."

  - name: "Tissue Siphon"
    desc: "`pf2:1` (manipulate,occult) **Requirements** The conformer is within reach of an [[Conditions/Unconscious|Unconscious]] or willing creature, or a creature taking persistent bleed damage\n* * *\n\n**Effect** The conformer touches and absorbs some of the creature's flesh. The target must attempt a DC 26 Fortitude check save; on a failure, they become [[Conditions/Drained|Drained 1]] and take damage from their persistent bleed damage, even though it isn't the end of their turn."

  - name: "Wear Flesh"
    desc: "`pf2:1` (occult) **Requirements** The conformer has used Tissue Siphon to absorb flesh within the last hour\n* * *\n\n**Effect** The conformer expends the flesh they've absorbed to transform their body, reproducing the effects of one of the following spells: [[Spells/Adapt Self|Adapt Self]], [[Spells/Enlarge|Enlarge]], [[Spells/Shifting Form|Shifting Form]], [[Spells/Tentacular Limbs|Tentacular Limbs]], or [[Spells/Unusual Anatomy|Unusual Anatomy]]. The Wear Flesh action gains the traits of the spell it's reproducing, and the conformer can Sustain a Spell on these effects."
 
```

```encounter-table
name: Fleshforged Conformer
creatures:
  - 1: Fleshforged Conformer
```



Shapeshifting fleshforged conformers have adapted to survive Ecanus's high-magic, population-dense sprawl. Resembling blocky humanoid skeletons splotched in uneven layers with cartilage and muscle, conformers are capable of attaching and detaching flesh from their bodies, often sending autonomous gobbets of fat and ligament to observe living creatures and harvest biological material.

Fleshforged conformers use their resources to augment and change their bodies, which helps them infiltrate Nexian society to better understand the arcane principles and occult secrets behind their creation. Some assume the guises of humans and animals to lead quiet, settled lives in Nex, but most are discovered and summarily exterminated as defects and threats to public safety.
