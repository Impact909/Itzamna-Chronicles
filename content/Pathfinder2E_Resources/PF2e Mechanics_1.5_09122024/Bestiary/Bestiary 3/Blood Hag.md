---
title: "Blood Hag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KN4JBaQOaunmXFj1" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/hag
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Blood Hag"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Blood Hag"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[hag]]
trait_04: [[humanoid]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +16, Deception: +19, Diplomacy: +17, Occultism: +14, Stealth: +17"
abilityMods: [4, 5, 2, 2, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +17, __Will__ +17"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  bleed; __Weaknesses__ cold iron 10; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "Bloodsense (Imprecise) 90 feet"
    desc: "  A blood hag can sense the presence of blood and creatures with blood. She can tell the difference between spilled blood and the blood within a living creature."

  - name: "Borrowed Skin"
    desc: "  A blood hag wears a covering of skin stolen from a humanoid creature she has killed, hiding her true form and granting her the effects of a 4th-rank [[Spells/Disguise Magic|Disguise Magic]], with herself as the primary target and the creature whose skin she is wearing as the secondary target.\n\nSpreading coarse salt inside the skin prevents the hag from putting it back on, forcing her to keep her fiery form until she kills another humanoid and spends 1 hour turning it into a new disguise."

  - name: "[[Bestiary Ability Glossary/Coven|Coven]]"
    desc: " (mental,occult) A blood hag adds [[Spells/Death Ward|Death Ward]], [[Spells/Fiery Body|Fiery Body]], and [[Spells/Nightmare|Nightmare]] to her coven's spells.\n* * *\n\nThis monster can form a coven with two or more other creatures who also have the coven ability. This involves performing an 8-hour ceremony with all prospective coven members. After the coven is formed, each of its members gains elite adjustments, adjusting their levels accordingly. Coven members can sense other members' locations and conditions by spending a single action, which has the concentrate trait, and can sense what another coven member is sensing as a two-action activity, which has the concentrate trait as well.\n\nCovens also grant spells and rituals to their members, but these can be cast only in cooperation between three coven members who are all within 30 feet of one another. A coven member can contribute to a coven spell with a single action that has the concentrate trait. If two coven members have contributed these actions within the last round, a third member can cast a coven spell on her turn by spending the normal spellcasting actions. A coven can cast its coven spells an unlimited number of times but can cast only one coven spell each round. All covens grant the 8th-rank [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]] spell and all the following spells, which the coven can cast at any rank up to 5th: [[Spells/Augury|Augury]], [[Spells/Charm|Charm]], [[Spells/Clairaudience|Clairaudience]], [[Spells/Clairvoyance|Clairvoyance]], [[Spells/Dream Message|Dream Message]], [[Spells/Illusory Disguise|Illusory Disguise]], [[Spells/Illusory Scene|Illusory Scene]], [[Spells/Scouting Eye|Scouting Eye]], and [[Spells/Talking Corpse|Talking Corpse]]. Individual creatures with the coven ability also grant additional spells to any coven they join. A coven can also cast the [[Spells/Control Weather|Control Weather]] ritual, with a DC of 23 instead of the standard DC.\n\nIf a coven member's departure or death brings the coven below three members, the remaining members keep their elite adjustments for 24 hours, but without enough members to contribute the necessary actions, they can't cast coven spells."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (agile)\n__Damage__  2d8 + 7 slashing plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 ()\n__Damage__  2d12 + 7 piercing"

  - name: "**Ranged** `pf2:1` Firebolt"
    desc: "+19 (agile, fire, range 30 feet)\n__Damage__  2d10 + 8 fire"

  - name: "Occult Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Charm|Charm]]_, _[[Spells/Sleep|Sleep (x3)]]_"

  - name: "Coven Spells"
    desc: "DC 23, attack +15; __8th __  _[[Spells/Cursed Metamorphosis|Baleful Polymorph]]_; __7th __  _[[Spells/Fiery Body|Fiery Body]]_; __5th __  _[[Spells/Augury|Augury]]_, _[[Spells/Charm|Charm]]_, _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Death Ward|Death Ward]]_, _[[Spells/Dream Message|Dream Message]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Scouting Eye|Prying Eye]]_, _[[Spells/Talking Corpse|Talking Corpse]]_; __4th __  _[[Spells/Nightmare|Nightmare]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Assume Fiery Form"
    desc: "`pf2:3` (concentrate,fire,occult,polymorph) The blood hag removes her borrowed skin and transforms into a brilliant ball of fire.\n\nShe becomes amorphous, gains the fire trait and a fly Speed of 60 feet, becomes immune to fire, and emits light as a torch. She loses her melee Strikes and can't Drain Blood, but she deals 3d10 fire damage (DC 26 Reflex check save) to each creature that touches her, as well as to each creature that succeeds at a melee Strike against her with an unarmed attack or from an adjacent space.\n\nIf her skin is intact, she can return to her normal form by spending a single action that has the manipulate trait while adjacent to the skin.\n\nThe hag can instead Assume Fiery Form as a single action, bursting through her skin in a blast of flames. Doing so destroys her borrowed skin and deals 9d6 fire damage (DC 26 Reflex check save) in a 20-foot emanation.\n\n[[Bestiary Effects/Effect_ Fiery Form|Effect: Fiery Form]]"

  - name: "Drain Blood"
    desc: "`pf2:1` (occult) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the blood hag's reach\n* * *\n\n**Effect** The hag sinks her fangs into the creature to drink its blood. This requires a successful Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions.\n\nThe victim becomes [[Conditions/Drained|Drained 1]]. The hag regains 15 healing Hit Points, gaining any excess HP as temporary Hit Points that last for 1 hour. Drinking blood from a creature that's already drained doesn't restore any Hit Points to the hag but increases the victim's drained value by 1, killing the victim when it reaches drained 5.\n\nA victim's drained condition decreases by 1 per week. A blood transfusion, which requires a successful DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drained condition by 1 after 10 minutes."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Blood Hag
creatures:
  - 1: Blood Hag
```



Blood hags, also known as soucouyants, infiltrate communities in the guise of young, innocent humanoids. This disguise is more than an illusion, for a blood hag wears the skin of a previous victim to hide her true appearance. During the day, her disguise is almost perfect, especially if the community knows nothing about the person the hag is pretending to be. But after sunset, the creature sheds her skin, hides it in a safe place, and stalks the night to drink the blood that sustains her.

Able to travel quickly in the form of a ball of fire and to slip through keyholes or the slightest crack in a door or window, blood hags feed on sleeping victims then return home before morning to don their stolen skin.

* * *

Foul creatures who appear as wizened old women, hags share little in common with the humanoids they terrorize. They are hateful entities whose greatest joy lies in the corruption and ultimate destruction of anything good and virtuous. Whatever power created the first hags is lost to time, but numerous hag varieties have arisen over the ages, each with their own powers and abilities to spread pain and suffering.
