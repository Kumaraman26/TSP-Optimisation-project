
# Solving TSP Using Evolutionary Optimization

This project explores evolutionary optimization techniques for solving the **Travelling Salesman Problem (TSP)**, one of the most well-known NP-hard combinatorial optimization problems.

We implemented and compared two nature-inspired algorithms:

- **Particle Swarm Optimization (PSO)** 🐦 – inspired by the social behavior of birds and fish.
- **Social Group Optimization (SGO)** 👥 – inspired by human group dynamics and leader-based learning.

### 🔑 Key Features
- Implemented in **Python** on **Google Colab**.
- Tested on **TSPLIB datasets** (e.g., `berlin52`).
- Visualization of optimized routes and convergence behavior.
- Modular, reusable code with clear documentation.

### 📊 Results
- On the **Berlin52 dataset**:
  - **PSO Best Distance:** `15609.54`
  - **SGO Best Distance:** `14002.20`
- **Improvement of SGO over PSO:**
  \[
  \frac{15609.54 - 14002.20}{15609.54} \times 100 \approx 10.3\%
  \]

➡️ **SGO outperformed PSO by ~10.3%**, showing better exploration and convergence for TSP.

### 🚀 Future Scope
- Hybrid models (PSO + local search / SGO + 2-opt, 3-opt).
- Real-world logistics mapping with traffic constraints.
- Extension to dynamic TSP with changing inputs.

---

## 🏆 Authors
- Kumar Aman  

Under the guidance of **Dr. Suresh Chandra Satapathy**, KIIT University.
