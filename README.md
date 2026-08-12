<div align="center">

# Xiaofeng Shi

**AI Researcher & Engineer · Beijing, China**

Industry LLMs · Post-training · AI Agents · RAG · Multimodal Reasoning

[Website](https://xiaofengshi.com/) · [Google Scholar](https://scholar.google.com/citations?user=DJLXJtAAAAAJ&hl=en) · [Semantic Scholar](https://www.semanticscholar.org/author/Xiaofeng-Shi/2307379264) · [OpenReview](https://openreview.net/profile?id=~Xiaofeng_Shi1) · [ORCID](https://orcid.org/0009-0009-6052-7713) · [Hugging Face](https://huggingface.co/XiaofengAlg) · [Email](mailto:xfshi@baai.ac.cn)

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
| 2026 | **Wnuan** (first author / equal contribution) | Staged post-training for QA over proprietary enterprise knowledge, combining task-oriented supervision, SFT with general-data replay, and RL on residual errors | [Paper](https://arxiv.org/abs/2608.01862) |
| ICML 2026 | **MechVQA / MechVL** | A benchmark with 3.3K mechanical drawings and 21K QA pairs, plus a domain-specialized multimodal model trained with SFT and self-play RL | [Paper](https://arxiv.org/abs/2605.30794) · [Code](https://github.com/xiaofengShi/MechVQA) · [Models & Data](https://huggingface.co/collections/XiaofengAlg/mechvqa) |
| 2026 | **RAFT** | Data refinement and adaptive on-policy distillation for domain fine-tuning while alleviating general-capability forgetting | [Paper](https://arxiv.org/abs/2606.00147) |
| 2026 | **ChartWalker** | A cross-chart RAG benchmark built with hierarchical knowledge graphs, structure-aware multi-hop sampling, and an agentic baseline | [Paper](https://arxiv.org/abs/2606.23997) |
| ICML 2026 RLxF Workshop | **Closing the Feedback Loop** | Insight governance for verbal reinforcement learning through structured rules, evidence, skills, and feedback-driven curation | [Paper](https://arxiv.org/abs/2606.17591) |
| 2025 | **SFTKey** (first author) | A two-stage SFT method that explicitly emphasizes answer-relevant tokens after learning the reasoning and output format | [Paper](https://arxiv.org/abs/2512.21017) |
| 2025 | **SPAR / SPARBench** (first author) | A multi-agent scholarly retrieval framework using query decomposition, query evolution, and citation-aware exploration | [Paper](https://arxiv.org/abs/2507.15245) · [Code](https://github.com/xiaofengShi/SPAR) · [Dataset](https://huggingface.co/datasets/XiaofengAlg/SPARBench) |
| 2025 | **SciSage / SurveyScope** (first author) | Multi-agent scientific survey generation with hierarchical reflection and a benchmark for evaluating research surveys | [Paper](https://arxiv.org/abs/2506.12689) · [Code](https://github.com/FlagOpen/SciSage) |
| AAAI 2025 | **CareBot** | A full-process open-source medical language model covering continual pre-training, SFT, preference alignment, and evaluation | [Paper](https://doi.org/10.1609/aaai.v39i24.34799) · [Models](https://huggingface.co/XiaofengAlg/CareBot_Medical_multi-llama3-8b-instruct) |
| COLING 2025 | **MoSLD** | A parameter-efficient mixture of shared LoRAs for multi-task learning and out-of-domain generalization | [Paper](https://arxiv.org/abs/2412.08946) |
| 2024 | **CCI3.0-HQ** | A high-quality 500GB Chinese pre-training corpus produced through a two-stage hybrid filtering pipeline | [Paper](https://arxiv.org/abs/2410.18505) · [Dataset](https://huggingface.co/datasets/BAAI/CCI3-HQ) |
| 2024 | **Aquila-Med** | A bilingual medical LLM with open continual pre-training, SFT, preference-alignment data, and training recipes | [Paper](https://arxiv.org/abs/2406.12182) · [Models](https://huggingface.co/XiaofengAlg) |

## Open Models & Data

- **[IndustryCorpus2](https://huggingface.co/collections/BAAI/industrycorpus2):** multilingual, multi-industry pre-training corpora with accompanying data-rating and classification models
- **[Industry Instruction](https://huggingface.co/collections/BAAI/industry-instruction):** a 2.7M-sample multilingual, multi-industry instruction collection with domain-adapted models
- **[IndustryCorpus](https://huggingface.co/collections/BAAI/industrycorpus):** open pre-training corpora spanning finance, medicine, law, education, technology, and other industries
- **[XiaofengAlg on Hugging Face](https://huggingface.co/XiaofengAlg):** MechVL, CareBot, industry-specific LLMs, MechVQA, SPARBench, and related research releases

## Earlier Open Source

- **[CHINESE-OCR](https://github.com/xiaofengShi/CHINESE-OCR):** an end-to-end natural-scene Chinese text detection and recognition pipeline built with CTPN, CRNN, and CTC
- **[Image2Katex](https://github.com/xiaofengShi/Image2Katex):** image-to-LaTeX recognition for printed and handwritten mathematical formulas
- **[DKT-TensorFlow](https://github.com/xiaofengShi/DKT-TensorFlow):** a Deep Knowledge Tracing implementation for adaptive learning

## Connect

For publications and peer-review activity, see [Google Scholar](https://scholar.google.com/citations?user=DJLXJtAAAAAJ&hl=en), [Semantic Scholar](https://www.semanticscholar.org/author/Xiaofeng-Shi/2307379264), and [OpenReview](https://openreview.net/profile?id=~Xiaofeng_Shi1). Models and datasets are available on [Hugging Face](https://huggingface.co/XiaofengAlg). Research discussions and open-source collaboration are welcome via [email](mailto:xfshi@baai.ac.cn) or GitHub issues.
