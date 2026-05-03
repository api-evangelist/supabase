# Supabase

Supabase is an open-source Firebase alternative that provides a full suite of backend services built on top of PostgreSQL. The developer platform offers managed databases with auto-generated REST and GraphQL APIs, authentication with JWT, file storage, real-time WebSocket subscriptions, globally distributed edge functions, and a Management API for programmatic project administration.

**URL:** [APIs.yml](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml)

## Tags

Backend As A Service, PostgreSQL, Open Source, Authentication, Real Time, Storage, Edge Functions, Database

## APIs

### Supabase Management API
Programmatic management of projects, organizations, Edge Functions, secrets, custom domains, network restrictions, and database migrations. Auth: Personal Access Token (Bearer). Base: `https://api.supabase.com/v1`.

**URL:** [https://supabase.com/docs/reference/api/introduction](https://supabase.com/docs/reference/api/introduction)

**Tags:** Management, Projects, Organizations, Edge Functions, Database

**Properties:**
- [Documentation](https://supabase.com/docs/reference/api/introduction)
- [OpenAPI](openapi/supabase-management-api-openapi.yml)

### Supabase Auth API
JWT-based authentication service (GoTrue) supporting email/password, magic links, OTP, OAuth2 social login, MFA (TOTP/WebAuthn), and SAML SSO. Auth: `apikey` header + Bearer JWT. Base: `https://{ref}.supabase.co/auth/v1`.

**URL:** [https://supabase.com/docs/guides/auth](https://supabase.com/docs/guides/auth)

**Tags:** Authentication, Users, OAuth, JWT, MFA, SAML

**Properties:**
- [Documentation](https://supabase.com/docs/guides/auth)
- [OpenAPI](openapi/supabase-auth-api-openapi.yml)

### Supabase Storage API
S3-compatible object storage with bucket management, standard and TUS resumable uploads, on-the-fly image transformation, and signed URL generation. Access controlled via Row Level Security. Base: `https://{ref}.supabase.co/storage/v1`.

**URL:** [https://supabase.com/docs/guides/storage](https://supabase.com/docs/guides/storage)

**Tags:** Storage, File Upload, Buckets, Images, S3

**Properties:**
- [Documentation](https://supabase.com/docs/guides/storage)
- [OpenAPI](openapi/supabase-storage-api-openapi.yml)

### Supabase Database REST API
Auto-generated PostgREST endpoints for all database tables, views, and stored functions with full CRUD, advanced filtering operators, pagination, sorting, and foreign key embedding. Base: `https://{ref}.supabase.co/rest/v1`.

**URL:** [https://supabase.com/docs/guides/api](https://supabase.com/docs/guides/api)

**Tags:** Database, REST, PostgreSQL, PostgREST, CRUD

**Properties:**
- [Documentation](https://supabase.com/docs/guides/api)
- [OpenAPI](openapi/supabase-database-rest-api-openapi.yml)

### Supabase Edge Functions API
Globally distributed TypeScript serverless functions on the Deno runtime. Invoked via HTTP. Supports JWT verification, Supabase client access, and custom logic. Base: `https://{ref}.supabase.co/functions/v1`.

**URL:** [https://supabase.com/docs/guides/functions](https://supabase.com/docs/guides/functions)

**Tags:** Edge Functions, Serverless, Deno, TypeScript

**Properties:**
- [Documentation](https://supabase.com/docs/guides/functions)
- [OpenAPI](openapi/supabase-edge-functions-api-openapi.yml)

### Supabase Realtime API
WebSocket-based real-time subscriptions for database change events (INSERT/UPDATE/DELETE), presence (connected user tracking), and broadcast (client-to-client messaging). Uses Phoenix channels protocol.

**URL:** [https://supabase.com/docs/guides/realtime](https://supabase.com/docs/guides/realtime)

**Tags:** Realtime, WebSocket, Database, Presence, Broadcast

**Properties:**
- [Documentation](https://supabase.com/docs/guides/realtime)
- [AsyncAPI](asyncapi/supabase-realtime-api-asyncapi.yml)

## Artifacts

| Type | File |
|------|------|
| OpenAPI — Management API | [supabase-management-api-openapi.yml](openapi/supabase-management-api-openapi.yml) |
| OpenAPI — Auth API | [supabase-auth-api-openapi.yml](openapi/supabase-auth-api-openapi.yml) |
| OpenAPI — Storage API | [supabase-storage-api-openapi.yml](openapi/supabase-storage-api-openapi.yml) |
| OpenAPI — Database REST API | [supabase-database-rest-api-openapi.yml](openapi/supabase-database-rest-api-openapi.yml) |
| OpenAPI — Edge Functions API | [supabase-edge-functions-api-openapi.yml](openapi/supabase-edge-functions-api-openapi.yml) |
| AsyncAPI — Realtime API | [supabase-realtime-api-asyncapi.yml](asyncapi/supabase-realtime-api-asyncapi.yml) |
| JSON Schema — Project | [supabase-project-schema.json](json-schema/supabase-project-schema.json) |
| JSON Structure — Project | [supabase-project-structure.json](json-structure/supabase-project-structure.json) |
| JSON-LD Context | [supabase-context.jsonld](json-ld/supabase-context.jsonld) |
| Spectral Rules | [supabase-rules.yml](rules/supabase-rules.yml) |
| Capabilities — Shared: Management | [capabilities/shared/management-api.yaml](capabilities/shared/management-api.yaml) |
| Capabilities — Shared: Auth | [capabilities/shared/auth-api.yaml](capabilities/shared/auth-api.yaml) |
| Capabilities — Shared: Storage | [capabilities/shared/storage-api.yaml](capabilities/shared/storage-api.yaml) |
| Capabilities — Shared: Database REST | [capabilities/shared/database-rest-api.yaml](capabilities/shared/database-rest-api.yaml) |
| Capabilities — Backend as a Service | [capabilities/backend-as-a-service.yaml](capabilities/backend-as-a-service.yaml) |
| Vocabulary | [supabase-vocabulary.yml](vocabulary/supabase-vocabulary.yml) |
| Example — List Projects | [supabase-list-projects-example.json](examples/supabase-list-projects-example.json) |
| Example — Sign Up | [supabase-sign-up-example.json](examples/supabase-sign-up-example.json) |
| Example — Select Rows | [supabase-select-rows-example.json](examples/supabase-select-rows-example.json) |

## Common Properties

- [Website](https://supabase.com)
- [Documentation](https://supabase.com/docs)
- [GitHub Organization](https://github.com/supabase)
- [Status Page](https://status.supabase.com)
- [Pricing](https://supabase.com/pricing)
- [Blog](https://supabase.com/blog)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
