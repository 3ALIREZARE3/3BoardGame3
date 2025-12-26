# 3BoardGame3 🎲
### The Ultimate Browser-Based Virtual Tabletop

**3BoardGame3** is a lightweight, single-file virtual tabletop (VTT) engine designed for playing custom board games, RPGs, or strategy simulations. It requires no installation, no login, and runs entirely in your browser.

![Version](https://img.shields.io/badge/version-5.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

### 🛠️ Architect Mode (Builder)
- **Grid Snapping:** Easily create maps by clicking on the grid.
- **Custom Sectors:** Rename and color-code specific houses/zones.
- **Map Resizing:** Define custom dimensions (Rows/Columns) and cell sizes.
- **Excel-Style Coordinates:** Rulers with A-Z columns and 1-99 rows.

### 🎮 Play Mode
- **Fog of War Logic:** In Play Mode, the grid disappears, leaving only your active "Houses" floating in void space.
- **Token Management:** Drag and drop players.
- **Graveyard System:** Drag players to the "Elimination Zone" when they lose.
- **Context Menu:** Right-click players to Rename, Recolor, or Delete.

### 🖥️ Advanced UI
- **Dual-Monitor Spectator:** Open a synchronized "Spectator Board" in a new tab. Moves update instantly across windows (perfect for casting to a TV).
- **Minimap:** Real-time navigation map for large grids.
- **3 Themes:** Switch instantly between **Neon Cyber**, **Dark Pro**, and **Paper Light**.
- **Save/Load:** Export your entire game state to a `.json` file and load it back later.

---

## 🚀 How to Use

### Hosting Online (GitHub Pages)
1. Rename the main file to `index.html`.
2. Upload it to a public GitHub Repository.
3. Go to **Settings > Pages** and enable it on the `main` branch.
4. Your game is now live!

### Running Offline
Simply double-click the `.html` file. No internet connection is required.

---

## 📖 User Guide

### Navigation
- **Pan Map:** Hold **Right Click** and drag anywhere on the background.
- **Zoom:** Use the slider in the right panel.
- **Scroll:** Use mouse wheel or scrollbars to move the rulers.

### Building a Map
1. Switch to **Build Mode** in the right panel.
2. Click anywhere on the grid to place a House.
3. **Left Click** a House to select it (Edit Name/Color in the right panel).
4. **Click "Resize Grid"** to change the map size.

### Playing
1. Switch to **Play Mode**.
2. Add players using the Left Panel.
3. Drag and drop tokens into Houses.
4. **Right Click** a token to edit it.

### Spectator Mode
Go to **View > Open Spectator Board**. Drag the new window to a second monitor. This view hides all administrative panels and only shows the map.

---

## 🛠️ Technical Details

- **Stack:** HTML5, CSS3 (Variables), Vanilla JavaScript.
- **Syncing:** Uses the `BroadcastChannel` API for instantaneous cross-tab communication without a backend server.
- **Persistence:** Uses JSON serialization for the Save/Load system.

---

## 👤 Author & Contact

**Alireza Zare**

- 📧 Email: [3alirezare3@gmail.com](mailto:3alirezare3@gmail.com)

If you have suggestions or want to contribute to the project, feel free to contact me!

---

*© 2025 3BoardGame3. All rights reserved.*
