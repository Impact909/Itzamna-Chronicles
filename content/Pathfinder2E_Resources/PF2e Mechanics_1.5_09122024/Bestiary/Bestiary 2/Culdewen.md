---
title: "Culdewen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4F0UmyVvLMq8oe2c" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Culdewen"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Culdewen"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fey]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: "Common, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Deception: +16, Intimidation: +14, Nature: +12, Stealth: +15, Survival: +16, Sailing Lore: +14"
abilityMods: [4, 5, 1, -1, 2, 4]
speed: 40 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +14, __Ref__ +18, __Will__ +13; -2 status to all saves vs. curses"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Mace|Oar (Functions as Mace)]], [[Equipment/Ogre Hook|Fish Hook]]"
  - name: "Culdewen's Curse"
    desc: " (curse,primal) A culdewen that captures a creature is compelled to immediately retreat to a secluded place to eat, typically journeying by boat. The travel to the secluded place always takes at least 1 day. Their captive is cursed to vanish on the journey-typically being lost in the water or consumed by aquatic creatures-and can be recovered only by a [[Spells/Wish|Wish]] spell or similarly powerful magic."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fish Hook"
    desc: "+17 (trip)\n__Damage__  2d10 + 7 piercing plus hooked"

  - name: "**Melee** `pf2:1` Oar"
    desc: "+17 (shove)\n__Damage__  2d6 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Fish Hook"
    desc: "+18 (thrown 30 ft.)\n__Damage__  2d10 + 7 piercing plus hooked"

  - name: "Hooked"
    desc: "  A creature struck by the culdewen's fish hook is skewered, taking 1d4 bleed as long as the hook remains stuck in it. The fish hook can be removed if a creature [[Actions/Escape|Escapes]] (DC 25 Athletics check), pulling it free."

  - name: "Land the Fish"
    desc: "`pf2:1`  **Requirements** A creature is hooked by the culdewen's fish hook and adjacent to the culdewen\n* * *\n\n**Effect** The culdewen hoists the creature over their shoulder, as though it weighs no more than a fish. Unless the creature is unable to act, the culdewen must attempt an Athletics check check against the creature's Fortitude DC. On a success, the creature is [[Conditions/Restrained|Restrained]] by the culdewen. [[Actions/Escape|Escaping]] from the restrained condition (DC 25) also allows a creature to remove the hook.\n\nWhile hoisting a creature, the culdewen gains a +20-foot status bonus to their Speeds and is compelled to escape with it (see culdewen's curse above)."

  - name: "Reel In"
    desc: "`pf2:1` (manipulate) The culdewen pulls the rope attached to their hook. If they have no creature hooked, the fish hook returns to the culdewen's hand. If a creature is hooked, the culdewen attempts an Athletics check check against the creature's Fortitude DC, pulling it up to 30 feet closer on a success (60 feet on a critical success)."

  - name: "Swear"
    desc: "`pf2:1` (auditory,curse,primal) The culdewen unleashes a string of invectives. Each creature that hears them must attempt a DC 25 Will check save, with the effects of [[Spells/Mariner's Curse|Mariner's Curse]] and is then temporarily immune for 24 hours. Even on a failed save, the curse ends automatically after 1 day."
 
```

```encounter-table
name: Culdewen
creatures:
  - 1: Culdewen
```



Perpetually cursed to hunger and failure, a culdewen plies waterways in search of appealing fish to catch-the bigger the better. Of course, this diminutive, emaciated fey calls every living creature a "fish." Only other fey are exempt, and they tend to consider culdewens lost causes. A culdewen can never find satisfaction. Each time they catch a fish, a magical curse forces them to hunt for an appealing spot to dine-an island, cove, or abandoned dock or shack where they can eat in peace. By the time they arrive, their catch will be gone. Every time. Forever.

A foul mood hovers over a culdewen, causing them to swear colorfully, smack things with their oar, and shake their tiny fists at the sky. Conversation with a culdewen is fruitless, as they talk in circles, speaking only of fishing and the weather. Capturing a "fish" gives a culdewen a rare moment of happiness; the culdewen capers and ululates, pleased with their catch, and rushes off to their boat.
