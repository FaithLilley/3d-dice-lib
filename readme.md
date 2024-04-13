# FAITH'S 3D DICE TESTBED

Experimenting with digital dice for TTRPG sites.

Currently, this is a bit of a mess - a mish-mash of different libs & code that needs to be pulled apart, optimised, and put back together to be modular.

## FEATURE SET

- Simulate actual dice rolling as 3d objects.
- Provide a deterministic rolling model (provide the desired result in advance).
- Synchronise with multiple users.
- Multiple dice shapes/models/faces.
- Textures & colours for dice.

## DEMO PAGE

https://faithlilley.github.io/3d-dice-lib/

## LIBRARIES

- [three.js](https://threejs.org/) - a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.
- [cannon.js](https://github.com/schteppe/cannon.js) - a lightweight 3D physics engine, written entirely in JavaScript.
- [jQuery](https://jquery.com/) - pretty much fundamental.

## ADDITIONAL SOURCE & INPIRATION

- https://github.com/MajorVictory/3DDiceRoller
- http://www.teall.info/2014/01/online-3d-dice-roller.html
- Star Wars™ RPG font from The Alexandrian
http://thealexandrian.net/wordpress/37660/roleplaying-games/star-wars-force-and-destiny-system-cheat-sheet
- Star Wars™ Armada font from err404
https://boardgamegeek.com/filepage/116568/armada-icon-fonts
- Star Wars™ X-Wing font from geordanr
https://github.com/geordanr/xwing-miniatures-font
- Star Wars™ Legion font from lyerelian
https://github.com/lyerelian/Legion-font
- autodice.php contains an example of using the JavaScript PostMessage API from another tab to trigger dice throws.

Note that the [Dice So Nice](https://foundryvtt.com/packages/dice-so-nice/) module for FoundryVTT is based on the same code.