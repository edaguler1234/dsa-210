# dsa-210
# DSA210 Project: Analyzing the Relationship Between Screen Time and Exam Periods

## Project Overview

This project studies the link between my screen-time habits and academic schedule, especially during exam weeks. The primary goal of this project is to understand how my screen time changes, especially during exam weeks.

My hypothesis is that screen time increases during exam weeks relative to other periods. This may be an indication of procrastination (e.g., using a phone for social media) or the use of electronics for studies. By comparing screen time data from my phone with the university exam schedule, this study intends to identify those changes in behavior.

---

## Dataset Description

### Screen Time Data

The **Screen Time (iOS)** feature will be used to obtain the dataset, which includes:

- **Timestamp**: The specific day when the screen time was recorded.
- **Total Screen Time**: The total amount of hours spent using a phone throughout the day.
- **App Usage Breakdown**: The amount of time spent on certain apps, such as Instagram, TikTok, Gmail, CollaNote, etc.
- **Unlock Count**: The number of times the phone has been unlocked in a 24-hour period.

### Exam Schedule Data

The exam schedule dataset will be taken from:

- The **official Sabancı University academic calendar** for term exams.
- Any **personal adjustments** (rescheduled exams, additional tests) will be manually added.

The dataset includes:

- **Exam Dates**: Exact dates of midterms, finals, and other major assessments.
- **Exam Types**: Midterm, final, or quiz.
- **Course Load**: Number of exams in a given week.

---

## Project Goals

### 1. Assessing Screen Time Trends
- Examine daily, weekly, and monthly trends in screen time.
- Determine the hours with the most screen time.
- Compare screen time for exam and non-exam weeks.

### 2. Getting Behavioral Understanding
- Determine trends in study-related app usage (e.g., productivity apps, e-books, note-taking apps) vs. procrastination (e.g., increased social media usage).
- Link **late-night phone usage** with exam dates.

### 3. Producing Visuals
- **Heatmaps**: Understand screen time distribution across a given period.
- **Time-series graphs**: Show variations in screen time during the semester.
- **Bar charts and line graphs**: Compare app usage patterns before, during, and after exam weeks.

### 4. Noting Important Discoveries
- Highlight unexpected findings, such as shifts in app usage behavior.
- List key trends and patterns.

---

## Planned Steps

### 1. Data Collection
- Export screen time data from **Screen Time (iOS)**.
- Retrieve exam schedule from the **Sabancı University academic calendar**.
- Convert all timestamps to a consistent format (local time).

### 2. Data Cleaning and Preprocessing
- Arrange datasets into a **CSV format** for easier manipulation.
- Verify data consistency (**missing values, duplicates**).
- Categorize app usage into relevant groups:
  - **Social Media**: Instagram, TikTok, Twitter
  - **Messaging**: WhatsApp, Telegram, Messenger
  - **Entertainment**: YouTube, Netflix, Spotify, Disney+
  - **Study-Related**: Google Docs, Notion, Coursera, Zoom, CollaNote

### 3. Exploratory Data Analysis (EDA)
- Determine daily **average screen time** over several weeks.
- Identify **screen time peaks** and compare usage **before, during, and after** exam periods.
- Examine relationships between **exam frequency** and screen time habits.
- Analyze **app usage patterns** to check if study-related app usage increases during exam weeks.

### 4. Visualization
- **Heatmaps**: Show screen time allocation across the semester.
- **Time-series graphs**: Display daily and weekly fluctuations in screen usage.
- **Bar charts**: Compare screen time during exams versus normal weeks.
- **Stacked area charts**: Visualize how different app categories contribute to total screen time.

### 5. Insights and Documentation
- Identify key trends (e.g., rise in late-night screen time before exams).
- Discuss whether increased screen time is due to **procrastination** or **study-related activities**.
- Present results clearly, highlighting conclusions and providing **recommendations for behavior change**.

### 6. Future Work and Recommendations
- Investigate **potential relationships between screen time and grades**.
- Suggest strategies to **reduce excessive screen time** and enhance **exam focus**.

---

## Tools and Libraries

The following tools will be used for data collection, processing, and analysis:

- **Python**: Primary programming language.
- **Pandas**: Data cleaning, filtering, and structuring.
- **Matplotlib & Seaborn**: Visualization of trends and patterns.
- **NumPy**: Statistical analysis and computations.
- **Google Takeout / Digital Wellbeing / iOS Screen Time**: Data export and collection.

---

## Final Deliverables

- A **detailed report** summarizing findings, insights, and key takeaways.
- A set of **visualizations** highlighting screen usage trends and behavioral patterns.
- A **PDF document** compiling all results, including charts, tables, and key analysis points.
