---
title: "Nosferatu Malefactor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6SsUImYCWGSkuFbQ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Nosferatu Malefactor"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Nosferatu Malefactor"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[vampire]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Aklo, Common, Necril; telepathy 60 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Arcana: +21, Athletics: +19, Deception: +17, Intimidation: +19, Stealth: +23"
abilityMods: [5, 7, 3, 7, 5, 3]
speed: 30 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +17, __Ref__ +21, __Will__ +19"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, fast healing 10, void healing, plagued coffin restoration; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ physical 10 (except magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 60 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Nosferatu Vulnerabilities|Nosferatu Vulnerabilities]]"
    desc: "  *   **Revulsion** A nosferatu can't voluntarily come within 10 feet of brandished garlic or a brandished religious symbol of a non-evil deity. To brandish garlic or a religious symbol, a creature must Interact to do so for 1 round (similar to Raising a Shield). If the nosferatu involuntarily comes within 10 feet of an object of their revulsion, they gain the [[Conditions/Fleeing|Fleeing]] condition, running from the object of their revulsion until they end an action beyond 10 feet. After 1 round of being exposed to the subject of their revulsion, a nosferatu can attempt a DC 25 Will check save as a single action, which has the concentrate trait. On a success, they overcome their revulsions for 1d6 rounds (or 1 hour on a critical success).\n*   **Stake** A magical wooden stake (such as one affected by a weapon potency rune, magic weapon, or similar magic) driven through the nosferatu's heart drops the nosferatu to 0 HP and prevents them from healing above 0 HP, even in their coffin. Staking a nosferatu requires 3 actions and works only if the nosferatu is [[Conditions/Unconscious|Unconscious]]. If the stake is removed, the nosferatu can heal above 0 HP again, and if they're in their coffin, the 1-hour rest period begins once the stake is removed. If the nosferatu's head is severed and anointed with _[[Equipment/Holy Water|Holy Water]]_ while the stake is in place, the nosferatu is destroyed.\n*   **Sunlight** If exposed to direct sunlight, a nosferatu immediately becomes [[Conditions/Slowed|Slowed 1]]. The slowed value increases by 1 each time the nosferatu ends their turn in sunlight, and the condition ends when they're no longer in sunlight. If the nosferatu loses all their actions in this way, they're destroyed."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Plagued Coffin Restoration|Plagued Coffin Restoration]]"
    desc: " (divine,void) Unlike other undead, a nosferatu isn't destroyed at 0 HP. Instead, they disperse into an immense number of individual rats heading in every direction in an attempt to return to their coffin. If even a single rat reaches the coffin, the nosferatu can recover. A nosferatu regains their strength through resting in earth taken from the grave of a creature who died of plague. If their body rests in their earth-filled coffin for 1 hour, the nosferatu gains 1 HP, after which their fast healing begins to function normally. If the coffin doesn't contain this plagued grave dirt, they instead need to rest in their coffin for 1 day before they gain 1 HP and regain their fast healing."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+23 (finesse)\n__Damage__  2d12 + 11 piercing plus vampire-nosferatu-drink-blood"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, finesse)\n__Damage__  2d10 + 11 piercing plus vampire-nosferatu-plague-of-ancients"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +21; __6th __  _[[Spells/Dominate|Dominate (At Will) (See Dominate)]]_; __5th __  _[[Spells/Telekinetic Haul|Telekinetic Haul (x3)]]_"

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The nosferatu transforms into a swarm of pale-gray rats. They gain a land Speed of 30 feet and a climb Speed of 10 feet, and they become Large. Each enemy in the swarm's space takes 2d10 piercing damage and must attempt a DC 29 Reflex check save with a high DC for the creature's level. A creature that fails its save is exposed to plague of ancients.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Command Thrall|Command Thrall]]"
    desc: " (auditory,divine,mental) **Requirements** One of the nosferatu's thralls is present and can hear the nosferatu\n* * *\n\n**Effect** The nosferatu gives a single command to one of their thralls, which the thrall follows to the best of its ability during its next turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Dominate|Dominate]]"
    desc: "`pf2:2` (divine,incapacitation,mental,visual) The nosferatu can cast [[Spells/Dominate|Dominate]] at will as a divine innate spell. Casting it requires staring into the target's eyes, giving the spell the visual trait (DC 29 Will check). The save DC uses a high DC for the nosferatu's level, and a creature that succeeds is temporarily immune to that nosferatu's Dominate for 24 hours. Fully destroying the nosferatu ends the domination, but merely reducing the nosferatu to 0 HP is insufficient to break the spell."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Drink Blood|Drink Blood]]"
    desc: "`pf2:1` (divine) **Requirements** The nosferatu's last action was a successful fangs Strike\n* * *\n\n**Effect** The nosferatu sinks their fangs into the targeted creature to drink its blood. This requires an Athletics check check against the creature's Fortitude DC. On a success, the creature becomes [[Conditions/Drained|Drained 1]], and the nosferatu regains 13 healing HP, gaining any excess HP as temporary Hit Points. Drinking Blood from a creature that's already drained doesn't restore any HP to the nosferatu, but increases the creature's drained condition value by 1. A nosferatu can also consume blood that's been emptied into a vessel for sustenance, but they gain no HP from doing so.\n\nThe target creature's drained condition value decreases by 1 per week. A blood transfusion, which requires a successful DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drained value by 1 after 10 minutes."

  - name: "[[Creature Family Ability Glossary/(Vampire, Nosferatu) Plague of Ancients|Plague of Ancients]]"
    desc: " (disease,virulent) **Saving Throw** DC 29 Fortitude check (use a high DC for the nosferatu's level)\n* * *\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)\n\n**Stage 3** [[Conditions/Doomed|Doomed 1]], [[Conditions/Drained|Drained 3]], and [[Conditions/Enfeebled|Enfeebled 3]] (1 day)\n\n**Stage 4** [[Conditions/Doomed|Doomed 2]], drained 3, and enfeebled 3 (1 day)\n\n**Stage 5** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 6** death"
 
```

```encounter-table
name: Nosferatu Malefactor
creatures:
  - 1: Nosferatu Malefactor
```



Twisted by age and eternal hunger, nosferatu malefactors spread plague in their wake and yearn for mortal blood.

* * *

Among the most ancient of vampires are the nosferatus, twisted remnants of mortals who died in great plagues of old. Perhaps because of their age, nosferatus can no longer create more of their kind. Yet they still lurk among the living, manipulating the hearts and minds of their prey to either serve them beyond the limits of natural life or to become sustenance for the nosferatu like so many others before.
