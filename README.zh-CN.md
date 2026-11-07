<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="VisuaLeaf 标志" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — 面向 MongoDB 与 SQL 的可视化数据库 GUI</h1>

<p align="center">
  <strong>可视化构建查询。绘制 ER 图。设计聚合管道。把结果绘成图表。一个工作区，同时搞定 MongoDB、PostgreSQL、MySQL、SQLite 以及 30 多种其他数据库。</strong>
</p>

<p align="center">
  一款支持 macOS、Windows 和 Linux 的现代 <strong>数据库客户端</strong>。无论数据存放在文档、表还是键中，都能轻松浏览、查询并理解你的数据，无需死记语法。
</p>

<p align="center">
  <a href="https://visualeaf.com">官网</a> •
  <a href="https://visualeaf.com/download">下载</a> •
  <a href="https://visualeaf.com/docs">文档</a> •
  <a href="https://visualeaf.com/features">功能</a> •
  <a href="https://visualeaf.com/database">支持的数据库</a> •
  <a href="https://visualeaf.com/pricing">定价</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="平台：macOS、Windows、Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB：Atlas 与自托管">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL：PostgreSQL、MySQL、SQL Server、SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="支持 36 种数据库">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="许可证">
</p>

<p align="center">
  <a href="README.md">English</a> •
  <strong>简体中文</strong> •
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

## VisuaLeaf 是什么？

VisuaLeaf 是一款面向开发者、DBA 和数据团队的可视化**数据库工作区**。它最初是一款 MongoDB GUI，如今作为 **SQL 客户端**同样得心应手：连接 MongoDB、PostgreSQL、MySQL、MariaDB、SQL Server、Oracle、SQLite、ClickHouse、Redis 等数据库，并在每一种数据库上使用同一套可视化工作流。

点选几下即可构建查询，基于外键或 MongoDB 实际存储的内容绘制 ER 图，直接在表格和文档中内联编辑，剖析慢查询，在数据库之间迁移数据，搭建仪表盘，还可以让 AI 根据你真实的 schema 起草查询。一切都在本地运行，并直接连接到你的数据库。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="VisuaLeaf 可视化 SQL 查询构建器正在联接 MySQL 表，并实时显示结果网格" width="850">
  </a>
</p>

### 团队为什么选择 VisuaLeaf

- **一款应用同时覆盖 MongoDB 和 SQL**：36 种数据库，文档型、关系型、键值型和分析型，全部在一个工作区中。
- **所有 SQL 功能在 Community Edition（社区版）中完全免费**。
- **两个世界都有可视化查询构建器**：SQL 可根据外键自动建议 JOIN，MongoDB 可用 AND/OR 分组组合过滤条件。
- **ER 图与 schema 可视化**：可由 SQL 外键生成，也可从 MongoDB 集合中推断，并且可以把设计直接物化为真实的表或集合。
- **SQL 编辑器与 MongoDB shell**：语法高亮、自动补全、历史记录，结果可按网格、树或 JSON 查看。
- **拖拽式聚合管道设计器**，每个阶段都有预览。
- **AI 助手**：用自然语言生成查询、聚合和图表，并解释查询计划。
- **内置 MCP 服务器**：把 Claude、Cursor 等 AI 工具接入你的数据库。
- **在真实数据上依然快速**：50,000 条文档几秒内打开，达到 MongoDB 16 MB 上限的文档也能从容处理。
- **数据留在本地**：直连数据库，无代理，不对你的查询做任何遥测。

---

## 支持的数据库

| 类别 | 数据库 |
|----------|-----------|
| **文档型与键值型** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/)、[Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/)、[Amazon DocumentDB](https://visualeaf.com/database/documentdb/)、[Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL 及兼容数据库** | [PostgreSQL](https://visualeaf.com/database/postgresql/)、[Neon](https://visualeaf.com/database/neon/)、[Supabase](https://visualeaf.com/database/supabase/)、[TimescaleDB](https://visualeaf.com/database/timescaledb/)、[Citus](https://visualeaf.com/database/citus/)、[Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/)、[Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/)、[Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/)、[CockroachDB](https://visualeaf.com/database/cockroachdb/)、[YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL 及兼容数据库** | [MySQL](https://visualeaf.com/database/mysql/)、[MariaDB](https://visualeaf.com/database/mariadb/)、[Percona Server](https://visualeaf.com/database/percona/)、[TiDB](https://visualeaf.com/database/tidb/)、[Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/)、[Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **企业级 SQL** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/)、[Azure SQL Database](https://visualeaf.com/database/azure-sql/)、[Oracle](https://visualeaf.com/database/oracle/)、[IBM Db2](https://visualeaf.com/database/db2/)、[Firebird](https://visualeaf.com/database/firebird/) |
| **分析、数仓与流式** | [ClickHouse](https://visualeaf.com/database/clickhouse/)、[Amazon Redshift](https://visualeaf.com/database/amazon-redshift/)、[Snowflake](https://visualeaf.com/database/snowflake/)、[CrateDB](https://visualeaf.com/database/cratedb/)、[QuestDB](https://visualeaf.com/database/questdb/)、[RisingWave](https://visualeaf.com/database/risingwave/)、[Materialize](https://visualeaf.com/database/materialize/) |
| **文件型与嵌入式** | [SQLite](https://visualeaf.com/database/sqlite/)、[DuckDB](https://visualeaf.com/database/duckdb/)、[H2](https://visualeaf.com/database/h2/)、[HSQLDB](https://visualeaf.com/database/hsqldb/)、[Apache Derby](https://visualeaf.com/database/derby/) |

[查看全部支持的数据库 →](https://visualeaf.com/database)

---

## MongoDB 与 SQL 通用功能

无论连接的是 MongoDB 还是 SQL 数据库，这些工具的用法都完全一致。

### 连接管理器
把 MongoDB、PostgreSQL、MySQL、SQL Server、SQLite 等连接统一放在一处管理。保存连接配置，按项目或环境分组，在数据库之间即时切换，并通过 SSH 隧道和 SSL 安全访问远程及云端实例。

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="VisuaLeaf 连接管理器，以项目树形式组织环境与连接" width="800">
  </a>
</p>

[了解连接管理器 →](https://visualeaf.com/features/connection-manager/)

---

### 可视化查询构建器
无需编写语法即可构建查询。对于 SQL，把表拖到画布上，VisuaLeaf 会根据外键建议 JOIN，并在实时预览中同步生成 SQL。对于 MongoDB，可通过字段选择器、操作符下拉框和 AND/OR 分组来组装 `find()` 过滤条件。想要完全掌控时，随时可以切回原始语法。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="可视化 MongoDB 查询构建器，带过滤分组与结果" width="800">
  </a>
</p>

[了解可视化查询构建器 →](https://visualeaf.com/features/visual-query-builder/)

---

### ER 图与可视化 Schema
根据 SQL 外键，或根据 MongoDB 每个集合中实际存储的内容生成 ER 图，字段类型自动推断。反过来也行：在画布上设计 schema，点击 **Materialize（物化）**，表或集合就会自动创建好。

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="根据 MySQL 外键生成的 ER 图" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="展示集合及其关系的 MongoDB schema 图" width="800">
  </a>
</p>

[了解 ER 图与可视化 Schema →](https://visualeaf.com/features/visual-schema/)

---

### SQL 编辑器与 MongoDB Shell
运行 SQL 脚本或 `mongosh` 命令，支持语法高亮、自动补全和命令历史，结果可按可编辑网格、树或 JSON 查看。保存脚本以便日后再次运行，每一条结果都清晰可读。

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="PostgreSQL SQL 编辑器，结果网格旁是表管理面板" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="MongoDB shell，可视化输出支持表格、树和 JSON" width="800">
  </a>
</p>

[了解 SQL 编辑器与 MongoDB Shell →](https://visualeaf.com/features/mongo-shell/)

---

### 表管理
以可视化方式创建和修改 SQL 表。编辑列、类型、默认值和可空性，管理主键和外键、索引、约束、触发器和分区，并在应用前检查生成的 DDL。视图、序列、存储过程和用户也在同一个工作区中管理。

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="PostgreSQL 表的表管理界面，显示列、外键和索引" width="800">
  </a>
</p>

[阅读表管理文档 →](https://visualeaf.com/docs/sql-table)

---

### 查询剖析器
一条在一万行上飞快的查询，到了一千万行可能就慢如蜗牛。剖析器会告诉你哪些查询在消耗资源、原因何在，提供执行计划、耗时指标、索引使用情况，以及能解决问题的索引建议。

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="查询剖析器，含执行时间时间线以及按查询形态分组的查询" width="800">
  </a>
</p>

[了解查询剖析器 →](https://visualeaf.com/features/query-profiler/)

---

### 图表与仪表盘
用 20 多种图表类型把 SQL 查询或 MongoDB 聚合的结果绘成图表，再固定到仪表盘上。不需要另外的 BI 工具。

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="门店销售仪表盘，包含折线图、环形图、饼图、热力图、漏斗图和雷达图" width="800">
  </a>
</p>

[了解图表与仪表盘 →](https://visualeaf.com/features/charts-dashboard/)

---

### 任务管理器（导入、导出、迁移）
在 MongoDB、SQL 数据库和文件（JSON、CSV、SQL、mongodump）之间运行导入、导出和迁移任务，任务运行期间可以继续其他工作。支持字段重映射与转换、敏感数据脱敏、任务调度与串联，并可查看每个任务的完整执行历史。

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="数据传输界面，左侧按文件夹组织任务，右侧显示所选任务的详情" width="800">
  </a>
</p>

[了解任务管理器 →](https://visualeaf.com/features/task-manager/)

---

### 分屏视图
把集合、表、查询、ER 图和仪表盘并排打开。支持水平或垂直分屏，拖动标签页重新排列，并保持滚动同步，方便跨数据库或跨环境对比结果。

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="分屏视图，并排对比查询与数据" width="800">
  </a>
</p>

[了解分屏视图 →](https://visualeaf.com/features/split-panel-views/)

---

### AI 助手与 MCP 服务器
描述你想要的结果，助手就会基于你真实的 schema 写出查询。它可以起草聚合、把结果变成图表、生成 ER 图、审查数据结构，并用通俗语言而非层层嵌套的 JSON 解释查询计划。借助内置的 **MCP 服务器**，还可以把 Claude、Cursor 等 AI 工具直接接入你的数据库。

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="AI 助手根据自然语言生成数据库查询" width="800">
  </a>
</p>

[了解 AI 助手 →](https://visualeaf.com/features/ai-helper/)

---

## MongoDB 功能

VisuaLeaf 赖以起家的工具集，适用于 MongoDB、Atlas、Cosmos DB 和 DocumentDB。

### 浏览集合
三种方式浏览文档：树视图适合嵌套数据，表视图适合快速扫读，BSON 视图保留原始类型。过滤、排序、内联编辑，并可深入嵌套数组和子文档而不丢失上下文。

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="以树、表和 BSON 视图浏览 MongoDB 集合" width="800">
  </a>
</p>

[了解浏览集合 →](https://visualeaf.com/features/browse-collections/)

---

### 聚合管道构建器
通过拖拽式阶段面板设计 MongoDB 聚合管道。添加 `$match`、`$group`、`$lookup`、`$project`、`$unwind` 等阶段，预览每个阶段转换后的数据，并在可视化模式与代码模式之间自由切换。

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="MongoDB 聚合管道构建器，逐阶段预览" width="800">
  </a>
</p>

[了解聚合管道构建器 →](https://visualeaf.com/features/aggregation-pipeline/)

---

### MongoDB 的 SQL 模式
用熟悉的 SQL 查询 MongoDB 集合。VisuaLeaf 会把 `SELECT`、`WHERE`、`GROUP BY` 和 `JOIN` 翻译成对应的 `find()` 查询或聚合管道，让你清楚看到实际执行的是什么。

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="MongoDB 的 SQL 模式，直接对 MongoDB 集合编写 SQL" width="800">
  </a>
</p>

[了解 SQL 模式 →](https://visualeaf.com/features/sql-mode/)

---

### JSON Schema 验证
用树形编辑器设计并实施 MongoDB JSON Schema 验证。完整支持 BSON 类型和验证规则，一键对实时集合进行校验。

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="Schema 构建器，显示带必填字段、BSON 类型和规则的验证器" width="800">
  </a>
</p>

[了解 JSON Schema 验证 →](https://visualeaf.com/features/schema-validation/)

---

### 索引管理器
以可视化方式创建、查看和管理 MongoDB 索引：单字段、复合、文本、TTL、唯一和部分索引。查看索引大小和使用统计，发现缺失或冗余的索引，并安全地删除或重建。

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="MongoDB 索引管理器，含大小与使用统计" width="800">
  </a>
</p>

[了解索引管理器 →](https://visualeaf.com/features/index-manager/)

---

### 集合对比
并排对比 MongoDB 集合，找出结构或数据上的差异。在部署后审计变更，保持开发、预发布和生产环境一致。

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="数据对比画布，将源数据库与目标数据库中的集合和表配对" width="800">
  </a>
</p>

[了解集合对比 →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
在 MongoDB 数据库、集合和环境之间同步、复制和迁移数据。把本地集合迁移到 Atlas，运行带过滤或定时的同步任务，通过变更流实时保持数据同步，并在写入前用试运行预览全部变更。

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="MongoSync 在数据库和环境之间同步 MongoDB 数据" width="800">
  </a>
</p>

[了解 MongoSync →](https://visualeaf.com/features/mongosync/)

---

### GridFS 查看器
浏览、上传、下载和预览存储在 MongoDB GridFS 中的文件，支持拖拽上传、进度跟踪，以及图片、PDF 和文档的内联预览。

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="MongoDB GridFS 查看器，带文件预览" width="800">
  </a>
</p>

[了解 GridFS 查看器 →](https://visualeaf.com/features/gridfs-viewer/)

---

### RBAC 仪表盘
以可视化方式管理用户、角色和权限。查看谁有权访问哪个数据库和集合，审计权限，让团队访问控制井井有条，无需手动编辑角色文档。

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="用户与角色仪表盘，显示用户、角色和会话数量以及快捷操作" width="800">
  </a>
</p>

[了解 RBAC 仪表盘 →](https://visualeaf.com/features/rbac-dashboard/)

---

### 副本集与分片集群
查看副本集拓扑、健康状态和 oplog，执行滚动维护和重新配置，进行副本集感知的备份，并在同一个应用中管理分片集群。

---

## Redis

按模式扫描键空间，用与各值类型匹配的编辑器打开它们，过滤值，在内置 Redis CLI 中操作，并测试 ACL 规则。

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="VisuaLeaf Redis 键浏览器" width="800">
  </a>
</p>

[了解 VisuaLeaf for Redis →](https://visualeaf.com/database/redis/)

---

## 安全与隐私

**你的数据留在本地。** VisuaLeaf 从你的电脑直接连接到数据库。我们绝不会查看、存储或代理你的数据。

- **直接连接**：localhost、MongoDB Atlas、托管云数据库或任何自托管服务器
- **SSH 隧道与 SSL**：通过跳板机安全连接，也可安全连接云端实例
- **可离线使用**：激活后可完全离线工作
- **凭据本地存储**：连接信息在你的电脑上加密保存
- **无查询遥测**：我们不会追踪你查询了什么或访问了哪些数据

---

## 支持的平台

| 平台 | 架构 | 下载 |
|----------|--------------|----------|
| macOS    | Intel 与 Apple Silicon | [下载](https://visualeaf.com/download) |
| Windows  | x64 | [下载](https://visualeaf.com/download) |
| Linux    | x64、AppImage、deb | [下载](https://visualeaf.com/download) |

支持 **MongoDB 4.x–8.x**（Atlas、副本集和分片集群）、**PostgreSQL**、**MySQL**、**MariaDB**、**SQL Server**、**Oracle**、**SQLite**、**Redis**，以及 [30 多种其他数据库](https://visualeaf.com/database)。

---

## 快速开始

1. 从 [visualeaf.com/download](https://visualeaf.com/download) **下载** VisuaLeaf
2. 在 macOS、Windows 或 Linux 上**安装**
3. **连接**到 MongoDB、PostgreSQL、MySQL、SQLite 或任何其他受支持的数据库
4. 用可视化工具**探索**你的数据

---

## 定价

| 方案 | 价格 | 说明 |
|------|-------|-------------|
| **Community** | 免费 | 全部 SQL 功能、最多 3 个已保存的 MongoDB 连接、shell、浏览、索引管理、ER 图 |
| **Basic** | $79 一次性付费 + 1 年更新 | 可视化查询与聚合构建器、Redis、查询剖析器、导入/导出任务、数据脱敏、AI 助手 |
| **Professional** | $149 一次性付费 + 1 年更新 | Basic 的全部功能，外加无限任务、集合对比、MongoSync、RBAC、图表与仪表盘、MCP 服务器、优先支持 |

所有许可证均为永久授权。可先免费试用 **14 天** Professional 功能，无需信用卡。

[查看完整定价 →](https://visualeaf.com/pricing)

---

## 文档

- [入门指南](https://visualeaf.com/docs)
- [连接管理器](https://visualeaf.com/docs/connection-manager)
- [SQL 编辑器](https://visualeaf.com/docs/sql-editor)
- [SQL 查询构建器](https://visualeaf.com/docs/sql-query-builder)
- [MongoDB 可视化查询构建器](https://visualeaf.com/docs/mongo-query)
- [聚合管道](https://visualeaf.com/docs/aggregation)
- [Schema 设计器](https://visualeaf.com/docs/schema-designer)
- [常见问题](https://visualeaf.com/faq)

---

## 联系我们

- 官网：[visualeaf.com](https://visualeaf.com)
- Twitter：[@SozoCode](https://twitter.com/SozoCode)
- 邮箱：[support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn：[SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## 相关项目

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**：开源 MongoDB 查看器（轻量级，只读）

---

<p align="center">
  由 <a href="https://visualeaf.com">SozoCode</a> 用心打造
</p>
