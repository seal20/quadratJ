quadratJ
========

A set of macros for ImageJ and objectJ to analyze quadrats in ecology.

For the moment it is only for temperate corals and algae (what I am working on) and use the random points methods.
It is heavily inspired by CPCe (http://www.nova.edu/ocean/cpce/) but because this one is not free (libre) software and runs only under windows, I decided to start using imageJ (http://imagej.nih.gov/). The cell counter in imageJ was not enough and I used and modify the cell counter of the plugin objectJ (http://simon.bio.uva.nl/objectj/) to fit my needs.

To use it download the project file and open it with imageJ, I tested it with imageJ 1.48t and objectJ 1.03m

Features (in the last git version)
=======
From objectj:
* Allow non destructive marking of quadrat photos
* Produce the count results for each object

Customization:
* The project include categories suitable for temperate corals ecosystems in Shimoda, these categories are easily changeable but need to edit the macro file to change the shortcut.
* Draw a user defined number of random points on all the photos (see ToDo)
* Draw 64 points (8*8) on a grid within the user defined quadrat zone.

ToDo
====
* Make the number of points for the grid variable
* Add an if check if slope of the qudarat frame are 0 or infinity to be able to draw the grid in these case.
* User-Defined zone for random points
* Write the documentation
* Add the possibility to remove all markers elsewhere than in the objectj menu
* Add the possibilty to edit the object which will automatically edit the shorcut.
* Add the tracing area methods. but it is already possible in imageJ alone
* One day perhaps...completely fork objectj and create an independant plugin, if it seems good.
