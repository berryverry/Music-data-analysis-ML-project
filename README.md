# 🎵 Music Data Analysis & Mental Health Modeling 🎵 
<sub><i>A data science project exploring the relationship between music and mental health</i></sub>

---

## 📌 Project Background

The recommendation algorithm of YouTube is great at suggesting music **within the user’s comfort zone**, but not so much **beyond it**. This can result in missed opportunities to discover new genres or emotionally helpful music.

> _What if music recommendations could be tailored not only by genre but also by psychological needs?_

Inspired by this question, I analyzed music-related survey data focusing on **the relationship between music habits and mental health**, especially **insomnia**.

---

## 🔍 Key Research Questions

I conducted exploratory data analysis (EDA) to answer questions such as:

- 📊 **User Behavior**
  - What are the top-ranked music streaming services?
  - BPM patterns across preferred genres
  - Do musicians also compose music? Vice versa?
  - How much time do composers or instrumentalists spend listening to music?
  - Do people who listen to music while working spend more time on average?

- 🌐 **Listening Habits**
  - Proportion of users who listen to foreign-language music
  - How does the number of genres relate to exploratory tendencies?

- 🧠 **Mental Health Correlations**
  - What is the correlation between **anxiety, depression, insomnia, OCD**?
  - Does music listening time affect mental health metrics?
  - Do music effects (e.g., healing, emotional impact) show a pattern with mental health?
  - Do music creators (composers, instrumentalists) show higher or lower mental distress?

- 🎧 **Genre-Based Insights**
  - How favorite genres relate to anxiety, depression, insomnia, OCD
  - Does genre diversity help with mental health?

---

## 🧪 Modeling: Predicting Insomnia

After EDA, **5 key features** with potential relationships to insomnia were selected:

| Feature | Type |
|--------|------|
| 🎼 Composing music | Binary |
| 🎹 Playing an instrument | Binary |
| 🎶 Number of music genres listened to | Numerical |
| 😔 Depression level | Continuous |
| 😵 OCD level | Continuous |

I framed it as a **binary classification** problem:  
**“Does the user suffer from insomnia?”**  

The final model used was:

> ✅ **Logistic Regression**

I evaluated performance using standard classification metrics (accuracy, recall, etc.) and validated the features' relevance in predicting insomnia symptoms.

---

## 📈 Insights & Reflection

- Strong correlations exist between **musical activity** and **mental health conditions**.
- The project revealed that music-based features can be **meaningful proxies for emotional states**.

> _This project inspired me to further explore music-aware recommendation systems that respect emotional and mental needs, not just user clicks._

---

## 🛠️ Tools Used

- **Languages:** Python  
- **Libraries:** pandas, matplotlib, seaborn, plotly, scikit-learn  
- **Techniques:** Data preprocessing, correlation analysis, EDA, Logistic Regression, binary classification  
- **Visualization:** Pair plots, scatter plots, bar charts, heatmaps  

---

## 📎 Dataset
#### Data: Music & Mental Health Survey Results from Kaggle

<br>

> Description of the data

>> 0 represents "No" and 1 represents "Yes" for columns consisting of rows of 0s and 1s.

<br>

* Age: Respondent's age

* Primary streaming service: Respondent's primary streaming service

* Hours per day: Number of hours the respondent listens to music per day

* While working: Does the respondent listen to music while working?

* Instrumentalist: Does the respondent play an instrument regularly?

* Composer: Does the respondent compose music?

* Fav genre: Respondent's favorite or top genre

* Exploratory: Does the respondent actively explore new artists/genres?

* Foreign languages: Does the respondent regularly listen to music with lyrics in a language they are not fluent in?

* BPM: Beats per minute of favorite genre

* Frequency count: Number of music genres people listen to<br>(Sum of classical, country, edm, folk, gospel, hip hop, jazz, k pop,<br>latin, lofi, metal, pop, r&b, rap, rock, video game music)

* Average frequency: The average frequency of listening to music genres<br>(Average of Classical, Country, EDM, Folk, Gospel, Hip hop, Jazz, K pop,<br>Latin, Lofi, Metal, Pop, R&B, Rap, Rock, Video game music)

* Classical, Country, EDM, Folk, Gospel, Hip hop, Jazz, K pop,<br>Latin, Lofi, Metal, Pop, R&B, Rap, Rock, Video game music<br>: How frequently the respondent listens to each genre, on a scale of 0-4<br>(0: Never, 1: Rarely, 2: Sometimes, 3: Very frequently)

* classical, country, edm, folk, gospel, hip hop, jazz, k pop,<br>latin, lofi, metal, pop, r&b, rap, rock, video game music<br>: The binary status of whether each genre is listened to or not

* Anxiety: Self-reported anxiety, on a scale of 0-10

* Depression: Self-reported depression, on a scale of 0-10

* Insomnia: Self-reported insomnia, on a scale of 0-10

* OCD: Self-reported OCD, on a scale of 0-10

* Music effects: Does music improve/worsen respondent's mental health conditions?, on a scale of 0-2<br>(0:Worsen, 1: No effect, 2: Improve)
