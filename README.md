# Development and Benchmarking of Heuristic Solution Methods for the Picker Routing Problem in E-Commerce Warehouses

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Academic Project](https://img.shields.io/badge/Project-Master%2FBachelor%20Thesis-blue.svg)]()

> **Project Status:** Active Research (Thesis Project)  
> **Last Updated:** March 2026

---

## 📌 Project Overview

Reducing unproductive travel times is a critical optimization goal in e-commerce warehouse order picking. While numerous exact and heuristic solution procedures exist, few scale well or apply to a **general problem setting** characterized by arbitrary layout topologies and highly varying demand patterns.

The primary objective of this repository is to:
1. Develop flexible heuristic solution methods for the **General Picker Routing Problem (PRP)**.
2. Provide a modular framework capable of modeling arbitrary e-commerce warehouse layouts.
3. Benchmark the developed heuristics against established baseline methods and standard exact/heuristic benchmarks.

---

## 🎯 Key Features

* **Arbitrary Layout Support:** Accommodates flexible graph representations beyond traditional rectangular block-layout topologies.
* **Heuristic Solvers:** Implementation of custom heuristic and metaheuristic solution procedures designed for general PRP instances.
* **Benchmarking Suite:** Tools to evaluate travel distance/time reduction, algorithmic efficiency, and runtime scalability.
* **Modular Codebase:** Object-oriented design allowing easy integration of new heuristics or layout types.

---

## 🛠 Repository Structure

```text
├── data/               # Instance generators, layout definitions, and test datasets
├── docs/               # Thesis documentation, literature reviews, and figures
├── src/                # Core implementation
│   ├── core/           # Warehouse graphs, routing instances, and data models
│   ├── heuristics/     # Implemented heuristic solution algorithms
│   └── utils/          # Distance metrics, file I/O, and helpers
├── tests/              # Unit tests and validation scripts
├── benchmarks/         # Experiments, runner scripts, and result logs
├── LICENSE             # Open-source license
└── README.md           # Project documentation
