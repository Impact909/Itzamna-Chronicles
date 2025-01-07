---
title: "Hryngar Battlepriest"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vuk9QJ45ReB5rEun" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/hryngar
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Hryngar Battlepriest"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Hryngar Battlepriest"
level: "Creature 9"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[hryngar]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Intimidation: +19, Nature: +15, Religion: +19"
abilityMods: [4, 1, 4, 1, 5, 3]
speed: 20 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +18, __Ref__ +15, __Will__ +21"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Resistances__ poison 8"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Light Hammer|+1 Striking Returning Light Hammer]], [[Equipment/Chain Mail|Chain Mail]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "Sheltered Command"
    desc: "`pf2:r` (auditory,linguistic,mental) **Trigger** The battlepriest is targeted with an attack while adjacent to or sharing a space with a hryngar\n* * *\n\n**Effect** The battlepriest commands the hryngar to intercept the attack. The hryngar becomes the target of the attack."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Light Hammer"
    desc: "+20 (agile, magical, thrown 20 ft.)\n__Damage__  2d6 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Light Hammer"
    desc: "+20 (agile, magical, thrown 20 ft.)\n__Damage__  2d6 + 8 bludgeoning"

  - name: "Divine Prepared Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Flame Strike|Flame Strike]]_, _[[Spells/Spiritual Guardian|Spiritual Guardian]]_; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Unfettered Movement|Freedom of Movement]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Heroism|Heroism]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/See the Unseen|See the Unseen]]_; __1st __  _[[Spells/Fear|Fear]]_, _[[Spells/Heal|Heal]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Shield|Shield]]_"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __4th __  _[[Spells/Blood Vendetta|Blood Vendetta]]_; __2nd __  _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(5th)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Part the Troops"
    desc: "  The hryngar battlepriest and their mount can share the same space as creatures with both the hryngar and troop traits. Such creatures ignore the Trample ability of any creature the battlepriest is riding."

  - name: "Toil and Trample"
    desc: "`pf2:1`  **Requirements** The battlepriest is mounted on a creature with a Trample ability\n* * *\n\n**Effect** The battlepriest commands their mount. Until the beginning of the battlepriest's next turn, the saving throw DC of the mount's Trample increases to DC 26 Reflex check, and the Trample deals an additional 3d6 spirit damage."
 
```

```encounter-table
name: Hryngar Battlepriest
creatures:
  - 1: Hryngar Battlepriest
```




