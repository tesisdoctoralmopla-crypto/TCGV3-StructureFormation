Non-Linear Structure Formation in Constitutive Gravity V3: The Core-Cusp Problem and Quantitative Falsifiability

This repository supports the findings presented in the paper "Non-Linear Structure Formation in Constitutive Gravity V3."

The \LambdaCDM model faces a major challenge on galactic scales known as the Cusp-Core problem. Standard N-body simulations predict steep dark matter profiles (cusps) that are observationally contradicted by the flat cores observed in low surface brightness galaxies.

This work presents the latest iteration of the Constitutive Gravity Theory (TCG V3), a modified scalar-tensor framework that fundamentally eliminates the requirement for Cold Dark Matter (CDM).

Key Results

Gravitational Wave Consistency: We formally demonstrate that TCG V3 is consistent with the multi-messenger observation GW170817 by proving that the speed of gravitational waves is c_{GW}=c.

Core-Cusp Solution: We implement the TCG non-linear field equation, which is characterized by a DBI-like constitutive function Z(y)=(1+y^{2})^{-1/2}, into a custom Newton-Gauss-Seidel solver for structure formation. Our numerical simulations show that TCG V3 robustly and deterministically forms cores in isolated galactic halos, solving the Cusp-Core problem purely through modified gravity.

Falsifiable Predictions: TCG V3 yields quantitative, falsifiable predictions that distinguish it from the $\Lambda$CDM model combined with baryonic feedback. The resulting galactic core size (r_{c}) is fixed by the fundamental acceleration scale a_{0}, which leads to a significantly narrower relationship between core size and stellar mass (r_{c} vs. M_{*}).

Implementation Details

The core of the numerical solution uses a custom Newton-Gauss-Seidel solver optimized for the non-linear TCG field equation. Specific numerical predictions for ultra-pristine dwarf galaxies are provided within the accompanying manuscript.
