# Outcomes of Open Cohen vs. Lich-Gregoir Ureteral Reimplantation for Pediatric VUR

Dataset and scripts related to a multicenter retrospective study comparing the medium- to long-term outcomes of two open ureteral reimplantation techniques (Cohen and Lich-Gregoir) in children with unilateral dilating vesicoureteral reflux (VUR).

---

##  Purpose

To compare the incidence and identify predictors of late surgical outcomes following ureteral reimplantation (UR) for dilating vesicoureteral reflux (VUR) (grades III–V), assessing the need for differential follow-up.

---

## Study Population

- **Design**: Multicenter retrospective cohort study (5 international institutions)
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
- **VUR or UTI Recurrence**: Higher recurrence observed in the Cohen group
- **postoperative outcomes**:
  - Increased incidence of contralateral reflux in Cohen group
  - Obstruction more frequent in the Lich-Gregoir group
- **Genitourinary Readmissions and visits**:
  - Cohen group had more GU-related follow-up care
  - Common causes included voiding dysfunction and incision infections
- **Reoperation Rates**:
  - Low overall (approximately 3%) and comparable between groups
  - Driven mainly by obstruction (Lich-Gregoir) or VUR recurrence (Cohen)
- **Key Predictors**:
  - Surgical technique was a strong predictor of both obstruction and readmission burden
  - Voiding dysfunction, surgical site issues, and contralateral reflux were also associated with adverse outcomes

---

##  Repository Structure

```bash
Outcomes-cohen-vs-lichgregoir/
├── data/
│   └── dataset.csv            # De-identified patient-level data
├── scripts/
│   └── analysis.R             # Statistical analysis script
├── results/
│   ├── model_output/          # Tables and output summaries, under preparation
│   └── figures/               
├── README.md                  # Project documentation
│
└── .gitignore

---

##  Test