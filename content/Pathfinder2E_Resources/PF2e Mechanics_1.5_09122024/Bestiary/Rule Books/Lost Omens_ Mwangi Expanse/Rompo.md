---
title: "Rompo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CjNwy75be7JWD7Pn" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Rompo"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: The Mwangi Expanse"
name: "Rompo"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +12, Survival: +12"
abilityMods: [5, 2, 2, -3, 2, 0]
speed: 30 feet,  climb 25 feet
sourcebook: "_Pathfinder Lost Omens: The Mwangi Expanse_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +9, __Will__ +11"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80"
abilities_top:
  - name: ""

  - name: "Camouflage"
    desc: "  The rompo can change its coloration to match its surroundings. It doesn't need cover to attempt to Hide with a Stealth check."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 ()\n__Damage__  2d8 + 5 piercing plus rompo-chills"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+13 (agile)\n__Damage__  2d6 + 5 slashing"

  - name: "Crooning Cry"
    desc: "`pf2:2` (incapacitation,mental,primal) 60 feet. The rompo hums in a low voice. Each creature within the emanation must succeed at a DC 19 Will check save or become [[Conditions/Fascinated|Fascinated]] and compelled to move away from the rompo, traveling to the furthest edge of the emanation. Fascinated creatures are also [[Conditions/Off-Guard|Off-Guard]].\n\nThe effect lasts for 1 round, but if the rompo spends a single action on subsequent rounds, it can extend the duration by 1 round for all affected creatures. If the rompo attacks, the fascinated condition ends only for the creature that is attacked.\n\nOn a successful save, a creature is temporarily immune to Crooning Cry for 24 hours."

  - name: "Rompo Chills"
    desc: " (disease) The target can't reduce its sickened condition while affected by rompo chills\n\n**Saving Throw** DC 19 Fortitude check\n\n**Onset** 1 day\n* * *\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 day)\n\n**Stage 2** Clumsy 1 and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Sickened|Sickened 2]] (1 day)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 5** dead"
 
```

```encounter-table
name: Rompo
creatures:
  - 1: Rompo
```



Rompos are unusual creatures that feed on corpses. They have thin, almost-skeletal bodies with strong rear legs that resemble a bear's, front legs like a badger's, and a head like a hare's with humanoid ears. A rompo tends to be timid on its own; it avoids other creatures and typically flees in the presence of larger animals. Though no more intelligent than any other beast, it usually acts with extreme paranoia, dodging traps or ambushes with an uncanny acumen. When danger is present, a rompo utters a loud cry to afford itself space to run and hides by using its body's natural color-shifting fur as camouflage.

Although rompos sport the perfect physical features to act as predators, they tend to live their lives as solitary scavengers of leftover corpses. Rompos prefer to avoid hunting for themselves since they risk sustaining injuries in the process. It's not uncommon for rompos to follow other predators for hours, waiting for an opportunity to feast on the leftover remains of a hunt.

Once a rompo gains access to a meal, it takes several minutes circling the corpse to make sure the area is clear. As it begins to feast, it lets out a whimpering cry that fascinates and compels other creatures to keep away so that the rompo can feed in peace. Due to its constant feeding on decaying flesh, a rompo's mouth is filled with rot, parasites, and deadly pathogens. Its bite can impart these combined infections as a dangerous disease known as rompo chills. The disease causes its victim to tremble uncontrollably, lightly at first but eventually developing into a violent shaking that ends with the victim's death. Despite their cautious nature, rompos always seem to linger close to creatures they infect with rompo chills; though they remain unseen while the victim lives, they emerge when that victim finally succumbs, in order to feed on the corpse.
