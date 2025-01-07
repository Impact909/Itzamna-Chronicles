---
title: "Cult Leader"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.A41FVcQmdaD0a1yc" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Cult Leader"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Cult Leader"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Arcana: +13, Deception: +16, Diplomacy: +14, Intimidation: +16, Occultism: +17, Society: +13, Cult Lore (Applies to the Leader's own cult): +19"
abilityMods: [0, 4, 1, 4, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +15, __Will__ +18"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|+1 Staff]], [[Equipment/Explorer's Clothing|Ceremonial Robes]], [[Equipment/Spellbook (Blank)|Indecipherable Book of Sigils]]"
abilities_mid:
  - name: ""
  - name: "Protect the Master!"
    desc: "`pf2:r` (auditory,concentrate,emotion,linguistic,mental,move) **Trigger** The cult leader is targeted with an attack, and a lower-ranking cultist is adjacent to them\n* * *\n\n**Effect** The cult leader orders their cultist to leap in front of the attack. The cultist and cult leader swap places, and the cultist becomes the target of the attack. If the cultist has Fanatical Frenzy or a similar ability, they can activate it as a reaction if they take damage from the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+13 (magical, two-hand d8)\n__Damage__  1d4 + 6 bludgeoning"

  - name: "Occult Spontaneous Spells"
    desc: "DC 26, attack +18; __4th __ (3 slots) _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Honeyed Words|Glibness]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __ (4 slots) _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Mind Reading|Mind Reading]]_; __2nd __ (4 slots) _[[Spells/Augury|Augury]]_, _[[Spells/Calm|Calm Emotions]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_, _[[Spells/Stupefy|Touch of Idiocy]]_; __1st __ (4 slots) _[[Spells/Bless|Bless]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Lock|Lock]]_, _[[Spells/Phantasmal Minion|Unseen Servant]]_\n__Cantrips__  __(4th)__ _[[Spells/Void Warp|Chill Touch]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Shield|Shield]]_"

  - name: "Gather Converts"
    desc: "`pf2:3` (auditory,concentrate,emotion,linguistic,mental) With a short emotional phrase, the cult leader tries to sway the public to do their bidding. The cult leader tries to convince up to four bystanders in a crowd to either cause a commotion, turn against a person or group, leave the area, protect the cult leader, or calm down.\n\nThe cult leader attempts a single Deception check against the highest Perception DC among the targets.\n* * *\n\n**Critical Success** The targets believe the lie and act as directed for 1 minute. Additionally, one bystander remains by the cult leader's side, influenced enough to join their sect.\n\nAll other targets become wise to the cult leader after 1 minute, at which point their attitude toward the leader worsens by one step.\n\n**Success** As a critical success, but no bystander joins the sect permanently.\n\n**Critical Failure** The crowd is unmoved and unamused, and their attitude toward the cult leader worsens by one step."
 
```

```encounter-table
name: Cult Leader
creatures:
  - 1: Cult Leader
```



A career of mystical accomplishments combined with a lifetime of subterfuge and intimidation has elevated this occultist to a powerful position.

* * *

Those initiated into the hidden truths and forbidden secrets of the world are forever transformed-or so they claim. To the cynical, a mystic is nothing more than a charlatan or zealot. Others profess to sense an aura around such luminaries and treat them with reverence, lest they offend some harbinger of unspeakable doom.
