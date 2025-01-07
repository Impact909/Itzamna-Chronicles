---
title: "Bright Walker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2sQ6lCtFNw2C4AGL" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Bright Walker"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Bright Walker"
level: "Creature 9"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Greater Darkvision"
languages: "Caligni"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Intimidation: +18, Stealth: +19"
abilityMods: [-5, 6, 0, 0, 4, 3]
speed:  fly 25 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +15, __Ref__ +21, __Will__ +19"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

abilities_mid:
  - name: ""
  - name: "Bright Release"
    desc: " (fire,light) When a bright walker is reduced to 0 Hit Points, they flash out in a burst of light, obtaining the blazing end they were denied at death. This blaze deals 10d6 fire damage (DC 25 Reflex check save) to creatures within 20 feet.\n\nCreatures who fail this save are also [[Conditions/Dazzled|Dazzled]] for 1 minute ([[Conditions/Blinded|Blinded]] for 1 minute on a critical failure)."

  - name: "Light Aura"
    desc: " (aura,divine,light) 30 feet. The bright walker sheds bright light. Any creature that starts its turn in the aura must attempt at a DC 24 Fortitude check save.\n* * *\n\n**Critical Success** The creature is temporarily immune for 24 hours.\n\n**Success** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Failure** The creature is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Critical Failure** The creature is blinded for 1 hour."

  - name: "Suppress Aura"
    desc: "`pf2:1` (concentrate) The bright walker suppresses their light aura for 1 round, reducing it to a faint, ghostly glow of dim light."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Radiant Touch"
    desc: "+21 (agile, finesse, fire, light, magical)\n__Damage__  2d8 + 11 fire"

  - name: "**Ranged** `pf2:1` Radiant Ray"
    desc: "+21 (fire, light, magical, range increment 60 feet)\n__Damage__  2d6 + 11 fire"

  - name: "Landbound"
    desc: "  A bright walker can't fly higher than 1 foot above the ground. If they fly higher than this distance, they fall but don't take any damage from falling."

  - name: "Light Flare"
    desc: "`pf2:2` (divine,fire,light) **Requirement** The bright walker's Light Aura is suppressed\n* * *\n\n**Effect** The bright walker reignites their Light Aura with a burst of brightness that deals 5d6 fire damage (DC 25 Reflex check save) to creatures within a 20-foot burst.\n\nCreatures who are [[Conditions/Dazzled|Dazzled]] or with [[Bestiary Ability Glossary/Light Blindness|Light Blindness]] find this flare particularly painful; such a creature's save result is one degree of success worse than the result it rolled."

  - name: "Shadow Jump"
    desc: "`pf2:1` (divine,teleportation) **Requirement** The bright walker's Light Aura is suppressed\n* * *\n\n**Effect** The bright walker teleports to a square it can see within 60 feet that is not in an area of bright light. The bright walker can't use again for 1d4 rounds."
 
```

```encounter-table
name: Bright Walker
creatures:
  - 1: Bright Walker
```



Those who encounter calignis quickly learn that their deaths involve burning out instead of bleeding out. At times, this dramatic immolation is denied to a caligni, so they arise as a bright walker. Tied to caligni society, these creatures don't understand that their glow damages and repels living calignis. Despite their name, these undead don't walk; they instead float a few inches above the ground.
