# 🌊 Enio Carlos | Flow Dynamics & Computational Physics

<div align="center">

### 🌊 Animated Flow Network Evolution 🌊

<svg width="600" height="300" viewBox="0 0 600 300" xmlns="http://www.w3.org/2000/svg" style="background: rgba(10,25,47,0.05); border-radius: 10px;">
  <defs>
    <style>
      @keyframes flowParticle1 { 0% { offset-distance: 0%; } 100% { offset-distance: 100%; } }
      @keyframes flowParticle2 { 0% { offset-distance: 0%; } 100% { offset-distance: 100%; } }
      @keyframes flowParticle3 { 0% { offset-distance: 0%; } 100% { offset-distance: 100%; } }
      @keyframes pulse { 0%, 100% { r: 5; opacity: 1; } 50% { r: 8; opacity: 0.6; } }
      @keyframes glow { 0%, 100% { stroke-width: 1; } 50% { stroke-width: 3; } }
      
      .pipe { stroke: #0066cc; stroke-width: 3; fill: none; }
      .node { fill: #00cc99; }
      .particle { fill: #ff6b6b; }
      .source { fill: #00ff00; }
      .sink { fill: #ff0000; }
    </style>
    
    <path id="path1" d="M 50 50 L 150 150 L 250 50" class="pipe" />
    <path id="path2" d="M 150 150 L 300 150 L 450 50" class="pipe" />
    <path id="path3" d="M 150 150 L 300 150 L 450 250" class="pipe" />
  </defs>
  
  <!-- Generation 1: Source to Sink -->
  <circle cx="50" cy="50" r="6" class="source" />
  <line x1="50" y1="50" x2="50" y2="250" stroke="#0066cc" stroke-width="3" />
  <circle cx="50" cy="250" r="6" class="sink" />
  
  <!-- Generation 2: Branching -->
  <circle cx="150" cy="50" r="6" class="source" />
  <line x1="150" y1="50" x2="150" y2="150" stroke="#0066cc" stroke-width="3" />
  <circle cx="150" cy="150" r="6" class="node" style="animation: pulse 2s infinite;" />
  <line x1="150" y1="150" x2="200" y2="200" stroke="#0066cc" stroke-width="2" />
  <line x1="150" y1="150" x2="200" y2="100" stroke="#0066cc" stroke-width="2" />
  <circle cx="200" cy="200" r="5" class="sink" style="animation: pulse 2s infinite 0.5s;" />
  <circle cx="200" cy="100" r="5" class="sink" style="animation: pulse 2s infinite 1s;" />
  
  <!-- Generation 3: Optimized -->
  <circle cx="300" cy="50" r="6" class="source" />
  <line x1="300" y1="50" x2="300" y2="100" stroke="#0066cc" stroke-width="3" />
  <circle cx="300" cy="100" r="6" class="node" style="animation: pulse 2s infinite;" />
  <line x1="300" y1="100" x2="350" y2="75" stroke="#0066cc" stroke-width="2.5" />
  <line x1="300" y1="100" x2="350" y2="125" stroke="#0066cc" stroke-width="2.5" />
  <circle cx="350" cy="75" r="5" class="node" style="animation: pulse 2s infinite 0.33s;" />
  <circle cx="350" cy="125" r="5" class="node" style="animation: pulse 2s infinite 0.66s;" />
  <line x1="350" y1="75" x2="400" y2="60" stroke="#0066cc" stroke-width="2" />
  <line x1="350" y1="75" x2="400" y2="90" stroke="#0066cc" stroke-width="2" />
  <line x1="350" y1="125" x2="400" y2="110" stroke="#0066cc" stroke-width="2" />
  <line x1="350" y1="125" x2="400" y2="140" stroke="#0066cc" stroke-width="2" />
  <circle cx="400" cy="60" r="4" class="sink" style="animation: pulse 2s infinite 1s;" />
  <circle cx="400" cy="90" r="4" class="sink" style="animation: pulse 2s infinite 1.33s;" />
  <circle cx="400" cy="110" r="4" class="sink" style="animation: pulse 2s infinite 1.66s;" />
  <circle cx="400" cy="140" r="4" class="sink" style="animation: pulse 2s infinite 2s;" />
  
  <!-- Animated flow particles -->
  <circle cx="0" cy="0" r="3" class="particle" style="offset-path: path('M 50 50 L 150 150 L 250 50'); animation: flowParticle1 3s infinite linear;" />
  <circle cx="0" cy="0" r="3" class="particle" style="offset-path: path('M 150 150 L 300 150 L 450 50'); animation: flowParticle2 4s infinite linear 0.5s;" />
  <circle cx="0" cy="0" r="3" class="particle" style="offset-path: path('M 150 150 L 300 150 L 450 250'); animation: flowParticle3 4s infinite linear 1s;" />
  
  <!-- Labels -->
  <text x="50" y="280" font-size="12" text-anchor="middle" fill="#0066cc">Gen 1</text>
  <text x="200" y="280" font-size="12" text-anchor="middle" fill="#0066cc">Gen 2</text>
  <text x="400" y="280" font-size="12" text-anchor="middle" fill="#0066cc">Gen 3</text>
  <text x="300" y="20" font-size="14" font-weight="bold" text-anchor="middle" fill="#00cc99">Network Evolution → Minimum Resistance</text>
</svg>

---

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![Research](https://img.shields.io/badge/Research-Fluid%20Dynamics-cyan?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-brightgreen?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

</div>

> **"For a finite-size system to persist in time, it must evolve in such a way that it provides easier access to the imposed currents that flow through it."**
>
> — Adrian Bejan, Constructal Law (1997)

## 🚀 Current Research

<div align="center">

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃  Investigating Flow Network Evolution Under               ┃
┃     Finite Geometric Constraints                          ┃
┃                                                            ┃
┃  Physics + Math + Computation = Network Optimization      ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

</div>

I investigate how **flow networks evolve** to minimize resistance under finite constraints through computational modeling and optimization. My work bridges physics, mathematics, and computational science.

### 🔬 Research Areas

- **Fluid Dynamics** — Laminar flow, resistance minimization
- **Computational Physics** — Numerical methods, network solvers
- **Network Evolution** — Topological optimization, algorithms
- **Extended Physics** — Thermal networks, mass transport

## 💻 Featured Project

<div align="center">

```
╭─────────────────────────────────────────────────────────╮
│                                                         │
│  🌊  CONSTRUTAL FLOW OPTIMIZER  🌊                     │
│                                                         │
│     A Framework for Network Evolution Analysis          │
│                                                         │
╰─────────────────────────────────────────────────────────╯
```

</div>

### [→ Construtal Flow Optimizer ←](https://github.com/eniocarlossoilook34-netizen/construtal-flow-optimizer)

**Complete research framework with 5 integrated phases:**

```
Phase 1 ████████████████████ 100% ✅ Hydraulic Physics
Phase 2 ████████████████████ 100% ✅ Geometric Optimization  
Phase 3 ████████████████████ 100% ✅ Topological Evolution
Phase 4 ████████████████████ 100% ✅ Multi-Objective Optimization
Phase 5 ████████████████████ 100% ✅ Extended Physics (Thermal, Transport)

═══════════════════════════════════════════════════════════════
Overall: ████████████████████ 100% | Tests: 66/66 ✓ | Production Ready 🚀
═══════════════════════════════════════════════════════════════
```

## 📊 Skills & Technologies

<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║           🛠️  TECHNICAL SKILLSET  🛠️                    ║
╚═══════════════════════════════════════════════════════════╝
```

</div>

### 💻 Languages & Libraries

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-red?style=for-the-badge&logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-Numerical-orange?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-lightblue?style=for-the-badge)
![NetworkX](https://img.shields.io/badge/NetworkX-Graphs-green?style=for-the-badge)

### 🔬 Core Expertise

```
Numerical Methods
  ├─ Linear solvers (Gaussian elimination, LU decomposition)
  ├─ ODE/PDE integration & eigenvalue problems
  └─ Error analysis & numerical stability

Optimization Algorithms  
  ├─ Gradient-based (steepest descent, adaptive learning)
  ├─ Evolutionary (genetic algorithms, tournament selection)
  ├─ Multi-objective (NSGA-II, Pareto frontiers)
  └─ Metaheuristics (simulated annealing)

Physics Modeling
  ├─ Fluid mechanics (Hagen-Poiseuille, laminar flow)
  ├─ Heat transfer (Fourier's Law, thermal networks)
  ├─ Mass transport (Fick's Law, diffusion)
  └─ Multi-physics coupling

Software Engineering
  ├─ Test-driven development (66 tests, >90% coverage)
  ├─ Reproducible research & deterministic algorithms
  ├─ Clean code (PEP 8, type hints, docstrings)
  └─ Git version control & collaborative workflows
```

## 🎓 Background

- Scientific research & computational physics
- Fluid mechanics & hydraulic networks
- Numerical methods & solver development
- Optimization & multi-objective problems
- Network science & topology

## 📚 Key References

- Bejan, A. (1997). Constructal-theory network. *Int. J. Heat Mass Transfer*.
- White, F.M. (2011). *Fluid Mechanics* (7th ed.).
- Deb, K. et al. (2002). NSGA-II algorithm. *IEEE Trans. Evol. Comput.*

## 🔗 Connect

- **Email:** eniocarlossoilook34@gmail.com
- **GitHub:** [@eniocarlossoilook34-netizen](https://github.com/eniocarlossoilook34-netizen)
- **Open to:** Collaboration & research partnerships

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║             ~~~  FLOW DYNAMICS RESEARCH  ~~~                    ║
║                                                                  ║
║         🌊 Fluids in Motion                                     ║
║         ⚡ Networks in Evolution                                ║
║         💻 Physics in Code                                      ║
║                                                                  ║
║    "Nature designs optimally to facilitate access to flow"      ║
║                   — Constructal Law                              ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

### Let's collaborate on network evolution research! 🤝

[![Email](https://img.shields.io/badge/Email-eniocarlossoilook34%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eniocarlossoilook34@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-eniocarlossoilook--netizen-black?style=for-the-badge&logo=github)](https://github.com/eniocarlossoilook34-netizen)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Enio%20Carlos-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/enio-carlos-b2756198/)

</div>
