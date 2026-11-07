<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="VisuaLeaf 標誌" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — MongoDB 與 SQL 的視覺化資料庫 GUI</h1>

<p align="center">
  <strong>以視覺化方式建立查詢、繪製 ER 圖、設計聚合管線、把結果繪製成圖表。一個工作區，搞定 MongoDB、PostgreSQL、MySQL、SQLite 等 30 多種資料庫。</strong>
</p>

<p align="center">
  一款支援 macOS、Windows 與 Linux 的現代化<strong>資料庫用戶端</strong>。不必死記語法，就能探索、查詢並理解你的資料，無論它存放在文件、資料表還是鍵值中。
</p>

<p align="center">
  <a href="https://visualeaf.com">官方網站</a> •
  <a href="https://visualeaf.com/download">下載</a> •
  <a href="https://visualeaf.com/docs">文件</a> •
  <a href="https://visualeaf.com/features">功能</a> •
  <a href="https://visualeaf.com/database">資料庫</a> •
  <a href="https://visualeaf.com/pricing">價格</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Platform: macOS, Windows, Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas and self-hosted">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL: PostgreSQL, MySQL, SQL Server, SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="36 supported databases">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="License">
</p>

<p align="center">
  <a href="README.md">English</a> •
  <a href="README.zh-CN.md">简体中文</a> •
  <strong>繁體中文</strong> •
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

## VisuaLeaf 是什麼？

VisuaLeaf 是一款為開發者、DBA 與資料團隊打造的視覺化**資料庫工作區**。它最初是一款 MongoDB GUI，如今作為 **SQL 用戶端**同樣得心應手：連線到 MongoDB、PostgreSQL、MySQL、MariaDB、SQL Server、Oracle、SQLite、ClickHouse、Redis 等資料庫，並在每一種資料庫上使用相同的視覺化工作流程。

用點選的方式建立查詢、依外鍵或 MongoDB 實際儲存的內容繪製 ER 圖、直接在資料表與文件中就地編輯、剖析慢查詢、在資料庫之間搬移資料、建立儀表板，並讓 AI 依你的真實結構描述草擬查詢。一切都在本機執行，並直接連線到你的資料庫。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="VisuaLeaf 視覺化 SQL 查詢建構器，正在聯結 MySQL 資料表並即時顯示結果格線" width="850">
  </a>
</p>

### 為什麼團隊選擇 VisuaLeaf

- **MongoDB 與 SQL 共用同一款應用程式**：36 種資料庫，涵蓋文件、關聯式、鍵值與分析型，全在同一個工作區。
- **所有 SQL 功能在 Community Edition（社群版）中完全免費**。
- **兩個世界都有視覺化查詢建構器**：SQL 會依外鍵建議 JOIN，MongoDB 篩選條件支援 AND/OR 群組。
- **ER 圖與結構描述視覺化**：可由 SQL 外鍵產生，或從 MongoDB 集合推斷而來，還能把設計具現化成真正的資料表或集合。
- **SQL 編輯器與 MongoDB shell**：語法標示、自動完成、歷史紀錄，結果可用格線、樹狀或 JSON 檢視。
- **拖放式聚合管線設計器**，每個階段都能預覽。
- **AI 助理**，用白話文就能寫出查詢、聚合與圖表，並解釋查詢計畫。
- **內建 MCP 伺服器**：讓 Claude、Cursor 與其他 AI 工具連上你的資料庫。
- **處理真實資料也夠快**：50,000 筆文件幾秒內開啟，達到 MongoDB 16 MB 上限的文件也能從容處理。
- **資料留在本機**：直接連線，沒有代理伺服器，也不會對你的查詢做遙測。

---

## 支援的資料庫

| 類別 | 資料庫 |
|----------|-----------|
| **文件與鍵值** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/), [Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/), [Amazon DocumentDB](https://visualeaf.com/database/documentdb/), [Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL 與相容資料庫** | [PostgreSQL](https://visualeaf.com/database/postgresql/), [Neon](https://visualeaf.com/database/neon/), [Supabase](https://visualeaf.com/database/supabase/), [TimescaleDB](https://visualeaf.com/database/timescaledb/), [Citus](https://visualeaf.com/database/citus/), [Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/), [Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/), [Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/), [CockroachDB](https://visualeaf.com/database/cockroachdb/), [YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL 與相容資料庫** | [MySQL](https://visualeaf.com/database/mysql/), [MariaDB](https://visualeaf.com/database/mariadb/), [Percona Server](https://visualeaf.com/database/percona/), [TiDB](https://visualeaf.com/database/tidb/), [Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/), [Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **企業級 SQL** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/), [Azure SQL Database](https://visualeaf.com/database/azure-sql/), [Oracle](https://visualeaf.com/database/oracle/), [IBM Db2](https://visualeaf.com/database/db2/), [Firebird](https://visualeaf.com/database/firebird/) |
| **分析、資料倉儲與串流** | [ClickHouse](https://visualeaf.com/database/clickhouse/), [Amazon Redshift](https://visualeaf.com/database/amazon-redshift/), [Snowflake](https://visualeaf.com/database/snowflake/), [CrateDB](https://visualeaf.com/database/cratedb/), [QuestDB](https://visualeaf.com/database/questdb/), [RisingWave](https://visualeaf.com/database/risingwave/), [Materialize](https://visualeaf.com/database/materialize/) |
| **檔案型與嵌入式** | [SQLite](https://visualeaf.com/database/sqlite/), [DuckDB](https://visualeaf.com/database/duckdb/), [H2](https://visualeaf.com/database/h2/), [HSQLDB](https://visualeaf.com/database/hsqldb/), [Apache Derby](https://visualeaf.com/database/derby/) |

[查看所有支援的資料庫 →](https://visualeaf.com/database)

---

## MongoDB 與 SQL 共通功能

無論你連線的是 MongoDB 還是 SQL 資料庫，這些工具的用法都一樣。

### 連線管理員
將 MongoDB、PostgreSQL、MySQL、SQL Server、SQLite 及其他連線集中在一處。儲存連線設定檔、依專案或環境分組，並在資料庫之間即時切換；遠端與雲端執行個體則可透過 SSH 通道與 SSL 連線。

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="VisuaLeaf 連線管理員，以專案樹狀結構呈現環境與連線" width="800">
  </a>
</p>

[探索連線管理員 →](https://visualeaf.com/features/connection-manager/)

---

### 視覺化查詢建構器
不必撰寫語法就能建立查詢。SQL 方面，把資料表拖到畫布上，VisuaLeaf 會依外鍵建議 JOIN，同時在即時預覽中寫出 SQL。MongoDB 方面，可用欄位選擇器、運算子下拉選單與 AND/OR 群組組合 `find()` 篩選條件。想要自己掌控時，隨時可以切回原始語法。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="視覺化 MongoDB 查詢建構器，含篩選群組與結果" width="800">
  </a>
</p>

[探索視覺化查詢建構器 →](https://visualeaf.com/features/visual-query-builder/)

---

### ER 圖與視覺化結構描述
由 SQL 外鍵產生 ER 圖，或依 MongoDB 各集合實際儲存的內容產生，欄位型別會自動推斷。反過來也行：在畫布上設計結構描述，按下**具現化（Materialize）**，資料表或集合就會自動建立。

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="由 MySQL 外鍵產生的 ER 圖" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="顯示集合與關聯的 MongoDB 結構描述圖" width="800">
  </a>
</p>

[探索 ER 圖與視覺化結構描述 →](https://visualeaf.com/features/visual-schema/)

---

### SQL 編輯器與 MongoDB Shell
執行 SQL 指令碼或 `mongosh` 指令，具備語法標示、自動完成與指令歷史紀錄，結果可用可編輯的格線、樹狀或 JSON 檢視。儲存指令碼、日後再次執行，並讓每一份結果都清楚易讀。

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="PostgreSQL SQL 編輯器，結果格線旁是資料表管理" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="MongoDB shell，以表格、樹狀與 JSON 視覺化輸出" width="800">
  </a>
</p>

[探索 SQL 編輯器與 MongoDB Shell →](https://visualeaf.com/features/mongo-shell/)

---

### 資料表管理
以視覺化方式建立與修改 SQL 資料表。編輯欄位、型別、預設值與可否為 NULL，管理主鍵與外鍵、索引、約束、觸發器與分割區，並在套用前檢查產生的 DDL。檢視表、序列、預存程序與使用者也在同一個工作區中管理。

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="PostgreSQL 資料表的資料表管理畫面，顯示欄位、外鍵與索引" width="800">
  </a>
</p>

[閱讀資料表管理文件 →](https://visualeaf.com/docs/sql-table)

---

### 查詢剖析器
在一萬筆資料上飛快的查詢，到了一千萬筆可能慢得像在爬。剖析器會告訴你哪些查詢在消耗資源、原因是什麼，並提供執行計畫、時間指標、索引使用情況，以及能解決問題的索引建議。

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="查詢剖析器，含執行時間時間軸與依查詢形狀分組的查詢" width="800">
  </a>
</p>

[探索查詢剖析器 →](https://visualeaf.com/features/query-profiler/)

---

### 圖表與儀表板
用 20 多種圖表類型將 SQL 查詢或 MongoDB 聚合的結果繪製成圖表，再釘選到儀表板上。不需要另外的 BI 工具。

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="門市銷售儀表板，含折線圖、環圈圖、圓餅圖、熱度圖、漏斗圖與雷達圖" width="800">
  </a>
</p>

[探索圖表與儀表板 →](https://visualeaf.com/features/charts-dashboard/)

---

### 任務管理員（匯入、匯出、遷移）
在 MongoDB、SQL 資料庫與檔案（JSON、CSV、SQL、mongodump）之間執行匯入、匯出與遷移，執行期間可繼續工作。重新對應與轉換欄位、遮罩敏感資料、排程並串接任務，還能查看每個任務完整的執行歷史。

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="資料傳輸畫面，左側是依資料夾整理的任務，右側是所選任務的詳細資訊" width="800">
  </a>
</p>

[探索任務管理員 →](https://visualeaf.com/features/task-manager/)

---

### 分割面板檢視
將集合、資料表、查詢、ER 圖與儀表板並排開啟。水平或垂直分割、拖曳分頁重新排列，並保持同步捲動，方便跨資料庫或跨環境比較結果。

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="分割面板檢視，並排比較查詢與資料" width="800">
  </a>
</p>

[探索分割面板檢視 →](https://visualeaf.com/features/split-panel-views/)

---

### AI 助理與 MCP 伺服器
描述你想要的結果，助理就會依你的真實結構描述寫出查詢。它能草擬聚合、把結果轉成圖表、產生 ER 圖、檢視你的資料結構，並用白話文而不是層層巢狀的 JSON 來解釋查詢計畫。透過內建的 **MCP 伺服器**，你還能讓 Claude、Cursor 與其他 AI 工具直接連上你的資料庫。

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="AI 助理依自然語言產生資料庫查詢" width="800">
  </a>
</p>

[探索 AI 助理 →](https://visualeaf.com/features/ai-helper/)

---

## MongoDB 功能

VisuaLeaf 賴以起家的工具，適用於 MongoDB、Atlas、Cosmos DB 與 DocumentDB。

### 瀏覽集合
用三種方式探索文件：樹狀檢視適合巢狀資料，表格檢視適合快速掃視，BSON 檢視則完整保留原始型別。篩選、排序、就地編輯，再深入巢狀陣列與子文件，而不會失去上下文。

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="以樹狀、表格與 BSON 檢視瀏覽 MongoDB 集合" width="800">
  </a>
</p>

[探索瀏覽集合 →](https://visualeaf.com/features/browse-collections/)

---

### 聚合管線建構器
透過拖放式階段面板設計 MongoDB 聚合管線。加入 `$match`、`$group`、`$lookup`、`$project`、`$unwind` 等階段，在每個階段預覽轉換後的資料，並在視覺化與程式碼模式之間切換。

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="MongoDB 聚合管線建構器，逐階段預覽" width="800">
  </a>
</p>

[探索聚合管線建構器 →](https://visualeaf.com/features/aggregation-pipeline/)

---

### MongoDB 的 SQL 模式
用熟悉的 SQL 查詢 MongoDB 集合。VisuaLeaf 會將 `SELECT`、`WHERE`、`GROUP BY` 與 `JOIN` 轉譯成對應的 `find()` 查詢或聚合管線，讓你清楚看到實際執行的內容。

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="MongoDB 的 SQL 模式，直接以 SQL 查詢 MongoDB 集合" width="800">
  </a>
</p>

[探索 SQL 模式 →](https://visualeaf.com/features/sql-mode/)

---

### JSON Schema 驗證
以樹狀編輯器設計並強制套用 MongoDB JSON Schema 驗證。完整支援 BSON 型別與驗證規則，並可一鍵對即時集合進行驗證。

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="Schema 建構器，顯示含必填欄位、BSON 型別與規則的驗證器" width="800">
  </a>
</p>

[探索 JSON Schema 驗證 →](https://visualeaf.com/features/schema-validation/)

---

### 索引管理員
以視覺化方式建立、檢視與管理 MongoDB 索引：單一欄位、複合、文字、TTL、唯一與部分索引。檢視索引大小與使用統計、找出缺少或多餘的索引，並安全地刪除或重建。

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="MongoDB 索引管理員，含大小與使用統計" width="800">
  </a>
</p>

[探索索引管理員 →](https://visualeaf.com/features/index-manager/)

---

### 集合比對
並排比對 MongoDB 集合，找出結構或資料上的差異。部署後稽核變更，讓開發、預備與正式環境保持一致。

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="資料比對畫布，將來源與目標資料庫中的集合與資料表配對" width="800">
  </a>
</p>

[探索集合比對 →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
在 MongoDB 資料庫、集合與環境之間同步、複製與遷移資料。把本機集合搬到 Atlas、執行篩選式或排程式同步任務、透過變更串流（change streams）即時保持資料同步，並在寫入前以試執行（dry run）預覽所有內容。

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="MongoSync 在資料庫與環境之間同步 MongoDB 資料" width="800">
  </a>
</p>

[探索 MongoSync →](https://visualeaf.com/features/mongosync/)

---

### GridFS 檢視器
瀏覽、上傳、下載並預覽儲存在 MongoDB GridFS 中的檔案，支援拖放上傳、進度追蹤，以及圖片、PDF 與文件的內嵌預覽。

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="MongoDB GridFS 檢視器，含檔案預覽" width="800">
  </a>
</p>

[探索 GridFS 檢視器 →](https://visualeaf.com/features/gridfs-viewer/)

---

### RBAC 儀表板
以視覺化方式管理使用者、角色與權限。檢視誰能存取哪個資料庫與集合、稽核權限，不必手動編輯角色文件就能讓團隊存取權保持井然有序。

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="使用者與角色儀表板，顯示使用者、角色與工作階段數量及快速操作" width="800">
  </a>
</p>

[探索 RBAC 儀表板 →](https://visualeaf.com/features/rbac-dashboard/)

---

### 複本集與分片叢集
查看複本集拓樸、健康狀態與 oplog，執行滾動維護與重新設定，進行支援複本集的備份，並在同一款應用程式中管理分片叢集。

---

## Redis

依模式掃描鍵空間、用最適合的編輯器開啟每種值型別、篩選值、在內建的 Redis CLI 中操作，並測試 ACL 規則。

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="VisuaLeaf Redis 鍵瀏覽器" width="800">
  </a>
</p>

[探索 VisuaLeaf 的 Redis 功能 →](https://visualeaf.com/database/redis/)

---

## 安全與隱私

**你的資料留在本機。** VisuaLeaf 從你的電腦直接連線到你的資料庫。我們絕不會看到、儲存或代理你的資料。

- **直接連線**：localhost、MongoDB Atlas、受管雲端資料庫，或任何自架伺服器
- **SSH 通道與 SSL**：透過跳板主機及連往雲端執行個體的安全連線
- **可離線使用**：啟用後可完全離線運作
- **憑證儲存在本機**：連線資訊在你的電腦上加密儲存
- **不做查詢遙測**：我們不會追蹤你查詢了什麼或存取了哪些資料

---

## 支援的平台

| 平台 | 架構 | 下載 |
|----------|--------------|----------|
| macOS    | Intel 與 Apple Silicon | [下載](https://visualeaf.com/download) |
| Windows  | x64 | [下載](https://visualeaf.com/download) |
| Linux    | x64、AppImage、deb | [下載](https://visualeaf.com/download) |

支援 **MongoDB 4.x–8.x**（Atlas、複本集與分片叢集）、**PostgreSQL**、**MySQL**、**MariaDB**、**SQL Server**、**Oracle**、**SQLite**、**Redis**，以及[其他 30 多種資料庫](https://visualeaf.com/database)。

---

## 快速開始

1. 從 [visualeaf.com/download](https://visualeaf.com/download) **下載** VisuaLeaf
2. 在 macOS、Windows 或 Linux 上**安裝**
3. **連線**到 MongoDB、PostgreSQL、MySQL、SQLite 或任何其他支援的資料庫
4. 用視覺化工具**探索**你的資料

---

## 價格

| 方案 | 價格 | 說明 |
|------|-------|-------------|
| **Community** | 免費 | 所有 SQL 功能、最多 3 個已儲存的 MongoDB 連線、shell、瀏覽、索引管理、ER 圖 |
| **Basic** | $79 一次性付費 + 1 年更新 | 視覺化查詢與聚合建構器、Redis、查詢剖析器、匯入/匯出任務、資料遮罩、AI 助理 |
| **Professional** | $149 一次性付費 + 1 年更新 | Basic 的所有功能，再加上無限任務、集合比對、MongoSync、RBAC、圖表與儀表板、MCP 伺服器、優先支援 |

所有授權皆為永久授權。可先以 **14 天免費試用**體驗 Professional 功能，無需信用卡。

[查看完整價格 →](https://visualeaf.com/pricing)

---

## 文件

- [入門指南](https://visualeaf.com/docs)
- [連線管理員](https://visualeaf.com/docs/connection-manager)
- [SQL 編輯器](https://visualeaf.com/docs/sql-editor)
- [SQL 查詢建構器](https://visualeaf.com/docs/sql-query-builder)
- [MongoDB 視覺化查詢建構器](https://visualeaf.com/docs/mongo-query)
- [聚合管線](https://visualeaf.com/docs/aggregation)
- [結構描述設計器](https://visualeaf.com/docs/schema-designer)
- [常見問題](https://visualeaf.com/faq)

---

## 與我們聯繫

- 官方網站：[visualeaf.com](https://visualeaf.com)
- Twitter：[@SozoCode](https://twitter.com/SozoCode)
- 電子郵件：[support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn：[SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## 相關專案

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**：開放原始碼的 MongoDB 檢視器（輕量、唯讀）

---

<p align="center">
  由 <a href="https://visualeaf.com">SozoCode</a> 用心打造
</p>
