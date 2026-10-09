# PHY 321 — Computational Classical Mechanics

![Python](https://img.shields.io/badge/python-3.9%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Homework and projects solving mechanics problems numerically in Python.

**Course:** PHY 321 — Classical Mechanics I  
**Term:** Spring 2023  
**Institution:** Michigan State University

## Highlights

- **Honors project:** coupled differential equations integrated with Euler's method and Velocity Verlet, with energy-conservation and step-size analysis.
- **Final project:** motion of a balloon with drag and the nonlinear mathematical pendulum.

## Collaboration

Several homework sets and the final project were completed jointly with **Agrim Gupta**, as noted at the top of each notebook.

## Contents

- [`honors_project_coupled_odes.ipynb`](honors_project_coupled_odes.ipynb) — honors project
- [`final_project.ipynb`](final_project.ipynb) — final project

## Notebook Index

### Homework

- [`hw01.ipynb`](homework/hw01.ipynb) — PHY321: Classical Mechanics 1
- [`hw02.ipynb`](homework/hw02.ipynb) — PHY321: Classical Mechanics 1
- [`hw03.ipynb`](homework/hw03.ipynb) — PHY321: Classical Mechanics 1
- [`hw04.ipynb`](homework/hw04.ipynb) — PHY321: Classical Mechanics 1
- [`hw06.ipynb`](homework/hw06.ipynb) — PHY321: Classical Mechanics 1
- [`hw07.ipynb`](homework/hw07.ipynb) — PHY321: Classical Mechanics 1
- [`hw08.ipynb`](homework/hw08.ipynb) — PHY321: Classical Mechanics 1

## Repository Structure

```text
phy321-classical-mechanics/
├── homework/
│   ├── hw01.ipynb
│   ├── hw02.ipynb
│   ├── hw03.ipynb
│   ├── hw04.ipynb
│   ├── hw06.ipynb
│   ├── hw07.ipynb
│   └── hw08.ipynb
├── final_project.ipynb
├── honors_project_coupled_odes.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## Tech Stack

Python, NumPy, matplotlib

## Getting Started

```bash
git clone https://github.com/siddakmarwaha/phy321-classical-mechanics.git
cd phy321-classical-mechanics
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

> **Academic integrity:** This repository contains my own submitted work for a university course and is shared as a portfolio sample. Assignment prompts and starter code belong to the course instructors. Current students should not copy this work.

## Author

**Siddak Marwaha**

## License

Code in this repository is released under the [MIT License](LICENSE). Course-provided prompts and materials remain the property of their authors.
