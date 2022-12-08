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
- Added broken wind instead of broken arm for birds, bats, and dragons
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