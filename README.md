# RMS Schemas

A Dart package containing OpenAPI schema definitions for RMS data structures.

## 📖 Interactive Documentation

Quick Links:

- **[Job Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_schema.json)**
- **[Settings Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/settings_schema.json)**
- **[Fault and Outcome Codes Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/fault_outcome_codes_schema.json)**
- **[Authentication Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/authentication_schema.json)**
- **[JWT Claims Schema](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/jwt_claims_schema.json)**

> 💡 Click any link above for clean, interactive schema visualization

## Overview

This repository provides OpenAPI schema definitions for RMS (Recovery Management System) data structures. These schemas define the structure, validation rules, and data types for all RMS system components, ensuring consistent data contracts across mobile apps, backend services, and integrations.

## Schemas Included

### Firebase Schemas

- **Job schema** (`lib/schemas/firebase/job_schema.json`)
- **Settings Schema** (`lib/schemas/firebase/settings_schema.json`)
- **Fault and Outcome Codes Schema** (`lib/schemas/firebase/fault_outcome_codes_schema.json`)

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
