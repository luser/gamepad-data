gamepad-data
============

This repository is an experiment in collecting data about various
game controllers in support of the [W3C Gamepad API] [1].

[1]: https://dvcs.w3.org/hg/gamepad/raw-file/default/gamepad.html

controllers.json
================

This file contains information about the physical layout of controls
on specific controllers.

mappings.json
=============

This file contains mappings indicating how the physical controls
of a specific controller are exposed from a particular driver.

Controller Layout
=================

Controllers are defined in terms of a "platonic ideal" of gamepads, as
expressed in this diagram:
![Gamepad Layout](https://raw.github.com/luser/gamepad-data/master/gamepad.svg)
