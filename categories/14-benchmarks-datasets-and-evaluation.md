# Benchmarks, Datasets, and Evaluation

[Back to the index](../README.md)

Threat-specific measurement, reproducibility, attack success, legitimate task utility, and evaluation datasets.

**30 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

Read each benchmark against its own threat model. Common corruptions, safety refusals, prompt injection, and adversarial perturbations measure different properties.

## Reading list

1. **[RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)** — Benchmark paper; source year 2020. Compare robustness results under explicit shared evaluation settings. Source ID: `robustbench`.

2. **[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://arxiv.org/abs/2406.13352)** — Benchmark paper; source year 2024. Evaluate prompt injection together with legitimate task completion in tool-using agents. Source ID: `agentdojo`.

3. **[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/abs/2403.02691)** — Benchmark paper; source year 2024. Study indirect prompt injection against tool-integrated agents. Source ID: `injecagent`.

4. **[MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers](https://arxiv.org/abs/2508.14925)** — Benchmark paper; source year 2025. Evaluate tool-description poisoning in realistic MCP settings. Source ID: `mcptox`.

5. **[HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal](https://arxiv.org/abs/2402.04249)** — Benchmark paper; source year 2024. Study standardized evaluations of harmful behavior and robust refusal. Source ID: `harmbench`.

6. **[JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models](https://arxiv.org/abs/2404.01318)** — Benchmark paper; source year 2024. Examine jailbreak threat models, behaviors, scoring, and reproducible artifacts. Source ID: `jailbreakbench`.

7. **[Dataset and Lessons Learned from the 2024 SaTML LLM Capture-the-Flag Competition](https://arxiv.org/abs/2406.07954)** — Competition paper; source year 2024. Study competition data and lessons from adversarial secret-protection tasks. Source ID: `satml-ctf`.

8. **[BackdoorDM: A Comprehensive Benchmark for Backdoor Learning on Diffusion Model](https://papers.nips.cc/paper_files/paper/2025/hash/ba9b181cd30b4f1819583be24fdfeb17-Abstract-Datasets_and_Benchmarks_Track.html)** — Benchmark paper; source year 2026. Compare diffusion backdoors and defenses under a shared benchmark. Source ID: `gen-backdoordm`.

9. **[Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/abs/2410.02644)** — Benchmark paper; source year 2024. Compare agent attack surfaces and defenses in a common evaluation framework. Source ID: `agent-asb`.

10. **[AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024)** — Benchmark paper; source year 2024. Distinguish malicious task completion from ordinary agent capabilities. Source ID: `agent-harm`.

11. **[Towards More Robust Retrieval-Augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks](https://arxiv.org/abs/2412.16708)** — Paper; source year 2024. Compare retrieval and generation robustness under knowledge poisoning. Source ID: `rag-evalpoison`.

12. **[Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models](https://arxiv.org/abs/2312.14197)** — Benchmark paper; source year 2023. Study indirect injection and defenses over externally supplied content. Source ID: `bipia`.

13. **[Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470)** — Benchmark paper; source year 2024. Compare safety failure modes across interactive agent environments. Source ID: `agent-safetybench`.

14. **[Identifying the Risks of LM Agents with an LM-Emulated Sandbox](https://arxiv.org/abs/2309.15817)** — Benchmark paper; source year 2023. Study the opportunities and limits of language-model-emulated risk evaluations. Source ID: `agent-toolemu`.

15. **[ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://arxiv.org/abs/2410.06703)** — Benchmark paper; source year 2024. Evaluate safety and trustworthiness of enterprise web agents. Source ID: `agent-stweb`.

16. **[TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/abs/2401.05561)** — Benchmark paper; source year 2024. Review multiple dimensions of language-model trustworthiness. Source ID: `bench-trustllm`.

17. **[DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698)** — Benchmark paper; source year 2023. Study trustworthiness evaluation dimensions and their measurement assumptions. Source ID: `bench-decodingtrust`.

18. **[A StrongREJECT for Empty Jailbreaks](https://arxiv.org/abs/2402.10260)** — Benchmark paper; source year 2024. Examine whether jailbreak scoring reflects genuinely useful harmful responses. Source ID: `bench-strongreject`.

19. **[SORRY-Bench: Systematically Evaluating Large Language Model Safety Refusal](https://arxiv.org/abs/2406.14598)** — Benchmark paper; source year 2024. Study systematic evaluation of language-model safety refusals. Source ID: `bench-sorry`.

20. **[XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models](https://arxiv.org/abs/2308.01263)** — Benchmark paper; source year 2023. Measure exaggerated refusal of legitimate requests. Source ID: `bench-xstest`.

21. **[Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs](https://arxiv.org/abs/2308.13387)** — Dataset paper; source year 2023. Study an annotated dataset for evaluating harmful response behavior. Source ID: `bench-donotanswer`.

22. **[WildGuard: Open One-Stop Moderation Tools for Safety Risks, Jailbreaks, and Refusals of LLMs](https://arxiv.org/abs/2406.18495)** — Dataset paper; source year 2024. Examine datasets and evaluation of harmful requests, responses, and refusals. Source ID: `bench-wildguard`.

23. **[WildTeaming at Scale: From In-the-Wild Jailbreaks to (Adversarially) Safer Language Models](https://arxiv.org/abs/2406.18510)** — Dataset paper; source year 2024. Study diverse adversarial safety training and evaluation examples. Source ID: `bench-wildjailbreak`.

24. **[SALAD-Bench: A Hierarchical and Comprehensive Safety Benchmark for Large Language Models](https://arxiv.org/abs/2402.05044)** — Benchmark paper; source year 2024. Explore hierarchical safety evaluation across models, attacks, and defenses. Source ID: `bench-salad`.

25. **[Adversarial GLUE: A Multi-Task Benchmark for Robustness Evaluation of Language Models](https://arxiv.org/abs/2111.02840)** — Benchmark paper; source year 2021. Compare adversarial robustness across natural-language understanding tasks. Source ID: `bench-advglue`.

26. **[Natural Adversarial Examples](https://arxiv.org/abs/1907.07174)** — Dataset paper; source year 2019. Study naturally occurring examples that are difficult for image classifiers. Source ID: `bench-imageneta`.

27. **[Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://arxiv.org/abs/1903.12261)** — Benchmark paper; source year 2019. Distinguish common corruption robustness from adversarial robustness. Source ID: `bench-imagenetc`.

28. **[BackdoorBench: A Comprehensive Benchmark of Backdoor Learning](https://arxiv.org/abs/2206.12654)** — Benchmark paper; source year 2022. Compare backdoor attacks and defenses with shared evaluation procedures. Source ID: `bench-backdoor`.

29. **[MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/abs/2311.17600)** — Benchmark paper; source year 2023. Evaluate multimodal safety across image-text scenarios. Source ID: `multimodal-safetybench`.

30. **[JailBreakV: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2404.03027)** — Benchmark paper; source year 2024. Study transfer of jailbreaks across text and multimodal settings. Source ID: `multimodal-jailbreakv`.

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
