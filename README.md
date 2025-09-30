# Task 07 – Ethical Implications of Decision Making  

### 📌 Project Overview  
This project explores **LLM-assisted decision making in sports analytics**, focusing on the **English Premier League (2024/25)** dataset.  
The main goal was to evaluate **one high-impact attacker** and **one reliable chance creator** using descriptive statistics, LLM-generated narratives, and rigorous verification pipelines.  

The project emphasizes:
- **Ethics** – transparency, fairness, accountability of AI in decision support.  
- **Reliability** – validation of all LLM responses with Python code & statistical checks.  
- **Reproducibility** – complete scripts, outputs, and lineage are archived.  

---

### 🎯 Purpose  
As a coach or performance analyst, the objective is to identify:  
1. **Attacker** → consistent goal output (measured by Goals, GA/90, conversion).  
2. **Chance Creator** → build-up & final-third influence (measured by SCA Proxy, Chance Creation, CTS).  

---

### 📊 Key Findings  
- **Top Scorer:** Mohamed Salah (29 goals) – CI confirms significance over Isak & Haaland.  
- **SCA Proxy Leader:** Brennan Johnson (875) – consistent creativity over 2,000+ mins.  
- **Chance Creation Leader:** Joël Veltman (726) – unusually high for a defender, deep-lying playmaker profile.  
- **High CTS but Low Goals:** Timo Werner – facilitator role, not finisher.  

---

### ✅ Recommendations (Risk-Tiered)  
- **Low Risk (Operational):** Train finishing drills with Brennan Johnson to better convert created chances.  
- **Medium Risk (Investigatory):** Test Joël Veltman in set-piece & crossing schemes during friendlies.  
- **High Risk (Strategic):** Consider acquisition of a high-conversion striker; requires HR/legal review.  

---

### ⚖️ Ethical & Legal Considerations  
- **LLM Transparency:** Raw outputs archived; all edits annotated.  
- **Bias Risks:** Attackers dominate goal metrics; defenders undervalued unless CTS/DCI considered.  
- **Fairness:** Position-specific benchmarks applied (attackers vs defenders).  
- **Reproducibility:** All code, prompts, outputs, and random seeds documented in GitHub.  
- **Governance:** Human-in-the-loop required for high-stakes recruitment.  

---

### 📂 Repository Structure  
Task_07_Ethical_Implications_of_Decision-Making/
├─ Dataset/
│  └─ epl_player_stats_24_25.csv
├─ outputs/
│  ├─ player_summary.csv
│  ├─ top_scorers.csv
│  ├─ top_assists.csv
│  ├─ top_clean_sheets.csv
│  ├─ top_cts.csv
│  ├─ top_sca_proxy.csv
│  ├─ top_sca_proxy_per90.csv
│  ├─ top_chance_creation.csv
├─ Scripts/
│  ├─ EDA.ipynb
│  └─ Verify_LLM.ipynb
├─ Report/
│  └─ TASK07_Report.pdf
└─ README.md




---

### ⚙️ Methods & Validation  
- **Bootstrap CI (5,000 reps)** for uncertainty quantification.  
- **Minutes filters (≥900, ≥1500)** to avoid small-sample bias.  
- **Reproducibility:** `np.random.seed(42)` used for deterministic outputs.  
- **LLM Verification:** Responses checked against CSV exports in `/outputs/verify/`.  

---

### 🔗 References  
- Premier League Player Dataset (Kaggle, 2024/25 season).  
- Syracuse University – IST Research Task 07 guidelines.  

---

### 👤 Author  
**Akanksh Shetty**  
Graduate Student – Syracuse University (MS in Information Systems + Data Science)  
📧 Contact: [Insert your email if comfortable]  
🔗 GitHub: [Akanksh171717](https://github.com/Akanksh171717)  

---
