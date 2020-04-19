---
title: API Reference
nav_order: 1
has_children: false
parent: Library Documentation
permalink: /library/upygamereference
---

# Python uPyGame API Reference

Here is listed and explained all Pokitto specific MicroPython functions, part of the uPyGame library.

<h1> uPyGame <span class="label label-green">namespace</span></h1>

<h2> TAS (Tiles And Sprites) <span class="label label-purple">class</span></h2>

This class is ment to be used in TAS screen mode. That is a special mode where the graphics primitive methods (like drawCircle()) cannot be used. The normal drawText() can be used but each character takes one sprite, so the methods of this this class is recommended instead. 

### Functions

| Name                                                                     | Description                                                  |
|:-------------------------------------------------------------------------|:-------------------------------------------------------------|
| [setCursor()]({{site.url}}{{site.baseurl}}/library/upygame/setcursor)               | Set the cursor position.                                          | 
| [printString()]({{site.url}}{{site.baseurl}}/library/upygame/printstring)       | Print a text.                                             |
| [printInteger()]({{site.url}}{{site.baseurl}}/library/upygame/printinteger)             | Print an integer number.                               |
| [clear()]({{site.url}}{{site.baseurl}}/library/upygame/clear)     | Clear all UI tiles, i.e. all text and graphics.                   |
| [setTile()]({{site.url}}{{site.baseurl}}/library/upygame/settile)           | Set the content of a tile.                   |
| [fillRectTiles()]({{site.url}}{{site.baseurl}}/library/upygame/fillrecttiles)                 | Fill the rectangular are of tile with a tile content.                                     |
| [drawBox()]({{site.url}}{{site.baseurl}}/library/upygame/drawbox) | Draw a box with borders.                                             |
| [drawGauge()]({{site.url}}{{site.baseurl}}/library/upygame/drawgauge) | Draw a gauge.                                             |


<h2> Other classes  TODO <span class="label label-purple">class</span></h2>

