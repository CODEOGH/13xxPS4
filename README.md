\# PS4 13.xx Exploit Host By OGH



This repository contains the complete updated host environment for the \*\*PlayStation 4\*\* Kernel Exploit targeting supported 13.xx firmwares. The original basic layout has been completely redesigned into a modern "Cyber Dark" dashboard style, featuring high-end neon glowing components, an expanded brand identity, and complete optimizations for offline execution via the PS4 web browser.



\---



\## 🛠️ Detailed Changelog \& Visual Upgrades



\### 1. Unified Project Rebranding

\* \*\*Title Realignment:\*\* Changed all global text titles, custom `<title>` headers, and index parameters to \*\*`PS4 13.xx Exploit By OGH`\*\*.

\* \*\*RAW GAME Partnership:\*\* Integrated a striking digital header across the core framework reading \*\*`RAW GAME X OGH`\*\*.

\* \*\*Copyright Updates:\*\* Updated all project footers, meta descriptions, and code signature comments to read \*\*`© 2026 OGH`\*\*.



\### 2. Cyberpunk Palette \& Vibrant Orange Neon Glow

\* \*\*Premium Immersive Canvas:\*\* Integrated a full-screen, high-definition background graphic (`background.jpg`) configured to stretch fluidly (`background-size: cover`) and remain anchored (`fixed`) for flat screens and televisions.

\* \*\*Aggressive Heavy Typography:\*\* Forced all default log components and font weights to rendering variants of \*\*Black/Gras (`font-weight: 900` / `bold`)\*\* to maintain readability at a distance.

\* \*\*Orange Neon Accent Vectors:\*\* Styled titles, sub-headers, and the data log container border with electric orange luminous values (`text-shadow` and `box-shadow`) replicating a developer console environment.

\* \*\*Intensified Dynamic State Highlights:\*\*

&#x20; \* `\[OK / CACHED]` : Vivid Cyber Green (`#00ff66`) coupled with a localized neon text glow.

&#x20; \* `\[BAD / DANGER]` : Intense Crimson Red (`#ff2222`) coupled with an explicit error halo glow.

&#x20; \* `\[WARN / UPDATE]` : Fluorescent Amber Gold (`#ffcc00`) wrapped in a notification light burst effect.



\### 3. Extended Custom Brand Logo (300% Scale) \& Neon Spinner Ring

\* \*\*Dynamic Media Swapping:\*\* Replaced the default blank CSS loading wheel loop with your signature corporate media file (`logo.png`).

\* \*\*Scale Multiplying (300% Boost):\*\* Expanded the target rendering canvas of the central logo element to a heavy \*\*`180px`\*\* resolution (scaled up from the stock 60px size).

\* \*\*Sync-Rotated Glow Ring:\*\* Embedded a circular border outline (`border-radius: 50%`) with deep cyan properties (`#00d2ff`) and dual-layered shadows (`drop-shadow`). This system rotates concurrently with the branding assets during memory manipulation stages.



\### 4. Seamless Full-Screen Success/Failure Layouts

\* \*\*Exploit Success Handle (`success.jpg`):\*\* Instantaneously upon `body.done` activation, the processing interfaces, text lines, and animated loading indicators completely dissolve. The view transitions to a full-bleed splash displaying your green neon graphic with the message \*"Jailbreak success by OGH - PRESS THE (PS4) HOME BUTTON"\*.

\* \*\*Exploit Failure Handle (`failed.jpg`):\*\* Upon memory exceptions or kernel panics (`body.fail`), the viewport overwrites text artifacts immediately to show a full-screen warning image. This safely prompts users to reboot the system without layout breaking or text collisions.



\### 5. Architectural Offline Web Application Cache Fixes

\* \*\*Cache Manifest (`cache.appcache`) Structural Rebuild:\*\* Revised target indexes inside the explicit cache zones to ensure newly introduced visual elements are compiled on the system storage during first-load routines.

\* \*\*AppCache Asset Registration:\*\*

&#x20; ```ini

&#x20; # Graphical assets explicitly cached for standalone execution

&#x20; background.jpg

&#x20; logo.png

&#x20; success.jpg

&#x20; failed.jpg

&#x20; ```

\* \*\*Redirection Automation:\*\* Adjusted the execution delays and typography paths on the background installation page (`cache.html`) to ensure caching cycles refresh smoothly when offline operations are initiated.



\---



\## 📂 Final Host Directory Tree



Ensure the production folder layout on your remote hosting server, local computer, or ESP32 internal partition maps precisely to this structure:



```text

├── index.html          # Gateway Router (Firmware check, safety switches, and cache forwards)

├── jb.html             # Main Exploit Engine (Contains the 300% logo and full-screen screens)

├── cache.html          # Caching setup tool for standalone execution

├── cache.appcache      # Application network manifest and system hash records

├── jb.js               # Exploit coordination core script

├── ps4\_offsets.js      # Internal memory lookup tables for target Kernels

├── background.jpg      # Premium Cyber dark background file (Stored offline)

├── logo.png            # Main 180px branding logo image (Stored offline)

├── success.jpg         # Green neon controller success graphic (Stored offline)

└── failed.jpg          # Red neon hazard crash notice warning screen (Stored offline)

```



\---



> \*\*Disclaimer:\*\* This project is intended exclusively for research, educational, and legitimate homebrew development purposes. Use it only on hardware and software you own or are explicitly authorized to modify. The authors and distributors assume zero liability for software instabilities, data corruption, or collateral system issues resulting from its usage.

