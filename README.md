# JMbdirect Shiny App

## 📖 Overview
The **JMbdirect Shiny App** provides an interactive interface for fitting **joint models for longitudinal and multiple time‑to‑event data**. Joint modeling is widely used in medical research to simultaneously analyze repeated biomarker measurements and survival outcomes, offering deeper insights into disease progression and treatment effects.

This app is built on the **JMbdirect R package** and is designed to make model specification, estimation, and visualization more accessible to clinicians, biostatisticians, and researchers.

---

## ✨ Features
- **Interactive model specification**
  - Define longitudinal and survival submodels with user‑friendly controls.
- **Visualization tools**
  - Plot longitudinal trajectories and survival curves for multiple events.
  - Display bidirectional survival plots for subjects.
- **Mathematical framework**
  - Longitudinal submodel:  
    
$$ y_i(t) = X_i(t)\beta + Z_i(t)b_i + \epsilon_i(t)\$$

  - Survival submodel:  
    
$$h_i(t) = h_0(t) \exp(W_i\gamma + \alpha m_i(t))$$

- **Downloadable results**
  - Export fitted models, plots, and summaries for reporting.

---


