---
title: "Projects & Work"
date: 2025-01-03
draft: false
---

# My Projects & Contributions

A showcase of my work in ceramic engineering, from competitive case studies to academic research and technical content creation.

---

## 🏆 Featured Project

### CUMI National Case Study Contest 2025
**Achievement:** 🥉 2nd Runner-up (National Level)

<div style="background: #061926ff; padding: 1.5rem; border-left: 4px solid #2196f3; margin: 2rem 0;">

**Organization:** Carborundum Universal Limited (CUMI)  
**Role:** Problem Solver, Researcher                                                  
   **Duration:** October 2025 - December 2025  
**Competition Level:** National

</div>

#### 🎯 Project Overview

Participated in a prestigious national-level case study competition where we tackled a complex industrial quality challenge for **Carborundam Universal Limited (CUMI)**, one of India's leading manufacturers of abrasives, ceramics, refractories, and related products.

The challenge involved analyzing critical manufacturing defects in ceramic production and developing a comprehensive, implementable solution that balanced technical feasibility with economic viability.

#### 🔍 The Challenge

CUMI presented us with real-world data from their manufacturing facility showing:
- Increasing defect rates in ceramic products
- Quality inconsistencies across production batches
- Rising production costs due to rework and rejection
- Customer complaints about product performance
- Need for systematic root cause identification

**Objective:** Develop a prioritized techno-economic action plan to address these quality issues while maintaining cost-effectiveness.

#### 🛠️ Our Approach

**1. Data Collection & Preparation**
- Received manufacturing data spanning 6 months of production
- Cleaned and organized data using **Python** and **Excel**
- Identified key variables: temperature, pressure, raw material composition, production time, operator shifts
- Created comprehensive database for analysis

**2. Exploratory Data Analysis**
```python
# Example of our analytical approach
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load manufacturing data
data = pd.read_csv('cumi_production_data.csv')

# Identify defect patterns
defect_analysis = data.groupby('defect_type')['frequency'].sum()

# Visualize trends
plt.figure(figsize=(10,6))
sns.barplot(x=defect_analysis.index, y=defect_analysis.values)
plt.title('Defect Type Distribution')
```

**3. Root Cause Analysis**

Used multiple methodologies:

- **Fishbone Diagram (Ishikawa):** Identified potential causes across 6M categories
  - Man: Operator training, shift patterns
  - Machine: Equipment calibration, maintenance schedules
  - Material: Raw material quality, supplier consistency
  - Method: Process parameters, standard operating procedures
  - Measurement: Sensor accuracy, inspection methods
  - Environment: Temperature, humidity, dust control

- **Pareto Analysis:** Identified that 80% of defects came from 20% of causes
  - Temperature fluctuations: 35% of defects
  - Raw material variability: 28% of defects
  - Equipment calibration: 17% of defects

- **Statistical Process Control (Minitab):**
  - Created control charts to identify out-of-control processes
  - Conducted capability analysis (Cp, Cpk values)
  - Performed hypothesis testing to validate findings

**4. Solution Development**

Developed a multi-tiered action plan:

**Immediate Actions (0-3 months):**
- Recalibrate temperature control systems
- Implement raw material inspection protocols
- Provide operator refresher training
- **Expected Impact:** 40% reduction in defects
- **Cost:** ₹5 lakhs

**Short-term Actions (3-6 months):**
- Upgrade sensor systems for real-time monitoring
- Establish supplier quality agreements
- Implement statistical process control charts
- **Expected Impact:** Additional 30% reduction
- **Cost:** ₹15 lakhs

**Long-term Actions (6-12 months):**
- Install automated quality control systems
- Develop predictive maintenance schedule
- Implement Six Sigma methodology
- **Expected Impact:** Total 80% defect reduction
- **Cost:** ₹40 lakhs
- **ROI:** 18 months payback period

**5. Economic Analysis**

Created comprehensive cost-benefit analysis:

| Investment Area | Cost (₹) | Expected Savings/Year (₹) | Payback Period |
|----------------|----------|---------------------------|----------------|
| Temperature Control | 5L | 8L | 7.5 months |
| Material Testing | 4L | 6L | 8 months |
| Operator Training | 1L | 3L | 4 months |
| Sensor Upgrade | 15L | 22L | 8.2 months |
| Automation | 35L | 45L | 9.3 months |
| **Total** | **60L** | **84L/year** | **8.6 months** |

**6. Presentation & Defense**

- Created comprehensive 20-slide presentation
- Prepared detailed technical report (35 pages)
- Presented findings to panel of 5 industry experts and 3 academics
- Defended our methodology and recommendations in Q&A session
- Incorporated feedback and refined solutions

#### 💡 Technologies & Tools Used

**Data Analysis:**
- **Python:** pandas, numpy, matplotlib, seaborn
- **Minitab:** Statistical process control, design of experiments
- **Microsoft Excel:** Pivot tables, data visualization, scenario analysis

**Presentation:**
- **PowerPoint:** Technical slides, charts, graphs
- **Canva:** Infographics and visual aids

**Documentation:**
- **Microsoft Word:** Technical report writing
- **LaTeX:** Mathematical equations and statistical formulas

#### 📊 Key Results & Learnings

**Quantitative Results:**
- Identified 12 major root causes of defects
- Proposed solutions with 80% potential defect reduction
- Developed implementation plan with 8.6-month ROI
- Created sustainable quality management framework

**Qualitative Impact:**
- Gained practical experience in industrial problem-solving
- Learned to balance technical solutions with economic constraints
- Developed presentation skills for technical audiences
- Enhanced ability to work under pressure and tight deadlines

**Personal Learnings:**
- Real-world data is messy - data cleaning is crucial
- Communication is as important as technical analysis
- Cost considerations drive industrial decisions
- Teamwork and collaboration are essential
- Systematic approaches yield better results than intuition

#### 🎖️ Recognition

- **2nd Runner-up** among 50+ students from across India
- Praised for systematic methodology and practical approach
- Recognized for comprehensive cost-benefit analysis
- Commended for clear presentation and effective communication


## 📝 Content Creation Projects

### Technical Writing for InCerS Student Chapter
**Role:** Technical Content Editor  
**Duration:** December 2024 - Present  
**Organization:** Indian Ceramic Society - GCECT Student Chapter

#### Project Description

Leading the technical content creation and editorial efforts for the InCerS Student Chapter, making advanced ceramic engineering concepts accessible to fellow students and the broader academic community.

#### Responsibilities & Contributions

**Content Creation:**
- Research and write articles on advanced ceramic topics
- Simplify complex technical concepts for student audience
- Create educational materials on material characterization techniques
- Develop case studies on industrial ceramic applications

**Editorial Work:**
- Edit submissions from other chapter members
- Ensure technical accuracy and scientific rigor
- Maintain consistency in tone and formatting
- Review and approve final publications

**Topics Covered:**

1. **"Advanced Ceramics in Modern Manufacturing"**
   - Overview of high-performance ceramic materials
   - Applications in aerospace, automotive, and electronics
   - Future trends and innovations

2. **"Quality Control Methods in Ceramic Production"**
   - Statistical process control techniques
   - Common defect types and prevention
   - Case studies from industry

3. **"Material Characterization: A Student's Guide"**
   - Introduction to analytical techniques
   - XRD, SEM, TEM basics
   - Practical tips for laboratory work

4. **"Sustainable Practices in Ceramic Manufacturing"**
   - Environmental challenges in ceramics industry
   - Green manufacturing techniques
   - Energy efficiency improvements

#### Impact

- **10+ articles** published in chapter's social media platform
- **200+ students** reached through social media
- **40% improvement** in content quality and engagement
- Established editorial guidelines for consistency

#### Skills Developed

- Technical writing and editing
- Content strategy and planning
- Collaboration and team management
- Research and information synthesis
- Academic communication

---

## 🔬 Academic Projects

### Material Science Laboratory Projects
**Course:** Material Science and Characterization  
**Duration:** July 2024 - December 2024  
**Institution:** GCECT

#### Project 1: Ceramic Sample Preparation and Testing

**Objective:** Prepare ceramic samples and test their mechanical properties

**Methodology:**
1. Powder preparation and mixing
2. Compaction using hydraulic press
3. Sintering at various temperatures
4. Mechanical testing (hardness, strength)
5. Microstructural analysis

**Results:**
- Successfully prepared 15 ceramic samples
- Analyzed effect of sintering temperature on properties
- Documented complete experimental procedure
- Created comprehensive lab report with graphs and analysis

#### Project 2: Microstructural Analysis of Ceramics

**Objective:** Study microstructure of different ceramic materials

**Techniques Used:**
- Optical microscopy
- Sample preparation and polishing
- Image analysis software
- Grain size measurement

**Findings:**
- Identified different phases in ceramic samples
- Measured grain sizes and distribution
- Correlated microstructure with properties
- Presented findings in class seminar

---

## 🎓 Mini Projects & Assignments



## 🚀 Future Project Plans

### Planned Research Projects

**1. Sustainable Ceramic Manufacturing**
- Investigating eco-friendly raw materials
- Reducing energy consumption in firing
- Waste reduction strategies

**2. Advanced Material Characterization**
- Learning XRD and SEM techniques
- Analyzing novel ceramic compositions
- Collaborating with faculty on research

**3. Industrial Automation in Ceramics**
- Exploring IoT applications
- Predictive maintenance systems
- Quality control automation

---

## 🤝 Open for Collaboration

I am actively seeking opportunities to collaborate on:

- **Research Projects:** Ceramic materials, quality control, sustainability
- **Industrial Challenges:** Real-world problem-solving
- **Technical Writing:** Content creation for academic or industry publications
- **Case Study Competitions:** Team-based analytical challenges
- **Internship Projects:** Hands-on industrial experience

---

## 📬 Get Involved

Have an interesting project or collaboration opportunity?

**Email:** anubhabd06@gmail.com  
**Phone:** +91-9038831854  
**LinkedIn:** [linkedin.com/in/anubhab1106](https://www.linkedin.com/in/anubhab1106/)

Let's create something impactful together!