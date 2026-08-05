# WISER-Vanguard-Challenge

# Portfolio Optimization Engine: Quantum vs. Classical

A hybrid optimization framework designed to solve complex portfolio allocation problems. This pipeline generates synthetic financial market data, formulates the allocation as a Quadratic Unconstrained Binary Optimization (QUBO) problem, and evaluates performance across both classical brute-force baselines and quantum Approximate Optimization Algorithm (QAOA) solvers with local optimization.

## 🏗️ System Architecture

```mermaid
graph TD
    A["1. Synthetic Market Data"] --> B["2. Mathematical QUBO Engine"]
    B --> C["3. Classical Baseline<br/>(Brute-Force Master Key)"]
    B --> D["4. Quantum QAOA Engine"]
    D --> E["5. Local Refinement"]
    C --> F["6. Portfolio Co-Pilot Report"]
    E --> F
