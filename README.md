<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="VisuaLeaf logo" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — Visual Database GUI for MongoDB & SQL</h1>

<p align="center">
  <strong>Build queries visually. Draw ER diagrams. Design aggregation pipelines. Chart your results. One workspace for MongoDB, PostgreSQL, MySQL, SQLite and 30+ more databases.</strong>
</p>

<p align="center">
  A modern <strong>database client</strong> for macOS, Windows, and Linux. Explore, query, and understand your data, whether it lives in documents, tables, or keys, without memorizing syntax.
</p>

<p align="center">
  <a href="https://visualeaf.com">Website</a> •
  <a href="https://visualeaf.com/download">Download</a> •
  <a href="https://visualeaf.com/docs">Documentation</a> •
  <a href="https://visualeaf.com/features">Features</a> •
  <a href="https://visualeaf.com/database">Databases</a> •
  <a href="https://visualeaf.com/pricing">Pricing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Platform: macOS, Windows, Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas and self-hosted">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL: PostgreSQL, MySQL, SQL Server, SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="36 supported databases">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="License">
</p>

<p align="center">
  <strong>English</strong> •
  <a href="README.zh-CN.md">简体中文</a> •
  <a href="README.zh-TW.md">繁體中文</a> •
  <a href="README.ja.md">日本語</a> •
  <a href="README.ko.md">한국어</a> •
  <a href="README.es.md">Español</a> •
  <a href="README.pt-BR.md">Português (Brasil)</a> •
  <a href="README.de.md">Deutsch</a> •
  <a href="README.fr.md">Français</a> •
  <a href="README.ru.md">Русский</a> •
  <a href="README.hi.md">हिन्दी</a>
</p>

---

## What is VisuaLeaf?

VisuaLeaf is a visual **database workspace** for developers, DBAs, and data teams. It started as a MongoDB GUI and now works just as well as a **SQL client**: connect to MongoDB, PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, SQLite, ClickHouse, Redis and more, and use the same visual workflow on every one of them.

Build a query by pointing and clicking, draw an ER diagram from your foreign keys or from what MongoDB actually stores, edit tables and documents inline, profile slow queries, move data between databases, build dashboards, and let AI draft queries against your real schema. Everything runs locally and connects directly to your databases.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="VisuaLeaf visual SQL query builder joining MySQL tables with a live results grid" width="850">
  </a>
</p>

### Why teams choose VisuaLeaf

- **One app for MongoDB and SQL**: 36 databases, document, relational, key-value and analytics, in one workspace.
- **All SQL features are free** in the Community Edition.
- **Visual query builders for both worlds**: SQL with JOINs suggested from foreign keys, MongoDB filters with AND/OR groups.
- **ER diagrams and schema visualization**: generated from SQL foreign keys or inferred from MongoDB collections, and you can materialize a design into real tables or collections.
- **SQL editor and MongoDB shell**: syntax highlighting, autocomplete, history, and results as a grid, tree, or JSON.
- **Drag-and-drop aggregation pipeline designer** with a preview at every stage.
- **AI assistant** that writes queries, aggregations and charts from plain English and explains query plans.
- **Built-in MCP server**: connect Claude, Cursor and other AI tools to your databases.
- **Fast on real data**: 50,000 documents open in seconds, and documents at MongoDB's 16 MB limit are handled comfortably.
- **Your data stays local**: direct connections, no proxy, no telemetry on your queries.

---

## Supported Databases

| Category | Databases |
|----------|-----------|
| **Document & key-value** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/), [Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/), [Amazon DocumentDB](https://visualeaf.com/database/documentdb/), [Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL & compatible** | [PostgreSQL](https://visualeaf.com/database/postgresql/), [Neon](https://visualeaf.com/database/neon/), [Supabase](https://visualeaf.com/database/supabase/), [TimescaleDB](https://visualeaf.com/database/timescaledb/), [Citus](https://visualeaf.com/database/citus/), [Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/), [Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/), [Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/), [CockroachDB](https://visualeaf.com/database/cockroachdb/), [YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL & compatible** | [MySQL](https://visualeaf.com/database/mysql/), [MariaDB](https://visualeaf.com/database/mariadb/), [Percona Server](https://visualeaf.com/database/percona/), [TiDB](https://visualeaf.com/database/tidb/), [Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/), [Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **Enterprise SQL** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/), [Azure SQL Database](https://visualeaf.com/database/azure-sql/), [Oracle](https://visualeaf.com/database/oracle/), [IBM Db2](https://visualeaf.com/database/db2/), [Firebird](https://visualeaf.com/database/firebird/) |
| **Analytics, warehouse & streaming** | [ClickHouse](https://visualeaf.com/database/clickhouse/), [Amazon Redshift](https://visualeaf.com/database/amazon-redshift/), [Snowflake](https://visualeaf.com/database/snowflake/), [CrateDB](https://visualeaf.com/database/cratedb/), [QuestDB](https://visualeaf.com/database/questdb/), [RisingWave](https://visualeaf.com/database/risingwave/), [Materialize](https://visualeaf.com/database/materialize/) |
| **File-based & embedded** | [SQLite](https://visualeaf.com/database/sqlite/), [DuckDB](https://visualeaf.com/database/duckdb/), [H2](https://visualeaf.com/database/h2/), [HSQLDB](https://visualeaf.com/database/hsqldb/), [Apache Derby](https://visualeaf.com/database/derby/) |

[See all supported databases →](https://visualeaf.com/database)

---

## Features for MongoDB and SQL

These tools work the same way whether you're connected to MongoDB or a SQL database.

### Connection Manager
Keep MongoDB, PostgreSQL, MySQL, SQL Server, SQLite and other connections in one place. Save connection profiles, group them by project or environment, and switch between databases instantly, with SSH tunneling and SSL for remote and cloud instances.

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="VisuaLeaf Connection Manager with a project tree of environments and connections" width="800">
  </a>
</p>

[Explore the Connection Manager →](https://visualeaf.com/features/connection-manager/)

---

### Visual Query Builder
Build queries without writing syntax. For SQL, drop tables on the canvas and VisuaLeaf suggests JOINs from your foreign keys while it writes the SQL in a live preview. For MongoDB, assemble `find()` filters with field selectors, operator dropdowns, and AND/OR groups. Drop into raw syntax whenever you want control back.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="Visual MongoDB query builder with filter groups and results" width="800">
  </a>
</p>

[Explore the Visual Query Builder →](https://visualeaf.com/features/visual-query-builder/)

---

### ER Diagrams & Visual Schema
Generate ER diagrams from SQL foreign keys, or from what MongoDB actually stores in each collection, with field types inferred automatically. It works the other way too: design a schema on the canvas, hit **Materialize**, and the tables or collections are created for you.

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="ER diagram generated from MySQL foreign keys" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="MongoDB schema diagram showing collections and relationships" width="800">
  </a>
</p>

[Explore ER Diagrams & Visual Schema →](https://visualeaf.com/features/visual-schema/)

---

### SQL Editor & MongoDB Shell
Run SQL scripts or `mongosh` commands with syntax highlighting, autocomplete, and command history, then view the results as an editable grid, a tree, or JSON. Save scripts, run them again later, and keep every result readable.

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="PostgreSQL SQL editor with results grid next to table management" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="MongoDB shell with visual output in table, tree, and JSON" width="800">
  </a>
</p>

[Explore the SQL Editor & MongoDB Shell →](https://visualeaf.com/features/mongo-shell/)

---

### Table Management
Create and alter SQL tables visually. Edit columns, types, defaults and nullability, manage primary and foreign keys, indexes, constraints, triggers and partitions, and check the generated DDL before you apply it. Views, sequences, procedures and users are managed from the same workspace.

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="Table management for a PostgreSQL table showing columns, foreign keys, and indexes" width="800">
  </a>
</p>

[Read the Table Management docs →](https://visualeaf.com/docs/sql-table)

---

### Query Profiler
A query that's quick on ten thousand rows can crawl on ten million. The profiler shows which queries are costing you and why, with execution plans, timing metrics, index usage, and suggestions for the index that would fix it.

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="Query Profiler with an execution-time timeline and queries grouped by shape" width="800">
  </a>
</p>

[Explore the Query Profiler →](https://visualeaf.com/features/query-profiler/)

---

### Charts & Dashboards
Chart the results of a SQL query or a MongoDB aggregation with 20+ chart types, then pin them to dashboards. No separate BI tool required.

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="Dashboard of store sales with line, donut, pie, heatmap, funnel and radar charts" width="800">
  </a>
</p>

[Explore Charts & Dashboards →](https://visualeaf.com/features/charts-dashboard/)

---

### Task Manager (Import, Export, Migration)
Run imports, exports, and migrations between MongoDB, SQL databases, and files (JSON, CSV, SQL, mongodump), and keep working while they run. Remap and transform fields, mask sensitive data, schedule and chain jobs, and review the full history of what each task did.

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="Data Transfer with tasks in folders on the left and the selected task's details on the right" width="800">
  </a>
</p>

[Explore the Task Manager →](https://visualeaf.com/features/task-manager/)

---

### Split Panel Views
Open collections, tables, queries, ER diagrams and dashboards side by side. Split horizontally or vertically, drag tabs to reorganize, and keep scrolling in sync so you can compare results across databases or environments.

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="Split panel views comparing queries and data side by side" width="800">
  </a>
</p>

[Explore Split Panel Views →](https://visualeaf.com/features/split-panel-views/)

---

### AI Assistant & MCP Server
Describe what you want and the assistant writes the query against your real schema. It drafts aggregations, turns results into charts, generates ER diagrams, reviews how your data is structured, and explains query plans in plain English instead of nested JSON. With the built-in **MCP server**, you can also connect Claude, Cursor, and other AI tools directly to your databases.

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="AI assistant generating database queries from natural language" width="800">
  </a>
</p>

[Explore the AI Assistant →](https://visualeaf.com/features/ai-helper/)

---

## MongoDB Features

The tools VisuaLeaf was built on, for MongoDB, Atlas, Cosmos DB and DocumentDB.

### Browse Collections
Explore documents three ways: tree view for nested data, table view for fast scanning, and BSON view for raw type fidelity. Filter, sort, and edit inline, then drill into nested arrays and subdocuments without losing context.

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="Browse MongoDB collections in tree, table, and BSON views" width="800">
  </a>
</p>

[Explore Browse Collections →](https://visualeaf.com/features/browse-collections/)

---

### Aggregation Pipeline Builder
Design MongoDB aggregation pipelines with a drag-and-drop stage palette. Add `$match`, `$group`, `$lookup`, `$project`, `$unwind`, and more, preview the transformed data at each stage, and switch between visual and code modes.

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="MongoDB aggregation pipeline builder with stage-by-stage previews" width="800">
  </a>
</p>

[Explore the Aggregation Pipeline Builder →](https://visualeaf.com/features/aggregation-pipeline/)

---

### SQL Mode for MongoDB
Query MongoDB collections with familiar SQL. VisuaLeaf translates `SELECT`, `WHERE`, `GROUP BY`, and `JOIN` into the `find()` query or aggregation pipeline it becomes, so you can see exactly what runs.

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="SQL mode for MongoDB, writing SQL against MongoDB collections" width="800">
  </a>
</p>

[Explore SQL Mode →](https://visualeaf.com/features/sql-mode/)

---

### JSON Schema Validation
Design and enforce MongoDB JSON Schema validation with a tree-based editor. Full BSON type support, validation rules, and one-click verification against live collections.

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="Schema Builder showing a validator with required fields, BSON types and rules" width="800">
  </a>
</p>

[Explore JSON Schema Validation →](https://visualeaf.com/features/schema-validation/)

---

### Index Manager
Create, view, and manage MongoDB indexes visually: single-field, compound, text, TTL, unique, and partial. Review index size and usage stats, spot missing or redundant indexes, and drop or rebuild them safely.

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="MongoDB index manager with size and usage stats" width="800">
  </a>
</p>

[Explore the Index Manager →](https://visualeaf.com/features/index-manager/)

---

### Collection Compare
Compare MongoDB collections side by side to spot structural or data differences. Audit changes after a deploy and keep dev, staging, and production aligned.

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="Data Compare canvas pairing collections and tables in a source and a target database" width="800">
  </a>
</p>

[Explore Collection Compare →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
Sync, copy, and migrate data between MongoDB databases, collections, and environments. Move a local collection to Atlas, run filtered or scheduled sync jobs, keep data in sync in real time with change streams, and preview everything with a dry run before it's written.

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="MongoSync syncing MongoDB data between databases and environments" width="800">
  </a>
</p>

[Explore MongoSync →](https://visualeaf.com/features/mongosync/)

---

### GridFS Viewer
Browse, upload, download, and preview files stored in MongoDB GridFS, with drag-and-drop uploads, progress tracking, and inline previews for images, PDFs, and documents.

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="MongoDB GridFS viewer with file previews" width="800">
  </a>
</p>

[Explore the GridFS Viewer →](https://visualeaf.com/features/gridfs-viewer/)

---

### RBAC Dashboard
Manage users, roles, and permissions visually. Review who has access to which database and collection, audit privileges, and keep team access tidy without hand-editing role documents.

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="Users and Roles dashboard with user, role and session counts and quick actions" width="800">
  </a>
</p>

[Explore the RBAC Dashboard →](https://visualeaf.com/features/rbac-dashboard/)

---

### Replica Sets & Sharded Clusters
See replica set topology, health and the oplog, run rolling maintenance and reconfigs, take replica-set-aware backups, and manage sharded clusters from the same app.

---

## Redis

Scan the keyspace by pattern, open each value type in the editor that fits it, filter values, work in the built-in Redis CLI, and test ACL rules.

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="VisuaLeaf Redis key browser" width="800">
  </a>
</p>

[Explore VisuaLeaf for Redis →](https://visualeaf.com/database/redis/)

---

## Security & Privacy

**Your data stays local.** VisuaLeaf connects directly from your machine to your databases. We never see, store, or proxy your data.

- **Direct connections**: localhost, MongoDB Atlas, managed cloud databases, or any self-hosted server
- **SSH tunneling and SSL**: secure connections through bastion hosts and to cloud instances
- **Offline-capable**: works fully offline after activation
- **Local credential storage**: connection details encrypted on your machine
- **No query telemetry**: we don't track what you query or what data you access

---

## Supported Platforms

| Platform | Architecture | Download |
|----------|--------------|----------|
| macOS    | Intel & Apple Silicon | [Download](https://visualeaf.com/download) |
| Windows  | x64 | [Download](https://visualeaf.com/download) |
| Linux    | x64, AppImage, deb | [Download](https://visualeaf.com/download) |

Works with **MongoDB 4.x–8.x** (Atlas, replica sets, and sharded clusters), **PostgreSQL**, **MySQL**, **MariaDB**, **SQL Server**, **Oracle**, **SQLite**, **Redis**, and [30+ more databases](https://visualeaf.com/database).

---

## Getting Started

1. **Download** VisuaLeaf from [visualeaf.com/download](https://visualeaf.com/download)
2. **Install** it on macOS, Windows, or Linux
3. **Connect** to MongoDB, PostgreSQL, MySQL, SQLite, or any other supported database
4. **Explore** your data with visual tools

---

## Pricing

| Plan | Price | Description |
|------|-------|-------------|
| **Community** | Free | All SQL features, up to 3 saved MongoDB connections, shell, browsing, index management, ER diagrams |
| **Basic** | $79 one-time + 1 year of updates | Visual query and aggregation builders, Redis, query profiler, import/export tasks, data masking, AI assistant |
| **Professional** | $149 one-time + 1 year of updates | Everything in Basic plus unlimited tasks, collection compare, MongoSync, RBAC, charts & dashboards, MCP server, priority support |

Every license is perpetual. Start with a **14-day free trial** of Professional features, no credit card required.

[View full pricing →](https://visualeaf.com/pricing)

---

## Documentation

- [Getting Started Guide](https://visualeaf.com/docs)
- [Connection Manager](https://visualeaf.com/docs/connection-manager)
- [SQL Editor](https://visualeaf.com/docs/sql-editor)
- [SQL Query Builder](https://visualeaf.com/docs/sql-query-builder)
- [MongoDB Visual Query Builder](https://visualeaf.com/docs/mongo-query)
- [Aggregation Pipeline](https://visualeaf.com/docs/aggregation)
- [Schema Designer](https://visualeaf.com/docs/schema-designer)
- [FAQ](https://visualeaf.com/faq)

---

## Connect With Us

- Website: [visualeaf.com](https://visualeaf.com)
- Twitter: [@SozoCode](https://twitter.com/SozoCode)
- Email: [support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn: [SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## Related Projects

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**: Open-source MongoDB viewer (lightweight, read-only)

---

<p align="center">
  Made with care by <a href="https://visualeaf.com">SozoCode</a>
</p>
