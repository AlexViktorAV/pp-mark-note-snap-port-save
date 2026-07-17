[README.md](https://github.com/user-attachments/files/30107992/README.md)
# pp-mark-note-snap-port-save# ✒️ MNCMP Highlighter

A privacy-focused Chrome Extension built to provide robust on-page text highlighting, precision note-anchoring architecture, and screenshot stitching systems.

---

## 🚀 Core Features

### 🎨 Precision Highlighting & Painter Engine
- **Flexible Hue Tuning:** Built-in popup sliders control Hue, Saturation, and Brightness variables to dynamically match page layouts.
- **Painter Mode Toggle:** Keep highlighting mode continuously active for fast multi-selection workflows.
- **Intelligent DOM Merging:** Automatically identifies close boundary markings and merges continuous inline highlights to keep records cleanly grouped.

### 📌 Dynamic Sticky Notes Architecture
- **Geometric Visual Anchors:** Swap, drop, and drag visual layout indicators (Triangles, Circles, Squares, Crosses) onto targeted elements.
- **Dynamic Connection Vectors:** Arrows automatically anchor and calculate intersections directly from the note bounding box perimeter.
- **Double-Click Re-activation:** Notes stay hidden by default unless they contain text or are triggered explicitly via text double-clicks.

### 📸 Universal Capture Suite
- **Full Page & Window Snapping:** High-fidelity vertical stitching engines compile multi-view snapshots.
- **Smart Slicing Core:** Draws custom bounding boxes with responsive crosshair layouts that ignore infinite scroll lines.
- **Advanced Scrollbox Stitcher:** Intelligently loops through vertical or horizontal scrolling boxes (such as wide embedded data tables or side-panels), tracking viewport increments to export wide stitched outputs.
- **Clean Falloff Logic:** Strips CSS mask-gradients and shadows during active scrollbox cycles to prevent blurred stitch seams.
- **🚫 Element Hider (Ad-Blocker):** Point-and-click overlay mode targeting complex DOM paths with red dashed hover boxes to hide ads, banners, and static elements before capturing snapshots.

---

## 🛠️ Data Utility & Backups
- **Whitespace Compressor:** Detects large empty document gaps and merges them down into lightweight assets using a 4px dashed separator line.
- **Full Backup Engine:** Generates standalone structured `.zip` data models compiled alongside text outputs, notes summaries, and raw JSON configurations for easy portability.

---

## 🔒 Privacy Policy
MNCMP Highlighter operates as a **fully local client sandbox extension**. It requests zero analytics network connectivity permissions, tracking modules, or remote syncing channels. Review the complete [Privacy Policy](index.html) file inside this repository for individual API context permissions.
