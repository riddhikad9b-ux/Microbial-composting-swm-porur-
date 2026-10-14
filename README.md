# Bio-Inoculated Microbial Composting & Municipal SWM Scaling Package
## Porur Pilot (50-Tonne) · Greater Chennai Corporation (GCC) Submission

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Policy Alignment](https://img.shields.io/badge/SWM%20Rules-2016%20Compliant-green.svg)](#regulatory--policy-alignment)

---

## 📌 Project Overview

This repository contains the complete analytical workflow, experimental data analysis, financial models, and field execution package for the **Phase B Microbial Composting Pilot** and **Phase C Municipal Scaling Proposal** in Porur, Chennai.

The project demonstrates a decentralized, bio-inoculated **Micro Composting Centre (MCC)** model designed to process municipal organic waste efficiently, safely, and cost-effectively, fully aligned with the **Solid Waste Management (SWM) Rules 2016**, **Fertilizer Control Order (FCO)**, and **Greater Chennai Corporation (GCC) Bye-Laws 2019**.

---

## 📊 Key Analytical & Experimental Findings

### 1. Mass Balance & Dry-Matter Stabilization
* **Control Group (Uninoculated)**: Sustained a mean dry-matter loss of **-5.54%**.
* **Inoculated Group (*Bacillus subtilis* + *Pseudomonas sp.*)**: Accelerated organic stabilization with a controlled mean mass change of **-0.44%**.

### 2. Thermophilic Kinetics & Pathogen Destruction
* **Sanitation Threshold**: Sustained core temperatures \\(\ge 55^\circ\text{C}\\) for at least 3 consecutive days to eliminate enteric pathogens (*E. coli*, *Salmonella*) and weed seeds.
* **Pilot Unit B1 Validation**: Reached **56.5°C on Day 7** and peaked at **58.2°C on Day 14**, verifying thermal pathogen destruction.

### 3. Financial & Economic Model
* **Total Estimated Expenditure**: **₹2,28,500.00** for a 50-tonne pilot.
* **Cost Per Tonne**: **₹4,570.00 / tonne** (fits comfortably within the provisional municipal envelope of ₹2.5–5.0 Lakhs).
* **Budget Breakdown**:
  * Site Prep & HDPE Containment Pad: **₹65,000.00**
  * Transport & Authorized Reject Disposal: **₹60,000.00**
  * Laboratory QA/QC & Heavy Metal Screening: **₹35,000.00**
  * Rotary Trommel Screening (4mm/10mm): **₹27,500.00**
  * Labour & Health Supervision (with PPE): **₹25,000.00**
  * Excavator & Loader Rental: **₹16,000.00**

### 4. Automated Laboratory QA/QC Compliance
* **`PRR-ORG-01` (Organic Fraction)**: pH 7.2, C/N 18.5:1, Lead 15.2 mg/kg, Pathogens Absent \\(\rightarrow\\) **Route 1: Approved for Composting**.
* **`PRR-SLT-01` (Silt/Fines Fraction)**: Lead 155.0 mg/kg (violates 100 mg/kg FCO/SWM limit), Pathogens Present \\(\rightarrow\\) **Reject: Isolated for Authorized Landfill Disposal**.

---

## 🏛️ Regulatory & Policy Alignment

* **Solid Waste Management Rules 2016 & FCO Standards**: Mandates final C/N ratio \\(\le 20:1\\), pH 6.5–7.5, and Lead \\(\le 100\text{ mg/kg}\\).
* **Tamil Nadu State SWM Policy (2018) & GCC Bye-Laws (2019)**: Enforces 100% source segregation, door-to-door collection via Battery Operated Vehicles (BOVs), and neighborhood Micro Composting Centres (MCCs).
* **Madras High Court Full Bench Ruling**: Landmark judicial precedent confirming that establishing MCCs on municipal public land/parks is legally permissible and serves essential public health functions.

---

## 🚀 Phase C Operational Plan & Field Blueprint

1. **Site Engineering**: Impermeable High-Density Polyethylene (HDPE) pad with concrete base and peripheral leachate sumps with recirculation.
2. **Equipment Schedule**: Excavator/loader for windrow turning (Days 0–28), rotary trommel screening (Days 28–35).
3. **Worker Safety**: PPE allocation (N95 respirators, heavy-duty gloves, safety boots) and health tracking per SBM-Gramin and TN labor guidelines.

---

## 📂 Repository Layout

```text
microbial-composting-swm-porur/
│
├── README.md                          # Project documentation
├── LICENSE                            # MIT License
│
├── data/
│   └── phase_b_experiment.xlsx        # Experimental lab and cost tracking dataset
│
├── scripts/
│   ├── run_lab_compliance.py          # Automated compliance decision matrix
│   ├── run_fixed_cost.py              # Financial cost tracking & data cleaning
│   └── generate_dashboard.py          # 4-module integrated visualization dashboard
│
├── visualizations/
│   ├── phase_b_composting_dashboard.png
│   ├── cost_breakdown_analysis-v2.png
│   └── compliance_routing_summary.png
│
└── docs/
    ├── Phase_C_Operational_Plan.md    # Municipal DPR execution package
    └── Research_Report_TN_SWM.md      # Literature & policy synthesis report
```

---

## 💻 How to Run the Scripts

### 1. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

### 2. Generate Integrated Executive Dashboard
```bash
python scripts/generate_dashboard.py
```

### 3. Run Automated Laboratory Compliance Matrix
```bash
python scripts/run_lab_compliance.py
```

---

## 📜 Citation & License

This project is open-source under the **MIT License**.

```bibtex
@techreport{PorurMicrobialComposting2026,
  title={Decentralized Bio-Inoculated Microbial Composting: Phase B Pilot Validation & Phase C Scaling Package for Porur Zone},
  author={Porur Environmental Engineering Working Group},
  institution={Greater Chennai Corporation (GCC)},
  year={2026}
}
```
```

---

