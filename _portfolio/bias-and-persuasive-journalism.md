---
title: "A Computational Approach to Examining Bias and Persuasion in Political News"
excerpt: "Inspired by the plethora of machine learning models on bias detection, my project aims to analyze structures, linguistic styles, and rhetorical strategies that influence or challenge readers' perception of news trustworthiness and expertise. I will be centering my research around national and local news articles associated with Covid-19 and the 2020 election."
date: 2020-12-02
collection: portfolio
---
<i>Updated on December 23, 2020</i>

Fake news detection is a popular use case of machine learning models in the areas of computational linguistics and cybersecurity. Given the democratization of technology in recent years and a decades-old trend toward greater polarization in political discourse, it is ever more important for news readers to develop a critical mindset, regardless of the reputability of the news source. To a large extent, machine learning and natural langauge processing methodologies have helped both content distributors and consumers discern fiction from truth via auto-detection user interfaces. An algorithmic approach to fake news detection is largely favored by social networks due to their potential ability to reduce human bias and increase efficiency. However, these models and algorithms still need a great degree of fine tuning, as the ecosystem of fake and misleading news is rapidly evolving now more than ever.

Project Goal
-----------------

There is an abundance of literature in the field of computational disinformation research that facilitates auto-detection of fake and misleading news by developing hard classfications based on prelabeled datasets. This approach, though scalable, has its own limitations. For one, bias and neutrality are difficult to define in a political context &ndash; even the most matter-of-fact storytelling can be interpreted in unflattering ways. In addition, our news ecosystem incentivizes discourse competition over accuracy (Han, "Manufacturing Distrust", 130). We as readers are so acclimated to the elements of rhetoric spectacle that our perception of truth is most often subjective. 

Because discourse competition and bias are ubiquitous, I think the task of labeling is a major challenge in the disinformation space. Rather than drawing hard classification rules using known natural language processing pipelines, I am more intrigued by the way elements of bias are weaved into the seemingly "neutral" construction of journalistic texts. For this research project, I'd like to make an effort to answer the bigger question of how media can effectively shape or challenge readers' preexisting beliefs. I will draw upon past scholarship on persuasive journalism and utilize natural language processing techniques to analyze a variety of editorials and op-ed pieces on the current developments of Covid-19 and the presidential transition.

My research will consist of two parts. First, I'd like to investigate how media outlets with different political leanings and agendas report on the same issues differently. The classifical approach to natural language processing will allow me to assess the styles, lexicon, and sentiments of journalistic text. I would also look at  

<i>Handbook of Social Media Research Methods</i> identifies numerous features that affect news articles' expertise and trustworthiness, including but not limited to name, location, and credentials of the author, information completeness and timeliness, match to prior expectations, aesthetic presentation, literary appeal, reputability of the news source, and placement of the news article on the webpage (Rubin, V.L., "Deception Detection and Rumor Debunking for Social Media", 16). I will focus on some or all of these features for my analysis.

Below I will outline some of the top-level ideas I've conceived for the project. Out of concern for the lengthiness of the article, I will post the specifics of my research process and methodologies in separate blog posts.

Methodology
-----------

My project will follow the conventional data mining CRISP-DM pipeline. A rough draft of the process is as follows:

* Establish precise definitions for the concept of <i>credibility</i>, and identify linguistic cues that match these definitions.

* Come up with hypotheses and translate them into predictive features. 

* Specify the scope of the sample. Perform stratified sampling to collect news articles and comments from various sources detailing the 2020 election.

* <i>subject to change</i> Label the sample. I am hesitant to use existing fake news data sources due to concerns outlined above. I will build my own survey forms and recruit a small subset of survey takers to help with the labeling process. This step will ensure that the variable definitions are accurately communicated and that the survey generate fairly unbiased responses. The collected data will help me assess whether my definitions, hypotheses or surveys need further optimization.

* Distribute the optimized version of the survey and label at scale.

* BUild the data processing pipeline for the model fitting process. Perform data wrangling and imputation as needed.

* Fit both classification and regression models and select the most predictive and explainable features.

* Repeat any steps as needed. Depending on feasibility, I may build a user interface or dashboard for the final model.

Potential Use Cases
-------------------

One potential use case of the model is to help journalists and content curators gauge how their writing is likely to be perceived by readers. The model can also be used to inform interested readers of any implicit bias that may be present when they approach certain types of news articles. Ultimately, I envision this project to be more of a "mindfulness" exercise rather than a mechanical truth filter. I also want to acknowledge that my findings from this project will be limited in scope, as I am not (yet) a computational linguist nor a machine learning engineer. I'm happy to chat about my ideas and processes further, and in the meantime, I won't be offended in the least by honest and instructive feedback.
