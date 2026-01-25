---
layout: default
title: Auto-Save & Restore
parent: Features
nav_order: 1
---

# Auto-Save & Restore System

The core of PlayModeSaver is its ability to track every modification you make while the game is running and offer to restore them when you stop.

## How it Works

1.  **Snapshotting**: When you press **Play**, the tool takes a lightweight snapshot of your current scene state.
2.  **Tracking**: Every 300ms, it scans for differences between the current runtime state and the initial snapshot.
3.  **Restoration**: When you press **Stop**, the **Restore Window** appears.

## The Restore Window

The Restore Window gives you granular control over what to keep.

*   **View Changes**: See a list of all modified objects, components, and fields.
*   **Filter**: Sort by "Modified Values", "New Objects", or "New Components".
*   **Apply Selected**: Pick specific changes you want to keep.
*   **Apply All**: Restore everything in one click.
*   **Discard**: Ignore changes and revert to the original scene.

> **Pro Tip**: The tool handles deep modifications, including `Mesh` and `Material` property changes!
