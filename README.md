<div align="center">

```
██████╗  ██████╗  ██████╗ ██╗   ██╗███████╗
██╔══██╗██╔═══██╗██╔════╝ ██║   ██║██╔════╝
██████╔╝██║   ██║██║  ███╗██║   ██║█████╗  
██╔══██╗██║   ██║██║   ██║██║   ██║██╔══╝  
██║  ██║╚██████╔╝╚██████╔╝╚██████╔╝███████╗
╚═╝  ╚═╝ ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝
                                             
 █████╗  ██████╗ █████╗ ██████╗ ███████╗███╗   ███╗██╗   ██╗
██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔════╝████╗ ████║╚██╗ ██╔╝
███████║██║     ███████║██║  ██║█████╗  ██╔████╔██║ ╚████╔╝ 
██╔══██║██║     ██╔══██║██║  ██║██╔══╝  ██║╚██╔╝██║  ╚██╔╝  
██║  ██║╚██████╗██║  ██║██████╔╝███████╗██║ ╚═╝ ██║   ██║   
╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝     ╚═╝   ╚═╝  
```

### *"Knowledge is a weapon. Curated, focused, and free — learn it. Own it. Use it to shape the future of AI."*

---

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Phase](https://img.shields.io/badge/course%2001-physics%20→%20AI-red?style=flat-square)
![Resources](https://img.shields.io/badge/resources-free%20first-green?style=flat-square)

</div>

---

## What is Rogue Academy?

Rogue Academy is a self-directed AI learning initiative — built in the open, from the ground up.

It started as a personal project: a way to teach myself the foundational knowledge that actually underlies AI and deep learning — not surface-level tutorials, not API wrappers, but the real mathematical and physical intuitions that make these systems make sense.

The first course takes an unconventional path in. Rather than starting with ML textbooks, it starts with **physics** — because the ideas powering modern AI didn't appear from nowhere. Entropy, equilibrium, energy landscapes, phase transitions, dynamical systems — these were formalized in physics long before they were repurposed for machine learning. Understanding them in their original context builds a different kind of intuition: one that transfers, generalizes, and holds up when the frameworks change.

Eventually, Rogue Academy will grow into a platform that helps others explore specialized AI topics and contribute meaningfully to the field.

---

## Current Status

> 🔨 **Development Phase** — Course 01 is actively being studied.

| Phase | Status |
|---|---|
| Define learning approach | ✅ Done |
| Curate Course 01 resources | ✅ Done |
| Build Course 01 structure | ✅ Done |
| Complete Course 01 | 🔄 Active |
| Publish Course 01 | ⏳ Coming soon |
| Open to contributors | 🔮 Future |
| Expand to new AI topics | 🔮 Future |

---

## The Philosophy

Most AI learning content suffers from one of two problems: it's either too shallow to be useful, or too scattered to follow. Rogue Academy exists to fix both.

**① Curated over comprehensive**
Not every resource deserves your time. The ones here have been selected because they build real understanding — not just familiarity with buzzwords.

**② Free first**
The core curriculum is built entirely on free, publicly available materials. Where paid resources are listed, they are clearly marked as optional and reserved for those seeking mastery.

**③ Depth over breadth**
It's better to understand one thing well than to skim ten things poorly. Each course focuses on building genuine, transferable knowledge.

---

## Course 01 — Physics as a Lens for AI *(In Development)*

Most people learning AI start with gradient descent and work backwards. This course does the opposite.

It uses **physics** as the entry point — rebuilding the mathematical and systems-thinking toolkit through mechanics, thermodynamics, information theory, and dynamical systems. The goal isn't to become a physicist. The goal is to arrive at ML and deep learning already holding the right intuitions: what it means for a system to reach equilibrium, why entropy measures uncertainty, how energy landscapes govern optimization, what it means for a system to be stable or chaotic.

These aren't analogies. The mathematics is often literally the same. Physics came first.

**Standard workflow for every lecture:**
> `① Watch lecture → ② Read the corresponding book chapter → ③ Solve the exercises`

---

### Module 1 · Statistical Mechanics

📖 **Book:** *An Introduction to Thermal Physics* — Daniel V. Schroeder
🎬 **Lectures:** [Theoretical Minimum — Statistical Mechanics (Susskind)](https://theoreticalminimum.com/courses/statistical-mechanics/2013/spring)

**Why this module:**
Statistical mechanics is where ML borrows most heavily from physics. The Boltzmann distribution is the mathematical ancestor of softmax. Partition functions appear throughout probabilistic modelling. Free energy minimization is what variational inference is actually doing. The entropy studied here is the same entropy that defines information content, uncertainty in predictions, and regularization in neural networks. After this module, gradient descent starts to look like a system seeking its lowest energy state — because formally, it is.

| Lecture | Topic | Reading |
|---|---|---|
| Lecture 1 | [Probability & Entropy](https://theoreticalminimum.com/courses/statistical-mechanics/2013/spring/lecture-1) | Chapters 1–2 |
| Lecture 3 | [Boltzmann Distribution](https://theoreticalminimum.com/courses/statistical-mechanics/2013/spring/lecture-3) | Chapter 6 |
| Lecture 4 | [Boltzmann Distribution & Partition Functions](https://theoreticalminimum.com/courses/statistical-mechanics/2013/spring/lecture-4) | Chapters 6–7 |
| Lecture 5 | [Helmholtz Free Energy & Ideal Gas](https://theoreticalminimum.com/courses/statistical-mechanics/2013/spring/lecture-5) | Chapter 5 + parts of Ch. 3 |

> **🔗 AI Connections:** Softmax & temperature scaling · Boltzmann machines · Energy-based models · Free energy principle · Entropy regularization · Equilibrium as convergence

---

### Module 2 · Information Theory

📖 **Book:** *Information Theory, Inference, and Learning Algorithms* — David J. C. MacKay *(free online)*
🎬 [Lecture Playlist](https://www.youtube.com/playlist?list=PLruBu5BI5n4aFpG32iMbdWoRVAA-Vcso6)

**Why this module:**
This is where physics and ML meet most explicitly. Shannon entropy is a direct extension of Boltzmann entropy — same formula, different domain. Cross-entropy loss, used to train almost every classification model in existence, is a direct consequence of information-theoretic reasoning. Bayesian inference, variational methods, KL divergence, the mathematics behind VAEs and diffusion models — all of it lives here. MacKay's book is one of the few that treats neural networks as a natural consequence of probabilistic reasoning, not a separate subject bolted on at the end.

| Lecture | Topic | Reading |
|---|---|---|
| Lecture 1 | Introduction to Information Theory | Chapter 1 |
| Lecture 2 | Entropy & Data Compression (I) | Chapter 2 |
| Lecture 3 | Entropy & Data Compression (II) | Chapter 5 |
| Lecture 6 | Noisy Channel Coding | Chapters 8–9 |
| Lectures 9–10 | Bayesian Inference | Chapters 3–4 |
| Lecture 14 | Variational Methods | Chapter 33 |
| Lectures 15–16 | Neural Networks & Boltzmann Machines | Chapters 39–41 |

> **🔗 AI Connections:** Cross-entropy loss · KL divergence · Mutual information · Maximum likelihood estimation · Bayesian neural networks · VAEs · ELBO · The math behind diffusion models

---

### Module 3 · Nonlinear Dynamics & Chaos

📖 **Book:** *Nonlinear Dynamics and Chaos* — Steven H. Strogatz
🎬 [Course Playlist](https://www.youtube.com/playlist?list=PLbN57C5Zdl6j_qJA-pARJnKsmROzPnO9V)

**Why this module:**
Neural networks are nonlinear dynamical systems. Training is a trajectory through a high-dimensional loss landscape. Fixed points, attractors, bifurcations, and stability — these aren't metaphors for what happens during training, they describe it precisely. Recurrent networks are literally dynamical systems evolving over time. Understanding when nonlinear systems stabilize, oscillate, or go chaotic builds the intuition needed to reason about why networks fail to converge, why they escape saddle points, and what a good solution actually means geometrically.

| Topic | Reading | Exercises |
|---|---|---|
| One-Dimensional Systems | Chapter 2 | 2.1–2.12 |
| Two-Dimensional Linear Systems | Chapter 3 | 3.1–3.10 |
| Nonlinear Systems — Fixed Points & Stability | Chapter 4 | 4.1–4.10 |
| Limit Cycles | Chapter 5 | 5.1–5.6 |
| Bifurcations | Chapter 7 | 7.1–7.8 |
| Chaos & Lorenz Equations | Chapter 8 | 8.1–8.10 |

> **🔗 AI Connections:** Loss landscape geometry · Saddle points & escape dynamics · Convergence & divergence · RNNs as dynamical systems · Hopfield networks as associative memory · Gradient flow

---

### Module 4 · Forecasting — Applied Time Series

📖 **Book:** *Forecasting: Principles & Practice (Python edition)* — Hyndman & Athanasopoulos *(free online)*
🎬 [Lecture Playlist](https://www.youtube.com/playlist?list=PLyCNZ_xXGzpm7W9jLqbIyBAiSO5jDwJeE)

**Why this module:**
This is where physical systems thinking gets applied computationally. Time series are the observable outputs of dynamical systems — everything from climate to financial markets to neural signals. Decomposition, smoothing, ARIMA, and state-space models are all grounded in the same reasoning used to analyse physical processes evolving over time. The transition to neural forecasting (N-BEATS, TFT) then shows directly how deep learning enters as a generalization of classical methods — not a replacement for understanding them, but an extension of the same underlying logic.

| Topic | Reading | Practice |
|---|---|---|
| Intro & Visualization | Chapter 2 | pandas time series + plotting |
| Decomposition | Chapter 3 | STL and seasonal_decompose |
| Exponential Smoothing (ETS) | Chapter 4 | statsmodels ExponentialSmoothing |
| ARIMA | Chapter 5 | ARIMA / auto_arima |
| Dynamic Regression | Chapter 6 | SARIMAX with exogenous variables |
| Neural Forecasting | Chapters 7–8 | N-BEATS / TFT |

> **🔗 AI Connections:** State-space models · Sequential prediction · Physical systems as time series · How classical methods inform neural architectures · Temporal structure in data

---

### Module 5 · Probabilistic Graphical Models

📖 **Book:** *Probabilistic Graphical Models: Principles and Techniques* — Koller & Friedman
🎬 [Lecture Playlist](https://www.youtube.com/playlist?list=PLBAGcD3siRDjiQ5VZQ8t0C7jkHQ8fhuq8)

**Why this module:**
PGMs are the formal language for representing uncertainty and dependence between variables — the same concepts that appear in physical systems as conditional probabilities and joint distributions over states. Bayesian networks, Markov networks, and the EM algorithm connect directly to how modern generative models learn latent structure from data. Variational inference, which closes this module, is the bridge between the free energy ideas in Module 1 and the practical machinery inside VAEs, diffusion models, and modern probabilistic AI.

| Topic | Reading |
|---|---|
| Bayesian Networks | Chapters 2–3 |
| Dynamic Bayesian Networks | Chapter 9 |
| Markov Networks & CRFs | Chapters 4–5, 7 |
| Inference | Chapters 6, 8 |
| MAP Inference | Chapter 10 |
| Learning & EM | Chapters 12–13 |
| Variational Inference | Chapter 16 |

> **🔗 AI Connections:** Latent variable models · Generative models · EM algorithm · Variational autoencoders · Belief propagation · Structured prediction · The probabilistic backbone of modern AI

---

### Module 6 · Hamiltonian Mechanics

📖 **Book:** *Classical Mechanics* — John R. Taylor
🎬 Lectures: [1](https://theoreticalminimum.com/courses/classical-mechanics/2011/fall/lecture-1) · [4](https://theoreticalminimum.com/courses/classical-mechanics/2011/fall/lecture-4) · [7](https://theoreticalminimum.com/courses/classical-mechanics/2011/fall/lecture-7)

**Why this module:**
The Hamiltonian formulation of mechanics — energy as the central object, phase space as the arena — is the conceptual ancestor of several ideas now appearing at the frontier of deep learning. Hamiltonian Monte Carlo is a direct application used in Bayesian inference. Hamiltonian Neural Networks learn to respect conservation laws in physical simulations. The Lagrangian framework, built on the principle of least action, mirrors how optimization finds paths of minimal cost through parameter space. This module sharpens the energy-based systems thinking started in Module 1 and closes the loop — the physicist's toolkit is now the ML practitioner's toolkit.

| Topic | Reading |
|---|---|
| State Space | Chapters 1–2 |
| Lagrangian Mechanics | Chapter 7 |
| Hamiltonian Mechanics | Chapters 8–9 |

> **🔗 AI Connections:** Hamiltonian Monte Carlo (HMC) · Hamiltonian Neural Networks · Symplectic integrators · Energy-conserving architectures · Optimization as a variational problem · Least action & least cost

---

## The Thread Running Through All Six Modules

These modules are not independent topics. They are six angles on the same underlying question: *how do complex systems organize, evolve, and settle into structure?*

```
  Statistical Mechanics  ──▶  Energy, entropy, equilibrium
          │
          ▼
  Information Theory     ──▶  Entropy as uncertainty, inference under noise
          │
          ▼
  Nonlinear Dynamics     ──▶  How systems move, stabilize, and break down
          │
          ▼
  Forecasting            ──▶  Physical intuition applied to real data
          │
          ▼
  Graphical Models       ──▶  Probabilistic structure and latent variables
          │
          ▼
  Hamiltonian Mechanics  ──▶  Energy conservation, phase space, optimization geometry
```

By the end, the mathematics of deep learning — loss functions, optimization, latent representations, generative models — should feel less like a disconnected collection of techniques and more like a natural consequence of ideas that were always there, waiting to be recognized.

---

## How Resources Are Chosen

Every resource in the curriculum is evaluated against the same criteria:

- **Does it build real understanding**, or just surface familiarity?
- **Does it make the physics–ML connection explicit**, or treat them as separate subjects?
- **Is it the best version of its kind**, or just well-known?
- **Is it free** (or, if paid, genuinely worth the cost)?

---

## Roadmap

```
[NOW]    Course 01 — Physics as a Lens for AI (6 modules)
          ↓
[NEXT]   Publish Course 01 for public use
          ↓
[THEN]   Course 02 — Specialized AI topic (TBD)
          ↓
[FUTURE] Community contributions + collaborative roadmaps
```

---

## Contributing

Rogue Academy isn't open to contributions yet — it's still being shaped. But that will change.

If you have a resource, idea, or a connection between physics and AI that belongs here, **open an issue** and make the case. The bar is high, but the door isn't closed.

---

## License

MIT — because knowledge should be free to use, share, and build on.

---

<div align="center">

**Rogue Academy** · Built in the open · Started from zero

*The future of AI won't be shaped by those who waited.*

</div>
