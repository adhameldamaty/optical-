# OPTOELECTRONICS

## ASSOC. PROF. SAMEH A. NAPOLEON 2020-2021

---

## OPTICAL SOURCES

### Optical Fibre Joining (Splices)
- Critical points in the optical fiber network.
- They affect the quality and lifetime of the link.
- High quality = low splice loss, tensile strength, stable over the design life of the system.
- Two technologies for splicing:
  - **Fusion**
  - **Mechanical**

---

## LIGHT PRODUCTION
- Light is produced through the rapid change of state of an electron from a high energy state to a lower stable state.
- Emission of light can be:
  - **Spontaneous**
  - **Stimulated** (by the presence of another photon of the right energy level).

### Considerations with Optical Sources
- Physical dimensions to suit the fiber.
- Narrow radiation pattern (beam width).
- Linearity (output light power proportional to driving current).
- Ability to be directly modulated by varying driving current.
- Fast response time (wide band).
- Adequate output power into the fiber.
- Narrow spectral width (or line width).
- Stability and efficiency.
- Driving circuit issues.
- Reliability and cost.

---

## SPONTANEOUS EMISSION
- Spontaneous emission is the random generation of photons within the active layer of the LED.
- The emitted photons move in random directions; only a certain percentage enter the fiber.
- Many photons are absorbed by LED materials, dissipating energy as heat.
- When an electron transitions from a high energy state, it emits a photon randomly in direction and phase, with wavelength determined by energy release.

---

## STIMULATED EMISSION
- An electron in a high energy (excited) state can be **stimulated** by an incident photon to emit another photon.
- Conditions for stimulated emission:
  - Identical energy → Identical wavelength → Narrow linewidth.
  - Identical direction → Narrow beam width.
  - Identical phase → Coherence.
  - Identical polarization.

---

## HOW TO PROVIDE ENERGY TO AN ELECTRON?
- **Heat**
- **Electrical Discharge**
- **Electric Current**
- **Chemical Reaction**
- **Biological Reactions (Bioluminescence)**
- **Absorption of Light**
- **Nuclear Radiation**

### Heat
- One of the most common ways to boost an electron into a higher energy state.

### Electrical Discharge
- When electric current passes through a gas, energy ionizes the gas.
- Injected energy excites electrons, and light is emitted when they return to lower energy states (fluorescent light).

---

## LIGHT EMITTING DIODES (LEDS)
### Forward Biasing:
- Electrons move towards the junction and recombine with holes.
- This recombination emits energy as electromagnetic radiation (light), depending on the energy gap.
- This process is called **Injection Luminescence**.
- Proper material selection leads to visible light emission.

### Reverse Biasing:
- When exposed to light, the junction absorbs photons, causing ionization.
- This creates electron-hole pairs and generates a current, making a **light detector**.

---

## CONSTRUCTION AND OPERATION OF LEDS
- LED is a forward-biased **p-n junction**.
- Free electrons from the **conduction band** recombine with holes in the **valence band**, emitting light.
- The wavelength of emitted light is **inversely proportional** to the band gap energy.

### Wavelength Formula:
```math
\lambda = \frac{h \cdot c}{E_{ph}}
```
Where:
- \( \lambda \) = Wavelength in microns
- \( h \) = Planck’s constant = \( 6.63 × 10^{-34} \) = \( 4.14 \times 10^{-15} \) eV/s
- \( c \) = Speed of light = \( 3 × 10^8 \) m/s
- \( E_{ph} \) = Photon energy in eV

---

## BANDGAP ENERGY AND POSSIBLE WAVELENGTH RANGES
| Material Formula | Wavelength Range (\( \mu m \)) | Bandgap Energy (eV) |
|----------------|------------------|------------------|
| Indium Phosphide (InP) | 0.92 - 1.35 | 1.35 |
| Indium Arsenide (InAs) | 3.6 | 0.34 |
| Gallium Phosphide (GaP) | 0.55 | 2.24 |
| Gallium Arsenide (GaAs) | 0.87 | 1.42 |
| Aluminium Arsenide (AlAs) | 0.59 | 2.09 |
| Gallium Indium Phosphide (GaInP) | 0.64 - 0.68 | 1.82 - 1.94 |
| Aluminium Gallium Arsenide (AlGaAs) | 0.8 - 0.9 | 1.4 - 1.55 |
| Indium Gallium Arsenide (InGaAs) | 1.0 - 1.3 | 0.95 - 1.24 |
| Indium Gallium Arsenide Phosphide (InGaAsP) | 0.9 - 1.7 | 0.73 - 1.35 |

---

## SEMICONDUCTOR LIGHT-EMITTING DIODES
- **LEDs emit incoherent light** due to spontaneous emission.
- **LDs emit coherent light** with a fixed-phase relationship.
- LEDs are mainly used for **multimode** systems.
- LDs are typically used for **single-mode** fiber systems.

---

## TYPES OF LED
- **Surface-emitting LED (SLED)**
- **Edge-emitting LED (ELED)**

---

## LED PERFORMANCE DIFFERENCES
1. **Short-distance (0 - 3 km), low-data-rate systems:**
   - SLEDs & ELEDs preferred.
   - SLEDs operate efficiently up to 250 Mb/s.
   - SLEDs mainly used in multimode systems.

2. **Medium-distance, medium-data-rate systems:**
   - ELEDs preferred.
   - Modulated at rates up to 400 Mb/s.
   - Used in both single-mode and multimode systems.

3. **Long-distance, high-data-rate systems:**
   - Superluminescent diodes (SLDs) used.
   - Operate at bit rates **> 400 Mb/s**.

---

📌 **تم تحويل محتوى الملف إلى Markdown مع تنظيم العناوين، القوائم، والمعادلات. يمكنك نسخه ولصقه في StackEdit أو أي محرر يدعم Markdown!** 🚀
