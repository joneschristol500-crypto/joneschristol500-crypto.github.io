---
title: Glucose-Insulin Control System
excerpt: A biomedical simulation tool for studying glucose-insulin dynamics and control strategies.
header:
  overlay_color: "#0b5563"
---

**Developer** · Independent Project · [View the code](https://github.com/joneschristol500-crypto/Glucose-Insulin-App)

This project explores how different control strategies could keep a patient's blood glucose in range through a day of meals. It combines an interactive Streamlit application with Jupyter research notebooks.

## What it does

- **Dynamical model:** a minimal glucose-insulin ODE system with exponential meal-absorption disturbances.
- **Control strategies:** an open-loop baseline, basal-bolus insulin therapy, and PID closed-loop control with integral anti-windup and safe output limits.
- **Clinical metrics:** Time in Range, hypoglycemia and hyperglycemia analysis, and glucose variability.
- **Patient presets:** healthy, insulin-resistant, Type 1 Diabetes, and Type 2 Diabetes.

## How it's built

- **Language and interface:** Python and an interactive Streamlit app with real-time simulation and parameter tuning
- **Research:** four Jupyter notebooks covering model checks, open-loop meals, closed-loop PID, and sensitivity sweeps
- **Testing:** pytest

<figure class="poster-figure">
  <a href="{{ '/assets/images/glucose-insulin/simulation-illustration.jpg' | relative_url }}"><img src="{{ '/assets/images/glucose-insulin/simulation-illustration.jpg' | relative_url }}" alt="Line chart of blood glucose over one day with three meals, comparing open-loop and PID closed-loop control against the 70 to 180 mg/dL target range" loading="lazy"></a>
  <figcaption>Illustration of one simulated day with three meals, comparing open-loop and PID closed-loop control. It was generated from the minimal model and is not a screenshot of the app or real patient data.</figcaption>
</figure>
