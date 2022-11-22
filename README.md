Non-Fatal Wounds
================

This is an add-on for the game [Wesnoth](https://www.wesnoth.org/).
* Author :  [CookieLord](https://forums.wesnoth.org/memberlist.php?mode=viewprofile&u=248402)
* Mantainer : [Toranks](http://toranks.blogspot.com/)
* Changelog : see [CHANGELOG.md](CHANGELOG.md)
* License : [GNU-GPL](LICENSE.md)
* Code Repository [on GitHub](https://github.com/Toranks/Non_Fatal_Wounds-Extended)
* Dedicated [forum thread](https://forums.wesnoth.org/viewtopic.php?t=56108)

Spoiler warning
---------------

The `utils/campaigns.cfg` and `utils/campaign_*.cfg` files contain campaign-specific events. Many of these are plot spoilers.

As the first line of the Git commit messages is shown in Github’s directory listings, I'll try to avoid adding spoilers there.


In-game description (for the add-ons server)
--------------------------------------------

This is an extension of the Non-Fatal Wounds add-on by Octalot and Armagedonus that adds lasting injuries to your units whom nearly escaped death.

When a unit reaches 0 hp, instead of dying, it’s removed for the current scenario and receives an injury. The wounded units go back into the “recall” pool for next mission.

This will affect campaign balance, but makes the RNG much less punishing of mistakes, while still being not too lenient (losing a unit still stings because you lose the opportunity to level them up). It also doesn’t affect units that the scenario objectives require you to keep alive.

This was inspired by Armagedonus’s suggestion in [a thread discussing save-scumming](https://r.wesnoth.org/p641153).

This does not protect your heroes — you’ll still lose if any character who has to survive is wounded. The enemy isn’t going to miss the chance of finishing the battle by letting a leader escape.



CURRENT INJURIES

Amnesia (resets exp)

Broken arm (-20% non-magical damage)

Broken leg (-20% mp)

Broken rib (-10% impact resistance)

Burned (-10% fire resistance)

Captured (increased recall cost based on level untill you recall them)

Concussion (-20% magical damage)

Coward (-10% accuracy)

Fear of weapon (reduced 1 strikes against what wounded them)

Fear of terrain (increased 1 move cost for the terrain they were wounded on)

Fear of the dark/light (reduced 1 strikes during the time they were wounded)

Frostbite (-10% cold resistance)

Gash (-10% blade resistance)

Infection (chance to be poisoned)

Insanity (berserk on melee attacks)

Maimed (-15% hp)

Short-term memory loss (lose 1 xp/round)

Wild magic (magical attacks now are 50% chance)



OPTIONAL INJURIES

Death (they are dead)

Paper cut (the second worst thing to ever happen)

Stepping on a Lego (the worst thing to ever happen)

Turning into a ghost (custom ghost, cant advance beyond level 2)

Turning into a zombie (custom zombie, heavily debuffed ranged attacks)



INJURY HEALING SYSTEM

Injured units who receives an AMLA removes the injury

Injuries that can be toggled off cant be healed

Fear of terrain: 10% chance of recovery when defeating an opponent while standing on the terrain unit is scared of

Fear of weapon: 20% chance of recovery when defeating an opponent wielding the weapon the unit is scared of

Fear of dark/light: 20% chance of recovery when defeating an opponent during the day/night


Feedback
========

Please use either Github’s issue tracker, or the [general feedback thread](https://forums.wesnoth.org/viewtopic.php?t=56108).
