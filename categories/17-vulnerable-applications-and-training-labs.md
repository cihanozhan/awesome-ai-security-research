# Vulnerable Applications and Training Labs

[Back to the index](../README.md)

Intentionally vulnerable applications and structured lab collections for studying AI security through concrete examples.

**14 sources.** Each project or collection is counted once, regardless of its number of challenges.

Selection favors explicit learning objectives, available application code or hosted exercises, and documented setup. New entries include a learning focus, the reason for inclusion, and an environment note. These are documentation-based selections; deployments and challenge outcomes were not tested.

## Existing collection

1. **[OWASP FinBot](https://genai.owasp.org/resource/finbot-agentic-ai-capture-the-flag-ctf-application/)** — Vulnerable application. Explore intentionally vulnerable financial-agent workflows for learning agentic security. Source ID: `lab-finbot`.

2. **[Damn Vulnerable LLM Agent](https://github.com/ReversecLabs/damn-vulnerable-llm-agent)** — Vulnerable application. Study prompt injection and its impact on an intentionally vulnerable LLM agent. Source ID: `lab-dvla`.

3. **[Orca AI Goat](https://github.com/orcasecurity-research/AIGoat)** — Vulnerable application. Explore intentionally vulnerable AI infrastructure and machine learning scenarios. Source ID: `lab-aigoat`.

4. **[Damn Vulnerable MCP Server](https://github.com/harishsg993010/damn-vulnerable-MCP-server)** — Vulnerable application. Study MCP implementation vulnerabilities through educational challenges. Source ID: `lab-dvmcp`.

## Added application projects

5. **[SECFORCE LLMGoat](https://github.com/SECFORCE/LLMGoat)** — Vulnerable application. Work through OWASP LLM risk categories using separate challenges for prompt injection, sensitive data exposure, supply-chain assumptions, and excessive agency. Source ID: `lab-llmgoat`.

   **Educational value:** Documented challenge modules and CPU/GPU container options support structured self-study.

   **Environment:** Uses a local GGUF model; the maintainers describe it as a single-user application.

6. **[AI Goat (dhammon)](https://github.com/dhammon/ai-goat)** — Vulnerable application. Study basic prompt injection and unsafe downstream use of model output through two local CTF-style applications. Source ID: `lab-rootcauz-ai-goat`.

   **Educational value:** Includes challenge source, solution documents, and optional CTFd scoring.

   **Environment:** Uses a local Vicuna model and Docker. The observed last repository push was in 2024; treat it as a historical learning reference and recheck dependencies.

7. **[Microsoft AI Red Teaming Playground Labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs)** — Training lab collection. Explore secret disclosure, instruction injection, and application integration failures in a configurable Chat Copilot training environment. Source ID: `lab-ms-playground`.

   **Educational value:** Includes challenge definitions, deployment files, notebooks, and accompanying course references.

   **Environment:** The documented container setup uses OpenAI or Azure OpenAI endpoints and credentials.

8. **[LLMForge](https://github.com/SasanLabs/LLMForge)** — Vulnerable application. Compare progressively defended prompt injection, LLM-mediated authorization, RAG poisoning, and retrieval data-exposure exercises. Source ID: `lab-llmforge`.

   **Educational value:** Contains separate lab controllers and level definitions within the OWASP VulnerableApp ecosystem.

   **Environment:** Uses Ollama chat and embedding models; first startup requires model downloads.

9. **[Damn Vulnerable AI Agent (OpenA2A)](https://github.com/opena2a-org/damn-vulnerable-ai-agent)** — Vulnerable application. Study agent memory manipulation, tool misuse, MCP weaknesses, and delegation trust failures across vulnerable agent scenarios. Source ID: `lab-opena2a-dvaa`.

   **Educational value:** Includes scenario documentation, expected-check records, and examples with different security controls.

   **Environment:** Distinguishes simulated responses from live LLM mode. The maintainer labels the project reference-only; agent availability can differ between source and published images.

10. **[AIGoat (AI Security Consortium)](https://github.com/AISecurityConsortium/AIGoat)** — Vulnerable application. Explore a vulnerable shopping assistant with a poisonable knowledge base, excessive agency, and progressively enabled defenses. Source ID: `lab-consortium-aigoat`.

   **Educational value:** Includes guided attack labs, challenge evaluators, and an instructor workshop guide.

   **Environment:** Uses a local Ollama-backed application. Training content has separate licensing terms from the application code.

11. **[Damn Vulnerable AI Platform (DVAP)](https://github.com/sonuoffsec/DVAP)** — Vulnerable application. Study vulnerable memory, retrieval, tool-output, agent identity, and domain-specific application workflows through documented lab scenarios. Source ID: `lab-dvap`.

   **Educational value:** Includes individual lab applications, challenge metadata, flags, and learning guidance.

   **Environment:** Uses Docker and Ollama. Its MCP-themed lab includes simplified HTTP endpoints; do not assume protocol-conformance coverage.

12. **[Damn Vulnerable AI Application (DVAIA)](https://github.com/airtasystems/DVAIA-Damn-Vulnerable-AI-Application)** — Vulnerable application. Explore vulnerable document ingestion, RAG context handling, web content ingestion, and tool-using agents in a local learning application. Source ID: `lab-dvaia`.

   **Educational value:** Provides application source and distinct interaction panels that expose how untrusted content reaches the model.

   **Environment:** Supports local and cloud model backends. Included here for its vulnerable application surfaces; auxiliary payload-generation features are not a separate archive entry.

## Additional sample and hosted lab collections

13. **[OWASP ASI Insecure Agent Samples](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/tree/main/initiatives/agent_security_initiative/code_samples)** — Training lab collection. Read deliberately insecure agent examples to connect framework configuration and application code to agentic security failures. Source ID: `lab-owasp-insecure-agents`.

   **Educational value:** The official OWASP collection separates examples by topic and includes explanatory material alongside code.

   **Environment:** A collection of samples rather than one deployable application; dependencies and model backends vary by example.

14. **[PortSwigger Web Security Academy: Web LLM Attacks](https://portswigger.net/web-security/llm-attacks)** — Hosted training labs. Practice LLM API misuse, indirect prompt injection, and unsafe output handling through guided web-application exercises. Source ID: `lab-portswigger-llm`.

   **Educational value:** Combines structured explanations with linked lab exercises and solution guidance.

   **Environment:** Hosted Academy exercises; application source and local deployment are not provided by this entry.

## Choosing a starting point

| Learning goal | Relevant resources |
| --- | --- |
| Guided LLM application exercises | SECFORCE LLMGoat; Microsoft Playground Labs; PortSwigger Academy |
| RAG poisoning and retrieval data exposure | LLMForge; AIGoat (AI Security Consortium); DVAIA |
| Agent tools, delegation, and memory | OWASP FinBot; Reversec's Damn Vulnerable LLM Agent; OpenA2A DVAA; OWASP ASI samples |
| MCP implementation and trust boundaries | Damn Vulnerable MCP Server; OpenA2A DVAA; DVAP's simplified MCP-themed exercises |
| ML and cloud infrastructure scenarios | Orca AI Goat |
| Compact historical exercises with solutions | AI Goat (dhammon) |

Projects with similar names are independent resources: Orca AI Goat, AI Goat (dhammon), and AIGoat (AI Security Consortium) have different maintainers and learning scopes.

Repository status and environment observations were checked on 2026-09-11. Maintainer claims about defense effectiveness, coverage, or benchmark scores are not independently validated here. See [CURATION.md](../CURATION.md) and [VALIDATION.md](../VALIDATION.md).
