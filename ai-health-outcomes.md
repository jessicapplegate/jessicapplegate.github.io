# AI & Health Outcomes: Mapping the Rural Digital Divide

> **The Challenge:** Investigating how geographic and infrastructural barriers prevent rural communities from accessing AI-driven healthcare "superstructures."
>
> **The Impact:** Identified that "distance to care" isn't just physical—it’s digital. Provided a data-backed foundation for UX Designers to consider "offline-first" or "low-bandwidth" healthcare interfaces.

---

## ## Overview

* **The Problem:** AI is revolutionizing healthcare, but its benefits are concentrated in urban "superstructures," leaving rural populations behind.
* **The Solution:** A mixed-methods spatial analysis to identify where infrastructure (broadband) and social factors (SES) intersect with health risks.
* **My Role:** Lead Researcher (Directed Research Group, UW).
* **The Toolkit:** `R` (sf, ggplot2), `Overleaf/LaTeX`, `USDA` & `CDC` Datasets.

---

## ## Understand

In this phase, I moved beyond the "what" to the "why" of rural healthcare adoption.

### The Strategic Why
AI models are often trained on urban data. I hypothesized that the **UX of Healthcare** in rural areas is hindered by a geographic disconnect. If a user lives 50 miles from an AI-integrated hospital, the "user journey" for a life-saving diagnosis is fundamentally broken.

### Literature Audit
Performed a deep dive into **25 peer-reviewed papers** to identify existing friction points in rural health tech, tracking all insights in a centralized research repository.

---

## ## Research



### Methodology & Data Rigor
* **Quantitative Analysis:** Loaded and cleaned multi-source public datasets (USDA, CDC, NHANES) using **R**.
* **Controlling for Confounds:** To ensure integrity, I controlled for socioeconomic status (SES) and poverty levels, ensuring findings weren't just a proxy for wealth.
* **Spatial Regression:** Used `sf` and `sfdep` packages to map the correlation between physical distance and health outcomes.

### Research Artifacts
* [**Spatial Regression Analysis**](./link-to-stats) – Statistical proof of the distance-to-care gap.
* [**Research Repository**](./link-to-docs) – Systematic tracking of 25 literature sources.

---

## ## Outcome & Impact

### 1. The "Superstructure" Gap
* **Finding:** Spatial distance from AI-healthcare hubs correlates with heightened health risks.
* **UX Implication:** We cannot assume "Always-On" connectivity. Healthcare UX must be designed for **asynchronous or "store-and-forward"** data transmission.

### 2. The Trust & Adoption Barrier
* **Finding:** Rural populations often resist "big city" healthcare solutions.
* **UX Implication:** AI-driven tools need a **localized Voice and Tone**. Building trust requires UI that feels culturally relevant, not just technically superior.

### 3. Infrastructure as a UX Constraint
* **Finding:** Limited broadband is the primary "gatekeeper" for AI health tools.
* **UX Implication:** **Design for Low-Bandwidth Accessibility.** If an AI tool requires 5G to process an image, it is functionally useless for 20% of the US population.

---

## ## Takeaways

* **Operational Excellence:** Synthesized 25+ academic sources into actionable data visualizations (Choropleth maps and Regression plots).
* **Technical Rigor:** Leveraged **Overleaf/LaTeX** for high-fidelity documentation, ensuring the research was ready for professional publication.
* **The Big Picture:** This project proved that UX Research isn't just about "buttons"—it's about the **Infrastructure of Access.**
