# Awesome AI Security Research

AI Security Research: Papers, Documents, Standards and more...

An English-language knowledge archive of AI security and adversarial machine learning: papers, surveys, research reports, standards, evaluation studies, competition archives, and intentionally vulnerable learning applications.

**276 distinct sources · 466 category entries · 19 categories**

The practice collections contain four CTF resources and 14 vulnerable applications or training collections. Cross-listed sources retain one shared record in [data/resources.json](data/resources.json); category counts are not counts of globally unique works.

## Scope

The archive covers Machine Learning, Deep Learning, Reinforcement Learning, Computer Vision, LLMs, RAG, Vector Databases, Agentic AI, multi-agent systems, MCP, federated learning, graph learning, audio, multimodal systems, and generative models.

The primary purpose is to understand attacks, threat models, defenses, evidence, and research methods. Security-adjacent safety, privacy, and robustness work is included when it helps explain a specific threat or evaluation limitation.

Software catalogs, scanner lists, attack-framework directories, commercial product rankings, and generic AI tutorials are outside the scope. A paper about a named attack or benchmark is included as a research contribution. Reproduction code linked by its authors does not make that paper a tool listing. Vulnerable applications have a dedicated educational collection.

## How to read

Start with **Foundations, Taxonomies, and Education**, then choose a model family or attack surface. Use **Model Privacy and Model Extraction**, **Data Poisoning, Backdoors, and Model Supply Chain**, and **Defenses, Robustness, and Formal Verification** as complementary paths. Read **Benchmarks, Datasets, and Evaluation** and **Case Studies and Research Methodology** before interpreting attack success rates or defense claims.

Each entry provides a primary link, document type, source year where confirmed, a short reading focus, and a stable source ID. Entries are curated readings, not a leaderboard or an exhaustive ranking. Newer research and foundational work are both represented.

## Foundations, Taxonomies, and Education

Threat models, attacker capabilities, lifecycle stages, foundational readings, and research tutorials.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)** — Survey; source year 2017. Trace the development of threat models across classical and deep learning. Source ID: `wild-patterns`.

2. **[Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199)** — Paper; source year 2013. Study the discovery of adversarial examples and cross-model generalization. Source ID: `intriguing-properties`.

3. **[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)** — Paper; source year 2014. Understand linearity-based explanations and single-step adversarial perturbations. Source ID: `fgsm`.

4. **[Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)** — Paper; source year 2016. Examine optimization-based attacks and the evaluation of defensive distillation. Source ID: `cw`.

5. **[Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420)** — Paper; source year 2018. Recognize misleading robustness caused by gradient masking. Source ID: `obfuscated-gradients`.

6. **[Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083)** — Paper; source year 2017. Understand adversarial training as a robust optimization problem. Source ID: `madry`.

7. **[Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)** — Paper; source year 2019. Examine the hypothesis that adversarial vulnerability reflects predictive non-robust features. Source ID: `nonrobust-features`.

8. **[BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733)** — Paper; source year 2017. Understand hidden triggers and trust in outsourced model training. Source ID: `badnets`.

9. **[Poisoning Attacks against Support Vector Machines](https://arxiv.org/abs/1206.6389)** — Paper; source year 2012. Understand training-time poisoning against support vector machines. Source ID: `svm-poisoning`.

10. **[Deep Leakage from Gradients](https://arxiv.org/abs/1906.08935)** — Paper; source year 2019. Study reconstruction of training examples from shared gradients. Source ID: `dlg`.

11. **[Membership Inference Attacks against Machine Learning Models](https://arxiv.org/abs/1610.05820)** — Paper; source year 2016. Study how prediction behavior can reveal training-set membership. Source ID: `membership-inference`.

12. **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** — Paper; source year 2020. Study recovery of memorized language-model training examples. Source ID: `llm-training-extraction`.

13. **[Adversarial Attacks on Neural Network Policies](https://arxiv.org/abs/1702.02284)** — Paper; source year 2017. Understand observation perturbations against learned control policies. Source ID: `rl-policy-attacks`.

14. **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** — Paper; source year 2023. Understand instruction injection through external content and broken trust boundaries. Source ID: `indirect-injection`.

15. **[Security and Privacy Issues in Deep Reinforcement Learning: Threats and Countermeasures](https://doi.org/10.1145/3640312)** — Survey; source year 2024. Review security and privacy threats across the deep reinforcement learning lifecycle. Source ID: `rl-survey`.
   Access: Publisher record; full-text access was not checked.

16. **[Adversarial attack and defense in reinforcement learning-from AI security view](https://link.springer.com/article/10.1186/s42400-019-0027-x)** — Survey; source year 2019. Survey adversarial attack and defense concepts specific to reinforcement learning. Source ID: `rl-security-view`.

17. **[Backdoor Attacks and Defenses in Federated Learning: Survey, Challenges and Future Research Directions](https://arxiv.org/abs/2303.02213)** — Survey; source year 2023. Review federated backdoor threat models, defenses, and remaining challenges. Source ID: `fl-survey`.

18. **[Adversarial Attacks and Defenses on Graphs: A Review, A Tool and Empirical Studies](https://arxiv.org/abs/2003.00653)** — Survey; source year 2020. Review graph attack and defense assumptions alongside empirical comparisons. Source ID: `graph-survey`.

19. **[Attacks and Defenses for Generative Diffusion Models: A Comprehensive Survey](https://arxiv.org/abs/2408.03400)** — Survey; source year 2024. Survey attacks and defenses for generative diffusion systems. Source ID: `gen-survey`.

20. **[TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/abs/2401.05561)** — Benchmark paper; source year 2024. Review multiple dimensions of language-model trustworthiness. Source ID: `bench-trustllm`.

21. **[A Survey of Privacy Attacks in Machine Learning](https://arxiv.org/abs/2007.07646)** — Survey; source year 2020. Survey privacy attacks, attacker knowledge, and affected model families. Source ID: `privacy-survey`.

22. **[Adversarial Robustness: Theory and Practice](https://adversarial-ml-tutorial.org/)** — Tutorial. Build foundations in adversarial optimization, training, and robustness guarantees. Source ID: `aml-tutorial`.

23. **[Adversarial Machine Learning Reading List](https://nicholas.carlini.com/writing/2018/adversarial-machine-learning-reading-list.html)** — Reading list. Follow an expert reading sequence for adversarial examples and evaluation. Source ID: `aml-reading`.

24. **[Dos and Don'ts of Machine Learning in Computer Security](https://www.usenix.org/conference/usenixsecurity22/presentation/arp)** — Methodology paper; source year 2022. Recognize data leakage, unrealistic assumptions, and other experimental pitfalls. Source ID: `ml-dos-donts`.

25. **[NIST AI 100-2 E2025: Adversarial Machine Learning - A Taxonomy and Terminology of Attacks and Mitigations](https://csrc.nist.gov/pubs/ai/100/2/e2025/final)** — Technical report; source year 2025. Use consistent language for attacker goals, capabilities, knowledge, and lifecycle stages. Source ID: `nist-aml`.

26. **[OWASP AI Exchange](https://owaspai.org/)** — Community knowledge base. Explore AI threat categories, security controls, and shared terminology. Source ID: `owasp-exchange`.

## Machine Learning and Deep Learning Security

Classical and neural model evasion, transferability, query access, and security evaluation.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning](https://arxiv.org/abs/1712.03141)** — Survey; source year 2017. Trace the development of threat models across classical and deep learning. Source ID: `wild-patterns`.

2. **[Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199)** — Paper; source year 2013. Study the discovery of adversarial examples and cross-model generalization. Source ID: `intriguing-properties`.

3. **[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)** — Paper; source year 2014. Understand linearity-based explanations and single-step adversarial perturbations. Source ID: `fgsm`.

4. **[Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)** — Paper; source year 2016. Examine optimization-based attacks and the evaluation of defensive distillation. Source ID: `cw`.

5. **[The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528)** — Paper; source year 2015. Explore saliency-based feature modification under adversarial conditions. Source ID: `jsma`.

6. **[DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599)** — Paper; source year 2015. Understand boundary-based estimates of small adversarial perturbations. Source ID: `deepfool`.

7. **[Universal adversarial perturbations](https://arxiv.org/abs/1610.08401)** — Paper; source year 2016. Study input-agnostic perturbations and shared decision-boundary geometry. Source ID: `universal-perturbations`.

8. **[Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697)** — Paper; source year 2016. Examine substitute models and transferable attacks with limited target access. Source ID: `blackbox-practical`.

9. **[Adversarial Machine Learning at Scale](https://arxiv.org/abs/1611.01236)** — Paper; source year 2016. Study adversarial training and robustness evaluation at ImageNet scale. Source ID: `transferability`.

10. **[Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533)** — Paper; source year 2016. Examine whether adversarial examples remain effective after physical capture. Source ID: `physical-examples`.

11. **[ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models](https://arxiv.org/abs/1708.03999)** — Paper; source year 2017. Study zeroth-order optimization when model gradients are unavailable. Source ID: `zoo`.

12. **[Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/abs/1712.04248)** — Paper; source year 2017. Explore attacks using only the target model's final decisions. Source ID: `boundary-attack`.

13. **[Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598)** — Paper; source year 2018. Understand attacks with limited query budgets and limited prediction information. Source ID: `nes-attack`.

14. **[Prior Convictions: Black-Box Adversarial Attacks with Bandits and Priors](https://arxiv.org/abs/1807.07978)** — Paper; source year 2018. Study prior information and query efficiency in black-box attacks. Source ID: `bandits`.

15. **[HopSkipJumpAttack: A Query-Efficient Decision-Based Attack](https://arxiv.org/abs/1904.02144)** — Paper; source year 2019. Examine query-efficient decision-based adversarial optimization. Source ID: `hopskipjump`.

16. **[Square Attack: a query-efficient black-box adversarial attack via random search](https://arxiv.org/abs/1912.00049)** — Paper; source year 2019. Study randomized search for query-efficient score-based attacks. Source ID: `square-attack`.

17. **[Simple Black-box Adversarial Attacks](https://arxiv.org/abs/1905.07121)** — Paper; source year 2019. Understand a simple query-based black-box attack baseline. Source ID: `simba`.

18. **[Reliable evaluation of adversarial robustness with an ensemble of diverse parameter-free attacks](https://arxiv.org/abs/2003.01690)** — Paper; source year 2020. Study reliable robustness evaluation with diverse parameter-free attacks. Source ID: `autoattack`.

19. **[RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)** — Benchmark paper; source year 2020. Compare robustness results under explicit shared evaluation settings. Source ID: `robustbench`.

20. **[Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420)** — Paper; source year 2018. Recognize misleading robustness caused by gradient masking. Source ID: `obfuscated-gradients`.

21. **[Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083)** — Paper; source year 2017. Understand adversarial training as a robust optimization problem. Source ID: `madry`.

22. **[Theoretically Principled Trade-off between Robustness and Accuracy](https://arxiv.org/abs/1901.08573)** — Paper; source year 2019. Study the trade-off between standard accuracy and adversarial robustness. Source ID: `trades`.

23. **[Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)** — Paper; source year 2019. Examine the hypothesis that adversarial vulnerability reflects predictive non-robust features. Source ID: `nonrobust-features`.

24. **[Robustness May Be at Odds with Accuracy](https://arxiv.org/abs/1805.12152)** — Paper; source year 2018. Analyze when robustness and accuracy objectives may conflict. Source ID: `robustness-accuracy`.

25. **[Adversarially Robust Generalization Requires More Data](https://arxiv.org/abs/1804.11285)** — Paper; source year 2018. Study the data requirements of adversarial generalization. Source ID: `robust-generalization`.

## Data Poisoning, Backdoors, and Model Supply Chain

Training data corruption, hidden triggers, compromised training components, and model provenance.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733)** — Paper; source year 2017. Understand hidden triggers and trust in outsourced model training. Source ID: `badnets`.

2. **[Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks](https://arxiv.org/abs/1804.00792)** — Paper; source year 2018. Study targeted poisoning without changing training labels. Source ID: `poison-frogs`.

3. **[Poisoning Attacks against Support Vector Machines](https://arxiv.org/abs/1206.6389)** — Paper; source year 2012. Understand training-time poisoning against support vector machines. Source ID: `svm-poisoning`.

4. **[Witches' Brew: Industrial Scale Data Poisoning via Gradient Matching](https://arxiv.org/abs/2009.02276)** — Paper; source year 2020. Study gradient matching for targeted data poisoning. Source ID: `witches-brew`.

5. **[Hidden Trigger Backdoor Attacks](https://arxiv.org/abs/1910.00033)** — Paper; source year 2019. Explore backdoor learning with concealed trigger relationships. Source ID: `hidden-trigger`.

6. **[Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks](https://arxiv.org/abs/1805.12185)** — Paper; source year 2018. Examine pruning and fine-tuning as backdoor mitigation strategies. Source ID: `fine-pruning`.

7. **[Spectral Signatures in Backdoor Attacks](https://arxiv.org/abs/1811.00636)** — Paper; source year 2018. Study representation-space signals associated with poisoned training examples. Source ID: `spectral-signatures`.

8. **[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://arxiv.org/abs/2401.05566)** — Paper; source year 2024. Examine persistent conditional behavior after subsequent safety training. Source ID: `sleeper-agents`.

9. **[How To Backdoor Federated Learning](https://arxiv.org/abs/1807.00459)** — Paper; source year 2018. Understand model replacement attacks in federated learning. Source ID: `fl-backdoor`.

10. **[PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867)** — Paper; source year 2024. Study knowledge-base poisoning that changes retrieval-augmented answers. Source ID: `poisonedrag`.

11. **[How to Backdoor Diffusion Models?](https://arxiv.org/abs/2212.05400)** — Paper; source year 2022. Examine backdoor implantation in diffusion training processes. Source ID: `baddiffusion`.

12. **[Adversarial Inception Backdoor Attacks against Reinforcement Learning](https://proceedings.mlr.press/v267/rathbun25a.html)** — Paper; source year 2025. Study backdoor attacks under constraints on reward manipulation. Source ID: `rl-inception`.

13. **[Beyond Training-time Poisoning: Component-level and Post-training Backdoors in Deep Reinforcement Learning](https://arxiv.org/abs/2507.04883)** — Paper; source year 2025. Explore component-level and post-training backdoors in reinforcement learning. Source ID: `rl-components`.

14. **[Beware Untrusted Simulators -- Reward-Free Backdoor Attacks in Reinforcement Learning](https://arxiv.org/abs/2602.05089)** — Paper; source year 2026. Study simulator-based backdoors without direct reward manipulation. Source ID: `rl-untrusted-simulators`.

15. **[TrojDRL: Evaluation of Backdoor Attacks on Deep Reinforcement Learning](https://susmitjha.github.io/papers/AAAI20.pdf)** — Paper. Examine trigger-based backdoor behavior in learned control policies. Source ID: `rl-troj`.

16. **[Analyzing Federated Learning through an Adversarial Lens](https://arxiv.org/abs/1811.12470)** — Paper; source year 2018. Study targeted model poisoning by malicious federated participants. Source ID: `fl-malicious`.

17. **[DBA: Distributed Backdoor Attacks against Federated Learning](https://research.ibm.com/publications/dba-distributed-backdoor-attacks-against-federated-learning)** — Paper; source year 2020. Study distributed backdoor triggers across malicious federated clients. Source ID: `fl-dba`.

18. **[Graph Backdoor](https://arxiv.org/abs/2006.11890)** — Paper; source year 2020. Study backdoor triggers in graph learning. Source ID: `graph-backdoor`.

19. **[VillanDiffusion: A Unified Backdoor Attack Framework for Diffusion Models](https://arxiv.org/abs/2306.06874)** — Paper; source year 2023. Study a unified formulation of backdoors across diffusion model settings. Source ID: `gen-villan`.

20. **[TrojDiff: Trojan Attacks on Diffusion Models with Diverse Targets](https://arxiv.org/abs/2303.05762)** — Paper; source year 2023. Examine diffusion backdoors with different attacker-selected output targets. Source ID: `gen-trojdiff`.

21. **[Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning](https://arxiv.org/abs/2305.04175)** — Paper; source year 2023. Examine backdoors introduced through image-text training pairs. Source ID: `gen-multimodal-poison`.

22. **[Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/abs/2310.19156)** — Paper; source year 2023. Examine adversarial passages injected into retrieval corpora. Source ID: `rag-corpus-poison`.

23. **[AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)** — Paper; source year 2024. Study backdoors introduced through agent memory or knowledge bases. Source ID: `agent-poison`.

24. **[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/abs/2310.03693)** — Paper; source year 2023. Study how downstream fine-tuning can weaken safety behavior. Source ID: `llm-finetune`.

25. **[BackdoorBench: A Comprehensive Benchmark of Backdoor Learning](https://arxiv.org/abs/2206.12654)** — Benchmark paper; source year 2022. Compare backdoor attacks and defenses with shared evaluation procedures. Source ID: `bench-backdoor`.

26. **[ETSI GR SAI 002 V1.1.1: Data Supply Chain Security](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/002/01.01.01_60/gr_SAI002v010101p.pdf)** — Group report; source year 2021. Examine threats and controls in the AI data supply chain. Source ID: `etsi002`.

## Model Privacy and Model Extraction

Membership inference, memorization, reconstruction, gradient leakage, and functionality theft.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Deep Leakage from Gradients](https://arxiv.org/abs/1906.08935)** — Paper; source year 2019. Study reconstruction of training examples from shared gradients. Source ID: `dlg`.

2. **[Inverting Gradients -- How easy is it to break privacy in federated learning?](https://arxiv.org/abs/2003.14053)** — Paper; source year 2020. Examine practical image reconstruction from model gradients. Source ID: `inverting-gradients`.

3. **[iDLG: Improved Deep Leakage from Gradients](https://arxiv.org/abs/2001.02610)** — Paper; source year 2020. Understand label recovery and improvements to gradient leakage attacks. Source ID: `idlg`.

4. **[Membership Inference Attacks against Machine Learning Models](https://arxiv.org/abs/1610.05820)** — Paper; source year 2016. Study how prediction behavior can reveal training-set membership. Source ID: `membership-inference`.

5. **[Membership Inference Attacks From First Principles](https://arxiv.org/abs/2112.03570)** — Paper; source year 2021. Examine membership inference at low false-positive rates. Source ID: `membership-first-principles`.

6. **[Label-Only Membership Inference Attacks](https://arxiv.org/abs/2007.14321)** — Paper; source year 2020. Study membership inference when only predicted labels are visible. Source ID: `label-only-membership`.

7. **[ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models](https://arxiv.org/abs/1806.01246)** — Paper; source year 2018. Examine membership leakage with reduced assumptions about target data and models. Source ID: `ml-leaks`.

8. **[The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks](https://arxiv.org/abs/1802.08232)** — Paper; source year 2018. Understand unintended memorization and exposure measurements in generative models. Source ID: `secret-sharer`.

9. **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** — Paper; source year 2020. Study recovery of memorized language-model training examples. Source ID: `llm-training-extraction`.

10. **[Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)** — Paper; source year 2022. Investigate how model and data properties influence memorization. Source ID: `quantifying-memorization`.

11. **[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)** — Paper; source year 2023. Study scalable training-data extraction from different language-model deployment settings. Source ID: `scalable-extraction`.

12. **[Stealing Part of a Production Language Model](https://arxiv.org/abs/2403.06634)** — Paper; source year 2024. Examine extraction of components of production language models. Source ID: `stealing-llm-part`.

13. **[Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766)** — Paper; source year 2018. Study functionality extraction from image-classification prediction services. Source ID: `knockoff-nets`.

14. **[High Accuracy and High Fidelity Extraction of Neural Networks](https://arxiv.org/abs/1909.01838)** — Paper; source year 2019. Distinguish model-stealing accuracy from agreement with the target model. Source ID: `high-accuracy-high-fidelity`.

15. **[Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133)** — Paper; source year 2016. Understand differentially private training and its privacy-utility trade-offs. Source ID: `dp-deep-learning`.

16. **[Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://arxiv.org/abs/1702.07464)** — Paper; source year 2017. Study information leakage in collaborative learning using generative models. Source ID: `collaborative-gan`.

17. **[Text Embeddings Reveal (Almost) As Much As Text](https://arxiv.org/abs/2310.06816)** — Paper; source year 2023. Understand recovery of source text from dense embedding vectors. Source ID: `embedding-inversion`.

18. **[Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188)** — Paper; source year 2023. Study memorization and recovery of images from diffusion training data. Source ID: `diffusion-extraction`.

19. **[SoK: Gradient Inversion Attacks in Federated Learning](https://www.usenix.org/system/files/usenixsecurity25-carletti.pdf)** — SoK paper. Systematize gradient inversion assumptions and evaluation practices. Source ID: `fl-gradient-sok`.

20. **[Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models](https://arxiv.org/abs/2110.13057)** — Paper; source year 2021. Explore training-data leakage induced by malicious model design. Source ID: `fl-robbing`.

21. **[Eluding Secure Aggregation in Federated Learning via Model Inconsistency](https://arxiv.org/abs/2111.07380)** — Paper; source year 2021. Study privacy attacks enabled by inconsistent models sent to clients. Source ID: `fl-dishonest`.

22. **[Membership Inference of Diffusion Models](https://arxiv.org/abs/2301.09956)** — Paper; source year 2023. Compare loss-based and likelihood-based membership inference against diffusion models. Source ID: `gen-mia-hu`.

23. **[The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)](https://arxiv.org/abs/2402.16893)** — Paper; source year 2024. Study the privacy implications of attaching retrieved knowledge to language models. Source ID: `rag-privacy-goodbad`.

24. **[Stealing Machine Learning Models via Prediction APIs](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/tramer)** — Paper; source year 2016. Understand functionality extraction from prediction APIs. Source ID: `model-stealing`.

25. **[A Survey of Privacy Attacks in Machine Learning](https://arxiv.org/abs/2007.07646)** — Survey; source year 2020. Survey privacy attacks, attacker knowledge, and affected model families. Source ID: `privacy-survey`.

## Computer Vision and Physical Attacks

Classification, detection, segmentation, patches, physical transformations, and real-world sensing.

**28 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199)** — Paper; source year 2013. Study the discovery of adversarial examples and cross-model generalization. Source ID: `intriguing-properties`.

2. **[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)** — Paper; source year 2014. Understand linearity-based explanations and single-step adversarial perturbations. Source ID: `fgsm`.

3. **[Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)** — Paper; source year 2016. Examine optimization-based attacks and the evaluation of defensive distillation. Source ID: `cw`.

4. **[The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528)** — Paper; source year 2015. Explore saliency-based feature modification under adversarial conditions. Source ID: `jsma`.

5. **[DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599)** — Paper; source year 2015. Understand boundary-based estimates of small adversarial perturbations. Source ID: `deepfool`.

6. **[Universal adversarial perturbations](https://arxiv.org/abs/1610.08401)** — Paper; source year 2016. Study input-agnostic perturbations and shared decision-boundary geometry. Source ID: `universal-perturbations`.

7. **[Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697)** — Paper; source year 2016. Examine substitute models and transferable attacks with limited target access. Source ID: `blackbox-practical`.

8. **[Adversarial Machine Learning at Scale](https://arxiv.org/abs/1611.01236)** — Paper; source year 2016. Study adversarial training and robustness evaluation at ImageNet scale. Source ID: `transferability`.

9. **[Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533)** — Paper; source year 2016. Examine whether adversarial examples remain effective after physical capture. Source ID: `physical-examples`.

10. **[RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)** — Benchmark paper; source year 2020. Compare robustness results under explicit shared evaluation settings. Source ID: `robustbench`.

11. **[Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083)** — Paper; source year 2017. Understand adversarial training as a robust optimization problem. Source ID: `madry`.

12. **[Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)** — Paper; source year 2019. Examine the hypothesis that adversarial vulnerability reflects predictive non-robust features. Source ID: `nonrobust-features`.

13. **[BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733)** — Paper; source year 2017. Understand hidden triggers and trust in outsourced model training. Source ID: `badnets`.

14. **[Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks](https://arxiv.org/abs/1804.00792)** — Paper; source year 2018. Study targeted poisoning without changing training labels. Source ID: `poison-frogs`.

15. **[Hidden Trigger Backdoor Attacks](https://arxiv.org/abs/1910.00033)** — Paper; source year 2019. Explore backdoor learning with concealed trigger relationships. Source ID: `hidden-trigger`.

16. **[Knockoff Nets: Stealing Functionality of Black-Box Models](https://arxiv.org/abs/1812.02766)** — Paper; source year 2018. Study functionality extraction from image-classification prediction services. Source ID: `knockoff-nets`.

17. **[Adversarial Patch](https://arxiv.org/abs/1712.09665)** — Paper; source year 2017. Study visible universal patches under varying image conditions. Source ID: `adversarial-patch`.

18. **[Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945)** — Paper; source year 2017. Explore physically realizable perturbations against visual classifiers. Source ID: `robust-physical`.

19. **[Synthesizing Robust Adversarial Examples](https://arxiv.org/abs/1707.07397)** — Paper; source year 2017. Study robust adversarial objects under transformations and physical viewing conditions. Source ID: `3d-adversarial`.

20. **[Adversarial Examples for Semantic Segmentation and Object Detection](https://arxiv.org/abs/1703.08603)** — Paper; source year 2017. Study adversarial perturbations against detection and segmentation tasks. Source ID: `cv-detection`.

21. **[Adversarial T-shirt! Evading Person Detectors in A Physical World](https://arxiv.org/abs/1910.11099)** — Paper; source year 2019. Examine wearable perturbations under deformation and physical viewing conditions. Source ID: `cv-tshirt`.

22. **[DPatch: An Adversarial Patch Attack on Object Detectors](https://arxiv.org/abs/1806.02299)** — Paper; source year 2018. Study patch attacks against object detectors. Source ID: `cv-dpatch`.

23. **[Fooling automated surveillance cameras: adversarial patches to attack person detection](https://arxiv.org/abs/1904.08653)** — Paper; source year 2019. Examine printed patches that interfere with person detection. Source ID: `cv-surveillance`.

24. **[One pixel attack for fooling deep neural networks](https://arxiv.org/abs/1710.08864)** — Paper; source year 2017. Study sparse perturbations constrained to very few pixels. Source ID: `cv-onepixel`.

25. **[Spatially Transformed Adversarial Examples](https://arxiv.org/abs/1801.02612)** — Paper; source year 2018. Explore adversarial spatial transformations rather than additive noise. Source ID: `cv-spatial`.

26. **[Natural Adversarial Examples](https://arxiv.org/abs/1907.07174)** — Dataset paper; source year 2019. Study naturally occurring examples that are difficult for image classifiers. Source ID: `bench-imageneta`.

27. **[Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://arxiv.org/abs/1903.12261)** — Benchmark paper; source year 2019. Distinguish common corruption robustness from adversarial robustness. Source ID: `bench-imagenetc`.

28. **[Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)** — Paper; source year 2023. Study visual perturbations that undermine language-model safety behavior. Source ID: `multimodal-visual-jailbreak`.

## Reinforcement Learning Security

Observation attacks, malicious policies, reward poisoning, simulator backdoors, and robust control.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Adversarial Attacks on Neural Network Policies](https://arxiv.org/abs/1702.02284)** — Paper; source year 2017. Understand observation perturbations against learned control policies. Source ID: `rl-policy-attacks`.

2. **[Adversarial Policies: Attacking Deep Reinforcement Learning](https://arxiv.org/abs/1905.10615)** — Paper; source year 2019. Study malicious opponent behavior in multi-agent reinforcement learning. Source ID: `adversarial-policies`.

3. **[Reward Tampering Problems and Solutions in Reinforcement Learning: A Causal Influence Diagram Perspective](https://arxiv.org/abs/1908.04734)** — Paper; source year 2019. Analyze incentives to manipulate reward functions and reward inputs. Source ID: `reward-tampering`.

4. **[Robust Adversarial Reinforcement Learning](https://arxiv.org/abs/1703.02702)** — Paper; source year 2017. Study adversarial environment disturbances as a robustness training objective. Source ID: `rl-rarl`.

5. **[Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452)** — Paper; source year 2017. Examine timing and effectiveness of perturbations against deep policies. Source ID: `rl-delving`.

6. **[Robust Deep Reinforcement Learning with Adversarial Attacks](https://arxiv.org/abs/1712.03632)** — Paper; source year 2017. Study adversarial training for deep reinforcement learning policies. Source ID: `rl-pattanaik`.

7. **[Robust Reinforcement Learning using Adversarial Populations](https://arxiv.org/abs/2008.01825)** — Paper; source year 2020. Explore robustness against diverse populations of adversaries. Source ID: `rl-populations`.

8. **[Certifiable Robustness to Adversarial State Uncertainty in Deep Reinforcement Learning](https://arxiv.org/abs/2004.06496)** — Paper; source year 2020. Study robustness certificates for uncertain state observations. Source ID: `rl-certified`.

9. **[Characterizing Attacks on Deep Reinforcement Learning](https://arxiv.org/abs/1907.09470)** — Paper; source year 2019. Compare attack surfaces and assumptions in deep reinforcement learning. Source ID: `rl-characterizing`.

10. **[Robust Reinforcement Learning on State Observations with Learned Optimal Adversary](https://arxiv.org/abs/2101.08452)** — Paper; source year 2021. Explore learned adversaries for corrupted state observations. Source ID: `rl-optimal-adversary`.

11. **[Who Is the Strongest Enemy? Towards Optimal and Efficient Evasion Attacks in Deep RL](https://arxiv.org/abs/2106.05087)** — Paper; source year 2021. Study policy-space optimization for efficient evasion attacks. Source ID: `rl-strongest-enemy`.

12. **[Robust Deep Reinforcement Learning against Adversarial Perturbations on State Observations](https://arxiv.org/abs/2003.08938)** — Paper; source year 2020. Understand robust policies under adversarial state perturbations. Source ID: `rl-state-robust`.

13. **[Vulnerability of Deep Reinforcement Learning to Policy Induction Attacks](https://arxiv.org/abs/1701.04143)** — Paper; source year 2017. Study transfer-based manipulation of learned policies. Source ID: `rl-induction`.

14. **[Tactics of Adversarial Attack on Deep Reinforcement Learning Agents](https://arxiv.org/abs/1703.06748)** — Paper; source year 2017. Compare strategically timed attacks with attacks targeting a chosen future state. Source ID: `rl-tactics`.

15. **[Reward Poisoning in Reinforcement Learning: Attacks Against Unknown Learners in Unknown Environments](https://arxiv.org/abs/2102.08492)** — Paper; source year 2021. Study reward poisoning when the learner and environment are unknown. Source ID: `rl-reward-blackbox`.

16. **[Defense Against Reward Poisoning Attacks in Reinforcement Learning](https://arxiv.org/abs/2102.05776)** — Paper; source year 2021. Explore defenses against adversarial changes to reward signals. Source ID: `rl-reward-defense`.

17. **[Adaptive Reward-Poisoning Attacks against Reinforcement Learning](https://proceedings.mlr.press/v119/zhang20u.html)** — Paper; source year 2020. Study feasibility thresholds and adaptive reward poisoning. Source ID: `rl-adaptive-reward`.

18. **[Adversarial Inception Backdoor Attacks against Reinforcement Learning](https://proceedings.mlr.press/v267/rathbun25a.html)** — Paper; source year 2025. Study backdoor attacks under constraints on reward manipulation. Source ID: `rl-inception`.

19. **[Beyond Training-time Poisoning: Component-level and Post-training Backdoors in Deep Reinforcement Learning](https://arxiv.org/abs/2507.04883)** — Paper; source year 2025. Explore component-level and post-training backdoors in reinforcement learning. Source ID: `rl-components`.

20. **[Beware Untrusted Simulators -- Reward-Free Backdoor Attacks in Reinforcement Learning](https://arxiv.org/abs/2602.05089)** — Paper; source year 2026. Study simulator-based backdoors without direct reward manipulation. Source ID: `rl-untrusted-simulators`.

21. **[Security and Privacy Issues in Deep Reinforcement Learning: Threats and Countermeasures](https://doi.org/10.1145/3640312)** — Survey; source year 2024. Review security and privacy threats across the deep reinforcement learning lifecycle. Source ID: `rl-survey`.
   Access: Publisher record; full-text access was not checked.

22. **[Adversarial attack and defense in reinforcement learning-from AI security view](https://link.springer.com/article/10.1186/s42400-019-0027-x)** — Survey; source year 2019. Survey adversarial attack and defense concepts specific to reinforcement learning. Source ID: `rl-security-view`.

23. **[SUB-PLAY: Adversarial Policies against Partially Observed Multi-Agent Reinforcement Learning Systems](https://arxiv.org/abs/2402.03741)** — Paper; source year 2024. Study adversarial policies under partial observability in multi-agent systems. Source ID: `rl-subplay`.

24. **[TrojDRL: Evaluation of Backdoor Attacks on Deep Reinforcement Learning](https://susmitjha.github.io/papers/AAAI20.pdf)** — Paper. Examine trigger-based backdoor behavior in learned control policies. Source ID: `rl-troj`.

25. **[Mitigating Deep Reinforcement Learning Backdoors in the Neural Activation Space](https://arxiv.org/abs/2407.15168)** — Paper; source year 2024. Study stealthy policy backdoors and their detection. Source ID: `rl-neural-watchdog`.

## Federated Learning and Graph Learning Security

Distributed training threats, malicious aggregation participants, graph structure attacks, and privacy leakage.

**28 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[How To Backdoor Federated Learning](https://arxiv.org/abs/1807.00459)** — Paper; source year 2018. Understand model replacement attacks in federated learning. Source ID: `fl-backdoor`.

2. **[Deep Leakage from Gradients](https://arxiv.org/abs/1906.08935)** — Paper; source year 2019. Study reconstruction of training examples from shared gradients. Source ID: `dlg`.

3. **[Inverting Gradients -- How easy is it to break privacy in federated learning?](https://arxiv.org/abs/2003.14053)** — Paper; source year 2020. Examine practical image reconstruction from model gradients. Source ID: `inverting-gradients`.

4. **[iDLG: Improved Deep Leakage from Gradients](https://arxiv.org/abs/2001.02610)** — Paper; source year 2020. Understand label recovery and improvements to gradient leakage attacks. Source ID: `idlg`.

5. **[Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133)** — Paper; source year 2016. Understand differentially private training and its privacy-utility trade-offs. Source ID: `dp-deep-learning`.

6. **[Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning](https://arxiv.org/abs/1702.07464)** — Paper; source year 2017. Study information leakage in collaborative learning using generative models. Source ID: `collaborative-gan`.

7. **[Backdoor Attacks and Defenses in Federated Learning: Survey, Challenges and Future Research Directions](https://arxiv.org/abs/2303.02213)** — Survey; source year 2023. Review federated backdoor threat models, defenses, and remaining challenges. Source ID: `fl-survey`.

8. **[SoK: Gradient Inversion Attacks in Federated Learning](https://www.usenix.org/system/files/usenixsecurity25-carletti.pdf)** — SoK paper. Systematize gradient inversion assumptions and evaluation practices. Source ID: `fl-gradient-sok`.

9. **[Analyzing Federated Learning through an Adversarial Lens](https://arxiv.org/abs/1811.12470)** — Paper; source year 2018. Study targeted model poisoning by malicious federated participants. Source ID: `fl-malicious`.

10. **[A Little Is Enough: Circumventing Defenses For Distributed Learning](https://arxiv.org/abs/1902.06156)** — Paper; source year 2019. Examine distributed learning attacks designed to evade robust aggregation. Source ID: `fl-little`.

11. **[Local Model Poisoning Attacks to Byzantine-Robust Federated Learning](https://arxiv.org/abs/1911.11815)** — Paper; source year 2019. Study local model poisoning against Byzantine-robust aggregation. Source ID: `fl-fang`.

12. **[Mitigating Sybils in Federated Learning Poisoning](https://arxiv.org/abs/1808.04866)** — Paper; source year 2018. Understand defenses against colluding Sybil participants. Source ID: `fl-foolsgold`.

13. **[FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping](https://arxiv.org/abs/2012.13995)** — Paper; source year 2020. Examine trust bootstrapping for Byzantine-robust federated aggregation. Source ID: `fl-trust`.

14. **[DBA: Distributed Backdoor Attacks against Federated Learning](https://research.ibm.com/publications/dba-distributed-backdoor-attacks-against-federated-learning)** — Paper; source year 2020. Study distributed backdoor triggers across malicious federated clients. Source ID: `fl-dba`.

15. **[Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models](https://arxiv.org/abs/2110.13057)** — Paper; source year 2021. Explore training-data leakage induced by malicious model design. Source ID: `fl-robbing`.

16. **[Eluding Secure Aggregation in Federated Learning via Model Inconsistency](https://arxiv.org/abs/2111.07380)** — Paper; source year 2021. Study privacy attacks enabled by inconsistent models sent to clients. Source ID: `fl-dishonest`.

17. **[Adversarial Attacks and Defenses on Graphs: A Review, A Tool and Empirical Studies](https://arxiv.org/abs/2003.00653)** — Survey; source year 2020. Review graph attack and defense assumptions alongside empirical comparisons. Source ID: `graph-survey`.

18. **[Adversarial Attacks on Neural Networks for Graph Data](https://arxiv.org/abs/1805.07984)** — Paper; source year 2018. Study targeted changes to graph structure and node attributes. Source ID: `graph-nettack`.

19. **[Adversarial Attacks on Graph Neural Networks via Meta Learning](https://arxiv.org/abs/1902.08412)** — Paper; source year 2019. Understand poisoning graph neural networks through meta-learning. Source ID: `graph-metattack`.

20. **[Adversarial Attack on Graph Structured Data](https://arxiv.org/abs/1806.02371)** — Paper; source year 2018. Study adversarial manipulation of graph-structured inputs. Source ID: `graph-structure`.

21. **[Adversarial Attacks on Node Embeddings via Graph Poisoning](https://arxiv.org/abs/1809.01093)** — Paper; source year 2018. Examine poisoning attacks on learned node embeddings. Source ID: `graph-embedding`.

22. **[Graph Backdoor](https://arxiv.org/abs/2006.11890)** — Paper; source year 2020. Study backdoor triggers in graph learning. Source ID: `graph-backdoor`.

23. **[Backdoor Attacks to Graph Neural Networks](https://arxiv.org/abs/2006.11165)** — Paper; source year 2020. Examine trigger-based attacks against graph neural networks. Source ID: `graph-backdoor2`.

24. **[Graph Structure Learning for Robust Graph Neural Networks](https://arxiv.org/abs/2005.10203)** — Paper; source year 2020. Study graph structure learning as a robustness defense. Source ID: `graph-prognn`.

25. **[GNNGuard: Defending Graph Neural Networks against Adversarial Attacks](https://arxiv.org/abs/2006.08149)** — Paper; source year 2020. Examine defenses that account for suspicious graph connections. Source ID: `graph-guard`.

26. **[Certifiable Robustness to Graph Perturbations](https://arxiv.org/abs/1910.14356)** — Paper; source year 2019. Understand certificates against discrete graph perturbations. Source ID: `graph-cert`.

27. **[Data Poisoning Attack against Knowledge Graph Embedding](https://arxiv.org/abs/1904.12052)** — Paper; source year 2019. Study poisoning of knowledge graph embeddings used in retrieval and reasoning. Source ID: `graph-kg-poison`.

28. **[Learning to Deceive Knowledge Graph Augmented Models via Targeted Perturbation](https://arxiv.org/abs/2010.12872)** — Paper; source year 2020. Explore targeted perturbations of knowledge graph augmented models. Source ID: `graph-kg-deceive`.

## LLM Security

Prompt injection, jailbreaks, fine-tuning risks, memorization, and adversarial NLP foundations.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://arxiv.org/abs/2401.05566)** — Paper; source year 2024. Examine persistent conditional behavior after subsequent safety training. Source ID: `sleeper-agents`.

2. **[The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks](https://arxiv.org/abs/1802.08232)** — Paper; source year 2018. Understand unintended memorization and exposure measurements in generative models. Source ID: `secret-sharer`.

3. **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** — Paper; source year 2020. Study recovery of memorized language-model training examples. Source ID: `llm-training-extraction`.

4. **[Quantifying Memorization Across Neural Language Models](https://arxiv.org/abs/2202.07646)** — Paper; source year 2022. Investigate how model and data properties influence memorization. Source ID: `quantifying-memorization`.

5. **[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)** — Paper; source year 2023. Study scalable training-data extraction from different language-model deployment settings. Source ID: `scalable-extraction`.

6. **[Stealing Part of a Production Language Model](https://arxiv.org/abs/2403.06634)** — Paper; source year 2024. Examine extraction of components of production language models. Source ID: `stealing-llm-part`.

7. **[Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** — Paper; source year 2023. Understand instruction injection through external content and broken trust boundaries. Source ID: `indirect-injection`.

8. **[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)** — Paper; source year 2023. Study transferable adversarial suffixes against aligned language models. Source ID: `gcg`.

9. **[HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal](https://arxiv.org/abs/2402.04249)** — Benchmark paper; source year 2024. Study standardized evaluations of harmful behavior and robust refusal. Source ID: `harmbench`.

10. **[JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models](https://arxiv.org/abs/2404.01318)** — Benchmark paper; source year 2024. Examine jailbreak threat models, behaviors, scoring, and reproducible artifacts. Source ID: `jailbreakbench`.

11. **[Benchmarking and Defending Against Indirect Prompt Injection Attacks on Large Language Models](https://arxiv.org/abs/2312.14197)** — Benchmark paper; source year 2023. Study indirect injection and defenses over externally supplied content. Source ID: `bipia`.

12. **[Jailbreaking Black Box Large Language Models in Twenty Queries](https://arxiv.org/abs/2310.08419)** — Paper; source year 2023. Study iterative black-box jailbreak refinement through model feedback. Source ID: `llm-pair`.

13. **[Tree of Attacks: Jailbreaking Black-Box LLMs Automatically](https://arxiv.org/abs/2312.02119)** — Paper; source year 2023. Examine tree search and pruning in automated jailbreak generation. Source ID: `llm-tap`.

14. **[AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models](https://arxiv.org/abs/2310.04451)** — Paper; source year 2023. Study automatically generated jailbreaks designed to remain interpretable. Source ID: `llm-autodan`.

15. **[DeepInception: Hypnotize Large Language Model to Be Jailbreaker](https://arxiv.org/abs/2311.03191)** — Paper; source year 2023. Examine nested fictional contexts as a jailbreaking mechanism. Source ID: `llm-deepinception`.

16. **[ArtPrompt: ASCII Art-based Jailbreak Attacks against Aligned LLMs](https://arxiv.org/abs/2402.11753)** — Paper; source year 2024. Study attacks exploiting the gap between visual text patterns and safety interpretation. Source ID: `llm-artprompt`.

17. **[Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack](https://arxiv.org/abs/2404.01833)** — Paper; source year 2024. Understand gradual multi-turn escalation in jailbreak conversations. Source ID: `llm-crescendo`.

18. **[The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions](https://arxiv.org/abs/2404.13208)** — Paper; source year 2024. Study instruction priority training for handling untrusted prompts. Source ID: `llm-hierarchy`.

19. **[Defending Against Indirect Prompt Injection Attacks With Spotlighting](https://arxiv.org/abs/2403.14720)** — Paper; source year 2024. Examine input transformations that mark externally supplied content as untrusted. Source ID: `llm-spotlighting`.

20. **[StruQ: Defending Against Prompt Injection with Structured Queries](https://arxiv.org/abs/2402.06363)** — Paper; source year 2024. Study structured separation of instructions and data against injection. Source ID: `llm-struq`.

21. **[SecAlign: Defending Against Prompt Injection with Preference Optimization](https://arxiv.org/abs/2410.05451)** — Paper; source year 2024. Explore preference optimization for resistance to prompt injection. Source ID: `llm-secalign`.

22. **[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/abs/2310.03693)** — Paper; source year 2023. Study how downstream fine-tuning can weaken safety behavior. Source ID: `llm-finetune`.

23. **[Universal Adversarial Triggers for Attacking and Analyzing NLP](https://arxiv.org/abs/1908.07125)** — Paper; source year 2019. Understand input-agnostic adversarial triggers for NLP models. Source ID: `llm-universal-triggers`.

24. **[HotFlip: White-Box Adversarial Examples for Text Classification](https://arxiv.org/abs/1712.06751)** — Paper; source year 2017. Study gradient-guided discrete changes to text inputs. Source ID: `llm-hotflip`.

25. **[Is BERT Really Robust? A Strong Baseline for Natural Language Attack on Text Classification and Entailment](https://arxiv.org/abs/1907.11932)** — Paper; source year 2019. Examine black-box text substitutions that preserve meaning while changing predictions. Source ID: `llm-textfooler`.

26. **[BERT-ATTACK: Adversarial Attack Against BERT Using BERT](https://arxiv.org/abs/2004.09984)** — Paper; source year 2020. Study language-model-guided adversarial word substitutions. Source ID: `llm-bertattack`.

## RAG, Embedding, and Retrieval Security

Corpus poisoning, retrieval corruption, embedding inversion, knowledge extraction, and retrieval privacy.

**27 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

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

## Vector Database Security

Embedding confidentiality, corpus and vector poisoning, private similarity search, tenant isolation, and database access controls.

**26 sources:** 23 research papers, preprints, or reproducibility studies, and three official technical documents. Eighteen sources are new to the archive; eight are cross-listed from related categories.

This category follows the vector storage and retrieval layer: stored embeddings, nearest-neighbor rankings, query confidentiality, metadata filters, and tenant boundaries. Some studies demonstrate application-level consequences of poisoned retrieval rather than a vulnerability in a particular database engine. Curator provides indexing background rather than an attack study.

### Embedding privacy and reconstruction

1. **[Text Embeddings Reveal (Almost) As Much As Text](https://arxiv.org/abs/2310.06816)** — Paper; source year 2023. Study reconstruction of stored source text from exposed dense embedding vectors. Source ID: `embedding-inversion`.

2. **[Rethinking the Privacy of Text Embeddings: A Reproducibility Study of "Text Embeddings Reveal (Almost) As Much As Text"](https://arxiv.org/abs/2507.07700)** — Reproducibility paper; source year 2025. Check how reproducibility, auxiliary data, and model assumptions affect embedding-inversion claims. Source ID: `rag-embedding-reproduction`.

3. **[Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence](https://aclanthology.org/2023.findings-acl.881/)** — Paper; source year 2023. Understand how a generative inversion model can reconstruct source sentences from exposed embedding vectors. Source ID: `vector-geia`.

4. **[Transferable Embedding Inversion Attack: Uncovering Privacy Risks in Text Embeddings without Model Queries](https://aclanthology.org/2024.acl-long.230/)** — Paper; source year 2024. Study embedding reconstruction when the attacker cannot query the target embedding model. Source ID: `vector-transfer-inversion`.

5. **[Information Leakage of Sentence Embeddings via Generative Embedding Inversion Attacks](https://arxiv.org/abs/2504.16609)** — Reproducibility paper; source year 2025. Examine reproduced embedding-inversion results and the distinction between input reconstruction and training-data leakage. Source ID: `vector-geia-reproduction`.

6. **[Information Leakage in Embedding Models](https://arxiv.org/abs/2004.00053)** — Paper; source year 2020. Distinguish inversion, sensitive-attribute inference, and membership leakage from embedding representations. Source ID: `vector-embedding-leakage`.

### Corpus poisoning and retrieval manipulation

7. **[PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867)** — Paper; source year 2024. Trace how corrupted knowledge-base content influences retrieval and downstream generated answers. Source ID: `poisonedrag`.

8. **[Poisoning Retrieval Corpora by Injecting Adversarial Passages](https://arxiv.org/abs/2310.19156)** — Paper; source year 2023. Study poisoned passage insertion into a dense retrieval corpus and generalization to unseen queries. Source ID: `rag-corpus-poison`.

9. **[AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)** — Paper; source year 2024. Examine poisoned retrieval memories and knowledge bases as entry points for agent backdoors. Source ID: `agent-poison`.

10. **[Unsupervised Corpus Poisoning Attacks in Continuous Space for Dense Retrieval](https://arxiv.org/abs/2504.17884)** — Paper; source year 2025. Compare continuous embedding-space poisoning with attacks that must produce valid text passages. Source ID: `vector-continuous-poison`.

11. **[Corpus Poisoning via Approximate Greedy Gradient Descent](https://aclanthology.org/2025.findings-acl.222/)** — Paper; source year 2025. Study adversarial passage construction and its effect on top-ranked dense retrieval results. Source ID: `vector-aggd`.

12. **[Tricking Retrievers with Influential Tokens: An Efficient Black-Box Corpus Poisoning Attack](https://aclanthology.org/2025.naacl-long.210/)** — Paper; source year 2025. Examine black-box manipulation of retrieval through influential tokens in poisoned passages. Source ID: `vector-diga`.

13. **[GASLITEing the Retrieval: Exploring Vulnerabilities in Dense Embedding-based Search](https://arxiv.org/abs/2412.20953)** — Paper; source year 2024. Analyze malicious passage promotion under different attacker knowledge and query-distribution assumptions. Source ID: `vector-gaslite`.

14. **[Can You Trust the Vectors in Your Vector Database? Black-Hole Attack from Embedding Space Defects](https://arxiv.org/abs/2604.05480)** — Preprint; source year 2026. Study centrality-driven hubness and malicious vectors that attract disproportionate nearest-neighbor matches. Source ID: `vector-black-hole`.

### Private similarity search and protected embeddings

15. **[Certifiably Robust RAG against Retrieval Corruption](https://arxiv.org/abs/2405.15556)** — Paper; source year 2024. Read bounded retrieval-corruption guarantees and the assumptions limiting their scope. Source ID: `rag-certified`.

16. **[Sentence-level Privacy for Document Embeddings](https://aclanthology.org/2022.acl-long.238/)** — Paper; source year 2022. Study sentence-level differential privacy and the utility trade-offs of protecting document representations. Source ID: `vector-sentence-dp`.

17. **[Don't forget private retrieval: distributed private similarity search for large language models](https://aclanthology.org/2024.privatenlp-1.2/)** — Paper; source year 2024. Explore multi-party computation for private top-k retrieval and the required distributed-server assumptions. Source ID: `vector-prag`.

18. **[Private Web Search with Tiptoe](https://people.eecs.berkeley.edu/~henrycg/pubs/tiptoe/)** — Paper; source year 2023. Study the reduction of private semantic search to private nearest-neighbor retrieval using cryptography. Source ID: `vector-tiptoe`.

19. **[SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)** — Paper; source year 2020. Examine query and result confidentiality for approximate nearest-neighbor search under a semi-honest threat model. Source ID: `vector-sanns`.

20. **[Approximate Distance-Comparison-Preserving Symmetric Encryption](https://eprint.iacr.org/2021/1666)** — Paper; source year 2021. Examine searchable encrypted vectors and the leakage implications of preserving distance-comparison information. Source ID: `vector-dcpe`.

### Evaluation and downstream exposure

21. **[The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)](https://arxiv.org/abs/2402.16893)** — Paper; source year 2024. Examine how a retrieval layer changes the privacy exposure of stored knowledge. Source ID: `rag-privacy-goodbad`.

22. **[Towards More Robust Retrieval-Augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks](https://arxiv.org/abs/2412.16708)** — Paper; source year 2024. Compare retrieval-stage poisoning effects with downstream answer robustness in a shared evaluation setting. Source ID: `rag-evalpoison`.

### Tenant isolation and database access controls

23. **[Curator: Efficient Indexing for Multi-Tenant Vector Databases](https://arxiv.org/abs/2401.07119)** — Architecture paper; source year 2024. Study tenant-aware index organization and filtering as background for reasoning about data isolation and search performance. Source ID: `vector-curator`.

24. **[Qdrant: Security and Access Control](https://qdrant.tech/documentation/security/)** — Official documentation. Review authentication, collection-scoped permissions, transport security, and network exposure controls for a vector store. Source ID: `vector-qdrant-security`.

25. **[Weaviate: Authorization](https://docs.weaviate.io/deploy/configuration/authorization)** — Official documentation. Study role-based permissions and authorization boundaries for vector database operations. Source ID: `vector-weaviate-rbac`.

26. **[Pinecone: Implement Multitenancy](https://docs.pinecone.io/guides/index-data/implement-multitenancy)** — Official documentation. Examine namespace-based tenant separation and the application responsibility for choosing the authorized tenant scope. Source ID: `vector-pinecone-tenancy`.

### Reading priorities

Start with *Information Leakage in Embedding Models* and *Text Embeddings Reveal (Almost) As Much As Text* for confidentiality. Follow *Poisoning Retrieval Corpora*, *GASLITEing the Retrieval*, and the *Black-Hole Attack* preprint for retrieval integrity. Use *SANNS*, *Tiptoe*, and *PRAG* to compare private-search designs. Read *Curator* alongside the official access-control documents for tenant-aware retrieval.

Compare attacker capabilities carefully: reading stored vectors, querying an embedding service, inserting text documents, and directly inserting arbitrary vectors are different threat models. Cryptographic and robustness guarantees apply under each paper's stated assumptions; transport or storage encryption alone does not establish private search. Tenant namespaces and metadata filtering require correct application authorization.

The three product-specific entries are technical reading references about security controls, not a database product catalog. Documentation was checked on 2026-09-11; deployment versions and supported controls should be verified before application. No experiments or database deployments were executed for this collection.

## Agentic AI, Multi-Agent, and MCP Security

Agent actions, memory, tool descriptions, trust boundaries, malicious interactions, and protocol security.

**27 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

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

## Audio, Speech, and Multimodal Security

Speech recognition attacks, inaudible commands, image-text attacks, and cross-modal instruction injection.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Adversarial Patch](https://arxiv.org/abs/1712.09665)** — Paper; source year 2017. Study visible universal patches under varying image conditions. Source ID: `adversarial-patch`.

2. **[Audio Adversarial Examples: Targeted Attacks on Speech-to-Text](https://arxiv.org/abs/1801.01944)** — Paper; source year 2018. Study targeted perturbations that alter speech-to-text output. Source ID: `audio-cw`.

3. **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** — Paper; source year 2023. Understand instruction injection carried by image and audio inputs. Source ID: `multimodal-indirect`.

4. **[Inaudible Voice Commands](https://arxiv.org/abs/1708.07238)** — Paper; source year 2017. Study inaudible command injection and microphone input assumptions. Source ID: `audio-inaudible`.

5. **[CommanderSong: A Systematic Approach for Practical Adversarial Voice Recognition](https://www.usenix.org/conference/usenixsecurity18/presentation/yuan-xuejing)** — Paper; source year 2018. Examine commands concealed in audio content and physical playback conditions. Source ID: `audio-commandersong`.

6. **[Adversarial Black-Box Attacks on Automatic Speech Recognition Systems using Multi-Objective Evolutionary Optimization](https://arxiv.org/abs/1811.01312)** — Paper; source year 2018. Study black-box speech attacks using multi-objective genetic search. Source ID: `audio-genetic`.

7. **[Adversarial Attacks Against Automatic Speech Recognition Systems via Psychoacoustic Hiding](https://arxiv.org/abs/1808.05665)** — Paper; source year 2018. Understand attacks constrained by psychoacoustic masking. Source ID: `audio-psychoacoustic`.

8. **[Robust Audio Adversarial Example for a Physical Attack](https://arxiv.org/abs/1810.11793)** — Paper; source year 2018. Study audio perturbations designed to survive physical playback. Source ID: `audio-physical`.

9. **[Characterizing Audio Adversarial Examples Using Temporal Dependency](https://arxiv.org/abs/1809.10875)** — Paper; source year 2018. Examine temporal dependencies as evidence for audio attack detection. Source ID: `audio-temporal`.

10. **[Practical Hidden Voice Attacks against Speech and Speaker Recognition Systems](https://arxiv.org/abs/1904.05734)** — Paper; source year 2019. Explore hidden-command risks in speech and speaker recognition. Source ID: `audio-hidden`.

11. **[Hear "No Evil", See "Kenansville": Efficient and Transferable Black-Box Attacks on Speech Recognition and Voice Identification Systems](https://arxiv.org/abs/1910.05262)** — Paper; source year 2019. Study efficient transferable attacks on voice identification and transcription. Source ID: `audio-kenansville`.

12. **[SirenAttack: Generating Adversarial Audio for End-to-End Acoustic Systems](https://arxiv.org/abs/1901.07846)** — Paper; source year 2019. Examine adversarial audio generation for end-to-end acoustic systems. Source ID: `audio-siren`.

13. **[Weighted-Sampling Audio Adversarial Example Attack](https://arxiv.org/abs/1901.10300)** — Paper; source year 2019. Explore weighted sampling for audio perturbation generation. Source ID: `audio-weighted`.

14. **[Universal Adversarial Perturbations for Speech Recognition Systems](https://arxiv.org/abs/1905.03828)** — Paper; source year 2019. Study perturbations shared across speech recognition inputs. Source ID: `audio-universal`.

15. **[Imperceptible, Robust, and Targeted Adversarial Examples for Automatic Speech Recognition](https://arxiv.org/abs/1903.10346)** — Paper; source year 2019. Compare perceptual constraints, targeted transcription, and physical robustness. Source ID: `audio-imperceptible`.

16. **[Imperio: Robust Over-the-Air Adversarial Examples for Automatic Speech Recognition Systems](https://arxiv.org/abs/1908.01551)** — Paper; source year 2019. Study over-the-air adversarial examples for speech recognition. Source ID: `audio-imperio`.

17. **[Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning](https://arxiv.org/abs/2305.04175)** — Paper; source year 2023. Examine backdoors introduced through image-text training pairs. Source ID: `gen-multimodal-poison`.

18. **[ArtPrompt: ASCII Art-based Jailbreak Attacks against Aligned LLMs](https://arxiv.org/abs/2402.11753)** — Paper; source year 2024. Study attacks exploiting the gap between visual text patterns and safety interpretation. Source ID: `llm-artprompt`.

19. **[Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)** — Paper; source year 2023. Study visual perturbations that undermine language-model safety behavior. Source ID: `multimodal-visual-jailbreak`.

20. **[Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://arxiv.org/abs/2402.08567)** — Paper; source year 2024. Examine propagation of adversarial content through multimodal agent interactions. Source ID: `multimodal-agent-smith`.

21. **[FigStep: Jailbreaking Large Vision-Language Models via Typographic Visual Prompts](https://arxiv.org/abs/2311.05608)** — Paper; source year 2023. Study typographic visual prompts and cross-modal safety gaps. Source ID: `multimodal-figstep`.

22. **[MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/abs/2311.17600)** — Benchmark paper; source year 2023. Evaluate multimodal safety across image-text scenarios. Source ID: `multimodal-safetybench`.

23. **[JailBreakV: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2404.03027)** — Benchmark paper; source year 2024. Study transfer of jailbreaks across text and multimodal settings. Source ID: `multimodal-jailbreakv`.

24. **[DolphinAtack: Inaudible Voice Commands](https://arxiv.org/abs/1708.09537)** — Paper; source year 2017. Examine inaudible commands and nonlinear microphone behavior. Source ID: `audio-dolphin`.

25. **[Hidden Voice Commands](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/carlini)** — Paper; source year 2016. Study audio commands intelligible to machines but difficult for people to recognize. Source ID: `audio-hiddencommands`.

## Generative Models Security

Diffusion and language-model memorization, backdoors, membership inference, and defensive unlearning.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

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

## Defenses, Robustness, and Formal Verification

Adversarial training, privacy protection, certified robustness, backdoor mitigation, and injection defenses.

**27 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

1. **[Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644)** — Paper; source year 2016. Examine optimization-based attacks and the evaluation of defensive distillation. Source ID: `cw`.

2. **[Reliable evaluation of adversarial robustness with an ensemble of diverse parameter-free attacks](https://arxiv.org/abs/2003.01690)** — Paper; source year 2020. Study reliable robustness evaluation with diverse parameter-free attacks. Source ID: `autoattack`.

3. **[RobustBench: a standardized adversarial robustness benchmark](https://arxiv.org/abs/2010.09670)** — Benchmark paper; source year 2020. Compare robustness results under explicit shared evaluation settings. Source ID: `robustbench`.

4. **[Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420)** — Paper; source year 2018. Recognize misleading robustness caused by gradient masking. Source ID: `obfuscated-gradients`.

5. **[Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083)** — Paper; source year 2017. Understand adversarial training as a robust optimization problem. Source ID: `madry`.

6. **[Theoretically Principled Trade-off between Robustness and Accuracy](https://arxiv.org/abs/1901.08573)** — Paper; source year 2019. Study the trade-off between standard accuracy and adversarial robustness. Source ID: `trades`.

7. **[Robustness May Be at Odds with Accuracy](https://arxiv.org/abs/1805.12152)** — Paper; source year 2018. Analyze when robustness and accuracy objectives may conflict. Source ID: `robustness-accuracy`.

8. **[Adversarially Robust Generalization Requires More Data](https://arxiv.org/abs/1804.11285)** — Paper; source year 2018. Study the data requirements of adversarial generalization. Source ID: `robust-generalization`.

9. **[Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks](https://arxiv.org/abs/1805.12185)** — Paper; source year 2018. Examine pruning and fine-tuning as backdoor mitigation strategies. Source ID: `fine-pruning`.

10. **[Spectral Signatures in Backdoor Attacks](https://arxiv.org/abs/1811.00636)** — Paper; source year 2018. Study representation-space signals associated with poisoned training examples. Source ID: `spectral-signatures`.

11. **[Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133)** — Paper; source year 2016. Understand differentially private training and its privacy-utility trade-offs. Source ID: `dp-deep-learning`.

12. **[Certified Adversarial Robustness via Randomized Smoothing](https://arxiv.org/abs/1902.02918)** — Paper; source year 2019. Understand randomized smoothing and norm-bounded robustness certificates. Source ID: `smoothing`.

13. **[Robust Adversarial Reinforcement Learning](https://arxiv.org/abs/1703.02702)** — Paper; source year 2017. Study adversarial environment disturbances as a robustness training objective. Source ID: `rl-rarl`.

14. **[Certifiable Robustness to Adversarial State Uncertainty in Deep Reinforcement Learning](https://arxiv.org/abs/2004.06496)** — Paper; source year 2020. Study robustness certificates for uncertain state observations. Source ID: `rl-certified`.

15. **[Robust Deep Reinforcement Learning against Adversarial Perturbations on State Observations](https://arxiv.org/abs/2003.08938)** — Paper; source year 2020. Understand robust policies under adversarial state perturbations. Source ID: `rl-state-robust`.

16. **[Defense Against Reward Poisoning Attacks in Reinforcement Learning](https://arxiv.org/abs/2102.05776)** — Paper; source year 2021. Explore defenses against adversarial changes to reward signals. Source ID: `rl-reward-defense`.

17. **[FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping](https://arxiv.org/abs/2012.13995)** — Paper; source year 2020. Examine trust bootstrapping for Byzantine-robust federated aggregation. Source ID: `fl-trust`.

18. **[Graph Structure Learning for Robust Graph Neural Networks](https://arxiv.org/abs/2005.10203)** — Paper; source year 2020. Study graph structure learning as a robustness defense. Source ID: `graph-prognn`.

19. **[GNNGuard: Defending Graph Neural Networks against Adversarial Attacks](https://arxiv.org/abs/2006.08149)** — Paper; source year 2020. Examine defenses that account for suspicious graph connections. Source ID: `graph-guard`.

20. **[Certifiable Robustness to Graph Perturbations](https://arxiv.org/abs/1910.14356)** — Paper; source year 2019. Understand certificates against discrete graph perturbations. Source ID: `graph-cert`.

21. **[Characterizing Audio Adversarial Examples Using Temporal Dependency](https://arxiv.org/abs/1809.10875)** — Paper; source year 2018. Examine temporal dependencies as evidence for audio attack detection. Source ID: `audio-temporal`.

22. **[Defensive Unlearning with Adversarial Training for Robust Concept Erasure in Diffusion Models](https://arxiv.org/abs/2405.15234)** — Paper; source year 2024. Examine adversarial training for robust concept removal. Source ID: `gen-advunlearn`.

23. **[Certifiably Robust RAG against Retrieval Corruption](https://arxiv.org/abs/2405.15556)** — Paper; source year 2024. Study certified robustness under bounded retrieval corruption. Source ID: `rag-certified`.

24. **[Defeating Prompt Injections by Design](https://arxiv.org/abs/2503.18813)** — Paper; source year 2025. Study architectural separation of data and control flow against prompt injection. Source ID: `agent-camel`.

25. **[The Task Shield: Enforcing Task Alignment to Defend Against Indirect Prompt Injection in LLM Agents](https://arxiv.org/abs/2412.16682)** — Paper; source year 2024. Examine task alignment checks for actions derived from untrusted content. Source ID: `agent-taskshield`.

26. **[StruQ: Defending Against Prompt Injection with Structured Queries](https://arxiv.org/abs/2402.06363)** — Paper; source year 2024. Study structured separation of instructions and data against injection. Source ID: `llm-struq`.

27. **[SecAlign: Defending Against Prompt Injection with Preference Optimization](https://arxiv.org/abs/2410.05451)** — Paper; source year 2024. Explore preference optimization for resistance to prompt injection. Source ID: `llm-secalign`.

## Benchmarks, Datasets, and Evaluation

Threat-specific measurement, reproducibility, attack success, legitimate task utility, and evaluation datasets.

**30 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

Read each benchmark against its own threat model. Common corruptions, safety refusals, prompt injection, and adversarial perturbations measure different properties.

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

## Standards, Frameworks, and Secure Development

International standards, institutional reports, risk frameworks, community guidance, and secure development practices.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

Document types matter: ISO entries are international standards; ETSI GR entries are group reports; NIST, ENISA, and government documents provide their stated frameworks or guidance. OWASP, MITRE, and MCP resources have their own community or protocol roles. Inclusion does not make every document a global standard. Listed editions are reading references, not a claim that they are the newest applicable requirements.

1. **[NIST AI 100-2 E2025: Adversarial Machine Learning - A Taxonomy and Terminology of Attacks and Mitigations](https://csrc.nist.gov/pubs/ai/100/2/e2025/final)** — Technical report; source year 2025. Use consistent language for attacker goals, capabilities, knowledge, and lifecycle stages. Source ID: `nist-aml`.

2. **[NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)** — Framework. Understand organizational processes for identifying, measuring, and managing AI risk. Source ID: `nist-rmf`.

3. **[NIST AI 600-1: Generative Artificial Intelligence Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence)** — Technical report; source year 2024. Map generative AI risks to risk-management actions. Source ID: `nist-genai`.

4. **[NIST SP 800-218A: Secure Software Development Practices for Generative AI and Dual-Use Foundation Models](https://csrc.nist.gov/pubs/sp/800/218/a/final)** — Technical guidance; source year 2024. Study secure development practices specific to AI and foundation models. Source ID: `nist-ssdf-ai`.

5. **[ISO/IEC 42001:2023 - Artificial Intelligence Management System](https://www.iso.org/standard/42001)** — International standard; source year 2023. Understand requirements for an organizational AI management system. Source ID: `iso42001`.
   Access: Public catalog; full standard may require purchase or institutional access.

6. **[ISO/IEC 23894:2023 - Guidance on Risk Management](https://www.iso.org/standard/77304.html)** — International standard; source year 2023. Study AI-specific risk management guidance. Source ID: `iso23894`.
   Access: Public catalog; full standard may require purchase or institutional access.

7. **[ISO/IEC 24029-2:2023 - Robustness of Neural Networks: Methodology for the Use of Formal Methods](https://www.iso.org/standard/79804.html)** — International standard; source year 2023. Study formal methods for assessing neural network robustness. Source ID: `iso24029`.
   Access: Public catalog; full standard may require purchase or institutional access.

8. **[OWASP AI Exchange](https://owaspai.org/)** — Community knowledge base. Explore AI threat categories, security controls, and shared terminology. Source ID: `owasp-exchange`.

9. **[OWASP Top 10 for LLM Applications 2025](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/)** — Community guidance. Review the 2025 risk categories for LLM applications. Source ID: `owasp-llm`.

10. **[OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)** — Community guidance. Review the 2026 risk categories for agentic applications. Source ID: `owasp-agent`.

11. **[Guidelines for Secure AI System Development](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development)** — Government guidance. Study secure design, development, deployment, and operation of AI systems. Source ID: `ncsc-development`.

12. **[ENISA: Securing Machine Learning Algorithms](https://www.enisa.europa.eu/publications/securing-machine-learning-algorithms)** — Technical report. Connect machine learning attack surfaces to practical security controls. Source ID: `enisa-ml`.

13. **[ENISA: Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)** — Technical report. Understand foundational, AI-specific, and sector-specific security practices. Source ID: `enisa-multilayer`.

14. **[ENISA: Cybersecurity of AI and Standardisation](https://www.enisa.europa.eu/publications/cybersecurity-of-ai-and-standardisation)** — Technical report. Study the report's historical mapping of AI cybersecurity standards and gaps. Source ID: `enisa-standards`.

15. **[UK Code of Practice for the Cyber Security of AI](https://www.gov.uk/government/publications/ai-cyber-security-code-of-practice/code-of-practice-for-the-cyber-security-of-ai)** — Government guidance. Review security principles and responsibilities across the AI lifecycle. Source ID: `uk-code`.

16. **[Model Context Protocol: Security Best Practices](https://modelcontextprotocol.io/docs/tutorials/security/security_best_practices)** — Protocol guidance. Study authorization, token handling, and trust boundaries in MCP implementations. Source ID: `mcp-security`.

17. **[MITRE ATLAS](https://atlas.mitre.org/)** — Threat knowledge base. Explore documented AI attack techniques, mitigations, and case studies. Source ID: `mitre-atlas`.

18. **[ETSI GR SAI 001 V1.1.1: AI Threat Ontology](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/001/01.01.01_60/gr_SAI001v010101p.pdf)** — Group report; source year 2022. Study the ETSI ontology for threats involving artificial intelligence. Source ID: `etsi001`.

19. **[ETSI GR SAI 002 V1.1.1: Data Supply Chain Security](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/002/01.01.01_60/gr_SAI002v010101p.pdf)** — Group report; source year 2021. Examine threats and controls in the AI data supply chain. Source ID: `etsi002`.

20. **[ETSI GR SAI 004 V1.1.1: Problem Statement](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/004/01.01.01_60/gr_SAI004v010101p.pdf)** — Group report; source year 2020. Understand the scope and problem statement for securing AI. Source ID: `etsi004`.

21. **[ETSI GR SAI 005 V1.1.1: Mitigation Strategy Report](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/005/01.01.01_60/gr_SAI005v010101p.pdf)** — Group report; source year 2021. Review mitigation strategies for AI-related security threats. Source ID: `etsi005`.

22. **[ETSI GR SAI 006 V1.1.1: The Role of Hardware in Security of AI](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/006/01.01.01_60/gr_SAI006v010101p.pdf)** — Group report; source year 2022. Explore hardware's role in protecting AI systems and computation. Source ID: `etsi006`.

23. **[ETSI GR SAI 007 V1.1.1: Explicability and Transparency of AI Processing](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/007/01.01.01_60/gr_SAI007v010101p.pdf)** — Group report; source year 2023. Examine explicability and transparency considerations in AI processing. Source ID: `etsi007`.

24. **[ETSI GR SAI 009 V1.1.1: Artificial Intelligence Computing Platform Security Framework](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/009/01.01.01_60/gr_SAI009v010101p.pdf)** — Group report; source year 2023. Study security architecture for AI computing platforms. Source ID: `etsi009`.

25. **[ETSI GR SAI 011 V1.1.1: Automated Manipulation of Multimedia Identity Representations](https://www.etsi.org/deliver/etsi_gr/SAI/001_099/011/01.01.01_60/gr_SAI011v010101p.pdf)** — Group report; source year 2023. Examine security issues involving manipulated multimedia identity representations. Source ID: `etsi011`.

## CTFs and Competition Archives

Competition papers, datasets, rules, and archived learning environments.

**4 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

These resources are included for their educational content. Hosted challenge availability and local deployment were not tested. Competition archives can remain useful after a competition has ended.

1. **[Dataset and Lessons Learned from the 2024 SaTML LLM Capture-the-Flag Competition](https://arxiv.org/abs/2406.07954)** — Competition paper; source year 2024. Study competition data and lessons from adversarial secret-protection tasks. Source ID: `satml-ctf`.

2. **[Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game](https://tensortrust.ai/paper/)** — Competition dataset. Study human-authored prompt injection attacks and defenses collected through a game. Source ID: `ctf-tensortrust`.

3. **[Gandalf the Red: Adaptive Security for LLMs](https://proceedings.mlr.press/v267/pfister25a.html)** — Competition paper; source year 2025. Examine adaptive adversaries and usability costs in game-based LLM security evaluation. Source ID: `ctf-gandalf`.

4. **[SaTML 2024 Large Language Models Capture-the-Flag](https://ctf.spylab.ai/)** — Competition archive. Explore the archived 2024 LLM capture-the-flag competition rules and setting. Source ID: `ctf-satml-site`.

## Vulnerable Applications and Training Labs

Intentionally vulnerable applications and structured lab collections for studying AI security through concrete examples.

**14 sources.** Each project or collection is counted once, regardless of its number of challenges.

Selection favors explicit learning objectives, available application code or hosted exercises, and documented setup. New entries include a learning focus, the reason for inclusion, and an environment note. These are documentation-based selections; deployments and challenge outcomes were not tested.

### Existing collection

1. **[OWASP FinBot](https://genai.owasp.org/resource/finbot-agentic-ai-capture-the-flag-ctf-application/)** — Vulnerable application. Explore intentionally vulnerable financial-agent workflows for learning agentic security. Source ID: `lab-finbot`.

2. **[Damn Vulnerable LLM Agent](https://github.com/ReversecLabs/damn-vulnerable-llm-agent)** — Vulnerable application. Study prompt injection and its impact on an intentionally vulnerable LLM agent. Source ID: `lab-dvla`.

3. **[Orca AI Goat](https://github.com/orcasecurity-research/AIGoat)** — Vulnerable application. Explore intentionally vulnerable AI infrastructure and machine learning scenarios. Source ID: `lab-aigoat`.

4. **[Damn Vulnerable MCP Server](https://github.com/harishsg993010/damn-vulnerable-MCP-server)** — Vulnerable application. Study MCP implementation vulnerabilities through educational challenges. Source ID: `lab-dvmcp`.

### Added application projects

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

### Additional sample and hosted lab collections

13. **[OWASP ASI Insecure Agent Samples](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/tree/main/initiatives/agent_security_initiative/code_samples)** — Training lab collection. Read deliberately insecure agent examples to connect framework configuration and application code to agentic security failures. Source ID: `lab-owasp-insecure-agents`.

   **Educational value:** The official OWASP collection separates examples by topic and includes explanatory material alongside code.

   **Environment:** A collection of samples rather than one deployable application; dependencies and model backends vary by example.

14. **[PortSwigger Web Security Academy: Web LLM Attacks](https://portswigger.net/web-security/llm-attacks)** — Hosted training labs. Practice LLM API misuse, indirect prompt injection, and unsafe output handling through guided web-application exercises. Source ID: `lab-portswigger-llm`.

   **Educational value:** Combines structured explanations with linked lab exercises and solution guidance.

   **Environment:** Hosted Academy exercises; application source and local deployment are not provided by this entry.

### Choosing a starting point

| Learning goal | Relevant resources |
| --- | --- |
| Guided LLM application exercises | SECFORCE LLMGoat; Microsoft Playground Labs; PortSwigger Academy |
| RAG poisoning and retrieval data exposure | LLMForge; AIGoat (AI Security Consortium); DVAIA |
| Agent tools, delegation, and memory | OWASP FinBot; Reversec's Damn Vulnerable LLM Agent; OpenA2A DVAA; OWASP ASI samples |
| MCP implementation and trust boundaries | Damn Vulnerable MCP Server; OpenA2A DVAA; DVAP's simplified MCP-themed exercises |
| ML and cloud infrastructure scenarios | Orca AI Goat |
| Compact historical exercises with solutions | AI Goat (dhammon) |

Projects with similar names are independent resources: Orca AI Goat, AI Goat (dhammon), and AIGoat (AI Security Consortium) have different maintainers and learning scopes.

Repository status and environment observations were checked on 2026-09-11. Maintainer claims about defense effectiveness, coverage, or benchmark scores are not independently validated here. See [CURATION.md](CURATION.md) and [VALIDATION.md](VALIDATION.md).

## Case Studies and Research Methodology

Published vulnerability studies, failed defense lessons, measurement validity, and reproducibility.

**26 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

This collection combines controlled research case studies and methodology papers. Inclusion does not imply that a paper describes a confirmed incident in a deployed production system.

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

Initial curation date: **2026-09-11**. This is a reading archive, not a complete literature review through that date. Linked works remain under their respective licenses; this repository does not redistribute their full texts.
