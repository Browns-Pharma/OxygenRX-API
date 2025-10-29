# Oxygen Public API Documentation

OpenAPI specification for Oxygen's Public API.

## Project Structure

```
.
├── specs/
│   └── public-api.yaml    # OpenAPI specification for public API
└── README.md
```

## API Overview

The Oxygen Public API (`/api/public/v1`) provides endpoints for third-party integrations:

- **Products** - Get product catalog and details
- **Treatments** - List available treatments
- **Prescriptions** - Create and manage prescriptions
- **Patients** - Patient CRUD operations
- **Questionnaires** - Manage questionnaires and answers
- **Webhooks** - Setup webhook subscriptions and view events

### Authentication

All endpoints require Client ID and Client Secret authentication via headers:
- `X-CLIENT-ID`: Your client ID
- `X-CLIENT-SECRET`: Your client secret

## Viewing Documentation

You can view the OpenAPI specification using:

- [Swagger Editor](https://editor.swagger.io/) - Import `specs/public-api.yaml`
- [Scalar](https://github.com/scalar/scalar) - Interactive API documentation
- [Postman](https://www.postman.com/) - Import the OpenAPI file
- Any OpenAPI-compatible tool
