# LLM-engineer-handbook
🔥 Large Language Models(LLM) have taken the ~~NLP community~~ ~~AI community~~ **the Whole World** by storm. 
The LLM space is complicated! This repo provides a curated list to help you navigate; it includes a collection of Large Language Model frameworks and tutorials, covering model training, serving, fine-tuning, and building LLM applications.


*However, classical ML is not going away. Even LLMs need them. We have seen classical models used for protecting data privacy, detecing hallucinations, and more. So, do not forget to study the fundamentals of classical ML.*

🤝 Please share this repo so we can continue investing in it and make it the go-to resource for LLM engineers—whether they are just starting out or looking to stay updated in the field.


[![Share on Twitter](https://img.shields.io/badge/Share_on-Twitter-1DA1F2?logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=Check+out+this+awesome+repository+for+LLM+engineers!&url=https://github.com/LLM-engineer-handbook)
[![Share on LinkedIn](https://img.shields.io/badge/Share_on-LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/LLM-engineer-handbook)



## Table of Content

- [LLM-engineer-handbook](#llm-engineer-handbook)
  - [Table of Content](#table-of-content)
  - [Applications](#applications)
  - [Pretraining](#pretraining)
  - [Fine-tuning](#fine-tuning)
  - [Serving](#serving)
  - [Prompt Management](#prompt-management)
  - [Datasets](#datasets)
  - [Benchmarks](#benchmarks)
  - [Understand LLM](#understand-llm)
  - [Learn LLM](#learn-llm)
    - [Modeling](#modeling)
    - [Training](#training)
    - [Fundamentals](#fundamentals)
    - [Books](#books)
    - [Applications](#applications-1)
      - [General](#general)
      - [Agent](#agent)
    - [Auto-optimization](#auto-optimization)
  - [Social Accounts](#social-accounts)
  - [Community](#community)
  - [Contributing](#contributing)

## Applications

**Build & Auto-optimize**

- [AdalFlow](https://github.com/SylphAI-Inc/AdalFlow) - The library to build & auto-optimize LLM applications, from Chatbot, RAG, to Agent by [SylphAI](https://www.sylph.ai/).

- [dspy](https://github.com/stanfordnlp/dspy) - DSPy: The framework for programming—not prompting—foundation models.

**Build**

- [LlamaIndex](https://github.com/jerryjliu/llama_index) — A Python library for augmenting LLM apps with data.
- [LangChain](https://github.com/hwchase17/langchain) — A popular Python/JavaScript library for chaining sequences of language model prompts.
- [Haystack](https://github.com/deepset-ai/haystack) — Python framework that allows you to build applications powered by LLMs.
- [Instill Core](https://github.com/instill-ai/instill-core) — A platform built with Go for orchestrating LLMs to create AI applications.
- [magentic](https://github.com/jackmpcollins/magentic) - A library to seamlessly integrate LLMs as Python functions.

**Prompt Optimization**

- [AutoPrompt](https://github.com/Eladlev/AutoPrompt) - A framework for prompt tuning using Intent-based Prompt Calibration.
- [PromptFify](https://github.com/promptslab/Promptify) - A library for prompt engineering that simplifies NLP tasks (e.g., NER, classification) using LLMs like GPT.

**Others**

- [LiteLLM](https://github.com/BerriAI/litellm) - Python SDK, Proxy Server (LLM Gateway) to call 100+ LLM APIs in OpenAI format.


## Pretraining

- [PyTorch](https://pytorch.org/) - PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing.
- [TensorFlow](https://www.tensorflow.org/) - TensorFlow is an open source machine learning library developed by Google.
- [JAX](https://github.com/jax-ml/jax) - Google’s library for high-performance computing and automatic differentiation.
- [tinygrad](https://github.com/tinygrad/tinygrad) - A minimalistic deep learning library with a focus on simplicity and educational use, created by George Hotz.
- [micrograd](https://github.com/karpathy/micrograd) - A simple, lightweight autograd engine for educational purposes, created by Andrej Karpathy.

## Fine-tuning

- [Transformers](https://huggingface.co/docs/transformers/en/installation) - Hugging Face Transformers is a popular library for Natural Language Processing (NLP) tasks, including fine-tuning large language models.
- [Unsloth](https://github.com/unslothai/unsloth) - Finetune Llama 3.2, Mistral, Phi-3.5 & Gemma 2-5x faster with 80% less memory!
- [LitGPT](https://github.com/Lightning-AI/litgpt) - 20+ high-performance LLMs with recipes to pretrain, finetune, and deploy at scale.

## Serving

- [TorchServe](https://pytorch.org/serve/) - An open-source model serving library developed by AWS and Facebook specifically for PyTorch models, enabling scalable deployment, model versioning, and A/B testing.

- [TensorFlow Serving](https://www.tensorflow.org/tfx/guide/serving) - A flexible, high-performance serving system for machine learning models, designed for production environments, and optimized for TensorFlow models but also supports other formats.

- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) - Part of the Ray ecosystem, Ray Serve is a scalable model-serving library that supports deployment of machine learning models across multiple frameworks, with built-in support for Python-based APIs and model pipelines.

- [NVIDIA TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - TensorRT-LLM is NVIDIA's compiler for transformer-based models (LLMs), providing state-of-the-art optimizations on NVIDIA GPUs.
 
- [NVIDIA Triton Inference Server](https://developer.nvidia.com/triton-inference-server) - A high-performance inference server supporting multiple ML/DL frameworks (TensorFlow, PyTorch, ONNX, TensorRT etc.), optimized for NVIDIA GPU deployments, and ideal for both cloud and on-premises serving.

- [ollama](https://github.com/ollama/ollama) - A lightweight, extensible framework for building and running large language models on the local machine.

- [llama.cpp](https://github.com/ggerganov/llama.cpp) - A library for running LLMs in pure C/C++. Supported architectures include (LLaMA, Falcon, Mistral, MoEs, phi and more)

- [TGI](https://github.com/huggingface/text-generation-inference) - HuggingFace's text-generation-inference toolkit for deploying and serving LLMs, built on top of Rust, Python and gRPC.

- [vllm](https://github.com/vllm-project/vllm) - An optimized, high-throughput serving engine for large language models, designed to efficiently handle massive-scale inference with reduced latency.

- [sglang](https://github.com/sgl-project/sglang) - SGLang is a fast serving framework for large language models and vision language models.

- [LitServe](https://github.com/Lightning-AI/LitServe) - LitServe is a lightning-fast serving engine for any AI model of any size. Flexible. Easy. Enterprise-scale.

## Prompt Management

- [Opik](https://github.com/comet-ml/opik) - Opik is an open-source platform for evaluating, testing and monitoring LLM applications

## Datasets

Use Cases

- [Datasets](https://huggingface.co/docs/datasets/en/index) - A vast collection of ready-to-use datasets for machine learning tasks, including NLP, computer vision, and audio, with tools for easy access, filtering, and preprocessing.
- [Argilla](https://github.com/argilla-io/argilla) - A UI tool for curating and reviewing datasets for LLM evaluation or training.
- [distilabel](https://distilabel.argilla.io/latest/) - A library for generating synthetic datasets with LLM APIs or models.

Fine-tuning

- [LLMDataHub](https://github.com/Zjh-819/LLMDataHub) - A quick guide (especially) for trending instruction finetuning datasets
- [LLM Datasets](https://github.com/mlabonne/llm-datasets) - High-quality datasets, tools, and concepts for LLM fine-tuning.

Pretraining

- [IBM LLMs Granite 3.0](https://www.linkedin.com/feed/update/urn:li:activity:7259535100927725569?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7259535100927725569%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29) - Full list of datasets used to train IBM LLMs Granite 3.0

## Benchmarks

- [lighteval](https://github.com/huggingface/lighteval) - A library for evaluating local LLMs on major benchmarks and custom tasks.

- [evals](https://github.com/openai/evals) - OpenAI's open sourced evaluation framework for LLMs and systems built with LLMs.
- [ragas](https://github.com/explodinggradients/ragas) - A library for evaluating and optimizing LLM applications, offering a rich set of eval metrics.

Agent

- [TravelPlanner](https://osu-nlp-group.github.io/TravelPlanner/) - [paper](https://arxiv.org/pdf/2402.01622) A Benchmark for Real-World Planning with Language Agents.

## Understand LLM

It can be fun and important to understand the capabilities, behaviors, and limitations of LLMs. This can directly help with prompt engineering.

In-context Learning

- [Brown, Tom B. "Language models are few-shot learners." arXiv preprint arXiv:2005.14165 (2020).](https://rosanneliu.com/dlctfs/dlct_200724.pdf)

Reasoning & Planning

- [Kambhampati, Subbarao, et al. "LLMs can't plan, but can help planning in LLM-modulo frameworks." arXiv preprint arXiv:2402.01817 (2024).](https://arxiv.org/abs/2402.01817)
- [Mirzadeh, Iman, et al. "Gsm-symbolic: Understanding the limitations of mathematical reasoning in large language models." arXiv preprint arXiv:2410.05229 (2024).](https://arxiv.org/abs/2410.05229) By Apple.

## Learn LLM

We will categorize the best resources to learn LLMs, from modeling to training, and applications.

### Applications

General

- [AdalFlow documentation](https://adalflow.sylph.ai/) - Includes tutorials from building RAG, Agent, to LLM evaluation and fine-tuning.

- [CS224N](https://www.youtube.com/watch?v=rmVRLeJRkl4) - Stanford course covering NLP fundamentals, LLMs, and PyTorch-based model building, led by Chris Manning and Shikhar Murty.

- [LLM-driven Data Engineering](https://github.com/DataExpert-io/llm-driven-data-engineering) -  A playlist of 6 lectures by [Zach Wilson](https://www.linkedin.com/in/eczachly) on how LLMs will impact data pipeline development 

- [LLM Course by Maxime Labonne](https://github.com/mlabonne/llm-course) - An end-to-end course for AI and ML engineers on open source LLMs.

#### Agent

Lectures

- [LLM Agents MOOC](https://youtube.com/playlist?list=PLS01nW3RtgopsNLeM936V4TNSsvvVglLc&si=LAonD5VfG9jFAOuE) - A playlist of 11 lectures by the Berkeley RDI Center on Decentralization & AI, featuring guest speakers like Yuandong Tian, Graham Neubig, Omar Khattab, and others, covering core topics on Large Language Model agents. [CS294](https://rdi.berkeley.edu/llm-agents/f24)

Projects

- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open source agents for developers by [AllHands](https://www.all-hands.dev/).
- [CAMEL](https://github.com/camel-ai/camel) - First LLM multi-agent framework and an open-source community dedicated to finding the scaling law of agents. by [CAMEL-AI](https://www.camel-ai.org/).
- [swarm](https://github.com/openai/swarm) - Educational framework exploring ergonomic, lightweight multi-agent orchestration. Managed by OpenAI Solution team.
- [AutoGen](https://github.com/microsoft/autogen) - A programming framework for agentic AI 🤖 by Microsoft.
- [CrewAI](https://github.com/crewAIInc/crewAI) - 🤖 CrewAI: Cutting-edge framework for orchestrating role-playing, autonomous AI agents.

### Modeling

- [Llama3 from scratch](https://github.com/naklecha/llama3-from-scratch) - llama3 implementation one matrix multiplication at a time with PyTorch.
- [Interactive LLM visualization](https://github.com/bbycroft/llm-viz) - An interactive visualization of transformers. [Visualizer](https://bbycroft.net/llm)
- [3Blue1Brown transformers visualization](https://www.youtube.com/watch?v=wjZofJX0v4M) - 3Blue1Brown's video on how transformers work.
- [Self-Attention explained as directed graph](https://x.com/akshay_pachaar/status/1853474819523965088) - An X post explaining self-attention as a directed graph by Akshay Pachaar.

### Training

- [Chip's Blog](https://huyenchip.com/blog/) - Chip Huyen's blog on training LLMs, including the latest research, tutorials, and best practices.
- [Lil'Log](https://lilianweng.github.io/) - Lilian Weng(OpenAI)'s blog on machine learning, deep learning, and AI, with a focus on LLMs and NLP.

### Fine-tuning

- [DPO](https://arxiv.org/abs/2305.18290): Rafailov, Rafael, et al. "Direct preference optimization: Your language model is secretly a reward model." Advances in Neural Information Processing Systems 36 (2024). [Code](https://github.com/eric-mitchell/direct-preference-optimization).

### Fundamentals
- [Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g&t=1390s&ab_channel=AndrejKarpathy) - A 1 hour general-audience introduction to Large Language Models by Andrej Karpathy.
- [Building GPT-2 from Scratch](https://www.youtube.com/watch?v=l8pRSuU81PU&t=1564s&ab_channel=AndrejKarpathy) - A 4 hour deep dive into building GPT2 from scratch by Andrej Karpathy.

### Books 
- [Build a Large Language Model from Scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch) by Sebastian Raschka
- [Hands-On Large Language Models: Build, Tune, and Apply LLMs](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961) by Jay Alammar , Maarten Grootendorst

- [LLM Engineer's Handbook: Master the art of engineering large language models from concept to production](https://www.amazon.com/dp/1836200072?ref=cm_sw_r_cp_ud_dp_ZFR4XZPT7EY41ZE1M5X9&ref_=cm_sw_r_cp_ud_dp_ZFR4XZPT7EY41ZE1M5X9&social_share=cm_sw_r_cp_ud_dp_ZFR4XZPT7EY41ZE1M5X9) by   Paul Iusztin , Maxime Labonne
- [Generative Deep Learning - Teaching machines to Paint, Write, Compose and Play](https://www.amazon.com/Generative-Deep-Learning-Teaching-Machines/dp/1492041947) by David Foster

### Newsletters

- [Ahead of AI](https://magazine.sebastianraschka.com/) - Sebastian Raschka's Newsletter, covering end-to-end LLMs understanding.
- [Decoding ML](https://decodingml.substack.com/) - Content on building production GenAI, RecSys and MLOps applications.



### Auto-optimization

- [TextGrad](https://github.com/zou-group/textgrad) - Automatic ''Differentiation'' via Text -- using large language models to backpropagate textual gradients.

## Social Accounts

Social accounts are the best ways to stay up-to-date with the lastest LLM research, industry trends, and best practices.

| Name                | Social                                              | Expertise                  |
|---------------------|-------------------------------------------------------|-----------------------------|
| Li Yin             | [LinkedIn](https://www.linkedin.com/in/li-yin-ai)      |    AdalFlow Author & SylphAI founder                      |
| Chip Huyen         | [LinkedIn](https://www.linkedin.com/in/chiphuyen)      |   AI Engineering & ML Systems                      |
| Damien Benveniste, PhD | [LinkedIn](https://www.linkedin.com/in/damienbenveniste/) |        ML Systems & MLOps                    |
| Jim Fan            | [LinkedIn](https://www.linkedin.com/in/drjimfan/)      |    LLM Agents & Robotics                        |
| Paul Iusztin       | [LinkedIn](https://www.linkedin.com/in/pauliusztin/)   | LLM Engineering & LLMOps    |
| Armand Ruiz        | [LinkedIn](https://www.linkedin.com/in/armand-ruiz/)   | AI Engineering Director at IBM           |
| Alex Razvant       | [LinkedIn](https://www.linkedin.com/in/arazvant/)      | AI/ML Engineering          |
| Pascal Biese       | [LinkedIn](https://www.linkedin.com/in/pascalbiese/)   | LLM Papers Daily            |
| Maxime Labonne     | [LinkedIn](https://www.linkedin.com/in/maxime-labonne/) | LLM Fine-Tuning             |
| Sebastian Raschka  | [LinkedIn](https://www.linkedin.com/in/sebastianraschka/) | LLMs from Scratch       |
| Zach Wilson        | [LinkedIn](https://www.linkedin.com/in/eczachly)       | Data Engineering for LLMs    |
| Eduardo Ordax    | [LinkedIn](https://www.linkedin.com/in/eordax/) | GenAI voice @ AWS |

## Community

| Name                | Social                                              | Scope                  |
|---------------------|-------------------------------------------------------|-----------------------------|
| AdalFlow     | [Discord](https://discord.gg/ezzszrRZvT)                |   LLM Engineering, auto-prompts, and AdalFlow discussions&contributions                      |

## Contributing

This is an active repository and your contributions are always welcome!

I will keep some pull requests open if I'm not sure if they are not an instant fit for this repo, you could vote for them by adding 👍 to them.

---

If you have any question about this opinionated list, do not hesitate to contact [Li Yin](https://www.linkedin.com/in/li-yin-ai)




