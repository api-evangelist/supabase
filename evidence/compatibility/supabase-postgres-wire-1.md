<!-- fetched 2026-10-13 from https://supabase.com/docs/guides/database/overview by sweep-shape-compat.py; text extracted from the provider's own page -->

Database | Supabase Docs 
 Skip to content 
 DOCS Start 
 Products 
 Build 
 Manage 
 Reference 
 Resources 
 DOCS 
 Search docs... 
 Ctrl K 
 Main menu 
 Database 
 Overview 
 Fundamentals Connecting to your database
 Connecting to your database 
 Connection pooling and limits 
 Serverless drivers 
 Importing data
 Securing your data
 Working with your database (basics) Managing tables and data
 Views
 Working with arrays
 Managing indexes
 Querying joins and nested tables
 JSON and unstructured data
 Working with your database (intermediate) Implementing cascade deletes
 Deleting data and dropping objects safely
 Managing enums
 Managing database functions
 Debugging database functions
 Managing database triggers
 Managing database webhooks
 Using Full Text Search
 Partitioning your tables
 Migrating to pg_partman
 Managing connections
 Managing event triggers
 OrioleDB Overview
 Multigres Overview
 Compatibility
 Access and security Row Level Security
 Row Level Security Performance
 Column Level Security
 Managing Postgres Roles
 Using Custom Postgres Roles
 Managing secrets with Vault
 Superuser Access and Unsupported Operations
 Configuration, optimization, and testing Database configuration
 Query optimization
 Database Advisors
 Testing your database
 Customizing Postgres config
 Postgres log configuration
 Debugging Timeouts
 Inspect the database
 Debugging performance issues
 Supavisor
 Troubleshooting
 ORM Quickstarts Prisma
 Connecting with Prisma 
 Prisma troubleshooting 
 Drizzle
 Postgres.js
 GUI quickstarts pgAdmin
 PSQL
 DBeaver
 Metabase
 Beekeeper Studio
 Database replication Overview
 Pipelines
 Setting up 
 BigQuery 
 ClickHouse 
 DuckLake 
 Snowflake 
 Monitoring 
 FAQ 
 Manual replication
 Setting up 
 Monitoring 
 FAQ 
 Extensions Overview
 HypoPG: Hypothetical indexes
 plv8 (deprecated)
 http: RESTful Client
 index_advisor: Query optimization
 PGAudit: Postgres Auditing
 pgjwt (deprecated)
 PGroonga: Multilingual Full Text Search
 pgRouting: Geospatial Routing
 pg_cron: Schedule Recurring Jobs
 pg_graphql: GraphQL Support
 pg_hashids: Short UIDs
 pg_jsonschema: JSON Schema Validation
 pg_net: Async Networking
 pg_partman: Partition management
 pg_plan_filter: Restrict Total Cost
 postgres_fdw: query data from an external Postgres server
 pgvector: Embeddings and vector similarity
 pg_stat_statements: SQL Planning and Execution Statistics
 pg_repack: Storage Optimization
 PostGIS: Geo queries
 pgmq: Queues
 pgsodium (pending deprecation): Encryption Features
 pgTAP: Unit Testing
 plpgsql_check: PL/pgSQL Linter
 timescaledb (deprecated)
 uuid-ossp: Unique Identifiers
 RUM: inverted index for full-text search
 Foreign Data Wrappers Overview
 Sources
 Airtable 
 Auth0 
 AWS Cognito 
 AWS DynamoDB 
 AWS S3 
 AWS S3 Vectors 
 BigQuery 
 Cal.com 
 Calendly 
 Clerk 
 ClickHouse 
 Cloudflare D1 
 DuckDB 
 Firebase 
 Gravatar 
 HubSpot 
 Iceberg 
 Infura 
 Logflare 
 MongoDB 
 MSSQL 
 MySQL 
 Notion 
 OpenAPI 
 Orb 
 Paddle 
 Redis 
 Shopify 
 Slack 
 Snowflake 
 Stripe 
 Examples Drop All Tables in Schema
 Select First Row per Group
 Print Postgres Version
 Replicating from Supabase to External Postgres
 DOCS Start 
 Products 
 Build 
 Manage 
 Reference 
 Resources 
 DOCS 
 Search docs... 
 Ctrl K 
 Database 
 Database
 Use Supabase to connect, manage, and secure your Postgres database.
 Every Supabase project gets a full Postgres database, not a Postgres abstraction. This database is the foundation that Auth, Storage, Realtime, and Edge Functions are built on, and Supabase manages daily database backups and offers point-in-time recovery on paid plans.
 Work with your project's database in the following ways:
 Visually using the Table Editor section of the Dashboard.
 With query syntax using the SQL Editor section of the Dashboard.
 Programmatically using a variety of different methods.
 Get started # 
 If you're new to the database section, these are the pages to read first:
 Connect to your database
 Connection strings, the Supavisor connection pooler, and when to use direct, transaction, or session mode. 
 Tables and data
 Create tables and relationships, and edit rows from the Dashboard. 
 Import data
 Load existing data from CSV files, `pg_dump`, or another Postgres database. 
 Secure your data
 Row Level Security (RLS) is how Supabase makes the database safe to query directly from the client. Read this before exposing any table to your app. 
 Extensions
 Add Postgres extensions from the Dashboard, including `pgvector` for embeddings, `PostGIS` for geospatial data, and `pg_cron` for scheduled jobs. 
 Run SQL commands
 Use the Dashboard's SQL Editor for ad-hoc queries and saved snippets. 
 Next steps # 
 Once you've covered the basics, these guides help with other use cases and features:
 Database functions
 Run logic inside the database in response to inserts, updates, or deletes. 
 Triggers
 Run logic inside the database in response to inserts, updates, or deletes. 
 Database webhooks
 Send row changes to an external HTTP endpoint. 
 Replication and read replicas
 Stream changes to other systems or read from a geographically closer replica. 
 Backups
 Daily backups on every project, with point-in-time recovery on paid plans. Backups cover the database itself; objects stored through the Storage API are not included. 
 Query performance and optimization
 Indexes, the query planner, and tools for finding slow queries. 
 Roles and permissions
 The Postgres roles Supabase ships with and how to add your own. 
 Deployment & Branching
 Preview environments, branching, migrations, and production readiness for your database changes. 
 Edit this page on GitHub 
 Is this helpful?
 No Yes 
 AI Tools
 Connect your AI agent Copy as Markdown Ask ChatGPT Ask Claude 
 Need some help?
 Contact support 
 Latest product updates?
 See Changelog 
 Something's not right?
 Check system status 
 © Supabase Inc — Contributing Author Styleguide Open Source SupaSquad Privacy Settings 
 Twitter 
 GitHub 
 Discord 
 Youtube 
 Database 
 Overview
