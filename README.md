Panda.js-physics-extention-plugin
=================================

Panda.js physics extention plugin

This plugin adds several features to the built in basic physics engine of Panda.js:

Added features:
* Collision between squares and circles is now far more realisic and follows the laws of physics. 
* Gravity is no longer affected by the mass of the object.
* The effect of the gravity on individual bodies can be regulated now with the body.gravityFactor property
* You can add squares that act like a wall with the body.fixed property.
* The bounciness of individual bodies can be regulated with the restitution property

Limitations:
* Polygons/lines/triangles are not supported
* Bodies won't rotate on collision

See live examples at:
http://vermeire.home.xs4all.nl/panda/
