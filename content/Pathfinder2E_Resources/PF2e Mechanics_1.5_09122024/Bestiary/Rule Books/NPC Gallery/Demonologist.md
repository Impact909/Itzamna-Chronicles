---
title: "Demonologist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y5oZaYpfSVqxCX9h" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Demonologist"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Demonologist"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: "Chthonian, Common"
skills:
  - name: "Skills"
    desc: "Arcana: +16, Diplomacy: +11, Religion: +15, Academia Lore: +14, Demon Lore: +18"
abilityMods: [3, 1, 2, 4, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +13, __Ref__ +12, __Will__ +15"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|+1 Longspear]], [[Equipment/Explorer's Clothing|Scholarly Robes]], [[Compendium.pf2e.equipment-srd.Item.VHxXMvBeBTq2FSdf|Spell Component Pouch]], [[Equipment/Spellbook (Blank)|Spellbook (Fiendish Hypotheses and Protections from Same)]]"
  - name: "Abyssal Temptation"
    desc: " (divine,mental) Demonic study has garnered the attention of at least one demon that is actively trying to possess the demonologist.\n\nWhen the demonologist publicly espouses the benefits of demonic power (whether they believe it a good thing or not), they gain a +1 status bonus to skill checks, AC, and saves for 1 day. These bonuses don't apply against demons.\n\nAt the end of the day, the demonologist must attempt a DC 20 Will check save, becoming possessed for 1 day on a failure (permanently on a critical failure)."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+17 (magical, reach)\n__Damage__  1d8 + 9 piercing"

  - name: "Arcane Prepared Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Containment|Resilient Sphere]]_; __3rd __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Rune Trap|Glyph of Warding]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Acid Arrow|Acid Arrow]]_, _[[Spells/Blur|Blur]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/See the Unseen|See Invisibility]]_; __1st __  _[[Spells/Fear|Fear]]_, _[[Spells/Fleet Step|Fleet Step]]_, _[[Spells/Mending|Mending]]_\n__Cantrips__  __(4th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Breach the Abyss"
    desc: "  **Requirements** The demonologist's last action was to cast a non-cantrip spell\n* * *\n\n**Effect** The demonologist siphons energy drawn from the Abyss into their weapon. Until the end of the turn, the weapon deals an extra 2d6 damage.\n\nRoll 1d20 to determine the type:\n\n*   1-7 acid\n*   8-9 cold\n*   10-11 electricity\n*   12-18 fire\n*   19-20 negative"

  - name: "Demon Summoning"
    desc: "  The demonologist can cast a 5th-rank [[Spells/Summon Fiend|Summon Fiend]] arcane spell to summon a demon. To do so, they must sacrifice two 4th-rank prepared spells and voluntarily take 4d12 mental damage that can't be reduced or prevented.\n\nIf the demonologist is unable to [[Actions/Sustain|Sustain]] the Spell, including if they're knocked out or killed, the spell continues, but the GM rolls a DC 10 Flat check each round, ending the spell on a failure."
 
```

```encounter-table
name: Demonologist
creatures:
  - 1: Demonologist
```



Demonologists can pull a creature from the Abyss and bend it to their will... for a time.

* * *

Those initiated into the hidden truths and forbidden secrets of the world are forever transformed-or so they claim. To the cynical, a mystic is nothing more than a charlatan or zealot. Others profess to sense an aura around such luminaries and treat them with reverence, lest they offend some harbinger of unspeakable doom.
