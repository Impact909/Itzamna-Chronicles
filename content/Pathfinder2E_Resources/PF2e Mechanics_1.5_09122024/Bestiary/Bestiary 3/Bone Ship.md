---
title: "Bone Ship"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MrNEdwu9YCYPfSl6" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Bone Ship"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Bone Ship"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision"
languages: "Common, Necril; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Intimidation: +31, Sailing Lore: +37"
abilityMods: [9, 5, 9, 1, 6, 5]
speed:  swim 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 42
armorclass:
  - name: AC
    desc: "42 all-around vision; __Fort__ +33, __Ref__ +27, __Will__ +30"
hp: 415
health:
  - name: ""
  - name: HP
    desc: "415; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 10, electricity 10, fire 10, piercing 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Skeleton Crew"
    desc: " (divine) The bone ship is compelled not by a single mind, but by the collective consciousness of dead sailors' souls.\n\nThe ship is immune to mental effects that target only a specific number of creatures. It's still subject to mental effects that affect all creatures in an area.\n\nAny creature that tries to communicate with the ship via telepathy or read its thoughts hears the dying screams and gasps of the crew, and is targeted with a 9th-rank [[Spells/Warp Mind|Warp Mind]] spell (DC 41 Will check).\n\nThe ship animates skeletal crew members out of its own bones, arming them with rusty old cutlasses or other armaments so they can attack anyone who comes next to the ship. These entities have appearances matching those the bound souls had in life but aren't truly individuals; anything that targets them in fact targets the bone ship they're a part of.\n\nHundreds of black soul gems decorate the ship's exterior, each holding one soul. These gems can hold souls of creatures whose level was 16th or lower, and they have no value. If the ship is destroyed, all these gems shatter, freeing the souls within."

  - name: "Trawl for Bones"
    desc: " (downtime) The bone ship spends 1 day scavenging bones from the sea and restores itself to full Hit Points."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Blood Wake"
    desc: " (aura,divine,fear,mental) 30 feet. The churning water around the bone ship tinges red with seeping blood. A living creature that enters water in the aura sees visions of itself drowning in the blood and must attempt a DC 37 Will check save. After attempting this saving throw, the creature is temporarily immune for 1 hour.\n\nOn a failure, the creature becomes [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 4]] on a critical failure) and [[Conditions/Stunned|Stunned 1]], and it takes a -4 status penalty to Athletics checks to Swim.\n\n[[Bestiary Effects/Effect_ Blood Wake|Effect: Blood Wake]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hull"
    desc: "+35 (reach 20 feet)\n__Damage__  3d10 + 17 bludgeoning 2d10 void"

  - name: "**Melee** `pf2:1` Skeleton Crew"
    desc: "+35 (agile)\n__Damage__  3d6 + 17 slashing 2d10 void"

  - name: "**Ranged** `pf2:1` Bone Cannon"
    desc: "+35 (brutal, divine, range increment 100 feet, void)\n__Damage__  2d12 + 12 bludgeoning 2d10 void"

  - name: "Cannonade"
    desc: "`pf2:2`  The bone ship makes four bone cannon Strikes, each targeting a different creature."

  - name: "Chain Shot"
    desc: "`pf2:1`  The bone ship makes a special bone cannon Strike, firing a chain made of bones. A creature hit by this Strike is [[Conditions/Grabbed|Grabbed]] by the chain ([[Actions/Escape|Escape]] DC 41).\n\nThe bone ship can use Interact actions to reel in a grabbed creature 50 feet per action spent, and when the ship moves, it pulls the grabbed creature along with it."

  - name: "Crew's Call"
    desc: "`pf2:2` (divine) The crew let out an anguished cry in unison. This is a [[Spells/Wails of the Damned|Wails of the Damned]] spell with 100-foot emanation (DC 39 Fortitude check). In addition, any creature within 5 feet of the ship is [[Conditions/Grabbed|Grabbed]] by the crew.\n\nThe ship can't use Crew's Call again for 1d4+1 rounds."

  - name: "[[Bestiary Ability Glossary/Trample|Keelhaul]]"
    desc: "`pf2:3`  As Trample (Huge or smaller, hull, DC 43 Reflex check), but the bone ship Swims up to double its swim Speed instead of Striding, and each creature that fails its save is also dragged under the ship.\n\nThe GM places each creature dragged along in an underwater space adjacent to the bone ship at the end of the ship's movement.\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Pressgang Soul"
    desc: "`pf2:1` (divine) The bone ship casts [[Spells/Seize Soul|Seize Soul]]. The target must have died due to the bone ship's assault or from drowning. The creature's soul becomes part of the ghostly crew.\n\nA new soul gem grows on the ship, and the bone ship is [[Conditions/Quickened|Quickened]] for 1 minute. It can use the extra action only to Strike or Swim."
 
```

```encounter-table
name: Bone Ship
creatures:
  - 1: Bone Ship
```



Rarely does anything living remain after a bone ship's passing-only death, destruction, and waves red as blood that clash and foam in its wake. When a bone ship forms, necromantic magic dredges great bones from the seabed and slowly bends them into place with malicious intent. Whales' ribs typically form the timbers of the hull, and their great spinal columns twist into towering masts. Muscles and tendons lash the ship together, tightening and loosening to precisely turn the ship as it sails.

When a bone ship encounters another vessel or finds some other opportunity to sow death, smaller corpses strewn throughout the ship animate to form a crew and boarding party. Each crew member resembles a humanoid skeleton, but they might be made of bones from multiple creatures. For battle, the ship also creates magical cannons formed of bone that propel bone shards and debris with blasts of magic. The small black gemstones stippled across the ship's structure hold the souls of a drowned crew, for a bone ship is the cursed legacy of dead sailors.

When mass death happens at sea-often from an entire ship sinking far from shore-the anguish of the dying victims can spawn a bone ship. This event might occur when a sailor makes a final plea to a dark god or when a deity takes the opportunity to bind many dead sailors' souls together as a destructive show of divine power. When not created through divine intervention, a bone ship can grow slowly and organically from one of the ships piloted by the undead sailors known as [[Bestiary 2/Draugr|Draugr]]. As draugr ships plague the seas and sink other vessels, they can collect more souls and bones, eventually becoming bone ships. These vessels look different from many other bone ships with patchwork or asymmetrical appearances.

A bone ship is almost gluttonous, possessing an unceasing appetite for death, destruction, and new souls to add to its number. These desires stem from an underlying cause, either placed within the ship by its creator or accreted from the scattered final wishes of its component dead souls. For example, a deity might send a bone ship on a special mission to carry a message or dispose of a particularly persistent adversary or annoyance. Though bone ships usually travel upon the waves, they have no need to breathe and can carry out underwater missions at the behest of their creator.

Bone ships hold a legendary reputation among sailors. These undead can appear out of nowhere to wreak destruction, and if a crew's bodies are absent from a shipwreck, the calamity might be blamed on a bone ship. The sea can bring death suddenly in many ways, but eternal enslavement of the soul presents a more terrifying fate than death alone.
