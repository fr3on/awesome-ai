# Awesome AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of frameworks, models, infrastructure, and vertical tools for building with AI.

Focused on things that are actually usable today: open-weight models you can run, APIs you can call, frameworks you'd reach for in production. Not a dump of every paper or demo.

Contributions welcome — see [Contributing](#contributing).

## Contents

- [Foundation Models](#foundation-models)
- [Multimodal & Generative Media](#multimodal--generative-media)
- [Agent Frameworks](#agent-frameworks)
- [Coding Agents & Dev Tools](#coding-agents--dev-tools)
- [RAG & Vector Search](#rag--vector-search)
- [Inference & Serving](#inference--serving)
- [Evaluation & Observability](#evaluation--observability)
- [Fine-Tuning & Training](#fine-tuning--training)
- [Vertical & Domain-Specific](#vertical--domain-specific)
- [Datasets](#datasets)
- [Safety & Alignment](#safety--alignment)
- [Learning Resources](#learning-resources)

## Foundation Models

- [Claude](https://www.anthropic.com/claude) - Anthropic's frontier model family, strong at agentic tool use and long-context reasoning.
- [GPT](https://openai.com/gpt-4) - OpenAI's model family, the default integration target for most AI tooling.
- [Gemini](https://deepmind.google/technologies/gemini/) - Google DeepMind's multimodal model family, tightly integrated with Google's own infra.
- [Llama](https://www.llama.com/) - Meta's open-weight model family, the most widely fine-tuned open base.
- [Qwen](https://github.com/QwenLM/Qwen) - Alibaba's open-weight models, strong multilingual and coding performance.
- [Mistral](https://mistral.ai/) - Open and commercial models from a European lab, known for efficient small models.
- [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3) - Open-weight models with strong reasoning-to-cost ratio.
- [Gemma](https://ai.google.dev/gemma) - Google's open-weight model family, permissively licensed.

## Multimodal & Generative Media

- [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) - Open-weight text-to-image model family, the base for most self-hosted image generation.
- [FLUX](https://github.com/black-forest-labs/flux) - Open-weight image generation models from Black Forest Labs, known for prompt adherence and detail.
- [Sora](https://openai.com/sora/) - OpenAI's text-to-video model, generates minute-long video clips from text prompts.
- [Suno](https://suno.com/) - Text-to-song generation, produces full tracks with vocals and instrumentation from a prompt.
- [ElevenLabs](https://elevenlabs.io/) - Text-to-speech and voice cloning platform, widely used for narration and dubbing.
- [Whisper](https://github.com/openai/whisper) - OpenAI's open-weight speech-to-text model, supports transcription and translation across many languages.

## Agent Frameworks

- [LangChain](https://github.com/langchain-ai/langchain) - The most widely adopted framework for chaining LLM calls, tools, and memory.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework focused on connecting LLMs to structured and unstructured data sources.
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) - Anthropic's SDK for building agents on top of Claude, used by Claude Code itself.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's framework for multi-agent conversation and orchestration.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent orchestration framework.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-based orchestration for stateful, multi-step agent workflows.
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Open standard for connecting AI agents to external tools and data sources.

## Coding Agents & Dev Tools

- [Claude Code](https://claude.com/claude-code) - Anthropic's agentic CLI/IDE tool that reads, edits, and runs code directly in your terminal or editor.
- [Cursor](https://cursor.com/) - AI-first code editor built as a fork of VS Code, with deep in-editor agentic edit and chat.
- [GitHub Copilot](https://github.com/features/copilot) - The original AI pair programmer, now with agent mode across VS Code, JetBrains, and github.com.
- [Aider](https://github.com/Aider-AI/aider) - Open-source terminal-based AI pair programmer that edits local git repos directly.
- [Cline](https://github.com/cline/cline) - Open-source autonomous coding agent as a VS Code extension, model-agnostic.
- [Windsurf](https://windsurf.com/) - AI-native IDE with a multi-file agentic "Cascade" mode.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source platform for autonomous software-engineering agents that can browse, run code, and call APIs.

## RAG & Vector Search

- [Qdrant](https://github.com/qdrant/qdrant) - Vector database written in Rust, supports hybrid dense+sparse search.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector database with built-in hybrid search and modules.
- [Milvus](https://github.com/milvus-io/milvus) - Vector database built for large-scale similarity search.
- [Pinecone](https://www.pinecone.io/) - Managed vector database, common default for hosted RAG pipelines.
- [pgvector](https://github.com/pgvector/pgvector) - Vector similarity search as a Postgres extension, useful when you don't want a separate vector store.

## Inference & Serving

- [vLLM](https://github.com/vllm-project/vllm) - High-throughput inference engine for open-weight LLMs, widely used in production serving.
- [Ollama](https://github.com/ollama/ollama) - Run open-weight models locally with a simple CLI and API.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - CPU/GPU inference for LLaMA-family models in C/C++, the base for most local-inference tooling.
- [TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference) - Hugging Face's production inference server for LLMs.

## Evaluation & Observability

- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM observability, tracing, and evaluation platform.
- [Ragas](https://github.com/explodinggradients/ragas) - Evaluation framework specifically for RAG pipelines.
- [PromptFoo](https://github.com/promptfoo/promptfoo) - Testing and evaluation for prompts and LLM outputs, CI-friendly.
- [Weights & Biases](https://wandb.ai/) - Experiment tracking, widely used for both training and LLM eval.

## Fine-Tuning & Training

- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) - Streamlined fine-tuning for open-weight LLMs across multiple formats.
- [Unsloth](https://github.com/unslothai/unsloth) - Fast, memory-efficient LoRA/QLoRA fine-tuning.
- [PEFT](https://github.com/huggingface/peft) - Hugging Face's library for parameter-efficient fine-tuning methods.
- [DeepSpeed](https://github.com/microsoft/DeepSpeed) - Microsoft's distributed training and inference optimization library.

## Vertical & Domain-Specific

- [Dike](https://dike.it.com) - MENA legal source layer for AI: a bilingual (Arabic/English) API grounding agents in official primary legal sources (statutes, gazettes, court rulings) across Saudi Arabia, UAE, Qatar, Kuwait, and Egypt, with citation anchors back to the original text.
- [BloombergGPT](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/) - Finance-domain LLM trained on Bloomberg's proprietary and public financial data.
- [Med-PaLM](https://sites.research.google/med-palm/) - Google's medical-domain LLM, benchmarked against clinical licensing exams.
- [BioGPT](https://github.com/microsoft/BioGPT) - Domain-specific generative model pretrained on biomedical literature.

## Datasets

- [Hugging Face Datasets](https://huggingface.co/datasets) - The largest open hub for ML datasets across every modality.
- [Common Crawl](https://commoncrawl.org/) - Petabyte-scale open web crawl data, the base corpus behind most large LLMs.
- [The Pile](https://pile.eleuther.ai/) - Large, diverse open-source text corpus for language model training.
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 15-trillion-token filtered and deduplicated web dataset from Hugging Face, built for LLM pretraining.
- [RedPajama](https://github.com/togethercomputer/RedPajama-Data) - Open reproduction of the LLaMA training dataset, fully public and reproducible.
- [Dolma](https://github.com/allenai/dolma) - Allen AI's open 3-trillion-token corpus with full data provenance and toolkit for building your own.
- [LAION-5B](https://laion.ai/blog/laion-5b/) - 5.8 billion image-text pairs, the dataset behind Stable Diffusion and most open multimodal models.
- [OpenOrca](https://huggingface.co/datasets/Open-Orca/OpenOrca) - Instruction-tuning dataset of GPT-3.5/GPT-4-augmented completions over FLAN-style prompts.

## Safety & Alignment

- [Anthropic's Responsible Scaling Policy](https://www.anthropic.com/rsp) - Public framework for managing frontier-model risk as capabilities scale.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) - US government framework for identifying and managing AI risk.
- [Alignment Forum](https://www.alignmentforum.org/) - Research community and discussion hub focused on AI alignment.
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - The standard reference for LLM-specific vulnerabilities: prompt injection, insecure output handling, training data poisoning, and more.
- [METR](https://metr.org/) - Independent nonprofit that evaluates frontier models for dangerous autonomous capabilities before release.
- [UK AI Security Institute](https://www.aisi.gov.uk/) - Government body running pre-deployment safety testing on frontier models.
- [Constitutional AI (Anthropic)](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback) - Foundational paper on training models to be helpful and harmless using AI-generated feedback instead of only human labels.
- [Llama Guard](https://github.com/meta-llama/PurpleLlama) - Meta's open-weight safeguard model for classifying and filtering unsafe prompts and completions.

## Learning Resources

- [Andrej Karpathy's Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) - Video course building neural networks and LLMs from scratch.
- [fast.ai](https://www.fast.ai/) - Practical deep learning courses, code-first approach.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) - Free course on transformers and modern NLP.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for the checklist and submission format.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) - This list is dedicated to the public domain.
