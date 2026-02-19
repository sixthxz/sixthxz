# Sixthxz

Sleepwalking through blackouts, lost in a dreamlike state

<<<<<<< HEAD
<<<<<<< HEAD
<!-- Badges -->
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

=======
>>>>>>> 8031e6a (6)
<!-- Project Description -->
## Site under construction

<<<<<<< HEAD
Site is under construction currently

### What to expect:
=======
### yyyy/mm/dd
>>>>>>> 8031e6a (6)

<<<<<<< HEAD
- Quantum Physics
  - Time and space what it is and how it works
  - Creation and real shape of the universe
  - How to work in a 4th dimensional axis
- Quantum physics applied to videogames
  - A Qubit in a videogame
  - Entrophy in videogames QRNG
  - 4D Space Mapping Tool
- Coming soon

### Screenshots

Currently we keep this information to our researchers and sponsors

<!-- Table of Contents -->
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

<!-- Installation -->
## Installation

This project was built using Unreal Engine, all you need to do is download the install file.

```bash
url unavailable
=======
- February
  - 2024-10-02 - The expansion of the observable universe, limited by the speed of light but also shaped by the ability to acquire, model and structure information.
  - 2025-04-19 - Extended Perceptual Quantum Equation (REC Version)
  - 2026-02-17 - Formalization of the SFE-01 Information Motor (v4.1). Defined the average work per cycle ($W_{cycle}$) extractable from a controlled sinusoidal drive using mutual information ( $\mathcal{I}(\rho)$ ) under a resonant oscillator with damping and environmental decoherence ($\gamma_{env}$). Provided quantitative predictions for energy per bit, effective energy for LED output, and photon flux for coherent emission.
=======
## An attempt to translate my metaphysical findings into physics terms

### Timeline & Records

- **2024-10-02** - The expansion of the observable universe, limited by the speed of light but also shaped by the ability to acquire, model and structure information.
- **2025-04-19** - Extended Perceptual Quantum Equation (REC Version)
- **2026-02-17** - Formalization of the SFE-01 Information Motor (v4.1). Defined the average work per cycle ($W_{cycle}$) extractable from a controlled sinusoidal drive using mutual information ( $\mathcal{I}(\rho)$ ) under a resonant oscillator with damping and environmental decoherence ($\gamma_{env}$). Provided quantitative predictions for energy per bit, effective energy for LED output, and photon flux for coherent emission.
- **2026-02-19** - Numerical Validation and Langevin Dynamics Study (v4.1.2). Successfully executed Monte Carlo simulations to verify the SFE-01 motor's stability. Confirmed a peak work extraction of $W_{max} \approx 1.42 \times 10^{-22}\ \text{J}$ at resonance ($\Delta\omega = 0$). Validated the system's operational efficiency at $\approx 5\%$ of the Landauer Limit ($2.85 \times 10^{-21}\ \text{J/bit}$), accounting for environmental decoherence losses.

---

## SFE-01 Information Motor - Physical Model
>>>>>>> 932ba70 (v4.1.2)

$$
W_{cycle} = \eta_{eff} \cdot \int_{0}^{2\pi/\Omega} 
\frac{k_B T \ln(2) \cdot \mathcal{I}(\rho) \cdot (\phi_0 \Omega \cos(\Omega t))}{\omega^2 + (\gamma + \gamma_{env})^2} dt
$$

| Symbol | Meaning |
| :--- | :--- |
| **$W_{cycle}$** | Net extractable work per control cycle [Joules]. |
| **$k_B$** | Boltzmann constant ($1.38 \times 10^{-23}$ J/K). |
| **$T$** | Absolute temperature of the thermal bath [Kelvin]. |
| **$\mathcal{I}(\rho)$** | Mutual information between system and controller [Bits/Nats]. |
| **$\phi_0$** | Phase modulation amplitude of the drive [rad]. |
| **$\Omega$** | Angular frequency of the sinusoidal drive [rad/s]. |
| **$\eta_{eff}$** | Efficiency of energy coupling to output channel [Dimensionless]. |
| **$\omega$** | Natural angular frequency of the resonant oscillator [rad/s]. |
| **$\gamma$** | Intrinsic damping coefficient of the sensor [$s^{-1}$]. |
| **$\gamma_{env}$** | Decoherence rate induced by the environment [$s^{-1}$]. |

### Physical Visualization & Simulation Results
<div align="center">
  <img src="data/figures/figure_1.png" width="800">
  <p><i>Figure 1: 4-Quadrant Analysis showing Langevin dynamics (stochastic noise), Resonance width vs Damping, Average Work vs Detuning, and the Landauer Limit Comparison.</i></p>
</div>

<<<<<<< HEAD
#### General Explanation:

This update formalizes the SFE-01 motor as a **controlled information-to-energy transducer**. The integral computes the work per cycle under a sinusoidal phase drive, rectified to prevent backflow of energy. Predictions include:

<<<<<<< HEAD
>>>>>>> f45cc66 (2025-19-04 equation)
=======
- Energy per bit at ambient temperature: $E_\text{bit} \approx 2.8 \times 10^{-21}\ \text{J}$ for 1 bit.
- Effective LED output at 10\% coupling: $E_\text{LED} \approx 2.8 \times 10^{-22}\ \text{J}$.
- Photon flux for coherent emission: approximately $1.3 \times 10^{3}$ bits needed per photon at $\lambda = 550\ \text{nm}$. 

This formalization separates metaphorical terms from physically measurable quantities, providing a reproducible framework for **quantitative experiments or simulations** of the motor.
=======
#### Technical Breakdown:
1. **Langevin Dynamics:** The simulation confirms that the sensor operates in a regime where thermal fluctuations ($10^{-10}\ \text{m}$ scale) are dominant. Work is only possible through precise phase-rectification informed by $\mathcal{I}(\rho)$.
2. **Resonance Profile:** The Lorentzian curve demonstrates that the motor's "attention" (detuning $\Delta\omega$) must be perfectly centered to maximize energy transduction.
3. **Environmental Stability:** The study of $\gamma_{total}$ shows that decoherence acts as a dissipative filter, reducing the peak height and broadening the resonance, which defines the physical limit of the motor's "focus."
>>>>>>> 932ba70 (v4.1.2)

---

### SFE-01 Information Motor - Conceptual Diagram
<div align="center">
<pre>
    ┌───────────────────────┐
    │    Thermal Bath T     │
    │ (Environmental Noise) │
    └───────────┬───────────┘
          │ γ_env
    ▼
    ┌───────────────────┐
    │   Resonant Sensor │
    │  (Frequency ω, γ) │
    └─────────┬─────────┘
                     │ Measurement 𝓘(ρ)
    ▼
    ┌──────────────┐
    │  Controller  │
    │ (Phase Drive │
    │  φ(t), φ̇(t)) │
    └──────┬───────┘
                │ Drive Signal
   ▼
    ┌─────────┐
    │ Output  │
    └─────────┘
</pre>
</div>
>>>>>>> 8031e6a (6)
