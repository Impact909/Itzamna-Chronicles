---
title: "Deep End Sarglagon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UrRiPMnR9alYaMUT" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Deep End Sarglagon"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Deep End Sarglagon"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[devil]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[lawful]]
trait_06: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Greater Darkvision"
languages: "Diabolic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +14, Athletics: +18, Deception: +15, Diplomacy: +15, Intimidation: +17, Stealth: +15"
abilityMods: [6, 3, 4, 2, 4, 3]
speed: 25 feet,  fly 25 feet,  swim 30 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +13, __Will__ +16; +1 status to all saves vs. magic"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  fire; __Weaknesses__ holy 5; __Resistances__ physical 5 (except silver), poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Fragment of Urevian's Pendant"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Heavy Aura"
    desc: " (aura,divine,incapacitation) 10 feet. A creature that enters the heavy aura must attempt a DC 23 Will check save. It is then temporarily immune for 10 minutes.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Encumbered|Encumbered]] while it remains in the area. If the creature is already encumbered, it is [[Conditions/Immobilized|Immobilized]] while it remains within the aura.\n\n**Critical Failure** As failure, but the effect persists for 3 rounds after leaving the aura."

  - name: "Stygian Guardian"
    desc: "`pf2:r`  **Trigger** A creature or object within the sarglagon's reach is targeted by an attack\n* * *\n\n**Effect** The sarglagon interposes themself, giving the creature or object [[Other Effects/Effect_ Cover|Standard Cover]] against the attack (+2 circumstance bonus to AC), or [[Other Effects/Effect_ Cover|Greater Cover]] (+4 circumstance bonus to AC) if the sarglagon was already granting it lesser cover."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+20 (magical, unholy)\n__Damage__  2d12 + 9 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Tentacle Arm"
    desc: "+20 (agile, magical, unholy)\n__Damage__  2d8 + 9 bludgeoning plus sarglagon-venom 1d6 spirit plus sarglagon-venom"

  - name: "Divine Innate Spells"
    desc: "DC 23, attack +18; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_\n__Constant__  __(2nd)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Drown"
    desc: "`pf2:2` (divine,incapacitation) The sarglagon conjures murky water to fill the lungs of a creature that can't breathe water within 30 feet. The target must attempt a DC 26 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target coughs up water and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The target is holding its breath. The only action it can take is to attempt a Fortitude save against Drown to expel the water, which is a single action.\n\n**Critical Failure** The target falls [[Conditions/Unconscious|Unconscious]] and begins suffocating. If the target succeeds at its Fortitude save while suffocating, it coughs up the water and can breathe again."

  - name: "Sarglagon Venom"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1**2d6 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2**3d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)"
 
```

```encounter-table
name: Deep End Sarglagon
creatures:
  - 1: Deep End Sarglagon
```



Sarglagons dwell in Hell's myriad waterways, lakes, and oceans. They serve as guardians of the Academy of Lies-the repository of secrets in Stygia, the fifth layer of Hell. Sarglagons breathe water and air with equal ease, and can move through water, land, and even air with uncanny swiftness. Few fiends travel the waterways of the multiverse, but where a river crosses the planes, odds are sarglagons have traveled it to further their infernal machinations. The only body of water they avoid is the River Styx, as the fiends have yet to develop any defense against that waterway's memory-sapping qualities. Mortal spellcasters sometimes bind sarglagons as guardians of precious secrets or treasures, particularly in aquatic areas. Most strangely, sarglagons sometimes act as unnerving caretakers to mortals who have no idea what they did to earn their unwanted protectors' attention. The constant uninvited vigilance of these devils is often disturbing and stifling to their wards.

* * *

Each type of devil plays a particular role in Hell's bureaucracies and hierarchies, though some have far more specialized functions than others.
