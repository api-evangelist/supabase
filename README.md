# Supabase

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Supabase is an open-source Firebase alternative that provides a suite of backend services built on top of PostgreSQL. It offers a managed PostgreSQL database with auto-generated REST and GraphQL APIs via PostgREST, real-time data subscriptions via WebSockets, user authentication with JWT (GoTrue), file storage with S3-compatible object storage, edge compute via globally distributed TypeScript functions on the Deno runtime, and a management API for programmatic control of projects and organizations. Supabase is available as a fully managed cloud service (app.supabase.com) and as a self-hosted open-source deployment.

**Areas:** Backend-as-a-Service · PostgreSQL · Open Source · Authentication · Real-Time · Storage · Edge Functions · Database · Identity Federation · Serverless

## Supabase on APIs.io

Everything profiled for Supabase is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/supabase/](https://apis.io/providers/supabase/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Supabase Realtime API](https://apis.io/apis/supabase/realtime-api/) — The Supabase Realtime API provides WebSocket-based subscriptions for real-time data changes from PostgreSQL databases. It supports three channel types:…
- [Supabase Admin API](https://apis.io/apis/supabase/supabase-admin-api/) — Administrative endpoints for managing users. Requires service_role key.
- [Supabase Authentication API](https://apis.io/apis/supabase/supabase-authentication-api/) — User signup, signin, and token management endpoints.
- [Supabase Buckets API](https://apis.io/apis/supabase/supabase-buckets-api/) — Manage storage buckets that organize files and folders. Buckets can be public or private and have configurable file size limits and allowed MIME types.
- [Supabase Configuration API](https://apis.io/apis/supabase/supabase-configuration-api/) — Server configuration and settings endpoints.
- [Supabase Database API](https://apis.io/apis/supabase/supabase-database-api/) — Manage database configurations, migrations, and extensions.
- [Supabase Domains API](https://apis.io/apis/supabase/supabase-domains-api/) — Configure custom domains and vanity subdomains for projects.
- [Supabase Functions API](https://apis.io/apis/supabase/supabase-functions-api/) — Deploy and manage Edge Functions for serverless compute at the edge.
- [Supabase Invocation API](https://apis.io/apis/supabase/supabase-invocation-api/) — Invoke deployed Edge Functions via HTTP requests. Each function is accessible at its own URL path based on its slug.
- [Supabase MFA API](https://apis.io/apis/supabase/supabase-mfa-api/) — Multi-factor authentication enrollment and verification endpoints.
- [Supabase Network API](https://apis.io/apis/supabase/supabase-network-api/) — Manage network restrictions, bans, and SSL enforcement.
- [Supabase Objects API](https://apis.io/apis/supabase/supabase-objects-api/) — Upload, download, move, copy, and delete files within storage buckets.
- [Supabase Organizations API](https://apis.io/apis/supabase/supabase-organizations-api/) — Manage organizations including membership, billing, and settings.
- [Supabase Projects API](https://apis.io/apis/supabase/supabase-projects-api/) — Manage Supabase projects including creation, configuration, pausing, restoring, and deletion.
- [Supabase Rendering API](https://apis.io/apis/supabase/supabase-rendering-api/) — Serve and transform stored files including image resizing and format conversion.
- [Supabase RPC API](https://apis.io/apis/supabase/supabase-rpc-api/) — Invoke PostgreSQL functions via remote procedure calls.
- [Supabase Secrets API](https://apis.io/apis/supabase/supabase-secrets-api/) — Manage project secrets used by Edge Functions and other services.
- [Supabase SSO API](https://apis.io/apis/supabase/supabase-sso-api/) — SAML-based single sign-on endpoints.
- [Supabase Tables API](https://apis.io/apis/supabase/supabase-tables-api/) — CRUD operations on database tables. Paths are auto-generated based on your database schema.
- [Supabase User Management API](https://apis.io/apis/supabase/supabase-user-management-api/) — Endpoints for managing the currently authenticated user profile.
- [Supabase O Auth API](https://apis.io/apis/supabase/supabase-oauth-api/) — OAuth social login provider endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Supabase Realtime API](https://apis.io/asyncapis/supabase/supabase-realtime-api-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [realtime/{topic}](https://apis.io/channels/supabase/realtime-topic/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/supabase/](https://apis.io/graphqls/supabase/supabase-graphql/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/supabase/mcp-server/)
- [supabase](https://apis.io/servers/supabase/supabase/)

#### Agent skills (2)

Agent skills built on the API.

- [supabase](https://apis.io/agent-skills/supabase/supabase/)
- [supabase-postgres-best-practices](https://apis.io/agent-skills/supabase/supabase-postgres-best-practices/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Supabase Agentic Access](https://apis.io/agentic-access/supabase/supabase-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Supabase Project](https://apis.io/schemas/supabase/supabase-project/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Supabase Project Structure](https://apis.io/json-structure/supabase/supabase-project-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Supabase Context](https://apis.io/jsonld/supabase/supabase-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Supabase Vocabulary](https://apis.io/vocabularies/supabase/supabase-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Supabase List Projects Example](https://apis.io/examples/supabase/supabase-list-projects-example/)
- [Supabase Select Rows Example](https://apis.io/examples/supabase/supabase-select-rows-example/)
- [Supabase Sign Up Example](https://apis.io/examples/supabase/supabase-sign-up-example/)

#### Collections (25)

Postman and Open Collection request collections.

- [Supabase Auth Admin API](https://apis.io/collections/supabase/open-supabase-admin-api/)
- [Supabase Auth API](https://apis.io/collections/supabase/open-supabase-auth-api/)
- [Supabase Auth Admin Authentication API](https://apis.io/collections/supabase/open-supabase-authentication-api/)
- [Supabase Auth Admin Buckets API](https://apis.io/collections/supabase/open-supabase-buckets-api/)
- [Supabase Auth Admin Configuration API](https://apis.io/collections/supabase/open-supabase-configuration-api/)
- [Supabase Auth Admin Database API](https://apis.io/collections/supabase/open-supabase-database-api/)
- [Supabase Database REST API](https://apis.io/collections/supabase/open-supabase-database-rest-api/)
- [Supabase Auth Admin Domains API](https://apis.io/collections/supabase/open-supabase-domains-api/)
- [Supabase Edge Functions API](https://apis.io/collections/supabase/open-supabase-edge-functions-api/)
- [Supabase Auth Admin Functions API](https://apis.io/collections/supabase/open-supabase-functions-api/)
- [Supabase Auth Admin Invocation API](https://apis.io/collections/supabase/open-supabase-invocation-api/)
- [Supabase Management API](https://apis.io/collections/supabase/open-supabase-management-api/)
- [Supabase Auth Admin MFA API](https://apis.io/collections/supabase/open-supabase-mfa-api/)
- [Supabase Auth Admin Network API](https://apis.io/collections/supabase/open-supabase-network-api/)
- [Supabase Auth Admin OAuth API](https://apis.io/collections/supabase/open-supabase-oauth-api/)
- [Supabase Auth Admin Objects API](https://apis.io/collections/supabase/open-supabase-objects-api/)
- [Supabase Auth Admin Organizations API](https://apis.io/collections/supabase/open-supabase-organizations-api/)
- [Supabase Auth Admin Projects API](https://apis.io/collections/supabase/open-supabase-projects-api/)
- [Supabase Auth Admin Rendering API](https://apis.io/collections/supabase/open-supabase-rendering-api/)
- [Supabase Auth Admin RPC API](https://apis.io/collections/supabase/open-supabase-rpc-api/)
- [Supabase Auth Admin Secrets API](https://apis.io/collections/supabase/open-supabase-secrets-api/)
- [Supabase Auth Admin SSO API](https://apis.io/collections/supabase/open-supabase-sso-api/)
- [Supabase Storage API](https://apis.io/collections/supabase/open-supabase-storage-api/)
- [Supabase Auth Admin Tables API](https://apis.io/collections/supabase/open-supabase-tables-api/)
- [Supabase Auth Admin User Management API](https://apis.io/collections/supabase/open-supabase-user-management-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Supabase — asyncapi rules](https://apis.io/rules/supabase/supabase-asyncapi-spectral-rules/)
- [Supabase — jsonschema rules](https://apis.io/rules/supabase/supabase-jsonschema-spectral-rules/)
- [Supabase API Rules](https://apis.io/rules/supabase/supabase-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Supabase Authentication](https://apis.io/security/supabase/supabase-authentication/)
- [Supabase Domain Security](https://apis.io/security/supabase/supabase-domain-security/)
- [Supabase Trust Center](https://apis.io/security/supabase/supabase-trust-center/)
- [Supabase Vulnerability Disclosure](https://apis.io/security/supabase/supabase-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Supabase Plans Pricing](https://apis.io/plans/supabase/supabase-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Supabase Rate Limits](https://apis.io/rate-limits/supabase/supabase-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Supabase Finops](https://apis.io/finops/supabase/supabase-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://supabase.com)
- [Documentation](https://supabase.com/docs)
- [Pricing](https://supabase.com/pricing)
- [Blog](https://supabase.com/blog)
- [GitHub](https://github.com/supabase)
- [Status](https://status.supabase.com)

## API Evangelist rating

**Kin Score 42.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 63.2 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 32.6 |
| Access clarity | 26.3 |

**Agent readiness 48.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/supabase/](https://apis.io/providers/supabase/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Supabase: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/supabase/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
