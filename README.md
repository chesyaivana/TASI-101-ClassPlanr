# 🧠📅 Dynamic University Course Timetabling using LLM + NSGA-III

A research project that explores the integration of **Large Language Models (LLMs)** with **multi-objective metaheuristics**, specifically **NSGA-III**, to solve the **Dynamic University Course Timetabling Problem (UCTP)**. This hybrid framework combines the optimization power of NSGA-III and the contextual reasoning of LLMs (GPT-4o, Gemini 2.0, DeepSeek V3) to produce efficient, adaptive, and Pareto-optimal schedules.

---

## 📌 Features

- ✅ **NSGA-III** for multi-objective optimization (hard + soft constraints)
- ✅ **LLM integration** to generate prompt-based rules and preferences
- ✅ **Dynamic constraint adaptation** using real-time updates
- ✅ **Pareto-based evaluation** (Hypervolume, IGD, conflicts)
- ✅ **Benchmark comparison** using IT Del and ITC 2019 datasets

---

## 📚 Datasets

- `Institut Teknologi Del` scheduling data
- `International Timetabling Competition (ITC) 2019` dataset

---
## 📊 Evaluation Metrics

- **Hypervolume (HV)**
- **Inverted Generational Distance (IGD)**
- **Conflict Count per Generation**
- **Execution Time**
- **Adaptability Score**

---

## 📂 Folder Structure

```plaintext
.
├── data/              # Dataset and preprocessing
├── optimization/      # NSGA-III and MOSA algorithms
├── llm_integration/   # Prompt templates and LLM execution
├── evaluation/        # Evaluation scripts and metrics
├── models/            # Saved solutions/models
├── results/           # Output schedules and plots
└── README.md

---

## 👨‍💻 Authors

- **Samuel Siagian** (12S21042)  
- **Chesya Ivana J. M. Sitorus** (12S21053)  
- **Tio Manalu** (12S21059)  

*Institut Teknologi Del — Program Studi Sistem Informasi*





