# dynamic-sentiment-AVs
## 🎯 Description
An end-user sentiment assessment tool to predict autonomous vehicles (AVs) adoption and commercialization.

## 💭 Scope definition and purpose
Our study complements previous research on social media platform user sentiment on AVs by (a) introducing a dynamic component by observing sentiment across time and critical news events, (b) correlating key user-discussed topics with shifts in user sentiment, and (c) predicting user sentiment based on news’ underlying topic assessment. We will leverage NewsCatcherAPI to extract filtered topic-specific news posts from the last 5 years to train a  model using topic scores for sentiment prediction.

## 🎓 Context
Our research is part of a project in a [text mining](https://www.mcgill.ca/study/2023-2024/courses/insy-448) class at McGill University.

## 💻 Technology and techniques
- [Python](python.org)
- [R](https://posit.co/products/open-source/rstudio/)
- Sentiment analysis using [VADER](https://www.nltk.org/_modules/nltk/sentiment/vader.html) and [TextAnalyzer](http://textanalyzer.org/lex/advanced)
- GPT-augmented topic modeling
- Regression inference (ridge)
- Deep learning models (RNN)
- Reddit [API](https://www.reddit.com/dev/api/)
- [NewsCatcherAPI](https://www.newscatcherapi.com/) for news scraping to extract topic-specific media postings and releases for model training data.  

## ✍🏽 Author(s)
A project by [Zachariya Sow](https://github.com/ZachariyaSow), Paul Prindiville-Porto, Gabriel Abbas, and Artiom Bakhrakh.
### ✉️ Contact information
- Academic: zachariya.sow@mail.mcgill.ca
- Personal: zachariyasow@gmail.com

## 📖 Previous literature
- Achal Shankar Gupta, & Sharma, S. (2022). [Analysis of Public Perception of Autonomous Vehicles Based on Unlabelled Data from Twitter](https://doi.org/10.1007/978-981-19-5331-6_7)
- Ding, Y., Korolov, R., Al) Wallace, W., & Wang, X. (Cara). (2021). [How are sentiments on autonomous vehicles influenced? An analysis using Twitter feeds](https://doi.org/10.1016/j.trc.2021.103356). Transportation Research Part C: Emerging Technologies, 131, 103356. 
