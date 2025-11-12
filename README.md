<!-- Banner -->
<h1 align="center">ANALYZING-THE-E-WASTE-AWARENESS</h1>
<p align="center">
  <b>A Data-Driven Behavioral Study Using the Theory of Planned Behavior — SEM Analysis</b>  
</p>

This repository contains the **project report**, **data**, and **analysis files** for the study  
📘 **“Analyzing The E-Waste Awareness: A Data-Driven Behavioral Study Using Theory of Planned Behavior”**.  
The project utilizes **Structural Equation Modeling (SEM)** to analyze behavioral factors influencing e-waste recycling among urban Indian consumers.

---

## 📌 Project Overview

This study uses the **Theory of Planned Behavior (TPB)** and **Structural Equation Modeling (SEM)** to examine the psychological and practical drivers of e-waste recycling behavior.  
The analysis investigates **attitudes**, **subjective norms**, **perceived behavioral control**, **intention**, and **actual recycling behavior** using data collected from 512 respondents.

### Key components included:
- Complete project report (PDF)
- Survey instrument / questionnaire
- Cleaned dataset for SEM
- Jupyter notebook with SEM workflow
- Exported model fit statistics and parameter estimates
- Scripts for data preprocessing and analysis

---

## 🎯 Objectives

**Research Objectives**
1. Develop and validate a TPB-based model explaining e-waste recycling intention and behavior.  
2. Design and validate a survey measuring attitudes, norms, perceived control, awareness, and recycling intention.  
3. Identify key psychological determinants influencing e-waste recycling behavior.  
4. Quantify the gap between recycling intention and actual behavior.  
5. Suggest practical recommendations for improving e-waste management awareness and participation.

---

## 🔬 Key Findings

- **Perceived Behavioral Control (PBC)** emerged as the strongest predictor of recycling intention (β ≈ 0.47, p < 0.001).  
- **Intention → Behavior** relation was moderate but significant (β ≈ 0.35), showing an intention-behavior gap.  
- Model fit was satisfactory: **CFI = 0.947**, **RMSEA = 0.048**, **SRMR = 0.041**.  
- Education level moderated the link between intention and actual behavior.  
- Younger participants showed higher environmental attitudes but lower control over recycling opportunities.  

(Refer to the report and notebook for full tables, charts, and interpretations.)

---

## 📂 Repository Structure
```bash
├── Report/
│   └── ANALYZING_THE_E-WASTE_AWARENESS.pdf          # Final project report
├── data/
│   ├── raw_survey_responses.csv                     # Original collected data
│   └── sem_data_cleaned.csv                         # Preprocessed dataset for SEM
├── notebooks/
│   └── Sem_Model_EWaste.ipynb                       # Jupyter notebook for SEM modeling
├── code/
│   ├── preprocessing.py                             # Data cleaning and feature engineering
│   └── sem_analysis.py                              # Model specification and fitting
├── outputs/
│   ├── sem_fit_statistics.csv                       # Model fit indices
│   └── sem_parameter_estimates.csv                  # Path coefficients and loadings
├── figures/
│   └── measurement_model.png                        # Path diagram and visualizations
├── requirements.txt
└── README.md
```
## ✅ Evaluation Metrics

- When reviewing results, check:
- Model Fit: χ², df, p-value, CFI, TLI, RMSEA, SRMR
- Factor Loadings: ≥ 0.50 preferred, significant p-values
- Reliability & Validity: Cronbach’s α, Composite Reliability (CR), Average Variance Extracted (AVE)
- Structural Paths: Standardized coefficients and their significance
- Modification Indices: Apply only theoretically valid changes

---

## 📝 Outputs & Reporting

- sem_fit_statistics.csv — Model fit results for report inclusion.
- sem_parameter_estimates.csv — Factor loadings and path coefficients.
- figures/ — Model visualization and analysis plots.
These files can be directly used in your research paper or presentation slides.

---

## 🤝 Contributors
Priyanshu Chouhan		22ad10pr1@mitsgwl.ac.in

Krish Gupta		22ad10kr661@mitsgwl.ac.in

Prateek Batham		22ad10pr632@mitsgwl.ac.in

Pratham Hande	r	22ad10pr656@mitsgwl.ac.in

## Supervised by:
- **Dr. Abhishek Bhatt** (Assistant Professor, CAI Department, MITS)
- **Dr. Vibha Tiwari** (Assistant Professor, CAI Department)
- Approved by: Dr. **Rajni Ranjan Singh** (HoD, CAI Department)

---

## 📜 License

This repository is provided for academic and educational purposes only.
Reproduction or redistribution of any content without permission is prohibited.

---

## ⭐ Acknowledgment

We would like to thank Madhav Institute of Technology and Science (MITS), Gwalior,
for providing the resources and guidance needed to complete this research successfully.

---

© 2025 — Team ANALYZING THE E-WASTE AWARENESS
All rights reserved.
