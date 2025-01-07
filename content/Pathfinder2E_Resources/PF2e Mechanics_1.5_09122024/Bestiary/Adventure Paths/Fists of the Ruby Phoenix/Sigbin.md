---
title: "Sigbin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NOoAgarya03Ie13Q" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Sigbin"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Sigbin"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[beast]]
trait_02: [[evil]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +10, Stealth: +14"
abilityMods: [1, 5, 4, -1, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +16, __Will__ +8"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the emanation must attempt a DC 19 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], or [[Conditions/Sickened|Sickened 2]] on a critical failure. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is immune to all sigbins' stenches for 1 minute."

  - name: "Unassuming Cloak"
    desc: "  A sigbin becomes almost imperceptible if it stands completely still. If the sigbin does not move or attack during its turn, it becomes [[Conditions/Invisible|Invisible]]. It remains invisible until it moves or takes a hostile action. Children and young creatures, like animal cubs, can see the sigbin normally, even while it's invisible."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claws"
    desc: "+14 (agile, finesse)\n__Damage__  2d4 + 5 slashing"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+14 (finesse)\n__Damage__  2d6 + 5 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+12 (agile, finesse, reach 10 feet)\n__Damage__  2d4 + 5 bludgeoning plus knockdown"

  - name: "Shadow Drain"
    desc: "`pf2:2`  **Requirements** The sigbin is [[Conditions/Unnoticed|Unnoticed]] by its target.\n* * *\n\n**Effect** The sigbin makes a fangs Strike (unlike other Strikes, this does not end its [[Conditions/Invisible|invisibility]] if the sigbin is invisible). On a hit, the target takes nonlethal damage from the Strike and becomes [[Conditions/Drained|Drained 1]] ([[Conditions/Drained|Drained 2]] on a critical hit). The sigbin gains 15 temporary Hit Points that remain for 1 hour."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Sigbin
creatures:
  - 1: Sigbin
```



Resembling hornless goats with extremely long tails, sigbins live in forests and prey on inhabitants of nearby humanoid villages. Sigbins drink the blood of their victims by biting into their shadows, rather than their flesh. This process typically leaves the victim so fatigued that they must lie down to rest, at which point the sigbin finishes the job by sinking their jaws into the person's chest and consuming their heart.

Due to their nauseating smell, many sigbins hide among livestock and in other overwhelmingly odorous places. Sigbins have the ability to hide in plain sight simply by standing stock still, but this power works only against adults and elders; for whatever reason, children and young animals can see the invisible sigbins. Many believe this is because children are unsullied by the cruel ways of the world, and so their eyes are still innocent enough to spot the devious beasts. Unfortunately, most adults tend to ignore children's cries about the monsters, chalking up such claims to overactive imaginations or attention-seeking behavior, inadvertently allowing sigbins to continue their hunts uninterrupted.
