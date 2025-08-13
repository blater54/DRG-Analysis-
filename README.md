# Medicare DRG Dashboard – Finding the Financial Gaps  

![Medicare DRG Dashboard Screenshot]()  
  

---

## What’s This Project About?  
Hospitals bill one amount for patient care… but Medicare doesn’t always pay anywhere close to that.  
This project digs into **CMS Medicare Inpatient Hospital data** to find:  
- Which **conditions (DRGs)** are costing hospitals the most money  
- Which **states** are feeling the biggest pinch  
- How much hospitals are *really* losing per patient on average  

---

## The Data  
- **Source**: [CMS Medicare Inpatient Hospitals – By Provider and Service](https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider-and-service/data)  
- **Level**: Hospital + DRG (Diagnosis Related Group)  
- **Key Columns**:  
  - `Total Discharges` – patient count  
  - `Average Covered Charges` – what the hospital billed  
  - `Average Medicare Payments` – what Medicare actually paid  
  - `Average Total Payments` – includes Medicare + patient + other insurance  

---

## What I Looked At  
**KPIs in the dashboard**:  
- Total discharges  
- Average covered charges (billed amount)  
- Average Medicare payments (reimbursement)  
- Loss per discharge *(covered charges − Medicare payments)*  
- Total loss per DRG and per state  

---

## Key Takeaways  
### 1. States hit hardest  
- **California, Texas, Florida** → biggest *total* losses (high volume of Medicare patients)  
- **Alaska** → highest *loss per patient* (care costs are much higher there)  

### 2. DRGs with the biggest gaps  
- Complex surgeries and high-acuity cases make up most of the **top 5 loss DRGs**.  
- Medicare covers **only ~15–25%** of the hospital’s bill for these DRGs.  

### 3. Geography matters  
- States with higher living costs (Alaska, Hawaii) bill much more per patient.  
- Medicare rates don’t adjust enough to match those costs → bigger losses.  

---

## Why It Matters  
If you work in hospital finance or operations, this dashboard helps you:  
1. Spot **high-volume states** where small changes can save millions.  
2. Identify **high-cost states** that might need operational or policy review.  
3. Target **loss-heavy DRGs** for process improvements or reimbursement negotiations.  

---

## 🖥 Dashboard Features  
- Clickable **state map** → see losses by geography  
- KPI cards for quick snapshots  
- DRG ranking tables  
- Filters for both DRG and state  

---

##  How I Built It  
- **Tool**: Tableau Public  
- **Data**: CMS Medicare DRG dataset  
- **Process**:  
  - Cleaned and loaded CSV into Tableau  
  - Created calculated fields for losses  
  - Built heatmaps, tables, and KPIs  
  - Published interactive dashboard  


---

## 🤝 About Me  
I have a **Master’s in Applied Mathematics** and a passion for using data to solve real-world problems in healthcare.  
This dashboard is part of my journey into **healthcare analytics**, with a focus on revenue cycle and operations improvement.  
