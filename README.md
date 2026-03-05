# 📐 2D Room Planner

A powerful, interactive 2D interior design and room planning web application. Built with a professional Photoshop-like dark mode interface, it allows users to draft floor plans, arrange furniture, and manage architectural structures using an advanced drag-and-drop system.

Designed for precision, it features a layer system, collision detection, dynamic dimensioning, and project state management.

## ✨ Key Features

### 🛠️ Advanced Object Management

- **Drag-and-Drop Interface:** Smoothly move, rotate, and place objects and room fixtures (doors/windows).
- **Layer System:** Organize objects into different layers (e.g., place a rug on Layer 1 and a table on Layer 2). Objects on different layers bypass collision detection. Toggle layer visibility directly from the Layers Panel.
- **Multi-Selection:** Hold `Shift` while clicking to select multiple objects and drag them together as a group.
- **Position Locking:** Lock individual objects in place to prevent accidental movements while editing nearby items.

### 📏 Precision & Measurement Tools

- **Smart Snapping:** \* _Snap to Grid:_ Magnetically align objects to a customizable grid.
  - _Snap to Walls:_ Automatically snap furniture to the edges of the room when dragged close to a wall.
- **Dynamic Auto-Dimensions:** Automatically displays the real-time distance between objects (on the same layer) and the room walls.
- **Free Ruler Tool:** A click-and-drag crosshair tool to measure exact distances between any two points on the canvas.
- **Area Calculator:** Real-time calculation displaying Total Area, Occupied Area (only counting visible layers), and Free Area in square meters (m²).

### 🚪 Structural Fixtures

- **Doors and Windows:** Easily attach fixtures to the Top, Bottom, Left, or Right walls.
- **Smart Doors:** Doors display their swing trajectory and highlight in red if their path is blocked by an object. You can instantly flip the swing direction with a single click.

### 💾 Project State & i18n

- **Save & Load (JSON):** Export your entire project—including room dimensions, objects, layers, and UI settings (like grid preferences and language)—into a `.json` file. Import it later to resume exactly where you left off.
- **Undo / Redo:** Full history tracking. Made a mistake? Just hit `Ctrl+Z`.
- **Internationalization (i18n):** Native support for 20 languages (English, Portuguese, Spanish, French, German, Italian, Chinese, Russian, etc.), switchable on the fly via the Settings menu.

## 🖥️ User Interface Overview

The UI is inspired by professional design software, featuring a dark theme by default:

- **Top Bar:** Quick access to Undo/Redo, Save/Import, Project Name, Area Metrics, Zoom controls, and App Settings.
- **Left Sidebar (Tools):** Room dimensions, Snapping toggles, Grid settings, Ruler activation, and forms to create new objects and structures.
- **Right Sidebar (Inspector):** \* _Object Inspector:_ Edit dimensions, layer, color, name, rotation, and lock status of existing objects.
  - _Layers Panel:_ View active layers and toggle their visibility with the eye icon.
- **Main Canvas:** The interactive grid where the design comes to life.
