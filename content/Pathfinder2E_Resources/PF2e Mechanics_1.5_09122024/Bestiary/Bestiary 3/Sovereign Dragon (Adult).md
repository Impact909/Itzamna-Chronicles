---
title: "Sovereign Dragon (Adult)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w96OIigBxzlA3m5f" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Sovereign Dragon (Adult)"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sovereign Dragon (Adult)"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[earth]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Common, Diabolic, Draconic, Empyrean, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +31, Deception: +28, Diplomacy: +32, Intimidation: +30, Occultism: +25, Society: +27, Stealth: +25, Survival: +27"
abilityMods: [8, 4, 6, 4, 6, 7]
speed: 50 feet,  fly 150 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +23, __Will__ +29; +1 status to all saves vs. magic"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  paralyzed,  sleep; __Resistances__ mental 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 34 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Violent Retort"
    desc: "`pf2:r`  **Trigger** A creature within the sovereign dragon's reach critically hits the dragon\n* * *\n\n**Effect** The sovereign dragon makes a claw or tail Strike against the creature, after applying all the effects of the critical hit to the dragon."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical, reach 15 feet)\n__Damage__  3d10 + 14 piercing 2d6 mental"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 10 feet)\n__Damage__  3d10 + 14 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (magical, reach 25 feet)\n__Damage__  3d10 + 14 bludgeoning plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +30; __8th __  _[[Spells/Shape Stone|Shape Stone]]_, _[[Spells/Suggestion|Suggestion]]_, _[[Spells/Wall of Stone|Wall of Stone]]_; __7th __  _[[Spells/Suggestion|Suggestion (At Will)]]_; __2nd __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Good or Evil Only)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (mental,occult) The dragon unleashes a roar charged with psychic energy, dealing 16d6 mental damage in a 40-foot cone (DC 36 Will check save).\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "Coiling Frenzy"
    desc: "`pf2:2`  The dragon makes one claw Strike and one tail Strike in either order, each against the same target. If either Strike hits, the dragon automatically [[Conditions/Grabbed|Grabs]] the target."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Breath Weapon whenever they score a critical hit with a Strike."

  - name: "Gleaming Armor"
    desc: "`pf2:1` (light,occult) **Frequency** once per hour\n* * *\n\n**Effect** The dragon's golden armor glows with a protective golden light. The dragon gains a +2 status bonus to AC and resistance 15 to energy damage. Each enemy in a 20-foot emanation must succeed at a DC 36 Fortitude check save or be [[Conditions/Dazzled|Dazzled]].\n\nAll these effects last until the end of the dragon's next turn.\n\n[[Bestiary Effects/Effect_ Gleaming Armor|Effect: Gleaming Armor]]"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  3d10+8 bludgeoning, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Inspire Envoy"
    desc: "`pf2:2` (mental,occult) **Frequency** once per day\n* * *\n\n**Effect** The dragon chooses a mortal they've observed performing an exceptional act and offers their august blessing in exchange for the creature carrying out a specific directive, such as defeating a tyrant or protecting a sacred site.\n\nIf the creature agrees, until its next daily preparations, it gains a +1 status bonus to the dragon's choice of attack rolls, AC, or all of the following: Perception, Will saves, and Charisma-based skill checks.\n\nThe dragon can Dismiss this benefit by spending a single action (that has the concentrate trait), which they're swift to do if the mortal dares to defy the dragon's directive.\n\n[[Bestiary Effects/Effect_ Inspire Envoy|Effect: Inspire Envoy]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sovereign Dragon (Adult)
creatures:
  - 1: Sovereign Dragon (Adult)
```



The most well-known of imperial dragons due to their deep involvement with mortals, the sovereign dragons' name comes from their mandate of selecting rulers-but at some point, the dragons themselves joined the list of worthy candidates. Other imperial dragons suspect the sovereign dragons offered their connection to the elemental cycle to attain forbidden magic, evidenced by their lack of any vulnerability to wood or ability to feed on fire, despite being creatures of the earth.

Most hesitate to question the sovereigns' authority. While some appreciate their impartial nature, others fault this adherence to neutrality. Regardless, the sovereign dragons' charm and centuries of experience in subtle manipulation have made them exceptional negotiators.

Almost all sovereign dragons appear gold in color. Their hair ranges from common colors found among humans to bright reds, greens, or blues. They're the only dragons with five digits per claw, a mark of special importance. Other imperial dragons dismiss this claim to status and instead tease the sovereign dragons over their need to wear armor, even while in their draconic forms.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
