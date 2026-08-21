<div align="center">

# Xiaofeng Shi

**AI Researcher & Engineer @ Beijing Academy of Artificial Intelligence (BAAI)**

I build **open data, post-training methods, and agentic/multimodal systems** that make foundation models work in specialized domains.

让基础模型真正进入专业领域：开放数据、后训练方法与 Agent / 多模态系统。

[![Research Website][research-website-badge]](https://xiaofengshi-research.pages.dev/)
[![Blog][blog-badge]](https://xiaofengshi.com/)
[![Google Scholar][google-scholar-badge]](https://scholar.google.com/citations?user=DJLXJtAAAAAJ&hl=en)
[![ORCID][orcid-badge]](https://orcid.org/0009-0009-6052-7713)
[![OpenReview][openreview-badge]](https://openreview.net/profile?id=~Xiaofeng_Shi1)
[![Semantic Scholar][semantic-scholar-badge]](https://www.semanticscholar.org/author/Xiaofeng-Shi/2307379264)
[![Hugging Face][hugging-face-badge]](https://huggingface.co/XiaofengAlg)

</div>

## Selected Research

My full paper list is available on my [personal homepage](https://xiaofengshi-research.pages.dev/).

### Domain adaptation & post-training

- `2026` · [Inject, Align, Recover (IAR)](https://arxiv.org/abs/2608.20281) · [Wnuan](https://arxiv.org/abs/2608.01862) · [RAFT](https://arxiv.org/abs/2606.00147)

### Multimodal & analytical reasoning

- `ICML 2026` · [MechVQA / MechVL](https://arxiv.org/abs/2605.30794) · [ChartWalker](https://arxiv.org/abs/2606.23997)

### Scholarly agents & scientific systems

- `2025` · [SPAR / SPARBench](https://arxiv.org/abs/2507.15245) · [SciSage / SurveyScope](https://arxiv.org/abs/2506.12689)

### Domain LLMs & open data

- `AAAI 2025` · [CareBot](https://doi.org/10.1609/aaai.v39i24.34799) · `2024` · [CCI3.0-HQ](https://arxiv.org/abs/2410.18505) · [Aquila-Med](https://arxiv.org/abs/2406.12182)
- BAAI collections · [IndustryCorpus2](https://huggingface.co/collections/BAAI/industrycorpus2) · [Industry Instruction](https://huggingface.co/collections/BAAI/industry-instruction) · [IndustryCorpus](https://huggingface.co/collections/BAAI/industrycorpus)

## Recent Research

| Year / Venue | Work | Paper Summary | Resources |
| --- | --- | --- | --- |
| 2026 | **Inject, Align, Recover (IAR)** | Introduces a three-stage post-training framework—Inject, Align, and Recover—for internalizing bounded document collections into parametric knowledge without retrieval at inference time. It separates document knowledge injection, QA alignment, and general-ability recovery to improve the domain–general capability frontier. | [Paper](https://arxiv.org/abs/2608.20281) |
| 2026 | **Wnuan** | Presents a three-stage pipeline for enterprise QA that converts documents into task-oriented supervision, uses general-data replay during SFT, and applies RL to residual errors. The study measures both QA gains and the general-capability cost of proprietary knowledge adaptation. | [Paper](https://arxiv.org/abs/2608.01862) |
| ICML 2026 | **MechVQA / MechVL** | Introduces a 3.3K-image, 21K-question benchmark for mechanical drawing understanding across recognition, reasoning, and judging, and develops the MechVL model on top of it. | [Paper](https://arxiv.org/abs/2605.30794) · [Code](https://github.com/xiaofengShi/MechVQA) · [HF](https://huggingface.co/collections/XiaofengAlg/mechvqa) |
| 2026 | **RAFT** | Proposes a two-stage domain fine-tuning framework that refines supervision and applies answer-conditioned on-policy distillation to reduce forgetting. It targets the trade-off between domain accuracy and general instruction-following ability. | [Paper](https://arxiv.org/abs/2606.00147) |
| 2026 | **ChartWalker** | Introduces a cross-chart RAG benchmark built with hierarchical chart knowledge graphs and structure-aware sampling for controllable multi-hop reasoning. It also provides an agentic baseline, ChartWalker-Agent. | [Paper](https://arxiv.org/abs/2606.23997) · [Code](https://github.com/downing777/ChartWalker_Pub) |
| 2025 | **Rethinking Supervised Fine-Tuning** | Proposes SFTKey, a two-stage fine-tuning scheme that gives additional emphasis to answer-relevant tokens after learning output format. The method aims to improve final-answer accuracy without sacrificing response structure. | [Paper](https://arxiv.org/abs/2512.21017) |
| 2025 | **SPAR / SPARBench** | Introduces a multi-agent scholarly retrieval framework with query decomposition and evolution, together with SPARBench, an expert-annotated benchmark for academic search. | [Paper](https://arxiv.org/abs/2507.15245) · [Code](https://github.com/xiaofengShi/SPAR) · [Data](https://huggingface.co/datasets/XiaofengAlg/SPARBench) |
| 2025 | **SciSage / SurveyScope** | Presents a multi-agent scientific survey generation framework with hierarchical reflection across outlines, sections, and documents. It also releases SurveyScope, a curated benchmark for evaluating survey quality. | [Paper](https://arxiv.org/abs/2506.12689) · [Code](https://github.com/FlagOpen/SciSage) · [Data](https://huggingface.co/datasets/BAAI/SurveyScope) |
| AAAI 2025 | **CareBot** | Presents a bilingual medical LLM trained through continuous pre-training, supervised fine-tuning, and RLHF, with Stable/Boost CPT, DataRater, and ConFilter for data and dialogue quality. The project develops an end-to-end recipe for medical consultation and education. | [Paper](https://doi.org/10.1609/aaai.v39i24.34799) · [Code](https://github.com/FlagOpen/CareBot) · [Models](https://huggingface.co/XiaofengAlg/CareBot_Medical_multi-llama3-8b-instruct) |
| COLING 2025 | **MoSLD** | Introduces a mixture-of-shared-LoRAs architecture for multi-task learning that shares the upper projection across experts while preserving task-specific lower projections. A dropout strategy reduces update imbalance and overfitting. | [Paper](https://arxiv.org/abs/2412.08946) |
| 2024 | **CCI3.0-HQ** | Releases a 500GB high-quality subset of CCI3.0, curated with a two-stage hybrid filtering pipeline for pretraining LLMs. Experiments show improved zero-shot performance and Chinese web-data classification. | [Paper](https://arxiv.org/abs/2410.18505) · [Data](https://huggingface.co/datasets/BAAI/CCI3-HQ) · [Classifier](https://huggingface.co/BAAI/CCI3-HQ-Classifier) |
| 2024 | **Aquila-Med** | Presents a bilingual medical LLM built through continued pretraining, SFT, and RLHF, supported by Chinese-English medical corpora and preference data. It open-sources the models, datasets, and training process for medical applications. | [Paper](https://arxiv.org/abs/2406.12182) · [Model](https://huggingface.co/BAAI/AquilaMed-RL) · [SFT Data](https://huggingface.co/datasets/BAAI/AquilaMed-Instruct) · [RL Data](https://huggingface.co/datasets/BAAI/AquilaMed-RL) |

## Earlier Open Source

- **[CHINESE-OCR](https://github.com/xiaofengShi/CHINESE-OCR)** — end-to-end natural-scene Chinese text detection and recognition with CTPN, CRNN, and CTC
- **[Image2Katex](https://github.com/xiaofengShi/Image2Katex)** — image-to-LaTeX recognition for printed and handwritten mathematical formulas
- **[DKT-TensorFlow](https://github.com/xiaofengShi/DKT-TensorFlow)** — Deep Knowledge Tracing for adaptive learning

## Connect

I welcome research discussions, open-source collaboration, and responsible adoption of the released models and datasets.

[![Email Xiaofeng][email-cta-badge]](mailto:xfshi@baai.ac.cn)
[![GitHub Issues][issues-badge]](https://github.com/xiaofengShi/xiaofengShi/issues)

[research-website-badge]: https://img.shields.io/badge/Research_Website-18181B?style=for-the-badge&logo=googlechrome&logoColor=white
[blog-badge]: https://img.shields.io/badge/Blog-0F766E?style=for-the-badge&logo=hexo&logoColor=white
[google-scholar-badge]: https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white
[orcid-badge]: https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white
[openreview-badge]: https://img.shields.io/badge/OpenReview-8C1B13?style=for-the-badge
[semantic-scholar-badge]: https://img.shields.io/badge/Semantic_Scholar-1857B6?style=for-the-badge&logo=semanticscholar&logoColor=white
[hugging-face-badge]: https://img.shields.io/badge/Hugging_Face-8A6D00?style=for-the-badge&logo=huggingface&logoColor=white
[email-cta-badge]: https://img.shields.io/badge/xfshi%40baai.ac.cn-0F766E?style=for-the-badge
[issues-badge]: https://img.shields.io/badge/GitHub_Issues-3F3F46?style=for-the-badge&logo=github&logoColor=white
