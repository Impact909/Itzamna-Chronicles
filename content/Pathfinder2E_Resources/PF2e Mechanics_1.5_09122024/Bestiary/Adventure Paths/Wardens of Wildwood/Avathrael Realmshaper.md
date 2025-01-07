---
title: "Avathrael Realmshaper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GGEKlZTALpi8zX7p" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/plant
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Avathrael Realmshaper"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Avathrael Realmshaper"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[plant]]
trait_03: [[shadow]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Greater Darkvision, Scent (Imprecise) 60 Feet"
languages: "Arboreal, Common, Draconic, Fey, Shadowtongue; Speak with Plants, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Arcana: +25, Athletics: +21, Crafting: +25, Intimidation: +20, Nature: +25, Occultism: +25, Survival: +25, Architecture Lore: +27, Art Lore: +27, Netherworld Lore: +27"
abilityMods: [5, 3, 5, 7, 7, 4]
speed: 40 feet,  fly 100 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +21, __Ref__ +19, __Will__ +25; +1 status to all saves vs. magic"
hp: 214
health:
  - name: ""
  - name: HP
    desc: "214; __Immunities__  paralyzed,  poison,  sleep,  stunned,  void"
abilities_top:
  - name: ""

  - name: "Shadowsense"
    desc: "  The shadows of Gloaming Arbor are an extension of Avathrael, and they can sense creatures in areas of dim light or darkness."

abilities_mid:
  - name: ""
  - name: "Floral Defense"
    desc: "`pf2:r` (plant) **Trigger** Avathrael is the target of a physical attack\n* * *\n\n**Effect** Avathrael raises their plant-covered wings to block the incoming blow. They gain a +2 circumstance bonus to AC against the triggering attack. If the attack misses, it's deflected by Avathrael's wing, causing some of the dangerous plants growing on the wing to burst and release a cloud of toxic pollen. The triggering creature takes 2d10 poison damage (DC 29 Fortitude check save). On a critical failure, the triggering creature is also [[Conditions/Sickened|Sickened 1]]."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet DC 29 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 (magical, reach 15 feet)\n__Damage__  3d10 + 11 piercing 1d8 poison"

  - name: "**Melee** `pf2:1` Razor Tail"
    desc: "+24 (magical, reach 20 feet)\n__Damage__  4d8 + 11 bludgeoning 1d8 bleed"

  - name: "**Melee** `pf2:1` Shadow Claws"
    desc: "+26 (agile, magical, reach 10 feet)\n__Damage__  1d8 void 2d8 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Seedpod"
    desc: "+22 (range increment 60 feet)\n__Damage__  2d6 + 11 bludgeoning 1d6 poison"

  - name: "Arcane Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Shadow Blast|Shadow Blast (x2)]]_; __5th __  _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Umbral Journey|Umbral Journey]]_; __4th __  _[[Spells/Chilling Darkness|Chilling Darkness]]_, _[[Spells/Darkness|Darkness]]_; __3rd __  _[[Spells/Inscrutable Mask|Inscrutable Mask]]_; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Primal Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Nature's Reprisal|Nature's Reprisal]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Nature's Pathway|Nature's Pathway]]_, _[[Spells/Wall of Thorns|Wall of Thorns]]_; __2nd __  _[[Spells/One with Plants|One with Plants]]_, _[[Spells/Shape Wood|Shape Wood (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Tangle Vine|Tangle Vine]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_ __(4th)__ _[[Spells/Speak with Plants|Speak with Plants]]_ __(1st)__ _[[Spells/Vanishing Tracks|Vanishing Tracks]]_"

  - name: "Rituals"
    desc: "_Awaken Animal_, _Blight_, _Commune_, _Dread Ambience_, _Plant Growth_, _Primal Call_, _Ward Domain_"

  - name: "Draconic Momentum"
    desc: "  Avathrael recharges their Poison Breath whenever they score a critical hit with a Strike."

  - name: "Poison Breath"
    desc: "`pf2:2` (poison,primal) Avathrael exhales a cloud of sweet-smelling poisonous gas that deals 13d6 poison damage in a 50-foot cone (DC 32 Fortitude check save). A creature that critically fails is also [[Conditions/Sickened|Sickened 2]]. Avathrael can't use Poison Breath again for 1d4 rounds."

  - name: "Shadow Step"
    desc: "`pf2:1` (arcane,healing,teleportation) **Frequency** twice per day\n* * *\n\n**Effect** Avathrael teleports with the effects of a 4th-rank [[Spells/Translocate|Translocate]] spell, but Avathrael must begin and end the teleportation effect in an area of dim light or darkness. If they use 2 actions to activate this ability, Avathrael also regains 8d10 healing Hit Points. Avathrael can't use Shadow Step again for 1d4 rounds."

  - name: "Shape Shadow Realm"
    desc: "`pf2:2` (arcane,concentrate,shadow) Avathrael mentally reshapes their realm, reshaping terrain and creating obstacles to hinder their foes. All squares within a 50-foot burst become difficult terrain. Creatures in the area take 10d6 void damage (DC 32 Reflex check save) from the shadows. On a failure, that creature is additionally [[Conditions/Grabbed|Grabbed]] by the malleable shadows ([[Actions/Escape|Escape]] DC 32). At the beginning of Avathrael's turn, each creature that's grabbed takes 4d6 void damage. Avathrael can't use Shape Shadow Realm again for 1d4 rounds."

  - name: "Snuff Light"
    desc: "  **Frequency** once per round\n* * *\n\n**Effect** Avathrael exhales, automatically extinguishing all non-magical lights within 100 feet. Avathrael attempts to counteract each light source within 100 feet (+22 counteract)."

  - name: "Woodland Stride"
    desc: "  Avathrael ignores difficult terrain and greater difficult terrain from non-magical foliage."
 
```

```encounter-table
name: Avathrael Realmshaper
creatures:
  - 1: Avathrael Realmshaper
```


Agender dragon


