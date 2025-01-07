---
title: "Mu Spore"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ePId8b27lE7gILNc" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fungus
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Mu Spore"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Mu Spore"
level: "Creature 21"

alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[fungus]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Low-Light Vision"
languages: "Aklo, Common, Petran, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Athletics: +41, Nature: +38, Occultism: +36"
abilityMods: [10, 3, 9, 4, 9, 9]
speed: 40 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +38, __Ref__ +32, __Will__ +38"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350, regeneration 50 (deactivated by sonic); __Resistances__ acid 20, all damage 10 (except sonic)"
abilities_top:
  - name: ""

  - name: "Windsense 240 feet"
    desc: "  The mu spore senses vibrations in the air through its aerial spores."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 50 (Deactivated by Sonic)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Enormous"
    desc: "  A mu spore is a massive creature and takes up a space of 10 squares by 10 squares (50 feet by 50 feet)."

  - name: "Grasping Tendrils"
    desc: "`pf2:0`  **Trigger** A creature within 10 feet of the mu spore moves or attacks the mu spore.\n* * *\n\n**Effect** The spore uses [[Bestiary Ability Glossary/Improved Grab|Grab]] on the triggering creature. There is no limit to how many creatures it can grab with the sticky tendrils that cover its body."

  - name: "Spores"
    desc: " (aura) 60 feet. A living creature that enters the area or ends its turn within it is corrupted by spores. It must succeed at a DC 42 Fortitude check save or be [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Enfeebled|Enfeebled 1]], and [[Conditions/Slowed|Slowed 1]] for 1 round. Fungi and plants are immune."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+40 (deadly 3d12, reach 30 feet)\n__Damage__  4d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+40 (agile, reach 100 feet)\n__Damage__  4d10 + 18 bludgeoning plus improved-grab"

  - name: "Cough Spores"
    desc: "`pf2:2`  The mu spore releases a cloud of burrowing spores in a 400-foot cone. The spores deal 22d6 piercing damage to all creatures, objects, and wooden structures in the area, but not to plants or fungi (DC 46 Reflex check save).\n\nThe mu spore can't use this ability again for 1d4 rounds."

  - name: "Enormous Inhalation"
    desc: "`pf2:2`  The mu spore pulls all creatures and objects in a 400-foot cone 400 feet towards it's mouth. A successful DC 43 Fortitude check save halves the distance, or avoids the pull on a critical success. The mu spore automatically attempts to Swallow Whole each creature adjacent to it at the end of the inhalation."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The mu spore [[Conditions/Grabbed|Grabs]] a creature with its jaws.\n* * *\n\n**Effect** The spore uses Swallow Whole."

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  15 bludgeoning damage, DC 45 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Overpowering Jaws"
    desc: "  The mu spore still deals 18 piercing damage if its jaws Strike is a failure"

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Gargantuan, 20d6+9 acid damage, Rupture 37.\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mu Spore
creatures:
  - 1: Mu Spore
```



A mu spore is a thankfully rare fungoid monstrosity of vast power and strange intellect. Even the smallest mu spores are never less than a hundred feet long from tentacle tip to tentacle tip, yet despite this vast bulk, they are capable of flying with an uncommon grace, venting jets of foul-smelling spores to guide their flight.

Many societies tell tales of vast mu spores appearing over cities at the dawn of apocalyptic events, but they're more than just ravenous eaters of nations. Mu spores often possess rare or esoteric knowledge, and if peaceful contact can be made, this lore can be quite valuable. Their spores can also be used to craft certain foul drugs or deadly alchemical poisons, but harvesting these ingredients is dangerous, as the spores are not viable for long once they've been shed, forcing alchemists seeking to harvest them to operate in perilously close proximity to the abominations.
