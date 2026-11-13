# CameraFX Support

Bug reports and feature requests for **CameraFX**, the drag-and-drop camera-effects addon for Godot 4.

* Get CameraFX: the itch.io page (linked from the project page).
* Questions and quick help: the comments on the itch.io page are the primary support channel.
* Bugs and feature requests that need tracking: open an issue here using a template.

This repository contains **no source code**. CameraFX is a commercial product; please do not
attach the addon, its scripts or the release ZIP to issues (see the license in your download).
Screenshots, short clips, console output and *your own* scene/script snippets are welcome.

## Before opening an issue
1. Check the Documentation (`3_docs/DOCUMENTATION.md` in your download), especially the Troubleshooting table and the Compatibility section.
2. Known limits (not bugs):
   * Tested by the author only on Godot 4.7.2 (macOS; GL Compatibility and Mobile renderers). Other versions, Windows/Linux and Forward+ are untested, so reports from those setups are very welcome.
   * Jump/landing detection is exact only with `CharacterBody3D`; other bodies are estimated.
   * Exports must use "Export all resources in the project".
   * One CameraFX per camera.
3. Search existing issues first.

## What helps most
Godot version, OS and GPU, renderer, what your controller/camera setup looks like, the
Inspector settings of the CameraFX node, and any Output panel messages (they begin with `[CameraFX]`).

Response times are best-effort. Free updates for 1.x purchasers.
