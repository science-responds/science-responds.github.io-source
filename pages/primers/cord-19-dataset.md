---
title: CORD-19 Dataset
permalink: /primers/cord-19-dataset/
wishlist: yes
---

# CORD-19 Dataset

Author: Rishi Patel  
Reviewer: **Needs reviewing**

# The CORD-19 Challenge
In response to the COVID-19 pandemic, the [Allen Institute for AI](https://allenai.org/) has partnered with leading research groups to prepare and distribute the COVID-19 Open Research Dataset (CORD-19), a free resource of over 52,000 scholarly articles, including over 41,000 with full text, about COVID-19 and the coronavirus family of viruses for use by the global research community.

This dataset is intended to mobilize researchers to apply recent advances in natural language processing to organize and group articles to allow researchers fast easy access to new advances in the fight against this infectious disease. This is a crucial goal as the medical community, public health officials and other academic experts try to keep up with the rapid increase in literature related to COVID-19. The corpus  will be updated weekly as new research is published in peer-reviewed publications and archival services like [bioRxiv](https://www.biorxiv.org/), [medRxiv](https://www.medrxiv.org/), and others.

[CORD-19 Explorer](https://cord-19.apps.allenai.org/) is a quick and easy way to search the CORD-19 corpus, and [CoViz](https://coviz.apps.allenai.org) allows you to discover associations between concepts appearing in the dataset. Or, get started by downloading the complete data at [semanticscholar](https://pages.semanticscholar.org/coronavirus-research)

Kaggle is hosting the [COVID-19 Open Research Dataset Challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) , a series of important questions designed to inspire the community to use CORD-19 to find new insights about the COVID-19 pandemic including the natural history, transmission, and diagnostics for the virus, management measures at the human-animal interface, lessons from previous epidemiological studies, and more.
## Code Primers
Natural language processing (NLP) is a vast field of study and often involves large datasets without any prior labeling. Topic modeling in python or a careful investigation in SQL queries can be used to organize the publications into topics e.g. transmission and incubation of the virus, social impacts, risk factors, potential for vaccines etc.  A key component of the user interface would be its ease of use as a twiki, a search engine, or SQL database (an example search engine [Discovid](https://discovid.ai/search) ). Listed below are some python tools which are useful in embarking on this project:

  * First steps of mining the text is often breaking up the corpus based on key phrases and "tokenizing" sentences. [SpaCy](https://spacy.io/) is an open source python tool for doing this generally. For biomedical, scientific or clinical text, [scispacy] (https://allenai.github.io/scispacy/) is a python library of spaCy models trained specifically on biomedical text.

  * Text ranking tools also exist to identify key phrases, infer links between words, and extract summary phrases from the body text. Many such tools exist, but here I list two to kickstart investigating the text. [pyTextRank] (https://github.com/DerwenAI/pytextrank) is a graph-based text ranking alogrithm. [RAKE](https://pypi.org/project/rake-nltk/) creates a covariance matrix based on word frequency and co-occurence with other words.

  * [K-means clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) is one approach to cluster key words from the corpus into candidate topics.
  * [Latent Dirichlet Allocation](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.LatentDirichletAllocation.html#id1) is a well studied method of finding topics in a corpus based on the Dirichlet probability distribution.</p>
  * [Example code](https://github.com/rpatelCERN/CORD19/) shows how the above tools could fit together to mine the text for key words and map them onto topics.

## Using the CORD-19 Dataset to Cross-reference

Since CORD-19 consists of peer-reviewed articles, it can be used as a knowledge base to cross-reference other orthogonal text data sources and aggregate information for each topic. Listed below are other open source COVID-19 datasets that could be used for this purpose :
  * [WikiProject COVID-19](https://www.wikidata.org/wiki/Wikidata:WikiProject_COVID-19)  - Project to collect Wikidata resources related to COVID-19 and SARS-CoV-2. Resources may also relate to relevant epidemiological events like 2019–20 COVID-19 pandemic.
  * [C3.ai COVID-19 Data Lake](https://c3.ai/covid/) - a collection of datasets from governmental, NGO, and commercial sources.
  * [NY Times COVID-19 in the US](https://github.com/nytimes/covid-19-data) -  cumulative counts of coronavirus cases in the United States, at the state and county level, over time.
  * [Springer Nature](https://www.springernature.com/gp/researchers/campaigns/coronavirus)  -  open source research articles, preprints, and in some cases underlying datasets from Springer Nature. </p>
