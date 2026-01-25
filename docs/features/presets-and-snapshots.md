---
layout: default
title: Presets & Snapshots
parent: Features
nav_order: 3
---

# Presets & Snapshots

Sometimes you make changes not to "fix" the scene, but to try out a new configuration. Presets allow you to save these experiments.

## Creating a Preset

1.  Make your changes in **Play Mode**.
2.  Open the **PlayModeSaver Menu** (or use the Restore Window).
3.  Click **"Save as Preset"**.
4.  Give it a name (e.g., "Hard Mode Balance", "Night Lighting").

## Loading a Preset

Presets are saved as `ScriptableObject` assets in your project.

1.  Locate the Preset in your Project view.
2.  Click **"Apply to Scene"**.
3.  Your scene instantly updates to match the saved configuration—even if you are in Edit Mode!

## Session History

The tool automatically backs up your last 10 sessions in `Library/PlayModeSaver/History`. If you accidentally clicked "Discard", you can recover your work from the history panel.
