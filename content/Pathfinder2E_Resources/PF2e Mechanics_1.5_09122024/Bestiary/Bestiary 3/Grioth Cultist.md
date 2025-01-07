---
title: "Grioth Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dlpTKND8gnJCObC5" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/grioth
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Grioth Cultist"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Grioth Cultist"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[grioth]]
trait_04: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Greater Darkvision, Echolocation 20 Feet"
languages: "Aklo, Grioth; telepathy 30 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Occultism: +9, Religion: +10, Stealth: +10"
abilityMods: [0, 3, 2, 2, 3, 0]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +10, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  cold; __Weaknesses__ fire 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Kukri|Voidglass Kukri]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 30 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Echolocation (Precise) 20 feet"
    desc: "  A grioth can use its hearing as a precise sense at the listed range."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "No Breath"
    desc: "  A grioth doesn't breathe except to speak and is immune to effects that require breathing (such as an inhaled poison)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Kukri"
    desc: "+10 (agile, finesse, trip)\n__Damage__  1d6 + 2 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (agile, finesse)\n__Damage__  1d8 + 2 piercing plus grioth-venom"

  - name: "Divine Prepared Spells"
    desc: "DC 20, attack +12; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Noise Blast|Sound Burst]]_; __1st __  _[[Spells/Fear|Fear]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Ventriloquism|Ventriloquism]]_\n__Cantrips__  __(2nd)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Message|Message]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Occult Innate Spells"
    desc: "DC 19, attack +11; __2nd __  _[[Spells/Phantom Pain|Phantom Pain]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Grioth Venom"
    desc: " (emotion,fear,mental,poison) **Saving Throw** DC 20 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Frightened|Frightened 1]] (1 round)\n\n**Stage 2** [[Conditions/Frightened|Frightened 2]] (1 round)\n\n**Stage 3** [[Conditions/Frightened|Frightened 3]] (1 round)"

  - name: "Invoke Haunter of the Dark"
    desc: "`pf2:2` (divine,mental,visual) **Frequency** once per day\n* * *\n\n**Effect** The grioth cultist waves a hand in a complex pattern to invoke dark powers, dealing 3d8 mental damage. Each non-grioth creature within 20 feet must attempt a DC 20 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage\n\n**Failure** The creature takes full damage and becomes [[Conditions/Stupefied|Stupefied 1]] for 1 round\n\n**Critical Failure** The creature takes double damage and becomes stupefied 1 for 1 minute."

  - name: "Shock Mind"
    desc: "`pf2:2` (mental,occult) The grioth cultist makes a Strike with a voidglass weapon.\n\nIf the Strike hits, it deals an additional 2d6 mental damage, and the target must succeed at a DC 20 Will check save (this has the incapacitation trait) or become [[Conditions/Confused|Confused]] for 1 round."
 
```

```encounter-table
name: Grioth Cultist
creatures:
  - 1: Grioth Cultist
```



Grioth cultists represent the lowest tier of their remorseless cult-worshippers of the Elder Mythos tasked with leading scouting missions into new worlds. Though ranked above scouts in the chain of command, they occupy a lowly place in the overall religious hierarchy. Though whispered rumors describe the legendary rituals needed to wrench worlds from their suns, these cultists don't learn this potent magic. Such secrets are left to grioth high priests, who are always the last to arrive in a colonized world.

Most grioths worship the Outer God Nyarlathotep in one of his many incarnations, although some worship other entities of the Elder Mythos such as Azathoth, Nhimbaloth, or Yog-Sothoth. In the highly rare cases where a grioth is cut off from their society and given the opportunity to explore other religions, they still lean into faiths associated with the stars or the night, such as Desna or Zon-Kuthon. However, these grioths are loathed by others of their own kind, who view them as dangerous heretics.

* * *

Planets that drift out of orbit from their stars grow cold and lifeless as they float through the Dark Tapestry. Such dead worlds are coveted by the horrific creatures known as grioths, who endure the awful cold on these wandering worlds and convert them into planetary temples devoted to the dark gods of the Elder Mythos. From these bastions of frozen darkness, grioths seek out warm, living worlds to tear away from their respective suns through forbidden rituals, a process that often takes numerous generations.

A single cultist typically leads a grioth scouting party, and the group seeks out a disused or forgotten location on the fringe of rural settlements as their initial invasion point. Over several generations, a grioth settlement grows powerful and conquers the surrounding cultures, and eventually, powerful grioths descend from the stars to begin the next stage of planetary conquest.

Grioths speak a language composed of trills and clicks. While capable of speaking other languages, they do so in dry, raspy voices. As grioths have wings, wriggling tails, and four-eyed, bat-like visages, many cultures mistakenly associate them with the evil Outer Planes, but they very much belong to this reality.
