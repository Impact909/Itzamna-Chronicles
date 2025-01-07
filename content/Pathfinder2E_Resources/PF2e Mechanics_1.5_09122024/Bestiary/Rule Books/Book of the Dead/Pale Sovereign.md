---
title: "Pale Sovereign"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ePQJQscQy1rfndIt" 
tags:
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Pale Sovereign"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Pale Sovereign"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[lawful]]
trait_02: [[undead]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Deception: +31, Diplomacy: +31, Intimidation: +33, Occultism: +28, Society: +28"
abilityMods: [4, 8, 4, 6, 6, 9]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +30, __Will__ +28; -2 to all saves vs. curses"
hp: 298
health:
  - name: ""
  - name: HP
    desc: "298, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "Demesne Confinement"
    desc: " (curse,occult) A pale sovereign is tied to their demesne, a territory of a 5-mile radius surrounding their home estate. They can't leave their demesne of their own accord. A pale sovereign taken from their demesne can't use any of their innate spells or rituals and gradually withers over the course of a week, turning to dust if they don't return before 7 days have passed."

  - name: "Sense Visitors"
    desc: " (detection,occult) A pale sovereign automatically knows when a creature enters or leaves their demesne, though this doesn't give them precise knowledge of the creature's location."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Charm"
    desc: " (aura,emotion,incapacitation,mental,occult) 80 feet. The aura of a pale sovereign is beguiling and inviting, affecting creatures beginning their turns within it with an 8th-rank [[Spells/Charm|Charm]] (DC 39 Will check save). A creature that fails its Will save perceives the pale sovereign as they were in life, not their current undead form. A creature that succeeds at its save is then temporarily immune to that pale sovereign's aura for 24 hours."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rosebriar Lash"
    desc: "+28 (finesse, magical, reach 10 feet, versatile p)\n__Damage__  4d8 + 8 slashing 2d6 bleed"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __8th __  _[[Spells/Spirit Song|Spirit Song]]_, _[[Spells/Spiritual Epidemic|Spiritual Epidemic]]_; __7th __  _[[Spells/Curse of Lost Time|Curse of Lost Time]]_, _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Project Image|Project Image]]_, _[[Spells/Suggestion|Suggestion]]_; __6th __  _[[Spells/Bestial Curse|Bestial Curse]]_, _[[Spells/Cloak of Colors|Cloak of Colors]]_, _[[Spells/Enthrall|Enthrall (At Will)]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_\n__Constant__  __(5th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Rituals"
    desc: "_Garden of Death_, _Unseen Custodians_, _Ward Domain_"

  - name: "Curse of Eternal Sleep"
    desc: "`pf2:2` (curse,incapacitation,mental,occult,sleep) The pale sovereign touches an adjacent living creature to send it into an endless slumber. The target must attempt a DC 39 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune for 24 hours.\n\n**Success** The target becomes drowsy and is [[Conditions/Slowed|Slowed 1]] for 1 minute.\n\n**Failure** The target falls [[Conditions/Unconscious|Unconscious]], though it doesn't fall [[Conditions/Prone|Prone]] or release what it's holding. It can't awaken with a successful Perception check, though dealing any amount of damage to the creature breaks the slumber. If it's still unconscious after 1 hour, it awakens.\n\n**Critical Failure** The target falls unconscious permanently, falling prone, and can't be awoken as long as the curse remains."

  - name: "Siphon Vitality"
    desc: "`pf2:3` (occult,void) The pale sovereign siphons the life force from creatures around them. All living creatures in a 30-foot emanation take 6d8 void damage (DC 39 Fortitude check). The pale sovereign regains HP equal to the highest damage a single creature took from this effect."
 
```

```encounter-table
name: Pale Sovereign
creatures:
  - 1: Pale Sovereign
```



A pale sovereign is a rare form of undead arising from a terrible curse that afflicts only those of royal blood. This curse drains its victim's vitality slowly over time, almost appearing to be a form of long-term wasting disease that no medicine can ever cure. The royal stricken by the curse sickens and wastes away until they finally perish, rising as a pale sovereign after death. The appearance of a pale sovereign is similar to their form in life, but so deathly pale and gaunt that no one who resists the mind-clouding effects of their aura would mistake them as living.

The curse is known by many names across various worlds—the Wasting, Blighted Legacy, Unraveled Heraldry—but its effects are the same. After suffering the curse, members of a royal bloodline begin to die out, their descendants dwindling, until only one is left. Upon becoming the last remaining member of their line, the unfortunate royal undergoes the transformation into a pale sovereign, the power and potential of the entire line channeled into one extremely dangerous undead creature, even if the royal was relatively inconsequential and unskilled in life.

The methods of inflicting the curse vary. Generally it's the result of rare occult rituals requiring a spellcaster of great power. Sometimes the curse is used to target a royal line abusing its authority, but just as often it's used by malicious forces against benevolent rulers or simply out of spite by the instigating caster. Mentioned only in whispers and veiled allusions, the curse is greatly feared by royal families who know of it. Be cautious in your dealings, the rumors say, and be careful who you spurn, for you never know what power they may wield.

More rarely, a pale sovereign can arise spontaneously if the last of a royal line dies while under a curse or due to a curse, particularly if they died with tasks left unfinished or as the result of a betrayal. Any curse will do in these rare instances, and it's possible that the first pale sovereign formed in this way.

Though morose and brooding, pale sovereigns are usually neutral rather than evil. They're very protective of their demesnes and whatever subjects remain to them, however, and attacking a pale sovereign's territory is the swiftest way to draw their ire. If a pale sovereign is ousted from their country's central throne, they retreat to any other holdings they might still possess and rule those.

The attitudes of a pale sovereign's subjects vary. Many aren't even aware of their ruler's true nature. Among those who know the secret, some value their sovereign's protection and view them fondly. Others are uncomfortable with an undead eternal monarch, especially if the sovereign has become corrupt or bitter.

A pale sovereign's territory is indelibly marked by their presence. Plants wither and blacken, struggling to grow in dry and lifeless soil. Wild animals often rise as undead unless they receive special ritual burials, leading to packs of skeletal and zombified beasts roaming the territory. Such monsters don't harm the demesne's residents but are quick to attack any intruders not bearing the sovereign's sigil. Even the living sapient inhabitants of a pale sovereign's demesne tend to have a drained, washed-out appearance, as if one step away from the grave themselves.
