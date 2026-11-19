# Awesome-AI-Long-Term-Memory-Knowledge-Retrieval

## Top AI Long-Term Memory & Knowledge Retrieval Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Persistent Agent Memory, Spatial/Palace Memory Architectures, Temporal Knowledge Graphs, Hybrid Vector/Graph Retrieval & Semantic Caching*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Long-Term Memory & Knowledge Retrieval**. These tools equip autonomous AI agents and assistants with persistent cross-session recall, episodic/semantic/procedural memory layers, structured knowledge palaces and temporal graphs, hybrid retrieval engines, and low-latency semantic caches.



**Examples** include Mem0, Zep, LangMem, Letta Platform, Graphlit, Pinecone, Qdrant Cloud, Redis LangCache, Weaviate, Ragie, and MemPalace/mempalace (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for structured spatial/palace memory systems (`MemPalace`), self-hosted hierarchical memory runtimes (`Letta`, `Mem0`, `MemOS`), temporal & GraphRAG knowledge engines (`Graphiti`, `LightRAG`, `Cognee`, `Microsoft GraphRAG`), local-first MCP memory servers, and high-speed vector/graph stores — ideal for AI engineers, cognitive architecture researchers, and developers building stateful, context-retaining systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The AI long-term memory, vector database, and retrieval infrastructure market is estimated at **$3.1B–$3.6B in 2026** and projected to expand past **$8B+ by 2030** (~23–27% CAGR) as autonomous agent workflows mandate persistent, stateful context. The sector is **moderately fragmented** among specialized managed memory/graph services and pure-play vector engines, but is progressively consolidating around dominant cloud database incumbents and major developer orchestration platforms.

## SaaS/Hosted Platforms

| Platform | Company Scale (Valuation / Revenue) | Starting Paid Pricing | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[LangMem / LangGraph Cloud (LangChain)](https://langchain.com)** | **$3.0B valuation** ($460M total funding) | **$39 / seat / month** (Plus Plan) | **5,000 base traces/month**, 1 user seat, 14-day retention, 1 developer LangGraph deployment | Managed persistence and long-term semantic, episodic, and procedural memory infrastructure integrated natively with LangGraph state checkpoints. |
| **[Redis Cloud & Redis LangCache](https://redis.io)** | **$2.0B valuation** (> $300M ARR) | **$5.00 / month** ($0.007/hr, Essentials Plan) | **30 MB RAM storage**, 30 concurrent connections, 5 GB monthly bandwidth, 100 ops/sec max throughput | Managed in-memory data store and semantic caching service engineered for ultra-low-latency short-term agent state, session checkpoints, and LLM response caching. |
| **[Pinecone](https://pinecone.io)** | **$750M valuation** ($138M total funding) | **$50.00 / month** minimum commitment (Standard Plan) | **2 GB storage** (~300k vectors @ 1536d), 1M read units/mo, 2M write units/mo, 5 serverless indexes, 1 GB egress/mo | Fully managed serverless vector database widely used as a high-throughput semantic long-term memory and knowledge retrieval store for production AI agents. |
| **[Weaviate Cloud](https://weaviate.io)** | **$200M valuation** ($67.7M total funding) | **$45.00 / month** (Flex Serverless Plan) | **100,000 objects**, 1 GB RAM / 10 GB disk, 1 collection (up to 3 tenants) | Managed AI-native vector database offering hybrid keyword/semantic search, generative feedback loops, and multi-tenancy for agent memory persistence. |
| **[Qdrant Cloud](https://qdrant.tech)** | **~$113M estimated valuation** ($37.8M total funding) | **$25.00 / month** (Standard 1GB Dedicated Cluster) | **4 GB disk storage**, 1 GB RAM, 0.5 vCPU (~1M vectors @ 768d, single-node cluster) | Managed high-performance vector search and semantic caching cloud built in Rust for multi-tenant agent memory, hybrid search, and context retrieval. |
| **[Letta Platform (Letta Cloud)](https://letta.com)** | **$70M valuation** ($10M total funding) | **$20.00 / month** (Pro Plan; includes $20 usage credits) | **3 stateful agents** (BYOK for LLM inference calls) | Managed stateful agent runtime built around MemGPT principles for self-editing hierarchical memory, perpetual learning, and long-running context persistence. |
| **[Mem0 Platform](https://mem0.ai)** | **$24.5M total funding** (Series A stage) | **$19.00 / month** (Starter Tier / base overage threshold) | **10,000 adds & 1,000 retrievals/mo** (first 30 days managed); **50,000 adds & 10,000 retrievals/mo** thereafter with BYOK | Managed cloud memory layer for personalized AI agents offering automatic fact extraction, multi-level user/session/agent scoping, and low-latency recall APIs. |
| **[Ragie](https://ragie.ai)** | **$5.5M total funding** (Seed stage) | **$100.00 / month** (Starter Plan) | **1,000 pages**, 1,000 retrievals, 10 GB streaming, 10 hours audio/video processing | Fully managed RAG-as-a-Service and knowledge retrieval platform providing automated document chunking, entity extraction, and hybrid search APIs for AI agents. |
| **[Graphlit](https://graphlit.com)** | **$3.56M total funding** (Seed stage) | **$49.00 / month** (Paid Plan base) | **1 GB content storage** ($0 developer credits plan) | Cloud-native multimodal knowledge-graph and RAG memory platform for ingesting, indexing, and querying conversations, documents, and media for AI agents. |
| **[Zep Cloud](https://getzep.com)** | **~$2.3M total funding** (Seed stage) | **$125.00 / month** (Flex Plan, 50,000 credits) | **10,000 credits/month** (Prototyping free tier, 1 credit ~ 350 bytes ingested) | Enterprise agent memory and context engineering platform powered by temporal knowledge graphs that continuously synthesize user interactions and business data. |





## Open-Source GitHub Projects



- **[MemPalace (`MemPalace/mempalace`)](https://github.com)**  

  Open-source structured AI memory system inspired by the classical Method of Loci ("Memory Palace"), organizing long-term agent knowledge, facts, and retrieval cues into navigable spatial hierarchies for high-recall persistence.



- **[Mem0 (`mem0ai/mem0`)](https://github.com)**  

  Open-source (`Apache-2.0`) universal memory layer for AI agents combining vector, graph, and key-value stores to dynamically extract, update, and retrieve user and session memories.



- **[Letta (formerly MemGPT)](https://github.com)**  

  Open-source (`Apache-2.0`) stateful agent framework and server equipping LLMs with self-editing core/archival/recall memory tiers and persistent daemon execution.



- **[Graphiti (`getzep/graphiti`)](https://github.com)**  

  Open-source (`Apache-2.0`) temporal knowledge-graph memory framework from Zep engineered for real-time incremental updates, bi-temporal entity tracking, and hybrid graph/vector agent recall.



- **[LangMem (`langchain-ai/langmem`)](https://github.com)**  

  Open-source (`MIT`) SDK from LangChain helping agents learn and adapt over time by extracting semantic facts, episodic experiences, and procedural rules into persistent stores.



- **[Cognee (`topoteretes/cognee`)](https://github.com)**  

  Open-source (`Apache-2.0`) deterministic AI memory engine that transforms raw documents and agent conversations into interconnected graph-and-vector knowledge pipelines.



- **[MemOS (`MemTensor/MemOS`)](https://github.com)**  

  Open-source Memory Operating System for LLMs providing unified scheduling, lifecycle management, and cross-session persistence across parametric, activation, and plaintext memory.



- **[Microsoft GraphRAG (`microsoft/graphrag`)](https://github.com)**  

  Open-source (`MIT`) modular graph-based knowledge retrieval system from Microsoft Research that extracts entity graphs and hierarchical community summaries for multi-hop reasoning.



- **[LightRAG (`HKUDS/LightRAG`)](https://github.com)**  

  Fast, lightweight open-source (`MIT`) graph-augmented knowledge retrieval framework offering dual-level entity/relation indexing and incremental updates at low token overhead.



- **[Basic Memory (`basicmachines-co/basic-memory`)](https://github.com)**  

  Local-first open-source (`AGPL-3.0`) MCP server that persists AI conversations and agent knowledge as bidirectional Markdown files synced with a local SQLite semantic graph.



- **[thedotmack/claude-mem](https://github.com)**  

  Popular open-source persistent memory plugin and MCP server for Claude Code that captures tool-use observations, compresses them into semantic summaries, and injects relevant historical context across sessions.



- **[Memori (`GibsonAI/Memori`)](https://github.com)**  

  Open-source (`Apache-2.0`) SQL-native memory engine enabling any LLM or agent framework to record, query, and persist structured episodic and semantic memories in standard relational databases.



- **[Qdrant (`qdrant/qdrant`)](https://github.com)**  

  Open-source (`Apache-2.0`) high-performance vector search engine and semantic caching backend written in Rust with rich payload filtering for long-term agent memory.



- **[Weaviate (`weaviate/weaviate`)](https://github.com)**  

  Open-source (`BSD-3-Clause`) cloud-native vector database featuring hybrid BM25 + vector search, multi-tenancy, and modular vectorizer integrations for persistent agent recall.



- **[Milvus (`milvus-io/milvus`)](https://github.com)**  

  Scalable open-source (`Apache-2.0`) distributed vector database engineered for billion-scale semantic search, hybrid retrieval, and enterprise knowledge-base workloads.



- **[LanceDB (`lancedb/lancedb`)](https://github.com)**  

  Embedded, serverless open-source (`Apache-2.0`) multimodal vector database built on the Lance columnar format for zero-config local agent memory and retrieval.



- **[GPTCache (`zilliztech/GPTCache`)](https://github.com)**  

  Open-source (`MIT`) semantic caching library for LLMs and agents that stores and retrieves semantically similar queries to slash latency and token costs.



- **[Khoj (`khoj-ai/khoj`)](https://github.com)**  

  Self-hostable open-source (`AGPL-3.0`) personal AI second-brain and knowledge retrieval engine indexing Markdown, PDFs, Notion, and GitHub for grounded recall.



### Additional Strong Open-Source Options



- **[OpenMemory / MCP Memory Server (`modelcontextprotocol/servers`)](https://github.com)** for the official Model Context Protocol knowledge-graph memory server enabling local entity and relation persistence.

- **[A-MEM (`agiresearch/A-mem`)](https://github.com)** and **[HippoRAG (`OSU-NLP-Group/HippoRAG`)](https://github.com)** for neurobiologically inspired hippocampal indexing and Zettelkasten-style dynamic memory networks.

- **[Neo4j (`neo4j/neo4j`)](https://github.com)** and **[FalkorDB (`FalkorDB/FalkorDB`)](https://github.com)** for low-latency property-graph databases powering GraphRAG and multi-hop relational knowledge retrieval.

- **[PostgreSQL + pgvector (`pgvector/pgvector`)](https://github.com)** and **[SQLite-vec (`asg017/sqlite-vec`)](https://github.com)** for ACID-compliant relational + vector memory storage in a single database.

- **[Valkey (`valkey-io/valkey`)](https://github.com)** and **[Chroma (`chroma-core/chroma`)](https://github.com)** for ultra-fast open-source in-memory semantic caching and embedded local vector retrieval.
