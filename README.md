# SeekMate — Flutter starter

This is the first UI prototype for an original GPS-based multiplayer hide-and-seek app.

## What works in this starter
- Home screen UI
- Create-game dialog (prototype placeholder)
- Join-game dialog with a 6-character room code field
- Responsive scrolling layout

## What is not connected yet
- Real account sign-in
- Firebase / online multiplayer
- GPS permissions or location tracking
- Map provider
- Real room creation, joining, or tagging

## Run it
1. Install Flutter and the Flutter/Dart extensions for VS Code.
2. Extract this ZIP.
3. Open the `seekmate` folder in VS Code.
4. In the terminal, run:

   flutter pub get
   flutter run

For Android, connect an Android phone with USB debugging enabled, or use an Android emulator.

For iOS builds, you will need macOS with Xcode.

## Next milestone
Add Firebase authentication and real multiplayer rooms. Before enabling outdoor GPS gameplay, add consent, visibility controls, safe play boundaries, and anti-cheat validation.
