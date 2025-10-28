# RMS Schemas

A Dart package containing OpenAPI schema definitions for RMS (Recovery Management System) data structures.

## 📖 Interactive Documentation

Quick Links:

- **[Firebase Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/firebase_schema.json)** - Job management and Firebase data structures
- **[Authentication Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/authentication_schema.json)** - User authentication structures
- **[JWT Claims Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/jwt_claims_schema.json)** - JWT token claims

> 💡 Click any link above for clean, interactive schema visualization!

## Overview

This package provides JSON schema definitions for job DTOs and related data structures used in the RMS system. It's designed to be used as a dependency in Flutter and Dart applications that need to validate or work with RMS data structures.

## Schemas Included

### Firebase Schemas

- **Firebase Schema** (`lib/schemas/firebase/firebase_schema.json`) - OpenAPI 3.0.3 schema for Firebase Firestore data transfer objects

### Authentication Schemas

- **Authentication Schema** (`lib/schemas/auth/authentication_schema.json`) - Schema for authentication data structures
- **JWT Claims Schema** (`lib/schemas/auth/jwt_claims_schema.json`) - Schema for JWT token claims

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
