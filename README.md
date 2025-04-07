# Render Selected Nodes

Plugin for [Autodesk Flame software](http://www.autodesk.com/products/flame).

Render selected Render or Write File nodes.  You might find this faster than using the Render List menu inside Batch.

## Installation

### Flame 2025 and newer
To make available to all users on the workstation, copy `render_selected_nodes.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `render_selected_nodes.py` to the appropriate path below...
|Platform|Path|
|---|---|
|Linux|`/home/<user_name>/flame/python/`|
|Mac|`/Users/<user_name>/Library/Preferences/Autodesk/flame/python/`|

### Flame 2022 up to 2024.2
To make available to all users on the workstation, copy `render_selected_nodes.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `render_selected_nodes.py` to `/opt/Autodesk/user/<user name>/python/`

### Last Step
Finally, inside of Flame, go to Flame (fish) menu `->` Python `->` Rescan Python Hooks

## Menus
- Right-click selected nodes in the Batch schematic `->` Render... `->` Selected Nodes

## Acknowledgements
Many thanks to [pyflame.com](http://www.pyflame.com)
