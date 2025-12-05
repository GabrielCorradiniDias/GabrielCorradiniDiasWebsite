# Thibado’s Graphene Ripple Harvester – A Clean SED Calculation

Paul Thibado's work on graphene membranes harvesting energy from thermal fluctuations via ripple waves is fascinating. But let's re-derive the power output using stochastic electrodynamics (SED) instead of pure quantum stats—SED treats the zero-point field (ZPF) as a real, classical bath of electromagnetic fluctuations.

## Quick Setup
The basic model: A graphene sheet oscillates due to ZPF pressure, creating voltage via piezoelectric coupling. SED power spectral density: $S(\omega) = \frac{\hbar \omega^3}{2\pi^2 c^3}$ (cutoff at Debye freq).

## Calculation Walkthrough
1. ZPF force on membrane: $F_{ZPF} = \int S(\omega) \cdot A \, d\omega$ (A = area).  
2. Ripple amplitude: $\delta z \approx \sqrt{kT / \kappa}$ (bending rigidity κ).  
3. Output power: $P = \frac{1}{2} C V^2 f$ where $V \sim e \delta z / d$ (d = gap).

Plugging numbers (Thibado's params: 1cm² sheet, room temp): ~nW/cm². Scalable to μW with arrays.

Ties back to Miller's ZPF extraction: This isn't "free energy"—it's vacuum engineering.

[[Related: library/puthoff-1989]] · X thread: 
