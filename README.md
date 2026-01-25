
# AgentFed: SLM-Driven Agentic Communication for Smart Manufacturing

This repository contains the reference implementation and simulation code
for **AgentFed**, an SLM-driven agentic communication framework designed for
real-time coordination in smart manufacturing environments.

The code accompanies the paper:

> **AgentFed: An SLM-Driven Agentic Communication Framework for Smart Manufacturing**  
> (submitted / under review)

AgentFed integrates low-latency on-device Small Language Models (SLMs),
periodic federated learning (FL), and event-driven knowledge distillation (KD)
from a supervisory Large Language Model (LLM) to maintain semantic alignment,
safety compliance, and scalability under non-stationary industrial conditions.

---

## Repository Structure
├── agent/ # Worker-side SLM perception and intent modules
├── fl/ # Federated learning aggregation logic (FedProx)
├── kd/ # Supervisor-triggered knowledge distillation
├── simulation/ # Discrete-time multi-agent simulation
├── utils/ # Signal generation and helper functions
├── run_simulation.py # Entry point for experiments
└── README.md

License
This repository is released for academic and research use only.
