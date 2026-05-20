---
name: generate-openapi-spec
description: Use this skill when the user wants to generate a complete OpenAPI/Swagger specification for an API.
---

# OpenAPI Spec Generation
## Instructions
1. Gather all endpoints, methods, request bodies, query params, and response schemas from the API design.
2. Structure the spec in OpenAPI 3.x format with info, servers, paths, and components sections.
3. Define reusable schemas in components/schemas to avoid duplication across endpoints.
4. Include all relevant response codes — success (200/201), client errors (400, 401, 404), and server errors (500).
5. Add security schemes if the API uses authentication (Bearer token, API key, or OAuth2).
