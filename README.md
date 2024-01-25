## Unveiling Trends: Exploring News Mining with Latent Dirichlet Allocation


<img src="lda_img.png" alt="LDA" width="400">


- [Context](#context)
- [Introduction](#introduction)
   + [Data exploring](data_explorer.ipynb)
- [ML models](#ml-models)
   + [building the model](loyalty_drivers.ipynb)
- [Most important features](#most-important-features)
   + [building SHAP values](loyalty_drivers.ipynb)
- [Budget optimization](#budget-optimization)
   + [building the optimization model](optimizing_loyalty.ipynb)
- [What if scenario](#what-if-scenario)
   + [DiCE model](optimizing_loyalty.ipynb)
- [Findings](#findings)


## Context


*Latent Dirichlet Allocation (LDA)* stands as a highly regarded algorithm within the domain of topic modeling, serving as a pivotal tool for revealing concealed thematic frameworks across extensive document collections. This algorithm is exceptionally beneficial for tasks in natural language processing and text mining, where its capabilities in structuring, deciphering, and encapsulating vast amounts of textual data are unparalleled.

In the context of analyzing a dataset comprised of various news articles related to the oil and gas industry, including factors influencing prices such as geopolitical tensions or wars, LDA becomes instrumental. The primary objective is to distill insights and identify distinct topics that encapsulate the essence of the information presented. This approach not only aids in understanding the multifaceted impacts on the energy sector but also in forecasting potential trends and shifts within the market.


## Introduction


*Latent Dirichlet Allocation (LDA)* is a generative statistical model that explains a set of observations through unobserved groups. In the context of text analysis, these observations are words collected into documents, and it posits that each document is a mixture of a small number of topics and that each word's presence is attributable to one of the document's topics.


<img src="sources.png" alt="sources" width="200">


<img src="words.png" alt="words" width="150">

```python

```
