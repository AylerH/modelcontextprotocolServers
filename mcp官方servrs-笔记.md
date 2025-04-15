# 概览
github-fork：https://github.com/AylerH/modelcontextprotocolServers

这个仓库是 Model Context Protocol (MCP) 的**参考实现**集合，以及社区构建的服务器和其他资源的引用。

这个仓库中的服务器展示了 MCP 的多功能性和可扩展性，演示了如何使用它为大型语言模型（LLM）提供安全、受控的工具和数据源访问。每个 MCP 服务器都使用 Typescript MCP SDK 或 Python MCP SDK 实现。



# 模型上下文协议服务器

本仓库是 [模型上下文协议](https://modelcontextprotocol.io/) (MCP) 的一系列 *参考实现*，以及社区构建的服务器和其他资源的参考。

本仓库中的服务器展示了 MCP 的多样性和可扩展性，演示了如何使用它为大型语言模型 (LLMs) 提供安全、受控的工具和数据源访问。
每个 MCP 服务器都是使用 [Typescript MCP SDK](https://github.com/modelcontextprotocol/typescript-sdk) 或 [Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk) 实现的。

> 注意：本 README 中的列表按字母顺序维护，以最小化添加新项目时的合并冲突。

## 🌟 参考服务器

这些服务器旨在展示 MCP 特性以及 TypeScript 和 Python SDK。

- **[AWS KB 检索](src/aws-kb-retrieval-server)** - 使用 Bedrock Agent Runtime 从 AWS 知识库中检索
- **[Brave 搜索](src/brave-search)** - 使用 Brave 的搜索 API 进行网络和本地搜索
- **[EverArt](src/everart)** - 使用各种模型进行 AI 图像生成
- **[Everything](src/everything)** - 参考/测试服务器，提供提示、资源和工具
- **[Fetch](src/fetch)** - 网络内容获取和转换，以提高 LLM 的使用效率
- **[Filesystem](src/filesystem)** - 具有可配置访问控制的安全文件操作
- **[Git](src/git)** - 读取、搜索和操作 Git 仓库的工具
- **[GitHub](src/github)** - 仓库管理、文件操作和 GitHub API 集成
- **[GitLab](src/gitlab)** - GitLab API，支持项目管理
- **[Google Drive](src/gdrive)** - Google Drive 的文件访问和搜索功能
- **[Google Maps](src/google-maps)** - 位置服务、方向和地点详情
- **[Memory](src/memory)** - 基于知识图谱的持久记忆系统
- **[PostgreSQL](src/postgres)** - 只读数据库访问和模式检查
- **[Puppeteer](src/puppeteer)** - 浏览器自动化和网络抓取
- **[Redis](src/redis)** - 与 Redis 键值存储交互
- **[Sentry](src/sentry)** - 从 Sentry.io 检索和分析问题
- **[Sequential Thinking](src/sequentialthinking)** - 通过思维序列进行动态和反思性问题解决
- **[Slack](src/slack)** - 渠道管理和消息功能
- **[Sqlite](src/sqlite)** - 数据库交互和商业智能功能
- **[Time](src/time)** - 时间和时区转换功能

## 🤝 第三方服务器

### 🎖️ 官方集成

由构建生产就绪 MCP 服务器的平台公司维护的官方集成。

- <img height="12" width="12" src="https://www.21st.dev/favicon.ico" alt="21st.dev Logo" /> **[21st.dev Magic](https://github.com/21st-dev/magic-mcp)** - 创建受最佳 21st.dev 设计工程师启发的 UI 组件。
- <img height="12" width="12" src="https://invoxx-public-bucket.s3.eu-central-1.amazonaws.com/frontend-resources/adfin-logo-small.svg" alt="Adfin Logo" /> **[Adfin](https://github.com/Adfin-Engineering/mcp-server-adfin)** - 您所需的唯一平台 - 所有支付集中在一个地方，发票和会计对账与 [Adfin](https://www.adfin.com/) 一起完成。
- <img height="12" width="12" src="https://www.agentql.com/favicon/favicon.png" alt="AgentQL Logo" /> **[AgentQL](https://github.com/tinyfish-io/agentql-mcp)** - 使 AI 代理能够使用 [AgentQL](https://www.agentql.com/) 从非结构化网络中获取结构化数据。
- <img height="12" width="12" src="https://agentrpc.com/favicon.ico" alt="AgentRPC Logo" /> **[AgentRPC](https://github.com/agentrpc/agentrpc)** - 使用 [AgentRPC](https://www.agentrpc.com/) 连接到任何函数、任何语言，跨网络边界。
- <img height="12" width="12" src="https://aiven.io/favicon.ico" alt="Aiven Logo" /> **[Aiven](https://github.com/Aiven-Open/mcp-aiven)** - 导航您的 [Aiven 项目](https://go.aiven.io/mcp-server) 并与 PostgreSQL®、Apache Kafka®、ClickHouse® 和 OpenSearch® 服务进行交互。
- <img height="12" width="12" src="https://iotdb.apache.org/img/logo.svg" alt="Apache IoTDB Logo" /> **[Apache IoTDB](https://github.com/apache/iotdb-mcp-server)** - MCP 服务器，用于 [Apache IoTDB](https://github.com/apache/iotdb) 数据库及其工具。
- <img height="12" width="12" src="https://apify.com/favicon.ico" alt="Apify Logo" /> **[Apify](https://github.com/apify/actors-mcp-server)** - [Actors MCP Server](https://apify.com/apify/actors-mcp-server)：使用 3,000 多个预构建的云工具从网站、电子商务、社交媒体、搜索引擎、地图等提取数据。
- <img height="12" width="12" src="https://2052727.fs1.hubspotusercontent-na1.net/hubfs/2052727/cropped-cropped-apimaticio-favicon-1-32x32.png" alt="APIMatic Logo" /> **[APIMatic MCP](https://github.com/apimatic/apimatic-validator-mcp)** - APIMatic MCP 服务器用于使用 [APIMatic](https://www.apimatic.io/) 验证 OpenAPI 规范。该服务器处理 OpenAPI 文件并返回验证摘要，利用 APIMatic 的 API。
- <img height="12" width="12" src="https://resources.audiense.com/hubfs/favicon-1.png" alt="Audiense Logo" /> **[Audiense Insights](https://github.com/AudienseCo/mcp-audiense-insights)** - 来自 [Audiense](https://www.audiense.com/products/audiense-insights) 报告的市场洞察和受众分析，涵盖人口统计、文化、影响者和内容参与分析。
- <img height="12" width="12" src="https://axiom.co/favicon.ico" alt="Axiom Logo" /> **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** - 用自然语言查询和分析您的 Axiom 日志、跟踪和所有其他事件数据。
- <img height="12" width="12" src="https://www.bankless.com/favicon.ico" alt="Bankless Logo" /> **[Bankless Onchain](https://github.com/bankless/onchain-mcp)** - 查询链上数据，如 ERC20 代币、交易历史、智能合约状态。
- <img height="12" width="12" src="https://bicscan.io/favicon.png" alt="BICScan Logo" /> **[BICScan](https://github.com/ahnlabio/bicscan-mcp)** - EVM 区块链地址 (EOA、CA、ENS) 及域名的风险评分/资产持有情况。
- <img height="12" width="12" src="https://www.box.com/favicon.ico" alt="Box Logo" /> **[Box](https://github.com/box-community/mcp-server-box)** - 通过 Box AI 与智能内容管理平台进行交互。
- <img height="12" width="12" src="https://browserbase.com/favicon.ico" alt="Browserbase Logo" /> **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** - 在云中自动化浏览器交互（例如，网页导航、数据提取、表单填写等）。
- <img height="12" width="12" src="https://www.chargebee.com/static/resources/brand/favicon.png" /> **[Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol)** - MCP 服务器，将 AI 代理连接到 [Chargebee 平台](https://www.chargebee.com)。
- <img height="12" width="12" src="https://trychroma.com/_next/static/media/chroma-logo.ae2d6e4b.svg" /> **[Chroma](https://github.com/chroma-core/chroma-mcp)** - 嵌入、向量搜索、文档存储和开源 AI 应用数据库的全文搜索。
- <img height="12" width="12" src="https://www.chronulus.com/favicon/chronulus-logo-blue-on-alpha-square-128x128.ico" alt="Chronulus AI Logo" /> **[Chronulus AI](https://github.com/ChronulusAI/chronulus-mcp)** - 使用 Chronulus AI 预测和预测代理预测任何事物。
- <img height="12" width="12" src="https://circleci.com/favicon.ico" alt="CircleCI Logo" /> **[CircleCI](https://github.com/CircleCI-Public/mcp-server-circleci)** - 使 AI 代理能够修复来自 CircleCI 的构建失败。
- <img height="12" width="12" src="https://clickhouse.com/favicon.ico" alt="ClickHouse Logo" /> **[ClickHouse](https://github.com/ClickHouse/mcp-clickhouse)** - 查询您的 [ClickHouse](https://clickhouse.com/) 数据库服务器。
- <img height="12" width="12" src="https://cdn.simpleicons.org/cloudflare" /> **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - 部署、配置和查询您在 Cloudflare 开发者平台上的资源（例如 Workers/KV/R2/D1）。
- <img height="12" width="12" src="https://codelogic.com/wp-content/themes/codelogic/assets/img/favicon.png" alt="CodeLogic Logo" /> **[CodeLogic](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server)** - 与 [CodeLogic](https://codelogic.com) 交互，这是一个软件智能平台，可以绘制复杂的代码和数据架构依赖关系，以提高 AI 的准确性和洞察力。
- <img height="12" width="12" src="https://www.comet.com/favicon.ico" alt="Comet Logo" /> **[Comet Opik](https://github.com/comet-ml/opik-mcp)** - 用自然语言查询和分析您的 [Opik](https://github.com/comet-ml/opik) 日志、跟踪、提示和所有其他 LLM 的遥测数据。
- <img height="12" width="12" src="https://www.convex.dev/favicon.ico" /> **[Convex](https://stack.convex.dev/convex-mcp-server)** - 直观查询和查询您部署到 Convex 的应用程序。
- <img height="12" width="12" src="http://app.itsdart.com/static/img/favicon.png" alt="Dart Logo" /> **[Dart](https://github.com/its-dart/dart-mcp-server)** - 与 [Dart](https://itsdart.com) 的任务、文档和项目数据进行交互，这是一个 AI 原生项目管理工具。
- <img height="12" width="12" src="https://www.devhub.com/img/upload/favicon-196x196-dh.png" alt="DevHub Logo" /> **[DevHub](https://github.com/devhub/devhub-cms-mcp)** - 在 [DevHub](https://www.devhub.com) CMS 平台内管理和利用网站内容。
- <img height="12" width="12" src="https://e2b.dev/favicon.ico" alt="E2B Logo" /> **[E2B](https://github.com/e2b-dev/mcp-server)** - 在 [E2B](https://e2b.dev) 托管的安全沙箱中运行代码。
- <img height="12" width="12" src="https://static.edubase.net/media/brand/favicon/favicon-32x32.png" alt="EduBase Logo" /> **[EduBase](https://github.com/EduBase/MCP)** - 与 [EduBase](https://www.edubase.net) 交互，这是一个全面的电子学习平台，具有高级测验、考试管理和内容组织能力。
- <img height="12" width="12" src="https://www.elastic.co/favicon.ico" alt="Elasticsearch Logo" /> **[Elasticsearch](https://github.com/elastic/mcp-server-elasticsearch)** - 在 [Elasticsearch](https://www.elastic.co/elasticsearch) 中查询您的数据。
- <img height="12" width="12" src="https://esignatures.com/favicon.ico" alt="eSignatures Logo" /> **[eSignatures](https://github.com/esignaturescom/mcp-server-esignatures)** - 合同和模板管理，用于起草、审查和发送具有约束力的合同。
- <img height="12" width="12" src="https://exa.ai/images/favicon-32x32.png" alt="Exa Logo" /> **[Exa](https://github.com/exa-labs/exa-mcp-server)** - 为 AI 制作的搜索引擎 [Exa](https://exa.ai)。
- <img height="12" width="12" src="https://fewsats.com/favicon.svg" alt="Fewsats Logo" /> **[Fewsats](https://github.com/Fewsats/fewsats-mcp)** - 使 AI 代理能够使用 [Fewsats](https://fewsats.com) 以安全的方式购买任何东西。
- <img height="12" width="12" src="https://fibery.io/favicon.svg" alt="Fibery Logo" /> **[Fibery](https://github.com/Fibery-inc/fibery-mcp-server)** - 在您的 [Fibery](https://fibery.io) 工作区中执行查询和实体操作。
- <img height="12" width="12" src="https://financialdatasets.ai/favicon.ico" alt="Financial Datasets Logo" /> **[Financial Datasets](https://github.com/financial-datasets/mcp-server)** - 为 AI 代理制作的股市 API。
- <img height="12" width="12" src="https://firecrawl.dev/favicon.ico" alt="Firecrawl Logo" /> **[Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)** - 使用 [Firecrawl](https://firecrawl.dev) 提取网络数据。
- <img height="12" width="12" src="https://fireproof.storage/favicon.ico" alt="Fireproof Logo" /> **[Fireproof](https://github.com/fireproof-storage/mcp-database-server)** - 具有实时同步的不可变账本数据库。
- <img height="12" width="12" src="https://gitee.com/favicon.ico" alt="Gitee Logo" /> **[Gitee](https://github.com/oschina/mcp-gitee)** - Gitee API 集成、仓库、问题和拉取请求管理等。
- <img height="12" width="12" src="https://cdn.prod.website-files.com/6605a2979ff17b2cd1939cd4/6605a460de47e7596ed84f06_icon256.png" alt="gotoHuman Logo" /> **[gotoHuman](https://github.com/gotohuman/gotohuman-mcp-server)** - 人工审核平台 - 允许 AI 代理和自动化向您的 [gotoHuman](https://www.gotohuman.com) 收件箱发送请求以获得批准。
- <img height="12" width="12" src="https://grafana.com/favicon.ico" alt="Grafana Logo" /> **[Grafana](https://github.com/grafana/mcp-grafana)** - 在您的 Grafana 实例中搜索仪表板、调查事件和查询数据源。
- <img height="12" width="12" src="https://framerusercontent.com/images/KCOWBYLKunDff1Dr452y6EfjiU.png" alt="Graphlit Logo" /> **[Graphlit](https://github.com/graphlit/graphlit-mcp-server)** - 从 Slack 到 Gmail 到播客源，除了网络爬虫外，将任何内容摄取到可搜索的 [Graphlit](https://www.graphlit.com) 项目中。
- <img height="12" width="12" src="https://greptime.com/favicon.ico" alt="Greptime Logo" /> **[GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)** - 为 AI 助手提供安全和结构化的方式来探索和分析 [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) 中的数据。
- <img height="12" width="12" src="https://www.herokucdn.com/favicons/favicon.ico" alt="Heroku Logo" /> **[Heroku](https://github.com/heroku/heroku-mcp-server)** - 通过 LLM 驱动的工具与 Heroku 平台进行交互，以管理应用程序、附加组件、dynos、数据库等。
- <img height="12" width="12" src="https://img.alicdn.com/imgextra/i3/O1CN01d9qrry1i6lTNa2BRa_!!6000000004364-2-tps-218-200.png" alt="Hologres Logo" /> **[Hologres](https://github.com/aliyun/alibabacloud-hologres-mcp-server)** - 连接到 [Hologres](https://www.alibabacloud.com/en/product/hologres) 实例，获取表元数据，查询和分析数据。
- <img height="12" width="12" src="https://hyperbrowser-assets-bucket.s3.us-east-1.amazonaws.com/Hyperbrowser-logo.png" alt="Hyperbrowsers23 Logo" /> **[Hyperbrowser](https://github.com/hyperbrowserai/mcp)** - [Hyperbrowser](https://www.hyperbrowser.ai/) 是下一代平台，赋予 AI 代理能力并实现轻松、可扩展的浏览器自动化。
- **[IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript)** - IBM 的工具平台，用于构建、测试和部署任何数据源的工具。
- <img height="12" width="12" src="https://forevervm.com/icon.png" alt="ForeverVM Logo" /> **[ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server)** - 在代码沙箱中运行 Python。
- <img height="12" width="12" src="https://www.getinboxzero.com/icon.png" alt="Inbox Zero Logo" /> **[Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server)** - 电子邮件的 AI 个人助理 [Inbox Zero](https://www.getinboxzero.com)。
- <img height="12" width="12" src="https://inkeep.com/favicon.ico" alt="Inkeep Logo" /> **[Inkeep](https://github.com/inkeep/mcp-server-python)** - 基于 RAG 的搜索，利用 [Inkeep](https://inkeep.com) 提供的内容。
- <img height="12" width="12" src="https://integration.app/favicon.ico" alt="Integration App Icon" /> **[Integration App](https://github.com/integration-app/mcp-server)** - 代表客户与其他 SaaS 应用程序进行交互。
- <img height="12" width="12" src="https://cdn.simpleicons.org/jetbrains" /> **[JetBrains](https://github.com/JetBrains/mcp-jetbrains)** – 在 JetBrains IDE 中处理代码。
- <img height="12" width="12" src="https://kagi.com/favicon.ico" alt="Kagi Logo" /> **[Kagi Search](https://github.com/kagisearch/kagimcp)** - 使用 Kagi 的搜索 API 搜索网络。
- <img height="12" width="12" src="https://connection.keboola.com/favicon.ico" alt="Keboola Logo" /> **[Keboola](https://github.com/keboola/keboola-mcp-server)** - 在单一直观平台上构建强大的数据工作流、集成和分析。
- <img height="12" width="12" src="https://laratranslate.com/favicon.ico" alt="Lara Translate Logo" /> **[Lara Translate](https://github.com/translated/lara-mcp)** - Lara Translate API 的 MCP 服务器，支持语言检测和上下文感知翻译的强大翻译能力。
- <img height="12" width="12" src="https://logfire.pydantic.dev/favicon.ico" alt="Logfire Logo" /> **[Logfire](https://github.com/pydantic/logfire-mcp)** - 通过 Logfire 提供对 OpenTelemetry 跟踪和指标的访问。
- <img height="12" width="12" src="https://langfuse.com/favicon.ico" alt="Langfuse Logo" /> **[Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse)** - 开源工具，用于协作编辑、版本控制、评估和发布提示。
- <img height="12" width="12" src="https://lingo.dev/favicon.ico" alt="Lingo.dev Logo" /> **[Lingo.dev](https://github.com/lingodotdev/lingo.dev/blob/main/mcp.md)** - 使用 [Lingo.dev](https://lingo.dev) 本地化引擎，使您的 AI 代理能够说出地球上每种语言。
- <img height="12" width="12" src="https://www.mailgun.com/favicon.ico" alt="Mailgun Logo" /> **[Mailgun](https://github.com/mailgun/mailgun-mcp-server)** - 与 Mailgun API 交互。
- <img height="12" width="12" src="https://www.make.com/favicon.ico" alt="Make Logo" /> **[Make](https://github.com/integromat/make-mcp-server)** - 将您的 [Make](https://www.make.com/) 场景转换为 AI 助手可调用的工具。
- <img height="12" width="12" src="https://www.meilisearch.com/favicon.ico" alt="Meilisearch Logo" /> **[Meilisearch](https://github.com/meilisearch/meilisearch-mcp)** - 与 Meilisearch 进行交互和查询（全文和语义搜索 API）。
- <img height="12" width="12" src="https://metoro.io/static/images/logos/Metoro.svg" /> **[Metoro](https://github.com/metoro-io/metoro-mcp-server)** - 查询和与 Metoro 监控的 Kubernetes 环境进行交互。
- <img height="12" width="12" src="https://milvus.io/favicon-32x32.png" /> **[Milvus](https://github.com/zilliztech/mcp-server-milvus)** - 在您的 Milvus 向量数据库中搜索、查询和交互数据。
- <img height="12" width="12" src="https://www.motherduck.com/favicon.ico" alt="MotherDuck Logo" /> **[MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)** - 使用 MotherDuck 和本地 DuckDB 查询和分析数据。
- <img height="12" width="12" src="https://needle-ai.com/images/needle-logo-orange-2-rounded.png" alt="Needle AI Logo" /> **[Needle](https://github.com/needle-ai/needle-mcp)** - 开箱即用的生产就绪 RAG，用于搜索和检索您自己的文档中的数据。
- <img height="12" width="12" src="https://neo4j.com/favicon.ico" alt="Neo4j Logo" /> **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** - Neo4j 图数据库服务器（模式 + 读/写 cypher）和单独的图数据库备份内存。
- <img height="12" width="12" src="https://avatars.githubusercontent.com/u/183852044?s=48&v=4" alt="Neon Logo" /> **[Neon](https://github.com/neondatabase/mcp-server-neon)** - 与 Neon 无服务器 Postgres 平台进行交互。
- <img height="12" width="12" src="https://avatars.githubusercontent.com/u/82347605?s=48&v=4" alt="OceanBase Logo" /> **[OceanBase](https://github.com/oceanbase/mcp-oceanbase)** - OceanBase 数据库及其工具的 MCP 服务器。
- <img height="12" width="12" src="https://docs.octagonagents.com/logo.svg" alt="Octagon Logo" /> **[Octagon](https://github.com/OctagonAI/octagon-mcp-server)** - 提供实时投资研究，涵盖广泛的私有和公共市场数据。
- <img height="12" width="12" src="https://oxylabs.io/favicon.ico" alt="Oxylabs Logo" /> **[Oxylabs](https://github.com/oxylabs/oxylabs-mcp)** - 使用 Oxylabs Web API 抓取网站，支持动态渲染和解析以提取结构化数据。
- <img height="12" width="12" src="https://developer.paddle.com/favicon.svg" alt="Paddle Logo" /> **[Paddle](https://github.com/PaddleHQ/paddle-mcp-server)** - 与 Paddle API 交互。管理产品目录、账单和订阅以及报告。
- <img height="12" width="12" src="https://www.paypalobjects.com/webstatic/icon/favicon.ico" alt="PayPal Logo" /> **[PayPal](https://mcp.paypal.com)** - PayPal 的官方 MCP 服务器。
- <img height="12" width="12" src="https://www.perplexity.ai/favicon.ico" alt="Perplexity Logo" /> **[Perplexity](https://github.com/ppl-ai/modelcontextprotocol)** - 一个连接到 Perplexity 的 Sonar API 的 MCP 服务器，支持实时网络范围内的对话 AI 研究。
- <img height="12" width="12" src="https://qdrant.tech/img/brand-resources-logos/logomark.svg" /> **[Qdrant](https://github.com/qdrant/mcp-server-qdrant/)** - 在 Qdrant 向量搜索引擎上实现语义记忆层。
- <img height="12" width="12" src="https://www.ramp.com/favicon.ico" /> **[Ramp](https://github.com/ramp-public/ramp-mcp)** - 与 [Ramp](https://ramp.com) 的开发者 API 交互，分析您的支出并利用 LLM 获得洞察。
- **[Raygun](https://github.com/MindscapeHQ/mcp-server-raygun)** - 与您的 Raygun 帐户上的崩溃报告和实时监控数据进行交互。
- <img height="12" width="12" src="https://www.rember.com/favicon.ico" alt="Rember Logo" /> **[Rember](https://github.com/rember/rember-mcp)** - 在 [Rember](https://rember.com) 中创建间隔重复的闪卡，以记住您在聊天中学习的任何内容。
- <img height="12" width="12" src="https://riza.io/favicon.ico" alt="Riza logo" /> **[Riza](https://github.com/riza-io/riza-mcp)** - 为 LLM 提供的任意代码执行和工具使用平台 [Riza](https://riza.io)。
- <img height="12" width="12" src="https://pics.fatwang2.com/56912e614b35093426c515860f9f2234.svg" /> [Search1API](https://github.com/fatwang2/search1api-mcp) - 一个用于搜索、爬虫和网站地图的 API。
- <img height="12" width="12" src="https://screenshotone.com/favicon.ico" alt="ScreenshotOne Logo" /> **[ScreenshotOne](https://github.com/screenshotone/mcp/)** - 使用 [ScreenshotOne](https://screenshotone.com/) 渲染网站截图。
- <img height="12" width="12" src="https://semgrep.dev/favicon.ico" alt="Semgrep Logo" /> **[Semgrep](https://github.com/semgrep/mcp)** - 使 AI 代理能够使用 [Semgrep](https://semgrep.dev/) 保护代码。
- <img height="12" width="12" src="https://www.singlestore.com/favicon-32x32.png?v=277b9cbbe31e8bc416504cf3b902d430"/> **[SingleStore](https://github.com/singlestore-labs/mcp-server-singlestore)** - 与 SingleStore 数据库平台进行交互。
- <img height="12" width="12" src="https://www.starrocks.io/favicon.ico" alt="StarRocks Logo" /> **[StarRocks](https://github.com/StarRocks/mcp-server-starrocks)** - 与 [StarRocks](https://www.starrocks.io/) 进行交互。
- <img height="12" width="12" src="https://stripe.com/favicon.ico" alt="Stripe Logo" /> **[Stripe](https://github.com/stripe/agent-toolkit)** - 与 Stripe API 进行交互。
- <img height="12" width="12" src="https://tavily.com/favicon.ico" alt="Tavily Logo" /> **[Tavily](https://github.com/tavily-ai/tavily-mcp)** - AI 代理的搜索引擎（搜索 + 提取），由 [Tavily](https://tavily.com/) 提供支持。
- <img height="12" width="12" src="https://thirdweb.com/favicon.ico" alt="Thirdweb Logo" /> **[Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp)** - 读取/写入超过 2,000 个区块链，支持数据查询、合约分析/部署和交易执行，由 [Thirdweb](https://thirdweb.com/) 提供支持。
- <img height="12" width="12" src="https://www.tinybird.co/favicon.ico" alt="Tinybird Logo" /> **[Tinybird](https://github.com/tinybirdco/mcp-tinybird)** - 与 Tinybird 无服务器 ClickHouse 平台进行交互。
- <img height="12" width="12" src="https://unifai.network/favicon.ico" alt="UnifAI Logo" /> **[UnifAI](https://github.com/unifai-network/unifai-mcp-server)** - 使用 [UnifAI Network](https://unifai.network) 动态搜索和调用工具。
- <img height="12" width="12" src="https://framerusercontent.com/images/plcQevjrOYnyriuGw90NfQBPoQ.jpg" alt="Unstructured Logo" /> **[Unstructured](https://github.com/Unstructured-IO/UNS-MCP)** - 在 [Unstructured Platform](https://unstructured.io) 中设置和与您的非结构化数据处理工作流进行交互。
- **[Vectorize](https://github.com/vectorize-io/vectorize-mcp-server/)** - [Vectorize](https://vectorize.io) 的 MCP 服务器，用于高级检索、私有深度研究、Markdown 文件提取和文本分块。
- <img height="12" width="12" src="https://verodat.io/assets/favicon-16x16.png" alt="Verodat Logo" /> **[Verodat](https://github.com/Verodat/verodat-mcp-server)** - 与 Verodat AI Ready Data 平台进行交互。
- <img height="12" width="12" src="https://www.veyrax.com/favicon.ico" alt="VeyraX Logo" /> **[VeyraX](https://github.com/VeyraX/veyrax-mcp)** - 控制所有 100 多个 API 集成和 UI 组件的单一工具。
- <img height="12" width="12" src="https://www.xero.com/favicon.ico" alt="Xero Logo" /> **[Xero](https://github.com/XeroAPI/xero-mcp-server)** - 使用我们的官方 MCP 服务器与您业务中的会计数据进行交互。
- <img height="12" width="12" src="https://cdn.zapier.com/zapier/images/favicon.ico" alt="Zapier Logo" /> **[Zapier](https://zapier.com/mcp)** - 立即将您的 AI 代理连接到 8,000 个应用程序。
- **[ZenML](https://github.com/zenml-io/mcp-zenml)** - 通过您的 [ZenML](https://www.zenml.io) MCP 服务器与您的 MLOps 和 LLMOps 管道进行交互。

### 🌎 社区服务器

一组不断增长的社区开发和维护的服务器展示了 MCP 在不同领域的各种应用。

> **注意：** 社区服务器是 **未经测试的**，应 **自担风险** 使用。它们与 Anthropic 无关或不被认可。
- **[Ableton Live](https://github.com/Simon-Kansara/ableton-live-mcp-server)** - 控制 Ableton Live 的 MCP 服务器。
- **[Airbnb](https://github.com/openbnb-org/mcp-server-airbnb)** - 提供工具以搜索 Airbnb 并获取列表详情。
- **[AI Agent Marketplace Index](https://github.com/AI-Agent-Hub/ai-agent-marketplace-index-mcp)** - MCP 服务器，用于搜索来自 [AI Agent Marketplace Index](http://www.deepnlp.org/store/ai-agent) 的 5000 多个 AI 代理和工具，并监控 AI 代理的流量。
- **[Algorand](https://github.com/GoPlausible/algorand-mcp)** - 一个全面的 MCP 服务器，用于工具交互（40 多个）和资源访问（60 多个），以及与 Algorand 区块链交互的许多有用提示。
- **[Airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow)** - 一个连接到 [Apache Airflow](https://airflow.apache.org/) 的 MCP 服务器，使用官方 Python 客户端。
- **[Airtable](https://github.com/domdomegg/airtable-mcp-server)** - 读取和写入 [Airtable](https://airtable.com/) 数据库，具有模式检查。
- **[Airtable](https://github.com/felores/airtable-mcp)** - Airtable 模型上下文协议服务器。
- **[AlphaVantage](https://github.com/calvernaz/alphavantage)** - MCP 服务器，用于股票市场数据 API [AlphaVantage](https://www.alphavantage.co)。
- **[Anki](https://github.com/scorzeth/anki-mcp-server)** - 与您的 [Anki](https://apps.ankiweb.net) 卡组和卡片进行交互的 MCP 服务器。
- **[Any Chat Completions](https://github.com/pyroprompts/any-chat-completions-mcp)** - 与任何兼容 OpenAI SDK 的聊天完成 API 进行交互，如 OpenAI、Perplexity、Groq、xAI 等。
- **[Apple Calendar](https://github.com/Omar-v2/mcp-ical)** - 一个允许您通过自然语言与 MacOS 日历交互的 MCP 服务器，包括事件创建、修改、日程列表、查找空闲时间等功能。
- **[ArangoDB](https://github.com/ravenwits/mcp-server-arangodb)** - 通过 [ArangoDB](https://arangodb.com/) 提供数据库交互能力的 MCP 服务器。
- **[Arduino](https://github.com/vishalmysore/choturobo)** - MCP 服务器，使用 Claude AI 和 Arduino (ESP32) 实现 AI 驱动的机器人技术，用于现实世界的自动化和与机器人的交互。
- **[Atlassian](https://github.com/sooperset/mcp-atlassian)** - 与 Atlassian Cloud 产品（Confluence 和 Jira）进行交互，包括搜索/读取 Confluence 空间/页面、访问 Jira 问题和项目元数据。
- **[Attestable MCP](https://github.com/co-browser/attestable-mcp-server)** - 在受信执行环境 (TEE) 内运行的 MCP 服务器，通过 Gramine 展示远程证明，使用 [RA-TLS](https://gramine.readthedocs.io/en/stable/attestation.html)。这允许 MCP 客户端在连接之前验证服务器。
- **[AWS](https://github.com/rishikavikondala/mcp-server-aws)** - 使用 LLM 对 AWS 资源执行操作。
- **[AWS Athena](https://github.com/lishenxydlgzs/aws-athena-mcp)** - 一个用于 AWS Athena 的 MCP 服务器，在 Glue Catalog 上运行 SQL 查询。
- **[AWS Cost Explorer](https://github.com/aarora79/aws-cost-explorer-mcp-server)** - 使用此 MCP 服务器优化您的 AWS 支出（包括 Amazon Bedrock 支出），通过检查跨区域、服务、实例类型和基础模型的支出。
- **[AWS Resources Operations](https://github.com/baryhuang/mcp-server-aws-resources-python)** - 运行生成的 Python 代码，以安全地查询或修改任何由 boto3 支持的 AWS 资源。
- **[AWS S3](https://github.com/aws-samples/sample-mcp-server-s3)** - 一个用于 AWS S3 的示例 MCP 服务器，灵活地从 S3 中获取对象，例如 PDF 文档。
- **[Azure ADX](https://github.com/pab1it0/adx-mcp-server)** - 查询和分析 Azure 数据探索数据库。
- **[Azure DevOps](https://github.com/Vortiago/mcp-azure-devops)** - 一个 MCP 服务器，提供与 Azure DevOps 服务的桥接，使 AI 助手能够查询和管理工作项。
- **[Baidu AI Search](https://github.com/baidubce/app-builder/tree/master/python/mcp_server/ai_search)** - 使用百度云的 AI 搜索进行网络搜索。
- **[Base Free USDC Transfer](https://github.com/magnetai/mcp-free-usdc-transfer)** - 使用 Claude AI 免费在 [Base](https://base.org) 上发送 USDC！使用 [Coinbase CDP](https://docs.cdp.coinbase.com/mpc-wallet/docs/welcome) 构建。
* **[Basic Memory](https://github.com/basicmachines-co/basic-memory)** - 本地优先知识管理系统，从 Markdown 文件构建语义图，实现与 LLM 的对话中的持久记忆。
- **[BigQuery](https://github.com/LucasHild/mcp-server-bigquery)** (by LucasHild) - 此服务器使 LLM 能够检查数据库模式并在 BigQuery 上执行查询。
- **[BigQuery](https://github.com/ergut/mcp-bigquery-server)** (by ergut) - Google BigQuery 集成的服务器实现，支持直接访问和查询 BigQuery 数据库。
- **[Bing Web Search API](https://github.com/leehanchung/bing-search-mcp)** (by hanchunglee) - 微软 Bing Web 搜索 API 的服务器实现。
- **[Bitable MCP](https://github.com/lloydzhou/bitable-mcp)** (by lloydzhou) - MCP 服务器通过模型上下文协议提供对 Lark Bitable 的访问。允许用户使用预定义工具与 Bitable 表进行交互。
- **[Blender](https://github.com/ahujasid/blender-mcp)** (by ahujasid) - Blender 集成，允许启用提示的 3D 场景创建、建模和操作。
- **[browser-use](https://github.com/co-browser/browser-use-mcp-server)** (by co-browser) - browser-use MCP 服务器，具有 docker 化的 playwright + chromium + vnc。支持 stdio 和可恢复的 http。
- **[Bsc-mcp](https://github.com/TermiX-official/bsc-mcp)** 第一个 MCP 服务器，作为 AI 和 BNB 链之间的桥梁，使 AI 代理能够通过无缝集成执行复杂的链上操作，包括转账、交换、启动、对任何代币的安全检查等。
- **[Calculator](https://github.com/githejie/mcp-server-calculator)** - 此服务器使 LLM 能够使用计算器进行精确的数值计算。
- **[CFBD API](https://github.com/lenwood/cfbd-mcp-server)** - 一个用于 [College Football Data API](https://collegefootballdata.com/) 的 MCP 服务器。
- **[ChatMCP](https://github.com/AI-QL/chat-mcp)** – 一个兼容 Linux、macOS 和 Windows 的开源跨平台 GUI 桌面应用程序，使用户能够无缝与 MCP 服务器进行交互，支持动态选择 LLM，由 **[AIQL](https://github.com/AI-QL)** 提供。
- **[ChatSum](https://github.com/mcpso/mcp-server-chatsum)** - 使用 LLM 查询和总结聊天消息。由 [mcpso](https://mcp.so) 提供。
- **[Chroma](https://github.com/privetin/chroma)** - 用于语义文档搜索和元数据过滤的向量数据库服务器，构建在 Chroma 上。
- **[ClaudePost](https://github.com/ZilongXue/claude-post)** - ClaudePost 使 Gmail 的电子邮件管理无缝，提供安全功能，如电子邮件搜索、阅读和发送。
- **[Cloudinary](https://github.com/felores/cloudinary-mcp-server)** - Cloudinary 模型上下文协议服务器，用于上传媒体到 Cloudinary 并返回媒体链接和详细信息。
- **[code-assistant](https://github.com/stippi/code-assistant)** - 一个编码助手 MCP 服务器，允许探索代码库并对代码进行更改。仅应与受信任的仓库一起使用（对提示注入的保护不足）。
- **[code-executor](https://github.com/bazinga012/mcp_code_executor)** - 一个允许 LLM 在指定的 Conda 环境中执行 Python 代码的 MCP 服务器。
- **[code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp)** - 一个 MCP 服务器，用于创建安全的代码沙箱环境，以在 Docker 容器中执行代码。
- **[cognee-mcp](https://github.com/topoteretes/cognee/tree/main/cognee-mcp)** - GraphRAG 内存服务器，具有可自定义的摄取、数据处理和搜索。
- **[coin_api_mcp](https://github.com/longmans/coin_api_mcp)** - 提供对 [coinmarketcap](https://coinmarketcap.com/) 加密货币数据的访问。
- **[Contentful-mcp](https://github.com/ivo-toby/contentful-mcp)** - 从此 MCP 服务器中读取、更新、删除、发布内容到 [Contentful](https://contentful.com) 空间。
- **[crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp)**  - 提供实时和历史的加密恐惧与贪婪指数数据。
- **[cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server)** - 为 AI 代理提供最新的加密货币新闻，由 CryptoPanic 提供支持。
- **[Dappier](https://github.com/DappierAI/dappier-mcp)** - 将 LLM 连接到来自可信来源的实时、权利清晰的专有数据。访问实时网络搜索、新闻、体育、金融数据、加密和优质出版商内容的专用模型。在 [marketplace.dappier.com](https://marketplace.dappier.com/marketplace) 探索数据模型。
- **[Databricks](https://github.com/JordiNeil/mcp-databricks-server)** - 允许 LLM 运行 SQL 查询，列出并获取 Databricks 帐户中作业执行的详细信息。
- **[Datadog](https://github.com/GeLi2001/datadog-mcp-server)** - Datadog MCP 服务器，用于应用程序跟踪、监控、仪表板、事件查询，基于官方 datadog api 构建。
- **[Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration)** - MCP 服务器，用于对基于 .csv 的数据集进行自主数据探索，提供智能洞察，尽可能少的努力。注意：将执行任意 Python 代码，请谨慎使用！
- **[Dataset Viewer](https://github.com/privetin/dataset-viewer)** - 浏览和分析 Hugging Face 数据集，具有搜索、过滤、统计和数据导出等功能。
- **[DBHub](https://github.com/bytebase/dbhub/)** - 通用数据库 MCP 服务器，连接到 MySQL、PostgreSQL、SQLite、DuckDB 等。
- **[DeepSeek MCP Server](https://github.com/DMontgomery40/deepseek-mcp-server)** - 集成 DeepSeek 的高级语言模型的模型上下文协议服务器，此外还有 [其他有用的 API 端点](https://github.com/DMontgomery40/deepseek-mcp-server?tab=readme-ov-file#features)。
- **[Deepseek_R1](https://github.com/66julienmartin/MCP-server-Deepseek_R1)** - 一个模型上下文协议 (MCP) 服务器实现，将 Claude Desktop 与 DeepSeek 的语言模型 (R1/V3) 连接起来。
- **[deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp)** - 一个 MCP (模型上下文协议) 提供者 Deepseek 推理内容到 MCP 启用的 AI 客户端，如 Claude Desktop。支持通过 Deepseek API 服务或本地 Ollama 服务器访问 Deepseek 的思维过程。
- **[Descope](https://github.com/descope-sample-apps/descope-mcp-server)** - 一个 MCP 服务器，与 [Descope](https://descope.com) 集成，搜索审计日志、管理用户等。
- **[DevRev](https://github.com/kpsunil97/devrev-mcp-server)** - 一个 MCP 服务器，与 DevRev API 集成，搜索 DevRev 知识图谱中的对象，可以从不同来源导入对象，列在 [这里](https://devrev.ai/docs/import#available-sources)。
- **[Dicom](https://github.com/ChristianHinge/dicom-mcp)** - 一个 MCP 服务器，用于查询和检索医学图像以及解析和读取 dicom 封装的文档（pdf 等）。
- **[Dify](https://github.com/YanxingLiu/dify-mcp-server)** - 一个简单的 MCP 服务器实现，用于 dify 工作流。
- **[Discord](https://github.com/v-3/discordmcp)** - 一个 MCP 服务器，通过机器人连接到 Discord 公会，并在频道中读取和写入消息。
- **[Discord](https://github.com/SaseQ/discord-mcp)** - 一个 MCP 服务器，通过机器人连接到 Discord，提供与 Discord 的全面集成。
- **[Discourse](https://github.com/AshDevFr/discourse-mcp-server)** - 一个 MCP 服务器，用于搜索 Discourse 论坛上的帖子。
- **[Docker](https://github.com/ckreiling/mcp-server-docker)** - 与 Docker 集成，以管理容器、映像、卷和网络。
- **[Drupal](https://github.com/Omedia/mcp-server-drupal)** - 使用 STDIO 传输层与 [Drupal](https://www.drupal.org/project/mcp) 进行交互的服务器。
- **[dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp)** - 一个 MCP 服务器，将 Dune Analytics 数据桥接到 AI 代理。
- **[EdgeOne Pages MCP](https://github.com/TencentEdgeOne/edgeone-pages-mcp)** - 一个 MCP 服务，用于将 HTML 内容部署到 EdgeOne Pages 并获取公开可访问的 URL。
- **[Elasticsearch](https://github.com/cr7258/elasticsearch-mcp-server)** - MCP 服务器实现，提供 Elasticsearch 交互。
- **[ElevenLabs](https://github.com/mamertofabian/elevenlabs-mcp-server)** - 一个与 ElevenLabs 文本转语音 API 集成的服务器，能够生成多种声音的完整配音。
- **[Ergo Blockchain MCP](https://github.com/marctheshark3/ergo-mcp)** - 一个 MCP 服务器，用于集成 Ergo 区块链节点和浏览器 API，以检查地址余额、分析交易、查看交易历史、进行地址的法医分析、搜索代币和监控网络状态。
- **[Eunomia](https://github.com/whataboutyou-ai/eunomia-MCP-server)** - Eunomia 框架的扩展，将 Eunomia 工具与 MCP 服务器连接。
- **[EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)** - 为 30 多个 EVM 网络提供全面的区块链服务，支持本地代币、ERC20、NFT、智能合约、交易和 ENS 解析。
- **[Everything Search](https://github.com/mamertofabian/mcp-everything-search)** - 跨 Windows（使用 [Everything SDK](https://www.voidtools.com/support/everything/sdk/)）、macOS（使用 mdfind 命令）和 Linux（使用 locate/plocate 命令）进行快速文件搜索的能力。
- **[Excel](https://github.com/haris-musa/excel-mcp-server)** - Excel 操作，包括数据读取/写入、工作表管理、格式化、图表和数据透视表。
- **[Fantasy PL](https://github.com/rishijatia/fantasy-pl-mcp)** - 让您的编码代理直接访问最新的 Fantasy Premier League 数据。
- **[fastn.ai – 统一 API MCP 服务器](https://github.com/fastnai/mcp-fastn)** - 一个远程动态 MCP 服务器，具有统一 API，连接到 1,000 多个工具、操作和工作流，具有内置身份验证和监控。
- **[Fetch](https://github.com/zcaceres/fetch-mcp)** - 一个灵活获取 HTML、JSON、Markdown 或纯文本的服务器。
- **[Fingertip](https://github.com/fingertip-com/fingertip-mcp)** - Fingertip.com 的 MCP 服务器，用于搜索和创建新网站。
- **[Figma](https://github.com/GLips/Figma-Context-MCP)** - 使您的编码代理直接访问 Figma 文件数据，帮助其一次性实现设计。
- **[Firebase](https://github.com/gannonh/firebase-mcp)** - 与 Firebase 服务（包括 Firebase 身份验证、Firestore 和 Firebase 存储）进行交互的服务器。
- **[FireCrawl](https://github.com/vrknetha/mcp-server-firecrawl)** - 具有 JavaScript 渲染、PDF 支持和智能速率限制的高级网络抓取。
- **[FlightRadar24](https://github.com/sunsetcoder/flightradar24-mcp-server)** - 一个 Claude Desktop MCP 服务器，帮助您使用 Flightradar24 数据实时跟踪航班。
- **[Ghost](https://github.com/MFYDev/ghost-mcp)** - 一个模型上下文协议 (MCP) 服务器，用于通过 LLM 接口与 Ghost CMS 进行交互。
- **[Github Actions](https://github.com/ko1ynnky/github-actions-mcp-server)** - 一个模型上下文协议 (MCP) 服务器，用于与 Github Actions 进行交互。
- **[Glean](https://github.com/longyi1207/glean-mcp-server)** - 一个使用 Glean API 进行搜索和聊天的服务器。
- **[Gmail](https://github.com/GongRzhe/Gmail-MCP-Server)** - 一个模型上下文协议 (MCP) 服务器，用于在 Claude Desktop 中集成 Gmail，支持自动身份验证。
- **[Gmail Headless](https://github.com/baryhuang/mcp-headless-gmail)** - 可远程托管的 MCP 服务器，可以在没有本地凭据或文件系统设置的情况下获取和发送 Gmail 消息。
- **[Goal Story](https://github.com/hichana/goalstory-mcp)** - 个人和职业发展的目标跟踪和可视化工具。
- **[GOAT](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol)** - 在任何区块链上运行超过 200 个链上操作，包括以太坊、Solana 和 Base。
- **[Godot](https://github.com/Coding-Solo/godot-mcp)** - 一个 MCP 服务器，提供全面的 Godot 引擎集成，用于项目编辑、调试和场景管理。
- **[Golang 文件系统服务器](https://github.com/mark3labs/mcp-filesystem-server)** - 使用 Go 构建的具有可配置访问控制的安全文件操作！
- **[Goodnews](https://github.com/VectorInstitute/mcp-goodnews)** - 一个简单的 MCP 服务器，提供策划的积极和鼓舞人心的新闻故事。
- **[Google Calendar](https://github.com/v-3/google-calendar)** - 与 Google 日历集成，检查日程、查找时间并添加/删除事件。
- **[Google Calendar](https://github.com/nspady/google-calendar-mcp)** - Google 日历 MCP 服务器，用于管理 Google 日历事件。还支持按标题和位置等属性搜索事件。
- **[Google Custom Search](https://github.com/adenot/mcp-google-search)** - 通过 Google 自定义搜索 API 提供 Google 搜索结果。
- **[Google Tasks](https://github.com/zcaceres/gtasks-mcp)** - Google Tasks API 模型上下文协议服务器。
- **[GraphQL Schema](https://github.com/hannesj/mcp-graphql-schema)** - 允许 LLM 探索大型 GraphQL 模式，而不会膨胀上下文。
- **[HDW LinkedIn](https://github.com/horizondatawave/hdw-mcp-server)** - 访问个人资料数据并管理用户帐户与 [HorizonDataWave.ai](https://horizondatawave.ai/)。
- **[Heurist Mesh Agent](https://github.com/heurist-network/heurist-mesh-mcp-server)** - 访问专门的 web3 AI 代理，用于区块链分析、智能合约安全、代币指标和通过 [Heurist Mesh network](https://github.com/heurist-network/heurist-agent-framework/tree/main/mesh) 进行区块链交互。
- **[Holaspirit](https://github.com/syucream/holaspirit-mcp-server)** - 与 [Holaspirit](https://www.holaspirit.com/) 进行交互。
- **[Home Assistant](https://github.com/tevonsb/homeassistant-mcp)** - 与 [Home Assistant](https://www.home-assistant.io/) 进行交互，包括查看和控制灯光、开关、传感器和所有其他 Home Assistant 实体。
- **[Home Assistant](https://github.com/voska/hass-mcp)** - 针对 Home Assistant 的 Docker 就绪 MCP 服务器，具有实体管理、域摘要、自动化支持和引导对话。包括预构建的容器映像以便于安装。
- **[HubSpot](https://github.com/buryhuang/mcp-hubspot)** - HubSpot CRM 集成，用于管理联系人和公司。通过 Claude 聊天直接创建和检索 CRM 数据。
- **[HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace)** - 用于使用 HuggingFace Spaces 的服务器，支持开源图像、音频、文本模型等。Claude Desktop 模式以便于集成。
- **[Hyperliquid](https://github.com/mektigboy/server-hyperliquid)** - 一个 MCP 服务器实现，集成 Hyperliquid SDK 以获取交易所数据。
- **[iFlytek Workflow](https://github.com/iflytek/ifly-workflow-mcp-server)** - 通过 MCP 服务器连接到 iFlytek 工作流并运行自己的代理。
- **[Image Generation](https://github.com/GongRzhe/Image-Generation-MCP-Server)** - 此 MCP 服务器提供使用 Replicate Flux 模型的图像生成能力。
- **[InfluxDB](https://github.com/idoru/influxdb-mcp-server)** - 针对 InfluxDB OSS API v2 运行查询。
- **[Inoyu](https://github.com/sergehuber/inoyu-mcp-unomi-server)** - 与 Apache Unomi CDP 客户数据平台进行交互，以检索和更新客户档案。
- **[Intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom)** - 一个符合 MCP 的服务器，用于从 Intercom 检索客户支持票据。此工具使 AI 助手（如 Claude Desktop 和 Cline）能够访问和分析您的 Intercom 支持票据。
- **[iOS Simulator](https://github.com/InditexTech/mcp-server-simulator-ios-idb)** - 一个模型上下文协议 (MCP) 服务器，使 LLM 能够通过自然语言命令与 iOS 模拟器（iPhone、iPad 等）进行交互。
- **[iTerm MCP](https://github.com/ferrislucas/iterm-mcp)** - 与 macOS 的 iTerm2 终端仿真器集成，使 LLM 能够执行和监控终端命令。
- **[JavaFX](https://github.com/mcpso/mcp-server-javafx)** - 使用 JavaFX 画布进行绘图。
- **[JDBC](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc)** - 连接到任何兼容 JDBC 的数据库，进行查询、插入、更新、删除等。支持 MySQL、PostgreSQL、Oracle、SQL Server、sqllite 等 [更多](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc#supported-jdbc-variants)。
- **[JSON](https://github.com/GongRzhe/JSON-MCP-Server)** - 具有使用 JSONPath 语法的高级查询能力和对数组、字符串、数字和日期操作支持的 JSON 处理和处理服务器。
- **[KiCad MCP](https://github.com/lamaalrajih/kicad-mcp)** - MCP 服务器，适用于 Mac、Windows 和 Linux。
- **[Keycloak MCP](https://github.com/ChristophEnglisch/keycloak-model-context-protocol)** - 此 MCP 服务器使用户能够与 Keycloak 进行自然语言交互，以进行用户和领域管理，包括创建、删除和列出用户和领域。
- **[Kibela](https://github.com/kiwamizamurai/mcp-kibela-server)** (by kiwamizamurai) - 与 Kibela API 进行交互。
- **[kintone](https://github.com/macrat/mcp-server-kintone)** - 通过 LLM 工具管理 [kintone](https://kintone.com) 中的记录和应用程序。
- **[Kong Konnect](https://github.com/Kong/mcp-konnect)** - 一个模型上下文协议 (MCP) 服务器，用于与 Kong Konnect API 进行交互，允许 AI 助手查询和分析 Kong 网关配置、流量和分析。
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** - 连接到 Kubernetes 集群并管理 pod、部署和服务。
- **[Kubernetes 和 OpenShift](https://github.com/manusa/kubernetes-mcp-server)** - 一个强大的 Kubernetes MCP 服务器，额外支持 OpenShift。除了为任何 Kubernetes 资源提供 CRUD 操作外，该服务器还提供与集群交互的专用工具。
- **[Langflow-DOC-QA-SERVER](https://github.com/GongRzhe/Langflow-DOC-QA-SERVER)** - 一个模型上下文协议服务器，用于由 Langflow 提供支持的文档问答。它通过提供简单的接口来查询文档，演示核心 MCP 概念。
- **[Lightdash](https://github.com/syucream/lightdash-mcp-server)** - 与 [Lightdash](https://www.lightdash.com/) 进行交互，这是一个 BI 工具。
- **[Linear](https://github.com/jerhadf/linear-mcp-server)** - 允许 LLM 与 Linear 的 API 进行交互，用于项目管理，包括搜索、创建和更新问题。
- **[Linear (Go)](https://github.com/geropl/linear-mcp-go)** - 允许 LLM 通过单个静态二进制文件与 Linear 的 API 进行交互。
- **[LINE](https://github.com/amornpan/py-mcp-line)** (by amornpan) - LINE Bot 集成的实现，使语言模型能够通过标准化接口读取和分析 LINE 对话。具有异步操作、全面日志记录、Webhook 事件处理和对各种消息类型的支持。
- **[LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud)** (by marcusschiesser) - 集成存储在 [LlamaCloud](https://cloud.llamaindex.ai/) 上的托管索引中的数据。
- **[llm-context](https://github.com/cyberchitta/llm-context.py)** - 提供一个仓库打包 MCP 工具，具有可配置的配置文件，指定文件包含/排除模式和可选提示。
- **[mac-messages-mcp](https://github.com/carterlasalle/mac_messages_mcp)** - 一个 MCP 服务器，通过模型上下文协议 (MCP) 安全地与您的 iMessage 数据库接口，允许 LLM 查询和分析 iMessage 对话。它包括强大的电话号码验证、附件处理、联系人管理、群聊处理和发送和接收消息的全面支持。
- **[MariaDB](https://github.com/abel9851/mcp-server-mariadb)** - MariaDB 数据库集成，具有可配置的访问控制，使用 Python 实现。
- **[Maton](https://github.com/maton-ai/agent-toolkit/tree/main/modelcontextprotocol)** - 连接到您的 SaaS 工具，如 HubSpot、Salesforce 等。
- **[MCP Compass](https://github.com/liuyoshio/mcp-compass)** - 为您的需求建议合适的 MCP 服务器。
- **[MCP Create](https://github.com/tesla0225/mcp-create)** - 一个动态 MCP 服务器管理服务，创建、运行和管理模型上下文协议服务器。
- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - 这是一个为您安装其他 MCP 服务器的服务器。
- **[mcp-k8s-go](https://github.com/strowk/mcp-k8s-go)** - 基于 Golang 的 Kubernetes 服务器，用于 MCP 浏览 pod 及其日志、事件、命名空间等。构建为可扩展。
- **[mcp-local-rag](https://github.com/nkapila6/mcp-local-rag)** - “原始” RAG 类似的网络搜索模型上下文协议 (MCP) 服务器，使用 Google 的 MediaPipe 文本嵌入器和 DuckDuckGo 搜索本地运行。✨ 无需 API ✨。
- **[mcp-proxy](https://github.com/sparfenyuk/mcp-proxy)** - 连接到运行在 SSE 传输上的 MCP 服务器，或将 stdio 服务器公开为 SSE 服务器。
- **[mem0-mcp](https://github.com/mem0ai/mem0-mcp)** - 一个模型上下文协议服务器，用于 Mem0，帮助管理编码偏好。
- **[MSSQL](https://github.com/aekanun2020/mcp-server/)** - MSSQL 数据库集成，具有可配置的访问控制和模式检查。
- **[MSSQL](https://github.com/JexinSam/mssql_mcp_server)** (by jexin) - 用于 MSSQL 数据库的 MCP 服务器。
- **[MSSQL-Python](https://github.com/amornpan/py-mcp-mssql)** (by amornpan) - MSSQL 数据库访问的只读 Python 实现，具有增强的安全功能、可配置的访问控制和模式检查能力。专注于通过 Python 生态系统安全地与数据库交互。
- **[MSSQL-MCP](https://github.com/daobataotie/mssql-mcp)** (by daobataotie) - MSSQL MCP，参考官方网页的 SQLite MCP 进行修改以适应 MSSQL。
- **[Markdownify](https://github.com/zcaceres/mcp-markdownify-server)** - MCP 将几乎任何内容转换为 Markdown（PPTX、HTML、PDF、Youtube 转录等）。
- **[Microsoft Teams](https://github.com/InditexTech/mcp-teams-server)** - MCP 服务器，集成 Microsoft Teams 消息（读取、发布、提及、列出成员和线程）。
- **[Mindmap](https://github.com/YuChenSSR/mindmap-mcp-server)** (by YuChenSSR) - 一个从包含 markdown 代码的输入生成思维导图的服务器。
- **[Minima](https://github.com/dmayboroda/minima)** - 用于本地文件的 RAG 的 MCP 服务器。
- **[Mobile MCP](https://github.com/mobile-next/mobile-mcp)** (by Mobile Next) - MCP 服务器，用于移动（iOS/Android）自动化、应用抓取和开发，使用物理设备或模拟器/仿真器。
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** - 一个模型上下文协议服务器，用于 MongoDB。
- **[MongoDB Lens](https://github.com/furey/mongodb-lens)** - 功能齐全的 MCP 服务器，用于 MongoDB 数据库。
- **[Monday.com](https://github.com/sakce/mcp-server-monday)** - MCP 服务器，用于与 Monday.com 板和项目进行交互。
- **[Multicluster-MCP-Sever](https://github.com/yanmxa/multicluster-mcp-server)** - GenAI 系统与多个 Kubernetes 集群交互的网关。
- **[MySQL](https://github.com/benborla/mcp-server-mysql)** (by benborla) - MySQL 数据库集成，使用 NodeJS，具有可配置的访问控制和模式检查。
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** (by DesignComputer) - MySQL 数据库集成，使用 Python，具有可配置的访问控制和模式检查。
- **[n8n](https://github.com/leonardsellem/n8n-mcp-server)** - 此 MCP 服务器为 AI 助手提供工具和资源，以管理 n8n 工作流和执行，包括列出、创建、更新和删除工作流，以及监控其执行状态。
- **[NASA](https://github.com/ProgramComputer/NASA-MCP-server)** (by ProgramComputer) - 访问 NASA 数据源的统一网关，包括但不限于 APOD、NEO、EPIC、GIBS。
- **[Nasdaq Data Link](https://github.com/stefanoamorelli/nasdaq-data-link-mcp)** (by stefanoamorelli) - 一个 MCP 服务器，用于访问、探索和与 Nasdaq Data Link 的广泛和有价值的金融和经济数据集进行交互。
- **[National Parks](https://github.com/KyrieTangSheng/mcp-server-nationalparks)** - 该服务器提供美国国家公园的最新信息，包括公园详情、警报、游客中心、露营地、徒步旅行路线和活动。
- **[NAVER](https://github.com/pfldy2850/py-mcp-naver)** (by pfldy2850) - 此 MCP 服务器提供与各种 Naver 服务的工具，例如搜索博客、新闻、书籍等。
- **[NS Travel Information](https://github.com/r-huijts/ns-mcp-server)** - 通过官方 NS API 访问荷兰铁路 (NS) 实时火车旅行信息和中断。
- **[Neo4j](https://github.com/da-okazaki/mcp-neo4j-server)** - 一个社区构建的服务器，与 Neo4j 图数据库进行交互。
- **[Neovim](https://github.com/bigcodegen/mcp-neovim-server)** - 一个 MCP 服务器，用于您的 Neovim 会话。
- **[Notion](https://github.com/suekou/mcp-notion-server)** (by suekou) - 与 Notion API 进行交互。
- **[Notion](https://github.com/v-3/notion-server)** (by v-3) - Notion MCP 集成。通过 Claude 聊天搜索、读取、更新和创建页面。
- **[ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp)** (by teddyzxcv) - 该 MCP 服务器通过 ntfy 向您的设备发送通知，让您保持信息灵通。
- **[oatpp-mcp](https://github.com/oatpp/oatpp-mcp)** - C++ MCP 集成，用于 Oat++。使用 [Oat++](https://oatpp.io) 构建 MCP 服务器。
- **[Obsidian Markdown Notes](https://github.com/calclavia/mcp-obsidian)** - 浏览和搜索您的 Obsidian 保险库或任何包含 Markdown 笔记的目录。
- **[obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp)** - (by Steven Stavrakis) 一个用于 Obsidian.md 的 MCP 服务器，提供搜索、读取、写入和组织笔记的工具。
- **[OceanBase](https://github.com/yuanoOo/oceanbase_mcp_server)** - (by yuanoOo) 一个模型上下文协议 (MCP) 服务器，允许安全地与 OceanBase 数据库进行交互。
- **[Okta](https://github.com/kapilduraphe/okta-mcp-server)** - 与 Okta API 进行交互。
- **[OneNote](https://github.com/rajvirtual/MCP-Servers/tree/master/onenote)** - (by Rajesh Vijay) 一个与 Microsoft Graph API 连接的 MCP 服务器。读取 OneNote 中的笔记本、部分和页面，在 OneNote 中创建新的笔记本、部分和页面。
- **[OpenAI WebSearch MCP](https://github.com/ConechoAI/openai-websearch-mcp)** - 这是一个基于 Python 的 MCP 服务器，提供 OpenAI `web_search` 内置工具。
- **[OpenAPI](https://github.com/snaggle-ai/openapi-mcp-server)** - 与 [OpenAPI](https://www.openapis.org/) API 进行交互。
- **[OpenAPI AnyApi](https://github.com/baryhuang/mcp-server-any-openapi)** - 使用内置的端点语义搜索与大型 [OpenAPI](https://www.openapis.org/) 文档进行交互。允许自定义 MCP 服务器前缀。
- **[OpenAPI Schema](https://github.com/hannesj/mcp-openapi-schema)** - 允许 LLM 探索大型 [OpenAPI](https://www.openapis.org/) 模式，而不会膨胀上下文。
- **[OpenCTI](https://github.com/Spathodea-Network/opencti-mcp)** - 与 OpenCTI 平台进行交互，以检索威胁情报数据，包括报告、指标、恶意软件和威胁行为者。
- **[OpenDota](https://github.com/asusevski/opendota-mcp-server)** - 与 OpenDota API 进行交互，以检索 Dota 2 比赛数据、玩家统计等。
- **[OpenRPC](https://github.com/shanejonas/openrpc-mpc-server)** - 通过 [OpenRPC](https://open-rpc.org) 进行交互和发现 JSON-RPC API。
- **[Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools)** - 产品营销的内容编辑代码、价值图和定位工具。
- **[Pandoc](https://github.com/vivekVells/mcp-pandoc)** - MCP 服务器，用于使用 Pandoc 进行无缝
- **[PIF](https://github.com/hungryrobot1/MCP-PIF)** - 个人智能框架 (PIF)，提供文件操作、结构化推理和基于日志的文档记录工具，以支持跨会话的人机协作的连续性和演变。
- **[Pinecone](https://github.com/sirmews/mcp-pinecone)** - MCP 服务器，用于搜索和上传记录到 Pinecone。允许简单的 RAG 功能，利用 Pinecone 的推理 API。
- **[Placid.app](https://github.com/felores/placid-mcp-server)** - 使用 Placid.app 模板生成图像和视频创意的 MCP 服务器。
- **[Playwright](https://github.com/executeautomation/mcp-playwright)** - 此 MCP 服务器将帮助您使用 Playwright 运行浏览器自动化和网络抓取。
- **[Postman](https://github.com/shannonlal/mcp-postman)** - MCP 服务器，用于通过 Newman 在本地运行 Postman 集合。允许简单执行 Postman 服务器并返回集合是否通过所有测试的结果。
- **[Productboard](https://github.com/kenjihikmatullah/productboard-mcp)** - 通过 MCP 将 Productboard API 集成到代理工作流中。
- **[Prometheus](https://github.com/pab1it0/prometheus-mcp-server)** - 查询和分析 Prometheus - 开源监控系统。
- **[Pulumi](https://github.com/dogukanakkaya/pulumi-mcp-server)** - MCP 服务器，用于与 Pulumi API 交互，创建和列出堆栈。
- **[Pushover](https://github.com/ashiknesin/pushover-mcp)** - 使用 [Pushover.net](https://pushover.net/) 向您的设备发送即时通知。
- **[QGIS](https://github.com/jjsantos01/qgis_mcp)** - 将 QGIS 连接到 Claude AI，通过 MCP 进行交互。此集成支持提示辅助项目创建、图层加载、代码执行等。
- **[QuickChart](https://github.com/GongRzhe/Quickchart-MCP-Server)** - 一个模型上下文协议服务器，用于使用 QuickChart.io 生成图表。
- **[Qwen_Max](https://github.com/66julienmartin/MCP-server-Qwen_Max)** - 一个模型上下文协议 (MCP) 服务器实现，适用于 Qwen 模型。
- **[RabbitMQ](https://github.com/kenliao94/mcp-server-rabbitmq)** - 与 RabbitMQ 交互的 MCP 服务器，用于发布和消费消息。
- **[RAG Web Browser](https://github.com/apify/mcp-server-rag-web-browser)** - 一个 MCP 服务器，用于 Apify 的开源 RAG Web 浏览器 [Actor](https://apify.com/apify/rag-web-browser)，执行网络搜索、抓取 URL，并以 Markdown 格式返回内容。
- **[Reaper](https://github.com/dschuler36/reaper-mcp-server)** - 与您的 [Reaper](https://www.reaper.fm/) (数字音频工作站) 项目进行交互。
- **[Redis](https://github.com/GongRzhe/REDIS-MCP-Server)** - Redis 数据库操作和缓存微服务服务器，支持键值操作、过期管理和基于模式的键列出。
- **[Redis](https://github.com/prajwalnayak7/mcp-server-redis)** - MCP 服务器，用于与 Redis 服务器、AWS Memory DB 等进行交互，适用于缓存或其他使用内存和键值存储的用例。
- **[Rememberizer AI](https://github.com/skydeckai/mcp-server-rememberizer)** - 一个 MCP 服务器，旨在与 Rememberizer 数据源进行交互，促进增强的知识检索。
- **[Replicate](https://github.com/deepfates/mcp-replicate)** - 在 Replicate 上搜索、运行和管理机器学习模型，通过简单的工具界面。浏览模型、创建预测、跟踪其状态并处理生成的图像。
- **[Rquest](https://github.com/xxxbrian/mcp-rquest)** - 一个 MCP 服务器，提供逼真的浏览器式 HTTP 请求能力，具有准确的 TLS/JA3/JA4 指纹，以绕过反机器人措施。
- **[Rijksmuseum](https://github.com/r-huijts/rijksmuseum-mcp)** - 与 Rijksmuseum API 接口，搜索艺术品、检索艺术品详情、访问图像切片和探索用户收藏。
- **[Salesforce MCP](https://github.com/smn2gnt/MCP-Salesforce)** - 与 Salesforce 数据和元数据进行交互。
- **[Scholarly](https://github.com/adityak74/mcp-scholarly)** - 一个 MCP 服务器，用于搜索学术和科研文章。
- **[scrapling-fetch](https://github.com/cyberchitta/scrapling-fetch-mcp)** - 从受机器人保护的网站访问文本内容。使用 Scrapling 从具有反自动化措施的网站抓取 HTML/Markdown。
- **[SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng)** - 一个模型上下文协议服务器，用于 [SearXNG](https://docs.searxng.org)。
- **[ServiceNow](https://github.com/osomai/servicenow-mcp)** - 一个 MCP 服务器，用于与 ServiceNow 实例进行交互。
- **[Shopify](https://github.com/GeLi2001/shopify-mcp)** - MCP 用于与 Shopify API 进行交互，包括订单、产品、客户等。
- **[Siri Shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts)** - MCP 用于与 macOS 上的 Siri Shortcuts 进行交互。将所有快捷方式公开为 MCP 工具。
- **[Snowflake](https://github.com/isaacwasserman/mcp-snowflake-server)** - 此 MCP 服务器使 LLM 能够与 Snowflake 数据库进行交互，允许安全和受控的数据操作。
- **[Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server)** - 此 MCP 服务器使 LLM 能够与 Solana 区块链进行交互，借助 Solana Agent Kit 提供 40 多个协议操作，且数量不断增加。
- **[Spotify](https://github.com/varunneal/spotify-mcp)** - 此 MCP 允许 LLM 播放和使用 Spotify。
- **[Starwind UI](https://github.com/Boston343/starwind-ui-mcp/)** - 此 MCP 提供相关命令、文档和其他信息，以便 LLM 充分利用 Starwind UI 的开源 Astro 组件。
- **[Stripe](https://github.com/atharvagupta2003/mcp-stripe)** - 此 MCP 允许与 Stripe 集成，以处理支付、客户和退款。
- **[ShaderToy](https://github.com/wilsonchenghy/ShaderToy-MCP)** - 此 MCP 服务器使 LLM 能够与 ShaderToy API 进行交互，允许 LLM 从计算着色器示例中学习，并使其能够创建以前无法实现的复杂 GLSL 着色器。
- **[TMDB](https://github.com/Laksh-star/mcp-server-tmdb)** - 此 MCP 服务器与电影数据库 (TMDB) API 集成，提供电影信息、搜索功能和推荐。
- **[Tavily search](https://github.com/RamXX/mcp-tavily)** - 一个用于 Tavily 的搜索和新闻 API 的 MCP 服务器，具有明确的站点包含/排除。
- <img height="12" width="12" src="https://www.zapier.com/favicon.ico" alt="Zapier Logo" /> **[Telegram](https://github.com/chigwell/telegram-mcp)** - 一个 MCP 服务器，提供分页聊天读取、消息检索和消息发送功能，通过 Telethon 集成。
- **[Terminal-Control](https://github.com/GongRzhe/terminal-controller-mcp)** - 一个 MCP 服务器，使安全的终端命令执行、目录导航和文件系统操作通过标准化接口成为可能。
- **[TFT-Match-Analyzer](https://github.com/GeLi2001/tft-mcp-server)** - MCP 服务器，用于团队战术比赛历史和比赛详情获取，为用户提供每场比赛的详细上下文。
- **[Ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster)** - 通过 Ticketmaster Discovery API 搜索事件、场馆和景点。
- **[Todoist](https://github.com/abhiz123/todoist-mcp-server)** - 与 Todoist 进行交互以管理您的任务。
- **[Typesense](https://github.com/suhail-ak-s/mcp-typesense-server)** - 一个模型上下文协议 (MCP) 服务器实现，提供 AI 模型访问 Typesense 搜索功能。此服务器使 LLM 能够发现、搜索和分析存储在 Typesense 集合中的数据。
- **[Travel Planner](https://github.com/GongRzhe/TRAVEL-PLANNER-MCP-Server)** - 旅行规划和行程管理服务器，集成 Google Maps API 进行位置搜索、地点详情和路线计算。
- **[Unity Catalog](https://github.com/ognis1205/mcp-server-unitycatalog)** - 一个 MCP 服务器，使 LLM 能够与 Unity Catalog AI 进行交互，支持对 Unity Catalog 函数的 CRUD 操作并将其作为 MCP 工具执行。
- **[Unity3d Game Engine](https://github.com/CoderGamester/mcp-unity)** - 一个 MCP 服务器，使 LLM 能够与 Unity3d 游戏引擎进行交互，支持访问各种 Unity 编辑器引擎工具（例如控制台日志、测试运行器日志、编辑器功能、层次状态等）并将其作为 MCP 工具执行或收集它们作为资源。
- **[Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)** - 从获取的数据生成可视化，使用 VegaLite 格式和渲染器。
- **[Video Editor](https://github.com/burningion/video-editing-mcp)** - 一个模型上下文协议服务器，用于添加、编辑和搜索与 [Video Jungle](https://www.video-jungle.com/) 相关的视频。
- **[Virtual location (Google Street View,etc.)](https://github.com/mfukushim/map-traveler-mcp)** - 集成 Google 地图、Google 街景、PixAI、Stability.ai、ComfyUI API 和 Bluesky，以在 LLM 中提供虚拟位置模拟（用 Effect.ts 编写）。
- **[VolcEngine TOS](https://github.com/dinghuazhou/sample-mcp-server-tos)** - 一个用于 VolcEngine TOS 的示例 MCP 服务器，灵活地从 TOS 获取对象。
- **[Wanaku MCP Router](https://github.com/wanaku-ai/wanaku/)** - Wanaku MCP 路由器是一个基于 SSE 的 MCP 服务器，提供一个可扩展的路由引擎，允许将您的企业系统与 AI 代理集成。
- **[Webflow](https://github.com/kapilduraphe/webflow-mcp-server)** - 与 Webflow API 进行交互。
- **[whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp)**  - 一个用于跟踪加密货币鲸鱼交易的 MCP 服务器。
- **[Whois MCP](https://github.com/bharathvaj-ganesan/whois-mcp)** - MCP 服务器，对域、IP、ASN 和 TLD 执行 whois 查找。
- **[Wikidata MCP](https://github.com/zzaebok/mcp-wikidata)** - 与 Wikidata 进行交互的 Wikidata MCP 服务器，通过搜索标识符、提取元数据和执行 sparql 查询。
- **[WildFly MCP](https://github.com/wildfly-extras/wildfly-mcp)** - WildFly MCP 服务器，使 LLM 能够与运行中的 WildFly 服务器进行交互（检索指标、日志、调用操作等）。
- **[Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)** - 用于在 Windows 系统上进行安全命令行交互的 MCP 服务器，允许对 PowerShell、CMD 和 Git Bash shell 的受控访问。
- **[World Bank data API](https://github.com/anshumax/world_bank_mcp_server)** - 一个从世界银行数据 API 获取可用数据指标的服务器。
- **[X (Twitter)](https://github.com/EnesCinr/twitter-mcp)** (by EnesCinr) - 与 Twitter API 进行交互。发布推文并按查询搜索推文。
- **[X (Twitter)](https://github.com/vidhupv/x-mcp)** (by vidhupv) - 直接通过 Claude 聊天创建、管理和发布 X/Twitter 帖子。
- **[xcodebuild](https://github.com/ShenghaiWang/xcodebuild)**  - 🍎 构建 iOS Xcode 工作区/项目并将错误反馈给 llm。
- **[Xero-mcp-server](https://github.com/john-zhang-dev/xero-mcp)** - 使客户能够与 Xero 系统进行交互，以简化会计、发票和业务操作。
- **[XiYan](https://github.com/XGenerationLab/xiyan_mcp_server)** - 🗄️ 一个 MCP 服务器，支持使用自然语言查询从数据库中获取数据，由 XiyanSQL 作为文本到 SQL 的 LLM 提供支持。
- **[XMind](https://github.com/apeyroux/mcp-xmind)** - 浏览和搜索您的 XMind 目录，包含 XMind 文件。
- **[YouTube](https://github.com/ZubeidHendricks/youtube-mcp-server)** - 综合 YouTube API 集成，用于视频管理、短视频创建和分析。

## 📚 框架

这些是高层框架，使构建 MCP 服务器或客户端变得更容易。

### 服务器

* **[EasyMCP](https://github.com/zcaceres/easy-mcp/)** (TypeScript)
- **[FastAPI to MCP auto generator](https://github.com/tadata-org/fastapi_mcp)** – 一个零配置工具，用于自动将 FastAPI 端点公开为 MCP 工具，由 **[Tadata](https://tadata.com/)** 提供。
* **[FastMCP](https://github.com/punkpeye/fastmcp)** (TypeScript)
* **[Foxy Contexts](https://github.com/strowk/foxy-contexts)** – 一个用于构建 Golang 中的 MCP 服务器的库，由 **[strowk](https://github.com/strowk)** 提供。
* **[Higress MCP Server Hosting](https://github.com/alibaba/higress/tree/main/plugins/wasm-go/mcp-servers)** - 一个通过 wasm 插件扩展 API 网关来托管 MCP 服务器的解决方案（基于 Envoy）。
* **[MCP-Framework](https://mcp-framework.com)** 使用优雅和快速构建 MCP 服务器。带有 CLI，可使用 `mcp create app` 创建项目。5 分钟内开始您的第一个服务器，由 **[Alex Andru](https://github.com/QuantGeekDev)** 提供。
* **[Quarkus MCP Server SDK](https://github.com/quarkiverse/quarkus-mcp-server)** (Java)
* **[Template MCP Server](https://github.com/mcpdotdirect/template-mcp-server)** - 一个 CLI 工具，用于创建新的模型上下文协议服务器项目，支持 TypeScript，双传输选项和可扩展结构。

### 客户端

* **[codemirror-mcp](https://github.com/marimo-team/codemirror-mcp)** - CodeMirror 扩展，实现模型上下文协议 (MCP)，用于资源提及和提示命令。

## 🚀 开始使用

### 使用本仓库中的 MCP 服务器
本仓库中的基于 TypeScript 的服务器可以直接使用 `npx`。

例如，这将启动 [Memory](src/memory) 服务器：
```sh
npx -y @modelcontextprotocol/server-memory
```

本仓库中的基于 Python 的服务器可以直接使用 [`uvx`](https://docs.astral.sh/uv/concepts/tools/) 或 [`pip`](https://pypi.org/project/pip/)。推荐使用 `uvx` 以便于使用和设置。

例如，这将启动 [Git](src/git) 服务器：
```sh
# 使用 uvx
uvx mcp-server-git

# 使用 pip
pip install mcp-server-git
python -m mcp_server_git
```

按照 [这些](https://docs.astral.sh/uv/getting-started/installation/) 指示安装 `uv` / `uvx` 和 [这些](https://pip.pypa.io/en/stable/installation/) 指示安装 `pip`。

### 使用 MCP 客户端
然而，单独运行服务器并没有太大用处，应该将其配置到 MCP 客户端中。例如，以下是 Claude Desktop 配置以使用上述服务器：

```json
{
  "mcpServers": {
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```

使用 Claude Desktop 作为 MCP 客户端的其他示例可能如下所示：

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/allowed/files"]
    },
    "git": {
      "command": "uvx",
      "args": ["mcp-server-git", "--repository", "path/to/git/repo"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "<YOUR_TOKEN>"
      }
    },
    "postgres": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-postgres", "postgresql://localhost/mydb"]
    }
  }
}
```

## 🛠️ 创建您自己的服务器

有兴趣创建自己的 MCP 服务器吗？请访问官方文档 [modelcontextprotocol.io](https://modelcontextprotocol.io/introduction)，获取有关实现 MCP 服务器的全面指南、最佳实践和技术细节。

## 🤝 贡献

请参阅 [CONTRIBUTING.md](CONTRIBUTING.md)，了解有关为本仓库做出贡献的信息。

## 🔒 安全

请参阅 [SECURITY.md](SECURITY.md)，以报告安全漏洞。

## 📜 许可证

本项目根据 MIT 许可证进行许可 - 请参阅 [LICENSE](LICENSE) 文件以获取详细信息。

## 💬 社区

- [GitHub 讨论](https://github.com/orgs/modelcontextprotocol/discussions)

## ⭐ 支持

如果您发现 MCP 服务器有用，请考虑给本仓库加星并贡献新的服务器或改进！


接下来，我将把这些翻译后的内容写入 `readme-cn.md` 文件中。请稍等。
