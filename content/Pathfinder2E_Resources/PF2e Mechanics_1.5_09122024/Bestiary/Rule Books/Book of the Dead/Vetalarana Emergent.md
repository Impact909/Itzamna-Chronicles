---
title: "Vetalarana Emergent"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Pg0Nrfm8giUdrxKa" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Vetalarana Emergent"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Vetalarana Emergent"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[vampire]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Thoughtsense (Precise) 100 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +18, Intimidation: +16, Occultism: +13, Stealth: +17"
abilityMods: [6, 5, 4, 3, 4, 4]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +17, __Will__ +16"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, fast healing 10, mental rebirth, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep; __Resistances__ mental 10, physical 10 (except cold iron)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|+1 Striking Crossbow]]"
  - name: "[[Bestiary Ability Glossary/Thoughtsense|Thoughtsense (Precise) 100 feet]]"
    desc: "  Thoughtsense allows a monster to sense all non-mindless creatures at the listed range."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 10]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Vampire, Vetalarana, Basic) Mental Rebirth|Mental Rebirth]]"
    desc: " (curse,incapacitation,mental,occult) Unlike most other undead, a vetalarana isn't destroyed when they reach 0 HP. Instead, their body is destroyed, crumbling to ash, and their mind is immediately transferred into a creature they rendered comatose through Drain Thoughts. This creature must be within 1 mile; if no such creature is in range, the vetalarana is destroyed. The creature becomes controlled by the vetalarana and loses the stupefied and [[Conditions/Unconscious|Unconscious]] conditions. If the creature controlled by a vetalarana in this way is killed, the vetalarana's mind transfers to another creature within 1 mile who they rendered comatose through Drain Thoughts.\n\nAfter 1d6 days of being controlled, the controlled creature dies, and its body transforms into that of the vetalarana who rendered it comatose."

  - name: "[[Creature Family Ability Glossary/(Vampire, Vetalarana, Basic) Vetalarana Vulnerabilities|Vetalarana Vulnerabilities]]"
    desc: "  All vetalaranas possess the following weaknesses.\n\n*   **Barred Senses** A vetalarana can't see or sense through force effects or cold iron, and their mind can't penetrate force effects or cold iron. Such barriers can prevent the transference of a vetalarana's mind through Mental Rebirth.\n*   **Revulsion** A vetalarana delights in consuming memories and secrets, and is disgusted by those who share such sensitive tidbits openly. A vetalarana can't voluntarily come within 10 feet of a creature loudly voicing their intimate personal secrets or most cherished memories aloud. Speaking such information aloud with conviction is a single action that has the auditory, concentrate, and linguistic traits, and protects the creature until the start of its next turn. A vetalarana that involuntarily comes within 10 feet of a creature sharing such information gains the [[Conditions/Fleeing|Fleeing]] condition until they're 10 feet or farther from the creature. After 1 round of being exposed to the secrets of a creature, a vetalarana can attempt a DC 25 Will check save as a single action, which has the concentrate trait. On a success, they overcome their revulsions for 1d6 rounds (or 1 hour on a critical success).\n*   **Vulnerable to Brain Destruction** A vetalarana whose brain has been destroyed, or is reduced to 0 HP while unable to take mental actions, can't use Mental Rebirth."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d8 + 9 slashing plus grab"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+20 (magical, range increment 120 feet, reload 1)\n__Damage__  2d8 + 3 piercing"

  - name: "Anticipatory Attack"
    desc: "  The vetalarana emergent uses consumed memories to anticipate their prey's movements. The vetalarana emergent's Strikes deal an additional 1d8 precision damage to creatures stupefied due to the vetalarana's Drain Thoughts."

  - name: "[[Creature Family Ability Glossary/(Vampire, Vetalarana, Basic) Drain Thoughts|Drain Thoughts]]"
    desc: "`pf2:1` (mental,occult) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the vetalarana's reach\n* * *\n\n**Effect** The vetalarana seizes a creature and consumes its memories. This requires an Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions. The victim is [[Conditions/Stupefied|Stupefied 1]], and the vetalarana regains 10 healing HP, gaining any excess as temporary Hit Points. Draining Thoughts from a creature that is already stupefied doesn't restore any HP to the vetalarana but increases the victim's stupefied value by 1. Additionally, the vetalarana views one of the victim's memories.\n\nA victim's stupefied condition value decreases by 1 every week.\n\nA victim that becomes stupefied 5 in this way is rendered comatose, becoming permanently [[Conditions/Unconscious|Unconscious]]. As long as the vetalarana lives, a comatose victim can't regain consciousness, and its stupefied condition doesn't decrease."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Vetalarana Emergent
creatures:
  - 1: Vetalarana Emergent
```



Vetalarana vampires feed on the emotions, thoughts, and memories of others. Although they are capable of feeding on animals, beings of the planes, and other intelligent undead, only the thoughts of an intelligent, living humanoid bring a vetalarana any sense of satisfaction. Slender and pale, with sunken cheeks and exceptionally long nails, vetalaranas become flushed with color and life after feeding on particularly potent emotions and thoughts, enabling some to pass as living for a short time.

A vetalarana is created when a person with psychic or occult abilities dies in denial of their death, refusing to pass on to the afterlife but unable to retain their grip on life. As their spirit has no cause left undone nor debt to settle, these tenacious souls rise not as ghosts but as vetalaranas, a formidable and tenacious mind animating their own corpse in a mockery of life.

A vetalarana's predations inevitably turn their victims into living husks, incapable of thought and devoid of any spark of personality. These victims fall into a senseless stupor, comatose but still living, without identity or memories. If a vetalarana is killed, they can occupy one of these comatose husks, while more powerful vetalaranas can control them like living puppets.

When a vetalarana is destroyed, all of their comatose victims are immediately freed. Most often, these people regain consciousness as amnesiacs whose memories return over time—taking at least months but sometimes as long as decades. These returned memories are fragmented and often jumbled with the thoughts of others the vetalarana fed upon. If a victim served as a failed host or was frequently controlled while comatose, a sliver of the vetalarana's corrupted thoughts remain in the victim's mind. These tainted victims recover much faster than their fellows, regaining their memories in record time and transforming into a new vetalarana soon after.

A vetalarana emergent is inexperienced and ravenous, often caring more for the consumption of thoughts than the quality of the thoughts and memories consumed. These undead gluttons gorge themselves on memories, leaving a crowd of addled and terrified victims in their wake. Experienced emergents are cannier than their newly risen kin, stalking their chosen victims and being sure to abduct, kill, or render their victims comatose after draining their memories to ensure no witnesses remain to reveal the presence of a vetalarana.
