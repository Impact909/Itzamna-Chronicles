---
title: "Silver Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ntYcQTISJCWtdPI5" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2e/creature/type/good
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Silver Dragon (Ancient, Spellcaster)"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Silver Dragon (Ancient, Spellcaster)"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[cold]]
trait_02: [[dragon]]
trait_03: [[good]]
trait_04: [[lawful]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +38, Diplomacy: +34, Intimidation: +37, Medicine: +33, Religion: +32, Society: +30"
abilityMods: [9, 4, 5, 5, 5, 7]
speed: 60 feet,  fly 180 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +34, __Ref__ +31, __Will__ +34; +1 status to all saves vs. magic"
hp: 410
health:
  - name: ""
  - name: HP
    desc: "410; __Immunities__  cold,  paralyzed,  sleep; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

  - name: "Cloud Walk"
    desc: "  The silver dragon can tread on clouds or fog as though on solid ground."

  - name: "Fog Vision"
    desc: "  The silver dragon ignores the [[Conditions/Concealed|Concealed]] condition from fog and clouds."

abilities_mid:
  - name: ""
  - name: "Cold Aura"
    desc: " (aura,cold) 15 feet. 3d6 cold damage\n\nThe silver dragon can turn this aura on or off as a single action, which has the concentrate trait, and can choose not to affect allies within the aura."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 40 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Reflect Spell"
    desc: "`pf2:r`  **Trigger** The silver dragon critically succeeds at a saving throw against a spell, or a caster trying to target the dragon critically fails their attack roll.\n* * *\n\n**Effect** The spell is reflected back upon the caster, with the effect of [[Spells/Spell Turning|Spell Turning]]."

  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** The silver dragon is targeted with an attack\n* * *\n\n**Effect** The dragon raises its wing, gaining a +2 circumstance bonus to AC against the triggering attack. If the dragon is flying, it descends 10 feet after the attack is complete."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (cold, magical, reach 20 feet)\n__Damage__  4d10 + 17 piercing 4d6 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+37 (agile, magical, reach 15 feet)\n__Damage__  4d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (magical, reach 25 feet)\n__Damage__  3d10 + 15 bludgeoning"

  - name: "Divine Prepared Spells"
    desc: "DC 40, attack +36; __8th __  _[[Spells/Pinpoint|Discern Location]]_; __7th __  _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_; __6th __  _[[Spells/Repulsion|Repulsion]]_, _[[Spells/Truesight|True Seeing]]_, _[[Spells/Zealous Conviction|Zealous Conviction]]_; __5th __  _[[Spells/Banishment|Banishment]]_, _[[Spells/Sending|Sending]]_; __4th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Read Omens|Read Omens]]_; __3rd __  _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Augury|Augury]]_, _[[Spells/Calm|Calm Emotions]]_, _[[Spells/Restoration|Restoration]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __  _[[Spells/Alarm|Alarm]]_, _[[Spells/Bless|Bless]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Protection|Protection]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Arcane Innate Spells"
    desc: "DC 40, attack +32; __1st __  _[[Spells/Detect Alignment|Detect Alignment (Evil Only)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,cold,incapacitation) The silver dragon breathes in one of two ways.\n\nThe dragon can't use Breath Weapon again for 1d4 rounds.\n\n*   **Frost** The dragon breathes a cloud of frost in a 50-foot cone that deals 20d6 cold damage (DC 42 Reflex check save).\n*   **Paralyzing Gas** The dragon breathes a blast of paralyzing gas. Each creature within a 50-foot cone must succeed at a DC 42 Fortitude check save or be [[Conditions/Paralyzed|Paralyzed]] for 1 round (or 3 rounds on a critical failure)."
 
```

```encounter-table
name: Silver Dragon (Ancient, Spellcaster)
creatures:
  - 1: Silver Dragon (Ancient, Spellcaster)
```



Silver dragons are among the most chivalrous of all dragonkind; they wield frost and cold as weapons, can walk on clouds, and dwell high upon snowy mountain peaks or deep in steep, misty valleys. Although they typically make their lairs among the highlands, the pursuit of justice leads silver dragons to travel far and wide-often into the very heart of realms overrun by evil. These exemplars of righteousness are ceaseless in their determination to help the weak, spread honor, and stamp out evil.

Silver dragons are sleek and sinuous. Their hides resemble nothing so much as a suit of gleaming armor, lending further credence to the popular myth that silver dragons are the paladins of dragonkind. The zeal with which they seek out, confront, and defeat evil is unsurpassed even among their metallic cousins, and they adhere to strict codes of honor usually passed down from parent to hatchling. On occasion, they instead learn these codes from trusted mentors, usually other silver dragons or gold dragons. As they age, they become even more dedicated to their codes, often adding new and even more restrictive clauses to the systems that guide their behavior.

Silver dragons are incredibly altruistic and regularly consort with the citizens of goodly societies, of which they consider themselves protectors and guides. In addition to responding to evil threats, silver dragons work to prevent evil from taking root in the first place, and they ensure mortals under their care are well fed, educated, and treated with dignity. Although silver dragons can seem overzealous or even eager to join the fight against evil, they know that the best way to rid the world of corruption is to stamp out strife and disillusionment at their source, not to passively sit back and watch it grow into an unsolvable problem. Silver dragons can be vindictive, but they can also be forgiving; for evildoers who seek to atone for their sins and turn over a new leaf, the support of a silver dragon is both unwavering and invaluable.

Many silver dragons are also drawn to religious endeavors, venerating deities such as Iomedae, Sarenrae, and other deities concerned with justice, virtue, and redemption.

* * *

Paragons of virtue, nobility, and grace, metallic dragons are benevolent entities revered as mythic beings akin to gods in both their power and majesty. Few have ever seen a metallic dragon firsthand, but tales of their intervention in mortals' lives-and of their passing-always spread far and wide. Named for the way their scales resemble the shining metals humanoids use in commerce, warfare, and industry, these immense beings are diverse in their interests and abilities, and they don't seem to mind being associated with such mundane materials. After all, to compare a gold dragon to a gold coin is like comparing an ocean to a glass of water-though they may seem similar at first glance, the raw power, breadth, and grandeur of one simply overwhelms the other.

In addition to metallic dragons and their chromatic counterparts, other types of dragons roam the world and the rest of the multiverse. In the legendary lands of Tian Xia on the other side of the globe are the imperial dragons, serpentine beings who protect the cosmic balance and defend their ancient homeland. Outside the Material Plane, primal dragons such as the domineering brine dragon and reclusive cloud dragon shape the nature and goings-on of the Elemental Planes. Countless other types of dragons are sure to exist, including dragons on far-flung planes of existence and, it is rumored, primeval dragons who soar between the stars.
