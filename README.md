# wan27_org

`wan27_org` is a small Dart package for projects that want a typed, installable
reference point for [wan27.org](https://wan27.org), the Wan 2.7 AI video
generation website.

The package is intentionally lightweight for the first release. It gives Dart
and Flutter projects a stable package name, clear package metadata, and a simple
entry point that can later grow into a fuller SDK for Wan 2.7 workflows.

## What is wan27.org?

[wan27.org](https://wan27.org) focuses on Wan 2.7 video generation workflows,
including text-to-video, image-to-video, first-frame and last-frame control,
subject reference, video editing, and video recreation. This package keeps those
links and identifiers available from Dart code so apps can reference the website
consistently.

## Installation

```bash
dart pub add wan27_org
```

Or add it manually to `pubspec.yaml`:

```yaml
dependencies:
  wan27_org: ^0.1.0
```

## Usage

```dart
import 'package:wan27_org/wan27_org.dart';

void main() {
  print(hello());
  print(homepage);
}
```

## Included utilities

- `homepage` pointing to `https://wan27.org`.
- `hello()` for confirming the package is installed.
- pub.dev metadata for homepage, documentation, repository, and issue tracker.

## Common use cases

- Keep a canonical Wan 2.7 homepage link inside a Dart or Flutter app.
- Add a small installable package that represents the wan27.org integration
  surface.
- Use this first release as the base for a future API wrapper, generated client,
  or Flutter UI integration.

## Package metadata

The package includes pub.dev metadata for:

- Homepage: https://wan27.org
- Documentation: https://wan27.org/docs
- Repository: https://github.com/youram470-art/wan27-org-dart
- Issue tracker: https://github.com/youram470-art/wan27-org-dart/issues

## Roadmap

Future releases can add:

- Request and response models for Wan 2.7 video generation workflows.
- Client helpers for text-to-video and image-to-video integrations.
- Flutter-friendly examples for linking app screens to wan27.org workflows.
- Validation utilities for common video generation parameters.

## Links

- Website: https://wan27.org
- Documentation: https://wan27.org/docs
- Source: https://github.com/youram470-art/wan27-org-dart

## License

MIT
