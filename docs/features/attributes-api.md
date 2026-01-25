---
layout: default
title: Attributes API
parent: Features
nav_order: 4
---

# Developer API & Attributes

For advanced users, PlayModeSaver exposes attributes to control behavior via code.

## `[SaveOnPlayModeExit]`

Mark specific fields in your `MonoBehaviour` scripts to ensure they are **always** prioritized for saving, or to flag them for specific handling.

```csharp
using UnityEngine;
using PlayModeSaver.Runtime.Attributes;

public class CharacterStats : MonoBehaviour
{
    [SaveOnPlayModeExit]
    public float movementSpeed = 5.0f;
    
    public float temporaryBuff = 0f; // This won't be prioritized
}
```

## Extensions

You can access the core system via `PlayModeSaver.Editor.Core`:

*   `PlayModeSaverSession.GetChanges()`: Get a list of all current runtime changes.
*   `PlayModeSaverSession.TakeSnapshots()`: Manually trigger a snapshot.
