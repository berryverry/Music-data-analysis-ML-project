# 🎶 Music data analysis / ML project 🎶

<br>

## ✅ Project background
### The recommendation algorithm of YouTube is great at suggesting similar types of music based on the user's selected preferences. However, it rarely recommends other types of music that the user may not usually listen to but is interested in exploring. This can lead to feelings of regret as the user may miss out on discovering new music. It would be better if the algorithm could suggest other types of music that people with similar music tastes might enjoy listening to.

### I had an idea to suggest music not only based on people's preferred genres but also based on their specific characteristics. For instance, if a certain genre of music is popular among people with insomnia, the algorithm could recommend music that has been proven to help alleviate insomnia. I conducted a project to analyze music-related data, specifically focusing on the relationship between music and mental health. Going forward, I believe it would be beneficial to incorporate the insights gained from this analysis into a recommendation system.

### After analyzing the data, I specifically examined the information related to insomnia. Subsequently, I conducted modelling and assessment to determine if individuals had insomnia based on various characteristics.

<br>

### ✔ Dataset
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
