---
title: "Dread Wisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yKeaKSrAkGoIdwQH" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Dread Wisp"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Dread Wisp"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Deception: +16, Intimidation: +16, Stealth: +23"
abilityMods: [-5, 6, 0, 2, 4, 2]
speed:  fly 50 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +14, __Ref__ +21, __Will__ +18"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, void healing; __Immunities__  magic; __Weaknesses__ vitality 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Dread Flickering"
    desc: " (aura,light) 20 feet. A dread wisp, though naturally invisible, glows with a grayish illumination, casting dim light in the aura and making them visible. Living creatures that end their turn in the aura must succeed at a DC 25 Will check saving throw or become [[Conditions/Frightened|Frightened 1]] (or [[Conditions/Frightened|Frightened 2]] on a critical failure).\n\nThose that critically succeed are temporarily immune for 10 minutes."

  - name: "Magic Immunity"
    desc: "  A dread wisp is immune to all spells except [[Spells/Faerie Fire|Faerie Fire]], [[Spells/Force Barrage|Force Barrage]], [[Spells/Quandary|Quandary]], [[Spells/Holy Light|Holy Light]], and spells with the vitality trait."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Draining Touch"
    desc: "+17 (magical, void)\n__Damage__  3d8 + 8 void plus wearying-touch"

  - name: "Feed on Despair"
    desc: "`pf2:1` (concentrate,occult,void) **Frequency** once per round\n\n**Requirement** An enemy within 15 feet of the dread wisp is under a fear effect, [[Conditions/Drained|Drained]], or [[Conditions/Dying|Dying]]\n* * *\n\n**Effect** The dread wisp feeds on the creature's despair. The dread wisp regains 2d8 healing Hit Points and deals 3d8 void damage to the creature (DC 25 Fortitude check save), and if the dread wisp has Gone Dark, their Dread Flickering reignites."

  - name: "Go Dark"
    desc: "`pf2:1` (concentrate) The dread wisp extinguishes their Dread Flickering, becoming [[Conditions/Invisible|Invisible]]. They can end this effect with another use of this action. If the dread wisp uses their draining touch Strike while invisible, the arc of pale energy lets any observer determine their location, making them [[Conditions/Hidden|Hidden]] to all observers only until the dread wisp moves."

  - name: "Shadow Flitter"
    desc: "`pf2:1` (occult,teleportation) The dread wisp teleports to a square they can see within 30 feet that isn't in an area of bright light. The dread wisp can't use again for 1d4 rounds."

  - name: "Wearying Touch"
    desc: "  If the dread wisp critically hits with their draining touch Strike, the target is [[Conditions/Drained|Drained 1]]."
 
```

```encounter-table
name: Dread Wisp
creatures:
  - 1: Dread Wisp
```



Will-o'-wisps native to the Darklands are more ominous and malevolent than those that bob about in the lonely marshes and surfaces of the upper world. These dread wisps instill terror with eerie shifts of light and consume the fear they create, drawing life energy from their victims in the process. While dread wisps can survive anywhere within the Darklands, they prefer moist areas like partially submerged caves, the banks of underground rivers, and towering fungus gardens.

Dread wisps don't glow as brightly as surface will-o'-wisps because even the dimmest light attracts notice underground. Long-lived and hateful creatures, they remember vivid details about their lives, travels, and most delicious prey. Although dread wisps could share extensive lore and unique experiences, they don't, as they find amusement in others' ignorance.
