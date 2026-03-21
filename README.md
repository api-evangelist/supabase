# Supabase (supabase)
Supabase is an open-source Firebase alternative that provides a full suite of backend services built on top of PostgreSQL. Their developer platform offers managed databases, authentication, file storage, real-time subscriptions, edge functions, and a comprehensive management API for programmatic project administration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/supabase/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Databases, PostgreSQL, Authentication, Storage, Realtime, Serverless, Edge Computing, Backend as a Service

## Timestamps

- **Created:** 2025-03-07
- **Modified:** 2026-03-20

## APIs

### Supabase Database REST API
The Supabase Database REST API provides auto-generated RESTful endpoints for every table and view in your PostgreSQL database. It is powered by PostgREST and supports full CRUD operations including GET, POST, PATCH, and DELETE requests. The API automatically updates as your database schema changes, and supports filtering, pagination, and embedding of related resources. Row Level Security policies are enforced on all API requests to ensure data access control.

**Human URL:** [https://supabase.com/docs/guides/api](https://supabase.com/docs/guides/api)


#### Tags:

 - Databases, PostgreSQL, REST, CRUD

#### Properties

- [Documentation](https://supabase.com/docs/guides/api)
- [OpenAPI](openapi/supabase-database-rest-api-openapi.yml)

### Supabase Auth API
The Supabase Auth API provides a complete authentication and authorization system built on top of PostgreSQL. It supports email and password login, passwordless authentication via magic links, OAuth social login with providers like Google, GitHub, and Apple, and mobile authentication. The API handles user management, session tokens, multi-factor authentication, and integrates with Row Level Security for fine-grained access control at the database level.

**Human URL:** [https://supabase.com/docs/guides/auth](https://supabase.com/docs/guides/auth)


#### Tags:

 - Authentication, Authorization, OAuth, Identity

#### Properties

- [Documentation](https://supabase.com/docs/guides/auth)
- [OpenAPI](openapi/supabase-auth-api-openapi.yml)

### Supabase Storage API
The Supabase Storage API enables developers to store, organize, and serve large files such as images, videos, and documents. It provides bucket-based organization with support for uploading, downloading, and transforming files including on-the-fly image resizing and optimization. Access control is managed through Row Level Security policies tied to the PostgreSQL database, allowing fine-grained permissions on file operations. The API supports both public and private storage buckets.

**Human URL:** [https://supabase.com/docs/guides/storage](https://supabase.com/docs/guides/storage)


#### Tags:

 - Storage, Files, Objects, Media

#### Properties

- [Documentation](https://supabase.com/docs/guides/storage)
- [OpenAPI](openapi/supabase-storage-api-openapi.yml)

### Supabase Realtime API
The Supabase Realtime API allows developers to listen to database changes in real time using WebSocket connections. It supports three main features: Postgres Changes for subscribing to INSERT, UPDATE, and DELETE events on database tables; Broadcast for sending ephemeral messages between connected clients on a channel; and Presence for tracking and synchronizing shared state across clients such as online status indicators. The API integrates with Row Level Security to ensure authorized access to real-time data.

**Human URL:** [https://supabase.com/docs/guides/realtime](https://supabase.com/docs/guides/realtime)


#### Tags:

 - Realtime, WebSockets, Streaming, Events

#### Properties

- [Documentation](https://supabase.com/docs/guides/realtime)
- [AsyncAPI](asyncapi/supabase-realtime-api-asyncapi.yml)

### Supabase Edge Functions API
Supabase Edge Functions are globally distributed, server-side TypeScript functions powered by the Deno runtime. They execute at the edge closest to the user for low-latency responses and can be invoked via HTTP requests or triggered by database webhooks. Edge Functions support NPM modules and Node.js built-in APIs, and have direct access to the Supabase client libraries for interacting with the database, auth, and storage services. They are useful for implementing custom business logic, third-party integrations, and webhook handlers.

**Human URL:** [https://supabase.com/docs/guides/functions](https://supabase.com/docs/guides/functions)


#### Tags:

 - Serverless, Edge Computing, Functions, Deno

#### Properties

- [Documentation](https://supabase.com/docs/guides/functions)
- [OpenAPI](openapi/supabase-edge-functions-api-openapi.yml)

### Supabase Management API
The Supabase Management API provides programmatic access to manage Supabase projects and organizations. It supports operations for creating, updating, and deleting projects, managing database configurations, retrieving project API keys, and controlling organization membership. Authentication is handled via personal access tokens or OAuth2 tokens. The API enables automation of infrastructure management tasks and integration with CI/CD pipelines for deploying and configuring Supabase projects at scale.

**Human URL:** [https://supabase.com/docs/reference/api/introduction](https://supabase.com/docs/reference/api/introduction)


#### Tags:

 - Management, Administration, Projects, Organizations

#### Properties

- [Documentation](https://supabase.com/docs/reference/api/introduction)
- [OpenAPI](openapi/supabase-management-api-openapi.yml)

### Supabase JavaScript SDK
The Supabase JavaScript SDK (supabase-js) is the official client library for interacting with Supabase services from JavaScript and TypeScript applications. It provides methods for querying the PostgreSQL database, managing user authentication sessions, uploading and downloading files from storage, subscribing to real-time database changes, and invoking Edge Functions. The SDK works in both browser and Node.js environments and includes full TypeScript type definitions generated from the database schema.

**Human URL:** [https://supabase.com/docs/reference/javascript/introduction](https://supabase.com/docs/reference/javascript/introduction)


#### Tags:

 - JavaScript, SDK, Client Library, Node.js

#### Properties

- [Documentation](https://supabase.com/docs/reference/javascript/introduction)

### Supabase Python SDK
The Supabase Python SDK (supabase-py) is the official client library for accessing Supabase services from Python applications. It provides methods for performing database queries, managing authentication, handling file storage operations, subscribing to real-time events, and invoking Edge Functions. The library supports both synchronous and asynchronous usage patterns and is suitable for backend services, data pipelines, and scripting workflows that interact with Supabase projects.

**Human URL:** [https://supabase.com/docs/reference/python/introduction](https://supabase.com/docs/reference/python/introduction)


#### Tags:

 - Python, SDK, Client Library

#### Properties

- [Documentation](https://supabase.com/docs/reference/python/introduction)

## Common Properties

- [Portal](https://supabase.com/developers)
- [Documentation](https://supabase.com/docs)
- [Website](https://supabase.com)
- [PrivacyPolicy](https://supabase.com/privacy)
- [TermsOfService](https://supabase.com/terms)
- [Support](https://supabase.com/support)
- [Blog](https://supabase.com/blog)
- [Login](https://supabase.com/dashboard/sign-in)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
