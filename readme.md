# 📊 EdTech Lead Conversion & Funnel Optimization Analysis

![Excel](https://img.shields.io/badge/Microsoft_Excel-Advanced_Analytics-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-EdTech_Growth_&_CRM-0078D4?style=for-the-badge)
![Framework](https://img.shields.io/badge/Framework-STAR_Case_Study-FF6F00?style=for-the-badge)

> **Executive Summary (TL;DR):**  
> Analyzed the end-to-end student acquisition and trial-to-paid conversion funnel for an EdTech platform (**Codeyoung dataset**). By evaluating multi-channel lead performance across **Referral, Google Search, Facebook Ads, and Organic Social**, this project identifies critical pre-trial and post-trial drop-off bottlenecks and delivers data-backed CRM and budget reallocation strategies to lower Customer Acquisition Cost (CAC) and boost overall subscription conversion.

---

## 🧭 Project Showcase Framework (STAR + Business Impact)

To make this repository easy to navigate for hiring managers and stakeholders, this case study follows the **STAR + Business Impact Framework**:
1. **[Situation & Business Problem](#-1-situation--business-problem)** — The commercial challenge in EdTech funnel unit economics.
2. **[Task & Analytical Objectives](#-2-task--analytical-objectives)** — Core business questions and KPI definitions.
3. **[Action: Methodology & Skills Showcased](#-3-action-methodology--skills-showcased)** — Data modeling, KPI formulation, and dashboard execution.
4. **[Results: Key Insights & Funnel Performance](#-4-results-key-insights--funnel-performance)** — Quantitative channel comparisons and bottleneck discovery.
5. **[Strategic Recommendations (Business Impact)](#-5-strategic-recommendations-business-impact)** — Actionable growth levers mapped to funnel stages.
6. **[Repository Files & How to Explore](#-6-repository-files--how-to-explore)** — Guide to the dataset and analysis workbooks.

---

## 🎯 1. Situation & Business Problem

In live-learning EdTech companies (such as Codeyoung and BrightChamps), the **Free Trial (Demo) Class** is the most critical inflection point in the customer journey. While paid acquisition channels generate high lead volume at the top of the funnel, revenue growth often stalls due to two major leaks:
1. **Top-of-Funnel Leakage (No-Shows):** Leads book a free trial class but fail to attend.
2. **Bottom-of-Funnel Leakage (Post-Trial Drop-off):** Students attend the demo class, but parents do not convert to a paid subscription.

Without granular visibility into how different **acquisition sources** and **student segments** progress through each stage, marketing teams risk overspending on high-volume, low-intent channels.

---

## 📋 2. Task & Analytical Objectives

The objective of this project was to transform raw lead-level funnel telemetry (`Codeyoung_EdTech_Funnel_Dataset.xlsx`) into a structured analytical model and executive dashboard (`Ed Tech Company Analysis Project.xlsx`) to answer four core business questions:

* **Funnel Health:** What is the stage-by-stage conversion and drop-off rate from *Lead Generated $\rightarrow$ Trial Attended $\rightarrow$ Paid Subscription*?
* **Channel Efficiency:** Which acquisition channels drive the highest-intent leads versus the highest drop-off rates?
* **Post-Trial Conversion:** Once a student attends a trial class, how effectively does each channel convert attendees into paying subscribers?
* **Budget & CRM Optimization:** Where should Marketing and Academic Counseling teams intervene to maximize Return on Ad Spend (ROAS)?

---

## 🛠️ 3. Action: Methodology & Skills Showcased

### **Technical & Analytical Skills Demonstrated**
* **Data Cleaning & Preparation:** Audited raw lead records for missing values, standardized categorical fields (acquisition channels, funnel statuses, course modules), and validated date-time sequences.
* **Multi-Stage Funnel Modeling:** Built structured Pivot Tables and dynamic aggregation matrices in Excel (`COUNTIFS`, `SUMIFS`, `IFERROR`, conditional formatting, and calculated fields) to track cohort movement across funnel stages.
* **KPI Engineering:** Formulated core EdTech growth metrics to separate *pre-trial marketing/onboarding efficiency* from *in-class/sales conversion efficiency*:

$$\text{Trial Attendance Rate (\%)} = \left( \frac{\text{Total Trials Attended}}{\text{Total Leads / Trials Booked}} \right) \times 100$$

$$\text{Post-Trial Conversion Rate (\%)} = \left( \frac{\text{Total Paid Subscriptions}}{\text{Total Trials Attended}} \right) \times 100$$

$$\text{Overall Lead-to-Subscription Rate (\%)} = \left( \frac{\text{Total Paid Subscriptions}}{\text{Total Leads / Trials Booked}} \right) \times 100$$

$$\text{Stage Drop-Off Rate (\%)} = 100\% - \text{Stage Conversion Rate (\%)}$$

* **Visual Storytelling:** Designed clear comparative charts and summary tables highlighting channel disparities and conversion bottlenecks for rapid executive decision-making.

---

## 📈 4. Results: Key Insights & Funnel Performance

### **A. Acquisition Channel Performance Breakdown**

| Acquisition Source | Trial Attendance Rate (%) | Trial No-Show / Drop-Off (%) | Post-Trial Conversion Rate (Subscribed / Attended) | Overall Subscription Rate (%) | Channel Diagnosis |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Referral** | $81.8\%$ | $18.2\%$ | $72.2\%$ | **$59.1\%$** | 🏆 **Star Performer:** Highest intent & trust |
| **Google Search** | $56.2\%$ | $43.8\%$ | $47.9\%$ | **$26.9\%$** | 📈 **High-Intent Scalable:** Strong search intent |
| **Facebook Ads** | $41.1\%$ | $58.9\%$ | $28.7\%$ | **$11.8\%$** | ⚠️ **High Leakage:** High volume, low attendance |
| **Organic Social** | $34.9\%$ | $65.1\%$ | $31.8\%$ | **$11.1\%$** | 🔍 **Top-of-Funnel Bottleneck:** Needs nurturing |

---

### **B. Core Analytical Findings**

1. **Referrals Outperform Paid Social by $5\times$ in Overall Conversion:**
   * **Referral** leads achieve an **$81.8\%$ trial attendance rate** and a **$59.1\%$ overall subscription rate** (converting **$72.2\%$** of all students who attend a trial). Peer trust dramatically reduces both no-shows and post-trial hesitation.
2. **The Pre-Trial Attendance Bottleneck in Social Channels:**
   * **Organic Social** ($65.1\%$ drop-off) and **Facebook Ads** ($58.9\%$ drop-off) lose the majority of their leads *before the student ever enters the virtual classroom*. Impulse sign-ups from social feeds lack urgency without structured pre-class engagement.
3. **Search Intent Translates to Strong Mid-Funnel Performance:**
   * **Google Search** captures parents actively looking for courses, resulting in a **$56.2\%$ attendance rate** and **$26.9\%$ overall conversion**—more than double the efficiency of Facebook Ads ($11.8\%$).
4. **Attending the Trial Class is the Ultimate Conversion Catalyst:**
   * Even in lower-performing channels like Organic Social and Facebook Ads, once a student actually attends the trial session, conversion jumps to **$28.7\%–31.8\%$**. Getting the student into the demo class is the single highest-leverage operational goal.

---

## 💡 5. Strategic Recommendations (Business Impact)

| Target Area | Identified Bottleneck | Actionable Recommendation | Expected Business Impact |
| :--- | :--- | :--- | :--- |
| **1. Referral Loop Expansion** | Referral generates $59.1\%$ conversion but typically has lower raw volume than paid ads. | Launch a **2-Sided Tiered Referral Program** (e.g., offer existing parents 2 free bonus classes immediately after their child completes a module if they refer a friend). | Scales the highest-converting channel while lowering blended CAC. |
| **2. Pre-Trial CRM & Reminder Cadence** | $58.9\%–65.1\%$ trial no-show rate on Facebook Ads & Organic Social leads. | Implement an **Automated WhatsApp + SMS Reminder Sequence** ($24\text{h}$, $2\text{h}$, and $15\text{m}$ prior to trial) featuring a 30-second intro video from the assigned teacher. | Reduces trial no-show rates by an estimated $15\%–20\%$ on social channels. |
| **3. Paid Media Budget Reallocation** | Facebook Ads convert at less than half the rate of Google Search ($11.8\%$ vs. $26.9\%$). | Shift $20\%–25\%$ of underperforming Facebook ad spend toward **High-Intent Google Search Keywords** and **Lookalike Audiences** modeled on Referral subscribers. | Improves overall Marketing ROAS and increases trial-to-paid yield. |
| **4. Post-Trial Speed-to-Lead SLA** | Post-trial drop-off ($>70\%$) among Facebook/Organic trial attendees. | Enforce a **$<60\text{-Minute}$ Counseling Follow-Up SLA** post-trial with a personalized student scorecard and time-bound enrollment incentive. | Lifts post-trial conversion on social cohorts from $\sim 29\%$ toward $38\%+$. |

---

## 📂 6. Repository Files & How to Explore

```text
📦 EdTech-Funnel-Analytics
 ┣ 📄 Codeyoung_EdTech_Funnel_Dataset.xlsx       # Raw EdTech lead & funnel dataset
 ┣ 📊 Ed Tech Company Analysis Project.xlsx      # Complete Excel analysis, Pivot Tables & Dashboard
 ┣ 🖼️ funnel_performance_by_source.png           # Visual chart of channel conversion performance
 ┗ 📜 README.md                                  # Project documentation & case study
```

### **How to Review the Work:**
1. Download and open **`Ed Tech Company Analysis Project.xlsx`** in Microsoft Excel or Google Sheets.
2. Explore the **Analysis & Pivot Tabs** to view the stage-by-stage cohort calculations, drop-off percentages, and channel segmentation tables.
3. Review the **Dashboard / Visual Summary** to see the comparative charts across acquisition channels.

---

## 👤 Author & Contact

**Somesh Kumar**  
*Business & Data Analyst | EdTech, Customer Insights & Funnel Analytics*  
📍 Bengaluru, Karnataka, India  
🔗 [LinkedIn](#) | [GitHub](#) | 📧 somesh.kumar@email.com