---
title: "Vrykolakas Ancient"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7hwhjoDu1awECwIT" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/vampire
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Vrykolakas Ancient"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Vrykolakas Ancient"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[vampire]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +29, Deception: +27, Intimidation: +27, Religion: +19, Stealth: +26, Survival: +23"
abilityMods: [8, 5, 4, 0, 4, 8]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +23, __Ref__ +24, __Will__ +21"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250, (void healing); __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "Children of the Night"
    desc: " (divine,mental) The presence of a vrykolakas ancient inspires savage creatures to crawl forth to do its bidding, including rat swarms, wargs, werewolves, and similar creatures. The vrykolakas ancient can give telepathic orders to these creatures within 100 feet, but they can't communicate back."

  - name: "Swift Tracker"
    desc: "  The vrykolakas moves at full Speed while [[Actions/Track|Tracking]]."

abilities_mid:
  - name: ""
  - name: "Feral Possession"
    desc: " (curse,divine,incapacitation,mental,possession) **Trigger** The vrykolakas is reduced to 0 Hit Points, and an animal is within 100 feet\n* * *\n\n**Effect** Unlike most other undead, a vrykolakas isn't destroyed when it reaches 0 HP. Instead, it attempts to cast its spirit into an animal within 100 feet, which must attempt a Will save (DC 33). On a failure, the animal is possessed. This has the effects of the [[Spells/Possession|Possession]] spell, but it lasts a number of days equal to the vrykolakas's level. This possession can't be counteracted with magic (though remove curse works against it normally).\n\nIf the animal succeeds at its save, the vrykolakas can attempt to possess a different animal within 100 feet. If at any point an animal critically succeeds at its save or no animal is within 100 feet, the vrykolakas fails to possess anything and is destroyed.\n\nA vrykolakas possessing an animal seeks out its burial site (see Burial Site Bound) immediately, burying itself there. While the vrykolakas is in this state of recovery, its animal host is [[Conditions/Paralyzed|Paralyzed]], and beheading it destroys the vrykolakas and kills its host. Removing the curse destroys the vrykolakas and returns the animal to normal.\n\nAfter 1d4 days, if the vrykolakas hasn't been destroyed, the animal dies and the vrykolakas rises in a new body that's identical to its previous one, formed from the animal's remains."

  - name: "Pestilential Aura"
    desc: " (aura,divine) 5 feet. DC 33 Fortitude check\n\nCreatures beginning their turn in the area while the vrykolakas is in its true form are exposed to bubonic plague.\n* * *\n\n**Bubonic Plague**\n\nThis widespread illness can sweep through entire communities, leaving few unaffected. The first indication of the disease is a telltale swelling of glands. In some cases, the disease can move into your lungs (pneumonic plague) or blood (septicemic plague), which is even more fatal.\n\nIf you have bubonic plague, you can't remove the [[Conditions/Fatigued|Fatigued]] condition while affected.\n\n**Onset** 1 day\n\n**Stage 1** fatigued (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 2]] and fatigued (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 3]], fatigued, and take 1d6 bleed every 1d20 minutes (1 day)"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Vrykolakas Vulnerabilities"
    desc: "  Vrykolakas all have the following vulnerabilities.\n\n*   **Burial Site Bound** A vrykolakas is bound to the place of its death or interment. It must return to this location once per week and bury itself in the earth for 24 hours, during which time it is [[Conditions/Paralyzed|Paralyzed]] and can be beheaded. If it is unable to return to this site, it is reduced to 0 Hit Points and attempts to use Feral Corruption; if this host animal can't return to the burial site before the possession effect ends, the vrykolakas is destroyed and the animal host returns to normal.\n*   **Vulnerable to Decapitation** A vrykolakas that is beheaded can't use its Feral Possession, and a beheaded corpse cannot rise as a vrykolakas."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+27 ()\n__Damage__  3d10 + 17 piercing plus drink-blood"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile)\n__Damage__  3d6 + 17 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 33, attack +23; __7th __  _[[Spells/Vampiric Feast|Vampiric Touch (x3)]]_; __3rd __  _[[Spells/Fear|Fear (x3)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) A vrykolakas ancient can transform into a form resembling the body it had in life, with the effects of [[Spells/Humanoid Form|Humanoid Form]] but with unlimited duration. It loses its fangs and claw Strikes but gains a +2 circumstance bonus to Deception checks to [[Action Macros/Impersonate_ Deception|Impersonate]] in this form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Create Spawn"
    desc: " (divine,downtime) If a creature dies after being reduced to 0 HP by Drink Blood, a vrykolakas ancient can turn this creature into a vrykolakas spawn by donating some of its own blood to the creature and burying it in earth for 3 nights.\n\nSuch vrykolakas spawn are generally friendly to the vrykolakas that created them, but they are not under its control and typically wander off on their own rampage within 1d6 days of their creation."

  - name: "Dominate Animal"
    desc: "`pf2:1` (divine,incapacitation,mental) DC 33\n\nThe vrykolakas can cast [[Spells/Dominate|Dominate]] at will as a divine innate spell that affects only animals. A creature that succeeds is immune to that vrykolakas's Dominate Animal for 24 hours. Destroying the vrykolakas ends the effect, but reducing it to 0 HP does not.\n\nA dominated animal takes a -4 circumstance penalty to saving throws against the vrykolakas's Feral Possession."

  - name: "Drink Blood"
    desc: "`pf2:1` (divine) **Requirements** The vrykolakas' last action was a successful fangs Strike\n* * *\n\n**Effect** The vrykolakas sinks its fangs into that creature to drink its blood. This requires an Athletics check check against the creature's Fortitude DC. On a success, the creature becomes [[Conditions/Drained|Drained 2]], and the vrykolakas regains 25 healing Hit Points, gaining any excess HP as temporary Hit Points.\n\nDrinking Blood from a creature that's already drained doesn't restore any HP to the vampire, but it increases the creature's drained condition value by 1. A vrykolakas can also consume blood that's been emptied into a vessel for sustenance, but it gains no HP from doing so.\n\nThe target creature's drained condition value decreases by 1 per week.\n\nA blood transfusion, which requires a successful DC 20 Medicine check check and sufficient blood or a blood donor, reduces the drained value by 1 after 10 minutes."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Sanguine Mauling"
    desc: "`pf2:1`  **Requirements** The vrykolakas ancient's last action was to Drink Blood\n* * *\n\n**Effect** The vrykolakas ancient makes two claw Strikes. Both count toward its multiple attack penalty, but the penalty increases only after it makes both attacks. If it hits with both claws, the target takes 1d6 bleed."

  - name: "Steal Breath"
    desc: "`pf2:2` (manipulate) **Requirements** The vrykolakas ancient is adjacent to an [[Conditions/Unconscious|Unconscious]] creature\n* * *\n\n**Effect** The vrykolakas ancient steals the creature's breath. The unconscious creature begins suffocating, can't be awakened for 1 round, and must attempt a DC 33 Fortitude check save. If a creature is targeted with this ability in consecutive rounds, the save DC decreases by 2 each round after the first.\n* * *\n\n**Critical Success** The target immediately awakens and is then temporarily immune to Steal Breath for 24 hours.\n\n**Success** The target is unaffected.\n\n**Failure** The target takes 1d10 damage.\n\n**Critical Failure** The target is reduced to 0 HP and becomes [[Conditions/Dying|Dying 1]]."
 
```

```encounter-table
name: Vrykolakas Ancient
creatures:
  - 1: Vrykolakas Ancient
```



Vrykolakas ancients are the sinister overlords of their kind, stealing blood, breath, and life to feed their immortal hunger.
