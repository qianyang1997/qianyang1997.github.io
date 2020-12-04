---
title: "A Computational Approach to Assessing News Trustworthiness in a Digital World"
excerpt: "Inspired by the plethora of machine learning models on fake new detection, my project aims to assess the correlation between certain rhetorical strategies and news readers' perception of bias and deception in online media sources. I will be primarily focusing on articles detailing the 2020 election."
date: 2020-12-02
collection: portfolio
---

Fake news detection is a popular use case of machine learning models in the areas of computational linguistics and cybersecurity. Given the democratization of technology in recent years and a decades-old trend toward greater polarization in political discourse, it is ever more important for news readers to develop a critical mindset, regardless of the reputation of the news source. To a large extent, machine learning and natural langauge processing methodologies have helped both content distributors and consumers discern fiction from truth. However, these models and algorithms still need a great degree of fine tuning, as the ecosystem of fake and misleading news is rapidly evolving now more than ever.

Problem Statement
-----------------

Most current literature in the field of computational disinformation research focuses on auto-detection of fake and misleading news, developing hard classfications based on predetermined labels. This approach, though highly reproducible and pragmatic, has its own limitations. For one, the concept of "neutral and non-partisan information" is difficult to define &dash; even the most matter-of-fact storytelling cannot be completely devoid of bias. In addition, our social and political system incentivizes discourse competition over accuracy. We as readers are so acclimated to the elements of rhetoric spectacle that our perception of truth is very likely to be subjective in the majority of cases. 

Because of these limitations and loose definitions, the task of labeling is a major challenge in the classification pipeline. Therefore, for this project, I would like to investigate how we as content consumers perceive the elements of bias and deception in political news. Rather than having machines "learn" the linguistic characteristics of fake news, I decide not to rely on a hard classification model. Instead, my goal is to assess the effect of certain rhetorical strategies and literary devices on readers' subjective assessment of bias and deception. 

Methodology
-----------

The steps I wish to take for the project are as follows:

* Come up with precise definitions for the key concepts at question. A major challenge of traditional fake detection models is a loosely defined boundary between real and falsified information. Should we classify an opinionated news article that touches on all the factual events as real or misleading? How do we quantify the degree of bias? These are the questions I hope to address.

* Design a preliminary list of hypotheses to serve as the x variables of my supervised learning model. Select linguistic cues that make practical sense for the project and translate them into predictive features. 

* Specify the scope of the sample. Perform stratified sampling to collect news articles from various sources detailing the 2020 election.

* Label the sample. I am hesitant to use existing fake news data sources due to concerns outlined above. I will recruit a small subset of volunteers to help with the labeling process. This step will ensure that the variable definitions are accurately communicated and that the survey generate fairly unbiased reponses. The collected data will help me assess whether my definitions, hypotheses or surveys need further optimization.

* Distribute the optimized survey and recruit more volunteers to label at scale.

* BUild the data processing pipeline for the model fitting process. Perform data wrangling and imputation as needed.

* Fit both classification and regression models and select the most predictive and explainable features.

* Repeat any steps as needed. Depending on feasibility, I may build a user interface or dashboard for the final model.

Potential Use Cases
-------------------

One potential use case of the model is to help journalists and content curators gauge how their writing is likely to be perceived by readers. The model can also be used to inform interested readers of any subconscious bias that may be present when they approach certain types of news articles. Ultimately, I envision this project to be more of a "mindfulness" exercise rather than a news filtering tool. It is important to acknowledge that my findings from this project will be limited in scope (just as all the models out there) and therefore no hard universal truth (which I'm adamently against) should be derived from it.
