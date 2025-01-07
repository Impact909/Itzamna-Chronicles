---
title: "Brimorak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q9GZ1VUF1h3gl5FR" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Brimorak"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Brimorak"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Chthonian, Draconic, Empyrean, Pyric; Telepathy 60 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Deception: +11, Religion: +10, Stealth: +12"
abilityMods: [4, 3, 4, 1, 1, 2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +12, __Will__ +10"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  fire; __Weaknesses__ cold iron 5, holy 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 60 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Extinguishing Aversion"
    desc: "  Dousing a brimorak with water, either ordinary water or from a water effect, causes no physical harm to the fiend but deals 3d6 mental damage. Fully immersing the brimorak in water deals 5d6 mental damage per round."

  - name: "Smoke Vision"
    desc: "  Smoke doesn't impair a brimorak's vision; they ignore the [[Conditions/Concealed|Concealed]] condition from smoke."

abilities_mid:
  - name: ""
  - name: "Boiling Blood"
    desc: "  Each time an adjacent creature deals slashing or piercing damage to the brimorak, the attacker is sprayed with the brimorak's boiling blood, which deals 2d4 fire damage (DC 19 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flaming Sword"
    desc: "+15 (magical, unholy)\n__Damage__  2d8 + 4 slashing 1d6 fire"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+15 (agile, unholy)\n__Damage__  2d4 + 4 bludgeoning 1d6 fire"

  - name: "Divine Innate Spells"
    desc: "DC 21, attack +13; __4th __  _[[Spells/Translocate|Translocate]]_; __3rd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Fireball|Fireball]]_\n__Cantrips__  __(3rd)__ _[[Spells/Ignition|Ignition]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Flaming Weapon"
    desc: " (divine,fire) A brimorak's hooves and any weapon they wield burst into flame. They can also Interact to create a sword of fire and steel, which dissolves if it leaves their grip."

  - name: "Frothing Spew"
    desc: "`pf2:2` (divine,fire,unholy) The brimorak spits their boiling blood in a 20-foot line that deals 6d6 fire damage (DC 21 basic Reflex save). Creatures that fail the save also fall [[Conditions/Prone|Prone]] as they slip in the greasy blood.\n\nThe brimorak can't use Frothing Spew again for 1d4 rounds."

  - name: "Fume"
    desc: "`pf2:2` (divine,fire) **Frequency** once per minute\n* * *\n\n**Effect** The brimorak emits a cloud of thick black smoke in a 10-foot burst adjacent to them. The cloud remains for 1 minute. All creatures within the smoke become [[Conditions/Concealed|Concealed]], and all creatures outside the smoke become concealed to creatures within it.\n\nA creature that enters or begins its turn within the smoke it must succeed at a DC 21 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure)."
 
```

```encounter-table
name: Brimorak
creatures:
  - 1: Brimorak
```



These goat-headed demons have glowing red eyes and flaming hooves but measure only about 4 feet in height. Born from the souls of arsonists, the fiery brimoraks continue the work they pursued in life, as everything they touch quickly burns.

Brimoraks are ill-tempered even for demons, although their spite turns to glee in the face of a growing fire. Those who have survived encounters with these fiends report that they remember the braying sound of the brimoraks' laughter as clearly as the heat of the flames or the choking scent of smoke.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
