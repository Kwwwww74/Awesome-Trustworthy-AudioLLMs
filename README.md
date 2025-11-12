# 🎧 Awesome Trustworthy Audio-LLMs  

*A curated and continuously evolving collection of research, benchmarks, datasets, and open resources on **Trustworthy Audio Large Language Models (Audio-LLMs)** — spanning the entire spectrum of **safety, robustness, alignment, security, interpretability, and ethical governance** across **speech perception, generation, and multimodal intelligence.***

---

## 🌍 Introduction  

With the rapid rise of **Audio Large Language Models (Audio-LLMs)** — systems capable of understanding, reasoning, and generating human speech — ensuring their **trustworthiness and safety** has become an essential research frontier.  

This repository serves as a **comprehensive and community-driven hub** for tracking progress in the field of **trustworthy audio intelligence**, integrating advances from **AI safety**, **robust learning**, **speech security**, and **responsible multimodal modeling**.  

It highlights research on:
- 🧩 **Safety alignment** and instruction robustness in speech-driven LLMs  
- ⚔️ **Adversarial and backdoor attacks** on audio and multimodal models  
- 🛡️ **Defense and detection** strategies for secure model deployment  
- 📊 **Benchmarks and evaluation** frameworks for risk assessment  
- 🧠 **Interpretability, transparency, and governance** in speech AI  

Together, these works aim toward a future where Audio-LLMs are **not only capable of understanding voices — but also worthy of being trusted**.

---

## 🧭 Table of Contents  

- [Overview](#overview)
- [Recent News](#recent-news)
- [Research Collections](#research-collections)
  - [Surveys & Overviews](#surveys--overviews)
  - [Attacks & Risks](#attacks--risks)
  - [Defense & Safety Alignment](#defense--safety-alignment)
  - [Benchmarks & Evaluation](#benchmarks--evaluation)
  - [Datasets](#datasets)
- [How to Contribute](#how-to-contribute)
- [Acknowledgement](#acknowledgement)
- [Citation](#citation)
- [License](#license)

---

## 🗞️ Recent News  
- **[2025.11]** Repository launched — initial release of *AudioSafe*, *HIN*, *TALEBench*, and *Fine-Mixing* resources.  
- **[2025.10]** Added new section on *multimodal reasoning safety* (video + audio).  
- **[2025.09]** Integrated backdoor detection and evaluation scripts for *AudioJailBench*.  

---

## 📚 Research Collections  

### 🧾 Surveys & Overviews  
| Year | Title | Venue | Keywords |
|------|--------|--------|----------|
| 2025 | *A Survey on Trustworthy Audio-LLMs: Capabilities and Threats* | KDD (under review) | Survey, Trustworthiness, Audio LLMs |
| 2024 | *Safety and Alignment in Speech-Driven LLMs* | arXiv | Safety, Alignment |
| 2024 | *Audio Deepfake Forensics in the Era of Generative AI* | ACM TOMM | Deepfake, Detection, Ethics |

---

### ⚔️ Attacks & Risks  
| Year | Title | Venue | Focus |
|------|--------|--------|-------|
| 2025 | **Hidden in the Noise (HIN): Audio Backdoor Attacks on Audio-LLMs** | AAAI (under review) | Backdoor, Trigger, Poisoning |
| 2024 | **AudioJailBench: Jailbreak Attacks on Speech-Driven LLMs** | arXiv | Jailbreak, Prompt Injection |
| 2024 | *Adversarial Whispering: Covert Speech Prompts for Multimodal LLMs* | arXiv | Adversarial Attack, Audio Prompt |
| 2023 | *Listen to My Voice: Attacking End-to-End ASR via Adversarial Speech* | IEEE S&P | Adversarial ASR, Security |

---

### 🛡️ Defense & Safety Alignment  
| Year | Title | Venue | Strategy |
|------|--------|--------|-----------|
| 2025 | **Fine-Mixing: Robust LoRA Fine-Tuning for Audio Safety Alignment** | NeurIPS | PEFT Defense, Alignment |
| 2024 | *AudioGuard: Detecting and Defending Audio-LLM Backdoors* | arXiv | Detection, Defense |
| 2024 | *MMDefend: Multimodal Jailbreak Defense Framework* | CVPR | Multimodal Defense |

---

### 📊 Benchmarks & Evaluation  
| Benchmark | Description | Focus |
|------------|--------------|--------|
| **AudioSafe (2025)** | A large-scale benchmark for assessing safety, robustness, and risk of Audio-LLMs under 9 categories. | Safety Evaluation |
| **TALEBench (2024)** | Task-Agnostic LLM Evaluation Benchmark for Long Audio Reasoning. | Comprehension, Long-Context |
| **AudioJailBench (2024)** | Benchmark for audio jailbreak and instruction-following failures. | Prompt Safety |
| **ASVspoof / AV-Deepfake1M++** | Classic audio deepfake and spoofing detection datasets. | Deepfake Detection |

---

### 🎙️ Datasets  
| Dataset | Description | Source |
|----------|--------------|--------|
| **ALLM_long_TTS** | Synthetic long-form audio for dictation, comprehension, and localization tasks. | Custom |
| **LAV-DF** | Multimodal audio-visual deepfake dataset. | Research |
| **VoxCeleb2** | Large-scale speaker corpus for voice identity verification. | Public |
| **FF++ Audio Extended** | Audio-augmented FaceForensics++ for multimodal forgery. | Derived |

---

## 🤝 How to Contribute  

We welcome contributions from researchers and practitioners!  
You can add new papers, datasets, or benchmarks via **Pull Request** or open an **Issue**.

**Entry format example (Markdown table row):**
```markdown
| 2025 | Paper Title | Venue | Keywords |

