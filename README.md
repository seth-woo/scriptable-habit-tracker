# scriptable-habit-tracker

**TL;DR:** Dot-style Countdown Habit Tracker Widget on iOS (via Scriptable)

A customizable iOS Scriptable widget that visualizes progress toward a habit or goal as a grid of dots from a start date to an end date. It supports event labels, countdown text, configurable colors/layout, and an optional background image for a clean, motivating home-screen tracker.

## Compatibility & Testing

This tracker has been tested on the latest publicly available iOS 26.x release at the time of testing, using medium-sized Scriptable widgets on the Home Screen.

Validation was done in all three appearance styles:

- Light mode
- Dark mode
- Clear mode (Apple's Liquid Glass)

In each mode, the dot grid, event label, days-left text, color opacity, and background overlay remained readable and visually stable (not to mention, minimal and aesthetically pleasing - but to each their own ofc).

## How to Use

1. Open Scriptable.
2. Tap `Add Script`.
3. Paste the contents of `tracker.js`.
4. Rename the script.
5. Tap `Run` in the bottom-right corner.

The spacing in this script is optimized for a medium-size widget (4x2 app icons) on a 6.3" display (iPhone 16 Pro). 

To add the widget to Home Screen:

1. Long-press the Home Screen, then tap `Edit`.
2. Tap `Add Widget`.
3. Search for `Scriptable`.
4. Insert a `Medium` Scriptable widget.
5. Long-press the new widget and tap `Edit Widget`.
6. Select your script by name.
7. Set interaction behavior to `Run Script`.
