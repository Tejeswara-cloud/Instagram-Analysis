# 📊 Alfido Tech Instagram Engagement Analysis

## 📌 Project Overview

This project analyzes Instagram engagement data to identify patterns in **content performance, hashtags, likes, comments, follower engagement, and posting strategies**.

The analysis was developed as part of an **AI-Powered Data Analysis Remote Internship** project for **Alfido Tech**.

The goal is to use data-driven insights to understand what types of Instagram content generate higher engagement and develop practical strategies to improve audience interaction.

---

## 🎯 Objectives

* Analyze Instagram posts and engagement data.
* Calculate likes and comments per follower.
* Compare engagement across different content types.
* Analyze hashtag performance.
* Study follower activity and engagement signals.
* Analyze posting dates and times.
* Create meaningful data visualizations.
* Develop an Instagram content calendar.
* Recommend strategies to increase engagement.

---

## 📂 Dataset

The project uses seven CSV datasets:

| Dataset          | Description                             |
| ---------------- | --------------------------------------- |
| `users.csv`      | Instagram user/profile information      |
| `photos.csv`     | Instagram post information              |
| `likes.csv`      | Like activity for posts                 |
| `comments.csv`   | Comment activity for posts              |
| `follows.csv`    | Follower/following relationships        |
| `tags.csv`       | Hashtag information                     |
| `photo_tags.csv` | Relationship between posts and hashtags |

---

## 🛠️ Technologies Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📈 Seaborn
* ☁️ Google Colab / Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Understanding

* Checked dataset dimensions.
* Examined columns and data types.
* Viewed sample records.
* Checked missing values.
* Checked duplicate records.

### 2. Date & Time Analysis

Post, like, comment, and follow timestamps were converted into proper datetime format.

The analysis also checks whether sufficient timestamp variation exists to identify high-performing posting days and hours.

### 3. Engagement Analysis

Calculated:

```text
Total Engagement = Likes + Comments

Likes per Follower = Likes / Followers

Comments per Follower = Comments / Followers

Engagement per Follower =
(Likes + Comments) / Followers
```

These metrics help compare post performance while considering audience size.

### 4. Content Type Analysis

Compared engagement across:

* Photo
* Video
* Carousel

Metrics analyzed include:

* Average likes
* Average comments
* Average engagement
* Engagement per follower

### 5. Hashtag Analysis

Analyzed hashtags based on:

* Number of posts
* Average likes
* Average comments
* Average engagement
* Engagement per follower

### 6. Follower Analysis

Analyzed:

* Follower counts
* Active followers
* Active follower rate
* Follower engagement signals

### 7. Data Visualization

Created visualizations including:

* Posts by content type
* Average engagement by content type
* Top-performing hashtags
* Engagement distribution
* Likes vs comments
* Follower activity

---

## 📊 Key Data Insight

The supplied dataset contains very limited timestamp variation, with the relevant activity records concentrated at the same timestamp.

Therefore, the dataset does **not provide enough evidence to claim a statistically reliable "best posting time."**

Instead, a controlled posting-time experiment is recommended for Alfido Tech.

---

## 📅 Recommended Posting Calendar

| Day       | Time     | Content                 |
| --------- | -------- | ----------------------- |
| Monday    | 7:30 PM  | Educational Carousel    |
| Tuesday   | 12:30 PM | Tutorial Reel           |
| Wednesday | 7:30 PM  | Project / Success Story |
| Thursday  | 12:30 PM | Trending Tech Reel      |
| Friday    | 7:30 PM  | Career / AI Carousel    |
| Saturday  | 11:00 AM | Behind-the-Scenes Reel  |
| Sunday    | —        | Stories / Poll / Q&A    |

These times are proposed as **initial testing slots**, not statistically proven optimal times.

---

## 🚀 Strategies to Increase Engagement

### 1. Hook-First Reels

Use a strong hook within the first 1–2 seconds to capture attention.

### 2. Create Saveable Carousels

Publish useful content such as:

* Python roadmaps
* AI tutorials
* Interview questions
* Coding tips
* Data Analytics guides
* Power BI tips

### 3. Encourage Conversations

Use specific questions in captions and respond to comments to encourage discussions.

### 4. Use Relevant Hashtags

Combine relevant niche technology hashtags with broader discovery hashtags instead of using unrelated popular hashtags.

### 5. Build Content Series

Create recurring content such as:

```text
Tech Tip Tuesday
Python in 60 Seconds
AI Friday
Data Analyst Roadmap
Career Sunday
```

---

## 📈 Recommended KPIs

For future Instagram performance tracking:

* Engagement Rate
* Reach
* Likes
* Comments
* Saves
* Shares
* Profile Visits
* Follows per Post
* Follower Growth
* Engagement per Follower

---

## 📁 Project Structure

```text
Alfido-Tech-Instagram-Analysis/
│
├── data/
│   ├── comments.csv
│   ├── follows.csv
│   ├── likes.csv
│   ├── photo_tags.csv
│   ├── photos.csv
│   ├── tags.csv
│   └── users.csv
│
├── Alfido_Tech_Instagram_Analysis.ipynb
│
├── Alfido_Tech_Instagram_Strategy.docx
│
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Alfido-Tech-Instagram-Analysis.git
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook Alfido_Tech_Instagram_Analysis.ipynb
```

### 4. Run all cells

Make sure the seven CSV files are available in the expected `data` directory or update the notebook's data path.

---

## 📌 Conclusion

This project demonstrates how Python-based data analysis can be used to evaluate Instagram engagement and convert social-media activity into actionable business insights.

The analysis focuses on **content performance, hashtag effectiveness, follower engagement, and experimental posting strategies** to help Alfido Tech improve its Instagram presence.

---

## 👨‍💻 Author

**K. Tejeswara**

B.Tech — Computer Science Engineering (AI & Data Science)

### Skills Demonstrated

`Python` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn` • `Data Analysis` • `Data Visualization` • `Social Media Analytics`

---

⭐ If you find this project useful, consider giving the repository a star!
