---
title: "Deimavigga"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3NUSHD02LDcJ39aA" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Deimavigga"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Deimavigga"
level: "Creature 17"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Greater Darkvision"
languages: "Chthonian, Common, Diabolic, Draconic, Empyrean; indominable oration, telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Deception: +34, Diplomacy: +36, Intimidation: +30, Religion: +30, Society: +27, Stealth: +33"
abilityMods: [7, 8, 6, 4, 7, 9]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +27, __Ref__ +29, __Will__ +32; +1 status to all saves vs. magic"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Immunities__  fire; __Weaknesses__ holy 15; __Resistances__ physical 15 (except silver)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Full Plate|+2 Resilient Glamered Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Indomitable Oration"
    desc: "  Any creature capable of comprehending speech understands the deimavigga, as if they constantly spoke in all languages at once."

abilities_mid:
  - name: ""
  - name: "Whispers of Discord"
    desc: "`pf2:r`  **Trigger** A creature within 60 feet is targeted by a spell that would restore Hit Points or provide a status bonus (the deimavigga automatically recognizes such effects).\n* * *\n\n**Effect** The deimavigga whispers disturbing lies, audible only to the target, to shake the target's faith in the spell's caster. The target must attempt a DC 43 Will check save.\n* * *\n\n**Critical Success** The target disbelieves the lies and receives the intended benefit of the spell; the target becomes temporarily immune to Whispers of Discord for 24 hours.\n\n**Success** As critical success, but the target isn't temporarily immune.\n\n**Failure** The spell fails to affect the target. The target refuses all aid from that caster for 1 round and doesn't count as the caster's ally.\n\n**Critical Failure** As failure, but the duration is 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, finesse, magical, unholy)\n__Damage__  3d8 + 15 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +34; __9th __  _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Dominate|Dominate]]_, _[[Spells/Illusory Scene|Illusory Scene (At Will)]]_; __7th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Scrying|Scrying]]_, _[[Spells/Stupefy|Touch of Idiocy (At Will)]]_, _[[Compendium.pf2e.spells-srd.Item.hkfH9Z53hPzcOwNB|Veil]]_, _[[Spells/Warp Mind|Warp Mind]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __3rd __  _[[Spells/Dream Message|Dream Message (At Will)]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Boundless Reach"
    desc: " (divine,teleportation) A deimavigga's razor-sharp claws can slice through reality, allowing them to make claw Strikes and use spells with a range of touch against any creature they can see directly or via divination magic.\n\nA creature targeted this way can retaliate until the start of the deimavigga's next turn; it can target the devil's claws as if the devil were physically present and adjacent to the target, though the claws are [[Conditions/Concealed|Concealed]]."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The deimavigga can take on the appearance of any humanoid. This doesn't change their Speed or attack and damage bonuses with Strikes but might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Whisper Earworm"
    desc: "`pf2:1` (divine,emotion,mental) The deimavigga whispers a terrifying multiversal truth to one adjacent creature, shaking its faith in reality and divinity. The target must attempt a DC 43 Will check save. Celestials and fiends gain a +2 status bonus to this save.\n* * *\n\n**Critical Success** The target is unaffected and temporarily immune to Whisper Earworm for 24 hours.\n\n**Success** The target is unaffected.\n\n**Failure** The next time the target rests, it ruminates on the deimavigga's words instead of sleeping or otherwise resting and awakens [[Conditions/Fatigued|Fatigued]]. The target also becomes [[Conditions/Drained|Drained 1]] and [[Conditions/Stupefied|Stupefied 1]] until it's no longer fatigued.\n\n**Critical Failure** As failure, but [[Conditions/Drained|Drained 2]]. After this rest, the target must attempt another DC 43 Will check save. On a failure, the target becomes [[Conditions/Stupefied|Stupefied 2]] and takes a -4 status penalty to Will saves against effects from evil creatures. These effects last until the target unlearns the truth spoken by the deimavigga, requiring a [[Spells/Rewrite Memory|Rewrite Memory]] spell, other means of modifying their memory, or powerful magic such as [[Spells/Wish|Wish]]."
 
```

```encounter-table
name: Deimavigga
creatures:
  - 1: Deimavigga
```



As masters of cold, calculated logic and perfectly timed proselytization, the loathsome deimaviggas seek to set friend against friend and turn the faithful from their beliefs at every opportunity.

* * *

There are countless legions of lawful fiends in the nine layers of Hell, warring against the celestial planes and scouring the Material Plane for souls to corrupt.
