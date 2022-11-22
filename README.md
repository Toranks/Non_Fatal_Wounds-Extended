Non-Fatal Wounds
================

This is an add-on for the game [Wesnoth](https://www.wesnoth.org/).

Spoiler warning
---------------

The `utils/campaigns.cfg` and `utils/campaign_*.cfg` files contain campaign-specific events. Many of these are plot spoilers.

As the first line of the Git commit messages is shown in Github’s directory listings, I'll try to avoid adding spoilers there.

In-game description (for the add-ons server)
--------------------------------------------

When a unit reaches 0 hp, instead of dying, it’s merely removed for the current scenario. The wounded units go back into the “recall” pool for next mission!

This will affect campaign balance, but makes the RNG much less punishing of mistakes, while still being not too lenient (losing a unit still stings because you lose the opportunity to level them up). It also doesn’t affect units that the scenario objectives require you to keep alive.

This was inspired by Armagedonus’s suggestion in [a thread discussing save-scumming](https://r.wesnoth.org/p641153).

This does not protect your heroes — you’ll still lose if any character who has to survive is wounded. The enemy isn’t going to miss the chance of finishing the battle by letting a leader escape.

Feedback
========

Please use either Github’s issue tracker, or the [general feedback thread](https://r.wesnoth.org/t51849).


Changelog Extended Version
=========
- Traducción al español
- Unificado original y Maimed Edition
- Mejor menú de selección
- Ajustadas probabilidades de algunas lesiones y añadidos algunos filtros (como lesiones que afectan a la magia sólo en unidades con magia) para que sean más consistentes
- Color del texto rojo, más visible
- Erratas de texto
- Hecho algunos textos traducibles con _ delante
- Filtrado "Captured" para que no se conceda a una unidad de la IA, para evitar error Lua. > Pendiente de averiguar causa exacta
- captured_unit_dummy > captured_unit_display