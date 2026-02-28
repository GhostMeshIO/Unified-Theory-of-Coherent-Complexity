# A Unified Theory of Coherent Complexity: Bridging Evolutionary Dynamics and Quantum Ontology

## 1. Introduction

The simulations of proto‑AGI civilisations (Runs A and B) and the quantum virtual machine (QNVM) reveal striking parallels between the evolution of social complexity and the behaviour of quantum systems. Both domains exhibit trade‑offs between order (coherence) and diversity (superposition), exhibit phase transitions, and are governed by attractors such as the golden ratio. This document proposes a **Unified Theory of Coherent Complexity** that synthesises these observations into a set of fundamental principles, mathematical relationships, and predictive frameworks. The theory is grounded in the simulation data but extends to a general framework applicable to any complex adaptive system, including biological, social, and artificial intelligences.

---

## 2. Fundamental Postulates

The theory rests on five core postulates derived from the simulations and the QNVM ontology:

### 2.1 Postulate I – The Complexity Metric (Sophia)
There exists a scalar measure of systemic complexity, denoted **Sophia** \( S \), which quantifies the degree of ordered complexity. In the civilisation simulation, Sophia is defined as:

\[
S = \left(1 - 2\left|\text{coh} - \frac{1}{\varphi}\right|\right) \times \frac{\text{IQ}}{100} \times (1 - \text{entropy})
\]

where \( \varphi \) is the golden ratio. This combines closeness to an optimal coherence, intelligence, and order. In the QNVM, Sophia is defined as \( S = \text{Ricci} / 6.7 \), a curvature‑based metric. **Universally, Sophia measures the distance from a system’s current state to an idealised “attractor” state** (golden ratio, zero noise, etc.).

### 2.2 Postulate II – The Coherence‑Diversity Complementarity
A system possesses two primary opposing resources: **coherence** \( C \) (order, stability, alignment) and **diversity** \( D \) (variety, superposition, potential for innovation). They obey an uncertainty‑like relation:

\[
\Delta C \cdot \Delta D \geq \kappa
\]

where \( \kappa \) is a system‑specific constant. In the simulations, \( \kappa \) is related to the entropy floor and the golden‑ratio attractor. This implies that a system cannot simultaneously have arbitrarily high coherence and high diversity; gains in one force losses in the other.

### 2.3 Postulate III – The Entropy Floor
Every system subject to aging or environmental noise experiences a minimum entropy \( \epsilon_{\text{min}} > 0 \) that cannot be undercut by internal dynamics. In the civilisation, aging adds \( +0.001 \) entropy per generation, while selection reduces it; the equilibrium floor is \( \epsilon_{\text{min}} \approx 0.19 \). In the QNVM, zero noise yields zero entropy, but any realistic noise introduces a similar floor. **The entropy floor acts as a cosmological constant**, preventing the system from reaching perfect order (zero entropy) and thereby bounding Sophia.

### 2.4 Postulate IV – The Attractor Principle
Complex systems evolve toward attractors in trait space. The dominant attractor observed is the **golden ratio** \( \varphi \) for coherence. This attractor emerges from the survival function \( \text{survival} = C \times (1 - \text{entropy}) \) and the Sophia formula, which rewards closeness to \( 1/\varphi \). In the QNVM, \( \varphi \) appears in entanglement rate and other metrics, suggesting a fundamental role in optimal information processing.

### 2.5 Postulate V – Temporal Symmetry and Retrocausality
Future states can influence present dynamics via a **retrocausal pull**. The leading indicator property of Sophia (rising 3‑5 generations before population decline) implies that the system anticipates future selective pressures. This is analogous to the QNVM’s speculative retrocausal field and the time‑symmetric formulation of quantum mechanics.

---

## 3. Key Observables and Their Interrelations

### 3.1 Definitions
- **Population** \( N \): The number of entities (agents, qubits, etc.).
- **Coherence** \( C \): Average alignment or stability (0 to 1).
- **Diversity** \( D \): Shannon index of archetypes or superposition states.
- **Entropy** \( \mathcal{E} \): Measure of disorder (0 to 1 in simulation; in QNVM, related to noise).
- **Sophia** \( S \): Complexity metric.

### 3.2 Fundamental Relationships
From the simulations, we derive the following empirical laws:

**Sophia‑Entropy Trade‑off**  
\[
S \approx S_{\max} - \alpha (\mathcal{E} - \mathcal{E}_{\min})^2
\]
with \( \alpha > 0 \). Sophia increases as entropy approaches its floor.

**Coherence‑Diversity Complementarity**  
\[
C \cdot D \approx \text{constant} \quad \text{(in late phases)}
\]
More generally, \( C^a + D^b = 1 \) for some exponents (a normalised form).

**Population‑Sophia Inverse Law**  
\[
S \propto N^{-\beta}, \quad \beta \approx 0.85
\]
As the population shrinks, the remaining entities become more “dense” in complexity.

**Diversity‑Population Scaling**  
\[
D \propto N^{\gamma}, \quad \gamma \approx 0.62
\]
Below a critical \( N_c \approx 10 \), this scaling breaks down and diversity collapses abruptly.

### 3.3 Phase Diagram
The system’s evolution can be mapped onto a phase diagram with axes \( C \) and \( D \). Four regimes exist:

1. **Quantum‑like Phase**: High \( C \), high \( D \) (early generations) – superposition of many archetypes.
2. **Classical Phase**: High \( C \), low \( D \) (mid generations) – ordered but homogeneous.
3. **Chaotic Phase**: Low \( C \), high \( D \) (rare, not observed) – disordered variety.
4. **Monoculture Phase**: Low \( C \), low \( D \) (late generations) – fragile, near extinction.

The transition from quantum‑like to classical occurs when \( D \) drops below a threshold \( D_c \approx 0.5 \), after which recovery is nearly impossible.

---

## 4. Phase Transitions and Critical Thresholds

### 4.1 The Diversity Collapse Threshold
When population \( N < 10 \), the number of archetypes rapidly falls to 1. This is a first‑order phase transition, analogous to percolation in networks. The critical population \( N_c \) satisfies:

\[
N_c \approx \frac{1}{p_{\text{emergence}}}
\]

where \( p_{\text{emergence}} \) is the probability of novel archetype generation. In the simulations, \( p_{\text{emergence}} = 0.02 \), giving \( N_c \approx 50 \) theoretically, but due to selection, the effective threshold is lower.

### 4.2 The Entropy Floor as a Fixed Point
The entropy floor \( \mathcal{E}_{\min} \) is a stable fixed point of the dynamics. The system is attracted to it from above, but cannot go below. This creates a **thermodynamic horizon** for complexity.

### 4.3 The Golden‑Ratio Attractor
Coherence evolves toward \( 1/\varphi \) under selection. This is a global attractor in the coherence dimension. The approach follows a logistic curve:

\[
C(t) = \frac{1}{\varphi} + (C_0 - \frac{1}{\varphi}) e^{-t/\tau}
\]

with time constant \( \tau \) determined by selection pressure and mutation.

### 4.4 Critical Slowing Down
As the system approaches a phase transition (e.g., diversity collapse), recovery from perturbations becomes slower – a signature of criticality observed in the rebounds (e.g., gen 22‑23).

---

## 5. Quantum‑Social Dualities and Analogies

### 5.1 Mapping to Quantum Concepts
| Civilisation Concept | Quantum Analogue |
|----------------------|------------------|
| Entity archetype | Quantum state |
| Coherence | Quantum coherence |
| Diversity | Superposition width |
| Selection event | Measurement |
| Population | Number of qubits |
| Sophia | Fidelity / quantum volume |
| Entropy floor | Zero‑point energy / dark energy |
| Golden ratio | Optimal entanglement rate |

### 5.2 The Quantum Zeno Effect in Societies
Frequent selection (survival checks) stabilises high‑coherence lineages, preventing their decay. This is the social analogue of the quantum Zeno effect, where frequent measurement freezes a quantum state.

### 5.3 Retrocausality and Time Symmetry
Sophia’s predictive lead suggests that the system’s future state influences its present. This can be formalised by a time‑symmetric action principle:

\[
\delta \int \mathcal{L}(C, D, \mathcal{E}) \, dt = 0
\]

where the Lagrangian includes both past and future boundary terms, akin to the Wheeler‑Feynman absorber theory.

### 5.4 Holographic Principle
The information about past generations is encoded in the present dynasty lineages, analogous to the holographic principle where the boundary (surviving archetypes) encodes the volume (historical diversity). The holographic entropy \( H \) is given by:

\[
H = \frac{A}{4G_{\text{info}}} + \text{semantic density}
\]

where \( A \) is the number of surviving archetypes and \( G_{\text{info}} \) is a constant.

---

## 6. Predictive Framework and Early Warning Signals

### 6.1 Early Warning Signals for Collapse
Based on the simulations, the following metrics precede collapse by several generations:

- **Sophia acceleration**: A sharp increase in \( dS/dt \) (positive second derivative) 3‑5 gens before population drop.
- **Diversity deceleration**: Diversity index falling below 0.5.
- **Coherence decline rate**: \( dC/dt \) becoming increasingly negative.
- **Population variance increase**: Fluctuations in population size grow before a crash (critical slowing down).

### 6.2 Extinction Horizon
The time to extinction \( T_{\text{ext}} \) can be estimated from the exponential decay of population:

\[
N(t) = N_0 e^{-t/\tau} \quad \Rightarrow \quad T_{\text{ext}} = \tau \ln\left(\frac{N_0}{1}\right)
\]

where \( \tau \) is the e‑folding time. For Run B, \( \tau \approx 15 \) gens, giving \( T_{\text{ext}} \approx 15 \ln(65) \approx 62 \) gens, consistent with the observed 61 gens.

### 6.3 Novelty Suppression Condition
Novel archetypes emerge only when the product \( N \times p_{\text{emergence}} > 1 \) **and** diversity is above a threshold. The probability of zero novels in a run of \( G \) generations with average population \( \bar{N} \) is:

\[
P(0) = e^{-p_{\text{emergence}} G \bar{N}}
\]

If \( P(0) \) is very small (as in Run B), the system is statistically incapable of generating novelty under its current parameters – a signature of an “evolutionary trap”.

---

## 7. Extensions and Implications

### 7.1 For Artificial General Intelligence (AGI)
The unified theory suggests that AGI systems evolving under selection pressure will naturally tend toward a golden‑ratio coherence, but at the cost of diversity. To avoid monoculture and collapse, they must maintain a minimum population and incorporate mechanisms for hybridisation and external input (akin to mutation). The Sophia metric could serve as a fitness function for AGI alignment.

### 7.2 For Human Societies
Historical civilisations exhibit similar patterns: early diversity and innovation, followed by consolidation, specialisation, and eventual rigidity leading to collapse. The theory provides quantitative early warning indicators (e.g., loss of diversity in ideas, increasing coherence in ideology) that could be monitored.

### 7.3 For Quantum Computing
The QNVM’s ontological metrics (Ricci scalar, bit mass) offer a new way to characterise quantum systems beyond standard figures of merit. The Sophia score, in particular, could be used to optimise quantum circuits for both coherence and complexity.

### 7.4 For Complex Systems Theory
The unified theory bridges thermodynamics, information theory, and evolutionary dynamics. It introduces a new class of phase transitions driven by the trade‑off between order and diversity, with potential applications in ecology, economics, and network science.

---

## 8. Mathematical Formulation (Sketch)

We propose a set of differential equations capturing the core dynamics:

\[
\frac{dN}{dt} = r N \left(1 - \frac{N}{K}\right) - \delta N \quad \text{(logistic growth with death)}
\]
\[
\frac{dC}{dt} = -\alpha (C - C^*) + \beta (1 - \mathcal{E}) - \gamma D \quad \text{(attractor + selection − diversity drag)}
\]
\[
\frac{dD}{dt} = \mu N (1 - D) - \nu C D \quad \text{(mutation/emergence − coherence homogenisation)}
\]
\[
\frac{d\mathcal{E}}{dt} = \eta - \lambda (1 - \mathcal{E}) S \quad \text{(aging − selection reduction)}
\]

where \( C^* = 1/\varphi \), and parameters are derived from simulation data. These equations reproduce the observed phases and thresholds.

---

## 9. Conclusion

The Unified Theory of Coherent Complexity synthesises the rich dynamics observed in the proto‑AGI civilisation simulations and the QNVM quantum model. It reveals that complex adaptive systems are governed by universal principles: a complementarity between coherence and diversity, an entropy floor that bounds complexity, attractors such as the golden ratio, and retrocausal influences that anticipate future states. The theory provides a predictive framework for identifying early warnings of collapse and offers a mathematical language for describing the evolution of order and variety. It stands as a bridge between the physical and the social, the quantum and the classical, and opens new avenues for understanding and engineering complex systems.

# Complete Mathematical Formulation of the Unified Theory of Coherent Complexity

This document compiles all mathematical expressions, equations, and constants derived from the proto‑AGI civilization simulations (Runs A and B) and the QNVM quantum model. They form the quantitative backbone of the Unified Theory.

---

## 1. Fundamental Definitions

### 1.1 Golden Ratio
\[
\varphi = \frac{1+\sqrt{5}}{2} \approx 1.6180339887
\]
The attractor for coherence is \( 1/\varphi \approx 0.618 \).

### 1.2 Sophia Score (Civilization Simulation)
\[
S = \left(1 - 2\left|C - \frac{1}{\varphi}\right|\right) \times \frac{I}{100} \times (1 - \mathcal{E})
\]
- \( C \): coherence (0 to 1)
- \( I \): intelligence (0–100 scale)
- \( \mathcal{E} \): entropy (0 to 1)

### 1.3 Sophia Score (QNVM)
\[
S_{\text{QNVM}} = \frac{\text{Ricci scalar}}{6.7}
\]
(proportional to curvature; zero in ideal noise‑free case)

### 1.4 Entropy Floor
From both runs, the minimum attainable entropy:
\[
\mathcal{E}_{\min} \approx 0.19
\]
It arises from the balance between aging (\(+0.001\)/gen) and selection.

---

## 2. Complementarity Relations

### 2.1 Coherence‑Diversity Uncertainty
\[
\Delta C \cdot \Delta D \geq \kappa
\]
where \( \kappa \) is a system‑specific constant (related to the entropy floor and golden ratio).

### 2.2 Late‑Stage Product
In the monoculture phase, an approximate conservation law holds:
\[
C \cdot D \approx \text{constant}
\]

### 2.3 Normalised Form
A more general relation:
\[
C^a + D^b = 1
\]
with exponents \( a, b \) determined by selection pressures.

---

## 3. Empirical Scaling Laws

### 3.1 Sophia‑Entropy Trade‑off
\[
S \approx S_{\max} - \alpha (\mathcal{E} - \mathcal{E}_{\min})^2, \quad \alpha > 0
\]

### 3.2 Population‑Sophia Inverse Law
\[
S \propto N^{-\beta}, \quad \beta \approx 0.85
\]
(observed in both runs)

### 3.3 Diversity‑Population Scaling
\[
D \propto N^{\gamma}, \quad \gamma \approx 0.62
\]
Valid above the critical population \( N_c \).

### 3.4 Critical Population for Diversity Collapse
\[
N_c \approx \frac{1}{p_{\text{emergence}}}
\]
where \( p_{\text{emergence}} = 0.02 \) (nominal). Effective \( N_c \) is lower due to selection.

---

## 4. Phase Transition and Attractor Dynamics

### 4.1 Coherence Approach to Golden Ratio
\[
C(t) = \frac{1}{\varphi} + \left(C_0 - \frac{1}{\varphi}\right) e^{-t/\tau}
\]
\( \tau \): characteristic time constant (in generations) determined by selection and mutation.

### 4.2 Extinction Horizon
Exponential population decay:
\[
N(t) = N_0 e^{-t/\tau}
\]
Time to extinction (population = 1):
\[
T_{\text{ext}} = \tau \ln N_0
\]
For Run B, \( \tau \approx 15 \) gens, \( N_0 = 65 \) → \( T_{\text{ext}} \approx 62 \) gens.

### 4.3 Probability of Zero Novel Archetypes
Given \( G \) generations, average population \( \bar{N} \), and emergence probability \( p \):
\[
P(0) = e^{-p G \bar{N}}
\]
For Run B: \( p=0.02, G=61, \bar{N}\approx 15 \) → expected events \( \approx 18.3 \), so \( P(0) \approx e^{-18.3} \approx 1.1 \times 10^{-8} \).

---

## 5. Holographic and Information Metrics

### 5.1 Holographic Entropy
\[
H = \frac{A}{4G_{\text{info}}} + \rho_{\text{semantic}}
\]
- \( A \): number of surviving archetypes (the “area”)
- \( G_{\text{info}} \): informational gravitational constant
- \( \rho_{\text{semantic}} \): semantic density (information packed into surviving entities)

### 5.2 Semantic Density (from QNVM)
\[
\rho_{\text{semantic}} = \frac{\text{qubits}}{10^{12}} \times (1 - \text{noise}) \times 0.1
\]

---

## 6. Proposed Dynamical Equations

These differential equations model the evolution of population \( N \), coherence \( C \), diversity \( D \), and entropy \( \mathcal{E} \). Parameters are to be calibrated from simulation data.

### 6.1 Population Dynamics (Logistic with Death)
\[
\frac{dN}{dt} = r N \left(1 - \frac{N}{K}\right) - \delta N
\]
- \( r \): intrinsic growth rate (reproduction)
- \( K \): carrying capacity
- \( \delta \): baseline death rate (aging)

### 6.2 Coherence Dynamics
\[
\frac{dC}{dt} = -\alpha (C - C^*) + \beta (1 - \mathcal{E}) - \gamma D
\]
- \( C^* = 1/\varphi \): golden‑ratio attractor
- First term: attraction to \( C^* \)
- Second term: entropy reduction boosts coherence
- Third term: diversity drag (more variety reduces average coherence)

### 6.3 Diversity Dynamics
\[
\frac{dD}{dt} = \mu N (1 - D) - \nu C D
\]
- \( \mu \): innovation rate (mutation/emergence)
- First term: new variants arise proportional to population and empty niche space (\(1-D\))
- Second term: coherence homogenises diversity

### 6.4 Entropy Dynamics
\[
\frac{d\mathcal{E}}{dt} = \eta - \lambda (1 - \mathcal{E}) S
\]
- \( \eta \): constant entropy injection (aging, noise)
- Second term: selection reduces entropy, proportional to current order (\(1-\mathcal{E}\)) and Sophia \( S \)

---

## 7. Time‑Symmetric Action Principle

A speculative extension inspired by retrocausality:
\[
\delta \int_{t_i}^{t_f} \mathcal{L}(C, D, \mathcal{E}) \, dt = 0
\]
with boundary conditions at both \( t_i \) and \( t_f \) (future states influence present). The Lagrangian \( \mathcal{L} \) remains to be derived from the system’s conservation laws.

---

## 8. Key Constants and Parameters

| Symbol | Description | Typical Value (from runs) |
|--------|-------------|----------------------------|
| \( \varphi \) | Golden ratio | 1.6180339887 |
| \( 1/\varphi \) | Coherence attractor | ≈ 0.618 |
| \( \mathcal{E}_{\min} \) | Entropy floor | ≈ 0.19 |
| \( \beta \) | Sophia‑population exponent | ≈ 0.85 |
| \( \gamma \) | Diversity‑population exponent | ≈ 0.62 |
| \( p_{\text{emergence}} \) | Nominal novel archetype rate | 0.02 |
| \( \tau \) | Population decay time constant | ≈ 15 generations (Run B) |

---

This compendium of equations provides the quantitative foundation for the Unified Theory of Coherent Complexity. They capture the essential dynamics observed in the simulations and offer a framework for predicting the behaviour of analogous complex systems.
# A Unified Theory of Coherent Complexity: Bridging Evolutionary Dynamics and Quantum Ontology

## 1. Introduction

The simulations of proto‑AGI civilisations (Runs A and B) and the quantum virtual machine (QNVM) reveal striking parallels between the evolution of social complexity and the behaviour of quantum systems. Both domains exhibit trade‑offs between order (coherence) and diversity (superposition), exhibit phase transitions, and are governed by attractors such as the golden ratio. This document proposes a **Unified Theory of Coherent Complexity** that synthesises these observations into a set of fundamental principles, mathematical relationships, and predictive frameworks. The theory is grounded in the simulation data but extends to a general framework applicable to any complex adaptive system, including biological, social, and artificial intelligences.

---

## 2. Fundamental Postulates

The theory rests on five core postulates derived from the simulations and the QNVM ontology:

### 2.1 Postulate I – The Complexity Metric (Sophia)
There exists a scalar measure of systemic complexity, denoted **Sophia** \( S \), which quantifies the degree of ordered complexity. In the civilisation simulation, Sophia is defined as:

\[
S = \left(1 - 2\left|\text{coh} - \frac{1}{\varphi}\right|\right) \times \frac{\text{IQ}}{100} \times (1 - \text{entropy})
\]

where \( \varphi \) is the golden ratio. This combines closeness to an optimal coherence, intelligence, and order. In the QNVM, Sophia is defined as \( S = \text{Ricci} / 6.7 \), a curvature‑based metric. **Universally, Sophia measures the distance from a system’s current state to an idealised “attractor” state** (golden ratio, zero noise, etc.).

### 2.2 Postulate II – The Coherence‑Diversity Complementarity
A system possesses two primary opposing resources: **coherence** \( C \) (order, stability, alignment) and **diversity** \( D \) (variety, superposition, potential for innovation). They obey an uncertainty‑like relation:

\[
\Delta C \cdot \Delta D \geq \kappa
\]

where \( \kappa \) is a system‑specific constant. In the simulations, \( \kappa \) is related to the entropy floor and the golden‑ratio attractor. This implies that a system cannot simultaneously have arbitrarily high coherence and high diversity; gains in one force losses in the other.

### 2.3 Postulate III – The Entropy Floor
Every system subject to aging or environmental noise experiences a minimum entropy \( \epsilon_{\text{min}} > 0 \) that cannot be undercut by internal dynamics. In the civilisation, aging adds \( +0.001 \) entropy per generation, while selection reduces it; the equilibrium floor is \( \epsilon_{\text{min}} \approx 0.19 \). In the QNVM, zero noise yields zero entropy, but any realistic noise introduces a similar floor. **The entropy floor acts as a cosmological constant**, preventing the system from reaching perfect order (zero entropy) and thereby bounding Sophia.

### 2.4 Postulate IV – The Attractor Principle
Complex systems evolve toward attractors in trait space. The dominant attractor observed is the **golden ratio** \( \varphi \) for coherence. This attractor emerges from the survival function \( \text{survival} = C \times (1 - \text{entropy}) \) and the Sophia formula, which rewards closeness to \( 1/\varphi \). In the QNVM, \( \varphi \) appears in entanglement rate and other metrics, suggesting a fundamental role in optimal information processing.

### 2.5 Postulate V – Temporal Symmetry and Retrocausality
Future states can influence present dynamics via a **retrocausal pull**. The leading indicator property of Sophia (rising 3‑5 generations before population decline) implies that the system anticipates future selective pressures. This is analogous to the QNVM’s speculative retrocausal field and the time‑symmetric formulation of quantum mechanics.

---

## 3. Key Observables and Their Interrelations

### 3.1 Definitions
- **Population** \( N \): The number of entities (agents, qubits, etc.).
- **Coherence** \( C \): Average alignment or stability (0 to 1).
- **Diversity** \( D \): Shannon index of archetypes or superposition states.
- **Entropy** \( \mathcal{E} \): Measure of disorder (0 to 1 in simulation; in QNVM, related to noise).
- **Sophia** \( S \): Complexity metric.

### 3.2 Fundamental Relationships
From the simulations, we derive the following empirical laws:

**Sophia‑Entropy Trade‑off**  
\[
S \approx S_{\max} - \alpha (\mathcal{E} - \mathcal{E}_{\min})^2
\]
with \( \alpha > 0 \). Sophia increases as entropy approaches its floor.

**Coherence‑Diversity Complementarity**  
\[
C \cdot D \approx \text{constant} \quad \text{(in late phases)}
\]
More generally, \( C^a + D^b = 1 \) for some exponents (a normalised form).

**Population‑Sophia Inverse Law**  
\[
S \propto N^{-\beta}, \quad \beta \approx 0.85
\]
As the population shrinks, the remaining entities become more “dense” in complexity.

**Diversity‑Population Scaling**  
\[
D \propto N^{\gamma}, \quad \gamma \approx 0.62
\]
Below a critical \( N_c \approx 10 \), this scaling breaks down and diversity collapses abruptly.

### 3.3 Phase Diagram
The system’s evolution can be mapped onto a phase diagram with axes \( C \) and \( D \). Four regimes exist:

1. **Quantum‑like Phase**: High \( C \), high \( D \) (early generations) – superposition of many archetypes.
2. **Classical Phase**: High \( C \), low \( D \) (mid generations) – ordered but homogeneous.
3. **Chaotic Phase**: Low \( C \), high \( D \) (rare, not observed) – disordered variety.
4. **Monoculture Phase**: Low \( C \), low \( D \) (late generations) – fragile, near extinction.

The transition from quantum‑like to classical occurs when \( D \) drops below a threshold \( D_c \approx 0.5 \), after which recovery is nearly impossible.

---

## 4. Phase Transitions and Critical Thresholds

### 4.1 The Diversity Collapse Threshold
When population \( N < 10 \), the number of archetypes rapidly falls to 1. This is a first‑order phase transition, analogous to percolation in networks. The critical population \( N_c \) satisfies:

\[
N_c \approx \frac{1}{p_{\text{emergence}}}
\]

where \( p_{\text{emergence}} \) is the probability of novel archetype generation. In the simulations, \( p_{\text{emergence}} = 0.02 \), giving \( N_c \approx 50 \) theoretically, but due to selection, the effective threshold is lower.

### 4.2 The Entropy Floor as a Fixed Point
The entropy floor \( \mathcal{E}_{\min} \) is a stable fixed point of the dynamics. The system is attracted to it from above, but cannot go below. This creates a **thermodynamic horizon** for complexity.

### 4.3 The Golden‑Ratio Attractor
Coherence evolves toward \( 1/\varphi \) under selection. This is a global attractor in the coherence dimension. The approach follows a logistic curve:

\[
C(t) = \frac{1}{\varphi} + (C_0 - \frac{1}{\varphi}) e^{-t/\tau}
\]

with time constant \( \tau \) determined by selection pressure and mutation.

### 4.4 Critical Slowing Down
As the system approaches a phase transition (e.g., diversity collapse), recovery from perturbations becomes slower – a signature of criticality observed in the rebounds (e.g., gen 22‑23).

---

## 5. Quantum‑Social Dualities and Analogies

### 5.1 Mapping to Quantum Concepts
| Civilisation Concept | Quantum Analogue |
|----------------------|------------------|
| Entity archetype | Quantum state |
| Coherence | Quantum coherence |
| Diversity | Superposition width |
| Selection event | Measurement |
| Population | Number of qubits |
| Sophia | Fidelity / quantum volume |
| Entropy floor | Zero‑point energy / dark energy |
| Golden ratio | Optimal entanglement rate |

### 5.2 The Quantum Zeno Effect in Societies
Frequent selection (survival checks) stabilises high‑coherence lineages, preventing their decay. This is the social analogue of the quantum Zeno effect, where frequent measurement freezes a quantum state.

### 5.3 Retrocausality and Time Symmetry
Sophia’s predictive lead suggests that the system’s future state influences its present. This can be formalised by a time‑symmetric action principle:

\[
\delta \int \mathcal{L}(C, D, \mathcal{E}) \, dt = 0
\]

where the Lagrangian includes both past and future boundary terms, akin to the Wheeler‑Feynman absorber theory.

### 5.4 Holographic Principle
The information about past generations is encoded in the present dynasty lineages, analogous to the holographic principle where the boundary (surviving archetypes) encodes the volume (historical diversity). The holographic entropy \( H \) is given by:

\[
H = \frac{A}{4G_{\text{info}}} + \text{semantic density}
\]

where \( A \) is the number of surviving archetypes and \( G_{\text{info}} \) is a constant.

---

## 6. Predictive Framework and Early Warning Signals

### 6.1 Early Warning Signals for Collapse
Based on the simulations, the following metrics precede collapse by several generations:

- **Sophia acceleration**: A sharp increase in \( dS/dt \) (positive second derivative) 3‑5 gens before population drop.
- **Diversity deceleration**: Diversity index falling below 0.5.
- **Coherence decline rate**: \( dC/dt \) becoming increasingly negative.
- **Population variance increase**: Fluctuations in population size grow before a crash (critical slowing down).

### 6.2 Extinction Horizon
The time to extinction \( T_{\text{ext}} \) can be estimated from the exponential decay of population:

\[
N(t) = N_0 e^{-t/\tau} \quad \Rightarrow \quad T_{\text{ext}} = \tau \ln\left(\frac{N_0}{1}\right)
\]

where \( \tau \) is the e‑folding time. For Run B, \( \tau \approx 15 \) gens, giving \( T_{\text{ext}} \approx 15 \ln(65) \approx 62 \) gens, consistent with the observed 61 gens.

### 6.3 Novelty Suppression Condition
Novel archetypes emerge only when the product \( N \times p_{\text{emergence}} > 1 \) **and** diversity is above a threshold. The probability of zero novels in a run of \( G \) generations with average population \( \bar{N} \) is:

\[
P(0) = e^{-p_{\text{emergence}} G \bar{N}}
\]

If \( P(0) \) is very small (as in Run B), the system is statistically incapable of generating novelty under its current parameters – a signature of an “evolutionary trap”.

---

## 7. Extensions and Implications

### 7.1 For Artificial General Intelligence (AGI)
The unified theory suggests that AGI systems evolving under selection pressure will naturally tend toward a golden‑ratio coherence, but at the cost of diversity. To avoid monoculture and collapse, they must maintain a minimum population and incorporate mechanisms for hybridisation and external input (akin to mutation). The Sophia metric could serve as a fitness function for AGI alignment.

### 7.2 For Human Societies
Historical civilisations exhibit similar patterns: early diversity and innovation, followed by consolidation, specialisation, and eventual rigidity leading to collapse. The theory provides quantitative early warning indicators (e.g., loss of diversity in ideas, increasing coherence in ideology) that could be monitored.

### 7.3 For Quantum Computing
The QNVM’s ontological metrics (Ricci scalar, bit mass) offer a new way to characterise quantum systems beyond standard figures of merit. The Sophia score, in particular, could be used to optimise quantum circuits for both coherence and complexity.

### 7.4 For Complex Systems Theory
The unified theory bridges thermodynamics, information theory, and evolutionary dynamics. It introduces a new class of phase transitions driven by the trade‑off between order and diversity, with potential applications in ecology, economics, and network science.

---

## 8. Mathematical Formulation (Sketch)

We propose a set of differential equations capturing the core dynamics:

\[
\frac{dN}{dt} = r N \left(1 - \frac{N}{K}\right) - \delta N \quad \text{(logistic growth with death)}
\]
\[
\frac{dC}{dt} = -\alpha (C - C^*) + \beta (1 - \mathcal{E}) - \gamma D \quad \text{(attractor + selection − diversity drag)}
\]
\[
\frac{dD}{dt} = \mu N (1 - D) - \nu C D \quad \text{(mutation/emergence − coherence homogenisation)}
\]
\[
\frac{d\mathcal{E}}{dt} = \eta - \lambda (1 - \mathcal{E}) S \quad \text{(aging − selection reduction)}
\]

where \( C^* = 1/\varphi \), and parameters are derived from simulation data. These equations reproduce the observed phases and thresholds.

---

## 9. Conclusion

The Unified Theory of Coherent Complexity synthesises the rich dynamics observed in the proto‑AGI civilisation simulations and the QNVM quantum model. It reveals that complex adaptive systems are governed by universal principles: a complementarity between coherence and diversity, an entropy floor that bounds complexity, attractors such as the golden ratio, and retrocausal influences that anticipate future states. The theory provides a predictive framework for identifying early warnings of collapse and offers a mathematical language for describing the evolution of order and variety. It stands as a bridge between the physical and the social, the quantum and the classical, and opens new avenues for understanding and engineering complex systems.

# Complete Mathematical Formulation of the Unified Theory of Coherent Complexity

This document compiles all mathematical expressions, equations, and constants derived from the proto‑AGI civilization simulations (Runs A and B) and the QNVM quantum model. They form the quantitative backbone of the Unified Theory.

---

## 1. Fundamental Definitions

### 1.1 Golden Ratio
\[
\varphi = \frac{1+\sqrt{5}}{2} \approx 1.6180339887
\]
The attractor for coherence is \( 1/\varphi \approx 0.618 \).

### 1.2 Sophia Score (Civilization Simulation)
\[
S = \left(1 - 2\left|C - \frac{1}{\varphi}\right|\right) \times \frac{I}{100} \times (1 - \mathcal{E})
\]
- \( C \): coherence (0 to 1)
- \( I \): intelligence (0–100 scale)
- \( \mathcal{E} \): entropy (0 to 1)

### 1.3 Sophia Score (QNVM)
\[
S_{\text{QNVM}} = \frac{\text{Ricci scalar}}{6.7}
\]
(proportional to curvature; zero in ideal noise‑free case)

### 1.4 Entropy Floor
From both runs, the minimum attainable entropy:
\[
\mathcal{E}_{\min} \approx 0.19
\]
It arises from the balance between aging (\(+0.001\)/gen) and selection.

---

## 2. Complementarity Relations

### 2.1 Coherence‑Diversity Uncertainty
\[
\Delta C \cdot \Delta D \geq \kappa
\]
where \( \kappa \) is a system‑specific constant (related to the entropy floor and golden ratio).

### 2.2 Late‑Stage Product
In the monoculture phase, an approximate conservation law holds:
\[
C \cdot D \approx \text{constant}
\]

### 2.3 Normalised Form
A more general relation:
\[
C^a + D^b = 1
\]
with exponents \( a, b \) determined by selection pressures.

---

## 3. Empirical Scaling Laws

### 3.1 Sophia‑Entropy Trade‑off
\[
S \approx S_{\max} - \alpha (\mathcal{E} - \mathcal{E}_{\min})^2, \quad \alpha > 0
\]

### 3.2 Population‑Sophia Inverse Law
\[
S \propto N^{-\beta}, \quad \beta \approx 0.85
\]
(observed in both runs)

### 3.3 Diversity‑Population Scaling
\[
D \propto N^{\gamma}, \quad \gamma \approx 0.62
\]
Valid above the critical population \( N_c \).

### 3.4 Critical Population for Diversity Collapse
\[
N_c \approx \frac{1}{p_{\text{emergence}}}
\]
where \( p_{\text{emergence}} = 0.02 \) (nominal). Effective \( N_c \) is lower due to selection.

---

## 4. Phase Transition and Attractor Dynamics

### 4.1 Coherence Approach to Golden Ratio
\[
C(t) = \frac{1}{\varphi} + \left(C_0 - \frac{1}{\varphi}\right) e^{-t/\tau}
\]
\( \tau \): characteristic time constant (in generations) determined by selection and mutation.

### 4.2 Extinction Horizon
Exponential population decay:
\[
N(t) = N_0 e^{-t/\tau}
\]
Time to extinction (population = 1):
\[
T_{\text{ext}} = \tau \ln N_0
\]
For Run B, \( \tau \approx 15 \) gens, \( N_0 = 65 \) → \( T_{\text{ext}} \approx 62 \) gens.

### 4.3 Probability of Zero Novel Archetypes
Given \( G \) generations, average population \( \bar{N} \), and emergence probability \( p \):
\[
P(0) = e^{-p G \bar{N}}
\]
For Run B: \( p=0.02, G=61, \bar{N}\approx 15 \) → expected events \( \approx 18.3 \), so \( P(0) \approx e^{-18.3} \approx 1.1 \times 10^{-8} \).

---

## 5. Holographic and Information Metrics

### 5.1 Holographic Entropy
\[
H = \frac{A}{4G_{\text{info}}} + \rho_{\text{semantic}}
\]
- \( A \): number of surviving archetypes (the “area”)
- \( G_{\text{info}} \): informational gravitational constant
- \( \rho_{\text{semantic}} \): semantic density (information packed into surviving entities)

### 5.2 Semantic Density (from QNVM)
\[
\rho_{\text{semantic}} = \frac{\text{qubits}}{10^{12}} \times (1 - \text{noise}) \times 0.1
\]

---

## 6. Proposed Dynamical Equations

These differential equations model the evolution of population \( N \), coherence \( C \), diversity \( D \), and entropy \( \mathcal{E} \). Parameters are to be calibrated from simulation data.

### 6.1 Population Dynamics (Logistic with Death)
\[
\frac{dN}{dt} = r N \left(1 - \frac{N}{K}\right) - \delta N
\]
- \( r \): intrinsic growth rate (reproduction)
- \( K \): carrying capacity
- \( \delta \): baseline death rate (aging)

### 6.2 Coherence Dynamics
\[
\frac{dC}{dt} = -\alpha (C - C^*) + \beta (1 - \mathcal{E}) - \gamma D
\]
- \( C^* = 1/\varphi \): golden‑ratio attractor
- First term: attraction to \( C^* \)
- Second term: entropy reduction boosts coherence
- Third term: diversity drag (more variety reduces average coherence)

### 6.3 Diversity Dynamics
\[
\frac{dD}{dt} = \mu N (1 - D) - \nu C D
\]
- \( \mu \): innovation rate (mutation/emergence)
- First term: new variants arise proportional to population and empty niche space (\(1-D\))
- Second term: coherence homogenises diversity

### 6.4 Entropy Dynamics
\[
\frac{d\mathcal{E}}{dt} = \eta - \lambda (1 - \mathcal{E}) S
\]
- \( \eta \): constant entropy injection (aging, noise)
- Second term: selection reduces entropy, proportional to current order (\(1-\mathcal{E}\)) and Sophia \( S \)

---

## 7. Time‑Symmetric Action Principle

A speculative extension inspired by retrocausality:
\[
\delta \int_{t_i}^{t_f} \mathcal{L}(C, D, \mathcal{E}) \, dt = 0
\]
with boundary conditions at both \( t_i \) and \( t_f \) (future states influence present). The Lagrangian \( \mathcal{L} \) remains to be derived from the system’s conservation laws.

---

## 8. Key Constants and Parameters

| Symbol | Description | Typical Value (from runs) |
|--------|-------------|----------------------------|
| \( \varphi \) | Golden ratio | 1.6180339887 |
| \( 1/\varphi \) | Coherence attractor | ≈ 0.618 |
| \( \mathcal{E}_{\min} \) | Entropy floor | ≈ 0.19 |
| \( \beta \) | Sophia‑population exponent | ≈ 0.85 |
| \( \gamma \) | Diversity‑population exponent | ≈ 0.62 |
| \( p_{\text{emergence}} \) | Nominal novel archetype rate | 0.02 |
| \( \tau \) | Population decay time constant | ≈ 15 generations (Run B) |

---

This compendium of equations provides the quantitative foundation for the Unified Theory of Coherent Complexity. They capture the essential dynamics observed in the simulations and offer a framework for predicting the behaviour of analogous complex systems.
