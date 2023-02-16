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

v2.2
============
- Separated arm and wing wounds, so now Drakes can have both wounds.
- Adjusted probabilities for almost all wounds, for example now sick and infection are more probable when the unit is wounded when is slowed or poisoned, respectively.
- Female names on many wounds (for translations), and changed names for more consistency.
- Ghosts and spirits now are properly filtered on corresponding wounds. Ghosts can't be ghost wounded or receives bone wounds, and other units can't be ghost wounded twice.
- Insanity, Amnesia, Wild magic, Infection, and Sick wounds doesn't applies twice. Others can.
- Fixed wounds that if suffered a second time after being healed, it would automatically heal again on the next post_advance event (display_healing cleaned)
- New Wounds: Nebulaphobia, fear of fog, -40% movement when fog is active. Damaged, only mechanic units, -5% to HP, movement, damage and accuracy (Repairable).
- Fixed excess of "Capture" again.
- Better LoW S19 Costly Revenge filter.
- Support to filter future 'bird' race.
- Undead and ghost wounds debuffed, they are excessively powerful.
- Filtered plagued wound to no be activated if the victim is on a village.
- Fear of weapon -20% accuracy extra when effect applies, and applies also when the enemy carries that weapon, even if is not using it.
- Increase chance of healing Fear of fog to 10% when fog is active
v2.2.1
- Drain ability on ghost wound doesn't applies to weapons that already have drain or heal.
- Undead trait doesn't applies twice.

v2.3
============
- New Option: Elementals. Set of 6 differents permanent elemental wounds that triggers randomly on certain conditions. Fire, water, poison, earth, arcane and wind. All of them have some regeneration methods.
- Removed exception of Surprise Attack from Advanced Wesnoth Wars to the Fear of Weapon wound, now is fully compatible. Update AWW if is the case.
- Ghosts with colored transparent image, with bluish tint instead of totally blue.
- Ghost and undead wounds indicated as red trait.
- Fixed damaged wound, now can't be healed for free the second time.
- Undead variations filtered on arm, leg and wing wounds.
- Minor changes on probabilities.
v2.3.2
- New event SOTBE S8, first elf death is "Execution".
v2.3.3
- Scrolling screen to the place where floating texts appear, except the healing points of elementals.
- New event SOTBE S10, the unit that blows up the bridge and and the stranded units on the other side allways receives "death" wound. This is mandatory to mantain plot consistency with the saurian units.
- New event SOTBE S14, Thelarion allways receives frostbite wound.
- New event EI S12 (Evacuation), you can choose if you want units stranded on the other side of the bridge to always receive death wound or not.
- Slow and poison status are checked simultaneously to sick and infection wounds, making them even more probable. Slowed>sick takes precedence.
- Damaged much more probable.
- Agoraphobia probability to half, because flat terrains is much frequent.
- Fixed sick, now works as expected, at new turn instead of turn end.
- Bigger help icon.

v3.0
============
- Deactivation option changes if you manually deactivates NFW to reflect that.
- Fear of weapon now do -50% strikes instead of -1 strike and can not be suffered several times (even if it is to different weapons)
- Translatable female version of some messages.
- Amnesia now works correctly when the unit have 2 or less XP.
- Changed float text of wounds recoverings and elementals healings with animation + float text.
- Fixed first wound message, that reappears on every scenario instead of only once per campaign.
- New healing method, now multiple wounds of the same type are correctly managed. If the unit has two wounds of the same type, the effects are cumulative, but only can heal one per AMLA or healing event.
- Time of day now filtered again by lawful or chaotic, to make compatible with differents time setups.
- General wounds rework, more harmful, included ghost, undead, and elementals.
- Improved some filters (mechanic units now doesn't receives maimed, light and dark fears are mutually exclusive, etc).
- Fixed bad filtered plant terrain, error present since Maimed Edition.
- New message when mechanical units are wounded or die.

v3.1
============
- Deleted duplicated macro.
- Added a way to avoid duplicate units on nfw_wounded variable.
- Reduced to half the chance to merfolk and naga gets aquaphobia.
- New event UTBS S12, "Destruction" when Aliens die.
- Changed uploading method on 1.17. Reset downloads: 22

v3.2
============
- Added define NON_FATAL_WOUNDS_EXTENDED
- Compatibility with Advanced Wesnoth Wars AMLA Bonus when a unit chooses a healing AMLA, optional.
- Agoraphobia not received on underground or indoors, but still can be suffered (movement cost applies to flat terrain, no matter the environment).
- Removed debug message on cowardice healing.
- New event NR S6a, "Dissolution" of Malifor.
- New event NR S6 and following, optional wounds for Sister Thera and Father Morvin, excluded some wounds and death.
- New event NR S7a, "Capture" of Ro'Sothian and Ro'Arthian.
- Fixed healing when the unit have two wounds, and choose healing > normal level up > healing, and the normal level up heals accidentally the second wound.
- Completely rework of the wounds filter and probabilities:
 * Avoided improbable stack overflows (>800)
 * Mechanical units now have is own set of wounds, with less probability to be destroyed than living units. Can only receives some wounds, included the exclusive wounds damaged and destruction.
 * Death, funny and elemental wounds triggers on separated events, and can be activated or deactivated independently of normal Wounds.
 * Captured triggers on a separated event for heroes, to increase probability only on heroes.
- New wound: Destroyed, same as death but for mechanic units. Rot, same as necrosis but for mechanical units.
- New funny wounds: Jinx, Dumb, Angel, Devil.
- New fear: Fear of enemy, same debuffs as fear of weapon, but applies to the unit type that hurts you.
- Float text when normal wounds are disabled and a unit is directly sent to recall list.
- All messages and floating text are now optional independently and can be activated even if Wounds are deactivated.
- Help menu revised: Wounds divided in two pages and added indication of chance % for all wounds.
- Mechanical units filtered by trait or race, to be sure.
- Excluded Drake Clasher tree unit types from broken wing, because they don't use their wings to fly.
- Added icon to healing advancements. Different icon for Rot and Damaged.
- Magical units treated as if there were ghosts or elementals and Rocs as birds (Era of Magic).
- Kamikaze units have a 66% possibility of die with death enabled (Era of Magic).
- Dimensional Portal with soul catcher now works properly, same as plagued units, with an exclusive info message (Era of Magic).
- The unit with Collar of Recall will not die or receive any wound, but the third time lost his HP, it will die definitely (To Lands Unknow).
- Units without name shows "This unit" (translatable) instead of a blank space on the wounds messages.
- Messages compatible with female units that doesn't have a female unit type name.
- When a unit type or weapon doesn't have a translatable name or, for whatever reason, is not detected, the respective "fear of" wound is now skipped.

v3.3
============
- Elementals can't transform to undead.
- Help menu updated with Era of Magic units.
- New event: TLU S12, Malib units on your side always receives death wound.