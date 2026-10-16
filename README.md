# Awesome-Context-Aware-TTS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of models, datasets, and benchmarks for context-aware text-to-speech (TTS).

This list covers conversational speech synthesis and expressive text-to-speech using dialogue history, audio context, or multimodal signals.

Contributions and pull requests are welcome!

Links marked `Comming Soon` point to official resources that have not been released yet.

## Table of Contents

- [Model](#model)
- [Dataset](#dataset)
- [Benchmark](#benchmark)

## Model

| &nbsp;&nbsp;&nbsp;&nbsp;Date&nbsp;&nbsp;&nbsp;&nbsp; | Title | Type | Relevant&nbsp;Resources |
|:--------:|:------|:------:|:------:|
| 2026-10 | **Fish Audio Drama 3 Technical Report** | End-to-End | [arXiv](https://arxiv.org/abs/2610.18010)/[GitHub](https://github.com/fishaudio/fish-speech)/[HuggingFace](https://huggingface.co/fishaudio/drama-3)/[Demo](https://huggingface.co/spaces/fishaudio/Drama-3)/[Website](https://fish.audio/) |
| 2026-09 | **From Script to Drama: An Agentic Framework for Controllable Multi-Speaker Dialogue TTS** | Agent | [arXiv](https://arxiv.org/abs/2609.33362)/[Demo](https://xkx-hub.github.io/FStD-demo/) |
| 2026-09 | **Interactive TTS: Dynamic Speaking Style Adaptation for Expressive Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2609.25707)/[Demo](https://wjtian-wonderful.github.io/InteractiveTTS/) |
| 2026-09 | **COT-TTS: Audio Context-Aware Text-to-Speech with Chain-of-Thought Reasoning** | End-to-End | [arXiv](https://arxiv.org/abs/2609.22697)/[GitHub](https://github.com/LuckyBian/COT-TTS)/[Model](https://drive.google.com/drive/folders/1v1pnjed3XxWtlogxYP00dbsnaB6SrX0a?usp=sharing)/[Demo](https://luckybian.github.io/COT-TTS/) |
| 2026-09 | **Listen Before You Speak: Response Planning from Listener Facial Reactions for Conversational Speech Generation** | End-to-End | [arXiv](https://arxiv.org/abs/2609.21683)/[GitHub](https://github.com/CYJ1/ReACT-TTS_public) |
| 2026-08 | **X2Streaming-TTS: Causal Token-Level Text-to-Speech from Streaming Text with Speech-State Inheritance** | End-to-End | [arXiv](https://arxiv.org/abs/2608.18661)/[GitHub](https://github.com/X-Square-Robot/X2Streaming-TTS)/[HuggingFace](https://huggingface.co/x-square-robot/X2Streaming-TTS-1.7B)/[Demo](https://x-square-robot.github.io/X2Streaming-TTS/) |
| 2026-08 | **VoiceChat-TTS: A Low-Latency Continuous Speech Synthesis Model for Interactive Agents** | End-to-End | [arXiv](https://arxiv.org/abs/2608.13831)/[GitHub](https://github.com/NVIDIA-NeMo/Speech/tree/nemotron-labs-voicechat)/[HuggingFace](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B) |
| 2026-07 | **Harness TTS: Towards Context-Aware Expressive Speech Synthesis with Harness Layer** | Agent | [arXiv](https://arxiv.org/abs/2607.17900) |
| 2026-07 | **AuEmoChat: Authentic Emotion Understanding and Rendering for Conversational Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2607.15755)/[GitHub (Comming Soon)](https://github.com/AI-S2-Lab/AuEmoChat) |
| 2026-04 | **ActorMind: Emulating Human Actor Reasoning for Speech Role-Playing** | Agent | [arXiv](https://arxiv.org/abs/2604.11103)/[GitHub](https://github.com/OzymandiasChen/ActorMind)/[Demo](https://github.com/OzymandiasChen/ActorMind#demos) |
| 2025-05 | **Chain-Talker: Chain Understanding and Rendering for Empathetic Conversational Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2505.12597)/[GitHub (Comming Soon)](https://github.com/AI-S2-Lab/Chain-Talker) |
| 2025-02 | **DiffCSS: Diverse and Expressive Conversational Speech Synthesis with Diffusion Models** | End-to-End | [arXiv](https://arxiv.org/abs/2502.19924)/[Demo](https://w-w-h.github.io/DiffCSS/) |
| 2025-01 | **JELLY: Joint Emotion Recognition and Context Reasoning with LLMs for Conversational Speech Synthesis** | Cascaded | [arXiv](https://arxiv.org/abs/2501.04904)/[GitHub](https://github.com/jh-cha-prml/JELLY)/[Demo](https://jh-cha-prml.github.io/JELLY/) |
| 2024-09 | **H4C-TTS: Leveraging Multi-Modal Historical Context for Conversational Text-to-Speech** | End-to-End | [Paper](https://www.isca-archive.org/interspeech_2024/seong24_interspeech.html)/[Demo](https://seongdonghyun.github.io/H4C-TTS-DEMO/) |
| 2024-07 | **Generative Expressive Conversational Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2407.21491)/[GitHub](https://github.com/walker-hyf/GPT-Talker)/[Demo](https://walker-hyf.github.io/GPT-Talker/) |
| 2023-12 | **Emotion Rendering for Conversational Speech Synthesis with Heterogeneous Graph-Based Context Modeling** | End-to-End | [arXiv](https://arxiv.org/abs/2312.11947)/[GitHub](https://github.com/walker-hyf/ECSS)/[Demo](https://walker-hyf.github.io/ECSS/) |
| 2023-05 | **M2-CTTS: End-to-End Multi-scale Multi-modal Conversational Text-to-Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2305.02269)/[Demo](https://happylittlecat2333.github.io/icassp2023/) |
| 2022-10 | **FCTalker: Fine and Coarse Grained Context Modeling for Expressive Conversational Speech Synthesis** | End-to-End | [arXiv](https://arxiv.org/abs/2210.15360)/[GitHub](https://github.com/AI-S2-Lab/FCTalker)/[Demo](https://walker-hyf.github.io/FCTalker/) |
| 2022-07 | **DailyTalk: Spoken Dialogue Dataset for Conversational Text-to-Speech** | End-to-End | [arXiv](https://arxiv.org/abs/2207.01063)/[GitHub](https://github.com/keonlee9420/DailyTalk) |
| 2020-05 | **Conversational End-to-End TTS for Voice Agent** | End-to-End | [arXiv](https://arxiv.org/abs/2005.10438)/[Demo](https://hhguo.github.io/DemoConvTTS/) |

## Dataset

| &nbsp;&nbsp;&nbsp;&nbsp;Date&nbsp;&nbsp;&nbsp;&nbsp; | Title | Relevant&nbsp;Resources |
|:--------:|:------|:------:|
| 2026-09 | **COT-TTS: Audio Context-Aware Text-to-Speech with Chain-of-Thought Reasoning** | [arXiv](https://arxiv.org/abs/2609.22697)/[GitHub](https://github.com/LuckyBian/COT-TTS/tree/main/data%20construction)/[HuggingFace](https://huggingface.co/datasets/HKUSTAudio/ISCSLP2026-CoT-TTS)/[Demo](https://luckybian.github.io/COT-TTS/) |
| 2026-09 | **SpeechAnnotator: A Context-Aware Multi-Agent Framework and Benchmark for Multidimensional Speech Annotation** | [arXiv](https://arxiv.org/abs/2609.09947)/[GitHub (Comming Soon)](https://github.com/ASLP-lab/SpeechAnnotator)/[Demo](https://zhanqirui.github.io/SpeechAnnotator-demo-page/) |
| 2026-07 | **AuEmoChat: Authentic Emotion Understanding and Rendering for Conversational Speech Synthesis** | [arXiv](https://arxiv.org/abs/2607.15755)/[GitHub (Comming Soon)](https://github.com/AI-S2-Lab/AuEmoChat) |
| 2026-06 | **ISCSLP 2026 CoT-TTS Challenge: Chain-of-Thought Reasoning for Context-Aware Text-to-Speech** | [arXiv](https://arxiv.org/abs/2606.21933)/[GitHub](https://github.com/iscslp2026-cot-tts/baseline)/[HuggingFace](https://huggingface.co/datasets/HKUSTAudio/ISCSLP2026-CoT-TTS)/[Website](https://iscslp2026-cot-tts.github.io/challenge-website/) |
| 2026-05 | **Evaluating the Expressive Appropriateness of Speech in Rich Contexts** | [arXiv](https://arxiv.org/abs/2605.09413)/[GitHub](https://github.com/wangtianrui/CEAEval)/[HuggingFace](https://huggingface.co/datasets/TianRW/CEAEval-Data)/[Demo](https://wangtianrui.github.io/ceaeval/) |
| 2025-07 | **DNASpeech: A Contextualized and Situated Text-to-Speech Dataset with Dialogues, Narratives and Actions** | [Paper](https://aclanthology.org/2025.acl-long.911/)/[GitHub](https://github.com/steven-ccq/DNASpeech)/[Dataset](https://drive.google.com/drive/folders/14DAmOQhIuqyR9kduJr1iRLqXljV00BLc?usp=drive_link) |
| 2024-07 | **Generative Expressive Conversational Speech Synthesis** | [arXiv](https://arxiv.org/abs/2407.21491)/[GitHub](https://github.com/walker-hyf/NCSSD)/[HuggingFace](https://huggingface.co/datasets/walkerhyf/NCSSD) |
| 2022-07 | **DailyTalk: Spoken Dialogue Dataset for Conversational Text-to-Speech** | [arXiv](https://arxiv.org/abs/2207.01063)/[GitHub](https://github.com/keonlee9420/DailyTalk)/[Dataset](https://drive.google.com/drive/folders/1WRt-EprWs-2rmYxoWYT9_13omlhDHcaL) |

## Benchmark

| &nbsp;&nbsp;&nbsp;&nbsp;Date&nbsp;&nbsp;&nbsp;&nbsp; | Title | Relevant&nbsp;Resources |
|:--------:|:------|:------:|
| 2026-09 | **From Script to Drama: An Agentic Framework for Controllable Multi-Speaker Dialogue TTS** | [arXiv](https://arxiv.org/abs/2609.33362)/[Demo](https://xkx-hub.github.io/FStD-demo/) |
| 2026-09 | **COT-TTS: Audio Context-Aware Text-to-Speech with Chain-of-Thought Reasoning** | [arXiv](https://arxiv.org/abs/2609.22697)/[GitHub](https://github.com/LuckyBian/COT-TTS)/[HuggingFace](https://huggingface.co/datasets/HKUSTAudio/ISCSLP2026-CoT-TTS/tree/main/eval-dataset)/[Demo](https://luckybian.github.io/COT-TTS/) |
| 2026-09 | **SpeechAnnotator: A Context-Aware Multi-Agent Framework and Benchmark for Multidimensional Speech Annotation** | [arXiv](https://arxiv.org/abs/2609.09947)/[GitHub (Comming Soon)](https://github.com/ASLP-lab/SpeechAnnotator)/[Demo](https://zhanqirui.github.io/SpeechAnnotator-demo-page/) |
| 2026-07 | **Harness TTS: Towards Context-Aware Expressive Speech Synthesis with Harness Layer** | [arXiv](https://arxiv.org/abs/2607.17900) |
| 2026-07 | **RW-Voice-EQ Bench: A Real World Benchmark for Evaluating Voice AI Systems** | [arXiv](https://arxiv.org/abs/2607.14846)/[Demo](https://huggingface.co/spaces/HumeAI/rw-voice-eq) |
| 2026-06 | **ISCSLP 2026 CoT-TTS Challenge: Chain-of-Thought Reasoning for Context-Aware Text-to-Speech** | [arXiv](https://arxiv.org/abs/2606.21933)/[GitHub](https://github.com/iscslp2026-cot-tts/baseline)/[HuggingFace](https://huggingface.co/datasets/HKUSTAudio/ISCSLP2026-CoT-TTS)/[Website](https://iscslp2026-cot-tts.github.io/challenge-website/) |
| 2026-06 | **NVMOS: Non-Verbal Vocalization Quality Assessment in Speech** | [arXiv](https://arxiv.org/abs/2606.15888)/[GitHub](https://github.com/yongaifadian1/NVMOS)/[HuggingFace](https://huggingface.co/maimai11/NVMOS)/[Demo](https://yongaifadian1.github.io/NVMOS/) |
| 2026-05 | **Evaluating the Expressive Appropriateness of Speech in Rich Contexts** | [arXiv](https://arxiv.org/abs/2605.09413)/[GitHub](https://github.com/wangtianrui/CEAEval)/[HuggingFace](https://huggingface.co/datasets/TianRW/CEAEval-Data)/[Demo](https://wangtianrui.github.io/ceaeval/) |
| 2026-04 | **ActorMind: Emulating Human Actor Reasoning for Speech Role-Playing** | [arXiv](https://arxiv.org/abs/2604.11103)/[GitHub](https://github.com/OzymandiasChen/ActorMind)/[Dataset](https://github.com/OzymandiasChen/ActorMind/tree/main/annotation)/[Demo](https://github.com/OzymandiasChen/ActorMind#demos) |
| 2026-04 | **Knowing What to Stress: A Discourse-Conditioned Text-to-Speech Benchmark** | [arXiv](https://arxiv.org/abs/2604.10580) |
| 2026-04 | **SpeechParaling-Bench: A Comprehensive Benchmark for Paralinguistic-Aware Speech Generation** | [arXiv](https://arxiv.org/abs/2604.20842)/[GitHub](https://github.com/Northern-byte-bit/SpeechParaling-Bench)/[HuggingFace](https://huggingface.co/datasets/Ruohan2/SpeechParaling-Bench)/[Demo](https://speechparaling-bench.github.io/) |
| 2025-09 | **VStyle: A Benchmark for Voice Style Adaptation with Spoken Instructions** | [arXiv](https://arxiv.org/abs/2509.09716)/[GitHub](https://github.com/alibaba/vstyle)/[HuggingFace](https://huggingface.co/datasets/zhanjun/VStyle)/[Demo](https://junzhan2000.github.io/VStyle.github.io/) |
| 2025-07 | **DNASpeech: A Contextualized and Situated Text-to-Speech Dataset with Dialogues, Narratives and Actions** | [Paper](https://aclanthology.org/2025.acl-long.911/)/[GitHub](https://github.com/steven-ccq/DNASpeech)/[Dataset](https://drive.google.com/drive/folders/14DAmOQhIuqyR9kduJr1iRLqXljV00BLc?usp=drive_link) |
