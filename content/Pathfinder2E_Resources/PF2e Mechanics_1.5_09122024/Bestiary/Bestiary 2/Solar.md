---
title: "Solar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iCakFhYqNozoM56N" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/23
statblock: inline
name: "Solar"
level: 23
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Solar"
level: "Creature 23"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
modifier: 40
perception:
  - name: "Perception"
    desc: "+40; Darkvision, Truesight"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Arcana: +38, Athletics: +43, Diplomacy: +43, Religion: +43, Stealth: +36, Survival: +46"
abilityMods: [10, 6, 8, 5, 9, 10]
speed: 35 feet,  fly 100 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 49
armorclass:
  - name: AC
    desc: "49; __Fort__ +40, __Ref__ +34, __Will__ +37; +1 status to all saves vs. magic"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500, regeneration 20 (deactivated by unholy); __Weaknesses__ unholy 25"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+3 Major Striking Greatsword]], [[Equipment/Longbow|+3 Major Striking Longbow]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Aura of Protection"
    desc: " (aura,divine) 20 feet. Allies in the solar's aura gain a +2 status bonus to AC against evil creatures and a +2 status bonus to saves against effects from evil creatures. The bonus increases to +4 against control by evil creatures and attacks by evil summoned creatures. When the solar or an ally is hit by an attack from a creature in the aura, that foe must succeed at a DC 43 Will check save or be blinded for 1 minute (this is an incapacitation effect). It's then temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Aura of Protection (Solar)|Effect: Aura of Protection (Solar)]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Holy Greatsword"
    desc: "+44 (holy, magical, versatile p)\n__Damage__  4d12 + 22 slashing 1d6 spirit"

  - name: "**Ranged** `pf2:1` Holy Longbow"
    desc: "+40 (deadly d10, holy, magical, propulsive, range increment 100 feet, volley 30 ft.)\n__Damage__  4d8 + 17 piercing plus arrow-of-mortality 1d6 spirit plus arrow-of-mortality"

  - name: "Divine Innate Spells"
    desc: "DC 46, attack +36; __10th __ (3 slots) _[[Spells/Charm|Charm]]_, _[[Spells/Power Word Stun|Power Word Stun]]_, _[[Compendium.pf2e.spells-srd.Item.OyFCwQuw8XRazsNr|Remove Curse]]_, _[[Compendium.pf2e.spells-srd.Item.RneiyehRO6f7LP44|Remove Disease]]_, _[[Spells/Revival|Revival]]_; __9th __ (6 slots) _[[Spells/Dispel Magic|Dispel Magic (At will)]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Overwhelming Presence|Overwhelming Presence]]_, _[[Spells/Power Word Blind|Power Word Blind]]_, _[[Spells/Power Word Kill|Power Word Kill]]_, _[[Spells/Sunburst|Sunburst]]_; __7th __ (2 slots) _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Clear Mind|Remove Fear (At will)]]_; __6th __ (1 slots) _[[Spells/Restoration|Restoration (At will)]]_; __5th __ (2 slots) _[[Spells/Breath of Life|Breath of Life]]_, _[[Spells/Death Ward|Death Ward]]_; __4th __ (1 slots) _[[Spells/Planar Tether|Dimensional Anchor (At will)]]_; __2nd __ (1 slots) _[[Spells/Invisibility|Invisibility]]_\n__Constant__  __(10th)__ _[[Spells/Detect Alignment|Detect Alignment (Evil only)]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Angelic Messenger_, _Animate Object_, _Call Spirit_, _Freedom_, _Imprisonment_, _Resurrect_"

  - name: "Animate Weapon"
    desc: "`pf2:r`  **Trigger** The solar hits with a melee weapon Strike while Animate Weapon is not already in effect\n* * *\n\n**Effect** The solar's weapon leaps into the air and moves with the solar as if held with both hands. The weapon gains the effects of the dancing weapon rune for 1 minute."

  - name: "Arrow of Mortality"
    desc: "  The solar doesn't need to provide ammunition for their bow. When they draw their bow, they create a magical arrow of light that sheds bright light in a 20-foot radius until the end of the solar's next turn.\n\nOn a critical hit with the arrow, if the target has 75 or fewer Hit Points after taking the damage, it drops to 0 Hit Points and becomes [[Conditions/Dying|Dying 1]] (or, if it was already dying, increases its dying value by 3)."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The solar can take on the appearance of any Small or Medium humanoid. This doesn't change their Speed or Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Holy Armaments"
    desc: " (divine) Any weapon gains the effect of a _[[Equipment/Holy|Holy]]_ property rune while a solar wields it."
 
```

```encounter-table
name: Solar
creatures:
  - 1: Solar
```



Solars are among the greatest of all angels, ranking just below empyreal lords. Many solars serve at the right hand of a deity or champion a cause that benefits an entire world. Most archangels resemble humanoids, but not all-they can adopt more unusual forms as needed. A typical solar is about 9 feet tall and weighs about 500 pounds, with a commanding voice that is impossible to ignore. Most have silvery or golden skin.

Solars are legendary trackers; the most masterful of them are said to be able to follow the centuries-old passage of a pit fiend flying through the Astral Plane.

* * *

Angels are benevolent messengers who aid good forces in the fight against evil. Each angel has a special aura that assists in their individual tasks, and each angel delivers certain types of messages and performs other duties for the angelic hosts. While most angels live in the enlightened realm of Nirvana, some serve the forces of Heaven and Elysium, especially in the case of the angel empyreal lords within those two realms. Angels organize themselves into choirs depending on their ranks and roles.
