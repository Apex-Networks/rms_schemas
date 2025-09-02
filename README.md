# RMS Schemas

A Dart package containing OpenAPI schema definitions for RMS (Recovery Management System) data structures.

## Overview

This package provides JSON schema definitions for job DTOs and related data structures used in the RMS system. It's designed to be used as a dependency in Flutter and Dart applications that need to validate or work with RMS data structures.

## Schemas Included

- **Job DTO Schema** (`lib/schemas/job_dto_schema.json`) - OpenAPI 3.0.3 schema for job data transfer objects

## Installation

Add this package to your `pubspec.yaml`:

```yaml
dependencies:
  rms_schemas:
    git:
      url: https://github.com/Apex-Networks/rms_schemas.git
```

To reference a specific tag/version:

```yaml
dependencies:
  rms_schemas:
    git:
      url: https://github.com/Apex-Networks/rms_schemas.git
      ref: v1.0.4  # Replace with desired tag
```

Then run:

```bash
flutter pub get
```

## License

This package is proprietary to Apex Networks.
