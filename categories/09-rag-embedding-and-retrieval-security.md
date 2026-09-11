# RAG, Embedding, and Retrieval Security

[Back to the index](../README.md)

Corpus poisoning, retrieval corruption, embedding inversion, knowledge extraction, and retrieval privacy.

**27 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

## Reading list

1. **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** — Paper; source year 2023. Understand instruction injection through external content and broken trust boundaries. Source ID: `indirect-injection`.

2. **[PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867)** — Paper; source year 2024. Study knowledge-base poisoning that changes retrieval-augmented answers. Source ID: `poisonedrag`.

3. **[Text Embeddings Reveal (Almost) As Much As Text](https://arxiv.org/abs/2310.06816)** — Paper; source year 2023. Understand recovery of source text from dense embedding vectors. Source ID: `embedding-inversion`.

4. **[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://arxiv.org/abs/2406.13352)** — Benchmark paper; source year 2024. Evaluate prompt injection together with legitimate task completion in tool-using agents. Source ID: `agentdojo`.

5. **[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/abs/2403.02691)** — Benchmark paper; source year 2024. Study indirect prompt injection against tool-integrated agents. Source ID: `injecagent`.

6. **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** — Paper; source year 2023. Understand instruction injection carried by image and audio inputs. Source ID: `multimodal-indirect`.

7. **[Adversarial Attacks on Node Embeddings via Graph Poisoning](https://arxiv.org/abs/1809.01093)** — Paper; source year 2018. Examine poisoning attacks on learned node embeddings. Source ID: `graph-embedding`.

8. **[Data Poisoning Attack against Knowledge Graph Embedding](https://arxiv.org/abs/1904.12052)** — Paper; source year 2019. Study poisoning of knowledge graph embeddings used in retrieval and reasoning. Source ID: `graph-kg-poison`.

9. **[Learning to Deceive Knowledge Graph Augmented Models via Targeted Perturbation](https://arxiv.org/abs/2010.12872)** — Paper; source year 2020. Explore targeted perturbations of knowledge graph augmented models. Source ID: `graph-kg-deceive`.

10. **[The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)](https://arxiv.org/abs/2402.16893)** — Paper; source year 2024. Study the privacy implications of attaching retrieved knowledge to language models. Source ID: `rag-privacy-goodbad`.

11. **[Feedback-Guided Extraction of Knowledge Base from Retrieval-Augmented LLM Applications](https://arxiv.org/abs/2411.14110)** — Paper; source year 2024. Study feedback-guided extraction of knowledge from retrieval-augmented applications. Source ID: `rag-thief`.

12. **[Silent Leaks: Implicit Knowledge Extraction Attack on RAG Systems through Benign Queries](https://arxiv.org/abs/2505.15420)** — Paper; source year 2025. Study knowledge extraction through apparently benign queries. Source ID: `rag-silent-leaks`.

13. **[Fine-Grained Privacy Extraction from Retrieval-Augmented Generation Systems via Knowledge Asymmetry Exploitation](https://arxiv.org/abs/2507.23229)** — Paper; source year 2025. Explore privacy extraction using differences between base models and RAG systems. Source ID: `rag-knowledge-asymmetry`.

14. **[Exposing Privacy Risks in Graph Retrieval-Augmented Generation](https://arxiv.org/abs/2508.17222)** — Paper; source year 2025. Study extraction risks introduced by graph-based retrieval. Source ID: `rag-graph-privacy`.

15. **[Poison-RAG: Adversarial Data Poisoning Attacks on Retrieval-Augmented Generation in Recommender Systems](https://arxiv.org/abs/2501.11759)** — Paper; source year 2025. Examine poisoning of retrieval-augmented recommendation pipelines. Source ID: `rag-recommender-poison`.

16. **[Privacy-Aware Decoding: Mitigating Privacy Leakage of Large Language Models in Retrieval-Augmented Generation](https://arxiv.org/abs/2508.03098)** — Paper; source year 2025. Study decoding-time defenses against leakage of retrieved sensitive information. Source ID: `rag-privacy-decoding`.

17. **[RAG with Differential Privacy](https://arxiv.org/abs/2412.19291)** — Paper; source year 2024. Explore differential privacy in retrieval-augmented generation. Source ID: `rag-dp`.

18. **[Rethinking the Privacy of Text Embeddings: A Reproducibility Study of "Text Embeddings Reveal (Almost) As Much As Text"](https://arxiv.org/abs/2507.07700)** — Reproducibility paper; source year 2025. Examine reproducibility and assumptions in text embedding inversion. Source ID: `rag-embedding-reproduction`.

19. **[BadRAG: Identifying Vulnerabilities in Retrieval Augmented Generation of Large Language Models](https://arxiv.org/abs/2406.00083)** — Paper; source year 2024. Study retrieval-triggered denial and manipulation risks in RAG systems. Source ID: `rag-badrag`.

20. **[Towards More Robust Retrieval-Augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks](https://arxiv.org/abs/2412.16708)** — Paper; source year 2024. Compare retrieval and generation robustness under knowledge poisoning. Source ID: `rag-evalpoison`.

21. **[Certifiably Robust RAG against Retrieval Corruption](https://arxiv.org/abs/2405.15556)** — Paper; source year 2024. Study certified robustness under bounded retrieval corruption. Source ID: `rag-certified`.

22. **[Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/abs/2310.19156)** — Paper; source year 2023. Examine adversarial passages injected into retrieval corpora. Source ID: `rag-corpus-poison`.

23. **[AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)** — Paper; source year 2024. Study backdoors introduced through agent memory or knowledge bases. Source ID: `agent-poison`.

24. **[Memory Injection Attacks on LLM Agents via Query-Only Interaction](https://arxiv.org/abs/2503.03704)** — Paper; source year 2025. Examine memory injection through interactions with an agent. Source ID: `agent-minja`.

25. **[Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models](https://arxiv.org/abs/2312.14197)** — Benchmark paper; source year 2023. Study indirect injection and defenses over externally supplied content. Source ID: `bipia`.

26. **[Defending Against Indirect Prompt Injection Attacks With Spotlighting](https://arxiv.org/abs/2403.14720)** — Paper; source year 2024. Examine input transformations that mark externally supplied content as untrusted. Source ID: `llm-spotlighting`.

27. **[Universal Adversarial Triggers for Attacking and Analyzing NLP](https://arxiv.org/abs/1908.07125)** — Paper; source year 2019. Understand input-agnostic adversarial triggers for NLP models. Source ID: `llm-universal-triggers`.

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
