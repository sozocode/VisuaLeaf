<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="VisuaLeaf のロゴ" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — MongoDB と SQL のためのビジュアルデータベース GUI</h1>

<p align="center">
  <strong>クエリを視覚的に組み立て、ER 図を描き、集計パイプラインを設計し、結果をグラフ化。MongoDB、PostgreSQL、MySQL、SQLite をはじめ 30 以上のデータベースを 1 つのワークスペースで。</strong>
</p>

<p align="center">
  macOS、Windows、Linux に対応したモダンな<strong>データベースクライアント</strong>です。データがドキュメント、テーブル、キーのどこにあっても、構文を覚えることなく探索・クエリ・理解できます。
</p>

<p align="center">
  <a href="https://visualeaf.com">Web サイト</a> •
  <a href="https://visualeaf.com/download">ダウンロード</a> •
  <a href="https://visualeaf.com/docs">ドキュメント</a> •
  <a href="https://visualeaf.com/features">機能</a> •
  <a href="https://visualeaf.com/database">対応データベース</a> •
  <a href="https://visualeaf.com/pricing">料金</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="プラットフォーム: macOS、Windows、Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas およびセルフホスト">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL: PostgreSQL、MySQL、SQL Server、SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="36 種類のデータベースに対応">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="ライセンス">
</p>

<p align="center">
  <a href="README.md">English</a> •
  <a href="README.zh-CN.md">简体中文</a> •
  <a href="README.zh-TW.md">繁體中文</a> •
  <strong>日本語</strong> •
  <a href="README.ko.md">한국어</a> •
  <a href="README.es.md">Español</a> •
  <a href="README.pt-BR.md">Português (Brasil)</a> •
  <a href="README.de.md">Deutsch</a> •
  <a href="README.fr.md">Français</a> •
  <a href="README.ru.md">Русский</a> •
  <a href="README.hi.md">हिन्दी</a>
</p>

---

## VisuaLeaf とは

VisuaLeaf は、開発者、DBA、データチームのためのビジュアルな**データベースワークスペース**です。MongoDB GUI として生まれ、現在は **SQL クライアント**としても同じように使えます。MongoDB、PostgreSQL、MySQL、MariaDB、SQL Server、Oracle、SQLite、ClickHouse、Redis などに接続し、どのデータベースでも同じビジュアルなワークフローで作業できます。

クリック操作でクエリを組み立て、外部キーや MongoDB に実際に格納されているデータから ER 図を描き、テーブルやドキュメントをその場で編集し、遅いクエリをプロファイルし、データベース間でデータを移動し、ダッシュボードを構築し、実際のスキーマをもとに AI にクエリの下書きを任せられます。すべてローカルで動作し、データベースに直接接続します。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="MySQL のテーブルを結合し、結果グリッドをリアルタイムに表示する VisuaLeaf のビジュアル SQL クエリビルダー" width="850">
  </a>
</p>

### VisuaLeaf が選ばれる理由

- **MongoDB と SQL を 1 つのアプリで**: ドキュメント、リレーショナル、キーバリュー、分析系まで、36 種類のデータベースを 1 つのワークスペースで扱えます。
- **SQL 機能はすべて無料**で Community Edition（無料版）に含まれます。
- **両方の世界に対応したビジュアルクエリビルダー**: SQL では外部キーから JOIN を提案し、MongoDB では AND/OR グループでフィルターを組み立てられます。
- **ER 図とスキーマの可視化**: SQL の外部キーから生成、または MongoDB のコレクションから推測。キャンバス上の設計を実際のテーブルやコレクションとして作成（マテリアライズ）することもできます。
- **SQL エディターと MongoDB シェル**: シンタックスハイライト、オートコンプリート、履歴に対応し、結果はグリッド、ツリー、JSON で表示できます。
- **ドラッグ＆ドロップの集計パイプラインデザイナー**: 各ステージでプレビューを確認できます。
- **AI アシスタント**: 自然言語からクエリ、集計、グラフを作成し、クエリプランを解説します。
- **MCP サーバーを内蔵**: Claude、Cursor などの AI ツールをデータベースに接続できます。
- **実データでも高速**: 50,000 件のドキュメントを数秒で開き、MongoDB の上限である 16 MB のドキュメントも快適に扱えます。
- **データはローカルに留まります**: 直接接続、プロキシなし、クエリのテレメトリーなし。

---

## 対応データベース

| カテゴリ | データベース |
|----------|-----------|
| **ドキュメント・キーバリュー** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/), [Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/), [Amazon DocumentDB](https://visualeaf.com/database/documentdb/), [Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL と互換 DB** | [PostgreSQL](https://visualeaf.com/database/postgresql/), [Neon](https://visualeaf.com/database/neon/), [Supabase](https://visualeaf.com/database/supabase/), [TimescaleDB](https://visualeaf.com/database/timescaledb/), [Citus](https://visualeaf.com/database/citus/), [Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/), [Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/), [Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/), [CockroachDB](https://visualeaf.com/database/cockroachdb/), [YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL と互換 DB** | [MySQL](https://visualeaf.com/database/mysql/), [MariaDB](https://visualeaf.com/database/mariadb/), [Percona Server](https://visualeaf.com/database/percona/), [TiDB](https://visualeaf.com/database/tidb/), [Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/), [Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **エンタープライズ SQL** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/), [Azure SQL Database](https://visualeaf.com/database/azure-sql/), [Oracle](https://visualeaf.com/database/oracle/), [IBM Db2](https://visualeaf.com/database/db2/), [Firebird](https://visualeaf.com/database/firebird/) |
| **分析・データウェアハウス・ストリーミング** | [ClickHouse](https://visualeaf.com/database/clickhouse/), [Amazon Redshift](https://visualeaf.com/database/amazon-redshift/), [Snowflake](https://visualeaf.com/database/snowflake/), [CrateDB](https://visualeaf.com/database/cratedb/), [QuestDB](https://visualeaf.com/database/questdb/), [RisingWave](https://visualeaf.com/database/risingwave/), [Materialize](https://visualeaf.com/database/materialize/) |
| **ファイルベース・組み込み** | [SQLite](https://visualeaf.com/database/sqlite/), [DuckDB](https://visualeaf.com/database/duckdb/), [H2](https://visualeaf.com/database/h2/), [HSQLDB](https://visualeaf.com/database/hsqldb/), [Apache Derby](https://visualeaf.com/database/derby/) |

[対応データベースの一覧を見る →](https://visualeaf.com/database)

---

## MongoDB と SQL の共通機能

以下のツールは、MongoDB に接続していても SQL データベースに接続していても同じように使えます。

### 接続マネージャー
MongoDB、PostgreSQL、MySQL、SQL Server、SQLite などの接続を 1 か所で管理できます。接続プロファイルを保存し、プロジェクトや環境ごとにグループ化して、データベースを瞬時に切り替えられます。リモートやクラウドのインスタンス向けに SSH トンネルと SSL にも対応しています。

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="環境と接続のプロジェクトツリーを表示する VisuaLeaf の接続マネージャー" width="800">
  </a>
</p>

[接続マネージャーを詳しく見る →](https://visualeaf.com/features/connection-manager/)

---

### ビジュアルクエリビルダー
構文を書かずにクエリを組み立てられます。SQL では、テーブルをキャンバスにドロップすると VisuaLeaf が外部キーから JOIN を提案し、ライブプレビューに SQL を書き出します。MongoDB では、フィールドセレクター、演算子のドロップダウン、AND/OR グループで `find()` フィルターを組み立てられます。細かく制御したいときは、いつでも生の構文に切り替えられます。

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="フィルターグループと結果を表示する MongoDB のビジュアルクエリビルダー" width="800">
  </a>
</p>

[ビジュアルクエリビルダーを詳しく見る →](https://visualeaf.com/features/visual-query-builder/)

---

### ER 図とビジュアルスキーマ
SQL の外部キーから、あるいは MongoDB の各コレクションに実際に格納されているデータから ER 図を生成します。フィールドの型は自動的に推測されます。逆方向にも使えます。キャンバス上でスキーマを設計し、**マテリアライズ**を押すだけで、テーブルやコレクションが作成されます。

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="MySQL の外部キーから生成された ER 図" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="コレクションとリレーションを表示する MongoDB のスキーマ図" width="800">
  </a>
</p>

[ER 図とビジュアルスキーマを詳しく見る →](https://visualeaf.com/features/visual-schema/)

---

### SQL エディターと MongoDB シェル
シンタックスハイライト、オートコンプリート、コマンド履歴を備えたエディターで SQL スクリプトや `mongosh` コマンドを実行し、結果を編集可能なグリッド、ツリー、JSON で表示できます。スクリプトを保存して後から再実行でき、どの結果も読みやすいまま保てます。

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="テーブル管理の隣に結果グリッドを表示する PostgreSQL の SQL エディター" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="テーブル、ツリー、JSON でビジュアルに出力する MongoDB シェル" width="800">
  </a>
</p>

[SQL エディターと MongoDB シェルを詳しく見る →](https://visualeaf.com/features/mongo-shell/)

---

### テーブル管理
SQL テーブルの作成と変更を視覚的に行えます。列、型、デフォルト値、NULL 許可を編集し、主キー・外部キー、インデックス、制約、トリガー、パーティションを管理して、適用前に生成された DDL を確認できます。ビュー、シーケンス、プロシージャ、ユーザーも同じワークスペースから管理できます。

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="PostgreSQL テーブルの列、外部キー、インデックスを表示するテーブル管理画面" width="800">
  </a>
</p>

[テーブル管理のドキュメントを読む →](https://visualeaf.com/docs/sql-table)

---

### クエリプロファイラー
1 万行では速かったクエリも、1,000 万行では極端に遅くなることがあります。プロファイラーは、どのクエリがどれだけコストを生んでいるのか、そしてその理由を、実行プラン、タイミング指標、インデックスの使用状況、問題を解決するインデックスの提案とともに示します。

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="実行時間のタイムラインと、形状ごとにグループ化されたクエリを表示するクエリプロファイラー" width="800">
  </a>
</p>

[クエリプロファイラーを詳しく見る →](https://visualeaf.com/features/query-profiler/)

---

### チャートとダッシュボード
SQL クエリや MongoDB 集計の結果を 20 種類以上のチャートで可視化し、ダッシュボードにピン留めできます。別途 BI ツールを用意する必要はありません。

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="折れ線、ドーナツ、円、ヒートマップ、ファネル、レーダーの各チャートで店舗売上を表示するダッシュボード" width="800">
  </a>
</p>

[チャートとダッシュボードを詳しく見る →](https://visualeaf.com/features/charts-dashboard/)

---

### タスクマネージャー（インポート・エクスポート・マイグレーション）
MongoDB、SQL データベース、ファイル（JSON、CSV、SQL、mongodump）の間でインポート、エクスポート、マイグレーションを実行し、その間も作業を続けられます。フィールドの再マッピングや変換、機密データのマスキング、ジョブのスケジュール実行や連結、各タスクの実行内容を記録した履歴の確認が可能です。

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="左にフォルダー分けされたタスク、右に選択したタスクの詳細を表示するデータ転送画面" width="800">
  </a>
</p>

[タスクマネージャーを詳しく見る →](https://visualeaf.com/features/task-manager/)

---

### 分割パネル表示
コレクション、テーブル、クエリ、ER 図、ダッシュボードを並べて開けます。横や縦に分割し、タブをドラッグして並べ替え、スクロールを同期させれば、データベースや環境をまたいで結果を比較できます。

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="クエリとデータを並べて比較する分割パネル表示" width="800">
  </a>
</p>

[分割パネル表示を詳しく見る →](https://visualeaf.com/features/split-panel-views/)

---

### AI アシスタントと MCP サーバー
やりたいことを説明すると、アシスタントが実際のスキーマに基づいてクエリを書きます。集計の下書き、結果のチャート化、ER 図の生成、データ構造のレビューに加えて、クエリプランを入れ子の JSON ではなく分かりやすい言葉で解説します。内蔵の **MCP サーバー**を使えば、Claude、Cursor などの AI ツールをデータベースに直接接続することもできます。

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="自然言語からデータベースクエリを生成する AI アシスタント" width="800">
  </a>
</p>

[AI アシスタントを詳しく見る →](https://visualeaf.com/features/ai-helper/)

---

## MongoDB 向け機能

VisuaLeaf の原点となったツール群です。MongoDB、Atlas、Cosmos DB、DocumentDB に対応しています。

### コレクションの閲覧
ドキュメントを 3 つの方法で探索できます。入れ子データにはツリービュー、素早く流し読みするにはテーブルビュー、生の型をそのまま確認するには BSON ビュー。フィルター、ソート、インライン編集を行い、コンテキストを失わずに入れ子の配列やサブドキュメントへ掘り下げられます。

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="ツリー、テーブル、BSON の各ビューで MongoDB コレクションを閲覧" width="800">
  </a>
</p>

[コレクションの閲覧を詳しく見る →](https://visualeaf.com/features/browse-collections/)

---

### 集計パイプラインビルダー
ドラッグ＆ドロップのステージパレットで MongoDB の集計パイプラインを設計できます。`$match`、`$group`、`$lookup`、`$project`、`$unwind` などを追加し、各ステージで変換後のデータをプレビューし、ビジュアルモードとコードモードを切り替えられます。

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="ステージごとのプレビューを表示する MongoDB 集計パイプラインビルダー" width="800">
  </a>
</p>

[集計パイプラインビルダーを詳しく見る →](https://visualeaf.com/features/aggregation-pipeline/)

---

### MongoDB 向け SQL モード
使い慣れた SQL で MongoDB のコレクションにクエリを実行できます。VisuaLeaf は `SELECT`、`WHERE`、`GROUP BY`、`JOIN` を、対応する `find()` クエリや集計パイプラインに変換するので、実際に何が実行されるのかを正確に確認できます。

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="MongoDB 向け SQL モードで MongoDB コレクションに対して SQL を記述" width="800">
  </a>
</p>

[SQL モードを詳しく見る →](https://visualeaf.com/features/sql-mode/)

---

### JSON Schema バリデーション
ツリー形式のエディターで MongoDB の JSON Schema バリデーションを設計し、適用できます。BSON 型を完全にサポートし、バリデーションルールを定義して、稼働中のコレクションに対してワンクリックで検証できます。

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="必須フィールド、BSON 型、ルールを含むバリデーターを表示するスキーマビルダー" width="800">
  </a>
</p>

[JSON Schema バリデーションを詳しく見る →](https://visualeaf.com/features/schema-validation/)

---

### インデックスマネージャー
MongoDB のインデックスを視覚的に作成、表示、管理できます。単一フィールド、複合、テキスト、TTL、ユニーク、パーシャルに対応。インデックスのサイズと使用統計を確認し、不足している、あるいは冗長なインデックスを見つけて、安全に削除や再構築ができます。

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="サイズと使用統計を表示する MongoDB インデックスマネージャー" width="800">
  </a>
</p>

[インデックスマネージャーを詳しく見る →](https://visualeaf.com/features/index-manager/)

---

### コレクション比較
MongoDB のコレクションを並べて比較し、構造やデータの差分を見つけられます。デプロイ後の変更を監査し、開発・ステージング・本番環境を揃えた状態に保てます。

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="ソースとターゲットのデータベースでコレクションとテーブルをペアリングするデータ比較キャンバス" width="800">
  </a>
</p>

[コレクション比較を詳しく見る →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
MongoDB のデータベース、コレクション、環境の間でデータを同期、コピー、マイグレーションできます。ローカルのコレクションを Atlas へ移動し、フィルター付きやスケジュール実行の同期ジョブを実行し、チェンジストリームでリアルタイムに同期を保ち、書き込み前にドライランですべてをプレビューできます。

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="データベースと環境の間で MongoDB のデータを同期する MongoSync" width="800">
  </a>
</p>

[MongoSync を詳しく見る →](https://visualeaf.com/features/mongosync/)

---

### GridFS ビューアー
MongoDB GridFS に保存されたファイルの閲覧、アップロード、ダウンロード、プレビューができます。ドラッグ＆ドロップでのアップロード、進捗表示、画像・PDF・ドキュメントのインラインプレビューに対応しています。

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="ファイルプレビューを表示する MongoDB GridFS ビューアー" width="800">
  </a>
</p>

[GridFS ビューアーを詳しく見る →](https://visualeaf.com/features/gridfs-viewer/)

---

### RBAC ダッシュボード
ユーザー、ロール、権限を視覚的に管理できます。誰がどのデータベースやコレクションにアクセスできるかを確認し、権限を監査して、ロールドキュメントを手で編集することなくチームのアクセス権を整理できます。

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="ユーザー数、ロール数、セッション数とクイックアクションを表示するユーザーとロールのダッシュボード" width="800">
  </a>
</p>

[RBAC ダッシュボードを詳しく見る →](https://visualeaf.com/features/rbac-dashboard/)

---

### レプリカセットとシャーディングクラスター
レプリカセットのトポロジー、ヘルス、oplog を確認し、ローリングメンテナンスや再構成を実行し、レプリカセットを考慮したバックアップを取得して、シャーディングクラスターも同じアプリから管理できます。

---

## Redis

パターンでキー空間をスキャンし、各値の型に合ったエディターで開き、値をフィルターし、内蔵の Redis CLI で作業し、ACL ルールをテストできます。

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="VisuaLeaf の Redis キーブラウザー" width="800">
  </a>
</p>

[Redis 向け VisuaLeaf を詳しく見る →](https://visualeaf.com/database/redis/)

---

## セキュリティとプライバシー

**データはローカルに留まります。** VisuaLeaf はお使いのマシンからデータベースへ直接接続します。私たちがお客様のデータを閲覧、保存、中継することは一切ありません。

- **直接接続**: localhost、MongoDB Atlas、マネージドクラウドデータベース、あらゆるセルフホストサーバーに対応
- **SSH トンネルと SSL**: 踏み台ホスト経由やクラウドインスタンスへの安全な接続
- **オフライン対応**: アクティベーション後は完全にオフラインで動作
- **認証情報のローカル保存**: 接続情報はお使いのマシン上で暗号化して保存
- **クエリのテレメトリーなし**: 何をクエリしたか、どのデータにアクセスしたかを追跡しません

---

## 対応プラットフォーム

| プラットフォーム | アーキテクチャ | ダウンロード |
|----------|--------------|----------|
| macOS    | Intel および Apple Silicon | [ダウンロード](https://visualeaf.com/download) |
| Windows  | x64 | [ダウンロード](https://visualeaf.com/download) |
| Linux    | x64、AppImage、deb | [ダウンロード](https://visualeaf.com/download) |

**MongoDB 4.x–8.x**（Atlas、レプリカセット、シャーディングクラスター）、**PostgreSQL**、**MySQL**、**MariaDB**、**SQL Server**、**Oracle**、**SQLite**、**Redis**、および [30 以上のデータベース](https://visualeaf.com/database)に対応しています。

---

## はじめに

1. [visualeaf.com/download](https://visualeaf.com/download) から VisuaLeaf を**ダウンロード**
2. macOS、Windows、または Linux に**インストール**
3. MongoDB、PostgreSQL、MySQL、SQLite、その他の対応データベースに**接続**
4. ビジュアルツールでデータを**探索**

---

## 料金

| プラン | 価格 | 内容 |
|------|-------|-------------|
| **Community** | 無料 | すべての SQL 機能、保存できる MongoDB 接続は 3 つまで、シェル、閲覧、インデックス管理、ER 図 |
| **Basic** | $79 買い切り + 1 年間のアップデート | ビジュアルクエリビルダーと集計ビルダー、Redis、クエリプロファイラー、インポート/エクスポートタスク、データマスキング、AI アシスタント |
| **Professional** | $149 買い切り + 1 年間のアップデート | Basic のすべてに加えて、無制限のタスク、コレクション比較、MongoSync、RBAC、チャートとダッシュボード、MCP サーバー、優先サポート |

すべてのライセンスは永続ライセンスです。まずは Professional の機能を **14 日間無料トライアル**でお試しください。クレジットカードは不要です。

[料金の詳細を見る →](https://visualeaf.com/pricing)

---

## ドキュメント

- [スタートガイド](https://visualeaf.com/docs)
- [接続マネージャー](https://visualeaf.com/docs/connection-manager)
- [SQL エディター](https://visualeaf.com/docs/sql-editor)
- [SQL クエリビルダー](https://visualeaf.com/docs/sql-query-builder)
- [MongoDB ビジュアルクエリビルダー](https://visualeaf.com/docs/mongo-query)
- [集計パイプライン](https://visualeaf.com/docs/aggregation)
- [スキーマデザイナー](https://visualeaf.com/docs/schema-designer)
- [よくある質問](https://visualeaf.com/faq)

---

## お問い合わせ

- Web サイト: [visualeaf.com](https://visualeaf.com)
- Twitter: [@SozoCode](https://twitter.com/SozoCode)
- メール: [support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn: [SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## 関連プロジェクト

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**: オープンソースの MongoDB ビューアー（軽量、読み取り専用）

---

<p align="center">
  <a href="https://visualeaf.com">SozoCode</a> が心を込めて作りました
</p>
