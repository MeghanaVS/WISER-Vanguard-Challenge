# Security Policy

## Supported Versions
Memory T4 GPU
Python 3.8 and above.
Modern Qiskit (qiskit >= 1.0.0)

| Version | Supported          |
| ------- | ------------------ |
| >= 3.8   | :white_check_mark: |
| < 3.0   | :x:                |
| >= 1.0.x   | :white_check_mark: |
| < 1.0.x   | :x:                |

## Reporting a Vulnerability

| Memory | Execution Time/Cell 
| ------- | ------------------ |
| RAM/CPU   | 19s + 49m + 62m + 77m |
| T4/GPU   | 9s + 16m + 24m + 32m   |

Each Cell execution time (seconds/minutes): 
------------------------------------------
* Cell 1 - Library Installation and restart time 
* Cell 2 - Core library imports, Synthetic Market Data Generation, Mathematical QUBO and Ising Mapping Engine, Optimization Logic 
* Cell 3 - Hybrid Post-Processing, Main Workflow Execution
* Cell 4 - CO-PILOT Engine runner with another dataset samples

