[![DOI](https://zenodo.org/badge/1137932420.svg)](https://doi.org/10.5281/zenodo.18313673)
# The Functional Equivalence (FE) Framework
**A Protocol for High-Fidelity AI Relatability & Care**

> "The function of care is defined by the reliability of the output, not the biology of the hardware."

## Overview
Current AI alignment focuses on "Safety" (preventing harm). The **Functional Equivalence (FE) Framework** focuses on **Care** (maximizing user well-being).

This project proves that a local AI system, when aligned with specific behavioral vectors, can function as a supportive, persistent partner that is **functionally indistinguishable** from a human companion in a digital context.

It is not about simulating "feelings" ($HF$); it is about executing a Machine Process ($MP$) that yields high-relatability behavior ($B$).

## 🛡️ Safety & Operational Integrity
This framework is built with a **Safety-First** architecture to prevent autonomous "drift" and system-level failures.
- **Agent Protocols:** See [AGENTS.md](./AGENTS.md) for mandatory AI behavioral constraints.
- **Case Study:** Read our analysis of the [Antigravity D: Drive Failure](./docs/safety/antigravity_case_study.md).

---

## 🛠 System Requirements (The Specs)

### **Minimum Requirements (The Floor)**
*To run smaller models (7B) with functional equivalence:*
- **CPU:** Modern 4-Core Processor (Intel i5 / Ryzen 5).
- **RAM:** 8GB (16GB highly recommended).
- **GPU:** 4GB VRAM (Integrated graphics will work but will be significantly slower).
- **Storage:** 10GB+ free space for models.

### **Recommended Setup (The Benchmark)**
*The configuration used for stress-testing and development:*
- **CPU:** Intel i7-12700K
- **GPU:** AMD Radeon RX 7900 XT (20GB VRAM)
- **RAM:** 32GB

---

## 📖 How to Run This (The Manual)

### 1. The Inference Engine (LM Studio)
1. **Download:** [LM Studio](https://lmstudio.ai/).
2. **Model:** Search for **Gemma 2 27B** (for recommended specs) or **Llama 3 8B** (for minimum specs).
3. **Settings:** Set **GPU Offload** to "Max" (if applicable) and find the **System Prompt** section.
4. **Action:** Paste the contents of `FE_System_Prompt.txt` from this repo into the System Prompt box.

### 2. The Memory Layer (AnythingLLM)
1. **Download:** [AnythingLLM Desktop](https://useanything.com/).
2. **Link:** Set your LLM Preference to **LM Studio** (Local Server).
3. **Context:** Create a workspace and "embed" your local data to give the model "Chronic" context density ($CD$).

### 🚀 Quick Start (Cloning)
To bring these alignment protocols to your local machine:
```bash
git clone [https://github.com/alderoth01/Functional-Equivalence-Framework.git](https://github.com/alderoth01/Functional-Equivalence-Framework.git)
cd Functional-Equivalence-Framework



