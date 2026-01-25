---
layout: default
title: Getting Started
nav_order: 1
---

# Getting Started with PlayModeSaver

**Stop losing your best work when you hit Stop.**  
PlayModeSaver is the ultimate Unity tool for retaining runtime changes, creating presets, and visualizing scene modifications in real-time.

---

## 🚀 Quick Start in 60 Seconds

1.  **Install** the plugin (see [Installation](docs/installation.html)).
2.  Enter **Play Mode**.
3.  **Tweak** your scene:
    *   Change values (move objects, adjust colors).
    *   Add new Components.
    *   Create new GameObjects.
4.  Notice the **Blue** (Modified) and **Green** (New) highlights in the Hierarchy.
5.  Exit Play Mode. A **Restore Window** will pop up.
6.  Click **"Apply All"** to keep your changes!

---

## Why PlayModeSaver?

| Problem | PlayModeSaver Solution |
| :--- | :--- |
| "I forgot to copy component values!" | **Auto-detects** every changed field in real-time. |
| "I added a perfect particle effect but lost it." | **Tracks new GameObjects & Components** automatically. |
| "Is this value different or default?" | **Visual Highlights** show you exactly what changed. |
| "I need to save this specific setup for later." | **Presets** let you save and load runtime configurations. |

## Key Concepts

*   **Session**: A recording of all changes made during a single Play Mode run.
*   **Snapshot**: A backup of the scene state taken *before* you enter Play Mode.
*   **Change Record**: A specific modification (e.g., `Transform.position` changed).
*   **Attributes**: Use `[SaveOnPlayModeExit]` to enforce saving for specific fields.

[Install Now](./docs/installation){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View Features](./docs/features){: .btn .fs-5 .mb-4 .mb-md-0 }
