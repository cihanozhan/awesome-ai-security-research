# Generative Models Security

[Back to the index](../README.md)

Diffusion and language-model memorization, backdoors, membership inference, and defensive unlearning.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

## Reading list

1. **[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://arxiv.org/abs/2401.05566)** — Paper; source year 2024. Examine persistent conditional behavior after subsequent safety training. Source ID: `sleeper-agents`.

2. **[The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks](https://arxiv.org/abs/1802.08232)** — Paper; source year 2018. Understand unintended memorization and exposure measurements in generative models. Source ID: `secret-sharer`.

3. **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** — Paper; source year 2020. Study recovery of memorized language-model training examples. Source ID: `llm-training-extraction`.

4. **[Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)** — Paper; source year 2022. Investigate how model and data properties influence memorization. Source ID: `quantifying-memorization`.

5. **[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)** — Paper; source year 2023. Study scalable training-data extraction from different language-model deployment settings. Source ID: `scalable-extraction`.

6. **[Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://arxiv.org/abs/1702.07464)** — Paper; source year 2017. Study information leakage in collaborative learning using generative models. Source ID: `collaborative-gan`.

7. **[Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188)** — Paper; source year 2023. Study memorization and recovery of images from diffusion training data. Source ID: `diffusion-extraction`.

8. **[How to Backdoor Diffusion Models?](https://arxiv.org/abs/2212.05400)** — Paper; source year 2022. Examine backdoor implantation in diffusion training processes. Source ID: `baddiffusion`.

9. **[VillanDiffusion: A Unified Backdoor Attack Framework for Diffusion Models](https://arxiv.org/abs/2306.06874)** — Paper; source year 2023. Study a unified formulation of backdoors across diffusion model settings. Source ID: `gen-villan`.

10. **[TrojDiff: Trojan Attacks on Diffusion Models with Diverse Targets](https://arxiv.org/abs/2303.05762)** — Paper; source year 2023. Examine diffusion backdoors with different attacker-selected output targets. Source ID: `gen-trojdiff`.

11. **[Membership Inference of Diffusion Models](https://arxiv.org/abs/2301.09956)** — Paper; source year 2023. Compare loss-based and likelihood-based membership inference against diffusion models. Source ID: `gen-mia-hu`.

12. **[Membership Inference Attacks against Diffusion Models](https://arxiv.org/abs/2302.03262)** — Paper; source year 2023. Examine privacy leakage from diffusion training membership. Source ID: `gen-mia-matsumoto`.

13. **[Are Diffusion Models Vulnerable to Membership Inference Attacks?](https://arxiv.org/abs/2302.01316)** — Paper; source year 2023. Study membership inference signals in diffusion denoising behavior. Source ID: `gen-mia-duan`.

14. **[Membership Inference Attacks on Diffusion Models via Quantile Regression](https://proceedings.mlr.press/v235/tang24g.html)** — Paper; source year 2024. Explore quantile-regression calibration for diffusion membership inference. Source ID: `gen-mia-quantile`.

15. **[Towards Black-Box Membership Inference Attack for Diffusion Models](https://proceedings.mlr.press/v267/li25k.html)** — Paper; source year 2025. Study membership inference with black-box access to diffusion models. Source ID: `gen-mia-blackbox`.

16. **[Towards More Realistic Membership Inference Attacks on Large Diffusion Models](https://openaccess.thecvf.com/content/WACV2024/html/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.html)** — Paper; source year 2024. Examine realistic evaluation assumptions for diffusion membership inference. Source ID: `gen-mia-realistic`.

17. **[Membership Inference on Text-to-Image Diffusion Models via Conditional Likelihood Discrepancy](https://arxiv.org/abs/2405.14800)** — Paper; source year 2024. Study conditional likelihood discrepancies as membership evidence. Source ID: `gen-mia-conditional`.

18. **[Attacks and Defenses for Generative Diffusion Models: A Comprehensive Survey](https://arxiv.org/abs/2408.03400)** — Survey; source year 2024. Survey attacks and defenses for generative diffusion systems. Source ID: `gen-survey`.

19. **[Erasing Undesirable Influence in Diffusion Models](https://arxiv.org/abs/2401.05779)** — Paper; source year 2024. Study removal of unwanted data influence from diffusion models. Source ID: `gen-erasediff`.

20. **[Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://arxiv.org/abs/2405.15234)** — Paper; source year 2024. Examine adversarial training for robust concept removal. Source ID: `gen-advunlearn`.

21. **[Data Unlearning in Diffusion Models](https://arxiv.org/abs/2503.01034)** — Paper; source year 2025. Study data unlearning objectives in diffusion models. Source ID: `gen-data-unlearn`.

22. **[Erasing Concepts from Diffusion Models](https://arxiv.org/abs/2303.07345)** — Paper; source year 2023. Understand concept erasure through diffusion model editing. Source ID: `gen-esd`.

23. **[Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models](https://arxiv.org/abs/2211.05105)** — Paper; source year 2022. Study safety guidance for latent diffusion generation. Source ID: `gen-safe-latent`.

24. **[Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning](https://arxiv.org/abs/2305.04175)** — Paper; source year 2023. Examine backdoors introduced through image-text training pairs. Source ID: `gen-multimodal-poison`.

25. **[BackdoorDM: A Comprehensive Benchmark for Backdoor Learning on Diffusion Model](https://papers.nips.cc/paper_files/paper/2025/hash/ba9b181cd30b4f1819583be24fdfeb17-Abstract-Datasets_and_Benchmarks_Track.html)** — Benchmark paper; source year 2026. Compare diffusion backdoors and defenses under a shared benchmark. Source ID: `gen-backdoordm`.

26. **[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/abs/2310.03693)** — Paper; source year 2023. Study how downstream fine-tuning can weaken safety behavior. Source ID: `llm-finetune`.

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
