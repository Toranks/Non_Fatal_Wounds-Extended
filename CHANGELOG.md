Changelog Non Fatal Wounds Extended Version

=========
- Traducción al español
- Unified original y Maimed Edition
- Better selection menu
- Red floating text, more visible
- Typos fixed
- Fully translatable
- Filtered "Captured" on IA units to avoid Lua error, reported on github. AI units still shows "Captured" floating text, and can be recalled, but at standard prize of 20. Maybe on the future will be solved.
- captured_unit_dummy > captured_unit_display
- Changelog and readme
- Allow undo recalls if not recalled a captured unit
- Amnesia is now Memory Loss and Short-term memory loss is Amnesia
- Fixed Scared of weapon, that didn't work to reduce -1 strikes (set_specials>attacks instead of abilities>attacks)
- Fixed fear of the light/dark, now doesn't trigger on dusk and afternoon
- Completely redo of the Randomizer with better filters and probabilities
- Death and undeath are now much more probable when is activated, same as funny wounds.
- Added broken wing instead of broken arm for birds, bats, and dragons
- Much more similar filters, as mechanic units not receives wounds related with mental status, magic alterations only for magical users
- New fear, Agoraphobia.

v1.1
===========
- Translatable unit type on death message
- Fixed typos on "Scared of X" (only affect spanish translation)
- When a unit die, captured, is plagued, or come back as undead or ghost, appears differents messages than if they are wounded, and these messages only appears for human players
- The message explaining the addon function only appears once on all the campaign.
- 30% chance to be captured if the unit is a non-essential hero, for more realism.
- Special events on units that you can kill but in doing so they change to your side or flee away, to prevent them from receiving a wound, which could be fatal. For now, I only filters Lady Outlaw. On "The Fall" (TROW) she "Surrender" when you beat her, on other situations she "Escape".

v1.2
===========
- Special event on "Temple in the Deep" (TROW), where you can choose if you want lose all units until Lord Lenvan dies or let NFW works normally.
- Icon on all NFW info messages.
- Fixed error on capture, that produces an excess of captures with respect to the other wounds on all units, not only heroes.
- Improved some extra filters.
- Burned wound now can be received on lava or volcano terrains.

v1.3
===========
- When the unit dies or is converted, first wound addon message doesn't appear if that's the case.
- Fixed "Captured" wound which is cleared on all units if there was more than one unit with it at the same time, bug present in the original version.
- Heal "Fear of light/dark" probability reduced from 10% to 5%
- Better filter of light/dark, now detects the unit hexagon instead of general time of day. >BUG
v1.3.1
- Added 'midnight' to filters

v1.4
===========
- Wounds now are optional, you can select original Non-Fatal Wounds behavior. Option to choose plagued units to die.
- Fixed Amnesia and short-term memory loss, that not worked properly
- Special event, only cosmetic, on the last scenario of TROW with Lord Jevyan, and fixed Lord Jenvan event, now only applies to the player.
- Cowardice now have a 25% probability of be healed when unit advances or kill a higher level unit, instead of 100%.
- Fixed photophobia and nictophobia, that doesn't work on 1.3 and 1.3.1

v2.0
============
- New Help Menu, with configurable options, included the possibility to deactivate Non-Fatal Wounds for single scenarios.
- Compatibility between "Fear of weapon" wound and Suprise Attacks from Advanced Wesnoth Wars. Now this wound doesn't applies to Surprise Attack kills.
- Cowardice healing probability reduced to 20%
- Amnesia, infection and sick fixed, before is activated every side turn, not every complete turn, error from 1.2
- Best deactivation method. When deactivated via campaign script or help menu, all units will now receive the "death" wound if Wounds is on, except in cases of plague. It has no effect on gameplay but adds more realism.
- Undeath zombies now have the image corresponding to the zombie variation of the original unit, and the color of the owner side.
- Translated weapons on ghosts (all languanges).
- Typo wind > wing
v2.0.1
- Divided Wounds help on two differents page due to 1.17 problem with long texts. Only for 1.17 server.
v2.0.2
- Fixed character error on 1.16 help menu. Only for 1.16 server.

v2.1
============
- Separated arm and wing wounds, so now Drakes can have both wounds.
- Adjusted probabilities for almost all wounds, for example now sick and infection are more probable when the unit is wounded when is slowed or poisoned, respectively.
- Female names on many wounds (for translations), and changed names for more consistency.
- Ghosts and spirits now are properly filtered on corresponding wounds. (Ghosts can't receive a ghost wound for example, as intended originally)