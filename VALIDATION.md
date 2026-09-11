# Validation report

Checked on 2026-09-11.

## Collection counts

- Distinct source records: **248**.
- Total category entries: **430**.
- Entries in the 16 knowledge categories: **422**.
- Entries in the two practice collections: **8**.
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
| [Agentic AI, Multi-Agent, and MCP Security](categories/10-agentic-ai-multi-agent-and-mcp-security.md) | 27 | Knowledge |
| [Audio, Speech, and Multimodal Security](categories/11-audio-speech-and-multimodal-security.md) | 25 | Knowledge |
| [Generative Models Security](categories/12-generative-models-security.md) | 26 | Knowledge |
| [Defenses, Robustness, and Formal Verification](categories/13-defenses-robustness-and-formal-verification.md) | 27 | Knowledge |
| [Benchmarks, Datasets, and Evaluation](categories/14-benchmarks-datasets-and-evaluation.md) | 30 | Knowledge |
| [Standards, Frameworks, and Secure Development](categories/15-standards-frameworks-and-secure-development.md) | 25 | Knowledge |
| [CTFs and Competition Archives](categories/16-ctfs-and-competition-archives.md) | 4 | Practice |
| [Vulnerable Applications and Training Labs](categories/17-vulnerable-applications-and-training-labs.md) | 4 | Practice |
| [Case Studies and Research Methodology](categories/18-case-studies-and-research-methodology.md) | 26 | Knowledge |

## Primary-source checks

- `direct_page_retrieval`: 233 sources.
- `direct_pdf_retrieval`: 10 sources.
- `primary_page_web_retrieval`: 4 sources.
- `publisher_search_metadata`: 1 sources.

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
