<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="Logo do VisuaLeaf" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — Interface visual de banco de dados para MongoDB e SQL</h1>

<p align="center">
  <strong>Monte consultas visualmente. Desenhe diagramas ER. Projete pipelines de agregação. Transforme seus resultados em gráficos. Um único workspace para MongoDB, PostgreSQL, MySQL, SQLite e mais de 30 outros bancos de dados.</strong>
</p>

<p align="center">
  Um <strong>cliente de banco de dados</strong> moderno para macOS, Windows e Linux. Explore, consulte e entenda seus dados, estejam eles em documentos, tabelas ou chaves, sem precisar decorar sintaxe.
</p>

<p align="center">
  <a href="https://visualeaf.com">Site</a> •
  <a href="https://visualeaf.com/download">Download</a> •
  <a href="https://visualeaf.com/docs">Documentação</a> •
  <a href="https://visualeaf.com/features">Recursos</a> •
  <a href="https://visualeaf.com/database">Bancos de dados</a> •
  <a href="https://visualeaf.com/pricing">Preços</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Plataformas: macOS, Windows, Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas e auto-hospedado">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL: PostgreSQL, MySQL, SQL Server, SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="36 bancos de dados suportados">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="Licença">
</p>

<p align="center">
  <a href="README.md">English</a> •
  <a href="README.zh-CN.md">简体中文</a> •
  <a href="README.zh-TW.md">繁體中文</a> •
  <a href="README.ja.md">日本語</a> •
  <a href="README.ko.md">한국어</a> •
  <a href="README.es.md">Español</a> •
  <strong>Português (Brasil)</strong> •
  <a href="README.de.md">Deutsch</a> •
  <a href="README.fr.md">Français</a> •
  <a href="README.ru.md">Русский</a> •
  <a href="README.hi.md">हिन्दी</a>
</p>

---

## O que é o VisuaLeaf?

O VisuaLeaf é um **workspace visual de banco de dados** para desenvolvedores, DBAs e equipes de dados. Ele nasceu como uma interface gráfica para MongoDB e hoje funciona igualmente bem como **cliente SQL**: conecte-se a MongoDB, PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, SQLite, ClickHouse, Redis e outros, e use o mesmo fluxo de trabalho visual em todos eles.

Monte uma consulta apontando e clicando, desenhe um diagrama ER a partir das suas chaves estrangeiras ou do que o MongoDB realmente armazena, edite tabelas e documentos diretamente na grade, faça o profiling de consultas lentas, mova dados entre bancos, construa dashboards e deixe a IA redigir consultas com base no seu esquema real. Tudo roda localmente e se conecta diretamente aos seus bancos de dados.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="Construtor visual de consultas SQL do VisuaLeaf unindo tabelas MySQL com uma grade de resultados ao vivo" width="850">
  </a>
</p>

### Por que as equipes escolhem o VisuaLeaf

- **Um só app para MongoDB e SQL**: 36 bancos de dados, de documentos, relacionais, chave-valor e analíticos, em um único workspace.
- **Todos os recursos SQL são gratuitos** na Community Edition (edição comunitária).
- **Construtores visuais de consulta para os dois mundos**: SQL com JOINs sugeridos a partir das chaves estrangeiras, filtros MongoDB com grupos AND/OR.
- **Diagramas ER e visualização de esquema**: gerados a partir das chaves estrangeiras SQL ou inferidos das coleções MongoDB, e você pode materializar um projeto em tabelas ou coleções reais.
- **Editor SQL e shell MongoDB**: realce de sintaxe, autocompletar, histórico e resultados em grade, árvore ou JSON.
- **Designer de pipelines de agregação com arrastar e soltar** e pré-visualização em cada estágio.
- **Assistente de IA** que escreve consultas, agregações e gráficos a partir de linguagem natural e explica planos de execução.
- **Servidor MCP integrado**: conecte Claude, Cursor e outras ferramentas de IA aos seus bancos de dados.
- **Rápido com dados reais**: 50.000 documentos abrem em segundos, e documentos no limite de 16 MB do MongoDB são tratados sem dificuldade.
- **Seus dados ficam na sua máquina**: conexões diretas, sem proxy, sem telemetria sobre suas consultas.

---

## Bancos de dados suportados

| Categoria | Bancos de dados |
|----------|-----------|
| **Documentos e chave-valor** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/), [Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/), [Amazon DocumentDB](https://visualeaf.com/database/documentdb/), [Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL e compatíveis** | [PostgreSQL](https://visualeaf.com/database/postgresql/), [Neon](https://visualeaf.com/database/neon/), [Supabase](https://visualeaf.com/database/supabase/), [TimescaleDB](https://visualeaf.com/database/timescaledb/), [Citus](https://visualeaf.com/database/citus/), [Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/), [Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/), [Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/), [CockroachDB](https://visualeaf.com/database/cockroachdb/), [YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL e compatíveis** | [MySQL](https://visualeaf.com/database/mysql/), [MariaDB](https://visualeaf.com/database/mariadb/), [Percona Server](https://visualeaf.com/database/percona/), [TiDB](https://visualeaf.com/database/tidb/), [Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/), [Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **SQL corporativo** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/), [Azure SQL Database](https://visualeaf.com/database/azure-sql/), [Oracle](https://visualeaf.com/database/oracle/), [IBM Db2](https://visualeaf.com/database/db2/), [Firebird](https://visualeaf.com/database/firebird/) |
| **Analytics, data warehouse e streaming** | [ClickHouse](https://visualeaf.com/database/clickhouse/), [Amazon Redshift](https://visualeaf.com/database/amazon-redshift/), [Snowflake](https://visualeaf.com/database/snowflake/), [CrateDB](https://visualeaf.com/database/cratedb/), [QuestDB](https://visualeaf.com/database/questdb/), [RisingWave](https://visualeaf.com/database/risingwave/), [Materialize](https://visualeaf.com/database/materialize/) |
| **Baseados em arquivo e embarcados** | [SQLite](https://visualeaf.com/database/sqlite/), [DuckDB](https://visualeaf.com/database/duckdb/), [H2](https://visualeaf.com/database/h2/), [HSQLDB](https://visualeaf.com/database/hsqldb/), [Apache Derby](https://visualeaf.com/database/derby/) |

[Ver todos os bancos de dados suportados →](https://visualeaf.com/database)

---

## Recursos para MongoDB e SQL

Estas ferramentas funcionam da mesma forma quer você esteja conectado ao MongoDB ou a um banco SQL.

### Gerenciador de Conexões
Mantenha suas conexões MongoDB, PostgreSQL, MySQL, SQL Server, SQLite e outras em um só lugar. Salve perfis de conexão, agrupe-os por projeto ou ambiente e alterne entre bancos instantaneamente, com túnel SSH e SSL para instâncias remotas e na nuvem.

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="Gerenciador de Conexões do VisuaLeaf com uma árvore de projetos contendo ambientes e conexões" width="800">
  </a>
</p>

[Conheça o Gerenciador de Conexões →](https://visualeaf.com/features/connection-manager/)

---

### Construtor Visual de Consultas
Monte consultas sem escrever sintaxe. No SQL, solte tabelas no canvas e o VisuaLeaf sugere JOINs a partir das suas chaves estrangeiras enquanto escreve o SQL em uma pré-visualização ao vivo. No MongoDB, monte filtros `find()` com seletores de campo, menus de operadores e grupos AND/OR. Volte para a sintaxe bruta sempre que quiser retomar o controle.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="Construtor visual de consultas MongoDB com grupos de filtros e resultados" width="800">
  </a>
</p>

[Conheça o Construtor Visual de Consultas →](https://visualeaf.com/features/visual-query-builder/)

---

### Diagramas ER e Esquema Visual
Gere diagramas ER a partir das chaves estrangeiras SQL, ou do que o MongoDB realmente armazena em cada coleção, com os tipos de campo inferidos automaticamente. O caminho inverso também funciona: projete um esquema no canvas, clique em **Materializar** e as tabelas ou coleções são criadas para você.

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="Diagrama ER gerado a partir de chaves estrangeiras do MySQL" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="Diagrama de esquema MongoDB mostrando coleções e relacionamentos" width="800">
  </a>
</p>

[Conheça os Diagramas ER e o Esquema Visual →](https://visualeaf.com/features/visual-schema/)

---

### Editor SQL e Shell MongoDB
Execute scripts SQL ou comandos `mongosh` com realce de sintaxe, autocompletar e histórico de comandos, e veja os resultados como grade editável, árvore ou JSON. Salve scripts, execute-os novamente mais tarde e mantenha todo resultado legível.

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="Editor SQL do PostgreSQL com grade de resultados ao lado do gerenciamento de tabelas" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="Shell MongoDB com saída visual em tabela, árvore e JSON" width="800">
  </a>
</p>

[Conheça o Editor SQL e o Shell MongoDB →](https://visualeaf.com/features/mongo-shell/)

---

### Gerenciamento de Tabelas
Crie e altere tabelas SQL visualmente. Edite colunas, tipos, valores padrão e nulabilidade, gerencie chaves primárias e estrangeiras, índices, constraints, triggers e partições, e confira o DDL gerado antes de aplicá-lo. Views, sequences, procedures e usuários são gerenciados no mesmo workspace.

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="Gerenciamento de tabelas de uma tabela PostgreSQL mostrando colunas, chaves estrangeiras e índices" width="800">
  </a>
</p>

[Leia a documentação de Gerenciamento de Tabelas →](https://visualeaf.com/docs/sql-table)

---

### Profiler de Consultas
Uma consulta rápida em dez mil linhas pode se arrastar em dez milhões. O profiler mostra quais consultas estão custando caro e por quê, com planos de execução, métricas de tempo, uso de índices e sugestões do índice que resolveria o problema.

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="Profiler de Consultas com linha do tempo de execução e consultas agrupadas por formato" width="800">
  </a>
</p>

[Conheça o Profiler de Consultas →](https://visualeaf.com/features/query-profiler/)

---

### Gráficos e Dashboards
Transforme o resultado de uma consulta SQL ou de uma agregação MongoDB em gráficos, com mais de 20 tipos disponíveis, e fixe-os em dashboards. Sem precisar de uma ferramenta de BI separada.

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="Dashboard de vendas de lojas com gráficos de linha, rosca, pizza, mapa de calor, funil e radar" width="800">
  </a>
</p>

[Conheça os Gráficos e Dashboards →](https://visualeaf.com/features/charts-dashboard/)

---

### Gerenciador de Tarefas (Importação, Exportação, Migração)
Execute importações, exportações e migrações entre MongoDB, bancos SQL e arquivos (JSON, CSV, SQL, mongodump) e continue trabalhando enquanto elas rodam. Remapeie e transforme campos, mascare dados sensíveis, agende e encadeie jobs e consulte o histórico completo do que cada tarefa fez.

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="Transferência de Dados com tarefas em pastas à esquerda e os detalhes da tarefa selecionada à direita" width="800">
  </a>
</p>

[Conheça o Gerenciador de Tarefas →](https://visualeaf.com/features/task-manager/)

---

### Painéis Divididos
Abra coleções, tabelas, consultas, diagramas ER e dashboards lado a lado. Divida na horizontal ou na vertical, arraste abas para reorganizar e mantenha a rolagem sincronizada para comparar resultados entre bancos ou ambientes.

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="Painéis divididos comparando consultas e dados lado a lado" width="800">
  </a>
</p>

[Conheça os Painéis Divididos →](https://visualeaf.com/features/split-panel-views/)

---

### Assistente de IA e Servidor MCP
Descreva o que você quer e o assistente escreve a consulta com base no seu esquema real. Ele redige agregações, transforma resultados em gráficos, gera diagramas ER, analisa como seus dados estão estruturados e explica planos de execução em linguagem natural, em vez de JSON aninhado. Com o **servidor MCP** integrado, você também pode conectar Claude, Cursor e outras ferramentas de IA diretamente aos seus bancos de dados.

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="Assistente de IA gerando consultas de banco de dados a partir de linguagem natural" width="800">
  </a>
</p>

[Conheça o Assistente de IA →](https://visualeaf.com/features/ai-helper/)

---

## Recursos para MongoDB

As ferramentas sobre as quais o VisuaLeaf foi construído, para MongoDB, Atlas, Cosmos DB e DocumentDB.

### Navegação em Coleções
Explore documentos de três maneiras: visão em árvore para dados aninhados, visão em tabela para varredura rápida e visão BSON para fidelidade total aos tipos. Filtre, ordene e edite diretamente na tela, e depois mergulhe em arrays e subdocumentos aninhados sem perder o contexto.

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="Navegação em coleções MongoDB nas visões de árvore, tabela e BSON" width="800">
  </a>
</p>

[Conheça a Navegação em Coleções →](https://visualeaf.com/features/browse-collections/)

---

### Construtor de Pipelines de Agregação
Projete pipelines de agregação do MongoDB com uma paleta de estágios de arrastar e soltar. Adicione `$match`, `$group`, `$lookup`, `$project`, `$unwind` e outros, pré-visualize os dados transformados em cada estágio e alterne entre os modos visual e código.

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="Construtor de pipelines de agregação do MongoDB com pré-visualização estágio a estágio" width="800">
  </a>
</p>

[Conheça o Construtor de Pipelines de Agregação →](https://visualeaf.com/features/aggregation-pipeline/)

---

### Modo SQL para MongoDB
Consulte coleções MongoDB com o SQL que você já conhece. O VisuaLeaf traduz `SELECT`, `WHERE`, `GROUP BY` e `JOIN` para a consulta `find()` ou o pipeline de agregação correspondente, para que você veja exatamente o que é executado.

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="Modo SQL para MongoDB, escrevendo SQL contra coleções MongoDB" width="800">
  </a>
</p>

[Conheça o Modo SQL →](https://visualeaf.com/features/sql-mode/)

---

### Validação com JSON Schema
Projete e aplique validação JSON Schema no MongoDB com um editor em árvore. Suporte completo aos tipos BSON, regras de validação e verificação com um clique contra coleções ao vivo.

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="Construtor de Esquema mostrando um validador com campos obrigatórios, tipos BSON e regras" width="800">
  </a>
</p>

[Conheça a Validação com JSON Schema →](https://visualeaf.com/features/schema-validation/)

---

### Gerenciador de Índices
Crie, visualize e gerencie índices do MongoDB visualmente: de campo único, compostos, de texto, TTL, únicos e parciais. Consulte estatísticas de tamanho e uso, identifique índices ausentes ou redundantes e remova-os ou reconstrua-os com segurança.

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="Gerenciador de índices do MongoDB com estatísticas de tamanho e uso" width="800">
  </a>
</p>

[Conheça o Gerenciador de Índices →](https://visualeaf.com/features/index-manager/)

---

### Comparação de Coleções
Compare coleções MongoDB lado a lado para identificar diferenças de estrutura ou de dados. Audite mudanças depois de um deploy e mantenha dev, staging e produção alinhados.

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="Canvas de Comparação de Dados pareando coleções e tabelas entre um banco de origem e um de destino" width="800">
  </a>
</p>

[Conheça a Comparação de Coleções →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
Sincronize, copie e migre dados entre bancos, coleções e ambientes MongoDB. Mova uma coleção local para o Atlas, execute jobs de sincronização filtrados ou agendados, mantenha os dados sincronizados em tempo real com change streams e pré-visualize tudo com um dry run antes de gravar.

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="MongoSync sincronizando dados MongoDB entre bancos e ambientes" width="800">
  </a>
</p>

[Conheça o MongoSync →](https://visualeaf.com/features/mongosync/)

---

### Visualizador GridFS
Navegue, envie, baixe e pré-visualize arquivos armazenados no GridFS do MongoDB, com upload por arrastar e soltar, acompanhamento de progresso e pré-visualização embutida de imagens, PDFs e documentos.

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="Visualizador GridFS do MongoDB com pré-visualização de arquivos" width="800">
  </a>
</p>

[Conheça o Visualizador GridFS →](https://visualeaf.com/features/gridfs-viewer/)

---

### Dashboard de RBAC
Gerencie usuários, papéis e permissões visualmente. Veja quem tem acesso a qual banco e coleção, audite privilégios e mantenha o acesso da equipe organizado sem editar documentos de papéis à mão.

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="Dashboard de Usuários e Papéis com contagens de usuários, papéis e sessões e ações rápidas" width="800">
  </a>
</p>

[Conheça o Dashboard de RBAC →](https://visualeaf.com/features/rbac-dashboard/)

---

### Replica Sets e Clusters Shardeados
Veja a topologia, a saúde e o oplog do replica set, execute manutenções e reconfigurações em rolling, faça backups que respeitam o replica set e gerencie clusters shardeados a partir do mesmo app.

---

## Redis

Varra o keyspace por padrão, abra cada tipo de valor no editor adequado, filtre valores, trabalhe no CLI Redis integrado e teste regras de ACL.

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="Navegador de chaves Redis do VisuaLeaf" width="800">
  </a>
</p>

[Conheça o VisuaLeaf para Redis →](https://visualeaf.com/database/redis/)

---

## Segurança e Privacidade

**Seus dados ficam na sua máquina.** O VisuaLeaf se conecta diretamente do seu computador aos seus bancos de dados. Nunca vemos, armazenamos nem intermediamos seus dados.

- **Conexões diretas**: localhost, MongoDB Atlas, bancos gerenciados na nuvem ou qualquer servidor auto-hospedado
- **Túnel SSH e SSL**: conexões seguras através de bastion hosts e com instâncias na nuvem
- **Funciona offline**: totalmente operacional sem internet após a ativação
- **Credenciais armazenadas localmente**: dados de conexão criptografados na sua máquina
- **Sem telemetria de consultas**: não rastreamos o que você consulta nem quais dados você acessa

---

## Plataformas suportadas

| Plataforma | Arquitetura | Download |
|----------|--------------|----------|
| macOS    | Intel e Apple Silicon | [Download](https://visualeaf.com/download) |
| Windows  | x64 | [Download](https://visualeaf.com/download) |
| Linux    | x64, AppImage, deb | [Download](https://visualeaf.com/download) |

Funciona com **MongoDB 4.x–8.x** (Atlas, replica sets e clusters shardeados), **PostgreSQL**, **MySQL**, **MariaDB**, **SQL Server**, **Oracle**, **SQLite**, **Redis** e [mais de 30 outros bancos de dados](https://visualeaf.com/database).

---

## Primeiros passos

1. **Baixe** o VisuaLeaf em [visualeaf.com/download](https://visualeaf.com/download)
2. **Instale** no macOS, Windows ou Linux
3. **Conecte-se** ao MongoDB, PostgreSQL, MySQL, SQLite ou a qualquer outro banco suportado
4. **Explore** seus dados com as ferramentas visuais

---

## Preços

| Plano | Preço | Descrição |
|------|-------|-------------|
| **Community** | Gratuito | Todos os recursos SQL, até 3 conexões MongoDB salvas, shell, navegação, gerenciamento de índices, diagramas ER |
| **Basic** | US$ 79 pagamento único + 1 ano de atualizações | Construtores visuais de consulta e agregação, Redis, profiler de consultas, tarefas de importação/exportação, mascaramento de dados, assistente de IA |
| **Professional** | US$ 149 pagamento único + 1 ano de atualizações | Tudo do Basic mais tarefas ilimitadas, comparação de coleções, MongoSync, RBAC, gráficos e dashboards, servidor MCP, suporte prioritário |

Toda licença é perpétua. Comece com um **teste gratuito de 14 dias** dos recursos Professional, sem precisar de cartão de crédito.

[Ver preços completos →](https://visualeaf.com/pricing)

---

## Documentação

- [Guia de primeiros passos](https://visualeaf.com/docs)
- [Gerenciador de Conexões](https://visualeaf.com/docs/connection-manager)
- [Editor SQL](https://visualeaf.com/docs/sql-editor)
- [Construtor de Consultas SQL](https://visualeaf.com/docs/sql-query-builder)
- [Construtor Visual de Consultas MongoDB](https://visualeaf.com/docs/mongo-query)
- [Pipeline de Agregação](https://visualeaf.com/docs/aggregation)
- [Designer de Esquemas](https://visualeaf.com/docs/schema-designer)
- [Perguntas frequentes](https://visualeaf.com/faq)

---

## Fale conosco

- Site: [visualeaf.com](https://visualeaf.com)
- Twitter: [@SozoCode](https://twitter.com/SozoCode)
- E-mail: [support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn: [SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## Projetos relacionados

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**: visualizador MongoDB de código aberto (leve, somente leitura)

---

<p align="center">
  Feito com carinho por <a href="https://visualeaf.com">SozoCode</a>
</p>
