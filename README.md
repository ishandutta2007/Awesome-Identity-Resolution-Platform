# Awesome-Identity-Resolution-Platform

# Top Identity Resolution Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Customer Identity Graphs, Entity Resolution, Deterministic & Probabilistic Matching, Cross-Device Identity, Unified Profiles & Record Linkage*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Resolution**. These tools stitch together fragmented customer, device, and household identifiers across channels and data sources to create unified profiles — enabling accurate targeting, personalization, measurement, and analytics while navigating privacy constraints.

**Examples** include LiveRamp, Amperity, Reltio, mParticle, Segment Personas, BlueConic, Tealium, ActionIQ, Treasure Data, Zeta Global, FullContact, Zeotap, Acxiom, Near, Tapad, Infutor, RingLead, Experian Identity, TransUnion TruAudience, LiveRamp Safe Haven, Neustar, and Lotame (the category leaders and widely used platforms).

**Open-source emphasis**: Full commercial-scale open-source identity graphs comparable to LiveRamp or Amperity are rare. This section prioritizes the strongest available open-source entity resolution, record linkage, and identity-stitching libraries and frameworks that data and engineering teams use to build custom identity resolution systems inside their own warehouses or infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[LiveRamp](https://liveramp.com/)**  
  Leading identity resolution and data connectivity platform with a large authenticated identity graph, Safe Haven clean-room capabilities, and broad ecosystem integrations.
- **[Amperity](https://amperity.com/)**  
  AI-powered customer data platform specializing in sophisticated identity resolution and unified customer profiles for enterprise brands.
- **[Reltio](https://www.reltio.com/)**  
  Cloud-native master data management (MDM) and entity resolution platform for creating trusted, real-time golden records.
- **[mParticle](https://www.mparticle.com/)**  
  Customer data platform with strong identity resolution (IDSync) capabilities, particularly for mobile and multi-channel environments.
- **[Segment Personas / Unify](https://segment.com/)**  
  Identity resolution and audience capabilities within the Segment CDP ecosystem.
- **[BlueConic](https://www.blueconic.com/)**  
  Customer data platform with identity and profile unification features for marketing use cases.
- **[Tealium](https://tealium.com/)**  
  Enterprise CDP and tag management platform with robust identity and audience resolution capabilities.
- **[ActionIQ](https://www.actioniq.com/)**  
  Composable CDP with identity resolution and audience management for large enterprises.
- **[Treasure Data](https://www.treasuredata.com/)**  
  Enterprise customer data platform emphasizing large-scale identity and profile unification.
- **[Zeta Global](https://zetaglobal.com/)**  
  Marketing and identity platform combining data, identity resolution, and activation.
- **[FullContact](https://www.fullcontact.com/)**  
  Identity resolution and enrichment APIs focused on person and household graphs.
- **[Zeotap](https://zeotap.com/)**  
  Customer data and identity platform with privacy-centric resolution capabilities.
- **[Acxiom](https://www.acxiom.com/)**, **[Experian](https://www.experian.com/)**, **[TransUnion / Neustar](https://www.transunion.com/)**, **[Tapad](https://www.tapad.com/)**, **[Infutor](https://www.infutor.com/)**, **[Lotame](https://www.lotame.com/)**  
  Established data and identity providers offering graphs, enrichment, and resolution services at scale (often bureau or publisher-oriented).
- **[RingLead](https://www.ringlead.com/)** and similar data quality / matching tools  
  Specialized solutions for lead-to-account matching, deduplication, and CRM identity hygiene.

## Open-Source GitHub Projects
- **[Splink](https://github.com/moj-analytical-services/splink)**  
  Leading open-source probabilistic record linkage and entity resolution framework (Python/SQL/Spark). Implements scalable Fellegi-Sunter models with transparent match weights — the strongest pure open-source option for building production identity resolution pipelines.
- **[Zingg](https://github.com/zinggAI/zingg)**  
  Scalable open-source entity resolution tool using active learning and Spark. Designed for large datasets and practical data-mastering workflows.
- **[dedupe](https://github.com/dedupeio/dedupe)**  
  Mature Python library for fuzzy matching, deduplication, and entity resolution using active learning. Excellent for structured data and teams that want flexible, inspectable matching logic.
- **[PyJedAI](https://github.com/AI-team-UoA/pyJedAI)**  
  Open-source toolkit implementing state-of-the-art entity resolution clustering and matching algorithms.
- **[DeepMatcher](https://github.com/anhaidgroup/deepmatcher)**  
  Deep learning-based entity matching library for more complex, semantic record linkage scenarios.
- **[RudderStack dbt ID Resolution](https://github.com/rudderlabs/dbt-id-resolution)** and similar warehouse-native patterns  
  Open examples and dbt projects for performing identity resolution directly inside the data warehouse using event and identify data.
- **Neo4j Entity Resolution Examples & Graph Approaches**  
  Graph-database patterns and community projects that model identity as connected nodes and relationships for resolution and analysis.
- **Emerging Semantic / LLM-based Entity Resolution Frameworks** (e.g., SERF and related projects)  
  Newer open-source efforts that apply embeddings and large language models to semantic entity resolution.
- **Record Linkage and Blocking Libraries**  
  Supporting open-source tools for candidate generation, string comparison, and evaluation that form building blocks of custom identity systems.
- **c1v-id and lightweight identity resolvers**  
  Focused open-source libraries designed for fast identity lookups in AI agents, CRM deduplication, and real-time matching scenarios.

### Additional Strong Open-Source Options
- Privacy-preserving and clean-room related open components that complement identity workflows.
- First-party ID and publisher identity open initiatives (e.g., SharedID-style approaches).
- Data quality and normalization libraries used as preprocessing steps before resolution.
- Graph analytics and community detection algorithms applied to identity graphs.
- Integration of open entity resolution engines with open CDP pipelines (RudderStack, Jitsu, Snowplow) for end-to-end first-party identity systems.

**Frameworks for building custom systems**: Most sophisticated open implementations run **Splink** or **Zingg** (or a combination of blocking + matching libraries) on data inside a warehouse or Spark cluster, often orchestrated with dbt. The resulting unified IDs feed analytics, activation, and personalization layers. Teams with strong graph expertise may model identity relationships in Neo4j or similar stores. Full commercial-scale graphs still typically rely on proprietary data networks; open-source tools excel at resolving *your* first-party and known data.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity resolution platforms should be evaluated for match accuracy (deterministic vs probabilistic), graph coverage, privacy and consent compliance (GDPR, CCPA, etc.), real-time vs batch capabilities, transparency of matching logic, and total cost of ownership.
- Open-source entity resolution tools give full control and auditability of matching models but require significant data engineering effort, high-quality input data, and ongoing tuning. They do not automatically provide the large third-party identity graphs offered by commercial providers.
---
**Made for data engineers, identity architects, CDP teams, and privacy-conscious organizations that want transparent, controllable identity resolution infrastructure.**
Let's make customer identity graphs and entity resolution more open, inspectable, and free from black-box proprietary matching.
