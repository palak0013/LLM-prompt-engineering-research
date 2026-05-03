# 🧠 Prompt Engineering Impact on LLM Reasoning

## 👩‍💻 Author

**Palak Singh**
B.Tech Computer Science Student
AI/ML Enthusiast

---

## 📌 Overview

This research paper investigates how different prompt engineering techniques affect the reasoning capabilities of Large Language Models (LLMs), especially small-scale models.

The study focuses on whether structured prompting can improve multi-step reasoning tasks such as mathematical problem solving.

---

## 🎯 Objectives

* Evaluate effectiveness of prompt engineering techniques
* Analyze reasoning limitations in small-scale LLMs
* Compare performance across different prompting strategies

---

## ⚙️ Methodology

### 🔹 Model Used

* TinyLLaMA-1.1B-Chat (local execution via LM Studio)

### 🔹 Prompting Techniques

* Zero-shot prompting
* Few-shot prompting
* Chain-of-thought (CoT) prompting

### 🔹 Task Categories

* Basic arithmetic
* Arithmetic expressions
* Proportional reasoning
* Speed-distance problems

---

## 📊 Key Findings

* Chain-of-thought prompting provides only marginal improvement
* Few-shot prompting fails to generalize reasoning patterns
* Small-scale models struggle with multi-step reasoning
* Prompt engineering alone cannot overcome model limitations

---

## ⚠️ Observed Errors

* Incorrect arithmetic transformations
* Misapplication of formulas
* Inconsistent intermediate reasoning steps
* Unnecessary floating-point conversions

---

## 🧠 Conclusion

The study demonstrates that reasoning ability in LLMs is strongly dependent on model scale. Prompt engineering improves structure but does not guarantee correctness in smaller models.

---

## 📄 Research Paper

👉 [Read Full Paper](https://github.com/palak0013/LLM-prompt-engineering-research.git)

---

## 🚀 Future Work

* Evaluate larger models (7B, 13B, 70B)
* Apply self-consistency techniques
* Integrate verification-based reasoning
* Expand dataset for broader evaluation

---

## ⭐ Note

This is a **student research project (solo work)** conducted to explore real-world limitations of LLM reasoning.
