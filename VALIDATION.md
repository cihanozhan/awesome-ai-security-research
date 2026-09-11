# Validation report

Checked on 2026-09-11.

## Collection counts

- Distinct source records: **276**.
- Total category entries: **466**.
- Entries in the 17 knowledge categories: **448**.
- Entries in the two practice collections: **18**.
- Minimum knowledge-category count: **25**.
- Duplicate source IDs, primary URLs, or normalized titles: **0**.
- Repeated source IDs within a category: **0**.

| Category | Sources | Collection |
| --- | ---: | --- |
| [Foundations, Taxonomies, and Education](categories/01-foundations-taxonomies-and-education.md) | 26 | Knowledge |
| [Machine Learning and Deep Learning Security](categories/02-machine-learning-and-deep-learning-security.md) | 25 | Knowledge |
| [Data Poisoning, Backdoors, and Model Supply Chain](categories/03-data-poisoning-backdoors-and-model-supply-chain.md) | 26 | Knowledge |
| [Model Privacy and Model Extraction](categories/04-model-privacy-and-model-extraction.md) | 25 | Knowledge |
| [Computer Vision and Physical Attacks](categories/05-computer-vision-and-physical-attacks.md) | 28 | Knowledge |
| [Reinforcement Learning Security](categories/06-reinforcement-learning-security.md) | 25 | Knowledge |
| [Federated Learning and Graph Learning Security](categories/07-federated-learning-and-graph-learning-security.md) | 28 | Knowledge |
| [LLM Security](categories/08-llm-security.md) | 26 | Knowledge |
| [RAG, Embedding, and Retrieval Security](categories/09-rag-embedding-and-retrieval-security.md) | 27 | Knowledge |
| [Vector Database Security](README.md#vector-database-security) | 26 | Knowledge |
| [Agentic AI, Multi-Agent, and MCP Security](categories/10-agentic-ai-multi-agent-and-mcp-security.md) | 27 | Knowledge |
| [Audio, Speech, and Multimodal Security](categories/11-audio-speech-and-multimodal-security.md) | 25 | Knowledge |
| [Generative Models Security](categories/12-generative-models-security.md) | 26 | Knowledge |
| [Defenses, Robustness, and Formal Verification](categories/13-defenses-robustness-and-formal-verification.md) | 27 | Knowledge |
| [Benchmarks, Datasets, and Evaluation](categories/14-benchmarks-datasets-and-evaluation.md) | 30 | Knowledge |
| [Standards, Frameworks, and Secure Development](categories/15-standards-frameworks-and-secure-development.md) | 25 | Knowledge |
| [CTFs and Competition Archives](categories/16-ctfs-and-competition-archives.md) | 4 | Practice |
| [Vulnerable Applications and Training Labs](categories/17-vulnerable-applications-and-training-labs.md) | 14 | Practice |
| [Case Studies and Research Methodology](categories/18-case-studies-and-research-methodology.md) | 26 | Knowledge |

## Primary-source checks

- `direct_page_retrieval`: 251 sources.
- `direct_pdf_retrieval`: 10 sources.
- `primary_page_web_retrieval`: 5 sources.
- `publisher_search_metadata`: 1 source.
- `github_readme_and_tree_review`: 8 sources.
- `github_sample_directory_review`: 1 source.

Direct HTML retrieval required source metadata or a meaningful title, with recognized challenge pages rejected. PDF retrieval required readable first-page text. Primary-source titles and reading focuses were reviewed for mismatches. Successful retrieval does not imply that every full paper was read or that experiments were reproduced.

## Retrieval exceptions

The following direct fetches were restricted or failed. Their identities were checked through the stated alternative primary-source evidence. These are not labeled as successful direct fetches.

| Source | Direct fetch | Alternative evidence |
| --- | --- | --- |
| [Security and Privacy Issues in Deep Reinforcement Learning: Threats and Countermeasures](https://doi.org/10.1145/3640312) | HTTP Error 403: Forbidden | publisher_search_metadata | 
| [DBA: Distributed Backdoor Attacks against Federated Learning](https://research.ibm.com/publications/dba-distributed-backdoor-attacks-against-federated-learning) | The read operation timed out | primary_page_web_retrieval | 
| [ISO/IEC 42001:2023 - Artificial Intelligence Management System](https://www.iso.org/standard/42001) | HTTP Error 403: Forbidden | primary_page_web_retrieval | 
| [ISO/IEC 23894:2023 - Guidance on Risk Management](https://www.iso.org/standard/77304.html) | HTTP Error 403: Forbidden | primary_page_web_retrieval | 
| [ISO/IEC 24029-2:2023 - Robustness of Neural Networks: Methodology for the Use of Formal Methods](https://www.iso.org/standard/79804.html) | HTTP Error 403: Forbidden | primary_page_web_retrieval | 

ISO catalog entries are publicly described; full standards may require purchase or institutional access. The publisher-index-only survey entry has a confirmed title and identifier but its full text was not inspected.

## Repository checks

Category counts, unique IDs, unique primary URLs, normalized-title duplicates, JSON parsing, local Markdown file targets, and the minimum source floor were checked. Authored prose and category labels were reviewed for English-only content. International proper names and official source titles are preserved. The package contains no copied abstracts, third-party PDFs, downloaded application code, or tool catalog.

External links reflect this curation session. Hosted CTFs and vulnerable applications were not executed or deployment-tested. Repository destination: https://github.com/cihanozhan/awesome-ai-security-research.

## Vulnerable application expansion

Added 10 educational projects or lab collections, increasing category 17 from 4 to 14 resources. A project is counted once regardless of its internal challenge count. The 16 knowledge categories retain their previous counts.

For eight standalone GitHub additions, repository metadata, README content, and source-tree listings were inspected. All eight were non-forks and not archived at the time of review. These observations establish provenance and visible implementation material, not code quality certification or guaranteed maintenance. The registry records observed README blob IDs, tree IDs, and repository push timestamps. A push timestamp is not a release date or proof of substantive maintenance.

OWASP's sample directory and its official explanatory page were inspected. PortSwigger's official learning page was checked for its linked lab curriculum. Additional spot checks covered the OpenA2A status document, the AIGoat workshop guide, and DVAP's MCP-themed application source.

Selection prioritized explicit learning objectives, distinct vulnerable application surfaces, available source or hosted exercises, and setup guidance. Runtime models, simulation limits, historical dependencies, and sample-specific setup differences are identified in the category annotations. No application was installed or executed during this update.

## Vector database category expansion

Added Vector Database Security as category 19, displayed after RAG in the README. Its 26 entries comprise 23 research works and three official technical documents. Eighteen source records are new and eight reuse existing records; this produces 276 distinct sources and 466 category entries across 19 categories. The 18 previously existing categories retain their counts.

All 18 new primary URLs returned readable page content. Titles, source years, abstracts or scope descriptions, and document identities were reviewed. ACL proceedings, USENIX, author pages, arXiv, IACR ePrint, and official database documentation provide the primary references. Eight cross-listed works retain their earlier source verification records and receive vector-specific reading focuses. This review does not claim full-paper reproduction, database penetration testing, or validation of every reported result.

The category distinguishes direct vector insertion from poisoned text ingestion, embedding reconstruction from training-data inference, and private-search protocols from database access controls. The Black-Hole Attack entry is explicitly labeled as a preprint. The Curator entry is labeled as architecture background. Official documentation is included for control design, without ranking or recommending products.

Validated the JSON registry, unique IDs and primary URLs, category mappings, per-category entry counts, and local Markdown links. The README retains expanded content for all categories and does not restore the removed minimum-source sentence or Repository contents section.
