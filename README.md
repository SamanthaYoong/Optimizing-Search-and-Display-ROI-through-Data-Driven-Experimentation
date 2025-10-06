#  Case Study: Optimizing Search and Display ROI through Data-Driven Experimentation

** Target Role:** Performance Marketing Analyst, Agoda  
**💡 Focus:** Scalable campaign optimization through data modeling and cross-channel experimentation

---

## 1. Context

As part of a simulated marketing analytics project inspired by **Agoda’s performance structure**, I analyzed multi-channel ad performance (Search + Display) to identify optimization opportunities that could:

- Increase **ROI**
- Improve **LTV**
- Reduce **Customer Acquisition Cost (CPA)**

**Objective:**  
Develop a data-driven testing framework that maximizes conversion efficiency while preserving long-term user value.

---

## 2. Data Setup & Tools

**Dataset:**  
Paid search + display campaigns, including:
- CTR (Click-Through Rate)  
- CVR (Conversion Rate)  
- CPC (Cost Per Click)  
- Impressions  
- Spend  
- Revenue  
- User Cohort LTV  

**Tools & Techniques:**
-  **SQL** – Campaign segmentation & performance queries  
-  **Tableau** – Dashboard & visualization  
-  **Excel** – Regression modeling, Budget modeling & ROI analysis  

**Key Metrics Analyzed:**
- CTR  
- CVR  
- ROAS (Return on Ad Spend)  
- CAC (Customer Acquisition Cost)  
- LTV (Customer Lifetime Value)  

---

## 3. Analysis Framework

### a. 🔍 Search Channel (Google/Bing Simulation)

**A/B Experiments:**  
Designed tests for:
- Text ad variations  
- Bidding structures  
- Match types (broad vs. exact)  
- Device types (mobile vs. desktop)

**Findings:**
- Branded keywords → **3× higher CVR**, but lower incremental lift  
- Generic keywords → Lower ROAS, but **35% higher LTV** when remarketed via display  

**Action:**  
Reallocated **20%** of generic keyword budget to **high-LTV segments** and launched **cross-channel retargeting** through display.

---

### b.  Display Channel (Meta/Instagram Simulation)

**Creative Tests:**  
Video vs. Carousel vs. Static

**Visualization:**  
Used **Tableau dashboard** to track spend efficiency and engagement.

**Findings:**
- Carousel ads → **1.8× higher CTR**, but **20% lower CVR** than video  
- Regression model revealed **ROAS drops when ad frequency > 3**

**Action:**  
- Set **frequency cap = 3**  
- Recommended **video-led retargeting** to maximize conversion efficiency  

---

### c.  Modeling & Dashboard

**Python Model:**  
Developed regression model linking:
- ROAS ~ Ad Frequency + Creative Type + Keyword Intent  

**Tableau Dashboard:**  
Enabled marketing managers to:
- Monitor campaign performance in real time  
- Adjust bids dynamically  
- Visualize channel-wise **CPA and LTV**  

---

## 4. Results & Insights

| Metric | Before | After Optimization | Improvement |
|--------|---------|--------------------|-------------|
| **Average ROAS** | 2.3 | 3.4 | +48% |
| **CAC** | \$18.2 | \$12.4 | -32% |
| **CTR (Search)** | 3.5% | 4.7% | +34% |
| **Retargeted LTV** | \$57 | \$77 | +35% |

---

## 5. Key Learnings

-  **Incrementality > short-term ROI:** High-ROAS segments aren’t always long-term profitable.  
-  **Modeling insights** (ad fatigue, keyword intent value) are key for scaling.  
-  **Automation-ready dashboards** drive agile, data-backed marketing decisions.

---

## 6. Relevance to Agoda

| Agoda Focus | My Case Study Alignment |
|--------------|--------------------------|
| Experimentation on search & display | A/B tested multiple creative and bidding strategies |
| Data modeling for optimization | Regression model + LTV-CAC framework |
| Dashboard for account managers | Tableau dashboard for channel visibility |
| Analytical rigor & curiosity | Used SQL, Python, Excel for end-to-end marketing analysis |
| Global, fast-paced team | Simulated cross-channel marketing environment similar to Agoda scale |

---

## 7. Next Steps (If at Agoda)

If I joined Agoda’s **Performance Marketing Team**, I would:

1.  Build **multi-layered LTV models** using Agoda’s booking and repeat visit data.  
2.  Experiment with **automated bidding scripts** informed by real-time conversion data.  
3.  Create dashboards integrating **product + marketing metrics** to link growth decisions with lifetime value.

---

## 📁 Repository Structure (suggested)

```bash
agoda-performance-marketing-case-study/
│
├── data/
│   ├── search_campaigns.csv
│   ├── display_campaigns.csv
│
├── notebooks/
│   ├── search_analysis.ipynb
│   ├── display_modeling.ipynb
│
├── dashboard/
│   ├── tableau_dashboard.twb
│
├── results/
│   ├── regression_summary.png
│   ├── roi_comparison.csv
│
└── README.md
