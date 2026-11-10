# Flutter Week 1 – Widgets and Layouts

A pair of introductory Flutter examples exploring Material widgets, visual styling, and the layout system.

## Exercises

| File | Description |
|---|---|
| `2(A)` | Material widget showcase with an AppBar, network image, text, containers, spacing and other basic UI elements |
| `2(B)` | Layout demonstration covering horizontal `Row`, vertical `Column`, and nested/stacked widget composition |
| `IMG-20260825-WA0001.jpg`, `Screenshot 2026-08-18 135247.png`, `WhatsApp Image 2026-08-25 at 9.35.44 AM.jpeg` | Exercise screenshots and reference output |

## Concepts covered

- `MaterialApp` and `Scaffold`
- App bars, text, images, icons and buttons
- `Container`, padding, margin and spacing
- `Row`, `Column`, alignment and nested layouts
- Building scrollable screens with `SingleChildScrollView`

## Run in Flutter

These examples are stored as extensionless source files rather than a complete Flutter project.

1. Install Flutter and verify the setup with `flutter doctor`.
2. Create a starter project:

   ```bash
   flutter create widget_practice
   cd widget_practice
   ```

3. Copy either exercise into `lib/main.dart` (keep a separate copy for each exercise).
4. Run:

   ```bash
   flutter run
   ```

The network-image example requires an internet connection. The project scaffold supplies the Flutter SDK dependencies; no project configuration is included in this repository itself.

## Purpose

Use these examples to understand how Flutter widgets compose into a screen and how layout widgets control positioning and spacing.
