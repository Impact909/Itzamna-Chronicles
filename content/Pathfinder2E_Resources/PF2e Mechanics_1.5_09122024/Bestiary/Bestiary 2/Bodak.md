---
title: "Bodak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ls83uKgVWlzKxFUo" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Bodak"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Bodak"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +15, Intimidation: +19, Stealth: +18"
abilityMods: [3, 4, 1, -2, 5, 5]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +13, __Ref__ +16, __Will__ +19"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Draining Glance"
    desc: "`pf2:r` (aura,death,occult,visual) **Trigger** A living creature within 30 feet that the bodak can perceive with its [[Bestiary Ability Glossary/Lifesense|Lifesense]] starts its turn\n* * *\n\n**Effect** The target must attempt a DC 23 Fortitude check save. If it fails, the bodak regains 5 healing Hit Points and the target becomes [[Conditions/Drained|Drained 1]]."

  - name: "Sunlight Vulnerability"
    desc: " (death) If exposed to direct sunlight, the bodak can't use actions with the death trait and it becomes [[Conditions/Slowed|Slowed 1]]. The slowed value increases by 1 each time the bodak ends its turn in sunlight. If the bodak loses all its actions this way, it is destroyed."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, finesse)\n__Damage__  2d6 + 6 bludgeoning 1d6 void"

  - name: "Bodak Spawn"
    desc: " (occult) Any humanoid who dies while [[Conditions/Drained|Drained]] or [[Conditions/Doomed|Doomed]] by a bodak rises as an autonomous bodak 24 hours after its death."

  - name: "Death Gaze"
    desc: "`pf2:2` (death,occult,visual) The bodak stares at a living creature within 30 feet that it can sense with its [[Bestiary Ability Glossary/Lifesense|Lifesense]]. That creature must attempt a DC 26 Fortitude check save. If the target becomes [[Conditions/Drained|Drained]], the bodak gains a number of temporary Hit Points equal to 5 times the value of the drained condition the target gained.\n\nMultiple exposures to this ability can increase a creature's drained condition to a maximum of 4. If the bodak is destroyed, any [[Conditions/Doomed|Doomed]] condition a creature has gained from Death Gaze are removed.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Drained|Drained 1]].\n\n**Failure** The creature is [[Conditions/Doomed|Doomed 1]] and [[Conditions/Drained|Drained 2]].\n\n**Critical Failure** The creature is doomed 1 and [[Conditions/Drained|Drained 4]]."
 
```

```encounter-table
name: Bodak
creatures:
  - 1: Bodak
```



When a living, sentient humanoid is exposed to an extreme expression of supernatural evil, the experience can irrevocably damn the victim, crushing their mind and ripping out their soul in an appalling, unholy transformation that results in a creature that's anathema to life-the bodak.

The shreds of physicality that survive this absolute corruption serve only to enhance the humanoid's profoundly disturbing appearance. The bodak's body is horrifically twisted, as though it's locked in a convulsion of agony and terror. Its desiccated and hairless flesh bears an otherworldly, pearlescent sheen, strung taut across a malformed skeleton that reduces its gait to a slow shamble. But most disturbing of all are its eyes, set in a drooping, melted visage with scant remains of its former facial structure. These eyes, sunken deep into their sockets, nevertheless glow with an unholy light, stare with unremitting malevolence, and constantly weep noxious vapor.

Fragmented memories of a prior existence filtered through a vengeful hatred of the living lead the bodak to try to return to those places it once knew. If successful, it assaults former friends, acquaintances, and loved ones with its murderous gaze and an incomprehensible torrent of gibberish laced with vile curses, accusations, and threats-an assault that often leads to the victims rising as newly formed bodaks themselves.
