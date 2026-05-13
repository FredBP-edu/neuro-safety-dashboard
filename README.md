# 🧠 Neuro-Safety Dashboard
> **Biological Telemetry & AI Usage Self-Simulation**

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://pages.github.com/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)

## 🌐 Overview
The **Neuro-Safety Dashboard** is a self-simulation tool designed to help humans understand the biological limits of AI interaction. While AI can process information at near-infinite speeds (Algorithmic Time), the human brain is bound by a biological bottleneck of roughly **60 bits per second** for conscious processing. 

This tool visualizes the "physics" of cognitive load, metabolic debt, and the risk of **Jacksonian Dissolution**—the state where high-velocity AI interaction bypasses our critical auditing capacity, leading to Automation Bias, systemic errors, and a measurable collapse in creative diversity.

## 🚀 Key Features
* **Dynamic 60-Bit Funnel:** Watch in real-time as your "Effective Capacity" shrinks based on circadian rhythms and cognitive exhaustion.
* **Physics-Based Simulation:** Experience how high-complexity outputs and stochasticity cause cognitive "bouncing," representing rejected information (Surprisal) when capacities are exceeded.
* **Metabolic Load Tracking:** Visualize the non-linear accumulation of lpFC (lateral prefrontal cortex) Glutamate and its impact on your Vagal Brake.
* **Diversity Collapse (Atrophy) Warning:** Track your risk of "Strategic Homogenization," predicting when your unique human variance is being replaced by the algorithmic mean.
* **Internationalized Safety Protocols:** Localized guidance and UI in **English, French, German, and Spanish**.

## 🧪 Core Concepts
* **TSF (Task Switching Frequency):** The speed at which you oscillate between different cognitive contexts or prompt responses. High TSF accelerates metabolic exhaustion.
* **CLN (Audit Latency):** The actual high-resolution time you have to consciously audit an AI output before the next interaction.
* **Stochasticity (Surprisal):** Based on the Free Energy Principle, this multiplier accounts for the difference between predictable data formatting and high-entropy creative ideation.
* **Metabolic Debt:** The biological tax paid by the brain to resolve epistemic uncertainty, which compounds exponentially under high loads.

---

## 🧮 Mathematical Model & Formulas
The dashboard operates on a strict neuro-computational model that calculates the friction between AI throughput and human biological capacity.

### Variables
* **$TSF$**: Task Switching Frequency (Prompts/hour)
* **$Tokens$**: Output Complexity
* **$S$**: Stochasticity / Surprisal Multiplier (1.0 to 4.0)
* **$H$**: Time of Day (8.0 to 22.0 Hours)

### 1. Metabolic Debt Calculation
Metabolic debt scales non-linearly to reflect the exponential burden of context-switching and high-entropy data on working memory.

**TSF Debt (lpFC Glutamate proxy):**
$$Debt_{TSF} = \left(\frac{TSF}{40}\right)^{1.2} \times 40$$

**Complexity Debt (Epistemic Tax):**
$$Debt_{Comp} = \left(\frac{Tokens}{1500}\right)^{1.2} \times 15 \times \sqrt{S}$$

**Circadian Tax:**
$$Tax_{Circ} = \max(0, H - 8) \times 2.5$$

**Total Metabolic Debt:**
$$Debt_{Total} = Debt_{TSF} + Debt_{Comp} + Tax_{Circ}$$

### 2. Effective Capacity ($C_{eff}$)
Your real-time biological processing limit. The base human ceiling is 60 b/s, which degrades as metabolic debt accumulates against a physiological constant ($K = 220$). A hard floor of 5 b/s ensures the system never hits zero capacity.
$$C_{eff} = \max\left(5, 60 \times \left(1 - \frac{Debt_{Total}}{220}\right)\right)$$

### 3. AI Throughput Pressure
The velocity of information hitting your biological funnel. To account for the "Hallucination Tax" (the effort required to verify non-deterministic output), we assign a weight of **24 bits per token**, scaled by the Stochasticity multiplier.

**Audit Latency (CLN):**
$$CLN = \frac{3600}{TSF}$$

**Throughput (Bits/Second):**
$$Throughput = \left(\frac{Tokens \times 24}{CLN}\right) \times S$$

### 4. Systemic State & Atrophy Risk
The primary neuro-state (Traffic Light System) is determined by the **Load Ratio** (Throughput vs. Capacity). 
$$Ratio_{Load} = \frac{Throughput}{C_{eff}}$$

* **GREEN (Ventral Vagal Safety):** $Ratio \le 1.0$ AND $Debt \le 60$
* **AMBER (Sympathetic Mobilization):** $Ratio > 1.0$ OR $Debt > 60$
* **RED (Jacksonian Dissolution):** $Ratio > 2.0$ OR $Debt > 100$
* **PURPLE (Dorsal Vagal Shutdown):** $Ratio > 4.0$ OR $Debt > 150$

**Diversity Collapse Risk:**
When $Ratio_{Load} > 1.0$, the brain begins to outsource cognition to the machine. This scales up to a maximum **10.7%** reduction in collective idea variance (based on empirical data from Doshi & Hauser).
$$Risk_{Atrophy} = \min(10.7, (Ratio_{Load} - 1) \times 3.5)$$

---

## 🛠 How to Use
1.  **Adjust Frequency:** See how "bursty" usage impacts your biological processing limits.
2.  **Select Complexity & Stochasticity:** Observe how reading simple data differs from auditing high-entropy creative ideation. 
3.  **Find the Optimal Balance:** Click the **Set to Optimal** button to automatically calculate the maximum frequency you can sustain safely based on your current complexity, time, and entropy settings.
4.  **Set Time of Day:** Observe how your biological capacity "throttles" naturally in the evening due to circadian rhythms.
5.  **Follow Protocols:** If you hit the **Warning**, **Critical**, or **Failure** zones, follow the designated A-F protocols to recover your predictive integrity.

## 📖 Deep Dive
This tool translates the theoretical architecture found at [Engineering Trust: The Architecture of Cognitive Governance](https://engineeringtrust.substack.com/p/the-architecture-of-cognitive-governance) into a tangible UI. We highly recommend reading **Part 5** to understand the deeper neuro-biological research grounding the protocols, the 60-bit limit, and the consequences of "Biological Throttling."

---
*Disclaimer: This is a simulation tool based on neuro-computational research (Wiehler, Porges, Friston). It is intended for educational and self-awareness purposes, not as a clinical diagnostic tool.*
