# 🎵 Project | Analyzing Website Performance for *The GRAMMYs*

![Recording Academy Logo](https://upload.wikimedia.org/wikipedia/en/7/7b/Grammy_Awards_logo.svg)

---

## 🏆 Overview

This project dives into **real analytics data** from **The Recording Academy**, the organization behind *The GRAMMY Awards*.  
Under the leadership of **Ray Starck (VP of Digital Strategy)**, the Recording Academy made a major digital change in 2022 — splitting its main website into two platforms:

- **GRAMMY.com** — for fans, news, music content, and award coverage  
- **RecordingAcademy.com** — for professionals, members, and advocacy  

My role was to **analyze the performance impact of this split**, evaluate audience engagement, and recommend strategies to help the Academy maintain year-round engagement beyond Awards Night.  
This project showcases the intersection of **data analytics, storytelling, and digital strategy**.

---

## 📊 Project Goals

1. Understand traffic and engagement trends before and after the website split.  
2. Measure key performance indicators (KPIs):  
   - Visitors  
   - Pageviews  
   - Sessions  
   - Bounce rate  
   - Average session duration  
3. Analyze audience demographics to identify shifts in user engagement.  
4. Develop actionable recommendations for long-term fan retention and web optimization.  
5. Compare GRAMMY.com’s performance with **The American Music Awards (AMA)** as a competitive benchmark.

---

## 📁 Data Sources

The project used multiple real-world datasets provided by The Recording Academy:

- `grammys_live_web_analytics.csv` – Traffic and engagement metrics for **GRAMMY.com**
- `ra_live_web_analytics.csv` – Metrics for **RecordingAcademy.com**
- `grammys_age_demographics.csv` – Visitor age breakdown for GRAMMY.com
- `tra_age_demographics.csv` – Visitor age breakdown for RecordingAcademy.com
- `desktop_users.csv` and `mobile_users.csv` – Device usage data (for competitive benchmarking)

Each dataset included information such as:
- Date of visit
- Total visitors and sessions
- Pageviews per session
- Bounce sessions
- Average session duration (seconds)
- Awards week and awards night flags

---

## 🧠 Part 1: Exploring the Data

The first phase focused on understanding **traffic patterns and spikes** across both websites.

### Key Findings
- **Awards Night** (late January or early February) generated the **highest traffic spikes**.
- **Nominations announcements** (November) caused noticeable secondary surges.
- Other minor peaks corresponded to GRAMMY Museum exhibits and tribute campaigns.
  
📈 **Insight:** The site’s traffic is heavily tied to event-based marketing, revealing a strong need for year-round engagement strategies.

---

## 📈 Part 2: Measuring Engagement Before and After the Split

### Key Metrics Compared

| Metric | Combined Site (Before Split) | GRAMMYs.com (After Split) | RecordingAcademy.com |
|--------|-------------------------------|----------------------------|----------------------|
| **Bounce Rate** | 41.6% | 40.1% | 33.7% |
| **Pages per Session** | ≈ 2.0 | ≈ 2.0 | ≈ 2.0 |
| **Avg. Session Duration** | 103 sec | 83 sec | 129 sec |

### Interpretation
- Engagement depth (pages/session) stayed **consistent** before and after the split.  
- Bounce rate slightly improved, showing the redesign didn’t harm visitor retention.  
- Average session duration dropped for GRAMMY.com (103 → 83 sec) but increased for RecordingAcademy.com (129 sec), suggesting professional users engaged with more in-depth content.

🎯 **Conclusion:**  
The split successfully differentiated the two audiences:
- GRAMMY.com attracts casual fans seeking quick updates and entertainment.
- RecordingAcademy.com appeals to professionals and members who spend more time on the site.

---

## 👥 Part 3: Audience Demographics Analysis

The GRAMMY.com and RecordingAcademy.com demographics were almost identical in distribution, but a few differences stood out:

| Age Group | GRAMMYs (%) | Recording Academy (%) |
|------------|--------------|------------------------|
| 18–24 | 27.4% | 25.1% |
| 25–34 | 24.1% | 26.2% |
| 35–44 | 18.6% | 20.3% |
| 45–54 | 14.2% | 13.8% |
| 55+ | 15.7% | 14.6% |

**Insights**
- GRAMMY.com slightly skews younger (18–24) and older (55+).  
- RecordingAcademy.com captures more 25–44 visitors — ideal for the professional demographic.  

📊 **Takeaway:** The audience segmentation achieved by the site split aligns perfectly with its target goals.

---

## 💬 Part 4: Business Memo to The Recording Academy

**To:** Ray Starck, VP of Digital Strategy  
**From:** M. Ammar Malick  
**Subject:** Website Split — Engagement Findings & Recommendations  

> Our analysis confirms GRAMMY.com’s heavy reliance on Awards Night traffic — **1.39 million visitors vs 32,000 on typical days** (+4,190%).  
> Post-split, bounce rate remained stable for GRAMMY.com (40%) and improved for RecordingAcademy.com (34%).  
> Average session duration fell slightly on GRAMMY.com (103s → 83s), but users on RecordingAcademy.com stayed longer (129s).  
>
> **Recommendation:**  
> Maintain separate domains to preserve distinct audiences but build an “always-on” digital ecosystem for GRAMMY.com to reduce seasonal dependency.  
> Suggested initiatives include:  
> - Weekly artist spotlights & nomination trackers  
> - Interactive archives & behind-the-scenes features  
> - Cross-linking both sites during campaign periods (Nov–Feb)  
>
> These steps will extend user engagement across the full year and improve brand consistency across audiences.

---

## ⚔️ Part 5: Competitive Benchmark — GRAMMYs vs. American Music Awards (AMA)

To evaluate performance, GRAMMY.com metrics were compared with AMA’s Q2 2023 website performance.

| KPI | GRAMMYs.com | AMA.com |
|------|--------------|---------|
| **Total Visits (Q2 2023)** | 1,428,482 | ~900,000 |
| **Device Share** | 68% Mobile / 32% Desktop | 60% Mobile / 40% Desktop |
| **Avg. Visit Duration** | 4 min 10 sec | 5 min 53 sec |
| **Pages per Visit** | 2.0 | 2.74 |
| **Bounce Rate** | 41% | 54% |

### Insights
- GRAMMYs.com draws **far more visitors** overall and has a healthier bounce rate.  
- AMA.com leads slightly in **session depth** and **time-on-site**, indicating stronger mid-session engagement.  
- GRAMMYs’ high mobile share shows accessibility strength but also the need to **enhance mobile UX** to improve retention.  

💡 **Recommendation:**  
Focus future optimization efforts on:
- Smoother mobile navigation  
- Richer multimedia for longer viewing sessions  
- Interactive features that encourage browsing multiple pages

---

## 🧰 Tools & Technologies

| Category | Tools |
|-----------|-------|
| **Data Analysis** | Python (pandas, NumPy) |
| **Visualization** | Plotly Express, Matplotlib |
| **Version Control** | Git & GitHub |
| **Workflow** | Jupyter Notebook, Google Colab |
| **Reporting** | Markdown, Business Memos, Dashboards |

---

## 🎓 Key Learnings

- Strengthened ability to **translate raw web data into actionable insights**.  
- Gained experience in **data storytelling** and executive-level reporting.  
- Improved technical fluency in **pandas**, **data cleaning**, and **trend visualization**.  
- Learned how to align analytics with **brand strategy and user engagement**.  

---

## 👤 Author

**M. Ammar Malick**  
🎓 *Software Engineering Student – University of Texas at Arlington*  
💼 *Data & Digital Strategy Enthusiast*  

[🔗 LinkedIn](www.linkedin.com/in/ammar-malick-1023b9278) | [💻 GitHub](https://github.com/amalick8)

---

## ✨ Summary

Through this project, I collaborated with *The Recording Academy* to evaluate how splitting GRAMMY.com and RecordingAcademy.com affected web performance and user engagement.  
The findings showed that the split improved clarity between fan and professional audiences while maintaining engagement levels.  

This analysis helped identify strategic opportunities to **turn a once-a-year event into a year-round digital experience** — leveraging data to strengthen one of the world’s most recognized entertainment brands.
