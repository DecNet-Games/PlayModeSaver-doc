---
layout: default
title: UI Tweaking
parent: Workflows
nav_order: 1
---

# UI Tweaking

Designing UI in Unity often requires running the game to see how layouts respond to different aspect ratios or dynamic content.

## The Problem
You spend 10 minutes adjusting padding, font sizes, and anchor positions in Play Mode to get it *just right*. Then you stop the game, and... **poof**, it's all back to the broken state.

## The Solution

1.  Enter Play Mode.
2.  Open your **Game View** alongside the **Scene View**.
3.  Select your UI Elements (RectTransforms, TextMeshPro, Images).
4.  **Tweak freely**: Adjust anchors, move buttons, change colors.
5.  Observe the **Blue Highlights** in the Hierarchy confirming changes are tracked.
6.  **Stop Play Mode**.
7.  In the Restore Window, verify your UI changes are listed.
8.  Click **Apply All**.

Your UI is now pixel-perfect, exactly as you saw it in the game.
