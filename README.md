# M-ultiTool Support Tool
[![GitHub release](https://img.shields.io/github/release/Is-Butter/M-ultiTool-Support-Tool.svg)](https://github.com/Is-Butter/M-ultiTool-Support-Tool/releases) [![License](https://img.shields.io/github/license/Is-Butter/M-ultiTool-Support-Tool.svg)](LICENSE) [![Version](https://img.shields.io/badge/version-2.0.0-green.svg)](https://github.com/Is-Butter/M-ultiTool-Support-Tool/releases) ![Source](https://img.shields.io/badge/Source-Closed-red.svg)

**M-ultiTool Support Tool** is a companion mod for *The Long Drive* that helps users diagnose why they may have failed MultiTool's validation checks. It provides a simple, user-friendly diagnostic window that appears only when the game is paused. The window is draggable so that it won’t obstruct important UI elements, and it can be toggled open or closed using the F2 key. Optionally, the tool offers a manual reset function (with a safety toggle and warning) to clear the validation status and distance data.

> **Note:** This mod is closed source.

---

## Features

- **Pause Menu Diagnostic Window:**  
  - Opens automatically when the game is paused (Time.timeScale == 0) and toggled via F2.
  - Draggable window so you can reposition it if needed.
  
- **User-Friendly Diagnostics:**  
  - Displays a concise message explaining potential reasons for validation failure without revealing sensitive internal logic.
  
- **Reset Functionality:**  
  - Provides an optional manual reset button to clear validation status and distance, with a safety toggle and warning.
  
- **Automatic Data Update on Menu Load:**  
  - The tool resets validation data automatically when exiting a save and returning to the main menu.

---

## Installation

1. **Download the DLL:**
   - Visit the [Releases](https://github.com/Is-Butter/M-ultiTool-Support-Tool/releases) page and download the latest `M-ultiTool-Support-Tool.dll`.

2. **Copy the DLL to Your Mods Folder:**
   - Locate your game installation directory.
   - Navigate to the `Mods` folder (or the folder required by your mod loader).
   - Paste the `M-ultiTool-Support-Tool.dll` file into that folder.

3. **Launch the Game:**
   - Start *The Long Drive* as you normally would.
   - When you pause the game, press F2 to open the diagnostic window.
   - If the tool does not function immediately, try loading or starting a new game and then returning to the main menu.

---

## Usage

- **Diagnostic Window:**  
  When the game is paused, press F2 to toggle the diagnostic window. The window displays:
  - A brief message about the validation status.
  - A warning about resetting validation data.
  - An optional reset button (if enabled) that clears your validation status and distance data.

- **Reset Option:**  
  The reset button is only visible if enabled by a toggle in the window. Use it to clear your saved validation data if needed.

---

## Troubleshooting

- **Window Not Appearing:**  
  - Ensure the game is paused (Time.timeScale == 0) since the window only appears when paused.
  - Press F2 to toggle the window open.
  
- **Reset Button Issues:**  
  - If the reset button isn’t visible, check that the mod’s configuration has the reset option enabled.
  
- **Other Issues:**  
  - Verify that the DLL is in the correct `Mods` folder.
  - If you continue to experience issues, please [open an issue](https://github.com/Is-Butter/M-ultiTool-Support-Tool/issues) with detailed information.

---

## Credits

- **Mod Author:** Is_Butter  
- **Special Thanks:** Thanks to the developers of MultiTool, TLDLoader, and the supportive modding community for their contributions and inspiration.

---

Enjoy *The Long Drive* with enhanced diagnostic support and happy modding!
