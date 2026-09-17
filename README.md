# Student Academic Performance Prediction & Profiling

## Group Members
- Leen Alfuraih (ID: 446202430)
- Lana Alrubaiya (ID: 446202797)
- Alanoud Aldosari (ID: 446202553)
- Student Name 4 (ID: XXXXXXXXX)

---

## 1. Problem Statement
Academic underachievement and student retention are critical challenges in higher education institutions. Identifying at-risk students often happens reactively when grades are finalized, leaving minimal room for timely guidance or academic remediation. The central question this project addresses is: **How can institutions predict student academic performance early in the semester using demographic, socioeconomic, and study-related behavioral indicators?**

## 2. Project Motivation
Education drives individual growth and long-term societal progress. Providing educators and academic advisors with early, data-informed insights offers significant advantages:
- **Early Intervention:** Identifies students struggling with foundational concepts or engagement before examinations, allowing for targeted academic support and tutoring.
- **Strategic Resource Allocation:** Directs advising and mentorship programs specifically to cohorts with higher vulnerability to academic drop-off.
- **Behavioral Understanding:** Uncovers how daily lifestyle and study factors—such as weekly study hours, attendance records, parental support, and screen time—impact cumulative performance.

## 3. Project Goals
This project applies fundamental data mining techniques to extract actionable educational patterns:

* **Classification Task:**
  Develop and evaluate supervised classification models (specifically Decision Trees) to predict a student's final grade category (`GradeClass` from 0 to 4). The analysis assesses accuracy across multiple training/testing partitions (90/10, 80/20, 70/30) and split measures (Gini index and Information Gain/Entropy).

* **Clustering Task:**
  Utilize unsupervised K-Means clustering across numerical lifestyle and study attributes to discover natural student segments. Optimal grouping will be assessed across multiple K values using Elbow analysis and Silhouette coefficients to reveal distinct behavioral profiles without prior label knowledge.
