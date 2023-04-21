# Marching Cubes v4.0 (Test Build)
 
## Installation and Execution
1. Download repository `Marching-Cubes-v4.0-Test_Build`.
2. Executable jar file located in `/src` folder.
3. Run via command line with `java -jar <install-location>/Marching-Cubes-v4.0.jar`

## Program Arguments
### Source Directory:
Directory containing slice data for program to read from.
### ISO Level:
Light intensity threshold for use in marching cube mesh construction.
#### Options:
- `0` - defaults to 0.1f
- `custom` - values above 0
### Fullscreen
Run window in fullscreen or windowed mode.
#### Options:
- `y` - run window in fullscreen mode
- `n` - run window in windowed mode
### Colours
Render mesh in coloured view.
#### Options:
- `y` - render mesh in RGB colours
- `n` - render mesh in white colour
### Window Width
Size of window width in pixels (not available if fullscreen is selected).
#### Options:
- `0` - defaults to 640 pixels
- `custom` - sets width of window
### Window Height
Size of window height in pixels (not available if fullscreen is selected).
#### Options:
- `0` - defaults to 480 pixels
- `custom` - sets height of window

## Program Controls
- `Esc` - Closes program
- `Arrow Up` - Moves camera up
- `Arrow Down` - Moves camera down
- `Arrow Left` - Moves camera left
- `Arrow Right` - Moves camera right
- `Page Up` - Moves camera forwards
- `Page Down` - Moves camera backwards
- `Mouse Drag (Left Click)` - Rotate mesh along X-axis and Y-axis
- `1` - Toggles auto rotation along X-axis
- `2` - Toggles auto rotation along Y-axis
- `3` - Toggles auto rotation along Z-axis
- `W` - Toggles wireframe render of mesh
- `R` - Resets mesh position, size and rotation