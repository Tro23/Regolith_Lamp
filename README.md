# 🌑 THE REGOLITH LAMP

**Directional Solar Solid-State Luminescent Engine**

[![Status: Stealth](https://img.shields.io/badge/Status-Stealth_R&D-black)](#)
[![License: Proprietary / NC](https://img.shields.io/badge/License-Proprietary_/_NC-red)](#)
[![Architecture: DhaaRn](https://img.shields.io/badge/Architecture-DhaaRn-blue)](#)

> **"The death of the glass bulb. The birth of solid-state lunar infrastructure."**

---

### ⚠️ PROPRIETARY TRADE SECRET NOTICE

**This repository serves strictly as a Source-Available conceptual overview.** The exact PMMA skeleton injection-molding parameters, Total Internal Reflection (TIR) optical curvature calculations, and solar-skin integration methodologies remain heavily restricted trade secrets. **Physical manufacturing of this device from these specifications is strictly prohibited by the attached license.**

---

## Phase 1: The Foundation & Light Engine (Photon Generation)
Before we diffuse the light, we have to create it and manage its heat. By putting the heavy components at the bottom, we lower the center of gravity, making the lamp incredibly stable.



* **Materials:** * **High-Efficacy COB (Chip-on-Board) LEDs:** These pack a massive amount of lumens into a tiny, flat surface area.
  * **Cast Aluminum Base/Heat Sink:** Acts as the structural anchor and pulls heat away from the LEDs into the ground.
* **The Build:** The LEDs are mounted facing perfectly straight up. They are encased in the aluminum base, which sits securely on the concrete or soil of the street corner.

## Phase 2: The Internal Skeleton (Photon Transport)
This is the invisible magic that makes your directional "X" or concave shapes work. We have to pipe the light from the base to the exact emission points without losing energy.



* **Materials:** **Optical-Grade PMMA (Polymethyl Methacrylate / Acrylic)**. It has exceptional light transmittance (up to **92%**) and is highly UV resistant.
* **The Build:** We injection-mold the PMMA into a solid "skeleton" that branches out like a tree. The trunk sits directly over the LED base. The branches reach out into the four corners of your "X" shape.

## Phase 3: The Regolith Skin (Photon Diffusion)
This is the visible, tactile part of the lamp—the frosted, monolithic exterior that gives the soft, lunar glow.

* **Materials:** **Frosted Polycarbonate** or **Recycled Thick-Wall HDPE**.
* **The Build:** This shell is molded to fit perfectly over the PMMA skeleton. However, the shell is only translucent at the specific concave faces pointing down the streets. The rest of the shell is coated internally with a highly reflective, opaque white film to prevent light from bleeding where it isn't wanted.

## Phase 4: The Dark Sky Cap (Power Generation)
The top of the lamp serves two purposes: blocking upward light pollution and capturing solar energy to make the unit **100%** off-grid.



* **Materials:** **Monocrystalline Flexible Solar Skin** and an **Opaque Matte Polymer Cap**.
* **The Build:** The top surface of the "X" shape is angled slightly to shed water and maximize sun exposure. The solar skin is adhered directly to the top, wiring discreetly down the center of the PMMA skeleton to a high-capacity lithium-ion battery hidden in the aluminum base next to the LEDs.

## Phase 5: The Mathematics & Physics of the Regolith
To make this work efficiently, we rely on two core principles of optical physics.

### 1. Total Internal Reflection (TIR)
To ensure the light travels up the clear PMMA skeleton without leaking out the sides, we use TIR. Light will bounce perfectly off the inside walls of the acrylic as long as it hits the boundary (between the acrylic and the air gap before the frosted shell) at a shallow enough angle.



We calculate the Critical Angle ($\theta_c$) using Snell's Law. If the refractive index of PMMA is $n_1$ (approximately **1.49**) and the refractive index of air is $n_2$ (**1.00**), the equation is:

$$\theta_c = \arcsin\left(\frac{n_2}{n_1}\right)$$

Plugging in our materials:

$$\theta_c = \arcsin\left(\frac{1.00}{1.49}\right)$$

This results in a critical angle of approximately **42.2°**.

* **The Engineering Takeaway:** As long as we design the internal curves of the PMMA skeleton so that the LED light beams hit the sides at an angle greater than **42.2°**, **100%** of the light will be trapped and guided straight to your concave frosted panels!

### 2. Illuminance and the Inverse-Square Law
Because the Regolith shell is a diffuser, the light spreads out. We need to calculate how much light actually hits the pavement ($E$, measured in lux). This is governed by the intensity of the source ($I$, in candelas) and the distance to the ground ($d$, in meters).

For a directional, point-like source, the law is:

$$E = \frac{I}{d^2} \cos(\theta)$$

Where $\theta$ is the angle between the light ray and the perpendicular to the surface.

* **The Engineering Takeaway:** Because our concave frosted panels have a large surface area (unlike a tiny bulb), the light acts as an extended source rather than a point source. This drastically reduces harsh shadows and glare on the street, providing a much more uniform distribution of lux across the pavement.
