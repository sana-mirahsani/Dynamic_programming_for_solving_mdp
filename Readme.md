# 🚀 Dynamic Programming for Solving a Markov Decision Problem

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

## 📌 Description

Welcome to the **Dynamic Programming for Solving a Markov Decision Problem** repository!

This project provides a complete and modular implementation of a **Markov Decision Process (MDP)** framework in Python. It includes tools for:

* Defining MDP environments
* Generating deterministic & stochastic policies
* Simulating trajectories
* Evaluating policies using multiple approaches

👉 Perfect for students and practitioners in:

* Reinforcement Learning
* Machine Learning
* Decision Systems

---

## 📂 Project Structure

```
📁 project/
│
├── mdp_solver.py
├── policy_evaluation.py
├── implementation.py
├── calculating_optimal_policy.py
```

| File                            | Description                                                                      |
| ------------------------------- | -------------------------------------------------------------------------------- |
| `mdp_solver.py`                 | Core MDP framework: states, actions, transitions, rewards, trajectory simulation |
| `policy_evaluation.py`          | Policy evaluation using Linear Algebra, Bellman Iteration, and Monte Carlo       |
| `implementation.py`             | Visualization for Taxi Driver & 21 Dice problems                                 |
| `calculating_optimal_policy.py` | Computes optimal policies and compares methods                                   |

---

## ✨ Features

### 🔹 MDP Framework

* Define:

  * States: `S = {e0, ..., eN}`
  * Actions: `A = {a0, ..., aM}`
  * Transition matrix `P`
  * Reward matrix `R`
  * Discount factor `γ ∈ [0,1]`
* Supports:

  * ✅ Deterministic policies
  * ✅ Stochastic policies
* Trajectory simulation:

  * Policy-based action selection
  * Probabilistic state transitions
  * Discounted reward computation

---

### 🔹 Policy Evaluation Methods

#### 📐 Linear Algebra

* Exact solution using matrix operations
* Solves:

```
(I − γPπ)V = Rπ
```

#### 🔁 Bellman Iteration

* Iterative convergence method
* Controlled via tolerance parameter

#### 🎲 Monte Carlo Estimation

* Simulation-based approach
* Uses multiple trajectories to estimate value

---

### 🔹 Experiments & Applications

* 🚕 Taxi Driver Problem
* 🎲 21 Dice Problem
* 📊 Visualization of results
* 🔍 Comparison of evaluation methods
* 📉 Impact analysis of discount factor (γ)

---

## ⚙️ Requirements

* Python 3.x
* NumPy
* Matplotlib

Install dependencies:

```bash
pip install numpy matplotlib
```

---

## ▶️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/sana-mirahsani/dynamic-programming-mdp.git
cd dynamic-programming-mdp
```

### 2. Run scripts

#### 🔹 MDP Simulation

```bash
python mdp_solver.py
```

#### 🔹 Policy Evaluation

```bash
python policy_evaluation.py
```

#### 🔹 Visualization

```bash
python implementation.py
```

#### 🔹 Optimal Policy

```bash
python calculating_optimal_policy.py
```

---

## 📊 Example Output

* Value function plots
* Policy comparisons
* Convergence curves
* Discount factor impact graphs

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Sana Mirahsani**
📧 [s.mirahsani1998@gmail.com](mailto:s.mirahsani1998@gmail.com)
🔗 LinkedIn: sana-mirahsani
💻 GitHub: sana-mirahsani

---

## ⭐ Support

If you find this project useful:

* ⭐ Star the repo
* 🍴 Fork it
* 🧠 Use it in your ML projects