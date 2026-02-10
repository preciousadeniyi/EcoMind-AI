
# Core Equations (25 Total)

## PVF (Primitive Valence Foundation) - 12 Equations

### 1. Affective Manifold Encoding
$\mathbf{s}(t) = \Phi(\mathbf{r}(t); \theta_\Phi) \in \mathbb{R}^d$ where $d=512$

### 2. Valence Primitives
$v_i(t) = \tanh\left(\mathbf{w}_i^\top \mathbf{s}(t) + b_i\right)$ for $i=1,\dots,8$

### 3. Quadratic Affective Field
$V(t) = \sigma\left(\mathbf{v}(t)^\top \mathbf{W}_v \mathbf{v}(t) + b_V\right)$ with $\rho(\mathbf{W}_v) \leq 0.95$

### 4. Existential Tension
$E_T(t) = -V(t) + \lambda_C C(t) + \lambda_R \|\mathbf{W}_v\|_F^2$

## PVF-AB (Affective Between) - 13 Equations

### 13. Collective Free Energy
$\mathcal{F}_C(t) = \sum_{a=1}^N \mathbb{E}_{q_a}[\mathcal{F}_a] - \beta \cdot \mathcal{I}(\{\mathbf{n}^a\}) - \gamma \cdot \mathcal{B}_{\text{contest}}(t) + \delta \cdot \mathcal{P}_{\text{power}}(t)$

### 14. Narrative Update
$\mathbf{n}^a(t+1) = \text{normalize}\left(\mathbf{n}^a(t) + \eta \left[\sum_{b \in \mathcal{N}_a} w_{ab}(t) \cdot \text{proj}_{\perp \mathbf{N}}(\mathbf{n}^b) + \boldsymbol{\xi}^a(t)\right]\right)$

### 25. Power Equity Index
$\PEI(t) = (1 - \text{Gini}(\{\sum_b w_{ab}\})) \times (1 - \text{Centralization}(t)) \times \text{MarginProtection}(t)$

*Full equations available in the paper: [link to your Google Drive]*
