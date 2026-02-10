
# Theorems (4 Total)

## Theorem 1: PVF Stability Guarantee
Given: $|v_i(t)| \leq 1$, spectral radius $\rho(\mathbf{W}_v) \leq \alpha < 1$, and $\sigma(\cdot)$ is 1-Lipschitz, then $|V(t)| \leq \sigma(K\alpha + |b_V|) < 1$ for all $t$.

## Theorem 2: Temporal Aliasing Bound
Let $V(t)$ be a continuous affective signal with power spectral density $S_V(f)$ non-zero for $f \in [0, B]$ where $B$ exceeds the Nyquist frequency. Sampling at $f_s = 1/\Delta t$ yields aliasing error:
$\E[\epsilon_{\text{cut}}^{\text{alias}}] = \int_{f_s/2}^{B} S_V(f) df$

## Theorem 3: Zero-Coupling Suboptimality
In PVF, $\mathbf{W}_v^{AB} = \mathbf{0}$ (no cross-agent terms by design). For coordination games where agents choose actions $a, b$ based on $V_A(a), V_B(b)$, the partial derivative:
$\frac{\partial V_A}{\partial b} = 0$
preventing gradient-based coordination.

## Theorem 4: Architectural Limits Theorem
Any architecture satisfying: (1) Rigid Markov blankets, (2) Fixed-dimensional geometry ($K=8$), (3) Individual optimization ($\min E_T$), necessarily violates at least one threshold in $\{\NC > 0.8, \PEI > 0.7, \CT > 0.3, \Ec > 0.30\}$ for participatory meaning-making.
