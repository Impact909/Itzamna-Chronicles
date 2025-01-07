---
title: "Ostiarius"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hmq22fFMAwkrwuS8" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Ostiarius"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Ostiarius"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Greater Darkvision"
languages: "Common, Diabolic, Shadowtongue; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Deception: +12, Diplomacy: +12, Intimidation: +16, Religion: +11, Torture Lore: +11"
abilityMods: [0, 4, 2, 2, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +15, __Will__ +13; +1 status to all saves vs. magic"
hp: 67
health:
  - name: ""
  - name: HP
    desc: "67, regeneration 5 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 5, silver 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions"

  - name: "Sense Portal"
    desc: " (divine) The ostiarius always knows the direction and distance to the closest portal between the Shadow Plane and the Material Plane. This sense functions only on these two planes."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 5 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Whispering Wounds"
    desc: " (aura,divine,mental,visual) 30 feet. When a creature ends its turn in the aura, it hears the wounds on the ostiarius's body whisper obscene truths. The creature must succeed at a DC 21 Will check save or become [[Conditions/Sickened|Sickened 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile, finesse, magical, unholy)\n__Damage__  2d6 + 2 slashing 2d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +14; __3rd __  _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Wanderer's Guide|Wanderer's Guide]]_; __2nd __  _[[Spells/Calm|Calm Emotions (At will)]]_, _[[Spells/Darkness|Darkness]]_, _[[Spells/Silence|Silence]]_\n__Cantrips__  __(3rd)__ _[[Spells/Shield|Shield]]_"

  - name: "Rituals"
    desc: "_Inveigle_"

  - name: "Compel Courage"
    desc: "`pf2:1` (auditory,divine,emotion,linguistic,mental) The ostiarius inspires their willing allies and themself by whispering words of courage from their wounds. The ostiarius and their allies in a 50-foot emanation gain a +1 status bonus to attack rolls, damage rolls, and saves against fear effects. The ostiarius can Sustain Compel Courage.\n\nNon-velstracs who accept this compelled courage find bleeding wounds opening on their own bodies to whisper in thanks. They take 1 bleed damage and can't attempt a flat check to end this damage as long as they're compelled."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,incapacitation,mental,visual) The ostiarius stares at a creature they can see within 30 feet. The creature must immediately attempt a Will save against Whispering Wounds. In addition, if the creature was already [[Conditions/Sickened|Sickened]] and fails its save, the creature is [[Conditions/Fascinated|Fascinated]] by the ostiarius and can't use hostile actions. This fascination lasts for 1 round or until the ostiarius takes any hostile action against the creature or the creature's allies. Whether the creature succeeds at or fails the save, it is temporarily immune for 1 hour."
 
```

```encounter-table
name: Ostiarius
creatures:
  - 1: Ostiarius
```



Ostiariuses, as emissaries of the velstracs, tend to the portals between the Shadow Plane and the Material Plane. They not only escort other velstracs into the world of mortals, but also work to entice mortals into the realms of the velstracs- from which most mortals never leave. Among the most pleasant and persuasive of the velstracs, ostiariuses are prepared to converse for hours upon any topic, and they are skilled at returning, again and again, to the subject of the delights found in their perverse philosophies. Ostiariuses stand over 6 feet tall, and individuals range from skeletally thin to hugely corpulent.
