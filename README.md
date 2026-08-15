<p align="center">
  <img src="assets/banner.svg" alt="Awesome Identity Resolution Platform Banner" width="100%" />
</p>

# Awesome Identity Resolution Platform 🔗 👤 🌐

<p align="center">
  <b>Curated Directory of SaaS Customer Data Platforms &amp; Open-Source Entity Resolution Frameworks for Customer Identity Graphs, Deterministic &amp; Probabilistic Matching, Cross-Device Tracking, Unified Profiles &amp; Record Linkage</b>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Resolution-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Identity-Resolution-Platform?style=social" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Resolution-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Identity-Resolution-Platform?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Identity-Resolution-Platform/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🧭 Overview & Architecture Ecosystem

Welcome to **Awesome Identity Resolution Platform** — the authoritative, SEO-indexed, and community-maintained ecosystem guide to **Identity Resolution (IDR)**, **Customer Identity Graphs**, **Entity Resolution (ER)**, **Record Linkage**, and **Customer 360 Infrastructure**.

In a cookieless, privacy-regulated, and multi-device digital ecosystem, businesses face extreme data fragmentation across CRMs, website clicks, mobile apps, offline point-of-sale (POS), email marketing, and data clean rooms. **Identity Resolution tools** stitch together first-party identifiers (emails, hashed PII, phone numbers), pseudo-identifiers (MAIDs, IP addresses, canvas fingerprints, third-party IDs), and offline customer records into a single **Deterministic or Probabilistic Golden Customer Record**.

This repository tracks:
- 🏢 **Enterprise SaaS & Data Bureau Platforms**: Full-scale commercial identity graphs, Customer Data Platforms (CDPs), clean room identity translation (RampID, InfoBase, TruAudience), and real-time streaming IDSync engines.
- 💻 **Open-Source Record Linkage & Entity Resolution Engines**: High-performance mathematical frameworks (Fellegi-Sunter models, machine learning active learning, deep neural matching, and dbt warehouse-native SQL graphs) for building transparent, inspectable in-house identity pipelines inside Snowflake, BigQuery, Databricks, DuckDB, or Spark clusters.

---

## 📑 Table of Contents
- [🏢 SaaS & Hosted Identity Platforms](#-saas--hosted-identity-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🌟 In-Warehouse & Graph Approaches](#-in-warehouse--graph-approaches)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Evaluation Disclaimer](#️-evaluation-disclaimer)
- [⭐ Star History](#-star-history)

---

## 🏢 SaaS & Hosted Identity Platforms

The table below catalogs premier commercial Customer Data Platforms (CDPs), data bureaus, and identity resolution SaaS vendors, sorted in **descending order by company size (market valuation / revenue)**:

| Platform | Company Size (Valuation / Revenue) | Description & Core Capabilities | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Experian](https://www.experian.com/)** (Identity Resolution) | 🏦 **~$45.0B** (LSE: EXPN Market Cap / ~$7.1B Revenue) | 🛡️ Bureau-grade identity resolution and ConsumerView graph enabling offline-to-online deterministic linkage, householding, and demographic enrichment. | Starts at **$2,500/mo** ($30,000/yr minimum annual commitment or **$0.02–$0.08 per match lookup**). | **No free-forever plan**; 30-day sample data match-rate diagnostic test (up to 5,000 record test batch) via enterprise sales. |
| **[TransUnion](https://www.transunion.com/)** (TruAudience) | 🏦 **~$19.0B** (NYSE: TRU Market Cap / ~$4.0B Revenue) | 🌐 Identity graph and resolution suite (incorporating Neustar OneID / Fabrick) for cross-screen identity, measurement, and privacy-first matching. | Starts at **$3,000/mo** ($36,000/yr base identity graph access and query license on Snowflake/AWS Marketplace). | **TruAudience Data Health Assessment (DHA)** free trial on Snowflake with up to **2,500 record matches**; 30-day POC trial. |
| **[Twilio Segment](https://segment.com/)** (Unify) | 🚀 **~$12.0B** (Parent TWLO Market Cap / ~$4.2B Revenue; Segment acquired for $3.2B) | ⚡ Real-time identity resolution engine (Segment Unify) and customer profile merging across mobile, web, and server event pipelines. | **Free Forever Tier** on Connections; Team plan starts at **$120/mo** (up to 10k MTUs); Unify identity add-on starts at **$1,250/mo** ($15,000/yr). | **Free Forever Plan** on Connections (up to **1,000 MTUs** and 2 data sources); 14-day free trial on Team & Business CDP features. |
| **[ZoomInfo RingLead](https://www.ringlead.com/)** | 📈 **~$5.0B** (NASDAQ: ZI Market Cap / ~$1.2B Revenue) | 🎯 Revenue operations and data orchestration platform for lead-to-account matching, CRM deduplication, data cleansing, and automated routing. | Starts at **$500/mo** ($6,000/yr base package for CRM deduplication; full Operations suite starts at **$20,000/yr**). | **No free-forever plan**; 14-day guided sandbox trial and CRM data quality health scan (up to 10,000 CRM records) upon scheduling a demo. |
| **[Zeta Global](https://zetaglobal.com/)** | 📊 **~$4.8B** (NYSE: ZETA Market Cap / ~$750M Revenue) | 🔮 Marketing and identity platform combining proprietary Data Cloud graph (2.4B+ profiles), deterministic resolution, and omni-channel activation. | Starts at **$5,000/mo** ($60,000/yr base platform license or equivalent annual media commitment). | **No free-forever plan**; 30-day custom match-rate diagnostic & POC trial on a sample customer list upon sales engagement. |
| **[Acxiom](https://www.acxiom.com/)** (Real ID) | 🏛️ **~$2.3B** (Enterprise Valuation / IPG Division / ~$500M Revenue) | 🧩 Enterprise identity resolution featuring the InfoBase identity graph and Acxiom Real ID for in-warehouse matching on Snowflake and Databricks. | Starts at **$2,000/mo** ($24,000/yr entry licensing or **$0.02–$0.05 per matched record** on Snowflake Marketplace). | **Snowflake Marketplace Test Drive** allowing up to **1,000 sample record matches**; 30-day proof of concept for enterprise datasets. |
| **[LiveRamp](https://liveramp.com/)** | 🔗 **~$2.0B** (NYSE: RAMP Market Cap / ~$660M Revenue) | 🔒 Enterprise identity resolution and data collaboration platform with RampID deterministic graph, cross-channel identity translation, and Safe Haven clean rooms. | Starts at **$833/mo** ($10,000/yr base RampID resolution tier on AWS/Snowflake Marketplace; enterprise contracts avg $50,000–$150,000/yr). | **No free-forever plan**; 14-day to 30-day Proof of Concept (POC) / test-drive with up to 10,000 sample records upon sales approval. |
| **[Reltio](https://www.reltio.com/)** | 🦄 **~$1.7B** (Series E Unicorn Valuation / ~$130M ARR) | 🏆 Cloud-native Master Data Management (MDM) and entity resolution platform for creating real-time trusted golden customer records. | **Free Forever Tier** available on Identity 360; Paid Enterprise MDM editions start at **$3,333/mo** ($40,000/yr on AWS Marketplace). | **Free Forever Plan** (Identity 360) supporting up to **10,000 unique consolidated profiles**; 30-day test drive for industry Velocity Packs. |
| **[Tealium](https://tealium.com/)** (AudienceStream) | 🦄 **~$1.2B** (Unicorn CDP Valuation / ~$150M ARR) | 📡 Enterprise Customer Data Hub and CDP delivering real-time visitor stitching, omnichannel identity unification, and tag management. | Starts at **$2,500/mo** ($30,000/yr for entry EventStream + AudienceStream bundle managing up to 1M events/mo). | **No free-forever plan**; 30-day sandbox / POC trial with up to 500,000 test events upon enterprise sales discovery. |
| **[Amperity](https://amperity.com/)** | 🦄 **~$1.0B** (Series D Unicorn Valuation / ~$100M ARR) | 🤖 AI-powered customer data platform specializing in patented Stitch identity resolution (probabilistic & deterministic) for unified enterprise Customer 360 profiles. | Starts at **$5,000/mo** ($60,000/yr base platform tier for Customer Data Cloud compute & Amp credits; enterprise contracts avg $100k–$250k+/yr). | **No free-forever plan**; 30-day custom sandbox / POC trial with up to 50,000 customer test records upon discovery demo. |
| **[Treasure Data](https://www.treasuredata.com/)** | 💼 **~$1.0B** (Enterprise Valuation / SoftBank backed / ~$120M ARR) | ☁️ Enterprise CDP using a "No Compute" model to deliver high-scale identity resolution, IoT/event data unification, and predictive analytics. | Starts at **$3,500/mo** ($42,000/yr base subscription for profile management and behavioral event ingestion on AWS Marketplace). | **No free-forever plan**; 30-day enterprise POC trial environment on AWS Marketplace / enterprise evaluation. |
| **[mParticle](https://www.mparticle.com/)** | 📱 **~$800M** (Series E Valuation / ~$80M ARR) | 📲 Real-time customer data platform with native IDSync multi-identifier resolution, cross-device rule stitching, and mobile SDK pipelines. | Starts at **$1,500/mo** ($18,000/yr base package for data ingestion and IDSync; average enterprise deployment ~$156,000/yr). | **No free-forever plan**; 30-day developer sandbox / POC trial with up to 100,000 test events upon sales consultation. |
| **[ActionIQ](https://www.actioniq.com/)** (Uniphore) | 🏢 **~$400M** (Acquisition Valuation by Uniphore / ~$45M ARR) | 🔄 Composable CDP providing zero-copy data warehouse integration, Hybrid Identity Resolution, and enterprise audience orchestration. | Starts at **$8,333/mo** ($100,000/yr base enterprise subscription for composable identity and audience management). | **No free-forever plan**; 30-day enterprise Proof of Concept (POC) sandbox environment following custom data scoping. |
| **[BlueConic](https://www.blueconic.com/)** | 💎 **~$350M** (Vista Equity Enterprise Valuation / ~$40M ARR) | 🎯 Pure-play customer data platform featuring automated profile unification, multi-identifier graph stitching, and real-time behavioral segmentation. | Starts at **$2,500/mo** ($30,000/yr base subscription tier for up to 100,000 active unified customer profiles). | **No free-forever plan**; 14-day to 30-day guided Proof of Concept (POC) trial upon scheduling an enterprise platform demo. |
| **[Tapad](https://www.tapad.com/)** | 📱 **~$280M** (Acquisition Valuation by Experian) | 📲 Cross-device identity resolution and digital device graph linking cookies, MAIDs, CTV IDs, and household devices for omnichannel targeting. | Starts at **$3,000/mo** ($36,000/yr entry graph licensing and data feed access). | **No free-forever plan**; 30-day POC match assessment on sample cross-device dataset (up to 10,000 test device IDs). |
| **[Infutor](https://www.infutor.com/)** (Verisk) | 🏢 **~$250M** (Acquisition Valuation by Verisk Marketing Solutions) | 🔍 Consumer identity resolution and TrueSource graph with real-time IDMax API for lead verification and CRM identity attribute completion. | Starts at **$500/mo** ($6,000/yr base API subscription or **$0.03–$0.07 per API lookup**). | **No free-forever plan**; 14-day free API test trial with up to **1,000 test lookups** upon developer account registration. |
| **[Zeotap](https://zeotap.com/)** | 🇪🇺 **~$200M** (Series C Valuation / ~$25M ARR) | 🇪🇺 Customer data platform and ID+ graph providing deterministic and probabilistic identity resolution with strict European GDPR compliance. | Starts at **$2,500/mo** ($30,000/yr base tier for identity resolution and profile management up to 250,000 profiles). | **No free-forever plan**; 30-day guided POC trial and sandbox environment following enterprise sales demo. |
| **[Lotame](https://www.lotame.com/)** (Panorama ID) | 🍪 **~$160M** (Enterprise Valuation / ~$35M ARR) | 🌐 Cookieless identity resolution (Panorama ID) and Spherical CDP for first-party data onboarding, enrichment, and cross-channel activation. | Starts at **$2,500/mo** ($30,000/yr base subscription for Spherical onboarding & identity platform). | **Free Forever Open Access** for Panorama ID generation/deployment for publishers/web; 30-day POC for Spherical CDP platform. |
| **[FullContact](https://www.fullcontact.com/)** | 👤 **~$120M** (Enterprise Valuation / ~$20M ARR) | 👥 Identity resolution and data enrichment APIs powered by persistent PersonID, multi-identifier graph matching, and household linkages. | Starts at **$99/mo** (Developer API tier with up to 2,500 lookups/mo; commercial API packages start at **$500/mo** or $6,000/yr). | **Free Developer Trial Key** with **1,000 free API match/enrichment queries** (no expiration for initial test credits). |

---

## 💻 Open-Source GitHub Projects

The list below features standout open-source frameworks, Python libraries, machine learning record linkers, and data cleaning utilities for building custom identity resolution pipelines, sorted in **descending order by GitHub star count**:

- **[OpenRefine](https://github.com/OpenRefine/OpenRefine)** [![Stars](https://img.shields.io/github/stars/OpenRefine/OpenRefine?style=social&color=white)](https://github.com/OpenRefine/OpenRefine/stargazers)  
  🧹 Powerful open-source data cleansing, entity reconciliation, and record clustering tool. Widely used for entity disambiguation, Wikidata reconciliation, and standardizing messy cross-channel identifier datasets before graph ingestion.

- **[Snowplow](https://github.com/snowplow/snowplow)** [![Stars](https://img.shields.io/github/stars/snowplow/snowplow?style=social&color=white)](https://github.com/snowplow/snowplow/stargazers)  
  ❄️ Enterprise-grade behavioral data pipeline that collects, enriches, and structures real-time customer event streams with first-party cookie IDs, device identifiers, and server-side identity stitching.

- **[Jitsu](https://github.com/jitsucom/jitsu)** [![Stars](https://img.shields.io/github/stars/jitsucom/jitsu?style=social&color=white)](https://github.com/jitsucom/jitsu/stargazers)  
  ⚡ Open-source, high-performance customer data platform (CDP) and event router for real-time user identification, anonymous-to-known user mapping, and warehouse synchronization.

- **[Dedupe](https://github.com/dedupeio/dedupe)** [![Stars](https://img.shields.io/github/stars/dedupeio/dedupe?style=social&color=white)](https://github.com/dedupeio/dedupe/stargazers)  
  🔍 Mature Python library for fuzzy matching, deduplication, and entity resolution using active learning. Learns domain-specific matching rules interactively with minimal human-labeled training data.

- **[thefuzz](https://github.com/seatgeek/thefuzz)** [![Stars](https://img.shields.io/github/stars/seatgeek/thefuzz?style=social&color=white)](https://github.com/seatgeek/thefuzz/stargazers)  
  🔤 Widely used fuzzy string matching library (formerly `fuzzywuzzy`) utilizing Levenshtein Distance to calculate similarity ratios for entity names, emails, and address fields in record linkage pipelines.

- **[Splink](https://github.com/moj-analytical-services/splink)** [![Stars](https://img.shields.io/github/stars/moj-analytical-services/splink?style=social&color=white)](https://github.com/moj-analytical-services/splink/stargazers)  
  🔗 Leading open-source probabilistic record linkage and entity resolution framework (DuckDB/SQL/Spark). Implements scalable Fellegi-Sunter mathematical models with transparent match weights, chart visualizers, and millions-of-records scale.

- **[usaddress](https://github.com/datamade/usaddress)** [![Stars](https://img.shields.io/github/stars/datamade/usaddress?style=social&color=white)](https://github.com/datamade/usaddress/stargazers)  
  📬 Probabilistic address parser powered by Conditional Random Fields (CRF) that normalizes unstructured street addresses into granular schema components for geographic entity resolution.

- **[Zingg](https://github.com/zinggAI/zingg)** [![Stars](https://img.shields.io/github/stars/zinggAI/zingg?style=social&color=white)](https://github.com/zinggAI/zingg/stargazers)  
  ⚡ Scalable open-source entity resolution tool using active learning and Apache Spark. Designed for large enterprise datasets, automated golden record creation, and customer 360 mastering workflows.

- **[DeepMatcher](https://github.com/anhaidgroup/deepmatcher)** [![Stars](https://img.shields.io/github/stars/anhaidgroup/deepmatcher?style=social&color=white)](https://github.com/anhaidgroup/deepmatcher/stargazers)  
  🧠 Deep learning-based entity matching library utilizing Recurrent Neural Networks (RNNs) and word embeddings to perform semantic record linkage across unstructured textual attributes.

- **[Python Record Linkage Toolkit](https://github.com/J535D165/recordlinkage)** [![Stars](https://img.shields.io/github/stars/J535D165/recordlinkage?style=social&color=white)](https://github.com/J535D165/recordlinkage/stargazers)  
  📊 Comprehensive Python library for record linkage and duplicate detection, offering indexing/blocking techniques, string comparison algorithms, and supervised/unsupervised classification models.

- **[ProbablePeople](https://github.com/datamade/probablepeople)** [![Stars](https://img.shields.io/github/stars/datamade/probablepeople?style=social&color=white)](https://github.com/datamade/probablepeople/stargazers)  
  👤 Machine learning-powered name parser for person and company names, parsing complex unstructured full names into first, middle, surname, nickname, and corporate entity attributes.

- **[Apache Unomi](https://github.com/apache/unomi)** [![Stars](https://img.shields.io/github/stars/apache/unomi?style=social&color=white)](https://github.com/apache/unomi/stargazers)  
  🌐 Open-source Customer Data Platform (CDP) server providing privacy-centric (GDPR/OASIS CDP compliant) real-time customer profile storage, event processing, and cross-channel persona segmentation.

- **[py_entitymatching (Magellan)](https://github.com/anhaidgroup/py_entitymatching)** [![Stars](https://img.shields.io/github/stars/anhaidgroup/py_entitymatching?style=social&color=white)](https://github.com/anhaidgroup/py_entitymatching/stargazers)  
  🔬 End-to-end Python entity matching pipeline framework covering data exploration, blocking, feature extraction, model selection, and matching evaluation.

- **[pyJedAI](https://github.com/AI-team-UoA/pyJedAI)** [![Stars](https://img.shields.io/github/stars/AI-team-UoA/pyJedAI?style=social&color=white)](https://github.com/AI-team-UoA/pyJedAI/stargazers)  
  🎓 State-of-the-art Python toolkit implementing modern entity resolution clustering, schema-agnostic blocking, graph-based entity matching, and embedding similarities.

- **[RudderStack dbt ID Resolution](https://github.com/rudderlabs/dbt-id-resolution)** [![Stars](https://img.shields.io/github/stars/rudderlabs/dbt-id-resolution?style=social&color=white)](https://github.com/rudderlabs/dbt-id-resolution/stargazers)  
  🏛️ Open dbt package and SQL models for executing graph-based identity resolution and anonymous-to-known user profile stitching directly inside Snowflake, BigQuery, Redshift, and Databricks.

---

## 🌟 In-Warehouse & Graph Approaches

Data engineering teams increasingly build custom identity resolution pipelines directly on their cloud data warehouses (CDW) and graph engines:

1. **Warehouse-Native Graph Stitching (dbt + SQL)**: Utilizing packages like **RudderStack dbt ID Resolution** to build connected component graphs over event tables and identify calls. This outputs unified customer clusters directly in Snowflake, BigQuery, or Databricks without data egress.
2. **High-Performance Probabilistic Linkage (Splink + DuckDB/Spark)**: Running **Splink** with DuckDB executes Fellegi-Sunter expectation-maximization models on millions of records in seconds, outputting transparent match probability scores and interactive cluster visualizations.
3. **Graph Databases (Neo4j / Amazon Neptune / JanusGraph)**: Modeling users, devices, emails, credit cards, and addresses as nodes and edges to perform real-time path traversal, community detection (Louvain algorithm), and fraud ring detection.
4. **Machine Learning Active Learning (Dedupe & Zingg)**: Using iterative human-in-the-loop labeling to train high-precision matching models on enterprise CRM datasets with complex business rules.

---

## 🤝 How to Contribute

Contributions from identity architects, data engineers, privacy researchers, and open-source developers are warmly welcome!

1. 🍴 **Fork the repository** on GitHub.
2. 🌿 **Create a feature branch**: `git checkout -b add-new-identity-tool`
3. 📝 **Add your entry** in `README.md` following the exact table/list format:
   - For SaaS tools: Include Platform Name, Website Link, Focus/Description, Company Size (Valuation/Revenue), Starting Pricing, and specific Free Tier/Trial Limits. Insert in the correct sorted order.
   - For Open-Source projects: Include Repo Name, GitHub Link, Stargazers Star Badge, and Description. Insert in the correct star-sorted order.
4. 🚀 **Submit a Pull Request** with a concise summary of the addition.

⭐ **Star the repo** if you find it helpful for your identity resolution pipelines!

---

## ⚠️ Evaluation Disclaimer

- This repository is a **community-curated index** for informational and educational purposes — it does not constitute an endorsement or legal/compliance certification.
- Identity resolution platforms must be evaluated for match accuracy (deterministic vs. probabilistic), false-positive tolerance, graph coverage, privacy regulation compliance (GDPR, CCPA/CPRA, HIPAA), latency requirements (real-time streaming vs. batch), and Total Cost of Ownership (TCO).
- Open-source record linkage libraries provide complete transparency, model inspectability, and data privacy, but require internal engineering maintenance, data normalization preprocessing, and ongoing model tuning.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Identity-Resolution-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Identity-Resolution-Platform&type=date&legend=top-left)

---

<p align="center">
  <sub>Made with 🔗 for data engineers, identity architects, CDP teams, and privacy-conscious organizations seeking transparent and reliable identity resolution infrastructure.</sub>
</p>
