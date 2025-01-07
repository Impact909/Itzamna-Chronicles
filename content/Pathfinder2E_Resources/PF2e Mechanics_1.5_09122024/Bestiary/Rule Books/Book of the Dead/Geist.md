---
title: "Geist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oJidQiq1OiowHlcN" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Geist"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Geist"
level: "Creature 9"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Necril; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Deception: +18, Intimidation: +20, Religion: +17, Stealth: +20"
abilityMods: [-5, 5, 0, 2, 2, 5]
speed:  fly 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +20, __Will__ +17"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Power of the Haunt"
    desc: "  If a geist is within 100 feet of a haunt that isn't disabled or destroyed, they gain a +2 status bonus to AC and saving throws and deal an additional 1d6 void damage with bite Strikes. A creature that succeeds at a DC 20 Perception check check to Seek or Recall Knowledge about the geist sees that the tendrils from the geist's cloak grow thicker and more agitated the closer it gets to the haunt."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+20 (agile, magical)\n__Damage__  1d10 + 11 piercing"

  - name: "Terrifying Laugh"
    desc: "`pf2:1` (divine,emotion,fear,mental) **Frequency** once per minute\n* * *\n\n**Effect** The geist unleashes soul-piercing laughter in a 20-foot emanation, lasting until the beginning of their next turn. Any creature in the area or entering it must succeed at a DC 26 Will check save or be overcome with panicked laughter, becoming [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). A creature attempts only one save per Terrifying Laugh, and a creature that succeeds on its saving throw is temporarily immune for 24 hours."

  - name: "Wrath of the Haunt"
    desc: "`pf2:2` (divine) **Frequency** once per round\n\n**Requirements** The geist is within 100 feet of an active haunt\n* * *\n\n**Effect** The haunt feeds necromantic power into the geist, becoming inactive until the end of the geist's next turn and deactivating the power of the haunt aura until the haunt becomes active again. The edges of the geist's cloak transform into whip-like tendrils that lash out at nearby creatures. Any living creature within 10 feet of the geist takes 4d10 slashing damage plus 4d6 void damage (DC 28 Reflex check save)."
 
```

```encounter-table
name: Geist
creatures:
  - 1: Geist
```



A geist is an ever-shifting mass of black sack cloth, teeth, and mouths, folding in and out of itself and cackling like a thousand frenzied and doomed souls. Created when a haunt kills an evil person, a geist rises from a soul trapped on the plane of their demise, now connected to the dark energy radiating from haunts everywhere. They wander the world, looking for solace and never finding it. In frustration, they turn their malice back onto the living, antagonizing any nearby creatures, hoping to fatally lure their victims into the clutches of a haunt to be turned into another geist and share the torment.

Geists are occasionally mistaken for other incorporeal undead, such as wraiths and ghosts, but their proximity to haunts is one of the surest ways to determine the nature of the undead being encountered.
