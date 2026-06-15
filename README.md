# Supabase (supabase)

Supabase is an open-source Firebase alternative that provides a suite of backend services built on top of PostgreSQL. It offers a managed PostgreSQL database with auto-generated REST and GraphQL APIs via PostgREST, real-time data subscriptions via WebSockets, user authentication with JWT (GoTrue), file storage with S3-compatible object storage, edge compute via globally distributed TypeScript functions on the Deno runtime, and a management API for programmatic control of projects and organizations. Supabase is available as a fully managed cloud service (app.supabase.com) and as a self-hosted open-source deployment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Backend As A Service
- PostgreSQL
- Open Source
- Authentication
- Real Time
- Storage
- Edge Functions
- Database

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Supabase Management API

The Supabase Management API provides programmatic access to manage Supabase projects and organizations. Supports creating, configuring, pausing, and deleting projects; managing database migrations and extensions; deploying Edge Functions; managing secrets; configuring custom domains and vanity subdomains; controlling network restrictions; and managing organization membership. Authentication uses personal access tokens or OAuth2 tokens. Base URL: https://api.supabase.com/v1.

- **Human URL:** [https://supabase.com/docs/reference/api/introduction](https://supabase.com/docs/reference/api/introduction)

#### Tags

- Management
- Projects
- Organizations
- Edge Functions
- Database

#### Properties

- [Documentation](https://supabase.com/docs/reference/api/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supabase Auth API

The Supabase Auth API (based on GoTrue) is a JWT-based authentication service supporting user signup, email/password sign-in, magic links, one-time passwords (OTP), OAuth2 social login (Google, GitHub, etc.), token refresh, multi-factor authentication (TOTP/WebAuthn), SAML-based SSO, and administrative user management. Authentication uses an apikey header (anon or service_role key) plus JWT bearer tokens for user context. Per-project base URL: https://{project_ref}.supabase.co/auth/v1.

- **Human URL:** [https://supabase.com/docs/guides/auth](https://supabase.com/docs/guides/auth)

#### Tags

- Authentication
- Users
- OAuth
- JWT
- MFA
- SAML

#### Properties

- [Documentation](https://supabase.com/docs/guides/auth)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-auth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supabase Storage API

The Supabase Storage API enables developers to store, organize, and serve large files in S3-compatible object storage. Provides bucket management (public/private), file upload (standard and TUS resumable), download, deletion, and on-the-fly image transformations (resize, format, quality). Access control is enforced via Row Level Security policies. Supports signed URLs for temporary access. Per-project base URL: https://{project_ref}.supabase.co/storage/v1.

- **Human URL:** [https://supabase.com/docs/guides/storage](https://supabase.com/docs/guides/storage)

#### Tags

- Storage
- File Upload
- Buckets
- Images
- S3

#### Properties

- [Documentation](https://supabase.com/docs/guides/storage)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-storage-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supabase Database REST API

The Supabase Database REST API provides auto-generated RESTful endpoints for every table, view, and stored function in the PostgreSQL database, powered by PostgREST. Supports full CRUD operations with advanced filtering operators (eq, neq, gt, lt, like, ilike, in, fts, cs, cd, ov, adj, not, or, and), horizontal and vertical filtering, pagination, ordering, and embedding related resources via foreign key relationships. Row Level Security policies are enforced on all requests. Per-project base URL: https://{project_ref}.supabase.co/rest/v1.

- **Human URL:** [https://supabase.com/docs/guides/api](https://supabase.com/docs/guides/api)

#### Tags

- Database
- REST
- PostgreSQL
- PostgREST
- CRUD

#### Properties

- [Documentation](https://supabase.com/docs/guides/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-database-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supabase Edge Functions API

Supabase Edge Functions are globally distributed, server-side TypeScript functions powered by the Deno runtime. They are deployed and invoked via HTTP requests to a project-specific URL. Functions can access Supabase client libraries to interact with the database, auth, and storage services. JWT verification is required by default but can be disabled per function. Per-project base URL: https://{project_ref}.supabase.co/functions/v1.

- **Human URL:** [https://supabase.com/docs/guides/functions](https://supabase.com/docs/guides/functions)

#### Tags

- Edge Functions
- Serverless
- Deno
- TypeScript

#### Properties

- [Documentation](https://supabase.com/docs/guides/functions)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/openapi/supabase-edge-functions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supabase Realtime API

The Supabase Realtime API provides WebSocket-based subscriptions for real-time data changes from PostgreSQL databases. It supports three channel types: database change events (INSERT/UPDATE/DELETE on tables via logical replication), presence (track and synchronize connected users' state), and broadcast (low-latency message passing between clients). Authentication uses JWT tokens. Implemented using the Phoenix channels protocol.

- **Human URL:** [https://supabase.com/docs/guides/realtime](https://supabase.com/docs/guides/realtime)

#### Tags

- Realtime
- WebSocket
- Database
- Presence
- Broadcast

#### Properties

- [Documentation](https://supabase.com/docs/guides/realtime)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/asyncapi/supabase-realtime-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/supabase-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-edge-functions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-edge-functions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supabase-storage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supabase-storage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/supabase)
- [Website](https://supabase.com)
- [Documentation](https://supabase.com/docs)
- [GitHub Organization](https://github.com/supabase)
- [Status Page](https://status.supabase.com)
- [Pricing](https://supabase.com/pricing)
- [Blog](https://supabase.com/blog)
- [Community](https://github.com/supabase/supabase/discussions)
- [X (Twitter)](https://twitter.com/supabase)
- [Features](undefined)
- [Integrations](https://supabase.com/partners)
- [M C P Server](https://supabase.com/blog/remote-mcp-server)
- [Agent Skill](https://github.com/supabase/agent-skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
