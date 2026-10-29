# phys-intersections

A computational workbench exploring physical dynamics across disciplinary boundaries—primarily at the intersections of **physics**, **neuroscience**, **chemistry**, and **geology**. 

This repository serves as an independent academic lab notebook and codebase for mathematical modeling, dynamical systems simulations, and numerical experiments.

---

## Repository Structure

The project is structured as a modular monorepo. Shared numerical engines and utility scripts live in `core/`, while domain-specific models reside in their respective directories.

```text
phys-intersections/
├── core/                     # Shared numerical solvers & visualization utilities
│   ├── integrators/          # ODE/PDE solvers (Euler, Runge-Kutta, Symplectic)
│   ├── stats/                # Non-equilibrium statistical mechanics, stochastic noise
│   └── plotting/             # Phase portraits, vector fields, and aesthetic presets
│
├── neurophysics/             # Physics × Neuroscience
│   ├── hodgkin_huxley/       # Conductance-based membrane dynamics & action potentials
│   ├── cable_theory/         # Electrotonic passive spread along dendrites/axons
│   └── neural_fields/        # Continuum neural field models & traveling cortical waves
│
├── chemical_physics/         # Physics × Chemistry
│   ├── reaction_diffusion/   # Turing pattern formation, Morphogenesis, Gray-Scott
│   ├── molecular_dynamics/   # Particle ensemble dynamics, Lennard-Jones potentials
│   └── kinetics/             # Non-linear rate laws, chemical oscillators (e.g., BZ reaction)
│
├── geophysics/               # Physics × Geology & Earth Systems
│   ├── heat_conduction/      # 1D/2D thermal diffusion, lithospheric cooling
│   ├── porous_flow/          # Darcy flow, fluid transport through rock matrices
│   └── convection/           # Rayleigh-Bénard convection & mantle transport
│
└── docs/                     # Derivations, notes, and background references
