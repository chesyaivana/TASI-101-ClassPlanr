# 🧠📅 Large Language Model-Enhanced Meta-Heuristic Multi-Criteria for Dynamic University Course Timetabling

## 📘 Project Description

This research focuses on solving the **Dynamic University Course Timetabling Problem (UCTP)** [cite: 40, 51]. Efficient scheduling in such complex systems requires balancing multiple conflicting objectives while considering both *hard* and *soft* constraints [cite: 2, 8]. This project integrates the multi-objective metaheuristic algorithm, **Non-Dominated Sorting Genetic Algorithm III (NSGA-III)**, with **Large Language Models (LLMs)** such as GPT-4 [cite: 3, 9]. NSGA-III is used to explore Pareto-optimal solutions that allow well-balanced trade-offs between constraints [cite: 4, 10], while LLMs enhance the framework by refining constraints, predicting user preferences, and generating more dynamic and contextual scheduling rules [cite: 5, 11].

Experimental results show that the combination of NSGA-III with GPT-4 significantly outperforms other methods, producing more optimal solutions in terms of both efficiency and diversity [cite: 6, 12, 1710, 1763].

---

## ⚙️ Key Features

- Solves the **Dynamic University Course Timetabling Problem (UCTP)**.
- Integrates NSGA-III metaheuristic with Large Language Models (LLMs) like GPT-4.
- Handles multi-objective optimization considering *hard* and *soft* constraints [cite: 2, 8].
- Leverages LLMs to dynamically refine constraints and generate contextual rules [cite: 5, 11].
- Produces Pareto-optimal scheduling solutions [cite: 4, 10].

---

## 🧪 Methodology

The main approach is the integration of **NSGA-III** [cite: 3, 9] with **LLM (GPT-4)** [cite: 3, 9].

- **NSGA-III** is used for multi-objective optimization, aiming for Pareto-optimal solutions by balancing various goals (e.g., minimizing conflicts, maximizing preferences) [cite: 4, 10].
- **LLM (GPT-4):**
  - Understands and refines constraints based on natural language input or scheduling data.
  - Predicts user preferences (lecturers/students).
  - Generates contextual and dynamic scheduling rules.
  - Automatically formulates objective functions for NSGA-III based on user preferences [cite: 1270, 1307].
- This hybrid approach is compared with standalone NSGA-III and MOSA+GPT-4o [cite: 19, 1001, 1710, 1739].

---

## 🧰 Technologies Used

- **Programming Language:** Python [cite: 1498]
- **Main Libraries:**
  - `numpy` [cite: 1504]
  - `pandas` [cite: 1510]
  - `deap` (for genetic algorithms/NSGA-III) [cite: 1509]
  - `matplotlib` (for visualization) [cite: 1502]
  - `copy`, `itertools`, `math`, `multiprocessing`, `random`, `time`, `xml`, `collections`, `pickle`, `tabulate` [cite: 1499–1512]
- **LLM Models:** GPT-4o [cite: 5, 1613], Gemini 2.0 [cite: 1627], and DeepSeek V3 [cite: 1660]
- **APIs:** OpenAI API [cite: 1622]

---

## 🗃️ Datasets

- **Institut Teknologi Del** dataset [cite: 666]
- **International Timetabling Competition 2019 (ITC 2019)** dataset [cite: 666, 671]

---

## 📊 Results Summary

- The **NSGA-III + GPT-4o** combination consistently outperforms:
  - **NSGA-III alone**
  - **NSGA-III + Gemini 2.0**
  - **NSGA-III + DeepSeek V3**
  - **MOSA + GPT-4o** [cite: 6, 12, 1689, 1700, 1710, 1718, 1763]
- Key metrics:
  - **Higher Hypervolume (HV)** → better solution spread [cite: 1690, 1701, 1711]
  - **Lower Inverted Generational Distance (IGD)** → closer to the optimal front [cite: 1714, 1715]
  - **Significantly fewer conflicts** (lecturer, room, and course conflicts) [cite: 1693, 1703, 1713, 1716, 1722, 1770]

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
