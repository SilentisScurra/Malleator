# PixelForge [Malleator]

A lightweight, zero-dependency pixel art editor built with HTML5 Canvas and vanilla JavaScript. Designed for workflow directly in the browser.

## Features

* **Core Tools:** Pencil, Eraser, Shapes (Line, Box, Circle), Bucket Fill, and Eyedropper.
* **Pro Navigation:** Infinite coordinate-based panning and scroll-wheel zoom. 
* **Dynamic Rulers:** Canvas rulers that automatically scale their increments (1, 5, 10) based on your current zoom level.
* **Auto-Palettizer:** Scans canvas luminance to generate a custom 16-color gradient bridge based on your drawing.
* **Procedural FX:** One-click 1px outlines and semi-transparent drop shadows. (Not very flexible but could be usefull)
* **I/O & History:** Save/Load PNGs, and full Undo/Redo state management.

## Controls

| Action | Input |
| :--- | :--- |
| **Draw / Pick** | Left-Click |
| **Alternate Color** | Right-Click |
| **Pan Canvas** | Spacebar + Drag OR Middle-Click |
| **Zoom** | Scroll Wheel |
| **Undo / Redo** | Ctrl + Z / Ctrl + Y |

## Getting Started

Clone the repository and open `Malleator.html` in any modern web browser. No build steps or local servers required.

## Tech Stack
* HTML5 Canvas
* Vanilla JavaScript
* CSS3
