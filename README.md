Mioka GTK Theme
===============

Mioka is a a fork of the awesome [Moka](https://github.com/moka-project/moka-gtk-theme) theme with some tweaks and added mintish green freshness.
Mioka GTK Theme is distributed under the terms the GNU GPL v.3

###Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * python3

To render new icons from their source SVG files, run the following:

    ./render-pngs.py

If it's throwing an error, the script may not be executable, try:
	
	chmod +x render-pngs.py

This script will look in the source directories (../src/*) and render the respective icons (provided there are changes).

-----------
