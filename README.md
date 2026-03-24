# VP Bank Customer Segmentation & Revenue Opportunity Analysis

---

## Context
- **Dataset:** 3 Excel files containing 113K+ anonymized customer records (AUM, customer profile, product holdings)  
- **Objective:** Analyze customer behavior and identify key opportunities to support **20% KPI growth**, focusing on:
  - Service usage patterns  
  - Customer segmentation  
  - High-impact product strategies  

---

## Steps

### 1. Data Consolidation
- Integrated multiple data sources into a unified dataset using **MySQL**  
- Performed statistical analysis and applied **IQR** to understand AUM distribution and handle outliers  

---

### 2. Segmentation Modeling
- **AUM Tiering:** Segmented customers into 5 wealth tiers (Mass → Ultra Premium) based on distribution  
- **Hybrid Segmentation:** Built a rule-based model (Power Query) combining:
  - Customer wealth (AUM)  
  - Number of profitable products  
→ Resulting in 5 strategic segments: **VIP, Strategic, Potential, Standard, Inactive**

---

### 3. Analysis & Visualization
- Developed interactive dashboards using **Power BI** and **DAX** to analyze product usage across segments  
- Constructed a **cross-sell matrix** (via data unpivoting) to identify product penetration gaps  

---

## Key Insights

- **High concentration of value:** ~20% of customers contribute **83.4% of total AUM (7.4T VND)**  
- **Geographic disparity:** Despite similar customer volumes, **Ho Chi Minh City holds ~4x higher AUM** than Hanoi  
- **Credit card gap:** **74% of Strategic customers** (high-potential segment) do not own a credit card → major cross-sell opportunity  
- **Untapped assets:** The Potential segment holds significant AUM but shows **zero adoption of profitable products**  

---

## Recommendations

- **Expand credit card penetration** in Strategic segment, especially in key cities (HCMC, Hanoi)  
- **Activate Potential segment** through bundled offerings (e.g., deposits + credit cards)  
- **Drive loan growth** across Standard, Strategic, and VIP segments leveraging available capital  
- **Retain high-value customers** via exclusive services for Strategic and VIP segments  

---

## Dashboard

### Overview
![Overview Dashboard](https://github.com/user-attachments/assets/b500f1d3-e8f0-4a99-80b0-8d360bc21ba2)

### Customer Segmentation
![Customer Segmentation Dashboard](https://github.com/user-attachments/assets/b6c9bbdf-a465-45c0-946b-a6f216b694f1)

### Revenue Opportunity
![Revenue Opportunity Dashboard](https://github.com/user-attachments/assets/d76be013-8748-4a3f-ad24-c14083059384)
