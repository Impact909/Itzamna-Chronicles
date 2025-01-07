---
title: "Serpentfolk Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zJL8S2Nta7URoL1k" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/serpentfolk
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Serpentfolk Cultist"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Serpentfolk Cultist"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[serpentfolk]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +13, Athletics: +13, Crafting: +13, Deception: +16, Intimidation: +14, Occultism: +15, Religion: +17, Society: +13"
abilityMods: [2, 3, 2, 4, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +14, __Will__ +17; +4 status to will saves vs. mental"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Resistances__ poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|+1 Striking Dagger]], [[Equipment/Religious Symbol (Silver)|Religious Symbol of Ydersius]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+16 (finesse)\n__Damage__  2d8 + 8 piercing plus serpentfolk-venom"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+17 (agile, finesse, magical, versatile s)\n__Damage__  2d4 + 8 piercing"

  - name: "Divine Spontaneous Spells"
    desc: "DC 25, attack +17; __4th __ (2 slots) _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Harm|Harm]]_; __3rd __ (3 slots) _[[Spells/Blindness|Blindness]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Heal|Heal]]_; __2nd __ (3 slots) _[[Spells/Create Food|Create Food]]_, _[[Spells/Noise Blast|Noise Blast]]_, _[[Spells/Spiritual Weapon|Spiritual Weapon]]_; __1st __ (3 slots) _[[Spells/Command|Command]]_, _[[Spells/Enfeeble|Enfeeble]]_, _[[Spells/Fear|Fear]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Occult Innate Spells"
    desc: "DC 28, attack +20; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will)]]_; __2nd __  _[[Spells/Mirror Image|Mirror Image (At Will)]]_; __1st __  _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_"

  - name: "Raise Serpent"
    desc: "`pf2:3` (concentrate,divine) **Frequency** once per day\n* * *\n\n**Effect** The bone prophet animates corpses of snakes, serpentfolk, or similar serpentine creatures within a 30-foot emanation. Any flesh on the bodies sloughs off, and they rise as skeletons. The bone prophet can raise one Large creature as a [[Monster Core/Skeletal Giant|Skeletal Giant]] or up to three Medium creatures as [[Monster Core/Skeletal Champion|Skeletal Champions]]; the equipment and attacks might be different depending on the corpses' possessions.\n\nThese skeletons have the minion trait and are under the bone prophet's control; the bone prophet can give all these minions the same command with a single action that has the concentrate trait. Any skeletal minions that still remain after 10 minutes crumble to dust."

  - name: "[[Actor.acGApO7HwzXQVlTU.Item.pkqZFkDwe6SFvUXX|Serpentfolk Venom]]"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d4 poison damage and enfeebled 1 (1 round)"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The creature's Strikes deal an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Serpentfolk Cultist
creatures:
  - 1: Serpentfolk Cultist
```


Variant serpentfolk bone prophet

The speakers for the dead known as bone prophets hold an esteemed place as voices for their decapitated god. Burial rites, necromantic rituals, and the delivery of cryptic utterances supposedly whispered to them by Ydersius all fall under the dominion of these priests. Bone prophets often raise fallen aapophs as skeletons.
