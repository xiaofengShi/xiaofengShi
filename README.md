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

## Start Here

### Industrial multimodal reasoning

**[MechVQA / MechVL](https://github.com/xiaofengShi/MechVQA)** · ICML 2026 · co-first and corresponding author

The first comprehensive mechanical-drawing understanding benchmark, with 3.3K drawings and 21K question-answer pairs, plus a domain-specialized multimodal model trained with SFT and self-play RL.

[Paper](https://arxiv.org/abs/2605.30794) · [Code](https://github.com/xiaofengShi/MechVQA) · [Models & Data](https://huggingface.co/collections/XiaofengAlg/mechvqa)

### Agentic research and knowledge systems

**[SPAR](https://github.com/xiaofengShi/SPAR)** and **[SciSage](https://github.com/FlagOpen/SciSage)** · first author

Multi-agent systems for scholarly retrieval and scientific survey generation, accompanied by the SPARBench and SurveyScope evaluation resources.

[SPAR Paper](https://arxiv.org/abs/2507.15245) · [SPARBench](https://huggingface.co/datasets/XiaofengAlg/SPARBench) · [SciSage Paper](https://arxiv.org/abs/2506.12689) · [SurveyScope](https://huggingface.co/datasets/BAAI/SurveyScope)

### Open infrastructure for domain LLMs

I led the development of three BAAI collections spanning multilingual pre-training corpora, instruction data, domain models, and data-quality models:

- **[IndustryCorpus2](https://huggingface.co/collections/BAAI/industrycorpus2)** — multilingual, multi-industry pre-training data, including [DataRater](https://huggingface.co/BAAI/IndustryCorpus2_DataRater) and classification models
- **[Industry Instruction](https://huggingface.co/collections/BAAI/industry-instruction)** — 2.7M multilingual, multi-industry instruction samples and domain-adapted models
- **[IndustryCorpus](https://huggingface.co/collections/BAAI/industrycorpus)** — open corpora for finance, medicine, law, education, technology, and other industries

## Recent Research

| Year / Venue | Work | Role / Contribution | Resources |
| --- | --- | --- | --- |
| 2026 | **Wnuan** | First author / equal contribution; staged post-training for enterprise knowledge QA | [Paper](https://arxiv.org/abs/2608.01862) |
| ICML 2026 | **MechVQA / MechVL** | Co-first & corresponding author; industrial multimodal benchmark and model | [Paper](https://arxiv.org/abs/2605.30794) · [Code](https://github.com/xiaofengShi/MechVQA) · [HF](https://huggingface.co/collections/XiaofengAlg/mechvqa) |
| 2026 | **RAFT** | Co-first & corresponding author; adaptive on-policy distillation with alleviated forgetting | [Paper](https://arxiv.org/abs/2606.00147) |
| 2026 | **ChartWalker** | Corresponding author; cross-chart RAG benchmark and agentic baseline | [Paper](https://arxiv.org/abs/2606.23997) · [Code](https://github.com/downing777/ChartWalker_Pub) |
| 2025 | **Rethinking Supervised Fine-Tuning** | First author; formerly SFTKey | [Paper](https://arxiv.org/abs/2512.21017) |
| 2025 | **SPAR / SPARBench** | First author; agentic scholarly retrieval | [Paper](https://arxiv.org/abs/2507.15245) · [Code](https://github.com/xiaofengShi/SPAR) · [Data](https://huggingface.co/datasets/XiaofengAlg/SPARBench) |
| 2025 | **SciSage / SurveyScope** | First author; scientific survey generation and evaluation | [Paper](https://arxiv.org/abs/2506.12689) · [Code](https://github.com/FlagOpen/SciSage) · [Data](https://huggingface.co/datasets/BAAI/SurveyScope) |
| AAAI 2025 | **CareBot** | Full-process open-source medical language model | [Paper](https://doi.org/10.1609/aaai.v39i24.34799) · [Code](https://github.com/FlagOpen/CareBot) · [Models](https://huggingface.co/XiaofengAlg/CareBot_Medical_multi-llama3-8b-instruct) |
| COLING 2025 | **MoSLD** | Parameter-efficient mixture of shared LoRAs | [Paper](https://arxiv.org/abs/2412.08946) |
| 2024 | **CCI3.0-HQ** | High-quality 500GB Chinese pre-training corpus | [Paper](https://arxiv.org/abs/2410.18505) · [Data](https://huggingface.co/datasets/BAAI/CCI3-HQ) · [Classifier](https://huggingface.co/BAAI/CCI3-HQ-Classifier) |
| 2024 | **Aquila-Med** | Open bilingual medical LLM, data, and training recipes | [Paper](https://arxiv.org/abs/2406.12182) · [Model](https://huggingface.co/BAAI/AquilaMed-RL) · [SFT Data](https://huggingface.co/datasets/BAAI/AquilaMed-Instruct) · [RL Data](https://huggingface.co/datasets/BAAI/AquilaMed-RL) |

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
