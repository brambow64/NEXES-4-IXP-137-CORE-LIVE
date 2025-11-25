# Contributing to NEXUS - IXP-137 CORE

First of all: thank you for your interest in contributing to the **IXP-137 CORE**
experimental research project.

This repository is part of an ongoing scientific and exploratory effort.
Contributions are welcome — but only under the conditions described below.


## 📌 1. Experimental Nature of the Project

The IXP-137 CORE is **not** a production system, and **must not** be treated as one.
All contributions, discussions and pull requests must respect the following facts:

- The system is **experimental**.
- Output is **approximate**, **non-operational**, and **not safety-critical**.
- No part of this project may be positioned or implied as an official
  early-warning system for real-world hazards.

By contributing, you acknowledge and agree with the terms of the **IXP-137
Experimental Research License (ERL-1.0)** found in the `LICENSE` file.


## 🧠 2. Types of Contributions Accepted

The following forms of contribution are welcome:

- Bug reports
- Code improvements
- Documentation enhancements
- Algorithmic refinements
- Additional analysis modules (non-safety-critical only)
- Logging and monitoring improvements
- Research insights or theoretical suggestions

The following are **NOT** accepted:

- Claims of predictive accuracy without verifiable data
- Safety-critical modules or suggestions
- Attempts to market, promote or position the software as an official warning tool
- Requests for operational deployment support


## 📝 3. How to Submit a Bug Report

Use GitHub Issues with the following structure:

- **Title:** Short and descriptive  
- **Body:**  
  - What happened  
  - Expected behavior  
  - Steps to reproduce  
  - Logs (if applicable)  
  - System/environment info  
  - Suggested fix (optional)

Please keep reports factual — avoid assumptions about seismic behavior
unless you can demonstrate a reproducible issue in the codebase.


## 🔧 4. Pull Request Guidelines

Before submitting a PR:

- Make sure the code runs without errors  
- Ensure all logging remains stable  
- Avoid introducing new safety-critical implications  
- Keep code style consistent with existing modules  
- Do not introduce dependencies
