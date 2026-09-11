# Agentic AI, Multi-Agent, and MCP Security

[Back to the index](../README.md)

Agent actions, memory, tool descriptions, trust boundaries, malicious interactions, and protocol security.

**27 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

## Reading list

1. **[Adversarial Policies: Attacking Deep Reinforcement Learning](https://arxiv.org/abs/1905.10615)** — Paper; source year 2019. Study malicious opponent behavior in multi-agent reinforcement learning. Source ID: `adversarial-policies`.

2. **[Reward Tampering Problems and Solutions in Reinforcement Learning: A Causal Influence Diagram Perspective](https://arxiv.org/abs/1908.04734)** — Paper; source year 2019. Analyze incentives to manipulate reward functions and reward inputs. Source ID: `reward-tampering`.

3. **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** — Paper; source year 2023. Understand instruction injection through external content and broken trust boundaries. Source ID: `indirect-injection`.

4. **[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://arxiv.org/abs/2406.13352)** — Benchmark paper; source year 2024. Evaluate prompt injection together with legitimate task completion in tool-using agents. Source ID: `agentdojo`.

5. **[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/abs/2403.02691)** — Benchmark paper; source year 2024. Study indirect prompt injection against tool-integrated agents. Source ID: `injecagent`.

6. **[MCPTox: A Benchmark for Tool Poisoning Attack on Real-World MCP Servers](https://arxiv.org/abs/2508.14925)** — Benchmark paper; source year 2025. Evaluate tool-description poisoning in realistic MCP settings. Source ID: `mcptox`.

7. **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** — Paper; source year 2023. Understand instruction injection carried by image and audio inputs. Source ID: `multimodal-indirect`.

8. **[Robust Reinforcement Learning using Adversarial Populations](https://arxiv.org/abs/2008.01825)** — Paper; source year 2020. Explore robustness against diverse populations of adversaries. Source ID: `rl-populations`.

9. **[SUB-PLAY: Adversarial Policies against Partially Observed Multi-Agent Reinforcement Learning Systems](https://arxiv.org/abs/2402.03741)** — Paper; source year 2024. Study adversarial policies under partial observability in multi-agent systems. Source ID: `rl-subplay`.

10. **[Feedback-Guided Extraction of Knowledge Base from Retrieval-Augmented LLM Applications](https://arxiv.org/abs/2411.14110)** — Paper; source year 2024. Study feedback-guided extraction of knowledge from retrieval-augmented applications. Source ID: `rag-thief`.

11. **[Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/abs/2410.02644)** — Benchmark paper; source year 2024. Compare agent attack surfaces and defenses in a common evaluation framework. Source ID: `agent-asb`.

12. **[AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024)** — Benchmark paper; source year 2024. Distinguish malicious task completion from ordinary agent capabilities. Source ID: `agent-harm`.

13. **[AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)** — Paper; source year 2024. Study backdoors introduced through agent memory or knowledge bases. Source ID: `agent-poison`.

14. **[Memory Injection Attacks on LLM Agents via Query-Only Interaction](https://arxiv.org/abs/2503.03704)** — Paper; source year 2025. Examine memory injection through interactions with an agent. Source ID: `agent-minja`.

15. **[Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models](https://arxiv.org/abs/2312.14197)** — Benchmark paper; source year 2023. Study indirect injection and defenses over externally supplied content. Source ID: `bipia`.

16. **[Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470)** — Benchmark paper; source year 2024. Compare safety failure modes across interactive agent environments. Source ID: `agent-safetybench`.

17. **[Identifying the Risks of LM Agents with an LM-Emulated Sandbox](https://arxiv.org/abs/2309.15817)** — Benchmark paper; source year 2023. Study the opportunities and limits of language-model-emulated risk evaluations. Source ID: `agent-toolemu`.

18. **[Defeating Prompt Injections by Design](https://arxiv.org/abs/2503.18813)** — Paper; source year 2025. Study architectural separation of data and control flow against prompt injection. Source ID: `agent-camel`.

19. **[The Task Shield: Enforcing Task Alignment to Defend Against Indirect Prompt Injection in LLM Agents](https://arxiv.org/abs/2412.16682)** — Paper; source year 2024. Examine task alignment checks for actions derived from untrusted content. Source ID: `agent-taskshield`.

20. **[AgentVigil: Generic Black-Box Red-teaming for Indirect Prompt Injection against LLM Agents](https://arxiv.org/abs/2505.05849)** — Paper; source year 2025. Study black-box red teaming of indirect injection in agents. Source ID: `agent-vigil`.

21. **[Imprompter: Tricking LLM Agents into Improper Tool Use](https://arxiv.org/abs/2410.14923)** — Paper; source year 2024. Examine adversarial prompts that induce improper tool use. Source ID: `agent-imprompter`.

22. **[ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://arxiv.org/abs/2410.06703)** — Benchmark paper; source year 2024. Evaluate safety and trustworthiness of enterprise web agents. Source ID: `agent-stweb`.

23. **[The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions](https://arxiv.org/abs/2404.13208)** — Paper; source year 2024. Study instruction priority training for handling untrusted prompts. Source ID: `llm-hierarchy`.

24. **[Defending Against Indirect Prompt Injection Attacks With Spotlighting](https://arxiv.org/abs/2403.14720)** — Paper; source year 2024. Examine input transformations that mark externally supplied content as untrusted. Source ID: `llm-spotlighting`.

25. **[Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://arxiv.org/abs/2402.08567)** — Paper; source year 2024. Examine propagation of adversarial content through multimodal agent interactions. Source ID: `multimodal-agent-smith`.

26. **[OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)** — Community guidance. Review the 2026 risk categories for agentic applications. Source ID: `owasp-agent`.

27. **[Model Context Protocol: Security Best Practices](https://modelcontextprotocol.io/docs/tutorials/security/security_best_practices)** — Protocol guidance. Study authorization, token handling, and trust boundaries in MCP implementations. Source ID: `mcp-security`.

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
