<!-- solve-problem:2af90020-4a11-4d3a-b30b-d4fb463e73df -->
# CHEM-000237: Guaranteed numerical errors for nonconvex Kohn–Sham calculations

A [Tangle Solve problem](https://solve.tangle.tools/problems/2af90020-4a11-4d3a-b30b-d4fb463e73df).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### CHEM-000237: Guaranteed numerical errors for nonconvex Kohn–Sham calculations
- **Subfield:** Round 2
- **Open:** Give computable energy-error bounds for nonconvex Kohn–Sham functionals, accounting for discretization and self-consistency while distinguishing local stationary states from the global minimum.
- **Status:** Guaranteed bounds were obtained for periodic equations with convex density functionals in 2025. Many practical exchange-correlation approximations violate that central hypothesis.
- **Type:** theory
- **Why:** Makes numerical phase orderings and energy differences testable independently of functional approximation error.
- **Key works:** A. Bordignon et al. (2025), *Fully Guaranteed and Computable Error Bounds on the Energy for Periodic Kohn–Sham Equations with Convex Density Functionals*, [DOI:10.1137/25M1735676](https://doi.org/10.1137/25M1735676).
- **Related:** Optimization: nonconvex global certification; numerical PDE: eigenvalue error bounds.
- **Source:** fleet:gpt6pro:chemistry:2026-10-06-gpt6pro-round2

## Source verification record

```json
{
  "census": "live",
  "domain": "chemistry",
  "id": "CHEM-000237",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "fleet-census",
  "triage": "suspect",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/2af90020-4a11-4d3a-b30b-d4fb463e73df?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: CHEM-000237.

- [Public source catalog](https://drewstone.github.io/problems/#/p/CHEM-000237)
