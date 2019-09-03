# Pyint_Pixel-Painter
Pyint by Burak

A 64x64 Pixel art drawing program made in Python, Pygame.
A variety of colors, 126 colors to be specific. First palette has 96 and the second one has 30.
The tools:
  * Brush tool:
      Normal brush tool to draw and paint with adjustable size
  * Eraser tool:
      Normal eraser tool to erase with adjustable eraser size
      -- If you keep pressing right click, as you draw, your selected tool becomes the eraser.
  * Fill tool:
      Fills any empty closed space with your selected color. Using the recursive flood fill algorithm.
  * Color Picker tool (Eyedropper):
      Lets you pick the color in the canvas from a single pixel.
  
  Added a "dragon.txt" and "dragon.png", one of my artworks in my program. To test that everything worked fine.

# Hotkeys
Hotkeys:
  * CTRL + Z : Undoes your last (and only last) adjustment.
  * CTRL + Space : Deletes your layer (Not undoable)
  * CTRL + S : Saves your work. Same as "save as".
  * B : Select brush tool.
  * E : Select eraser tool.
  * G : Select fill tool.
  * I : Select color picker / eyedropper tool.
  * Right Click : Your selected tool becomes the eraser -until you release the button-.
  * 1 and 2 : Change between the color palettes faster.

# Requirements
Modules:
  * Python 3.x
  * Pygame
  * Tkinter
