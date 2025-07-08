# Outcomes of Open Cohen vs. Lich-Gregoir Ureteral Reimplantation for Pediatric VUR

Dataset and scripts related to a multicenter retrospective study comparing the mid- to long-term outcomes of two open ureteral reimplantation techniques (Cohen and Lich-Gregoir) in children with unilateral dilating vesicoureteral reflux (VUR).

---

##  Purpose

To compare the incidence and identify predictors of late surgical outcomes following open ureteral reimplantation (OUR) for primary dilating vesicoureteral reflux (VUR) (grades III–V), and to assess the associated healthcare burden.

---

## Study Population

- **Design**: Multicenter retrospective cohort study (5 institutions)
- **Statistical robustness**: 
  - Propensity score-matched comparison using 14 covariates to minimize treatment bias
  - Rosenbaum’s sensitivity analysis confirmed findings were robust against hidden confounding
- **Participants**: 441 children with **primary unilateral dilating VUR (grades III–V)** with 127 matched pairs (n=254)
- **Inclusion criteria**:
  - aged ≥1-year
  - Underwent open ureteral reimplantation (Cohen or Lich-Gregoir) (June 2010– September 2022)
  - ≥1-year postoperative follow-up
- **Exclusion criteria**:
  - Had secondary VUR
  - Had repeated or tapering reimplantation
  - Had bladder and bowel dysfunction
  - Had posterior urethral valves
  - Had previous bladder surgery
  - Had reflux-related anomalies (ureteroceles, duplex systems, megaureter, and ectopic ureter)

---

##  Results Summary

- **Postoperative Pain (Day 1)**: Significantly higher in the Cohen group
- **VUR or UTI Recurrence**: Recurrence rates were slightly higher than previously reported values; No significant difference between groups 
- **postoperative outcomes**:
  - Higher rates compared to current and historical literature
  - Causes included broader reporting criteria, severe surgical indications, and a lack of standard surgical protocol across centers
  - Increased incidence of contralateral reflux and short-term bowel restriction in Cohen group (Weak association)
  - Obstruction was more frequent in the Lich-Gregoir group (Strong association)
- **Genitourinary Readmissions and visits**:
  - Remarkably higher than previously reported
  - Cohen group had more GU-related follow-up care
  - Causes included logistical constraints (e.g., travel for stent removal), management for complications (contralateral reflux, ureteral injury, voiding dysfunction, and incision infection), procedural factors (absence of stenting, prolonged catheterization, and shorter hospitalization)
- **Reoperation Rates**:
  - Low overall (approximately 4-5%) and comparable between groups
  - Driven mainly by recurrent infections and severe complications
- **Key Predictors**:
  - Surgical technique was a strong predictor of both obstruction (Lich‒Gregoir) and readmission burden (Cohen)
  - Other predictors for complications included operative time, catheterization, hospitalization, stenting status:
      - Shorter operative times were related to contralateral reflux, while longer durations were linked to bowel restriction.
      - Shorter catheterization increased risks of obstruction, bowel restriction, and incision bleeding, whereas longer durations were related to higher rates of readmissions/ER visits.
      - Shorter hospital stays were linked to bowel restriction and bleeding, while longer stays increased risks of obstruction, incision infection, 30-day ER visits, and VUR reoperation.
      - Absence of stenting raised risks of bowel restriction, incision infection, and readmissions/ER visits.
  - Other predictors for healthcare burden (readmissions and visits) included contralateral reflux, ureteral injury, voiding dysfunction and incision infection.
---

##  Repository Structure

```bash
Outcomes-cohen-vs-lichgregoir/
├── data/
│   └── dataset.csv            # De-identified patient-level data
├── scripts/
│   └── analysis.R             # Statistical analysis script
├── results/
│   ├── model_output/          # Tables and output summaries
│   └── figures/               
├── README.md                  # Project documentation
│
└── .gitignore
