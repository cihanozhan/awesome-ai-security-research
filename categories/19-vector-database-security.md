# Vector Database Security

Embedding confidentiality, corpus and vector poisoning, private similarity search, tenant isolation, and database access controls.

**26 sources:** 23 research papers, preprints, or reproducibility studies, and three official technical documents. Eighteen sources are new to the archive; eight are cross-listed from related categories.

This category follows the vector storage and retrieval layer: stored embeddings, nearest-neighbor rankings, query confidentiality, metadata filters, and tenant boundaries. Some studies demonstrate application-level consequences of poisoned retrieval rather than a vulnerability in a particular database engine. Curator provides indexing background rather than an attack study.

## Embedding privacy and reconstruction

1. **[Text Embeddings Reveal (Almost) As Much As Text](https://arxiv.org/abs/2310.06816)** — Paper; source year 2023. Study reconstruction of stored source text from exposed dense embedding vectors. Source ID: `embedding-inversion`.

2. **[Rethinking the Privacy of Text Embeddings: A Reproducibility Study of "Text Embeddings Reveal (Almost) As Much As Text"](https://arxiv.org/abs/2507.07700)** — Reproducibility paper; source year 2025. Check how reproducibility, auxiliary data, and model assumptions affect embedding-inversion claims. Source ID: `rag-embedding-reproduction`.

3. **[Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence](https://aclanthology.org/2023.findings-acl.881/)** — Paper; source year 2023. Understand how a generative inversion model can reconstruct source sentences from exposed embedding vectors. Source ID: `vector-geia`.

4. **[Transferable Embedding Inversion Attack: Uncovering Privacy Risks in Text Embeddings without Model Queries](https://aclanthology.org/2024.acl-long.230/)** — Paper; source year 2024. Study embedding reconstruction when the attacker cannot query the target embedding model. Source ID: `vector-transfer-inversion`.

5. **[Information Leakage of Sentence Embeddings via Generative Embedding Inversion Attacks](https://arxiv.org/abs/2504.16609)** — Reproducibility paper; source year 2025. Examine reproduced embedding-inversion results and the distinction between input reconstruction and training-data leakage. Source ID: `vector-geia-reproduction`.

6. **[Information Leakage in Embedding Models](https://arxiv.org/abs/2004.00053)** — Paper; source year 2020. Distinguish inversion, sensitive-attribute inference, and membership leakage from embedding representations. Source ID: `vector-embedding-leakage`.

## Corpus poisoning and retrieval manipulation

7. **[PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867)** — Paper; source year 2024. Trace how corrupted knowledge-base content influences retrieval and downstream generated answers. Source ID: `poisonedrag`.

8. **[Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/abs/2310.19156)** — Paper; source year 2023. Study poisoned passage insertion into a dense retrieval corpus and generalization to unseen queries. Source ID: `rag-corpus-poison`.

9. **[AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)** — Paper; source year 2024. Examine poisoned retrieval memories and knowledge bases as entry points for agent backdoors. Source ID: `agent-poison`.

10. **[Unsupervised Corpus Poisoning Attacks in Continuous Space for Dense Retrieval](https://arxiv.org/abs/2504.17884)** — Paper; source year 2025. Compare continuous embedding-space poisoning with attacks that must produce valid text passages. Source ID: `vector-continuous-poison`.

11. **[Corpus Poisoning via Approximate Greedy Gradient Descent](https://aclanthology.org/2025.findings-acl.222/)** — Paper; source year 2025. Study adversarial passage construction and its effect on top-ranked dense retrieval results. Source ID: `vector-aggd`.

12. **[Tricking Retrievers with Influential Tokens: An Efficient Black-Box Corpus Poisoning Attack](https://aclanthology.org/2025.naacl-long.210/)** — Paper; source year 2025. Examine black-box manipulation of retrieval through influential tokens in poisoned passages. Source ID: `vector-diga`.

13. **[GASLITEing the Retrieval: Exploring Vulnerabilities in Dense Embedding-based Search](https://arxiv.org/abs/2412.20953)** — Paper; source year 2024. Analyze malicious passage promotion under different attacker knowledge and query-distribution assumptions. Source ID: `vector-gaslite`.

14. **[Can You Trust the Vectors in Your Vector Database? Black-Hole Attack from Embedding Space Defects](https://arxiv.org/abs/2604.05480)** — Preprint; source year 2026. Study centrality-driven hubness and malicious vectors that attract disproportionate nearest-neighbor matches. Source ID: `vector-black-hole`.

## Private similarity search and protected embeddings

15. **[Certifiably Robust RAG against Retrieval Corruption](https://arxiv.org/abs/2405.15556)** — Paper; source year 2024. Read bounded retrieval-corruption guarantees and the assumptions limiting their scope. Source ID: `rag-certified`.

16. **[Sentence-level Privacy for Document Embeddings](https://aclanthology.org/2022.acl-long.238/)** — Paper; source year 2022. Study sentence-level differential privacy and the utility trade-offs of protecting document representations. Source ID: `vector-sentence-dp`.

17. **[Don't forget private retrieval: distributed private similarity search for large language models](https://aclanthology.org/2024.privatenlp-1.2/)** — Paper; source year 2024. Explore multi-party computation for private top-k retrieval and the required distributed-server assumptions. Source ID: `vector-prag`.

18. **[Private Web Search with Tiptoe](https://people.eecs.berkeley.edu/~henrycg/pubs/tiptoe/)** — Paper; source year 2023. Study the reduction of private semantic search to private nearest-neighbor retrieval using cryptography. Source ID: `vector-tiptoe`.

19. **[SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)** — Paper; source year 2020. Examine query and result confidentiality for approximate nearest-neighbor search under a semi-honest threat model. Source ID: `vector-sanns`.

20. **[Approximate Distance-Comparison-Preserving Symmetric Encryption](https://eprint.iacr.org/2021/1666)** — Paper; source year 2021. Examine searchable encrypted vectors and the leakage implications of preserving distance-comparison information. Source ID: `vector-dcpe`.

## Evaluation and downstream exposure

21. **[The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)](https://arxiv.org/abs/2402.16893)** — Paper; source year 2024. Examine how a retrieval layer changes the privacy exposure of stored knowledge. Source ID: `rag-privacy-goodbad`.

22. **[Towards More Robust Retrieval-Augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks](https://arxiv.org/abs/2412.16708)** — Paper; source year 2024. Compare retrieval-stage poisoning effects with downstream answer robustness in a shared evaluation setting. Source ID: `rag-evalpoison`.

## Tenant isolation and database access controls

23. **[Curator: Efficient Indexing for Multi-Tenant Vector Databases](https://arxiv.org/abs/2401.07119)** — Architecture paper; source year 2024. Study tenant-aware index organization and filtering as background for reasoning about data isolation and search performance. Source ID: `vector-curator`.

24. **[Qdrant: Security and Access Control](https://qdrant.tech/documentation/security/)** — Official documentation. Review authentication, collection-scoped permissions, transport security, and network exposure controls for a vector store. Source ID: `vector-qdrant-security`.

25. **[Weaviate: Authorization](https://docs.weaviate.io/deploy/configuration/authorization)** — Official documentation. Study role-based permissions and authorization boundaries for vector database operations. Source ID: `vector-weaviate-rbac`.

26. **[Pinecone: Implement Multitenancy](https://docs.pinecone.io/guides/index-data/implement-multitenancy)** — Official documentation. Examine namespace-based tenant separation and the application responsibility for choosing the authorized tenant scope. Source ID: `vector-pinecone-tenancy`.

## Reading priorities

Start with *Information Leakage in Embedding Models* and *Text Embeddings Reveal (Almost) As Much As Text* for confidentiality. Follow *Poisoning Retrieval Corpora*, *GASLITEing the Retrieval*, and the *Black-Hole Attack* preprint for retrieval integrity. Use *SANNS*, *Tiptoe*, and *PRAG* to compare private-search designs. Read *Curator* alongside the official access-control documents for tenant-aware retrieval.

Compare attacker capabilities carefully: reading stored vectors, querying an embedding service, inserting text documents, and directly inserting arbitrary vectors are different threat models. Cryptographic and robustness guarantees apply under each paper's stated assumptions; transport or storage encryption alone does not establish private search. Tenant namespaces and metadata filtering require correct application authorization.

The three product-specific entries are technical reading references about security controls, not a database product catalog. Documentation was checked on 2026-09-11; deployment versions and supported controls should be verified before application. No experiments or database deployments were executed for this collection.

