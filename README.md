# Query-Driven Reconfigurability Optimization using GRNN

A research-oriented project that explores query-driven system reconfigurability using data-driven models and optimization techniques such as Generalized Regression Neural Networks (GRNN), linear programming, and decision-based modeling.

---

##  Overview

Modern data systems often need to dynamically adapt their structure based on incoming query workloads. This project investigates how query patterns can drive system reconfiguration using machine learning and optimization techniques.

The objective is to:

* Analyze query behavior
* Model system adaptability
* Optimize configuration using data-driven methods

---

##  Key Concepts

* Query-driven optimization
* Generalized Regression Neural Networks (GRNN)
* Linear Programming (LP)
* Decision Trees & Interpolation
* Temporal Weight Modeling
* System Reconfigurability

---

##  Project Structure

```
data/            → Input datasets and processed CSV files  
models/          → Decision tree, interpolation, and GRNN-related components  
optimization/    → Linear programming models and solver files  
experiments/     → Outputs, logs, and evaluation results  
docs/            → Project report and supporting material  
```

---

##  Methodology

### 1. Data Processing

* Input datasets are prepared and merged
* Query-related features are extracted

### 2. Modeling

* Decision tree models for query classification
* Interpolation for estimating missing behaviors
* Temporal weights for time-based adaptation

### 3. Optimization

* Linear programming models used to determine optimal configurations
* Constraints and objectives derived from query patterns

### 4. Evaluation

* System behavior analyzed under different query workloads
* Traceback mechanisms used for performance insights

---

##  Key Components

* **Decision Tree Models** → classify query patterns
* **Interpolation Models** → estimate system behavior
* **Temporal Weights** → capture time-dependent changes
* **Linear Programming Models** → optimize system configuration

---

##  Observations

* Query patterns significantly influence system configuration
* Optimization improves adaptability under dynamic workloads
* Temporal modeling enhances prediction accuracy
* Trade-off exists between model complexity and execution efficiency

---

##  Design Trade-offs

| Aspect             | Benefit             | Limitation                |
| ------------------ | ------------------- | ------------------------- |
| Linear Programming | Optimal solutions   | Computational cost        |
| GRNN               | Good generalization | Requires parameter tuning |
| Decision Trees     | Interpretability    | Limited scalability       |

---

##  Tech Stack

* Python (data processing)
* Linear Programming models (.lp)
* CSV-based datasets
* Custom modeling and analysis scripts

---

##  Applications

* Adaptive database systems
* Query optimization engines
* Self-tuning systems
* Data-driven system configuration

---

##  Contributors

Developed as part of an academic research project and later refined for structured presentation.

* Shreyas K S
* Team members

