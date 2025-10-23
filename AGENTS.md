# Repository Guidelines

## Scope
These instructions apply to all files in this repository.

## Preferred Workflow
- Treat the generated Flutter assets in this repository (e.g., `main.dart.js`, `flutter.js`, `canvaskit/`) as build artifacts. Do not edit them directly unless you are intentionally working with compiled output.
- For documentation updates, keep tone professional and concise. Use U.S. English and write in complete sentences.
- When adding new documentation, cross-reference existing sections (e.g., README, PLAN) to avoid duplication.

## Testing
- If you modify any Flutter source and rebuild the web output, document the Flutter SDK version used and the exact build command in your commit message or documentation.
- Always re-run `flutter build web` (or the relevant build command) after modifying Dart sources.

## Pull Requests
- Summaries should highlight user-facing changes first, then internal maintenance.
- Include screenshots for visual changes to the site when feasible.
