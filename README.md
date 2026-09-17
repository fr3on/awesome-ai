# Awesome AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of frameworks, models, infrastructure, and vertical tools for building with AI.

Focused on things that are actually usable today: open-weight models you can run, APIs you can call, frameworks you'd reach for in production. Not a dump of every paper or demo.

Contributions welcome — see [Contributing](#contributing).

## Contents

- [Foundation Models & Reasoning](#foundation-models--reasoning)
- [Multimodal & Generative Media](#multimodal--generative-media)
- [Voice & Speech AI](#voice--speech-ai)
- [Agent Frameworks & Memory](#agent-frameworks--memory)
- [Browser & Computer-Use Agents](#browser--computer-use-agents)
- [Coding Agents & Dev Tools](#coding-agents--dev-tools)
- [RAG & Vector Search](#rag--vector-search)
- [Inference & Serving](#inference--serving)
- [Evaluation & Observability](#evaluation--observability)
- [Fine-Tuning & Training](#fine-tuning--training)
- [Hardware Acceleration & Kernels](#hardware-acceleration--kernels)
- [Robotics & Embodied AI](#robotics--embodied-ai)
- [Synthetic Data & Curation](#synthetic-data--curation)
- [MENA / Arabic-Language AI](#mena--arabic-language-ai)
- [Vertical & Domain-Specific](#vertical--domain-specific)
- [Datasets](#datasets)
- [Safety & Alignment](#safety--alignment)
- [Learning Resources](#learning-resources)

## Foundation Models & Reasoning

- [Claude](https://www.anthropic.com/claude) - Anthropic's frontier model family, known for steerability, long context, and agentic tool use.
- [Command R+](https://cohere.com/command) - Cohere's enterprise-focused model family optimized for multilingual retrieval-augmented generation and tool integration.
- [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3) - Open-weight MoE architecture offering frontier-class performance with high compute and inference efficiency.
- [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) - Open reasoning model trained with large-scale reinforcement learning, demonstrating competitive reasoning on math, code, and logic.
- [Gemini](https://deepmind.google/technologies/gemini/) - Google DeepMind's native multimodal model family, offering multi-million token context windows and audio-visual streaming.
- [Gemma](https://ai.google.dev/gemma) - Google's lightweight open-weight model family built on Gemini technology under a permissive license.
- [GPT](https://openai.com/gpt-4) - OpenAI's flagship conversational and general-purpose model family.
- [Grok](https://x.ai/) - Frontier multimodal models from xAI with native real-time web retrieval.
- [Llama](https://www.llama.com/) - Meta's open-weight model family, the primary base for community fine-tuning and local deployment.
- [Mistral](https://mistral.ai/) - Open and commercial models from Mistral AI, recognized for high efficiency and dense/MoE architectures.
- [OpenAI Reasoning (o1 / o3-mini)](https://openai.com/index/openai-o1-system-card/) - Models that leverage test-time compute to think through complex math, coding, and scientific reasoning tasks before answering.
- [Phi](https://github.com/microsoft/Phi-3CookBook) - Microsoft's small language model family trained on high-quality synthetic and filtered textbook data for constrained edge devices.
- [Qwen](https://github.com/QwenLM/Qwen) - Alibaba's open-weight foundation and reasoning models, with strong multilingual, coding, and mathematical capabilities.

## Multimodal & Generative Media

- [CogVideoX](https://github.com/THUDM/CogVideo) - Open-source 3D VAE video diffusion transformer for high-quality text-to-video generation on consumer and enterprise GPUs.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Modular, node-based graphical interface and execution backend for stable diffusion, flux, and video generation workflows.
- [FLUX](https://github.com/black-forest-labs/flux) - Open-weight image generation models from Black Forest Labs, offering state-of-the-art prompt adherence and typography rendering.
- [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) - Open-source 13B video foundation model from Tencent featuring a dual-stream visual-language architecture.
- [Midjourney](https://www.midjourney.com/) - Commercial text-to-image generation platform known for high aesthetic quality and artistic rendering.
- [Runway](https://runwayml.com/) - Commercial generative video platform offering text-to-video, image-to-video, and cinematic camera controls.
- [Sora](https://openai.com/sora/) - OpenAI's text-to-video model capable of generating minute-long scenes with camera motion and physical consistency.
- [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) - Open-weight text-to-image diffusion model family that established open ecosystem generative imaging.
- [Suno](https://suno.com/) - AI music generation platform that produces complete songs with vocal arrangements and instrumentation from text prompts.
- [TRELLIS](https://github.com/microsoft/TRELLIS) - Open-source model producing structured 3D representations (Gaussian splats, Radiance Fields, meshes) from a single 2D image.
- [Wan2.1](https://github.com/Wan-Video/Wan2.1) - Alibaba's open-weight video foundation model family supporting high-resolution text-to-video and image-to-video generation.

## Voice & Speech AI

- [AssemblyAI](https://www.assemblyai.com/) - Production API for speech-to-text, speaker diarization, streaming transcription, and speech understanding models.
- [CosyVoice](https://github.com/FunAudioLLM/CosyVoice) - Multi-lingual speech generation model supporting zero-shot cross-lingual voice cloning and fine-grained emotional control.
- [Deepgram](https://deepgram.com/) - Real-time speech-to-text and text-to-speech API engineered for sub-second latency voice applications.
- [ElevenLabs](https://elevenlabs.io/) - Commercial text-to-speech, voice cloning, and Conversational AI agent platform.
- [F5-TTS](https://github.com/SWivid/F5-TTS) - Non-autoregressive speech synthesis system based on flow matching with rapid zero-shot voice cloning.
- [Kokoro](https://github.com/hexgrad/kokoro) - Ultra-lightweight 82M open-weight text-to-speech model capable of fast, natural voice generation on CPU and edge devices.
- [LiveKit Agents](https://github.com/livekit/agents) - Open-source framework for building real-time multimodal voice and video AI agents over WebRTC.
- [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) - Low-latency speech-to-speech multimodal API for real-time conversational agents.
- [Whisper](https://github.com/openai/whisper) - OpenAI's open-weight automatic speech recognition (ASR) model with robust multilingual transcription and translation.

## Agent Frameworks & Memory

- [Agno](https://github.com/agno-agi/agno) - High-performance multi-modal agent framework (formerly Phidata) with integrated memory, knowledge, and tool execution.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent conversational framework enabling cooperative agents with configurable automation patterns.
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) - Anthropic's SDK for building agents with tool calling, context management, and safety boundaries.
- [Composio](https://github.com/ComposioHQ/composio) - Tool integration platform providing AI agents with managed authentication and execution for 250+ external APIs and applications.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing autonomous agents to collaborate on structured, multi-step workflows.
- [DSPy](https://github.com/stanfordnlp/dspy) - Declarative programming framework that programmatically optimizes LLM prompts and weights rather than relying on manual prompting.
- [E2B](https://github.com/e2b-dev/E2B) - Secure cloud sandboxes designed for AI agents to safely execute untrusted Python code and bash commands in isolated microVMs.
- [LangChain](https://github.com/langchain-ai/langchain) - Ecosystem framework for chaining LLM calls, retrieval components, prompt templates, and tools.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-based orchestration engine for building cyclic, stateful, multi-agent applications with human-in-the-loop controls.
- [Letta](https://github.com/letta-ai/letta) - Stateful agent service (formerly MemGPT) featuring hierarchical memory architectures and self-editing memory blocks across conversations.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework connecting LLMs to external enterprise data sources, document parsers, and custom knowledge indices.
- [Mem0](https://github.com/mem0ai/mem0) - Personalized memory layer for AI agents that continuously learns user preferences and context across sessions.
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Open standard created by Anthropic for exposing tools, prompts, and resources to AI agents through standardized client-server interfaces.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Enterprise agent orchestration SDK from Microsoft with support for C#, Python, and Java.
- [Smolagents](https://github.com/huggingface/smolagents) - Lightweight Hugging Face library where agents interact by writing executable Python code actions rather than JSON tool calls.

## Browser & Computer-Use Agents

- [Anthropic Computer Use](https://docs.anthropic.com/en/docs/build-with-claude/computer-use) - Frontier model capability enabling Claude to control the mouse, keyboard, and inspect screen state on desktop operating systems.
- [Browser Use](https://github.com/browser-use/browser-use) - Open-source library enabling AI agents to autonomously navigate, interact with, and extract data from websites via browser automation.
- [LaVague](https://github.com/lavague-ai/LaVague) - Open-source Large Action Model framework for automating web workflows using AI and browser drivers.
- [OpenAdapt](https://github.com/OpenAdaptAI/OpenAdapt) - Open-source AI desktop process automation tool recording and replaying user interactions visually.
- [Playwright](https://github.com/microsoft/playwright) - Reliable end-to-end browser automation framework commonly used as the execution runtime for browser agents.
- [Stagehand](https://github.com/browserbase/stagehand) - AI web browsing framework built on Playwright with natural language extraction, action execution, and self-healing selectors.
- [UI-TARS](https://github.com/bytedance/UI-TARS) - Open-source end-to-end GUI agent model by ByteDance capable of native keyboard and mouse interaction across mobile, desktop, and web.

## Coding Agents & Dev Tools

- [Aider](https://github.com/Aider-AI/aider) - Terminal-based AI pair programmer that pairs with local git repositories to apply multi-file edits with clean commit messages.
- [Claude Code](https://claude.com/claude-code) - Anthropic's agentic command-line interface that reads, edits, runs, and tests code directly in project repositories.
- [Cline](https://github.com/cline/cline) - Autonomous coding assistant extension for VS Code that executes terminal commands, edits files, and interacts with local browsers.
- [Codestral](https://mistral.ai/news/codestral/) - Mistral's open-weight code generation foundation model trained on over 80 programming languages with 32k context.
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant for VS Code and JetBrains with configurable model endpoints, codebase indexing, and tab completion.
- [Cursor](https://cursor.com/) - AI-first IDE built on a fork of VS Code featuring full-codebase indexing, multi-file agentic editing, and terminal integration.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer providing inline completions and multi-file workspace agent mode across major editors.
- [Goose](https://github.com/block/goose) - Open-source autonomous developer agent by Block that runs in your terminal to automate repetitive software engineering tasks.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open platform for autonomous software development agents capable of browsing documentation, debugging errors, and solving issues in Docker sandboxes.
- [Plandex](https://github.com/plandex-ai/plandex) - Open-source terminal coding engine built for complex multi-stage tasks with sandbox execution and git-aware diff reviews.
- [Roo Code](https://github.com/RooVetGit/Roo-Code) - Autonomous coding extension for VS Code with custom agent personas, multi-directory workspaces, and MCP support.
- [SWE-bench](https://github.com/princeton-nlp/SWE-bench) - Benchmark and evaluation harness for testing language models and autonomous agents on real-world GitHub issues.
- [Windsurf](https://windsurf.com/) - AI-native code editor featuring Cascade mode for real-time collaborative multi-file editing and terminal automation.

## RAG & Vector Search

- [BM25s](https://github.com/xhluca/bm25s) - Pure-Python implementation of BM25 lexical search designed for seamless hybrid sparse-dense retrieval.
- [Chroma](https://github.com/chroma-core/chroma) - Open-source AI-native embedding database focused on simplicity and rapid local-to-cloud deployment.
- [ColPali](https://github.com/illuin-tech/colpali) - Vision-language document retrieval model enabling late-interaction multi-vector search directly on PDF page screenshots without OCR.
- [FlashRank](https://github.com/PrithivirajDamodaran/FlashRank) - Lightweight CPU-native reranking library with zero PyTorch or CUDA dependencies.
- [GraphRAG](https://github.com/microsoft/graphrag) - Modular knowledge-graph-based retrieval pipeline from Microsoft designed for holistic reasoning and summarization across document collections.
- [LanceDB](https://github.com/lancedb/lancedb) - Serverless, embedded vector database built on Apache Arrow and Lance columnar format with multimodal storage.
- [LightRAG](https://github.com/HKUDS/LightRAG) - Dual-level knowledge graph retrieval framework balancing entity relationship extraction with low retrieval latency.
- [Milvus](https://github.com/milvus-io/milvus) - Distributed, cloud-native vector database engineered for billion-scale similarity search and high-throughput production.
- [pgvector](https://github.com/pgvector/pgvector) - PostgreSQL extension adding native vector similarity search, enabling relational and vector data in a single database.
- [Pinecone](https://www.pinecone.io/) - Fully managed cloud vector database offering fast indexing, metadata filtering, and serverless scaling.
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector search engine and database written in Rust with rich payload filtering and hybrid search.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Open-source ingestion engine for partitioning, cleaning, and extracting structured content from complex PDFs, Word docs, and slides.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector database supporting hybrid search, multi-tenancy, and modular vectorizers.

## Inference & Serving

- [ExLlamaV2](https://github.com/turboderp/exllamav2) - Fast inference library engineered specifically for modern quantized formats (EXL2 and GPTQ) on consumer GPUs.
- [Instructor](https://github.com/jxnl/instructor) - Python library extending Pydantic to guarantee validated, structured outputs from commercial and open LLM APIs.
- [LiteLLM](https://github.com/BerriAI/litellm) - Lightweight proxy and Python SDK to call 100+ LLMs using OpenAI standard format with unified cost tracking and load balancing.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Pure C/C++ inference engine for LLaMA and other open architectures, enabling efficient local execution across diverse hardware.
- [LM Studio](https://lmstudio.ai/) - Desktop GUI and local server for finding, downloading, and running open-weight GGUF models on Apple Silicon and Windows/Linux GPUs.
- [MLX LM](https://github.com/ml-explore/mlx-examples/tree/main/llms) - Apple's native machine learning framework for running and fine-tuning LLMs with unified memory on Apple Silicon.
- [Ollama](https://github.com/ollama/ollama) - Local model management CLI and API that packages open-weight LLMs into simple bundles with an OpenAI-compatible endpoint.
- [Outlines](https://github.com/dottxt-ai/outlines) - Guided text generation library using finite-state machines to guarantee JSON schema compliance and regex adherence during token sampling.
- [SGLang](https://github.com/sgl-project/sglang) - High-throughput LLM and VLM serving engine featuring RadixAttention for automatic KV cache reuse across complex multi-turn workflows.
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - NVIDIA's enterprise tensor compilation and runtime library for maximizing GPU inference throughput and minimizing latency.
- [TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference) - Hugging Face's production inference server with tensor parallelism, dynamic batching, and FlashAttention support.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput, memory-efficient serving engine featuring PagedAttention, widely used as the default open-weight serving backend.

## Evaluation & Observability

- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source AI observability and evaluation platform with OpenTelemetry tracing, hallucination detection, and prompt analysis.
- [DeepEval](https://github.com/confident-ai/deepeval) - Unit-testing framework for LLM applications providing production metrics for hallucination, answer relevancy, and G-Eval.
- [Helicone](https://github.com/Helicone/helicone) - Lightweight LLM proxy providing cost tracking, latency analytics, response caching, and rate limiting with a one-line integration.
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - Evaluation framework created by the UK AI Safety Institute for systematic, reproducible evaluation of frontier model capabilities.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform providing detailed tracing, prompt versioning, user feedback tracking, and evaluation.
- [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) - The standard unified benchmarking framework for evaluating open LLMs across hundreds of academic and standardized tasks.
- [OpenRouter](https://openrouter.ai/) - Unified API gateway aggregating 200+ models with automated fallback routing, competitive pricing, and load balancing.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - CLI and CI/CD testing tool for evaluating prompt quality, red-teaming security risks, and benchmarking LLM outputs.
- [Ragas](https://github.com/explodinggradients/ragas) - Evaluation framework specifically designed for measuring retrieval and generation quality in RAG pipelines.
- [Weights & Biases](https://wandb.ai/) - Developer platform for tracking machine learning experiments, hyperparameter sweeps, model checkpoints, and LLM evaluations.

## Fine-Tuning & Training

- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) - Config-driven framework that streamlines fine-tuning of open-weight LLMs with support for LoRA, QLoRA, and distributed backends.
- [DeepSpeed](https://github.com/microsoft/DeepSpeed) - Microsoft's deep learning optimization library implementing ZeRO memory optimization for distributed model training.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Unified fine-tuning framework supporting 100+ LLMs and VLMs with a web-based UI, multi-GPU scaling, and efficient quantization.
- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) - NVIDIA's large-scale transformer training framework implementing tensor, pipeline, and sequence parallelism for multi-node clusters.
- [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) - Ray-based distributed RLHF library supporting 70B+ model training with PPO, DPO, and KTO.
- [PEFT](https://github.com/huggingface/peft) - Hugging Face's library for parameter-efficient fine-tuning methods including LoRA, prefix tuning, and AdaLoRA.
- [torchtune](https://github.com/pytorch/torchtune) - PyTorch-native library providing modular recipes for fine-tuning LLMs with minimal abstractions.
- [TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl) - Hugging Face's full-stack library for post-training LLMs using SFT, DPO, PPO, and GRPO.
- [Unsloth](https://github.com/unslothai/unsloth) - High-speed, memory-efficient fine-tuning library providing hand-optimized CUDA kernels for LoRA and QLoRA training.
- [verl](https://github.com/volcengine/verl) - Flexible reinforcement learning framework featuring Hybrid Programming for scaling post-training RL (GRPO) on large models.

## Hardware Acceleration & Kernels

- [bitsandbytes](https://github.com/bitsandbytes-foundation/bitsandbytes) - Lightweight wrapper library around CUDA custom functions providing 8-bit optimizers and 4-bit/8-bit quantization primitives.
- [CUTLASS](https://github.com/NVIDIA/cutlass) - NVIDIA's open-source collection of CUDA C++ template abstractions for high-performance matrix multiplication (GEMM) and tensor operations.
- [FlashAttention](https://github.com/Dao-AILab/flash-attention) - Fast and memory-efficient exact attention algorithm reducing memory access overhead between GPU HBM and SRAM.
- [Triton](https://github.com/triton-lang/triton) - Open-source programming language and compiler from OpenAI for writing highly efficient custom GPU kernels directly in Python.

## Robotics & Embodied AI

- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) - Generative, differentiable physics simulation platform engineered for robotics, embodied AI, and tactile sensing.
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - Unified and modular framework for robot learning in NVIDIA Isaac Sim, accelerating policy training and sim-to-real transfer.
- [LeRobot](https://github.com/huggingface/lerobot) - Hugging Face's open-source library for real-world robotics, imitation learning, and affordable hardware teleoperation.
- [MuJoCo](https://github.com/google-deepmind/mujoco) - Multi-Joint dynamics with Contact, DeepMind's open-source physics engine widely used for robot simulation and reinforcement learning.
- [Octo](https://github.com/octo-models/octo) - Open-source generalist robot manipulation policy pretrained on 800k diverse robot interaction trajectories.
- [Open X-Embodiment](https://robotics-transformer-x.github.io/) - Cross-embodiment initiative providing open robotic manipulation datasets and foundation policies across 22 robot types.
- [OpenVLA](https://github.com/openvla/openvla) - Open-source 7B vision-language-action model trained on 970k robot demonstrations for direct robotic control.

## Synthetic Data & Curation

- [Argilla](https://github.com/argilla-io/argilla) - Open-source collaboration platform for data curation, human-in-the-loop feedback, and evaluation dataset validation.
- [Cosmopedia](https://huggingface.co/datasets/HuggingFaceTB/cosmopedia) - Synthetic dataset of 25 billion tokens across synthetic textbooks, stories, and tutorials generated by Mixtral-8x7B.
- [Data-Juicer](https://github.com/modelscope/data-juicer) - One-stop multimodal data processing system with 100+ filtering, deduplication, and transformation operators for LLM pretraining.
- [distilabel](https://github.com/argilla-io/distilabel) - Framework for synthesizing datasets, generating multi-turn dialogues, and automated preference annotation using LLM-as-a-judge.
- [FineWeb-Edu](https://huggingface.co/datasets/HuggingFaceFW/fineweb-edu) - 1.3-trillion-token web dataset filtered by an educational quality classifier to boost reasoning and knowledge capabilities.
- [Magpie](https://github.com/magpie-align/magpie) - Self-synthesis framework generating high-quality instruction-tuning and alignment data directly from aligned models without prompt seeds.
- [UltraFeedback](https://huggingface.co/datasets/openbmb/UltraFeedback) - Multi-aspect preference dataset widely used to train open reward models and align models with DPO.

## MENA / Arabic-Language AI

- [AceGPT](https://github.com/FreedomIntelligence/AceGPT) - Open-source Arabic foundation and instruction-tuned language models by MBZUAI and CUHK.
- [ALLaM](https://huggingface.co/sdaia) - Arabic foundation model developed by SDAIA (Saudi Data and Artificial Intelligence Authority) optimized for Arabic language understanding.
- [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) - Open-source Arabic NLP toolkit providing morphological modeling, dialect identification, and named-entity recognition from NYU Abu Dhabi.
- [Dike](https://dike.it.com) - MENA legal source layer providing a bilingual API that grounds AI agents in primary legal sources across Saudi Arabia, UAE, Qatar, Kuwait, and Egypt.
- [Falcon](https://falconllm.tii.ae/) - Open-weight foundation model series developed by the Technology Innovation Institute (TII) in Abu Dhabi.
- [Fanar](https://fanar.qa/) - Arabic language foundation model initiative developed by Qatar Computing Research Institute (QCRI) aligned with Arab cultural heritage.
- [Jais](https://huggingface.co/inceptionai/jais-13b-chat) - Open-weight Arabic-English bilingual pretrained model family developed by Inception (G42) and MBZUAI.

## Vertical & Domain-Specific

- [AlphaFold](https://github.com/google-deepmind/alphafold) - Google DeepMind's Nobel Prize-winning foundation system for accurately predicting 3D structures of proteins, DNA, RNA, and ligands.
- [BioGPT](https://github.com/microsoft/BioGPT) - Domain-specific generative transformer pretrained on biomedical literature for biomedical NLP tasks.
- [BloombergGPT](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/) - 50-billion parameter language model trained on Bloomberg's proprietary financial data alongside general web text.
- [ChemCrow](https://github.com/ur-whitelab/chemcrow-public) - Open chemistry agent integrating 18 expert computational chemistry tools for drug discovery and organic synthesis.
- [Evo](https://github.com/evo-design/evo) - Biological foundation model trained on 300 billion nucleotides for generating DNA, RNA, and protein sequences at whole-genome scale.
- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) - Open-source financial LLM ecosystem covering financial sentiment analysis, automated trading strategies, and financial news analysis.
- [LegalBench](https://github.com/HazyResearch/legalbench) - Open, collaboratively constructed benchmark comprising 162 tasks for evaluating legal reasoning in language models.
- [Med-PaLM](https://sites.research.google/med-palm/) - Google's medical-domain model family benchmarked against clinical licensing exams and consumer medical questions.
- [OpenBioLLM](https://huggingface.co/aaditya/Llama3-OpenBioLLM-70B) - Open-source biomedical foundation model series fine-tuned for medical summarization and clinical question answering.
- [OpenFold](https://github.com/aqlaboratory/openfold) - Trainable, open-source reproduction of AlphaFold2 enabling molecular biologists to train custom biomolecular structure models.
- [ProGen](https://github.com/salesforce/progen) - Language model for protein design generating functional artificial enzymes with customizable biological properties.

## Datasets

- [C4](https://huggingface.co/datasets/allenai/c4) - Colossal Clean Crawled Corpus, a petabyte-scale cleaned snapshot of Common Crawl data used to pretrain T5 and modern language models.
- [Common Crawl](https://commoncrawl.org/) - Petabyte-scale open repository of web crawl data, serving as the raw foundation for most web-scale LLM training.
- [Dolma](https://github.com/allenai/dolma) - Allen AI's open 3-trillion-token pretraining dataset with full data curation recipes and transparent data provenance.
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 15-trillion-token deduplicated and filtered web corpus from Hugging Face designed for pretraining frontier-grade models.
- [GSM8K](https://github.com/openai/grade-school-math) - Benchmark dataset of 8,500 diverse grade-school math word problems requiring multi-step reasoning.
- [Hugging Face Datasets](https://huggingface.co/datasets) - Community hub hosting hundreds of thousands of machine learning datasets across all modalities with streaming access.
- [LAION-5B](https://laion.ai/blog/laion-5b/) - Open dataset containing 5.85 billion image-text pairs, widely used for training open multimodal vision and diffusion models.
- [LMSYS Chatbot Arena Conversations](https://huggingface.co/datasets/lmsys/lmsys-chat-1m) - Dataset of 1 million real-world human-LLM conversations across diverse models for alignment and preference modeling.
- [MATH](https://github.com/hendrycks/math) - Challenging dataset of 12,500 high-school competition mathematics problems with full step-by-step LaTeX solutions.
- [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) - Extended multi-task language understanding benchmark with increased reasoning difficulty, expanded options, and reasoning noise reduction.
- [NuminaMath](https://huggingface.co/datasets/AI-MO/NuminaMath-CoT) - Large-scale mathematical reasoning dataset of 860k problems with chain-of-thought solutions, winner of the AIMO progress prize.
- [Open-Thoughts](https://huggingface.co/datasets/open-thoughts/Open-Thoughts-114k) - High-quality reasoning dataset with detailed step-by-step chain-of-thought trajectories curated for distillation.
- [OpenOrca](https://huggingface.co/datasets/Open-Orca/OpenOrca) - Instruction-tuning collection of millions of GPT-augmented completions mapped over FLAN-style prompts.
- [RedPajama](https://github.com/togethercomputer/RedPajama-Data) - Open reproduction of the LLaMA pretraining dataset with transparent token filtering and licensing specifications.
- [ShareGPT](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) - Community-collected conversational dataset of multi-turn user conversations with ChatGPT, foundational for early instruction tuning.
- [The Pile](https://pile.eleuther.ai/) - 825 GiB diverse English text dataset constructed by EleutherAI for training large language models.
- [UltraChat](https://huggingface.co/datasets/stingning/ultrachat) - Multi-turn conversational dataset containing 1.4 million dialogues across diverse topics, used to train Zephyr and open chat models.

## Safety & Alignment

- [Alignment Forum](https://www.alignmentforum.org/) - Research community and discussion hub focused on technical AI alignment and AI safety research.
- [Anthropic's Responsible Scaling Policy](https://www.anthropic.com/rsp) - Public policy framework detailing concrete safety levels and mitigations required as model capabilities increase.
- [Constitutional AI](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback) - Foundational methodology for training harmless and helpful AI systems using AI feedback against written constitutions.
- [CyberSecEval](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) - Meta's comprehensive evaluation suite for quantifying cybersecurity risks, code security vulnerabilities, and cyberattack assistance in LLMs.
- [DecodingTrust](https://github.com/AI-secure/DecodingTrust) - Comprehensive trustworthiness evaluation platform assessing toxicity, bias, robustness, and privacy in language models.
- [Garak](https://github.com/leondz/garak) - Open-source LLM vulnerability scanner that tests models for prompt injection, jailbreaks, data leakage, and hallucination vulnerabilities.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Framework for specifying, validating, and enforcing output schemas and safety policies on LLM responses.
- [HarmBench](https://github.com/centerforaisafety/HarmBench) - Standardized evaluation framework and dataset for automated red-teaming and assessing adversarial robustness in LLMs.
- [JailbreakBench](https://github.com/JailbreakBench/jailbreakbench) - Standardized benchmark and leaderboard tracking adversarial jailbreak vulnerabilities and defenses in frontier models.
- [Llama Guard](https://github.com/meta-llama/PurpleLlama) - Meta's open safeguard model family for classifying input prompts and generated responses against safety taxonomies.
- [METR](https://metr.org/) - Nonprofit research organization evaluating frontier models for catastrophic risks and autonomous capabilities prior to deployment.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - Open-source toolkit from NVIDIA for adding programmable topical, safety, and security guardrails to conversational systems.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) - Voluntary guidance framework from the US government for governing and mitigating risks in AI systems.
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - Authoritative cybersecurity reference documenting top vulnerabilities in LLM applications, from prompt injections to supply-chain risks.
- [PyRIT](https://github.com/Azure/PyRIT) - Microsoft's Python Risk Identification Tool for automated red-teaming, jailbreak evaluation, and AI security probing.
- [UK AI Security Institute](https://www.aisi.gov.uk/) - National institute conducting technical safety evaluations and red-teaming on advanced frontier AI models.

## Learning Resources

- [Andrej Karpathy's Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) - Video lecture series building micrograd, makemore, and GPT architectures from scratch in Python and PyTorch.
- [DeepLearning.AI](https://www.deeplearning.ai/) - Education platform founded by Andrew Ng offering courses on LLM architecture, agentic design patterns, and generative AI.
- [Designing Machine Learning Systems](https://github.com/chiphuyen/dmls-book) - Practical guide by Chip Huyen on building reliable, scalable, and maintainable production machine learning systems.
- [Eugene Yan's Applied LLM Guides](https://eugeneyan.com/writing/llm-patterns/) - Detailed, battle-tested practical patterns and system architecture guides for building production LLM applications.
- [fast.ai](https://www.fast.ai/) - Practical, code-first deep learning courses teaching practical model training and computer vision / NLP workflows.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) - Free interactive course covering modern transformer architectures, datasets, and tokenizers.
- [Jay Alammar's The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) - Visual guide deconstructing the mathematical mechanics of attention mechanisms and transformer models.
- [Lil'Log](https://lilianweng.github.io/) - Comprehensive technical blog by Lilian Weng featuring rigorous mathematical deep dives into LLMs, diffusion, agents, and alignment.
- [LLM Visualization](https://bbycroft.net/llm) - Interactive 3D web visualization showing token-by-token tensor transformations and matrix multiplications inside a Transformer model.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Comprehensive open-source guide and paper repository covering modern prompting techniques, reasoning strategies, and evaluation.
- [Stanford CS229: Machine Learning](https://cs229.stanford.edu/) - Stanford's foundational machine learning course materials covering statistical learning theory, supervised learning, and neural networks.
- [The LLM Course](https://github.com/mlabonne/llm-course) - Step-by-step open curriculum and roadmap covering modern LLM architecture, fine-tuning, quantization, and deployment.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for the checklist and submission format.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) - This list is dedicated to the public domain.
