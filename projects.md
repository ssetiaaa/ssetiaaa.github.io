---
layout: page
title: "Projects"
---

Here’s a curated list of projects with short write-ups, code, and (when available) reports/figures.  

---

## ⭐ Featured
### Strong Coupling Corrections in Quantum Thermodynamics ⭐
**Hook:** A full, step-by-step re-derivation of the strong-coupling corrections to the second law in quantum thermodynamics, written as a self-contained report with proofs, checks, and clarifications.

**Keywords:** quantum thermodynamics, strong coupling, open quantum systems, relative entropy, free energy, Carnot efficiency  
**Tools:** LaTeX (weekly reports); extensive handwritten derivations (converted into a clean write-up)

**Links**
- 📄 Report (PDF): assets/reports/strong_coupling_corrections_qthermo.pdf

**What I did**
- Reconstructed the operational framework (quenches, switch on/off interaction, equilibration) and derived the work expressions and isothermal-limit result (including why entropy production vanishes as the number of steps grows).
- Derived the *maximum extractable work* formula in the strong-coupling regime and expressed correction terms via **irreversible** and **residual** free-energy penalties.
- Worked through the variational minimizations that determine the optimal “switch-on” and “switch-off” Hamiltonians (stationarity conditions and existence of minima).
- Carried out a perturbative expansion in coupling strength
$g$
, obtaining leading-order corrections and interpreting them in terms of (generalized) covariance of the centered interaction.
- **Critical reading / consistency checks:** identified and documented mismatches/implicit assumptions in the paper + supplementary material (e.g., covariance/Kubo-transform conventions and conditions needed for certain expansions/boundary assumptions).

**Takeaway**
- Strong coupling does *not* give “free” advantages: switching the interaction on/off itself becomes a source of dissipation, and the leading corrections reduce ideal performance.

---

### Competing Contagion on Multiplex Networks
**Hook:** Research-style reports exploring how network structure and initial conditions shape competing spreading dynamics (T vs F) on a two-layer network that mixes **small-world locality** with **scale-free long-range shortcuts**, supported by simulations and statistical analysis over 1000-run batches.

**Keywords:** complex networks, multiplex networks, small-world, Barabási–Albert, contagion dynamics, stochastic simulations, sensitivity to initial conditions  
**Tools:** Python (simulation + plots), LaTeX (weekly reports)

**Links**
- Reports (PDF folder): assets/reports/finite_bath_weekly_reports.pdf  <!-- or a folder link -->
- Code: https://github.com/YOURUSERNAME/REPO_NAME

**What I did**
- Built a **two-layer network model**: a small-world “blue” layer with rewiring probability $p$ and mean degree $k_b$ , plus a preferential-attachment “red” layer with parameter $m_r$ (long-range shortcuts).
- Derived/used analytic expectations for structural properties (degree distribution regimes, clustering dependence on rewiring), then compared with numerically generated networks.
- Implemented a **competing-spread process** (T and F) with tunable rates $\beta_T$, $\beta_F$, tracked time courses, final dominance $\Delta=T-F$, and “win probability” across many random initial seeds.
- Quantified **seed sensitivity**: studied how initial-node degree, clustering, and distance affect outcomes using Pearson/Spearman correlations and conditional win-probability plots.
- Performed parameter sweeps over $(k_b, m_r, p, \beta_T, \beta_F)$ and documented when outcomes are driven mainly by **hub access** vs. rate advantage.

**Result highlight**
- Even when $\beta_T=\beta_F$, outcomes often become extreme (near full dominance) due to structural heterogeneity and seed placement; introducing a small rate advantage shifts the win-probability curve but **initial degree advantage remains a strong predictor**.


---

## Coursework Projects (selected)

### Feature Selection vs. Shapley Values: Concordance in Identifying Marker Genes in Gene Networks (Spring 2025)
**Supervisors:** Dr. Mohammad Reza Rahimi Tabar; Dr. Lalen Haghverdi  
**Collaborators:** Nargess Khorshidi, Amirhossein Movahedi

Built a pipeline to identify cell-type marker genes in PBMC3K single-cell RNA-seq by scoring genes using a Shapley-value–based cluster-specificity metric and benchmarking against standard feature-selection baselines. Mapped top candidates onto STRING protein–protein interaction networks and prioritized markers using network-neighborhood centrality to highlight biologically influential genes.

**Keywords:** single-cell RNA-seq, Shapley values, feature selection, marker genes, PPI networks, centrality  
**Links:** Code: … | Report: … (optional)

---

### Simulation of Site and Bond Percolation on Networks (Fall 2024)
**Supervisor:** Dr. Saman Moghimi Araghi  
**Collaborator:** Fatemeh Abbasian

Simulated and visualized site and bond percolation processes on multiple network families (e.g., small-world and other synthetic graphs), and compared qualitative changes in connectivity as occupation probability varies.

**Keywords:** percolation, phase transitions, complex networks, simulation, visualization  
**Links:** Code: … | Report: … (optional)

---

### Business Network Mapping for Economic Spillover Risk (Fall 2024)
**Supervisor:** Dr. Saman Moghimi Araghi  
**Collaborator:** Fatemeh Abbasian

Conducted a graph-theoretic analysis of the global trade network to study risk propagation mechanisms. Estimated country-level risk transmission coefficients from regression results and proposed a matrix-based method to compute spillover effects, then applied it to assess systemic vulnerability.

**Keywords:** economic networks, systemic risk, spillover, graph theory, matrix methods, regression  
**Links:** Code: … | Report: … (optional)


---

_Last updated: 2026-01-23_
