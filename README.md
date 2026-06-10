<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=BCA%20Data%20Science%20%F0%9F%8E%93&fontSize=55&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Semester%20VI%20Result%20Analysis%20Dashboard&descAlignY=60&descSize=20" width="100%"/>

<br/>

[![Power BI](https://img.shields.io/badge/Built%20with-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Sri Balaji University](https://img.shields.io/badge/University-Sri%20Balaji%2C%20Pune-0078D4?style=for-the-badge&logo=graduation-cap&logoColor=white)](https://sbu.edu.in/)
[![Academic Year](https://img.shields.io/badge/Academic%20Year-2023--26-7B2FBE?style=for-the-badge)](.)
[![Students](https://img.shields.io/badge/Total%20Students-154-00C49F?style=for-the-badge&logo=users&logoColor=white)](.)
[![Pass Rate](https://img.shields.io/badge/Pass%20Rate-85.06%25-28A745?style=for-the-badge)](.)

<br/>

> **"Turning raw scanned PDFs into a fully interactive multi-page Power BI dashboard — from scratch, by hand."**

<br/>

</div>

---

## 🌟 What Makes This Special

This isn't just a dashboard — this is a **full data journey**. The raw result data existed only as **scanned PDF files**. Every single value was **manually extracted and entered into Excel**, then transformed into this rich, multi-page analytical experience using Power BI.

```
📄 Scanned PDF Results  ──►  📊 Manual Excel Entry  ──►  🔮 Power BI Dashboard
```

---

## 📸 Dashboard Preview

<div align="center">

### 🏠 Home — Overview Dashboard
> *High-level KPIs: total students, pass/fail counts, SGPA distribution, and top rankers at a glance.*

![Home Dashboard](./screenshots/home.png)

---

### 📈 SGPA & Performance Analysis
> *Division-wise SGPA comparison, pass %, scatter plot of SGPA vs Total Marks.*

![SGPA Performance](./screenshots/sgpa_performance.png)

---

### 🧠 Aptitude & Reasoning
> *Grade distribution, internal vs external marks scatter, division-wise averages.*

![Aptitude](./screenshots/aptitude.png)

---

### 🔬 Subject Pages (NLP · DL · Design Thinking · MOOC · Mini Project)
> *Individual subject dashboards with topper highlights, grade rings, and division comparisons.*

![Subjects](./screenshots/subjects.png)

---

### ⚔️ Subject & Student Comparison
> *Side-by-side student comparison with subject-level internal, external, and total marks.*

![Comparison](./screenshots/comparison.png)

</div>

---

## 📊 Key Metrics at a Glance

<div align="center">

| Metric | Value |
|--------|-------|
| 🎓 Total Students | **154** |
| ✅ Passed Students | **131** |
| ❌ Failed Students | **23** |
| 📈 Pass Percentage | **85.06%** |
| ⭐ Average SGPA | **7.40** |
| 🏆 Highest SGPA | **9.09** (Vaishnavi Subhash Naik) |
| 🏛️ BCA-A Students | **76** |
| 🏛️ BCA-B Students | **78** |

</div>

---

## 🏆 Top Performers

<div align="center">

| 🥇 Rank | Student Name | SGPA |
|---------|-------------|------|
| 1 | Vaishnavi Subhash Naik | 9.09 |
| 2 | Sandili Arjun Shinde | 9.00 |
| 2 | Tejas Ramesh Waghmare | 9.00 |
| 3 | Gunn Manoj Mandhan | 8.86 |
| 3 | Karan Lakhmi Chimnani | 8.86 |
| 4 | Rohit Kumar | 8.82 |

</div>

---

## 📋 Dashboard Pages

```
📁 Dashboard Structure
│
├── 🏠  Home                    → Overall result summary & KPI cards
├── 📈  SGPA Performance        → Division-wise SGPA & pass % analysis
├── 🎯  Aptitude                → Career Advisory subject analysis
├── 🛠️  Mini Project / OJT      → Project marks & grade breakdown
├── 🌐  MOOC / SWAYAM           → Online certificate performance
├── 💡  Design Thinking         → Subject-level internal/external analysis
├── 🤖  NLP                     → Data Mining & NLP subject page
├── 🔬  NLP Lab                 → Lab performance & rankers
├── 🧠  Deep Learning (DL)      → Pattern recognition subject page
├── ⚗️  DL Lab                  → Deep Learning lab analysis
├── ⚖️  Subject Comparison      → Cross-subject pass % & fail counts
└── 👥  Student Comparison      → Head-to-head student breakdown
```

---

## 🛠️ Tools & Technologies

<div align="center">

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Dashboard creation & visualization |
| ![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) | Manual data entry from scanned PDFs |
| ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white) | Calculated measures & Quick Measures |
| 📄 Scanned PDFs | Original source of student result data |

</div>

---

## 🔍 Features

- 🎛️ **Interactive Filters** — Filter by SGPA category, division, or subject on every page
- 📊 **12 Dashboard Pages** — One dedicated page per subject + summary views
- 🏅 **Dynamic Topper Cards** — Auto-highlights the top performer for each subject
- ⚖️ **Student Comparison Tool** — Compare any two students side-by-side across all subjects
- 🔄 **Division-wise Breakdowns** — Every metric split by BCA-A and BCA-B
- 📉 **Grade Distribution Rings** — Donut charts for grade spread in every subject
- 📍 **Scatter Analysis** — Internal vs External marks correlation for each subject

---

## 💡 How It Was Built

```
Step 1 — Data Collection
   Obtained scanned PDF mark sheets (no digital data existed)

Step 2 — Manual Data Entry  ⬅ The hardest part!
   Extracted every student's marks subject-by-subject into Excel
   Cleaned, validated, and structured the data manually

Step 3 — Power BI Modelling
   Imported cleaned Excel into Power BI
   Built relationships, DAX measures, and calculated columns

Step 4 — Dashboard Design
   Designed 12 pages with consistent color language
   Added navigation, KPI cards, charts, and toppers

Step 5 — Polish & Deploy
   Added Quick Measures, tooltips, and interactive filters
```

---

## 📂 Repository Structure

```
📦 bca-result-dashboard/
 ┣ 📊 BCA_Sem6_Result_Dashboard.pbix   ← Main Power BI file
 ┣ 📗 student_marks_data.xlsx          ← Cleaned Excel data (manually entered)
 ┣ 📁 screenshots/
 ┃ ┣ 🖼️ home.png
 ┃ ┣ 🖼️ sgpa_performance.png
 ┃ ┣ 🖼️ aptitude.png
 ┃ ┣ 🖼️ subjects.png
 ┃ └ 🖼️ comparison.png
 ┗ 📄 README.md
```

---

## 🚀 Getting Started

```bash
# 1. Clone this repository
git clone https://github.com/YOUR_USERNAME/bca-result-dashboard.git

# 2. Open the dashboard
# → Open BCA_Sem6_Result_Dashboard.pbix in Power BI Desktop

# 3. If data needs refreshing
# → Update the Excel file path in Power BI → Transform Data → Source
```

> ⚠️ **Requires:** [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to open the `.pbix` file.

---

## 👨‍💻 Developer

<div align="center">

<img src="https://avatars.githubusercontent.com/u/YOUR_ID?v=4" width="100" style="border-radius:50%"/>

### **Prathviraj Bharat Chavan**
*BCA Data Science, Semester VI*
*Sri Balaji University, Pune*

[![Roll No](https://img.shields.io/badge/Roll%20No-BCA2302144-7B2FBE?style=flat-square)](.)
[![Email](https://img.shields.io/badge/Email-mr.prathvirajchavan%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mr.prathvirajchavan@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-9766638211-25D366?style=flat-square&logo=whatsapp&logoColor=white)](tel:9766638211)

</div>

---

## ⭐ Show Some Love

If this project helped you or inspired your own dashboard work, **drop a ⭐ on the repo!**

It motivates me to build more open data projects for students. 🙌

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

*Made with ❤️ by Prathviraj Chavan | BCA Data Science | Sri Balaji University, Pune*

</div>
