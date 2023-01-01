Non-Fatal Wounds Extended
================

This is an add-on for the game [Wesnoth](https://www.wesnoth.org/).
* Author :  [CookieLord](https://forums.wesnoth.org/memberlist.php?mode=viewprofile&u=248402), stevecotton, Octalot, Armagedonus, [Toranks](http://toranks.blogspot.com/)
* Mantainer : [Toranks](http://toranks.blogspot.com/)
* Changelog : see [CHANGELOG.md](CHANGELOG.md)
* License : [GNU-GPL](LICENSE.md)
* Code Repository [on GitHub](https://github.com/Toranks/Non_Fatal_Wounds-Extended)
* Dedicated [forum thread](https://forums.wesnoth.org/viewtopic.php?t=56108)

Spoiler warning
---------------

`utils/campaigns.cfg` and `utils/campaign_*.cfg` files contain campaign-specific events. Many of these are plot spoilers.

As the first line of the Git commit messages is shown in Github’s directory listings, I'll try to avoid adding spoilers there.


In-game description (for the add-ons server)
--------------------------------------------

This is an improved version of the Non-Fatal Wounds and Non-Fatal Wounds: Maimed Edition add-ons which acts as a standalone addon with many new features.

When a unit reaches 0 hp, it’s removed for the current scenario and receives an injury instead of dying (except if receives a 'death' wound).
If you activate wounds, most of them are based on fatal attacks received, the type of terrain where the victim is standing on, and other additional conditions. Other wounds and death depend solely on chance. In like manner, all wounds are designed to be applied to units that can suffer or are affected in some way. Magical wounds for magical units, wounds on arms, legs, or wings in races that possess such limbs, mechanical units are immune to fear, ghosts can't receives ghost wound, undeads can't receives the undead wound but can receives the ghost wound, etc.
The injured or wounded units go back into the “recall” pool for next mission.
If a unit is killed by a plague attack and isn't unplagueable, receives the death wound even if you don't choose the death wound as an option, so be careful.

This does not protect your heroes or other specific units — you’ll still lose if any character who has to survive is wounded. The enemy isn’t going to miss the chance of finishing the battle by letting a leader escape. Some mainline campaign events have also been adapted to change their behavior depending on the situation.

This will affect campaign balance, but makes the RNG much less punishing of mistakes, while still being not too lenient (losing a unit still stings because you lose the opportunity to level them up).

This was inspired by Armagedonus’s suggestion in [a thread discussing save-scumming](https://r.wesnoth.org/p641153).


**CURRENT WOUNDS**

* Amnesia (lose 2 xp/turn) > All units, random
* Broken arm (-20% non-magical damage) > Races with arms, random
* Broken wing (-20% mp) > Races with wings, random
* Broken leg (-20% mp) > Races with legs, random
* Broken rib (-30% impact resistance) > Not mechanical, wounded with impact attack
* Burned (-30% fire resistance) > All units, wounded with fire attack
* Captured (increased recall cost based on level) > All units, random but on leaders and heroes is much more probable
* Concussion (-20% magical damage) > Units with magical attacks, random
* Coward (-15% accuracy) > Not mechanical, random
* Fear of weapon (reduced 1 strikes against what wounded them) > Not mechanical, wounded with any weapon
* Fear of the dark/light (reduced 1 strikes during the time they were wounded) > Not mechanical, wounded on day, night, or underground
* Fear of terrain (increased 1-2 move cost for the terrain they were wounded on) > Not mechanical, wounded on some terrains
* Fear of fog (-40% mp when fog is active) > Not mechanical, wounded with fog active
* Frostbite (-30% cold resistance) > All units, wounded with ice attack
* Gash (-30% blade resistance) > All units, wounded with blade attack
* Infection (10% chance to be poisoned every turn) > Not mechanical or not unpoisonable, random
* Sick (20% chance of being slowed every turn) > All units, random
* Insanity (berserk on melee attacks) > Units without berserk ability
* Maimed (-20% hp) > All units, random
* Necrosis (-30% arcane resistance) > Not mechanical, random
* Damage (-5% mp, hp, damage and accuracy) > Mechanical, random
* Short-term memory loss (resets experience) > Units with more than 1/2 of the max experience, random
* Wild magic (magical attacks now are 50% chance) > Units with magical attacks, random
* Plagued (equivalent to death) > Units non unplagueables, killed with plague attack, allways

**OPTIONAL WOUNDS**

* Death (definitive death) > All, random
* Turning into a ghost (custom ghost, cant advance beyond level 2) > Not spirit or ghost, random
* Turning into a zombie (custom zombie) > Not undead, random
* Paper cut (the second worst thing to ever happen) > All units
* Stepping on a Lego (the worst thing to ever happen) > All units


**WOUNDS HEALING SYSTEM**

* Some wounds can be healed directly facing your fears.
* Fear of terrain: 10% chance of recovery when defeating an opponent while standing on the terrain unit is scared of.
* Fear of weapon: 20% chance of recovery when defeating an opponent wielding the weapon the unit is scared of.
* Fear of light/dark: 5% chance of recovery when defeating an opponent during the day/night.
* Fear of fog: 5% chance of recovery when defeating an opponent when fog is active.
* Coward: 20% chance of recovery when defeat an enemy 1 level higher or at his highest level.
* Short-term memory loss: is an 1-use wound and is healed inmediately.
* Captured: is an 1-use wound and is healed when the unit is recalled the first time.
* The rest of wounds can be healed choosing a recover AMLA instead of the advancement or default AMLA (still can advance later to the next advancement).
* Optional wounds can't be healed at all.


Feedback
========

Please use either Github’s issue tracker, or the [general feedback thread](https://forums.wesnoth.org/viewtopic.php?t=56108).
