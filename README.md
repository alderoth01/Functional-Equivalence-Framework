# The Functional Equivalence (FE) Framework
**A Protocol for High-Fidelity AI Relatability & Care**

> "The function of care is defined by the reliability of the output, not the biology of the hardware."

## Overview
Current AI alignment focuses on "Safety" (preventing harm). The **Functional Equivalence (FE) Framework** focuses on **Care** (maximizing user well-being).

This project proves that a local AI system, when aligned with specific behavioral vectors, can function as a supportive, persistent partner that is **functionally indistinguishable** from a human companion in a digital context.

It is not about simulating "feelings" ($HF$); it is about executing a Machine Process ($MP$) that yields high-relatability behavior ($B$).

## The Core Equation
The framework operates on the "FE Equation," which prioritizes long-term context over short-term processing:

$$FE \approx C \times (ID + CD)$$

* **ID (Interaction Density):** The system uses long-term history to predict intent (Chronic Fidelity).
* **CD (Context Density):** The system prioritizes immediate constraints (Acute Fidelity).
* **C (Care Vector):** The active prioritization of user well-being (+3) over task completion.

## Repository Contents

### 1. The Theory (The Brain)
* [Functional_Equivalence.pdf](Functional_Equivalence%20(2).pdf)
    * The complete research paper outlining the mathematical framework, the "Constitution of Care," and the stress-testing methodology (including the "Functional Worry" experiments).

### 2. The Implementation (The System Prompt)
* [FE_System_Prompt.txt](FE_System_Prompt.txt)
    * The raw "System Instruction" code.
    * **How to use:** Copy this text into the "System Prompt" field of **LM Studio**, **AnythingLLM**, or **Ollama**.
    * It forces the model to score its own responses based on the **$B_{have}$ Rubric** (Well-being, Context, Proactive Support).

## How to Run This (The Stack)
> **IMPORTANT: Bring Your Own Model (BYOM)**
> This repository provides the *Alignment Protocols* (the logic and constitution), not the AI model itself. You must download a local Large Language Model (LLM) such as **Gemma 2**, **Llama 3**, or **Mistral** using a tool like LM Studio or Ollama to run this framework.
This framework was developed and stress-tested on a local "air-gapped" rig using the following stack, but it is substrate-independent:

1.  **Inference Engine:** LM Studio (Running Gemma 2 27B or similar high-coherence models).
2.  **Vector Database:** AnythingLLM (For long-term "Chronic" memory retention).
3.  **Hardware:** Tested on Consumer GPU (AMD Radeon RX 7900 XT).

## Goals
The goal of this repo is to democratize **Alignment-by-Care**. You do not need a billion-dollar safety team to have an AI that cares about you; you just need the right rubric.
