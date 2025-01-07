---
title: "Sovereign Dragon (Young, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.izrutWwLL35mNQur" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Sovereign Dragon (Young, Spellcaster)"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sovereign Dragon (Young, Spellcaster)"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[earth]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Diabolic, Draconic, Empyrean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +22, Deception: +21, Diplomacy: +25, Intimidation: +23, Occultism: +18, Society: +20, Stealth: +18, Survival: +20"
abilityMods: [7, 3, 5, 3, 5, 6]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +22, __Ref__ +18, __Will__ +24; +1 status to all saves vs. magic"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  paralyzed,  sleep; __Resistances__ mental 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 28 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Violent Retort"
    desc: "`pf2:r`  **Trigger** A creature within the sovereign dragon's reach critically hits the dragon\n* * *\n\n**Effect** The sovereign dragon makes a claw or tail Strike against the creature, after applying all the effects of the critical hit to the dragon."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (reach 10 feet)\n__Damage__  2d8 + 13 piercing 2d6 mental"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile)\n__Damage__  2d8 + 13 slashing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+24 (reach 20 feet)\n__Damage__  2d8 + 13 bludgeoning plus grab"

  - name: "Occult Prepared Spells"
    desc: "DC 29, attack +23; __4th __  _[[Spells/Detect Scrying|Detect Scrying]]_; __3rd __  _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Heroism|Heroism]]_, _[[Spells/Hypnotize|Hypnotic Pattern]]_; __2nd __  _[[Spells/Calm|Calm Emotions]]_, _[[Spells/Translate|Comprehend Language]]_, _[[Spells/Clear Mind|Remove Fear]]_, _[[Spells/Silence|Silence]]_, _[[Spells/Status|Status]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Illusory Disguise|Illusory Disguise]]_, _[[Spells/Sure Strike|True Strike]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Occult Innate Spells"
    desc: "DC 30, attack +22; __6th __  _[[Spells/Shape Stone|Shape Stone]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_; __2nd __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Good or Evil Only)]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (mental,occult) The dragon unleashes a roar charged with psychic energy, dealing 12d6 mental damage in a 30-foot cone (DC 30 Will check save).\n\nThe dragon can't use Breath Weapon again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+10 bludgeoning, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Gleaming Armor"
    desc: "`pf2:1` (light,occult) **Frequency** once per hour\n* * *\n\n**Effect** The dragon's golden armor glows with a protective golden light. The dragon gains a +2 status bonus to AC and resistance 10 to energy damage. Each enemy in a 20-foot emanation must succeed at a DC 30 Fortitude check save or be [[Conditions/Dazzled|Dazzled]].\n\nAll these effects last until the end of the dragon's next turn.\n\n[[Bestiary Effects/Effect_ Gleaming Armor|Effect: Gleaming Armor]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sovereign Dragon (Young, Spellcaster)
creatures:
  - 1: Sovereign Dragon (Young, Spellcaster)
```



The most well-known of imperial dragons due to their deep involvement with mortals, the sovereign dragons' name comes from their mandate of selecting rulers-but at some point, the dragons themselves joined the list of worthy candidates. Other imperial dragons suspect the sovereign dragons offered their connection to the elemental cycle to attain forbidden magic, evidenced by their lack of any vulnerability to wood or ability to feed on fire, despite being creatures of the earth.

Most hesitate to question the sovereigns' authority. While some appreciate their impartial nature, others fault this adherence to neutrality. Regardless, the sovereign dragons' charm and centuries of experience in subtle manipulation have made them exceptional negotiators.

Almost all sovereign dragons appear gold in color. Their hair ranges from common colors found among humans to bright reds, greens, or blues. They're the only dragons with five digits per claw, a mark of special importance. Other imperial dragons dismiss this claim to status and instead tease the sovereign dragons over their need to wear armor, even while in their draconic forms.

* * *

Imperial dragons, namesake of the Dragon Empires and guardians of Tian Xia before humanity arrived, embody five strengthening and counteracting forces. Unlike other true dragons, imperial dragons dive deep into human affairs. Some remain secretive, posing as reclusive hermits, while others keep a high profile, openly ruling factions. Tian cultures in turn venerate the dragons, depicting gods in the form of dragons or claiming ancestry from them. Not all are adored, for plenty of these creatures act wickedly.

**Draconic Cycles**

Five elements underpin the magical powers of imperial dragons, influencing their relationships to all things and, especially, to others of their kind. These elements interlink in two cycles. In the first cycle, each element feeds one other: wood feeds fire, fire feeds earth, earth feeds metal, metal feeds water, and water feeds wood. In the second cycle, each element counters another: wood counters earth, earth counters water, water counters fire, fire counters metal, and metal counters wood.

Each imperial dragon represents one element and has four abilities related to the cycle. For example, the forest dragon-linked to wood-feeds fire, is fed by water, counters earth, and is countered by metal.
