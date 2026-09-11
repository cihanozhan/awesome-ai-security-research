# Model Privacy and Model Extraction

[Back to the index](../README.md)

Membership inference, memorization, reconstruction, gradient leakage, and functionality theft.

**25 sources.** Each source appears once in this category. Cross-listing in other categories does not create an additional unique source.

## Reading list

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

## Reading notes

Source years reflect the linked record; arXiv years are first-submission years and may differ from conference publication years. A paper label does not assert peer review. See the [curation policy](../CURATION.md) and [validation report](../VALIDATION.md) for evidence limits.
