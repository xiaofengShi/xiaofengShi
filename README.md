<div align="center">

# Xiaofeng Shi

**AI Researcher & Engineer @ BAAI xfshi@baai.ac.cn**<br />
Beijing, China

![Industry LLMs][industry-llms-badge]
![Post-training][post-training-badge]
![Agents][agents-badge]
![RAG][rag-badge]
![Multimodal][multimodal-badge]

[![Website][website-badge]](https://xiaofengshi.com/)
[![Google Scholar][google-scholar-badge]](https://scholar.google.com/citations?user=DJLXJtAAAAAJ&hl=en)
[![Semantic Scholar][semantic-scholar-badge]](https://www.semanticscholar.org/author/Xiaofeng-Shi/2307379264)
[![OpenReview][openreview-badge]](https://openreview.net/profile?id=~Xiaofeng_Shi1)
[![ORCID][orcid-badge]](https://orcid.org/0009-0009-6052-7713)
[![Hugging Face][hugging-face-badge]](https://huggingface.co/XiaofengAlg)

</div>

I am an AI researcher and engineer at the **Beijing Academy of Artificial Intelligence (BAAI)**, with previous experience at **ByteDance** and **Meituan**. My work has evolved from computer vision and OCR to large language models, with a current focus on domain adaptation, post-training, agentic systems, retrieval-augmented generation, and multimodal reasoning.

我目前在北京智源人工智能研究院从事 AI 研究与工程工作，曾就职于字节跳动和美团。我的研究关注如何让大模型真正进入专业领域：从高质量数据、监督微调和强化学习，到 Agent、RAG 与多模态推理，并尽可能将论文对应的代码、模型和数据开放出来。

## Research Interests

- **Domain LLMs & post-training:** data construction, supervised fine-tuning, reinforcement learning, knowledge adaptation, and capability retention
- **AI agents & retrieval:** academic search, scientific survey generation, agentic RAG, and long-horizon knowledge workflows
- **Multimodal reasoning:** visual-language models, technical drawing understanding, cross-chart reasoning, and OCR
- **Open data & models:** multilingual industry corpora, instruction datasets, domain models, benchmarks, and reproducible evaluation

## Selected Research

| Year / Venue | Work | Focus | Resources |
| --- | --- | --- | --- |
| 2026 | **Wnuan** (first author / equal contribution) | Staged post-training for QA over proprietary enterprise knowledge, combining task-oriented supervision, SFT with general-data replay, and RL on residual errors | [![Paper][paper-badge]](https://arxiv.org/abs/2608.01862) |
| ICML 2026 | **MechVQA / MechVL** (co-first & corresponding author) | A benchmark with 3.3K mechanical drawings and 21K QA pairs, plus a domain-specialized multimodal model trained with SFT and self-play RL | [![Paper][paper-badge]](https://arxiv.org/abs/2605.30794) [![Code][code-badge]](https://github.com/xiaofengShi/MechVQA) [![Models and Data][models-data-badge]](https://huggingface.co/collections/XiaofengAlg/mechvqa) |
| 2026 | **RAFT** (co-first & corresponding author) | Data refinement and adaptive on-policy distillation for domain fine-tuning while alleviating general-capability forgetting | [![Paper][paper-badge]](https://arxiv.org/abs/2606.00147) |
| 2026 | **ChartWalker** (corresponding author) | A cross-chart RAG benchmark built with hierarchical knowledge graphs, structure-aware multi-hop sampling, and an agentic baseline | [![Paper][paper-badge]](https://arxiv.org/abs/2606.23997) |
| 2025 | **SFTKey** (first author) | A two-stage SFT method that explicitly emphasizes answer-relevant tokens after learning the reasoning and output format | [![Paper][paper-badge]](https://arxiv.org/abs/2512.21017) |
| 2025 | **SPAR / SPARBench** (first author) | A multi-agent scholarly retrieval framework using query decomposition, query evolution, and citation-aware exploration | [![Paper][paper-badge]](https://arxiv.org/abs/2507.15245) [![Code][code-badge]](https://github.com/xiaofengShi/SPAR) [![Dataset][dataset-badge]](https://huggingface.co/datasets/XiaofengAlg/SPARBench) |
| 2025 | **SciSage / SurveyScope** (first author) | Multi-agent scientific survey generation with hierarchical reflection and a benchmark for evaluating research surveys | [![Paper][paper-badge]](https://arxiv.org/abs/2506.12689) [![Code][code-badge]](https://github.com/FlagOpen/SciSage) |
| AAAI 2025 | **CareBot** | A full-process open-source medical language model covering continual pre-training, SFT, preference alignment, and evaluation | [![Paper][doi-badge]](https://doi.org/10.1609/aaai.v39i24.34799) [![Models][models-badge]](https://huggingface.co/XiaofengAlg/CareBot_Medical_multi-llama3-8b-instruct) |
| COLING 2025 | **MoSLD** | A parameter-efficient mixture of shared LoRAs for multi-task learning and out-of-domain generalization | [![Paper][paper-badge]](https://arxiv.org/abs/2412.08946) |
| 2024 | **CCI3.0-HQ** | A high-quality 500GB Chinese pre-training corpus produced through a two-stage hybrid filtering pipeline | [![Paper][paper-badge]](https://arxiv.org/abs/2410.18505) [![Dataset][dataset-badge]](https://huggingface.co/datasets/BAAI/CCI3-HQ) |
| 2024 | **Aquila-Med** | A bilingual medical LLM with open continual pre-training, SFT, preference-alignment data, and training recipes | [![Paper][paper-badge]](https://arxiv.org/abs/2406.12182) [![Models][models-badge]](https://huggingface.co/XiaofengAlg) |

## Open Models & Data

- [![IndustryCorpus2][industrycorpus2-badge]](https://huggingface.co/collections/BAAI/industrycorpus2) Multilingual, multi-industry pre-training corpora with accompanying data-rating and classification models
- [![Industry Instruction][industry-instruction-badge]](https://huggingface.co/collections/BAAI/industry-instruction) A 2.7M-sample multilingual, multi-industry instruction collection with domain-adapted models
- [![IndustryCorpus][industrycorpus-badge]](https://huggingface.co/collections/BAAI/industrycorpus) Open pre-training corpora spanning finance, medicine, law, education, technology, and other industries
- [![XiaofengAlg][xiaofengalg-badge]](https://huggingface.co/XiaofengAlg) MechVL, CareBot, industry-specific LLMs, MechVQA, SPARBench, and related research releases

## Earlier Open Source

- [![CHINESE-OCR][chinese-ocr-badge]](https://github.com/xiaofengShi/CHINESE-OCR) An end-to-end natural-scene Chinese text detection and recognition pipeline built with CTPN, CRNN, and CTC
- [![Image2Katex][image2katex-badge]](https://github.com/xiaofengShi/Image2Katex) Image-to-LaTeX recognition for printed and handwritten mathematical formulas
- [![DKT-TensorFlow][dkt-badge]](https://github.com/xiaofengShi/DKT-TensorFlow) A Deep Knowledge Tracing implementation for adaptive learning

## Connect

Research discussions and open-source collaboration are welcome.

[![Email Xiaofeng][email-cta-badge]](mailto:xfshi@baai.ac.cn)
[![GitHub Issues][issues-badge]](https://github.com/xiaofengShi/xiaofengShi/issues)

[industry-llms-badge]: https://img.shields.io/badge/Industry_LLMs-2563EB?style=flat-square
[post-training-badge]: https://img.shields.io/badge/Post--training-2563EB?style=flat-square
[agents-badge]: https://img.shields.io/badge/AI_Agents-2563EB?style=flat-square
[rag-badge]: https://img.shields.io/badge/RAG-2563EB?style=flat-square
[multimodal-badge]: https://img.shields.io/badge/Multimodal_Reasoning-2563EB?style=flat-square

[website-badge]: https://img.shields.io/badge/Website-18181B?style=for-the-badge&logo=googlechrome&logoColor=white
[google-scholar-badge]: https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white
[semantic-scholar-badge]: https://img.shields.io/badge/Semantic_Scholar-1857B6?style=for-the-badge&logo=semanticscholar&logoColor=white
[openreview-badge]: https://img.shields.io/badge/OpenReview-8C1B13?style=for-the-badge
[orcid-badge]: https://img.shields.io/badge/ORCID-5C8C1A?style=for-the-badge&logo=orcid&logoColor=white
[hugging-face-badge]: https://img.shields.io/badge/Hugging_Face-8A6D00?style=for-the-badge&logo=huggingface&logoColor=white
[email-badge]: https://img.shields.io/badge/Email-0F766E?style=for-the-badge

[paper-badge]: https://img.shields.io/badge/Paper-B31B1B?style=flat-square&logo=arxiv&logoColor=white
[doi-badge]: https://img.shields.io/badge/Paper-A31F34?style=flat-square&logo=doi&logoColor=white
[code-badge]: https://img.shields.io/badge/Code-3F3F46?style=flat-square&logo=github&logoColor=white
[dataset-badge]: https://img.shields.io/badge/Dataset-8A6D00?style=flat-square&logo=huggingface&logoColor=white
[models-badge]: https://img.shields.io/badge/Models-8A6D00?style=flat-square&logo=huggingface&logoColor=white
[models-data-badge]: https://img.shields.io/badge/Models_%26_Data-8A6D00?style=flat-square&logo=huggingface&logoColor=white

[industrycorpus2-badge]: https://img.shields.io/badge/IndustryCorpus2-8A6D00?style=flat-square&logo=huggingface&logoColor=white
[industry-instruction-badge]: https://img.shields.io/badge/Industry_Instruction-8A6D00?style=flat-square&logo=huggingface&logoColor=white
[industrycorpus-badge]: https://img.shields.io/badge/IndustryCorpus-8A6D00?style=flat-square&logo=huggingface&logoColor=white
[xiaofengalg-badge]: https://img.shields.io/badge/XiaofengAlg-8A6D00?style=flat-square&logo=huggingface&logoColor=white

[chinese-ocr-badge]: https://img.shields.io/badge/CHINESE--OCR-3F3F46?style=flat-square&logo=github&logoColor=white
[image2katex-badge]: https://img.shields.io/badge/Image2Katex-3F3F46?style=flat-square&logo=github&logoColor=white
[dkt-badge]: https://img.shields.io/badge/DKT--TensorFlow-3F3F46?style=flat-square&logo=github&logoColor=white

[email-cta-badge]: https://img.shields.io/badge/xfshi%40baai.ac.cn-0F766E?style=for-the-badge
[issues-badge]: https://img.shields.io/badge/GitHub_Issues-3F3F46?style=for-the-badge&logo=github&logoColor=white
