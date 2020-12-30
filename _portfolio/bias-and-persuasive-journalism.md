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

My research will consist of two parts. First, I'd like to compare and contrast how media outlets with different political leanings and agendas report on the same issues differently. The classical approach to natural language processing will allow me to assess the styles, lexicon, and sentiments of journalistic text. I would also look at these articles at the topic and source level, examining the relative frequency of reports on a specific issue for each target media outlet in my database. This approach will offer insights into the extent of selection and partisan bias in major news outlets and the way these biased elements are carried out linguistically. 

The second part of the research will delve into the themes of persuasion and interaction. What structural and stylistic strategies do journalists employ, either consiously or subconsciously, to influence the opinion of the readers? Past scholarship in linguistics has proposed the concept of metadiscourse, a set of linguistic devices deemed essential to persuasive writing, as it is "used to communicate attitudes and to mark the structural properties of a piece of discourse" (Moghadam, <i>Persuasion in Journalism: A Study of Metadiscourse in Texts</i>). In his 2005 book, Hyland theorizes a set of metadiscourse markers used as instruments for persuasion in multi-lingual and multi-cultural contexts (Hyland, <i>Metadiscourse: Exploring Interaction in Writing</i>). By exploring the ways in which these markers are used in journalistic text via machine learning algorithms, I plan to investigate the persuasive intention of political news articles as well as the effectiveness of the agenda.

Methodology
-----------

My project will follow the conventional data mining CRISP-DM pipeline. A rough draft of the process is as follows:

* Set up preliminary hypotheses for my research questions. 

* Specify the scope of the sample and collect articles from various APIs, national and local news sites.

* Perform web scraping and text preprocessing to prepare data in a format that could be fed to machine algorithms. Leverage known NLP practices and apply new labeling methods as needed. 

* Utilize natural language processing to perform frequency analysis, clustering analysis, sentiment analysis, etc.

* Evaluate and validate the results.

Potential Use Cases
-------------------

One potential use case of the model is to help journalists and content curators gauge how their writing is likely to be perceived by readers. The model can also be used to inform interested readers of any implicit bias that may be present when they approach certain types of news articles. Ultimately, I envision this project to be more of a "mindfulness" exercise for the benefit of the media community. I also want to acknowledge that my findings from this project will be limited in scope, as I am not (yet) a computational linguist nor a machine learning engineer. I'm happy to chat about my ideas and processes further, and in the meantime, I won't be offended in the least by honest and instructive feedback.
