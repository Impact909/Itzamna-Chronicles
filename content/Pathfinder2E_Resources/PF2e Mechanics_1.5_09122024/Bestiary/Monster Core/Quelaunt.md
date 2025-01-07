---
title: "Quelaunt"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mGKUQHbFMjU0AcUp" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Quelaunt"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Quelaunt"
level: "Creature 15"

alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Tremorsense (Imprecise) 60 Feet"
languages: "Aklo; (Can&#x27;t Speak Any Language), Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Deception: +30, Intimidation: +30, Occultism: +27"
abilityMods: [6, 5, 4, 5, 6, 8]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +26, __Will__ +31; +2 to will saves vs. emotion"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305; __Resistances__ mental 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet)\n__Damage__  3d8 + 12 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 39, attack +31; __7th __  _[[Spells/Wave of Despair|Wave of Despair (x3)]]_; __3rd __  _[[Spells/Fear|Fear (At Will)]]_; __2nd __  _[[Spells/Laughing Fit|Laughing Fit]]_\n__Constant__  __(4th)__ _[[Spells/Fly|Fly]]_"

  - name: "Emotional Focus"
    desc: "DC 39, attack +31; __8th __  _[[Spells/Captivating Adoration|Captivating Adoration]]_, _[[Spells/Delusional Pride|Delusional Pride]]_, _[[Spells/Ignite Ambition|Ignite Ambition]]_"

  - name: "Emotional Focus"
    desc: "  The quelaunt can cast the following cleric domain spells as 8th-rank occult innate spells at will without spending Focus Points: [[Spells/Captivating Adoration|Captivating Adoration]], [[Spells/Delusional Pride|Delusional Pride]], and [[Spells/Ignite Ambition|Ignite Ambition]]."

  - name: "Emotional Frenzy"
    desc: "`pf2:3`  The quelaunt casts up to three spells chosen from its at-will innate spells and its emotional focus spells."

  - name: "Feed on Emotion"
    desc: "`pf2:1` (attack,emotion,incapacitation,mental) **Frequency** once per round;\n* * *\n\n**Effect** The quelaunt feeds on the emotional unrest of a single creature within 30 feet that's under a harmful emotion effect. The target must succeed at a DC 37 Will check save or take 4d10 mental damage and be [[Conditions/Stunned|Stunned]] for 1 round.\n\nIf the target fails its saving throw, the quelaunt regains the same number of Hit Points and regains the action it spent to Feed on Emotion. It can't use the regained action to Feed on Emotion again."

  - name: "Rapid Strikes"
    desc: "`pf2:2` (attack) The quelaunt makes three melee Strikes, each against a different target within reach. The multiple attack penalty applies to each attack but increases only after all the attacks have been made."

  - name: "Spiral of Despair"
    desc: " (emotion,mental) **Trigger** A creature fails a saving throw to resist one of the quelaunt's innate spells or emotional focus spells\n* * *\n\n**Effect** As the quelaunt invades the triggering creature's mind and plants the seeds of negative emotions, it also strips away the target's feelings of hope or positivity. The quelaunt can immediately end a single emotion effect from which the triggering creature is benefiting."
 
```

```encounter-table
name: Quelaunt
creatures:
  - 1: Quelaunt
```



This three-armed, three-legged monster has no discernible eyes, nose, ears, or mouth, and no visible means of ingesting food. Its limbs are distributed so evenly across its body that it's all but impossible to tell which way the creature is oriented at any given time. Few who witness a quelaunt linger on its alien looks for long though, as the invasion of their minds becomes a more pressing concern, sowing doubt, sorrow, and rage. This monstrosity not only delights in the negative emotions of its prey, but feeds on them, gaining strength and sustenance from their dismay. For the quelaunt, no act is too terrible or cruel to inflict on its victims, since the more a creature suffers, the more the quelaunt feasts.

Quelaunts are known to associate with other aberrant horrors, including jah-tohls and other creatures associated with the Dominion of the Black. However, the more prevalent theory paints them as more alien—perhaps invasive beings from another dimension of pure thought and feeling—and claims that in their natural state they have no physical bodies at all. Few dare speculate further; the only known autopsy of a quelaunt resulted in the researcher's suicide just days afterward and all the notes were mysteriously destroyed. Whatever secrets there are to be unlocked in the anatomy of these bizarre monsters are apparently important enough to warrant great protection from quelaunts, even after death.
