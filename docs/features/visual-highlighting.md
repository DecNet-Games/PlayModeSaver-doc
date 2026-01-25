---
layout: default
title: Visual Highlighting
parent: Features
nav_order: 2
---

# Visual Highlighting

Don't guess what changed—**see it**. PlayModeSaver enables real-time visual feedback directly in the Unity Editor.

## Hierarchy Highlighting

The Hierarchy window updates dynamically to reflect the status of your GameObjects.

*   <span style="color: #2ecc71; font-weight: bold;">■ Green Highlight</span>: **New GameObject**. This object was created during Play Mode (instantiated via code or manually).
*   <span style="color: #3498db; font-weight: bold;">■ Blue Highlight</span>: **Modified GameObject**. One or more components on this object have changed values.

## Inspector Highlighting

When you select a modified object, the Inspector provides detailed feedback.

*   **Banner**: A bold "UNSAVED CHANGES" or "UNSAVED ADDITION" banner appears at the top.
*   **Field Indicators**: Validated fields are listed, showing exactly which property (e.g., `BoxCollider.size`) was altered.
*   **Apply Button**: You can apply changes for *just that specific object* directly from the Inspector without waiting to stop the game.

> **Note**: This system uses `EditorApplication.hierarchyWindowItemOnGUI` to draw custom overlays without affecting your scene performance.
