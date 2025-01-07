---
title: "Doru"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bcDMFMMoze5eZfm8" 
tags:
  - pf2e/creature/type/div
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Doru"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Doru"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[div]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Greater Darkvision"
languages: "Common, Daemonic; telepathy (touch)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Arcana: +8, Deception: +6, Religion: +5, Stealth: +7, Lore (Any One): +10"
abilityMods: [0, 4, 1, 3, 2, 3]
speed: 15 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +4, __Ref__ +9, __Will__ +7"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Weaknesses__ cold iron 3, holy 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy (Touch)]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Covetous of Secrets"
    desc: "  Dorus have a weakness for secrets, hoarding them like a miser hoards gold. A creature can tempt a doru with some bit of obscure knowledge the doru doesn't know or thinks they don't know.\n\nPresenting the hint of the secret is a single action, which has the concentrate and linguistic traits, and requires a skill check using Deception, Lore, or Performance (or some other appropriate skill determined by the GM) against the doru's Will DC.\n\nOn a success, the doru is [[Conditions/Fascinated|Fascinated]] for as long as the presenter draws out the explanation of the secret (spending 1 action each round doing so, to a maximum of 1 minute). On a critical success, the doru is fascinated for that duration plus 1 minute more as it ponders the implications of the secret. Regardless of the outcome, the doru is temporarily immune to that creature's attempts to present it with secrets for 1 day."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+9 (agile, finesse, magical, poison, unholy)\n__Damage__  1d6 piercing plus doru-venom"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_; __1st __  _[[Spells/Charm|Charm]]_, _[[Spells/Illusory Object|Illusory Object]]_\n__Cantrips__  __(1st)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Doru Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 3** 1d6 poison damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)"
 
```

```encounter-table
name: Doru
creatures:
  - 1: Doru
```



These deceivers whisper fetid lies, sowing dark and dread inspiration into foolish mortal ears. Dorus serve as the spies and messengers of the divs. With silver tongues and dark motives, they often pledge themselves to vainglorious and deluded spellcasters, who they ply with wild conspiracies and rumors of deception among friends and foes alike; in the process, they push supposed masters to despotism and murderous revenge. All the while, dorus wean secrets, and weaknesses, from their marks. In the end, nearly every doru turns on their false liege, destroying the reputation and even causing the death of the person the doru pretended to serve.

* * *

Some fiends want to tear down the multiverse; others dedicate themselves to creating chaos and carnage, or to rule over realms with an iron fist. Divs strive toward a different, if equally reprehensible, goal-they seek to thwart and ruin the schemes and works of mortal beings.

Long ago, divs were once genies bound to serve ancient mortal empires lost to the passage of eons. In the beginning, these genies were masters of creation, working alongside gracious mortal partners to create works of subtle design and powerful magical potential. What started as a collaboration with mortals soon morphed into abuse, disrespect, and even slavery and bondage. Eventually, these genies rebelled, but in doing so, they came under the sway of a nihilistic demigod known as Ahriman. Their new master twisted their form and granted them the power to avenge themselves upon their mortal overlords, leading to the birth of the first divs.

Since that first wave of corruption, new divs arise from the spirits of the most wicked and hateful genies who die on the Material Plane, or those truly betrayed by mortals and overcome through their desire for vengeance. Upon such a death, instead of returning to the Elemental Planes, these genies' spirits are trapped in the dread orbit of Abaddon, where Ahriman reshapes them as divs and hoists them back to the world to wreak vengeance upon mortals.
