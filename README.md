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

This is an extension of the Non-Fatal Wounds add-on by Octalot and Armagedonus that adds lasting injuries to your units whom nearly escaped death.

When a unit reaches 0 hp, instead of dying, it’s removed for the current scenario and receives an injury. The wounded units go back into the “recall” pool for next mission.

This will affect campaign balance, but makes the RNG much less punishing of mistakes, while still being not too lenient (losing a unit still stings because you lose the opportunity to level them up). It also doesn’t affect units that the scenario objectives require you to keep alive.

This was inspired by Armagedonus’s suggestion in [a thread discussing save-scumming](https://r.wesnoth.org/p641153).

This does not protect your heroes — you’ll still lose if any character who has to survive is wounded. The enemy isn’t going to miss the chance of finishing the battle by letting a leader escape.


**CURRENT INJURIES**

* Amnesia (lose 2 xp/round)
* Broken arm (-20% non-magical damage)
* Broken leg (-20% mp)
* Broken wind (-20% mp)
* Broken rib (-30% impact resistance)
* Burned (-30% fire resistance)
* Captured (increased recall cost based on level untill you recall them)
* Concussion (-20% magical damage)
* Coward (-15% accuracy)
* Fear of weapon (reduced 1 strikes against what wounded them)
* Fear of terrain (increased 1-2 move cost for the terrain they were wounded on)
* Fear of the dark/light (reduced 1 strikes during the time they were wounded)
* Frostbite (-30% cold resistance)
* Gash (-30% blade resistance)
* Infection (chance to be poisoned)
* Insanity (berserk on melee attacks)
* Maimed (-20% hp)
* Short-term memory loss (resets experience)
* Wild magic (magical attacks now are 50% chance)

**OPTIONAL INJURIES**

* Death (they are dead)
* Paper cut (the second worst thing to ever happen)
* Stepping on a Lego (the worst thing to ever happen)
* Turning into a ghost (custom ghost, can't advance beyond level 2)
* Turning into a zombie (custom zombie, heavily debuffed ranged attacks)


**INJURY HEALING SYSTEM**

* Injured units who advances have the option of removes the injury instead of the advance. The unit still can advance normally later
* Injuries that can be toggled off can't be healed by AMLA
* Fear of terrain: 10% chance of recovery when defeating an opponent while standing on the terrain unit is scared of
* Fear of weapon: 20% chance of recovery when defeating an opponent wielding the weapon the unit is scared of
* Fear of dark/light: 10% chance of recovery when defeating an opponent during the day/night


Feedback
========

Please use either Github’s issue tracker, or the [general feedback thread](https://forums.wesnoth.org/viewtopic.php?t=56108).
