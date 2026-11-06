---
title: Breast Cancer Risk Assessment Platform
excerpt: A full-stack web application that helps women in Ghana and worldwide understand their personal breast cancer risk.
header:
  overlay_color: "#0b5563"
---

**Developer** · Independent Project · [Try the live app](https://breast-cancer-project-dpn4.vercel.app) · [View the code](https://github.com/joneschristol500-crypto/Breast-Cancer-Screening-App)

This application turns clinical risk factors into clear scores, charts, and screening guidance.

## What it does

- **Personalized risk assessment** based on age and BMI, family history, breast density, menopausal status, hormone use history, previous biopsies, and reproductive history.
- **Visual analytics** showing a risk score, a breakdown of contributing factors, and risk timeline projections.
- **Clinical recommendations** for screening and prevention, based on each person's risk profile.

## How it's built

- **Frontend:** React, TypeScript, and Vite, with shadcn/ui components
- **Backend:** Flask REST API in Python
- **Charts:** Matplotlib, generated on the server
- **Testing:** pytest

<figure class="poster-figure">
  <a href="{{ '/assets/images/breast-cancer/model-illustration.jpg' | relative_url }}"><img src="{{ '/assets/images/breast-cancer/model-illustration.jpg' | relative_url }}" alt="Line chart of projected cumulative breast cancer risk from age 30 to 80 for average, moderate, and high-risk profiles" loading="lazy"></a>
  <figcaption>Illustration of risk timeline projections across example profiles. It was generated from the project's model and is not a screenshot of the app or real patient data.</figcaption>
</figure>
