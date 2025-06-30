# 📊 YouTube Spam Abuse Analytics Dashboard

## 🔗 Live Dashboard 
https://public.tableau.com/app/profile/adithya.prahasith/viz/Book1_17513114090550/Dashboard1
---
## 🚀 Project Objective

- This project simulates a Trust & Safety analytics dashboard for detecting and monitoring spam abuse on 2k YouTube comments across 5 videos data. 
-Built using Tableau, it analyzes spam patterns across users, videos, and time to support operational decisions such as policy enforcement, content escalation, and abuse mitigation.
---
## 📁 Dataset

**Source:** Kaggle YouTube Spam Comments Dataset  
Link: https://www.kaggle.com/datasets/ahsenwaheed/youtube-comments-spam-dataset
**Features used:**
- `author`: username of the commenter  
- `content`: the comment text  
- `video_name`: YouTube video title  
- `date`: date of comment  
- `class`: 1 = spam, 0 = legitimate  

---

## 📊 Dashboard KPIs & Visuals

| KPI | Description |
|-----|-------------|
| Total Comments | Overall comment volume analyzed |
| Abuse Comments | Count of comments flagged as spam |
| Spam Rate (%) | % of total comments classified as spam |
| Avg Spam/Clean Length | Average word length of spam vs clean comments |

### Visual Sections:
- 📈 **Spam Rate by Video** – Surface most abused videos
- 👥 **Top Spamming Authors** – Identify repeat spam actors
- 🕒 **Monthly Trends** – Detect spikes and abuse waves
- 🔁 **New vs Repeat Authors** – Separate chronic abuse from one-time spam


---

## 🧠 Key Insights 

- Spam comments peaked in late 2014, a small number of videos (fewer than 10) accounted for the majority of spam activity, with spam rates consistently above 40%.
- This suggests that content-based targeting or video popularity likely played a role in attracting spam.
- 51% of all comments in the dataset were classified as spam.
- Repeat offenders contributed disproportionately to abuse volume.
- Spam comments are, on average, 3x longer than clean comments — suggesting long-form promo or bot behavior.

---

## 🔗 Live Dashboard 
https://public.tableau.com/app/profile/adithya.prahasith/viz/Book1_17513114090550/Dashboard1


---

## 📌 Limitations of Current Analysis
- Data for Moderators activity , spam review dates, escalated comments activity is not availble in this dataset
- i suggest, adding these details to the dataset in the future would be beneficial to streamline the SLA Complaince tracking.

---
- By Adithya Prahasith. 
-Contact me: adithyaprahasith@gmail.com  
