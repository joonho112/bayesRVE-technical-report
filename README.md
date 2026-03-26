# bayesRVE Technical Report

**bayesRVE: Cholesky Calibration Correction for Bayesian Meta-Analysis with Dependent Effect Sizes**

*Technical Report — Theory, Implementation, and Empirical Validation*

**Author:** JoonHo Lee (The University of Alabama)

## 📖 Read Online

👉 **[https://joonho112.github.io/bayesRVE-technical-report/](https://joonho112.github.io/bayesRVE-technical-report/)**

## Overview

This technical report provides a self-contained account of the theory, implementation, and empirical validation of the **bayesRVE** R package, which implements Cholesky Calibration Correction (CCC) for Bayesian meta-analysis with dependent effect sizes.

### Three-Layer Calibration

The bayesRVE package implements a three-layer calibration framework:

- **Layer 1 (Location):** Posterior mean as the point estimate (shrinkage)
- **Layer 2 (Spread):** CCC recalibrates posterior spread to match CR2 sandwich variance
- **Layer 3 (Tail behavior):** Satterthwaite degrees of freedom for small-sample correction

### Report Structure

| Part | Chapters | Focus |
|:-----|:---------|:------|
| **I: Foundations** | 1–5 | Statistical theory: models, sandwich, CCC, operating envelope |
| **II: Software** | 6–10 | Package architecture, Stan models, verification |
| **III: Empirical** | 11–13 | Real-data validation with Tanner-Smith & Lipsey (2015) |
| **Appendices** | A–D | Proofs, design decisions, API reference, reproducibility |

## Related

- **bayesRVE R package:** [https://github.com/joonho112/bayesRVE](https://github.com/joonho112/bayesRVE)

## Citation

Lee, J. H. (2026). *bayesRVE: Cholesky Calibration Correction for Bayesian Meta-Analysis with Dependent Effect Sizes.* Technical Report, The University of Alabama.

## License

© 2026 JoonHo Lee. All rights reserved.
