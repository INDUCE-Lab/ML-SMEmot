# ML-NLPEmot

ML-NLPEmot: Machine Learning-Natural Language Processing Event-Based Emotion Detection Proactive Framework Addressing Mental Health

A novel Twitter dataset of over 11 Thousands COVID-19 vaccine-related-and-non-vaccine-related tweets.

We collect tweets posted between 29-01-2020 and 31-07-2022. We divide the duration into three periods:

1) 29-01-2020 – 14-09-2020, from the first case of COVID-19 in UAE until the vaccination announcement, 2) 14-09-2020 – 09-12-2020, from the announcement of vaccination until the commencement of the vaccination program, and 3) 09-12-2020 – 31-07-2022, which is from the commencement of the vaccination program till the time of writing the paper

The information related to the Tweets dataset is represented in the following file:

**dataset/UAE-COVID-19-Vaccine-Related-Tweets_Annotated** which includes all the tweets COVID-19-vaccine-related in UAE annotated with **TextBlob**, **VADER**, **Canadian Emotion**, and the **final annotation** which constitute of the **three sentiments (negative, positive, and neutral),** and **Plutchik’s eight emotions (joy, fear, anger, anticipation, sadness, surprise, disgust, and trust)**.

We comply with Twitter’s Terms of Service by anonymizing the datasets which constitute tweet IDs.  

## Abstract

Global rapidly evolving events, e.g., COVID-19, are usually followed by countermeasures and policies. As a reaction, the public tends to express their emotions on social media platforms. Therefore, predicting emotional responses to events is critical to put a plan to avoid risky behaviors. This paper proposes a Machine Learning-Natural Language Processing-based framework to detect public emotions based on social media posts in response to specific events. It presents a precise measurement of population-level emotions which can aid governance in monitoring public response and guide it to put in place strategies such as targeted monitoring of mental health, to react to a rise in negative emotions in response to lockdowns, or information campaigns, for instance in response to elevated rates of fear in response to vaccination programs. We evaluate our framework by extracting 15,455 tweets. We annotate and categorize the emotions into 11 categories based on Plutchik’s study of emotion and extract the features using a combination of Bag of Words and Term Frequency-Inverse Document Frequency. We filter 813 COVID-19 vaccine-related tweets and use them to demonstrate our framework’s effectiveness. Numerical evaluation of emotions prediction using Random Forest and Logistic Regression shows that our framework predicts emotions with an accuracy up to 95.5%.

## About this work

This work proposes a novel Machine-Learning event-based framework to detect people emotions on Social Media. Unlike related work in the literature which focus on polarity emotions (negative, positive, and neutral), this paper detects Plutchik’s eight emotions (joy, fear, anger, anticipation, sadness, surprise, disgust, and trust), in addition to polarity emotions.

We create a novel twitter dataset annotated with emotions.  This dataset is a vehicle for research on Social Media Emotion Detection.


## Cite this work
L. Ismail, N. Shahin, H. Materwala, A. Hennebelle and L. Frermann, "ML-NLPEmot: Machine Learning-Natural Language Processing Event-Based Emotion Detection Proactive Framework Addressing Mental Health," in IEEE Access, vol. 11, pp. 144126-144149, 2023, doi: 10.1109/ACCESS.2023.3343121.

