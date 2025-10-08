# 🎬 Netflix Content Trends Analysis
_A Comprehensive Data Analytics & Business Intelligence Project_

---

## 📖 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on the Netflix dataset (7,789 records × 11 columns), covering both **Movies** and **TV Shows** across multiple years, genres, and countries.  
The goal is to uncover **content trends**, identify **strategic opportunities**, and generate **data-driven recommendations** for content investment, metadata enhancement, and audience targeting.

---

## 🎯 Problem Statement
> Netflix faces increasing competition from global and regional OTT platforms such as Amazon Prime Video, Disney+, and Hotstar.  
> To remain the market leader, Netflix must strategically analyze its **content library** — discovering which genres, countries, and content types (Movies vs. TV Shows) are driving engagement and where new opportunities exist.

---

## 🧩 Objectives
1. Analyze the **distribution of Movies vs. TV Shows** across years.  
2. Identify **most common genres** and how their popularity has evolved.  
3. Evaluate **country-wise content contributions** and regional dominance.  
4. Develop **strategic recommendations** for content production and acquisition.  
5. Ensure **data quality, enrichment, and visualization** for actionable insights.

---

## 📊 Dataset Description
| Attribute | Description |
|------------|-------------|
| `Show_Id` | Unique identifier for each title |
| `Category` | Content type: Movie or TV Show |
| `Title` | Name of the show/movie |
| `Director` | Director(s) of the title |
| `Cast` | Main cast members |
| `Country` | Country of production |
| `Release_Date` | Original release date |
| `Rating` | Audience classification (TV-MA, PG, etc.) |
| `Duration` | Runtime (in minutes or seasons) |
| `Type` | Category label (genre/type) |
| `Description` | Short synopsis of the title |

---

## 🔍 Key Insights
- Movies dominate Netflix’s library (~69%), with TV shows forming the rest.  
- The U.S. and India lead in content production; other countries are growing contributors.  
- Most common genres: **Drama, Comedy, Action, Thriller**.  
- Ratings skew toward **TV-MA** (mature audience).  
- Average movie duration ≈ **100 minutes**.  
- Metadata missing for some `Director` and `Cast` fields — improvement opportunity.

---

## 🧠 Business Intelligence Summary
| KPI | Value |
|-----|--------|
| Total Titles | 7,789 |
| Movies : TV Shows | 69% : 31% |
| Distinct Directors | 5,401 |
| Countries Represented | 90+ |
| Top Country | United States |
| Peak Content Year | 2020 |
| Most Common Rating | TV-MA |
| Average Duration | ~100 mins |

### Strategic Priorities
1. **Regional Portfolio Expansion** – Invest in emerging markets (e.g., Korea, Spain).  
2. **Genre Diversification** – Expand Documentary, Animation, and Family content.  
3. **Metadata Enrichment** – Fill missing Director/Cast data for 30% of titles.  
4. **Content Forecasting** – Use yearly trends to guide acquisitions.  
5. **Personalization** – Enhance recommendation systems with enriched metadata.

---

## 🧮 Methodology

### **Phase 1: Data Integrity & Quality**
- Data type validation, missing value analysis, imputation strategies.
- Outlier detection using IQR and Z-score (sorted and flagged per record).
- Duplicate detection and removal.

### **Phase 2: Data Transformation**
- Feature engineering: `is_movie`, `duration_value`, `cast_count`, `director_count`, `primary_genre`, `primary_country`.
- Data normalization and enrichment for better visualization.

### **Phase 3: Insight Generation**
- Visualization: Distribution plots, genre trends, country analysis, yearly additions.
- KPI computation and executive summary generation.

---

## ⚙️ Tech Stack

| Component | Tools & Libraries |
|------------|------------------|
| **Language** | Python 3 (Jupyter Notebook / VSCode) |
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Statistics** | scipy (for Z-score & IQR) |
| **Automation & Reporting** | Python markdown, reportlab, ChatGPT |
| **Version Control** | Git & GitHub |


---

