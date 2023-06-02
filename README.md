Non-Fatal Wounds Extended
================

This is an add-on for the game [Wesnoth](https://www.wesnoth.org/).
* Authors :  [CookieLord](https://forums.wesnoth.org/memberlist.php?mode=viewprofile&u=248402), [stevecotton - Octalot](https://github.com/stevecotton), [Toranks](http://toranks.blogspot.com/)
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

* When a unit reaches 0 hp, it’s removed for the current scenario and receives an injury instead of dying (except if receives a 'death' wound). This unit go back into the recall list for next mission with the wound received.

* If you activate wounds, most of them are based on fatal attacks received, the type of terrain where the victim is standing on, and other additional conditions. Other wounds and death depend solely on chance. In like manner, all wounds are designed to be applied to units that can suffer or are affected in some way. Magical wounds for magical units, wounds on arms, legs, or wings in races that possess such limbs, mechanical units are immune to fear, ghosts can't receives ghost wound, undeads can't receives the undead wound but can receives the ghost wound, etc.

* There are more than 50 psychological and physical wounds, plus 3 fears (to the race, weapon, and type of the enemy) that can have a virtually infinite variety. Optional wounds are death, undeath, ghosts, elementals and funny wounds. Ghost, undeath, elementals and some funny wounds affect not only the unit's stats, but also its appearance and abilities, and are permanent.

* If a unit is killed by a plague attack and isn't unplagueable, is lost even if you don't choose the death wound as an option, so be careful. You can disable this behavior by also disabling all basic wounds.

* Almost all wounds -except for optional wounds and plagued- can be healed with different methods.

* All wounds info, probabilities, and healing methods can be consulted at any time in the optional help menu, with the possibility of disable the addon for certain scenarios, or change the available wounds and other options.

* This does not protect your heroes or other specific units, you'll still lose if any character who has to survive is wounded. The enemy isn't going to miss the chance of finishing the battle by letting a leader escape. All mainline campaigns and some UMC campaigns has been adapted to change their behavior on certain events depending on the situation, some of them optionals.

* This addon may affects campaign balance, but makes the RNG much less punishing of mistakes, while still being not too lenient since you will lose the opportunity to continue leveling on that scenario, in addition to an important debuff that will be expensive to cure (if possible). With deaths activated, the campaigns will remain balanced in most. The severity of the consequences of injuries has been greatly increased compared to the Maimed version.

This was inspired by Armagedonus’s suggestion in [a thread discussing save-scumming](https://r.wesnoth.org/p641153).


Feedback
========

Please use either Github’s issue tracker, or the [general feedback thread](https://forums.wesnoth.org/viewtopic.php?t=56108).
