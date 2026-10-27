# Agent Guidance

## Project
- This is a Flutter application using Dart; the app entry point is `lib/main.dart`.
- Flutter dependencies and app metadata are defined in `pubspec.yaml`.
- The project currently uses `flutter_lints` through `analysis_options.yaml`.

## Working in This Repository
- Keep changes focused and follow the existing Flutter and Dart style.
- Prefer Flutter SDK widgets and APIs already available in the project; add dependencies only when needed.
- Put application code under `lib/` and automated tests under `test/`.
- Preserve the generated platform directories unless a task specifically requires platform changes.

## Verification
- Run `flutter analyze` after Dart changes.
- Run `flutter test` when tests exist or when behavior changes warrant adding tests.