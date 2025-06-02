# The Digital Balance: Exploring Social Media Use and Workplace Productivity

## 📊 Overview
![Dashboard Preview](https://github.com/gaiusufondu/The-Digital-Balance-Exploring-Social-Media-Use-and-Workplace-Productivity/blob/main/Sleep%20and%20social%20media%20productivity%20dashboard.png)

This report investigates the relationship between social media usage, sleep habits, and workplace productivity. Using a dataset of over 30,000 survey responses, we analyze behavioral patterns across job types, genders, and digital wellbeing practices. Our findings reveal nuanced correlations between screen time, perceived and actual productivity, and sleep duration. For instance, users who sleep 6–8 hours and use social media for 2–4 hours daily show the highest productivity. These insights offer actionable guidance for HR professionals, behavioral scientists, and workplace strategists.

## Introduction

In today's hyperconnected world, social media and digital engagement are integral to modern work and personal life. As organizations grapple with productivity optimization, it becomes essential to explore how digital habits—especially social media usage—impact job performance and rest patterns. This analysis aims to answer questions like:

* Does social media use correlate with lower productivity?
* Which job roles report higher productivity levels?
* How do sleep and digital wellbeing affect output?

## 📦 Dataset

The dataset titled **"social\_media\_vs\_productivity.csv"** contains 30,000+ survey records. Key columns include:

* `gender`: Categorical (Male, Female, Other)
* `job_type`: Occupation category (IT, Student, Education, etc.)
* `average_daily_social_media_time`: Continuous (in hours)
* `average_sleep_hours`: Continuous (in hours)
* `actual_productivity_score`: Productivity score (1–10)
* `perceived_productivity_score`: Self-assessed score
* `social_media_platform_preference`: TikTok, Twitter, etc.
* `breaks_during_work`: Time taken off during work hours (in hours)
* `digital_wellbeing_enabled`: Boolean (True/False)

## Methodology

We used Power BI to visualize the data and calculate summary statistics and performance trends. DAX measures were used for:

* Averaging productivity by group (job, gender, sleep hours, etc.)
* Analyzing productivity across screen time brackets
* Comparing perceived vs actual productivity
* Segmenting users by digital wellbeing settings

Before visualization, the dataset was cleaned by handling missing values and removing invalid or extreme outliers (e.g., users reporting >16 hours of screen time per day).

## 🛠 Tools Used
- **Power BI**: Visual analytics
- **DAX**: Metrics, averages, and category-level insights
  
## 🔍 Key Insights

### 1. **Overall Screen Time and Productivity**

* **Average screen time:** 3.11 hours/day
* Productivity drops significantly after 4 hours of daily social media use
* Users in the 2–4 hour bracket performed best

### 2. **Sleep Hours**

* Males average: 6.51 hrs | Females: 6.49 hrs
* Users with 6–8 hours of sleep showed highest productivity (avg: 6.5+)

### 3. **Gender-Based Trends**

* Male users: Slightly more productive (avg score: 4.95) than female users (avg score: 4.82)
* Males work longer hours but sleep marginally more
* Productivity distribution is similar across genders

### 4. **Job-Type Comparison**

* **Most productive job roles:**

  * IT (5.007)
  * Unemployed (4.985)
  * Finance (4.966)
* Students and educators reported the lowest actual productivity

### 5. **Platform Preference and Usage**

* **Most preferred platform:** TikTok (17.54K users)
* **Screen time (top 3):**

  * TikTok (5,829 users)
  * Twitter (5,736)
  * Telegram (5,681)
* No direct correlation between a specific platform and productivity; rather, total time spent is the stronger determinant

### 6. **Digital Wellbeing**

* 75.34% of users had digital wellbeing features enabled
* These users were moderately more productive and slept longer

### 7. **Breaks During Work**

* Users taking **1–2 hour breaks** had highest productivity (avg: 4.86)
* Very short breaks (<30 mins) or long breaks (>3 hrs) showed reduced scores

### 8. **Perceived vs Actual Productivity**

* Perception often overestimated real productivity
* Discrepancy widest among students and self-employed respondents

## Visualizations Used

* Bar Charts: Productivity by job, platform use
* Donut Charts: Gender-based distributions (work/sleep hours)
* Line Charts: Productivity over screen time, gender vs sleep
* Dual Axis: Perceived vs actual productivity

## Discussion

The data suggests that:

* Moderate screen time and 6–8 hours of sleep are ideal
* Short breaks enhance focus and productivity
* Enabling digital wellbeing tools (e.g., screen time limits) provides measurable benefits
* Self-perception of productivity is not always accurate, especially in non-corporate job roles

These insights highlight the importance of balanced digital consumption, workplace flexibility, and data-driven interventions to support employee performance. HR departments can leverage these findings to develop tailored break policies, encourage healthier sleep habits, and deploy screen time monitoring tools in productivity-focused roles.

## ⚠️ Limitations
* Self-reported data may carry biases
* Does not factor in environmental variables (e.g., work-from-home vs office)
* Lack of qualitative metrics on job satisfaction or stress levels
* Sampling bias may be present depending on survey platform and digital literacy of participants

## 🧠 Recommendations

1. **Encourage Digital Wellbeing**: Implement screen-time controls, especially for employees in non-IT roles.
2. **Sleep Hygiene Campaigns**: Educate teams on the value of consistent 6–8 hour sleep routines.
3. **Monitor Screen Time Trends**: Use internal tools to help staff visualize and self-regulate online behavior.
4. **Break Policies**: Promote structured breaks during work hours (ideally 1–2 hrs split) for improved focus.
5. **Job-Specific Approaches**: Tailor interventions by role, e.g., more support for educators and students.


📁 **Repository Contents**
- `social_media_vs_productivity.csv` – Source data
- `dashboard.pbix` – Power BI Dashboard File
- `README.md` – This summary

📬 For insights, feedback, or collaboration: **gaiusufondu@gmail.com**
