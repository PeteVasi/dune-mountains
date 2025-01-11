# Dune Mountains

Creating the best Dune board game map ever...

I started with [ScottE's map](https://boardgamegeek.com/thread/531160/scotts-dune-build-project)
as I've played on a print of this board for 10+ years.

I learned to cut a circular board on my table saw:

![Table saw circular cut](0-map/wood-board.jpg)

Took a modified version of the map, had it printed poster-sized, glued it on, and cut to fit:

![Poster Dune map](0-map/wood-poster.jpg)

3d-printed player holders that slide onto the board and are movable for more or fewer players:

![3d-printed player holder](0-map/wood-player.jpg)

But next ... I want to print mountains to attach to the board and make it fully 3d.

## 1. Image Editing Attempt

Started with some heightmaps found from https://tangrams.github.io/heightmapper/

Like this:

![Heightmapper sample](1-image-editing/heightmapper-1722820530771-size512.png)

I take a mountain section of the board:

![False Wall West](0-map/fww-crop.jpg)

Mask out the piece that I need:

![FWW Mask](1-image-editing/dune-height-fww-mask.png)

And crop out the heightmap to fit in that section:

![FWW Height](1-image-editing/dune-height-fww.png)

OpenSCAD is a bit slow to work with it, but looks ok:

![OpenSCAD Render](1-image-editing/screen-scad.png)

Just opening it directly in Cura is actually pretty controllable:

![Cura Render](1-image-editing/screen-cura.png)

But what I really need is mountains shaped to the territory, sloping down to the edges naturally.

