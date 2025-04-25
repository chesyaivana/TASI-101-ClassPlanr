# 🧠📅 Large Language Model-Enhanced Meta-Heuristic Multi-Criteria for Dynamic University Course Timetabling

## 📘 Project Description

This research focuses on solving the **Dynamic University Course Timetabling Problem (UCTP)**. Efficient scheduling in such complex systems requires balancing multiple conflicting objectives while considering both *hard* and *soft* constraints. This project integrates the multi-objective metaheuristic algorithm, **Non-Dominated Sorting Genetic Algorithm III (NSGA-III)**, with **Large Language Models (LLMs)** such as GPT-4. NSGA-III is used to explore Pareto-optimal solutions that allow well-balanced trade-offs between constraints, while LLMs enhance the framework by refining constraints, predicting user preferences, and generating more dynamic and contextual scheduling rules.

Experimental results show that the combination of NSGA-III with GPT-4 significantly outperforms other methods, producing more optimal solutions in terms of both efficiency and diversity.

---

## ⚙️ Key Features

- Solves the **Dynamic University Course Timetabling Problem (UCTP)**.
- Integrates NSGA-III metaheuristic with Large Language Models (LLMs) like GPT-4
- Handles multi-objective optimization considering *hard* and *soft* constraints 
- Leverages LLMs to dynamically refine constraints and generate contextual rules 
- Produces Pareto-optimal scheduling solutions 

---

## 🧪 Methodology

The main approach is the integration of **NSGA-III** with **LLM (GPT-4)** 

- **NSGA-III** is used for multi-objective optimization, aiming for Pareto-optimal solutions by balancing various goals (e.g., minimizing conflicts, maximizing preferences) 
- **LLM (GPT-4):**
  - Understands and refines constraints based on natural language input or scheduling data.
  - Predicts user preferences (lecturers/students).
  - Generates contextual and dynamic scheduling rules.
  - Automatically formulates objective functions for NSGA-III based on user preferences 
- This hybrid approach is compared with standalone NSGA-III and MOSA+GPT-4o

---

## 🧰 Technologies Used

- **Programming Language:** Python 
- **Main Libraries:**
  - `numpy` 
  - `pandas` 
  - `deap` (for genetic algorithms/NSGA-III) 
  - `matplotlib` (for visualization) 
  - `copy`, `itertools`, `math`, `multiprocessing`, `random`, `time`, `xml`, `collections`, `pickle`, `tabulate`
- **LLM Models:** GPT-4o , Gemini 2.0 , and DeepSeek V3 
- **APIs:** OpenAI API 
---

## 🗃️ Datasets

- **Institut Teknologi Del** dataset 
- **International Timetabling Competition 2019 (ITC 2019)** dataset 

---

## 📊 Results Summary

- The **NSGA-III + GPT-4o** combination consistently outperforms:
  - **NSGA-III alone**
  - **NSGA-III + Gemini 2.0**
  - **NSGA-III + DeepSeek V3**
  - **MOSA + GPT-4o**
- Key metrics:
  - **Higher Hypervolume (HV)** → better solution spread 
  - **Lower Inverted Generational Distance (IGD)** → closer to the optimal front 
  - **Significantly fewer conflicts** (lecturer, room, and course conflicts) 

---

## 📈 Evaluation Metrics

- **Hypervolume (HV)**
- **Inverted Generational Distance (IGD)**
- **Conflict Count per Generation**
- **Execution Time**

---

## 👨‍💻 Authors

- **Samuel Siagian (12S21042)**
- **Chesya Ivana J. M. Sitorus (12S21053)**
- **Tio Manalu (12S21059)**

---

## 📂 Folder Structure

```plaintext
.
├── data/              # Dataset and preprocessing
├── optimization/      # NSGA-III and MOSA algorithms
├── llm_integration/   # Prompt templates and LLM interaction
├── evaluation/        # Evaluation scripts and metrics
├── models/            # Saved solutions/models
├── results/           # Output schedules and visual results
└── README.md

