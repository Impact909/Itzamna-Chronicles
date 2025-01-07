---
title: "Iazmilor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MvZgeMnoHrr0ICUC" 
tags:
  - pf2e/creature/type/grioth
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Iazmilor"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Iazmilor"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[grioth]]
trait_02: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Echolocation 30 Feet, Greater Darkvision"
languages: "Aklo, Grioth; Telepathy 30 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Occultism: +17, Religion: +18, Stealth: +18"
abilityMods: [4, 6, 4, 3, 4, 4]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +16, __Will__ +18"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  cold; __Weaknesses__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|+1 Striking Voidglass Warhammer]], [[Equipment/Magic Wand (3rd-Rank Spell)|Wand of Blindness (Rank 3)]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 30 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary 3/Grioth Scout/Echolocation (Precise) 30 feet|Echolocation (Precise) 30 feet]]"
    desc: "  A grioth can use its hearing as a precise sense at the listed range."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "[[Bestiary 3/Grioth Scout/No Breath|No Breath]]"
    desc: "  A grioth doesn't breathe except to speak and is immune to effects that require breathing (such as an inhaled poison)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+17 (shove)\n__Damage__  2d8 + 6 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 (agile, finesse)\n__Damage__  2d8 + 6 piercing plus grioth-venom"

  - name: "Divine Prepared Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_; __3rd __  _[[Spells/Vampiric Feast|Vampiric Feast]]_; __2nd __  _[[Spells/Create Food|Create Food]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Silence|Silence]]_, _[[Spells/Spiritual Weapon|Spiritual Weapon]]_; __1st __  _[[Spells/Bane|Bane]]_, _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Heal|Heal]]_\n__Cantrips__  __(4th)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Occult Innate Spells"
    desc: "DC 23, attack +15; __4th __  _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Grim Curse of Azathoth"
    desc: "`pf2:2` (curse,divine,emotion,mental) **Frequency** once per day\n* * *\n\n**Effect** Iazmilor invokes Azathoth's name in Aklo as he stares at a creature he can see within 30 feet. His eyes glow orange, and the target endures a brief vision of the seething chaos that churns at the center of the Material Plane and, for that instant, beholds their own insignificance in the cosmos. The target must attempt a DC 26 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Stupefied|Stupefied 1]] for 1 hour.\n\n**Failure** The creature becomes stupefied 1, and the first time each night they gaze upon the night sky, they must make a DC 26 Will check save or they increase the value of their stupefied condition by 1 (to a maximum of [[Conditions/Stupefied|Stupefied 4]], or they become stupefied 1 if they do not have this condition). Even if the stupefied condition is removed, the target must continue to save upon gazing upon the night sky once per night until the curse is removed.\n\n**Critical Failure** As failure, but the target feels the weight of the cosmos when the sun sets on their homeland, wherever they may be in the Material Plane or the Great Beyond—they need not gaze upon the night sky."

  - name: "[[Bestiary 3/Grioth Scout/Grioth Venom|Grioth Venom]]"
    desc: " (emotion,fear,mental,poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Frightened|Frightened 1]] (1 round)\n\n**Stage 2** [[Conditions/Frightened|Frightened 2]] (1 round)\n\n**Stage 3** [[Conditions/Frightened|Frightened 3]] (1 round)"

  - name: "[[Bestiary 3/Grioth Scout/Shock Mind|Shock Mind]]"
    desc: "`pf2:2` (mental,occult) The grioth makes a Strike with a voidglass weapon.\n\nIf the Strike hits, it deals an additional 4d6 mental damage, and the target must succeed at a DC 26 Will check save (this has the incapacitation trait) or become [[Conditions/Confused|Confused]] for 1 round."
 
```

```encounter-table
name: Iazmilor
creatures:
  - 1: Iazmilor
```


Grioth priest of Azathoth


