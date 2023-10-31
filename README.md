# Deep Quantum Reinforcement Learning

This is a repository for applying Deep Model-Based Reinforcement Learning on Quantum Systems. Here we focus on the task of accelerating Transmon Qubit Readout by finding Optimal Pulse Waveforms for fast and high fidelity measurements.

This repository contains files for Readout Simulation, included in the envs folder, and various Reinforcement Learning Algorithms including PPO, RPO, and TRPO, included in the algos folder, all written in Jax.

Github Packages that have been incredibly helpful include:

1. [PureJaxRL](https://github.com/luchris429/purejaxrl) - For CPU and GPU Accelerated Jax-Based Reinforcement Learning Workflows
2. [Diffrax](https://docs.kidger.site/diffrax/) - For Jax-based Differential Equation Solvers, allowing for simulation of the physical quantum systems
3. [Gymnax](https://github.com/RobertTLange/gymnax/tree/main) - As a template for constructing Gymnasium-Style Reinforcement Learning Environments in the Jax Workflow
