---
title: "A Computational Approach to Assessing Readers' Perception of News Trustworthiness"
excerpt: "Inspired by the plethora of machine learning models on fake new detection, my project aims to analyze linguistic cues, rhetorical strategies and other non-linguistic factors that influence readers' perception of bias and deception in political news. I will be primarily focusing on articles about the 2020 election."
date: 2020-12-02
collection: portfolio
---
<i>Updated on December 6, 2020</i>

Fake news detection is a popular use case of machine learning models in the areas of computational linguistics and cybersecurity. Given the democratization of technology in recent years and a decades-old trend toward greater polarization in political discourse, it is ever more important for news readers to develop a critical mindset, regardless of the reputability of the news source. To a large extent, machine learning and natural langauge processing methodologies have helped both content distributors and consumers discern fiction from truth via auto-detection user interfaces. An algorithmic approach to fake news detection is largely favored by social networks due to their potential ability to reduce human bias and increase efficiency. However, these models and algorithms still need a great degree of fine tuning, as the ecosystem of fake and misleading news is rapidly evolving now more than ever.

Project Goal
-----------------

There is an abundance of literature in the field of computational disinformation research that approaches auto-detection of fake and misleading news by developing hard classfications based on predetermined labels. This approach, though fairly reproducible and explainable, has its own limitations. For one, the concept of "neutral and non-partisan information" is difficult to define &ndash; even the most matter-of-fact storytelling can contain biased elements. In addition, our current social and political system incentivizes discourse competition over accuracy (Han, "Manufacturing Distrust", 130). We as readers are so acclimated to the elements of rhetoric spectacle that our perception of truth is most often subjective. 

Because of these limitations, the task of labeling is a major challenge in the classification pipeline. Therefore, I'd like to investigate how we as content consumers identify elements of bias and deception in political news. Rather than having machines "learn" the linguistic characteristics of fake news, I decide not to rely on a hard classification model. Instead, my goal is to assess the effect of rhetorical strategies and certain non-linguistic factors on readers' subjective assessment of bias and deception. 

<i>Handbook of Social Media Research Methods</i> identifies numerous features that affect news articles' credibility and trustworthiness, including but not limited to name, location, and credentials of the author, information completeness and timeliness, match to prior expectations, aesthetic presentation, literary appeal, reputability of the news source, and placement of the news article on the webpage (Rubin, V.L., "Deception Detection and Rumor Debunking for Social Media", 16). Here, my analysis will focus primarily on linguistic cues and source reputability while controlling for the other variables.

Below I will outline some of the top-level ideas I've conceived for the project. Out of concern for the lengthiness of the article, I will post the specifics of my research process and methodologies in separate blog posts.

Methodology
-----------

My project will follow the conventional data mining CRISP-DM pipeline. A rough draft of the process is as follows:

* Establish precise definitions for the key concepts at question, including <i>trustworthiness</i>, <i>bias</i>, and <i>deception</i>. Should we classify an opinionated news article that touches on all the factual events as real or misleading? How do we quantify the degree of bias? How to communicate these definitions to my survey takers? These are the questions I hope to address.

* Design a preliminary list of hypotheses to serve as the x variables of my supervised learning model. Select linguistic cues that make practical sense for the project and translate them into predictive features. 

* Specify the scope of the sample. Perform stratified sampling to collect news articles from various sources detailing the 2020 election.

* Label the sample. I am hesitant to use existing fake news data sources due to concerns outlined above. I will build my own survey forms and recruit a small subset of survey takers to help with the labeling process. This step will ensure that the variable definitions are accurately communicated and that the survey generate fairly unbiased responses. The collected data will help me assess whether my definitions, hypotheses or surveys need further optimization.

* Distribute the optimized version of the survey and label at scale.

* BUild the data processing pipeline for the model fitting process. Perform data wrangling and imputation as needed.

* Fit both classification and regression models and select the most predictive and explainable features.

* Repeat any steps as needed. Depending on feasibility, I may build a user interface or dashboard for the final model.

Potential Use Cases
-------------------

One potential use case of the model is to help journalists and content curators gauge how their writing is likely to be perceived by readers. The model can also be used to inform interested readers of any subconscious bias that may be present when they approach certain types of news articles. Ultimately, I envision this project to be more of a "mindfulness" exercise rather than a mechanical truth filter. I also want to acknowledge that my findings from this project will be limited in scope, as I am not (yet) a computational linguist nor a machine learning engineer. I'm happy to chat about my ideas and processes further, and in the meantime, I won't be offended in the least by honest and instructive feedback.
