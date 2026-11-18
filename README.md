# ClayShot

ClayShot is a browser-based shooter game with an Android build.

## Project files

The repository is intended to contain:

- `index.html` — game source and browser build
- `app-debug.apk` — Android debug build
- `assets/audio/` — sound effects and ambience used by the game

## Running the browser version

Open `index.html` in a modern browser, or serve the repository root with a local static web server.

## Android build

Install the APK on a compatible Android device. This is a debug build, not a signed release package.

## Notes

- The source and assets should be kept together so relative audio paths continue to work.
- Keep the existing game behavior intact when making maintenance changes.
