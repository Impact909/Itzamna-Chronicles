---
title: "Avatar of the Lantern King"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cUzUNRbNAoa2HoAe" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/24
statblock: inline
name: "Avatar of the Lantern King"
level: 24
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Avatar of the Lantern King"
level: "Creature 24"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[fire]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Darkvision, Truesight"
languages: "Aklo, Common, Fey; telepathy 300 feet; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +46, Arcana: +41, Athletics: +41, Deception: +49, Diplomacy: +42, Intimidation: +46, Nature: +46, Occultism: +41, Religion: +41, Society: +39, Stealth: +42, Thievery: +42, First World Lore: +43"
abilityMods: [9, 12, 7, 9, 7, 12]
speed:  fly 60 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 54
armorclass:
  - name: AC
    desc: "54; __Fort__ +36, __Ref__ +39, __Will__ +41"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500; __Immunities__  bleed,  blinded,  controlled,  dazzled,  death effects,  doomed,  fire,  sleep,  unconscious; __Weaknesses__ cold 25, cold iron 20; __Resistances__ physical 20 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 300 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Fortune's Friend"
    desc: "`pf2:r` (fortune,primal) **Trigger** The Lantern King fails or critically fails a saving throw.\n\n**Effect** The result of the saving throw is improved one degree. The Lantern King can't Fortune's Friend for 1d4 rounds."

  - name: "Lantern King's Glow"
    desc: " (aura,light,primal) The Lantern King illuminates his aura with bright light. At the start of his turn, this aura attempts to counteract any ongoing darkness effect in the aura (counteract check +44). The Lantern King can suppress or activate this aura as a free action."

  - name: "Mocking Laughter"
    desc: " (aura,emotion,incapacitation,mental,primal) 30 feet. Whenever a creature misses the Lantern King with an attack or fails a skill check or saving throw, the creature is overtaken by overwhelming mirth at its mistake, as [[Spells/Laughing Fit|Laughing Fit]] (DC 45 Will check save). The creature is thereafter temporarily immune to mocking laughter for 1 hour."

  - name: "Reactive"
    desc: "  The Lantern King gains an additional reaction at the start of his turn, but he can use this additional reaction only to take a reaction he hasn't already taken since the end of his previous turn."

attacks:
  - name: ""

  - name: "Primal Innate Spells"
    desc: "DC 48, attack +40; __10th __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Primal Phenomenon|Primal Phenomenon]]_; __9th __  _[[Spells/Disjunction|Disjunction]]_, _[[Spells/Illusory Creature|Illusory Creature]]_, _[[Spells/Falling Stars|Meteor Swarm]]_; __8th __  _[[Spells/Illusory Object|Illusory Object]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Sunburst|Sunburst]]_, _[[Spells/Teleport|Teleport]]_, _[[Spells/Wall of Fire|Wall of Fire]]_; __7th __  _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Prismatic Spray|Prismatic Spray (At Will)]]_\n__Cantrips__  __(10th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Light|Light]]_, _[[Spells/Produce Flame|Produce Flame]]_, _[[Spells/Read Aura|Read Aura]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Commune with Nature_, _Control Weather_, _Create Demiplane_, _Fantastic Facade_, _Freedom_, _Geas_, _Primal Call_"

  - name: "Adjust Temperature"
    desc: "`pf2:1` (primal) The Lantern King adjusts the temperature of his flames. He shifts from orange to blue, and his Strikes inflict cold damage until he takes this action again to switch back to fire damage."

  - name: "Blindness"
    desc: "  A creature damaged by the Lantern King's blinding beam Strike must make a DC 48 Fortitude check save. If the Strike was a critical hit, the save's result is worsened one degree.\n* * *\n\n**Critical Success** The creature is unaffected by blindness.\n\n**Success** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Failure** The creature is [[Conditions/Blinded|Blinded]] for 1 minute. At the end of each of its turns, the creature can attempt a DC 48 Fortitude check save to end this blindness early.\n\n**Critical Failure** The creature is blinded permanently."

  - name: "Change Shape"
    desc: " (concentrate,polymorph,primal) The Lantern King can take on the appearance of any fey or humanoid, but he typically does so only to trick and confuse creatures. He loses his searing rune and blinding beam Strikes, but he gains a melee fist Strike that inflicts 4d8 + 19 bludgeoning damage."

  - name: "Drain Luck"
    desc: " (curse,mental,misfortune,primal) When the Lantern King damages a creature with his searing rune Strike, he drains the creature's luck. The creature must succeed at a DC 48 Will check save or gain a -1 status penalty to all checks; it is then temporarily immune to Drain Luck for 1 round. Further damage dealt by the Lantern King's searing rune Strikes increases the status penalty by 1 on a failed save to a maximum status penalty of -4. This status penalty is reduced by one every time the affected creature achieves a critical success on a die roll against a creature that is at least equal to them in level, but otherwise is permanent until removed.\n\n[[Bestiary Effects/Effect_ Drain Luck|Effect: Drain Luck]]"

  - name: "Playful Switch"
    desc: "`pf2:1` (primal,teleportation) The Lantern King targets two creatures within 60 feet, causing each to become surrounded by glowing runes. The Lantern King attempts a single Thievery check against each target's Reflex DC. The Lantern King can't use Playful Switch again for 1 round.\n* * *\n\n**Critical Success** If the Thievery check achieves a critical success against both targets, they swap places and are both [[Conditions/Stunned|Stunned 1]]. Each creature must be able to fit into their new spaces or the effect fails.\n\n**Success** If the Thievery check achieves a success against both targets (or a critical success on one and a success on another), the two targets swap places. Each creature must be able to fit into their new spaces or the effect fails.\n\n**Failure** If the Thievery check fails against either target, neither target is affected.\n\n**Critical Failure** As failure, but both creatures are temporarily immune to Playful Switch for 24 hours."

  - name: "Prismatic Burst"
    desc: "`pf2:r`  **Trigger** A creature achieves a critical hit against the Lantern King or damages it with a cold iron weapon.\n\n**Effect** The Lantern King casts [[Spells/Prismatic Spray|Prismatic Spray]]."
 
```

```encounter-table
name: Avatar of the Lantern King
creatures:
  - 1: Avatar of the Lantern King
```


Eldest of laughter, mischief, and transformation

The Lantern King is one of the Eldest-a pantheon of demigods whose rule over the First World is one of capriciousness that can be at times playful, enigmatic, bizarre, or even downright mean. For the most part, the Lantern King's plots and shenanigans tilt toward the cruel, and while he's long been a master at riding the proverbial razor's edge between mischief and outright sadism (if only by conserving his cruelest plans for those who invite that cruelty by being cruel themselves, as in the case of Nyrissa), his latest actions have certainly drawn the notice of the other Eldest. As such, they have largely distanced themselves from him, and as a result of this, any defeat the PCs deal to him in this adventure goes not only unpunished by the Lantern King's demigod siblings but will even be enforced, in a manner of speaking, by the other Eldest so that the Lantern King won't seek continued revenge against the PCs for their victories. Whether or not this also serves to teach the capricious eldest a lesson to temper his need for mischief with occasional bouts of patience and even mercy, only time can tell.

The Lantern King's direct interactions with the PCs in this campaign are via an avatar-a powerful proxy created from himself to rule over the Lantern Kingdom. While this avatar isn't as powerful as the Lantern King himself, it remains the single most dangerous foe the party faces in Kingmaker. As a demigod, the Lantern King is an even more dangerous foe, equivalent in power to a 29th-level creature and possessing abilities beyond the scope of the core experience in the _Pathfinder Roleplaying Game_. Some of these abilities, such as the power to manipulate reality, to create powerful artifacts like the _Apology_, and to build entire demiplane realms like the Hunting Dream or the Lantern Kingdom, manifest during the course of the _Kingmaker Adventure Path_ not as rules content but as story elements the PCs will need to endure-see Chapter 11 of this book for more details.

In combat, the Lantern King's avatar uses flight to remain out of melee for the first several rounds of combat, relying upon his spells to soften up the party before using his Strikes against them. He's fond of taking actions that disrupt, torment, or mock the PCs rather than those specifically tailored to maximize damage. For example, he often uses Playful Switch to swap a flying PC in the air with one who's on the ground and can't fly, or he uses illusions to create false foes or locations that play off of previous failures or embarrassments the PCs may have endured during the campaign itself. By playing the Lantern King's avatar in battle as more of a trickster than a cold-blooded killer, you'll not only enforce his legendary personality upon your players, but you'll also give their characters a bit more of a fighting chance against him in battle. He prefers to hold [[Spells/Primal Phenomenon|Primal Phenomenon]] in reserve to recover from an unwanted condition or situation, and as he realizes the PCs are dangerous foes, he abandons "playful tactics" for more serious or tactical decisions aimed toward defeating the party rather than toying with them.

While the Lantern King faces no lasting inconvenience if his avatar is slain, the sting of such a defeat is enough to compel the avatar to back down and ask for a truce if the PCs reduce him to fewer than 75 Hit Points. If the PCs agree to a truce, the avatar compliments their prowess and promises to turn his attentions away from the Stolen Lands. Furthermore, he agrees to any additional terms the PCs ask for, provided they are within his ability to grant. This includes restoring Nyrissa's place and realm to the First World (although he cannot provide further information about her lost lover) and unmaking _Briar_ to restore her capacity to love.
