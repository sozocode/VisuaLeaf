<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="VisuaLeaf — MongoDB GUI logo" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — Visual MongoDB GUI for Developers</h1>

<p align="center">
  <strong>Build MongoDB queries visually. Design aggregation pipelines. Visualize schemas. Generate queries with AI.</strong>
</p>

<p align="center">
  A modern <strong>MongoDB GUI</strong> and <strong>MongoDB client</strong> for macOS, Windows, and Linux. Explore, query, and understand your data — without memorizing syntax.
</p>

<p align="center">
  <a href="https://visualeaf.com">Website</a> •
  <a href="https://visualeaf.com/download">Download</a> •
  <a href="https://visualeaf.com/docs">Documentation</a> •
  <a href="https://visualeaf.com/features">Features</a> •
  <a href="https://visualeaf.com/pricing">Pricing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Platform: macOS, Windows, Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas and self-hosted">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="License">
</p>

---

## What is VisuaLeaf?

VisuaLeaf is a visual **MongoDB IDE** for developers, DBAs, and data teams. Drag-and-drop a query, prototype an aggregation pipeline, see your schema as a diagram, manage indexes, profile slow queries, sync data between environments, build dashboards, and generate MongoDB with AI — all in one app. It connects directly to MongoDB Atlas, self-hosted clusters, or local databases.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/github/query-builder.webp" alt="VisuaLeaf MongoDB GUI — visual query builder screenshot" width="850">
  </a>
</p>

### Why teams choose VisuaLeaf

- **Visual MongoDB query builder** — point, click, filter. No syntax memorization.
- **Drag-and-drop aggregation pipeline designer** — preview data at every stage.
- **AI MongoDB query generator** — describe what you want in plain English.
- **Interactive schema diagrams** — understand collection structure and relationships at a glance.
- **Visual index management** — create, review, and tune indexes without shell syntax.
- **Data sync and migration** — copy and keep collections in sync across local, Atlas, and team environments.
- **JSON Schema validation editor** — design, validate, and deploy schemas with full BSON support.
- **Charts, dashboards, shell, SQL mode, GridFS, profiler, RBAC, and more** — every MongoDB workflow, one app.
- **Your data stays local** — direct connections, no proxy, no telemetry on your queries.

---

## Features

### MongoDB Connection Manager
Organize MongoDB connections for local, Atlas, and team environments in one place. Save connection profiles, group by project or environment, and switch between databases instantly — with SSH tunneling support for remote clusters.

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://release.sozocode.com/github/connection-manager-visualeaf.webp" alt="MongoDB connection manager for local, Atlas, and remote databases" width="800">
  </a>
</p>

[Explore the Connection Manager →](https://visualeaf.com/features/connection-manager/)

---

### Browse MongoDB Collections
Explore MongoDB documents three ways — tree view for nested data, table view for fast scanning, and BSON view for raw type fidelity. Filter, sort, and edit inline, then drill into nested arrays and subdocuments without losing context.

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/github/3Views.webp" alt="Browse MongoDB collections in tree, table, and BSON views" width="800">
  </a>
</p>

[Explore Browse Collections →](https://visualeaf.com/features/browse-collections/)

---

### Visual MongoDB Query Builder
Build MongoDB queries visually with filters and logic groups — no code required. Use field selectors, operator dropdowns, and condition builders to assemble powerful `find()` queries faster than writing them by hand. Perfect for developers of all skill levels and for exploring unfamiliar collections.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/github/query-builder.webp" alt="Visual MongoDB query builder — build queries without code" width="800">
  </a>
</p>

[Explore the Visual Query Builder →](https://visualeaf.com/features/visual-query-builder/)

---

### MongoDB Aggregation Pipeline Builder
Design and visualize complex MongoDB aggregation pipelines with a drag-and-drop stage palette. Add `$match`, `$group`, `$lookup`, `$project`, `$unwind`, and more — preview transformed data at each step, and switch between visual and code modes for full flexibility.

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/github/aggregation-builder.webp" alt="MongoDB aggregation pipeline builder — visual stage designer with live previews" width="800">
  </a>
</p>

[Explore the Aggregation Pipeline Builder →](https://visualeaf.com/features/aggregation-pipeline/)

---

### AI Assistant for MongoDB Queries
Generate MongoDB queries and aggregation pipelines from natural language. Describe what you want — "top 10 customers by revenue last quarter" — and the AI helper writes the query inside your visual workflow. Great for learning MongoDB syntax or accelerating complex pipelines.

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/github/ai-assistant-visualeaf.webp" alt="AI assistant generating MongoDB queries from natural language" width="800">
  </a>
</p>

[Explore the AI Helper →](https://visualeaf.com/features/ai-helper/)

---

### SQL Mode for MongoDB
Query MongoDB with familiar SQL syntax. VisuaLeaf translates `SELECT`, `WHERE`, `GROUP BY`, and `JOIN` to MongoDB queries and aggregation pipelines automatically — a smooth onramp for analysts and developers coming from PostgreSQL or MySQL.

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/github/sql-query-mode-visualeaf.webp" alt="SQL mode for MongoDB — write SQL queries against MongoDB collections" width="800">
  </a>
</p>

[Explore SQL Mode →](https://visualeaf.com/features/sql-mode/)

---

### MongoDB Shell with Visual Output
Run MongoDB shell commands with syntax highlighting, autocomplete, and history — then view results as a table, tree, or JSON. Execute scripts and admin commands without losing the readability of a visual client.

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/github/mongo-shell.webp" alt="MongoDB shell with visual output in table, tree, and JSON" width="800">
  </a>
</p>

[Explore the MongoDB Shell →](https://visualeaf.com/features/mongo-shell/)

---

### MongoDB Schema Visualization & Diagrams
Visualize MongoDB collections and relationships with interactive schema diagrams. Auto-discover field types, nested documents, and references between collections — ideal for onboarding to a new database, documenting data, or planning a redesign.

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/github/schema-design-visualeaf.webp" alt="MongoDB schema visualization — interactive diagram of collections and relationships" width="800">
  </a>
</p>

[Explore Schema Visualization →](https://visualeaf.com/features/visual-schema/)

---

### MongoDB JSON Schema Validation
Design and enforce MongoDB JSON Schema validation with a tree-based editor. Full BSON type support, validation rules, and one-click verification against live collections — create, edit, and deploy schemas without hand-writing JSON.

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://release.sozocode.com/github/json-schema-visualeaf.webp" alt="MongoDB JSON Schema validation editor with BSON type support" width="800">
  </a>
</p>

[Explore JSON Schema Validation →](https://visualeaf.com/features/schema-validation/)

---

### MongoDB Index Manager
Create, view, and manage MongoDB indexes visually — single-field, compound, text, TTL, unique, and partial. Review index size and usage stats, spot missing or redundant indexes, and drop or rebuild them safely, all without shell syntax.

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/github/index-manager.webp" alt="MongoDB index manager — create and tune indexes visually with size and usage stats" width="800">
  </a>
</p>

[Explore the Index Manager →](https://visualeaf.com/features/index-manager/)

---

### MongoDB Query Profiler
Analyze MongoDB query performance with execution plans, timing metrics, and index usage. Spot slow operations, understand `$explain` output, and get optimization recommendations to keep your database fast.

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://release.sozocode.com/github/query-profiler-visualeaf.webp" alt="MongoDB query profiler with execution plans and index analysis" width="800">
  </a>
</p>

[Explore the Query Profiler →](https://visualeaf.com/features/query-profiler/)

---

### MongoDB Collection Compare
Compare MongoDB collections side-by-side to spot structural or data differences. Sync between environments, audit changes after a deploy, and keep dev, staging, and production aligned.

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://release.sozocode.com/github/collection-compare-visualeaf.webp" alt="MongoDB collection compare — side-by-side diff of collections" width="800">
  </a>
</p>

[Explore Collection Compare →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync — Sync & Migrate Data
Sync, copy, and migrate data between MongoDB databases, collections, and environments. Move a local collection to Atlas, keep dev, staging, and production aligned, and run filtered or scheduled sync jobs with a safe dry-run preview before anything is written.

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/github/mongo-sync.webp" alt="MongoSync — sync and migrate MongoDB data between databases and environments" width="800">
  </a>
</p>

[Explore MongoSync →](https://visualeaf.com/features/mongosync/)

---

### MongoDB Task Manager (Import, Export, ETL)
Run repeated MongoDB operations from one place: import, export, migration, schema transformation, data masking, and ETL workflows. Real-time monitoring and automation keep complex jobs consistent across projects.

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://release.sozocode.com/github/task-manager-visual-hierarchy.webp" alt="MongoDB task manager — import, export, and ETL automation" width="800">
  </a>
</p>

[Explore the Task Manager →](https://visualeaf.com/features/task-manager/)

---

### MongoDB GridFS Viewer
Browse, upload, download, and preview files stored in MongoDB GridFS. Familiar table view, drag-and-drop uploads with progress tracking, and inline previews for images, PDFs, and documents.

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/github/gridfs-viewer-visualeaf.webp" alt="MongoDB GridFS viewer with file previews and drag-and-drop uploads" width="800">
  </a>
</p>

[Explore the GridFS Viewer →](https://visualeaf.com/features/gridfs-viewer/)

---

### MongoDB Chart Builder, Charts & Dashboards
Turn MongoDB query results into bar charts, line graphs, pie charts, and dashboards. Drag-and-drop builder, no extra BI tool required — explore results visually and share insights with your team.

<p align="center">
  <a href="https://visualeaf.com/features/chart-builder/">
    <img src="https://release.sozocode.com/github/charts-dashboards-visualeaf.webp" alt="MongoDB chart builder and dashboards from query results" width="800">
  </a>
</p>

[Explore Charts & Dashboards →](https://visualeaf.com/features/chart-builder/)

---

### Split Panel Views
Work with multiple MongoDB collections, queries, or tools side-by-side. Split horizontally or vertically, drag tabs to reorganize, and compare results across databases or environments in one workspace.

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/github/split-panel-views-visualeaf.webp" alt="Split panel views — compare MongoDB queries and data side by side" width="800">
  </a>
</p>

[Explore Split Panel Views →](https://visualeaf.com/features/split-panel-views/)

---

### MongoDB RBAC Dashboard
Manage MongoDB users, roles, and permissions visually. Review who has access to which database and collection, audit privileges, and keep team access tidy — without hand-editing role documents.

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://release.sozocode.com/github/rbac-dashboard-visualeaf.webp" alt="MongoDB RBAC dashboard for users, roles, and permissions" width="800">
  </a>
</p>

[Explore the RBAC Dashboard →](https://visualeaf.com/features/rbac-dashboard/)

---

## Security & Privacy

**Your MongoDB data stays local.** VisuaLeaf connects directly from your machine to your MongoDB instances — we never see, store, or proxy your data.

- **Direct connections** — localhost, MongoDB Atlas, or any self-hosted cluster
- **SSH tunneling** — secure connections through bastion hosts
- **Offline-capable** — works fully offline after activation
- **Local credential storage** — connection details encrypted on your machine
- **No query telemetry** — we don't track what you query or what data you access

---

## Supported Platforms

| Platform | Architecture | Download |
|----------|--------------|----------|
| macOS    | Intel & Apple Silicon | [Download](https://visualeaf.com/download) |
| Windows  | x64 | [Download](https://visualeaf.com/download) |
| Linux    | x64, AppImage, deb | [Download](https://visualeaf.com/download) |

Works with **MongoDB 4.x, 5.x, 6.x, 7.x, 8.x**, **MongoDB Atlas**, and self-hosted replica sets and sharded clusters.

---

## Getting Started

1. **Download** VisuaLeaf from [visualeaf.com/download](https://visualeaf.com/download)
2. **Install** the application on macOS, Windows, or Linux
3. **Connect** to your MongoDB instance (localhost, Atlas, or remote)
4. **Explore** your data with visual tools

---

## Pricing

| Plan | Price | Description |
|------|-------|-------------|
| **Community** | Free | Core features, single connection |
| **Basic** | $79 one-time + 1 year of updates | Full feature set, unlimited connections |
| **Team** | $299/year | Collaboration, sharing, priority support |

All plans include a **14-day free trial** of Pro features.

[View full pricing →](https://visualeaf.com/pricing)

---

## Documentation

- [Getting Started Guide](https://visualeaf.com/docs)
- [Visual Query Builder](https://visualeaf.com/docs/mongo-query)
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

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)** — Open-source MongoDB viewer (lightweight, read-only)

---

<p align="center">
  Made with care by <a href="https://visualeaf.com">SozoCode</a>
</p>
