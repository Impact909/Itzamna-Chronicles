---
title: "Barbazu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JR7jAzfrqE6AAaxU" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Barbazu"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Barbazu"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Greater Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +13, Intimidation: +10, Religion: +11, Stealth: +11"
abilityMods: [4, 2, 4, -2, 2, 1]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +11, __Will__ +11; +1 status to all saves vs. magic"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  fire; __Weaknesses__ holy 5; __Resistances__ physical 5 (except silver), poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|Glaive]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+15 (deadly d8, forceful, magical, reach 10 feet, unholy)\n__Damage__  1d8 + 7 slashing plus infernal-wound 2d6 spirit plus infernal-wound"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, magical, unholy)\n__Damage__  2d6 + 7 slashing 1d6 spirit"

  - name: "**Melee** `pf2:1` Beard"
    desc: "+15 (magical, unholy)\n__Damage__  1d6 + 7 piercing plus avernal-fever"

  - name: "Divine Innate Spells"
    desc: "DC 19, attack +11; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Avernal Fever"
    desc: " (disease) **Saving Throw** DC 23 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"

  - name: "Infernal Wound"
    desc: " (divine) A bearded devil's glaive Strike also deals 1d6 bleed that resists attempts to heal it.\n\nThe flat check to stop the bleeding starts at DC 20 Flat check. The DC is reduced to DC 15 Flat check only if the bleeding creature or an ally successfully assists with the recovery. The DC to [[Actions/Administer First Aid|Administer First Aid]] to a creature with an infernal wound is increased by 5.\n\nA spellcaster or item attempting to use healing magic on a creature suffering from an infernal wound must succeed at a DC 21 counteract check or the magic fails to heal the creature.\n\n[[Bestiary Effects/Effect_ Infernal Wound|Effect: Infernal Wound]]"

  - name: "Reposition"
    desc: "  **Trigger** The devil hits a creature with a glaive Strike.\n* * *\n\n**Effect** The devil moves the creature 5 feet in any direction. The destination square must be within reach of the devil's glaive.\n\nThis movement doesn't trigger reactions."

  - name: "Wriggling Beard"
    desc: "`pf2:1`  **Frequency** once per round.\n* * *\n\n**Effect** The barbazu makes a beard Strike. This Strike ignores their multiple attack penalty and doesn't count toward that penalty."
 
```

```encounter-table
name: Barbazu
creatures:
  - 1: Barbazu
```



Barbazus, known also as bearded devils or infantry devils, are murderous fiends who satiate their lust for annihilation by serving as the foot soldiers of Hell's armies, often leading hordes of lesser devils such as imps and lemures into battle. Bearded devils wield serrated glaives to inflict jagged gashes that resist healing magic, resulting in tremendous blood loss. When enemies come too close, bearded devils strike with the spines of their wriggling beards to deliver a wretched contagion called Avernal fever, savoring the sight of their victim's strength being slowly devoured from within.

Barbazus can be found savagely indulging the whims of evil infernal lords from all layers of Hell, rejoicing as they disseminate murder, misery, and anguish as they see fit.

* * *

Masters of corruption and architects of conquest, devils seek both to tempt mortal life to join in their pursuit of all things profane and to spread tyranny throughout all worlds. The temptations they offer mortals range from great powers granted by the signing of an infernal contract to twisted favors following a whispered pledge to a diabolic patron, or any number of even subtler exchanges. Those who succumb to these temptations find themselves consigned to an afterlife of endless torment in the pits of Hell, wherein the only hope of escape lies in the chance of being promoted to become a devil in the infernal ranks. Every devil has a specific role to play in the upkeep of the remorseless bureaucratic machine that is Hell, from soldiers and scholars to inquisitors, lawyers, judges, and executioners. Lowly lemures and imps perform subservient labor to more powerful and specialized devils, such as contract devils and erinyes, while the greatest pit fiends command entire infernal armies.
