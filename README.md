maps
====
Designed in Fall 2013

Try it here: http://christj6.github.io/maps

For people on the MAPS team: edit the files in the gh-pages branch to affect the displayed web page, not the master branch.

====================================================

Provides a visualization of the costs of brownfield development in Trenton.

A site administrator can update the "data.txt" to include information on the costs of removing certain chemicals (for example -- 5000 dollars to remove Lead from one property). A user can enter the address of a property (geocoding implemented so that the user need not type in an exact set of GPS coordinates) and the chemimcals contained at that property, and if the cost exceeds the user-set threshold, a red marker is placed. Otherwise, a green marker is placed. A user can also hover their mouse over a marker to display information about the property: chemicals present at the property, total cost of redevelopment, etc.



Features to add:

If the user changes the threshold in between two different queries, the previous markers won't update to respond to the new threshold.

Also, the program would probably be more useful if the process of associating chemicals with properties was automated, so a user could simply type in an address without typing in a list of chemicals.
