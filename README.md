# Phase-Lifted RG Memory Flow


<!-- HERO_ANIMATION:BEGIN -->
![Phase-lifted RG memory flow](images/phase_lifted_rg_flow.gif)

_Hero animation: **Phase-lifted RG memory flow**. [Download high-resolution MP4](images/phase_lifted_rg_flow.mp4)._
<!-- HERO_ANIMATION:END -->

**ID:** `eq-phase-lifted-rg-memory-flow`  
**Tier:** derived  
**Score:** 84  
**Units:** TBD  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\frac{d g}{d\ln \mu}=\beta(g)-\lambda_M g\sin^2\!\left(\frac{\theta_R}{2\pi_a}\right)
$$

## Description

Renormalization-group flow with a bounded phase-memory correction. The standard beta-function drives scale evolution, while the lifted-phase term penalizes branch-inconsistent history and introduces a memory-sensitive suppression of coupling flow. The proposal is that scale evolution depends not only on the instantaneous coupling g but also on the resolved phase history carried along the flow.

## Assumptions

- A single effective coupling g captures the relevant scale dependence
- beta(g) is the baseline flow law in the memory-free limit
- theta_R is a meaningful lifted history variable along the flow
- The memory term is a bounded correction rather than a replacement for beta(g)

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Registry](https://rdm3dc.github.io/TopEquations/registry.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
