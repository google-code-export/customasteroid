# Launcher #


The new Launcher concept is centered around the "wheel". The wheel is an animated circle of items that can be rotated by turning the ASTEROIDs scroll wheel. Items are selected by pressing the center button.

The wheel is rendered in realtime and every widget (wheel item) may update it's label or icon at full speed (possibility to use animated icons and dynamic labels). Currently a clock widget (showing the current time as it's label) and a sd-card widget (as a preview of how ASTEROID specific menu items will be integrated) are impemented.
Only widgets that are rotated up to 45° above and below the center line get rendered to save performance.
The transition from one widget to the next one takes approximately half a second.
New widgets can easily be implemented by extending the [HomeItem](http://code.google.com/p/customasteroid/source/browse/src/org/asteroid/home/widgets/HomeItem.java?repo=home) class.


---
