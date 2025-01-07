---
title: "Meat Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y1jvvZZlM0ane2c6" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/divine
  - pf2e/creature/type/evil
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Meat Guardian"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Meat Guardian"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[divine]]
trait_03: [[evil]]
trait_04: [[golem]]
trait_05: [[mindless]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [4, -2, 3, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +9, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  electricity,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 5 (except adamantine or slashing)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Divine Warden) Divine Destruction|Divine Destruction]]"
    desc: " (divine,void) When the divine warden is reduced to 0 HP, it erupts with divine energy in a 30-foot emanation, dealing 5d6 void damage. Each creature in the area must attempt a DC 20 Will check save with the following outcomes.\n* * *\n\n**Critical Success** The creature takes half damage.\n\n**Success** The creature takes full damage.\n\n**Failure** The creature takes full damage and becomes temporarily cursed by the patron deity. The creature becomes [[Conditions/Enfeebled|Enfeebled 1]] and [[Conditions/Stupefied|Stupefied 1]] for 1 day; this is a curse effect that uses the Will save DC as the counteract DC.\n\n**Critical Failure** As failure, except the creature becomes [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Stupefied|Stupefied 2]]."

  - name: "[[Creature Family Ability Glossary/(Divine Warden) Faith Bound|Faith Bound]]"
    desc: " (divine) A divine warden can't attack a creature that openly wears or displays the religious symbol of the divine warden's patron deity unless that creature uses a hostile action against the divine warden first. If the divine warden is intelligent, it can also attack a creature it believes isn't faithful to its deity or who wears the religious symbol as a ruse (typically after succeeding at a Perception check to [[Actions/Sense Motive|Sense Motive]])."

  - name: "Golem Antimagic"
    desc: "  harmed by fire (4d6, 1d8 from areas or persistent damage); healed by electricity (area 1d6 HP); slowed by cold\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Stench"
    desc: " (aura,disease,olfactory) 40 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 19 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as it's sickened on a critical failure). While within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

  - name: "Vulnerable to Gentle Repose"
    desc: "  Casting a [[Spells/Peaceful Rest|Peaceful Rest]] spell on a meat guardian causes it to grow stiff. The golem attempts a DC 20 Fortitude check save. It's unaffected on a critical success, [[Conditions/Slowed|Slowed 1]] for 1d4 rounds on a success, and on a failure is [[Conditions/Immobilized|Immobilized]] and slowed for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (magical)\n__Damage__  2d10 + 4 piercing plus filth-fever"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, magical)\n__Damage__  2d6 + 4 slashing plus filth-fever"

  - name: "**Melee** `pf2:1` Scythe"
    desc: "+15 (deadly d10, magical, trip)\n__Damage__  2d10 + 4 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 20, attack +12\n__Cantrips__  __(3rd)__ _[[Spells/Divine Lance|Divine Lance]]_"

  - name: "Divine Focus Spells"
    desc: "1 Focus Point, DC 20, attack +12; __3rd __  _[[Spells/Overstuff|Overstuff]]_, _[[Spells/Touch of Undeath|Touch of Undeath]]_"

  - name: "[[Creature Family Ability Glossary/(Divine Warden) Faithful Weapon|Faithful Weapon]]"
    desc: "  Scythe\n* * *\n\nA divine warden always wields its patron deity's favored weapon. If the weapon is a ranged weapon, the divine warden automatically generates new ammunition with each attack. For a divine warden of 4th level or higher, the deity's favored weapon gains the effects of a _[[Equipment/Striking|Striking]]_ rune while the divine warden wields it; at 12th level, these effects are of a _[[Equipment/Striking (Greater)|Greater Striking]]_ rune, and at 19th level, they're instead of a _[[Equipment/Striking (Major)|Major Striking]]_ rune."

  - name: "Filth Fever"
    desc: " (disease) The [[Conditions/Sickened|Sickened]] and [[Conditions/Unconscious|Unconscious]] conditions from filth fever can't end or be reduced until the disease is cured.\n\n**Saving Throw** DC 20 Fortitude check\n\n**Stage 1** carrier with no ill effect (1d4 hours)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Sickened|Sickened 1]] and [[Conditions/Slowed|Slowed 1]] as long as it remains sickened (1 day)\n\n**Stage 4** unconscious (1 day)\n\n**Stage 5** dead"

  - name: "[[Creature Family Ability Glossary/(Divine Warden) Instrument of Faith|Instrument of Faith]]"
    desc: "  The divine warden is a beacon for its deity's faith. A cleric of the divine warden's patron deity can channel a [[Spells/Heal|Heal]] spell through a divine warden they can see within 60 feet. The cleric determines any targets or area for the spell as if they were standing in the divine warden's space."
 
```

```encounter-table
name: Meat Guardian
creatures:
  - 1: Meat Guardian
```


Divine warden carrion golem


