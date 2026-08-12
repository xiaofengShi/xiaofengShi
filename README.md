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

| Work | Focus | Resources |
| --- | --- | --- |
| **Wnuan** (2026, first author / equal contribution) | A three-stage post-training pipeline for question answering over proprietary enterprise knowledge: task-oriented supervision, SFT with general-data replay, and RL on residual errors | [Paper](https://arxiv.org/abs/2608.01862) |
| **MechVQA / MechVL** (ICML 2026) | A benchmark with 3.3K mechanical drawings and 21K QA pairs, plus a domain-specialized multimodal model trained with SFT and self-play RL | [Paper](https://arxiv.org/abs/2605.30794) · [Code](https://github.com/xiaofengShi/MechVQA) · [Models & Data](https://huggingface.co/collections/XiaofengAlg/mechvqa) |
| **RAFT** (2026) | Data refinement and adaptive on-policy distillation for domain fine-tuning with alleviated forgetting | [Paper](https://arxiv.org/abs/2606.00147) |
| **SPAR / SPARBench** (2025, first author) | A multi-agent scholarly retrieval framework using query decomposition, query evolution, and citation-aware exploration | [Paper](https://arxiv.org/abs/2507.15245) · [Code](https://github.com/xiaofengShi/SPAR) · [Dataset](https://huggingface.co/datasets/XiaofengAlg/SPARBench) |
| **SciSage / SurveyScope** (2025) | Multi-agent scientific survey generation with a benchmark for evaluating high-quality research surveys | [Paper](https://arxiv.org/abs/2506.12689) · [Code](https://github.com/FlagOpen/SciSage) |

Other recent work includes [ChartWalker](https://arxiv.org/abs/2606.23997) for cross-chart RAG, [Closing the Feedback Loop](https://arxiv.org/abs/2606.17591) for insight governance in verbal reinforcement learning, and [Rethinking Supervised Fine-Tuning](https://arxiv.org/abs/2512.21017) for answer-token-aware SFT. Earlier work includes [CareBot](https://doi.org/10.1609/aaai.v39i24.34799) at AAAI 2025, [MoSLD](https://arxiv.org/abs/2412.08946) at COLING 2025, and [CCI3.0-HQ](https://arxiv.org/abs/2410.18505) for high-quality Chinese pre-training data.

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
