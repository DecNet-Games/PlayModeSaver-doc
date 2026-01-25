---
layout: default
title: FAQ
nav_order: 5
permalink: /docs/faq
---

# Frequently Asked Questions

## Does this work with Prefabs?
Yes. Changes to scene instances of prefabs are applied as overrides. If you want to apply changes *to the Prefab Asset itself*, you will currently need to apply them to the instance first, then use Unity's "Overrides" dropdown to apply to the Prefab.

## What about objects I spawn during runtime?
PlayModeSaver detects new GameObjects created during runtime.
*   **Restore Window**: Shows them as "Added GameObject".
*   **Action**: Clicking "Apply" will create a new GameObject in the Editor scene with the same components and values. Note that it will be a "clone" and not linked to the original prefab code unless you manually reconnect it.

## Can I undo the restore?
Yes! The "Apply" action registers a full Unity **Undo**. simply press `Ctrl+Z` (or `Cmd+Z`) to revert the changes applied by PlayModeSaver.

## Performance Impact?
The tool is optimized to be lightweight.
*   **Snapshotting**: Takes < 50ms for average scenes (only runs on Start/Stop).
*   **Scanning**: Runs asynchronously every 300ms.
*   **Highlighting**: Uses efficiently cached lookups.
