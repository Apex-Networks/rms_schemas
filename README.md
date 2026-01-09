# RMS Schemas

A Dart package containing OpenAPI schema definitions for RMS data structures.

## 📖 Interactive Documentation

| Category | Schema | View |
|----------|--------|------|
| **Authentication** | Authentication Schema | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/authentication_schema.json) |
| | JWT Claims Schema | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/auth/jwt_claims_schema.json) |
| **Job** | Job Schema | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_schema.json) |
| **Lookups** | Job Acceptance Statements | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_acceptance_statements_schema.json) |
| | Job Fault Codes | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_fault_codes_schema.json) |
| | Job Items Present | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_items_present_schema.json) |
| | Job Outcome Codes | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/job_outcome_codes_schema.json) |
| **Settings** | Settings Schema | [→ View](https://elements-demo.stoplight.io/?spec=https://raw.githubusercontent.com/Apex-Networks/rms_schemas/main/lib/schemas/firebase/settings_schema.json) |

> 💡 Click any link above for clean, interactive schema visualization

## Overview

This repository provides OpenAPI schema definitions for RMS (Recovery Management System) data structures. These schemas define the structure, validation rules, and data types for all RMS system components, ensuring consistent data contracts across mobile apps, backend services, and integrations.

## Schemas Included

### Authentication Schemas

- **Authentication** (`lib/schemas/auth/authentication_schema.json`) - Schema for authentication data structures
- **JWT Claims** (`lib/schemas/auth/jwt_claims_schema.json`) - Schema for JWT token claims

### Firebase Schemas

- **Job** (`lib/schemas/firebase/job_schema.json`)
- **Job Acceptance Statements** (`lib/schemas/firebase/job_acceptance_statements_schema.json`)
- **Job Fault Codes** (`lib/schemas/firebase/job_fault_codes_schema.json`)
- **Job Items Present** (`lib/schemas/firebase/job_items_present_schema.json`)
- **Job Outcome Codes** (`lib/schemas/firebase/job_outcome_codes_schema.json`)
- **Settings** (`lib/schemas/firebase/settings_schema.json`)

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
