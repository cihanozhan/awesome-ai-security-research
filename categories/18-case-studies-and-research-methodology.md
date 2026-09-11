# Case Studies and Research Methodology

[Back to the index](../README.md)

Published vulnerability studies, failed defense lessons, measurement validity, and reproducibility.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

This collection combines controlled research case studies and methodology papers. Inclusion does not imply that a paper describes a confirmed incident in a deployed production system.

## Reading list

1. **[Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)** — Survey; source year 2017. Trace the development of threat models across classical and deep learning. Source ID: `wild-patterns`.

2. **[Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)** — Paper; source year 2016. Examine optimization-based attacks and the evaluation of defensive distillation. Source ID: `cw`.

3. **[Reliable evaluation of adversarial robustness with an ensemble of diverse parameter-free attacks](https://arxiv.org/abs/2003.01690)** — Paper; source year 2020. Study reliable robustness evaluation with diverse parameter-free attacks. Source ID: `autoattack`.

4. **[RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)** — Benchmark paper; source year 2020. Compare robustness results under explicit shared evaluation settings. Source ID: `robustbench`.

5. **[Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420)** — Paper; source year 2018. Recognize misleading robustness caused by gradient masking. Source ID: `obfuscated-gradients`.

6. **[Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)** — Paper; source year 2019. Examine the hypothesis that adversarial vulnerability reflects predictive non-robust features. Source ID: `nonrobust-features`.

7. **[Robustness May Be at Odds with Accuracy](https://arxiv.org/abs/1805.12152)** — Paper; source year 2018. Analyze when robustness and accuracy objectives may conflict. Source ID: `robustness-accuracy`.

8. **[BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733)** — Paper; source year 2017. Understand hidden triggers and trust in outsourced model training. Source ID: `badnets`.

9. **[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://arxiv.org/abs/2401.05566)** — Paper; source year 2024. Examine persistent conditional behavior after subsequent safety training. Source ID: `sleeper-agents`.

10. **[Membership Inference Attacks From First Principles](https://arxiv.org/abs/2112.03570)** — Paper; source year 2021. Examine membership inference at low false-positive rates. Source ID: `membership-first-principles`.

11. **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** — Paper; source year 2020. Study recovery of memorized language-model training examples. Source ID: `llm-training-extraction`.

12. **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** — Paper; source year 2023. Understand instruction injection through external content and broken trust boundaries. Source ID: `indirect-injection`.

13. **[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://arxiv.org/abs/2406.13352)** — Benchmark paper; source year 2024. Evaluate prompt injection together with legitimate task completion in tool-using agents. Source ID: `agentdojo`.

14. **[HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal](https://arxiv.org/abs/2402.04249)** — Benchmark paper; source year 2024. Study standardized evaluations of harmful behavior and robust refusal. Source ID: `harmbench`.

15. **[JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models](https://arxiv.org/abs/2404.01318)** — Benchmark paper; source year 2024. Examine jailbreak threat models, behaviors, scoring, and reproducible artifacts. Source ID: `jailbreakbench`.

16. **[Dataset and Lessons Learned from the 2024 SaTML LLM Capture-the-Flag Competition](https://arxiv.org/abs/2406.07954)** — Competition paper; source year 2024. Study competition data and lessons from adversarial secret-protection tasks. Source ID: `satml-ctf`.

17. **[SoK: Gradient Inversion Attacks in Federated Learning](https://www.usenix.org/system/files/usenixsecurity25-carletti.pdf)** — SoK paper. Systematize gradient inversion assumptions and evaluation practices. Source ID: `fl-gradient-sok`.

18. **[CommanderSong: A Systematic Approach for Practical Adversarial Voice Recognition](https://www.usenix.org/conference/usenixsecurity18/presentation/yuan-xuejing)** — Paper; source year 2018. Examine commands concealed in audio content and physical playback conditions. Source ID: `audio-commandersong`.

19. **[Towards More Realistic Membership Inference Attacks on Large Diffusion Models](https://openaccess.thecvf.com/content/WACV2024/html/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.html)** — Paper; source year 2024. Examine realistic evaluation assumptions for diffusion membership inference. Source ID: `gen-mia-realistic`.

20. **[Rethinking the Privacy of Text Embeddings: A Reproducibility Study of "Text Embeddings Reveal (Almost) As Much As Text"](https://arxiv.org/abs/2507.07700)** — Reproducibility paper; source year 2025. Examine reproducibility and assumptions in text embedding inversion. Source ID: `rag-embedding-reproduction`.

21. **[Identifying the Risks of LM Agents with an LM-Emulated Sandbox](https://arxiv.org/abs/2309.15817)** — Benchmark paper; source year 2023. Study the opportunities and limits of language-model-emulated risk evaluations. Source ID: `agent-toolemu`.

22. **[A StrongREJECT for Empty Jailbreaks](https://arxiv.org/abs/2402.10260)** — Benchmark paper; source year 2024. Examine whether jailbreak scoring reflects genuinely useful harmful responses. Source ID: `bench-strongreject`.

23. **[XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models](https://arxiv.org/abs/2308.01263)** — Benchmark paper; source year 2023. Measure exaggerated refusal of legitimate requests. Source ID: `bench-xstest`.

24. **[DolphinAtack: Inaudible Voice Commands](https://arxiv.org/abs/1708.09537)** — Paper; source year 2017. Examine inaudible commands and nonlinear microphone behavior. Source ID: `audio-dolphin`.

25. **[Dos and Don'ts of Machine Learning in Computer Security](https://www.usenix.org/conference/usenixsecurity22/presentation/arp)** — Methodology paper; source year 2022. Recognize data leakage, unrealistic assumptions, and other experimental pitfalls. Source ID: `ml-dos-donts`.

26. **[MITRE ATLAS](https://atlas.mitre.org/)** — Threat knowledge base. Explore documented AI attack techniques, mitigations, and case studies. Source ID: `mitre-atlas`.

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
