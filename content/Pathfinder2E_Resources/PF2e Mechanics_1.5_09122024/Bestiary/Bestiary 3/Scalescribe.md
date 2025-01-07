---
title: "Scalescribe"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nr2CKoXqEEjl5MNz" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Scalescribe"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Scalescribe"
level: "Creature 3"

alignment: ""
size: "tiny"
trait_01: [[aberration]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Aklo, Common, Draconic"
skills:
  - name: "Skills"
    desc: "Arcana: +11, Occultism: +9, Stealth: +8, Library Lore: +11, Scribing Lore: +11"
abilityMods: [-2, 3, 1, 4, 4, 0]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +10, __Will__ +11; +2 status to all saves vs. linguistic effects"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

  - name: "Mage Bond"
    desc: "  After performing a 1-hour ritual, a scalescribe can bond with one willing creature capable of Casting Spells.\n\nThe scalescribe can [[Actions/Aid|Aid]] their bonded caster in [[Actions/Craft|Crafting]] a scroll, and they can make their Transcribed spell available to the caster so long as the spell is of the caster's tradition.\n\nA bonded prepared caster can prepare the spell. A bonded spontaneous caster can add the spell to their spell repertoire during their daily preparations, and it remains as long as the Transcribed scroll exists."

abilities_mid:
  - name: ""
  - name: "Transcribe"
    desc: "`pf2:r`  **Trigger** Another creature targets the scalescribe with a spell requiring verbal components\n* * *\n\n**Effect** The scalescribe attempts to copy the incantation onto a scroll by attempting a counteract check (counteract rank 2, counteract modifier +10) with the following effects instead of the normal effects of counteracting. The spell still affects the scalescribe, regardless of the results of this check.\n\nThe scalescribe can Cast a Spell from any scroll they Transcribe as if it were on their spell list. Transcribing a new scroll renders any previously Transcribed scroll inert.\n* * *\n\n**Critical Success** If the triggering spell's rank was no more than 3 higher than the scalescribe's counteract rank, the scalescribe captures a copy of the spell in a scroll that appears in their hand. This scroll can be used normally but fades after 24 hours if not used before then.\n\n**Success** As critical success, but only if the spell's rank is no more than 1 higher than the scalescribe's counteract rank.\n\n**Failure** As critical success, but only if the spell's rank is lower than the scalescribe's counteract rank.\n\n**Critical Failure** The scalescribe fails to copy the spell."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fountain Pen"
    desc: "+10 (agile, finesse, magical)\n__Damage__  1d6 + 2 piercing plus inkstain"

  - name: "**Ranged** `pf2:1` Morpheme Glyph"
    desc: "+10 (magical, range 40 feet)\n__Damage__  3d6 force"

  - name: "Arcane Innate Spells"
    desc: "DC 20, attack +12; __3rd __  _[[Spells/Secret Page|Secret Page]]_; __2nd __  _[[Spells/Translate|Comprehend Language (Self Only) (x3)]]_, _[[Spells/Dispel Magic|Dispel Magic]]_\n__Cantrips__  __(2nd)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Message|Message]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Inkstain"
    desc: "  When the scalescribe deals damage to a creature with their fountain pen, the creature takes 1d4 persistent poison.\n\nWhen a creature taking this damage attempts to take an action with the concentrate trait, it must succeed at a DC 5 Flat check check or the action is disrupted."
 
```

```encounter-table
name: Scalescribe
creatures:
  - 1: Scalescribe
```



Often seen at the sides of spellcasters, scalescribes are tiny, snakelike creatures with numerous hands that usually hold a multitude of fountain pens in various ink colors. The words scrawled across their bodies shift depending on what texts they've encountered recently. Scalescribes have a fondness for language, especially magical language, and make their homes in libraries or other places of learning.
