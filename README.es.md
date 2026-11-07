<p align="center">
  <img src="https://visualeaf.com/assets/favicon.svg" alt="Logotipo de VisuaLeaf" width="80" height="80">
</p>

<h1 align="center">VisuaLeaf — Cliente visual de bases de datos para MongoDB y SQL</h1>

<p align="center">
  <strong>Construye consultas de forma visual. Dibuja diagramas ER. Diseña pipelines de agregación. Grafica tus resultados. Un solo espacio de trabajo para MongoDB, PostgreSQL, MySQL, SQLite y más de 30 bases de datos adicionales.</strong>
</p>

<p align="center">
  Un <strong>cliente de bases de datos</strong> moderno para macOS, Windows y Linux. Explora, consulta y entiende tus datos, ya vivan en documentos, tablas o claves, sin memorizar sintaxis.
</p>

<p align="center">
  <a href="https://visualeaf.com">Sitio web</a> •
  <a href="https://visualeaf.com/download">Descargar</a> •
  <a href="https://visualeaf.com/docs">Documentación</a> •
  <a href="https://visualeaf.com/features">Funcionalidades</a> •
  <a href="https://visualeaf.com/database">Bases de datos</a> •
  <a href="https://visualeaf.com/pricing">Precios</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Plataformas: macOS, Windows, Linux">
  <img src="https://img.shields.io/badge/MongoDB-Atlas%20%7C%20Self--Hosted-13aa52" alt="MongoDB: Atlas y autoalojado">
  <img src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server%20%7C%20SQLite-336791" alt="SQL: PostgreSQL, MySQL, SQL Server, SQLite">
  <img src="https://img.shields.io/badge/Databases-36-orange" alt="36 bases de datos compatibles">
  <img src="https://img.shields.io/badge/License-Proprietary-green" alt="Licencia">
</p>

<p align="center">
  <a href="README.md">English</a> •
  <a href="README.zh-CN.md">简体中文</a> •
  <a href="README.zh-TW.md">繁體中文</a> •
  <a href="README.ja.md">日本語</a> •
  <a href="README.ko.md">한국어</a> •
  <strong>Español</strong> •
  <a href="README.pt-BR.md">Português (Brasil)</a> •
  <a href="README.de.md">Deutsch</a> •
  <a href="README.fr.md">Français</a> •
  <a href="README.ru.md">Русский</a> •
  <a href="README.hi.md">हिन्दी</a>
</p>

---

## ¿Qué es VisuaLeaf?

VisuaLeaf es un **espacio de trabajo visual para bases de datos** pensado para desarrolladores, DBAs y equipos de datos. Nació como una GUI para MongoDB y hoy funciona igual de bien como **cliente SQL**: conéctate a MongoDB, PostgreSQL, MySQL, MariaDB, SQL Server, Oracle, SQLite, ClickHouse, Redis y más, y usa el mismo flujo de trabajo visual en todas ellas.

Construye una consulta con clics, dibuja un diagrama ER a partir de tus claves foráneas o de lo que MongoDB almacena realmente, edita tablas y documentos en línea, perfila consultas lentas, mueve datos entre bases de datos, arma dashboards y deja que la IA redacte consultas sobre tu esquema real. Todo se ejecuta en local y se conecta directamente a tus bases de datos.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://visualeaf.com/assets/hero/sql-visual-query-builder-1800w.webp" alt="Constructor visual de consultas SQL de VisuaLeaf uniendo tablas de MySQL con una cuadrícula de resultados en vivo" width="850">
  </a>
</p>

### Por qué los equipos eligen VisuaLeaf

- **Una sola app para MongoDB y SQL**: 36 bases de datos, documentales, relacionales, clave-valor y analíticas, en un único espacio de trabajo.
- **Todas las funcionalidades SQL son gratuitas** en la Community Edition (edición comunitaria).
- **Constructores visuales de consultas para ambos mundos**: SQL con JOINs sugeridos a partir de las claves foráneas, filtros de MongoDB con grupos AND/OR.
- **Diagramas ER y visualización de esquemas**: generados desde claves foráneas SQL o inferidos de colecciones de MongoDB, y puedes materializar un diseño en tablas o colecciones reales.
- **Editor SQL y shell de MongoDB**: resaltado de sintaxis, autocompletado, historial y resultados en cuadrícula, árbol o JSON.
- **Diseñador de pipelines de agregación con arrastrar y soltar** y vista previa en cada etapa.
- **Asistente de IA** que escribe consultas, agregaciones y gráficos a partir de lenguaje natural y explica los planes de ejecución.
- **Servidor MCP integrado**: conecta Claude, Cursor y otras herramientas de IA a tus bases de datos.
- **Rápido con datos reales**: 50 000 documentos se abren en segundos, y los documentos que rozan el límite de 16 MB de MongoDB se manejan sin problema.
- **Tus datos se quedan en local**: conexiones directas, sin proxy y sin telemetría sobre tus consultas.

---

## Bases de datos compatibles

| Categoría | Bases de datos |
|----------|-----------|
| **Documentales y clave-valor** | [MongoDB](https://visualeaf.com/database/mongodb-gui-tool/), [Azure Cosmos DB](https://visualeaf.com/database/cosmosdb/), [Amazon DocumentDB](https://visualeaf.com/database/documentdb/), [Redis](https://visualeaf.com/database/redis/) |
| **PostgreSQL y compatibles** | [PostgreSQL](https://visualeaf.com/database/postgresql/), [Neon](https://visualeaf.com/database/neon/), [Supabase](https://visualeaf.com/database/supabase/), [TimescaleDB](https://visualeaf.com/database/timescaledb/), [Citus](https://visualeaf.com/database/citus/), [Azure Database for PostgreSQL](https://visualeaf.com/database/azure-postgresql/), [Amazon RDS for PostgreSQL](https://visualeaf.com/database/amazon-rds-postgresql/), [Amazon Aurora PostgreSQL](https://visualeaf.com/database/amazon-aurora-postgresql/), [CockroachDB](https://visualeaf.com/database/cockroachdb/), [YugabyteDB](https://visualeaf.com/database/yugabytedb/) |
| **MySQL y compatibles** | [MySQL](https://visualeaf.com/database/mysql/), [MariaDB](https://visualeaf.com/database/mariadb/), [Percona Server](https://visualeaf.com/database/percona/), [TiDB](https://visualeaf.com/database/tidb/), [Amazon RDS for MySQL](https://visualeaf.com/database/amazon-rds-mysql/), [Amazon Aurora MySQL](https://visualeaf.com/database/amazon-aurora-mysql/) |
| **SQL empresarial** | [Microsoft SQL Server](https://visualeaf.com/database/mssql/), [Azure SQL Database](https://visualeaf.com/database/azure-sql/), [Oracle](https://visualeaf.com/database/oracle/), [IBM Db2](https://visualeaf.com/database/db2/), [Firebird](https://visualeaf.com/database/firebird/) |
| **Analítica, almacenes de datos y streaming** | [ClickHouse](https://visualeaf.com/database/clickhouse/), [Amazon Redshift](https://visualeaf.com/database/amazon-redshift/), [Snowflake](https://visualeaf.com/database/snowflake/), [CrateDB](https://visualeaf.com/database/cratedb/), [QuestDB](https://visualeaf.com/database/questdb/), [RisingWave](https://visualeaf.com/database/risingwave/), [Materialize](https://visualeaf.com/database/materialize/) |
| **Basadas en archivo y embebidas** | [SQLite](https://visualeaf.com/database/sqlite/), [DuckDB](https://visualeaf.com/database/duckdb/), [H2](https://visualeaf.com/database/h2/), [HSQLDB](https://visualeaf.com/database/hsqldb/), [Apache Derby](https://visualeaf.com/database/derby/) |

[Ver todas las bases de datos compatibles →](https://visualeaf.com/database)

---

## Funcionalidades para MongoDB y SQL

Estas herramientas funcionan igual tanto si estás conectado a MongoDB como a una base de datos SQL.

### Gestor de conexiones
Guarda tus conexiones a MongoDB, PostgreSQL, MySQL, SQL Server, SQLite y otras en un solo lugar. Crea perfiles de conexión, agrúpalos por proyecto o entorno y cambia de base de datos al instante, con túneles SSH y SSL para instancias remotas y en la nube.

<p align="center">
  <a href="https://visualeaf.com/features/connection-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/connection-manager/overview.webp" alt="Gestor de conexiones de VisuaLeaf con un árbol de proyectos con entornos y conexiones" width="800">
  </a>
</p>

[Descubre el gestor de conexiones →](https://visualeaf.com/features/connection-manager/)

---

### Constructor visual de consultas
Construye consultas sin escribir sintaxis. En SQL, arrastra tablas al lienzo y VisuaLeaf sugiere los JOINs a partir de tus claves foráneas mientras escribe el SQL en una vista previa en vivo. En MongoDB, arma filtros `find()` con selectores de campo, desplegables de operadores y grupos AND/OR. Pasa a la sintaxis en bruto cuando quieras recuperar el control.

<p align="center">
  <a href="https://visualeaf.com/features/visual-query-builder/">
    <img src="https://release.sozocode.com/features-screenshot/query-builder.webp" alt="Constructor visual de consultas de MongoDB con grupos de filtros y resultados" width="800">
  </a>
</p>

[Descubre el constructor visual de consultas →](https://visualeaf.com/features/visual-query-builder/)

---

### Diagramas ER y esquema visual
Genera diagramas ER a partir de las claves foráneas SQL, o de lo que MongoDB almacena realmente en cada colección, con los tipos de campo inferidos automáticamente. También funciona en sentido inverso: diseña un esquema en el lienzo, pulsa **Materializar** y las tablas o colecciones se crean por ti.

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/database-website-images/MySQL/er-diagram-mysql.png" alt="Diagrama ER generado a partir de claves foráneas de MySQL" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/visual-schema/">
    <img src="https://release.sozocode.com/features-screenshot/visual-schema%402x.webp" alt="Diagrama de esquema de MongoDB mostrando colecciones y relaciones" width="800">
  </a>
</p>

[Descubre los diagramas ER y el esquema visual →](https://visualeaf.com/features/visual-schema/)

---

### Editor SQL y shell de MongoDB
Ejecuta scripts SQL o comandos de `mongosh` con resaltado de sintaxis, autocompletado e historial de comandos, y luego consulta los resultados como cuadrícula editable, árbol o JSON. Guarda scripts, vuelve a ejecutarlos más tarde y mantén cada resultado legible.

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/postgres-interface@2x.webp" alt="Editor SQL de PostgreSQL con cuadrícula de resultados junto a la gestión de tablas" width="800">
  </a>
</p>

<p align="center">
  <a href="https://visualeaf.com/features/mongo-shell/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-shell.webp" alt="Shell de MongoDB con salida visual en tabla, árbol y JSON" width="800">
  </a>
</p>

[Descubre el editor SQL y el shell de MongoDB →](https://visualeaf.com/features/mongo-shell/)

---

### Gestión de tablas
Crea y modifica tablas SQL de forma visual. Edita columnas, tipos, valores por defecto y nulabilidad, gestiona claves primarias y foráneas, índices, restricciones, triggers y particiones, y revisa el DDL generado antes de aplicarlo. Las vistas, secuencias, procedimientos y usuarios se gestionan desde el mismo espacio de trabajo.

<p align="center">
  <a href="https://visualeaf.com/docs/sql-table">
    <img src="https://visualeaf.com/assets/hero/table-management-1800w.webp" alt="Gestión de tablas de una tabla de PostgreSQL mostrando columnas, claves foráneas e índices" width="800">
  </a>
</p>

[Lee la documentación de gestión de tablas →](https://visualeaf.com/docs/sql-table)

---

### Perfilador de consultas
Una consulta que vuela con diez mil filas puede arrastrarse con diez millones. El perfilador muestra qué consultas te están costando caro y por qué, con planes de ejecución, métricas de tiempo, uso de índices y sugerencias del índice que lo resolvería.

<p align="center">
  <a href="https://visualeaf.com/features/query-profiler/">
    <img src="https://visualeaf.com/assets/documentation/query-profiler/profiler_overview.webp" alt="Perfilador de consultas con una línea de tiempo de ejecución y consultas agrupadas por forma" width="800">
  </a>
</p>

[Descubre el perfilador de consultas →](https://visualeaf.com/features/query-profiler/)

---

### Gráficos y dashboards
Grafica los resultados de una consulta SQL o de una agregación de MongoDB con más de 20 tipos de gráficos y fíjalos en dashboards. Sin necesidad de una herramienta de BI aparte.

<p align="center">
  <a href="https://visualeaf.com/features/charts-dashboard/">
    <img src="https://visualeaf.com/assets/hero/charts-dashboards-visualeaf-1350w.webp" alt="Dashboard de ventas de tiendas con gráficos de líneas, anillo, tarta, mapa de calor, embudo y radar" width="800">
  </a>
</p>

[Descubre los gráficos y dashboards →](https://visualeaf.com/features/charts-dashboard/)

---

### Gestor de tareas (importación, exportación, migración)
Ejecuta importaciones, exportaciones y migraciones entre MongoDB, bases de datos SQL y archivos (JSON, CSV, SQL, mongodump), y sigue trabajando mientras se ejecutan. Reasigna y transforma campos, enmascara datos sensibles, programa y encadena trabajos, y revisa el historial completo de lo que hizo cada tarea.

<p align="center">
  <a href="https://visualeaf.com/features/task-manager/">
    <img src="https://visualeaf.com/assets/screenshots/features/task-manager/list-details.webp" alt="Transferencia de datos con tareas en carpetas a la izquierda y los detalles de la tarea seleccionada a la derecha" width="800">
  </a>
</p>

[Descubre el gestor de tareas →](https://visualeaf.com/features/task-manager/)

---

### Vistas en paneles divididos
Abre colecciones, tablas, consultas, diagramas ER y dashboards uno junto a otro. Divide en horizontal o en vertical, arrastra pestañas para reorganizarlas y sincroniza el desplazamiento para comparar resultados entre bases de datos o entornos.

<p align="center">
  <a href="https://visualeaf.com/features/split-panel-views/">
    <img src="https://release.sozocode.com/features-screenshot/split-panel-views-visualeaf.webp" alt="Vistas en paneles divididos comparando consultas y datos lado a lado" width="800">
  </a>
</p>

[Descubre las vistas en paneles divididos →](https://visualeaf.com/features/split-panel-views/)

---

### Asistente de IA y servidor MCP
Describe lo que quieres y el asistente escribe la consulta sobre tu esquema real. Redacta agregaciones, convierte resultados en gráficos, genera diagramas ER, revisa cómo están estructurados tus datos y explica los planes de ejecución en lenguaje claro en lugar de JSON anidado. Con el **servidor MCP** integrado, además puedes conectar Claude, Cursor y otras herramientas de IA directamente a tus bases de datos.

<p align="center">
  <a href="https://visualeaf.com/features/ai-helper/">
    <img src="https://release.sozocode.com/features-screenshot/ai-assistant-visualeaf.webp" alt="Asistente de IA generando consultas de bases de datos a partir de lenguaje natural" width="800">
  </a>
</p>

[Descubre el asistente de IA →](https://visualeaf.com/features/ai-helper/)

---

## Funcionalidades para MongoDB

Las herramientas con las que nació VisuaLeaf, para MongoDB, Atlas, Cosmos DB y DocumentDB.

### Explorar colecciones
Explora documentos de tres maneras: vista de árbol para datos anidados, vista de tabla para revisar rápido y vista BSON para fidelidad total de tipos. Filtra, ordena y edita en línea, y profundiza en arrays y subdocumentos anidados sin perder el contexto.

<p align="center">
  <a href="https://visualeaf.com/features/browse-collections/">
    <img src="https://release.sozocode.com/features-screenshot/TreeView.webp" alt="Exploración de colecciones de MongoDB en vistas de árbol, tabla y BSON" width="800">
  </a>
</p>

[Descubre la exploración de colecciones →](https://visualeaf.com/features/browse-collections/)

---

### Constructor de pipelines de agregación
Diseña pipelines de agregación de MongoDB con una paleta de etapas de arrastrar y soltar. Añade `$match`, `$group`, `$lookup`, `$project`, `$unwind` y más, previsualiza los datos transformados en cada etapa y alterna entre el modo visual y el modo código.

<p align="center">
  <a href="https://visualeaf.com/features/aggregation-pipeline/">
    <img src="https://release.sozocode.com/documentation_organized/Aggregation%20Pipelines/aggregation-builder%402x.webp" alt="Constructor de pipelines de agregación de MongoDB con vistas previas etapa por etapa" width="800">
  </a>
</p>

[Descubre el constructor de pipelines de agregación →](https://visualeaf.com/features/aggregation-pipeline/)

---

### Modo SQL para MongoDB
Consulta colecciones de MongoDB con el SQL de siempre. VisuaLeaf traduce `SELECT`, `WHERE`, `GROUP BY` y `JOIN` a la consulta `find()` o al pipeline de agregación equivalente, para que veas exactamente lo que se ejecuta.

<p align="center">
  <a href="https://visualeaf.com/features/sql-mode/">
    <img src="https://release.sozocode.com/features-screenshot/sql-query-mode-visualeaf.webp" alt="Modo SQL para MongoDB, escribiendo SQL sobre colecciones de MongoDB" width="800">
  </a>
</p>

[Descubre el modo SQL →](https://visualeaf.com/features/sql-mode/)

---

### Validación con JSON Schema
Diseña y aplica validación JSON Schema en MongoDB con un editor en forma de árbol. Compatibilidad completa con los tipos BSON, reglas de validación y verificación con un clic contra colecciones en vivo.

<p align="center">
  <a href="https://visualeaf.com/features/schema-validation/">
    <img src="https://visualeaf.com/assets/screenshots/features/schema-validation/schema-builder.webp" alt="Constructor de esquemas mostrando un validador con campos obligatorios, tipos BSON y reglas" width="800">
  </a>
</p>

[Descubre la validación con JSON Schema →](https://visualeaf.com/features/schema-validation/)

---

### Gestor de índices
Crea, consulta y gestiona índices de MongoDB de forma visual: de un solo campo, compuestos, de texto, TTL, únicos y parciales. Revisa el tamaño y las estadísticas de uso de cada índice, detecta índices faltantes o redundantes, y elimínalos o reconstrúyelos con seguridad.

<p align="center">
  <a href="https://visualeaf.com/features/index-manager/">
    <img src="https://release.sozocode.com/features-screenshot/index-manager%402x.webp" alt="Gestor de índices de MongoDB con estadísticas de tamaño y uso" width="800">
  </a>
</p>

[Descubre el gestor de índices →](https://visualeaf.com/features/index-manager/)

---

### Comparación de colecciones
Compara colecciones de MongoDB lado a lado para detectar diferencias de estructura o de datos. Audita los cambios después de un despliegue y mantén alineados desarrollo, staging y producción.

<p align="center">
  <a href="https://visualeaf.com/features/collection-compare/">
    <img src="https://visualeaf.com/assets/screenshots/features/data-compare/setup.webp" alt="Lienzo de comparación de datos emparejando colecciones y tablas de una base de datos origen y una destino" width="800">
  </a>
</p>

[Descubre la comparación de colecciones →](https://visualeaf.com/features/collection-compare/)

---

### MongoSync
Sincroniza, copia y migra datos entre bases de datos, colecciones y entornos de MongoDB. Lleva una colección local a Atlas, ejecuta trabajos de sincronización filtrados o programados, mantén los datos sincronizados en tiempo real con change streams y previsualízalo todo con una ejecución en seco antes de escribir nada.

<p align="center">
  <a href="https://visualeaf.com/features/mongosync/">
    <img src="https://release.sozocode.com/features-screenshot/mongo-sync%402x.webp" alt="MongoSync sincronizando datos de MongoDB entre bases de datos y entornos" width="800">
  </a>
</p>

[Descubre MongoSync →](https://visualeaf.com/features/mongosync/)

---

### Visor de GridFS
Explora, sube, descarga y previsualiza archivos almacenados en GridFS de MongoDB, con subida por arrastrar y soltar, seguimiento del progreso y vistas previas en línea de imágenes, PDF y documentos.

<p align="center">
  <a href="https://visualeaf.com/features/gridfs-viewer/">
    <img src="https://release.sozocode.com/features-screenshot/gridfs-viewer-visualeaf.webp" alt="Visor de GridFS de MongoDB con vistas previas de archivos" width="800">
  </a>
</p>

[Descubre el visor de GridFS →](https://visualeaf.com/features/gridfs-viewer/)

---

### Panel RBAC
Gestiona usuarios, roles y permisos de forma visual. Revisa quién tiene acceso a qué base de datos y colección, audita privilegios y mantén ordenado el acceso del equipo sin editar documentos de roles a mano.

<p align="center">
  <a href="https://visualeaf.com/features/rbac-dashboard/">
    <img src="https://visualeaf.com/assets/documentation/access-control/dashboard_overview.webp" alt="Panel de usuarios y roles con recuentos de usuarios, roles y sesiones, y acciones rápidas" width="800">
  </a>
</p>

[Descubre el panel RBAC →](https://visualeaf.com/features/rbac-dashboard/)

---

### Replica sets y clústeres fragmentados
Consulta la topología, el estado y el oplog del replica set, ejecuta mantenimiento y reconfiguraciones de forma escalonada, haz copias de seguridad conscientes del replica set y gestiona clústeres fragmentados desde la misma app.

---

## Redis

Escanea el espacio de claves por patrón, abre cada tipo de valor en el editor que le corresponde, filtra valores, trabaja en la CLI de Redis integrada y prueba reglas ACL.

<p align="center">
  <a href="https://visualeaf.com/database/redis/">
    <img src="https://release.sozocode.com/database-website-images/Redis/redis-visualeaf%402x.webp.png" alt="Explorador de claves de Redis en VisuaLeaf" width="800">
  </a>
</p>

[Descubre VisuaLeaf para Redis →](https://visualeaf.com/database/redis/)

---

## Seguridad y privacidad

**Tus datos se quedan en local.** VisuaLeaf se conecta directamente desde tu equipo a tus bases de datos. Nunca vemos, almacenamos ni intermediamos tus datos.

- **Conexiones directas**: localhost, MongoDB Atlas, bases de datos gestionadas en la nube o cualquier servidor autoalojado
- **Túneles SSH y SSL**: conexiones seguras a través de hosts bastión y hacia instancias en la nube
- **Funciona sin conexión**: totalmente operativo sin internet tras la activación
- **Credenciales almacenadas en local**: los datos de conexión se cifran en tu equipo
- **Sin telemetría de consultas**: no registramos qué consultas haces ni a qué datos accedes

---

## Plataformas compatibles

| Plataforma | Arquitectura | Descarga |
|----------|--------------|----------|
| macOS    | Intel y Apple Silicon | [Descargar](https://visualeaf.com/download) |
| Windows  | x64 | [Descargar](https://visualeaf.com/download) |
| Linux    | x64, AppImage, deb | [Descargar](https://visualeaf.com/download) |

Funciona con **MongoDB 4.x–8.x** (Atlas, replica sets y clústeres fragmentados), **PostgreSQL**, **MySQL**, **MariaDB**, **SQL Server**, **Oracle**, **SQLite**, **Redis** y [más de 30 bases de datos adicionales](https://visualeaf.com/database).

---

## Primeros pasos

1. **Descarga** VisuaLeaf desde [visualeaf.com/download](https://visualeaf.com/download)
2. **Instálalo** en macOS, Windows o Linux
3. **Conéctate** a MongoDB, PostgreSQL, MySQL, SQLite o cualquier otra base de datos compatible
4. **Explora** tus datos con herramientas visuales

---

## Precios

| Plan | Precio | Descripción |
|------|-------|-------------|
| **Community** | Gratis | Todas las funcionalidades SQL, hasta 3 conexiones MongoDB guardadas, shell, exploración, gestión de índices, diagramas ER |
| **Basic** | $79 pago único + 1 año de actualizaciones | Constructores visuales de consultas y agregaciones, Redis, perfilador de consultas, tareas de importación/exportación, enmascaramiento de datos, asistente de IA |
| **Professional** | $149 pago único + 1 año de actualizaciones | Todo lo de Basic más tareas ilimitadas, comparación de colecciones, MongoSync, RBAC, gráficos y dashboards, servidor MCP, soporte prioritario |

Todas las licencias son perpetuas. Empieza con una **prueba gratuita de 14 días** de las funcionalidades Professional, sin tarjeta de crédito.

[Ver todos los precios →](https://visualeaf.com/pricing)

---

## Documentación

- [Guía de primeros pasos](https://visualeaf.com/docs)
- [Gestor de conexiones](https://visualeaf.com/docs/connection-manager)
- [Editor SQL](https://visualeaf.com/docs/sql-editor)
- [Constructor de consultas SQL](https://visualeaf.com/docs/sql-query-builder)
- [Constructor visual de consultas de MongoDB](https://visualeaf.com/docs/mongo-query)
- [Pipelines de agregación](https://visualeaf.com/docs/aggregation)
- [Diseñador de esquemas](https://visualeaf.com/docs/schema-designer)
- [Preguntas frecuentes](https://visualeaf.com/faq)

---

## Contacto

- Sitio web: [visualeaf.com](https://visualeaf.com)
- Twitter: [@SozoCode](https://twitter.com/SozoCode)
- Correo: [support@sozocode.com](mailto:support@sozocode.com)
- LinkedIn: [SozoCode LLC](https://www.linkedin.com/company/sozocode-llc)

---

## Proyectos relacionados

- **[MiniLeaf](https://github.com/sozocode/mini-leaf)**: visor de MongoDB de código abierto (ligero, solo lectura)

---

<p align="center">
  Hecho con cariño por <a href="https://visualeaf.com">SozoCode</a>
</p>
