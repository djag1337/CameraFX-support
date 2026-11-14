# CameraFX To-Do

What is being worked on or considered. This is a plain list, not a promise: there are no release dates, and items can change or be dropped. Updates for 1.x are free for purchasers.

Want something added or fixed? Open an issue using a template, or comment on the itch.io page.

## Fixed, waiting for the next update
- [x] **Physics interpolation (Godot 4.4+):** effects were invisible with 3D physics interpolation enabled on the camera. Fixed and covered by a new render test; it will ship in the next update (not released yet). Until then: leave physics interpolation off for that camera. Known limit after the fix: nodes attached to the camera (view-models, flashlights) are not moved by the effect while interpolation is on.

## Needs testing (reports welcome)
- [ ] Windows and Linux (so far only tested on macOS)
- [ ] Godot versions other than 4.7.2
- [ ] Forward+ renderer (so far GL Compatibility and Mobile only)

## Ideas under consideration
- [ ] Nothing committed yet. Requests from issues and itch.io comments will be listed here.

## Done
- [x] Initial release
