---
title: "Zibik"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nIEajwfSdfxagcIq" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/leshy
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/24
  - remaster
statblock: inline
name: "Zibik"
level: 24
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Zibik"
level: "Creature 24"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[fungus]]
trait_02: [[leshy]]
trait_03: [[plant]]
modifier: 42
perception:
  - name: "Perception"
    desc: "+42; Darkvision"
languages: "Arboreal, Fey, Wildsong, Muan; green tongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +39, Athletics: +42, Deception: +40, Diplomacy: +40, Intimidation: +40, Medicine: +48, Nature: +48, Stealth: +41, Survival: +44, Plane of Wood Lore: +48"
abilityMods: [12, 9, 11, 7, 10, 8]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 51
armorclass:
  - name: AC
    desc: "51; __Fort__ +43, __Ref__ +39, __Will__ +42"
hp: 525
health:
  - name: ""
  - name: HP
    desc: "525; __Weaknesses__ axe vulnerability 20, fire 20; __Resistances__ bludgeoning 20, piercing 20"
abilities_top:
  - name: ""

  - name: "Green Tongue"
    desc: "  A green man can communicate with plants, with the effects of [[Spells/Speak with Plants|Speak with Plants]], and can use Diplomacy to [[Actions/Make an Impression|Make an Impression]] on plants and [[Actions/Request|Request]] things from plants."

  - name: "Plantsense 60 feet"
    desc: "  A green man can sense life force via plants. This allows them to observe a living or undead creature's vital essence within 60 feet of the green man, but they can also use this precise sense to observe any living or undead creature within 60 feet of any plant matter within 120 feet of the green man. This allows the green man to see living things through solid plant matter, as well as seeing through other barriers if there are plants on the other side."

abilities_mid:
  - name: ""
  - name: "Axe Vulnerability"
    desc: "  A green man takes 20 additional damage from axes."

  - name: "Green Caress"
    desc: " (aura,incapacitation,plant,primal) 60 feet. Living creatures in the area other than plants slowly transform into non-creature plants. The green man can exclude creatures from this effect, but they must be aware of a creature's presence and location to do so. A non-plant creature in the area must attempt a DC 45 Fortitude check save immediately before the start of its turn.\n* * *\n\n**Critical Success** The creature is unaffected, or if it is slowed by green caress, it reduces its slowed value by 2.\n\n**Success** The creature is unaffected, or if it is slowed by green caress, it reduces its slowed value by 1.\n\n**Failure** The creature becomes [[Conditions/Slowed|Slowed 1]], or if it was already slowed by green caress, increases the slowed value by 1, as their body transforms more and more into a non-creature plant. If the creature ever becomes slowed to the point they have no actions left for their turn, they become an inanimate plant, a condition that can only be reversed by [[Spells/Primal Phenomenon|Primal Phenomenon]] or similarly powerful magic.\n\n**Critical Failure** As failure, except the creature becomes [[Conditions/Slowed|Slowed 2]] (or increases the condition value by 2)."

  - name: "Root In Place"
    desc: "`pf2:r`  **Trigger** A creature within the green man's reach uses a move action or leaves a square during a move action it's using\n* * *\n\n**Effect** The green man lashes out to hold the foe in place. The green man makes a vine Strike against the triggering creature. If the attack hits, the green man disrupts the action. If the creature was Flying when its action was disrupted, it falls."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+46 (deadly 3d12, versatile p)\n__Damage__  4d10 + 27 bludgeoning plus absorb-magic,improved-grab"

  - name: "**Ranged** `pf2:1` Thorn"
    desc: "+43 (fatal d12, range increment 120 feet, reload 0)\n__Damage__  4d8 + 27 piercing plus embed"

  - name: "Primal Innate Spells"
    desc: "DC 48, attack +40; __10th __  _[[Spells/Flourishing Flora|Flourishing Flora (x3)]]_, _[[Spells/Heal|Heal (x3)]]_, _[[Spells/Nature's Pathway|Nature's Pathway (At Will)]]_, _[[Spells/Regenerate|Regenerate (x3)]]_, _[[Spells/Truesight|Truesight]]_; __9th __  _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Entwined Roots|Entwined Roots]]_; __8th __  _[[Spells/Desiccate|Desiccate]]_, _[[Spells/Life-Draining Roots|Life-Draining Roots]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_\n__Cantrips__  __(10th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Rituals"
    desc: "_Awaken Animal_, _Commune_, _Control Weather_, _Plant Growth_, _Primal Call_, _Wish_"

  - name: "Absorb Magic"
    desc: "`pf2:1`  The green man's vines leach away magic and transform it into life essence for the green man. On a successful vine Strike, the green man attempts to counteract one spell active on the target (typically one vexing the green man, or determined randomly if they aren't aware of specific effects), with a counteract rank of 10 and a modifier of +38.\n\nIf the effect is counteracted, the green man gains 30 temporary Hit Points that last for 10 minutes."

  - name: "Aura of Absorption"
    desc: " (aura,fungus,primal) 120 feet.\n\nZibik constantly absorbs toxins and pathogens from his surroundings. Zibik automatically absorbs afflictions from non-creature plants, increasing his drained value by 1 each round he absorbs any afflictions from such plants (with no maximum). Living creatures in the area can attempt a saving throw against any disease or poison afflicting them each round, increasing their degree of success for the save by one step. If a creature succeeds, Zibik automatically counteracts the affliction and increases his current drained value by 1 (with no maximum).\n\nWhen Zibik removes an affliction with this ability, he automatically advances to Stage 1 of the affliction and must continue to attempt saving throws as normal. Zibik can choose to exclude any number of creatures in the area from this effect, and generally does so to absorb Ayrzul's Blight while allowing natural afflictions to run their course."

  - name: "Embed"
    desc: "  The green man's thorns embed themselves into any creature they damage, taking root into the ground. A target damaged by a thorn has its Speeds halved, and it can't Step, [[Actions/Fly|Fly]], [[Spells/Air Walk|Air Walk]], or otherwise leave the ground until the thorn is removed.\n\nRemoving a thorn requires 3 Interact actions, which don't have to be consecutive. If the creature performing the final action doesn't succeed at a DC 45 Medicine check check as part of that action, the target takes 10d6 untyped damage upon the thorn's removal."

  - name: "Focus Vines"
    desc: "`pf2:2`  The green man focuses all their vines against a single vexing foe, making a single vine Strike.\n\nOn a success, the target takes 5d10 additional damage and is affected by Absorb Magic three times. Even on a failure, the target takes the normal effects of a hit with a vine Strike, but on a critical failure, the vines miss completely."

  - name: "Fungal Rebirth"
    desc: " (fungus,primal) When Zibik dies as the result of a disease or his Aura of Absorption, fungus rebuilds his body over the course of 3d6 days. If his body is destroyed before then, the process restarts.\n\nWhen restored to life, he's bolstered by primal might; he gains a +3 circumstance bonus to saving throws against diseases for a number of weeks equal to the number of days it took his body to regrow, and he's unaffected by the drained condition for the same duration (though he can still gain the condition)."

  - name: "Green Grab"
    desc: "  A green man can use their [[Bestiary Ability Glossary/Improved Grab|Improved Grab]] action against a creature of any size."

  - name: "Green Rituals"
    desc: "  A green man can perform all their rituals without secondary casters, relying on their own primal ties to the vital essence in spirits of nature.\n\nA green man's [[Spells/Awaken Animal|Awaken Animal]] and [[Spells/Primal Call|Primal Call]] rituals work on plants instead of their usual range of choices.\n\nMost green men also know the ritual to create various types of leshys and possibly even magic allowing the creation of arboreals or more powerful plant creatures."

  - name: "Purge Plaguebearers"
    desc: "`pf2:2` (fungus,primal) Zibik exudes a cloud of spores in a 30-foot-radius emanation. They cling to all creatures currently afflicted with any disease in the area. Afflicted creatures take 25d6 void damage with a DC 48 Fortitude check save.\n\nA creature that fails its save becomes [[Conditions/Doomed|Doomed 1]] for 1 minute and [[Conditions/Sickened|Sickened 3]]. Zibik can choose to exclude any number of creatures in the area from this effect.\n\nZibik can't use Purge Plaguebearers again for 1d4 rounds."

  - name: "Vine Forest"
    desc: "`pf2:2`  The green man lashes out with all six vines to attack many opponents. They make up to six vine Strikes, each against a different target; this counts as one attack for their multiple attack penalty, increasing only after all the attacks are made."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zibik
creatures:
  - 1: Zibik
```


Male variant green man

Green men are ancient, enigmatic lesser deities of the primeval forests, living embodiments of nature and plantkind. When a forest or other woodland terrain generates enough nature spirits, beings of the same sort of vital essence that embodies leshys or answers the call of a commune with nature, they naturally coalesce together and apotheosize into a green man. Green men aren't concerned with all the multifarious processes of nature like Gozreh or many other nature deities. Instead, they focus nearly all their attention on the plants of their home, only concerning themselves with animals, minerals, and the like insomuch as they affect the plants. Despite their name, green men aren't necessarily male; as creatures of pure natural power, to many of them, the concept of gender holds no meaning, and to those that do, they can be of any gender.

Most green men are neutral and tend to ignore "animals," which to them include sapient creatures such as humans. However, good and evil green men do exist. These individuals are far more likely to attempt to spread their influence far and wide, either for good or ill. Good green men provide succor to all that come within their home, not only to plants, providing wisdom like a nurturing parent. Evil green men, however, allow rare and dangerous plants to thrive in their domains by spreading fear and devastation to all those who might threaten plant life, though they might keep a few animals around to hunt for sport.
