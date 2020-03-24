---
title: Resources
permalink: /resources/
---

# COVID-19 ML and Tech Related Open Science Projects

## Context

This document is a place to collect details on open science/open source technology based projects related to COVID-19. This includes modeling, public health interventions, medical technology, resource distribution, and more. Please feel free to add your own project or other projects that you know of! We just ask that you keep the doc organized and follow the format below:

Project Title
Description: A brief description of the project
Resources: Links to important info about the project (include related articles if possible!)
Looking for: What kind of folks can best contribute to this project?
How to get involved: Include links to sign up forms, GitHub issues, Slack channels, etc

Let’s make the most of our work from home time and try to help our fellow humans (and maybe learn some new skills!). 

To reach out to the doc creator, please email savannah.thais@gmail.com.

## Projects

### CORD19 Data Set

**Description:** This open dataset is supported by the White House Office of Science and Technology Policy, The Chan Zuckerberg Initiative, Microsoft Research, The Allen Institute for AI, The NIH Library of Medicine, Georgetown’s Center for Security and Emerging Technology, Cold Spring Harbor Lab, and Kaggle AI. CORD-19 is a resource of over 29,000 scholarly articles, including over 13,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. The dataset represents the most extensive machine-readable coronavirus literature collection available for data and text mining to date and is updated as new research is published in peer-reviewed publications and archival services.

**Resources:**
  * [Kaggle Challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)
  * Georgetown’s Center for Security and Emerging Technology CORD19 [webpage](http://cset.georgetown.edu/covid-19-open-research-dataset-cord-19/)
  * Semantic Scholar CORD19 [webpage](https://pages.semanticscholar.org/coronavirus-research)
  * Tech Crunch [article](https://techcrunch.com/2020/03/16/coronavirus-machine-learning-cord-19-chan-zuckerberg-ostp/)
  * Unite.AI [article](https://www.unite.ai/open-data-set-on-covid-19-released-for-machine-learning/)
  * Whitehouse [Call to Action](https://www.whitehouse.gov/briefings-statements/call-action-tech-community-new-machine-readable-covid-19-dataset/)

**Looking for:** Researchers familiar with NLP-based ML and AI methods.

**How to get involved:** 
Form a team (or go solo) and submit to the Kaggle Challenge (see [Initial Key Questions](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge/tasks))

### Johns Hopkins Mapping nCOV Project

**Description:** This team has developed an [interactive web-based dashboard](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) hosted by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University, to visualize and track reported cases in real-time. The dashboard illustrates the location and number of confirmed COVID-19 cases, deaths and recoveries for all affected countries. It was developed to provide researchers, public health authorities and the general public with a user-friendly tool to track the outbreak as it unfolds. Additionally, the data (which is verified and updated daily) is available on GitHub. They are interested in conducting additional modeling of the emerging outbreak.

**Resources:**
  * Project [website](https://systems.jhu.edu/research/public-health/ncov/)
  * Project and data GitHub [Repo](https://github.com/CSSEGISandData/COVID-19)
  * The Lancet [article](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(20)30120-1/fulltext)
  * Interactive [Dashboard](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
  * [How to](https://blogs.sap.com/2020/03/11/quickly-load-covid-19-data-with-hana_ml-and-see-with-dbeaver/) quickly load the data with SAP API and Pandas
  * Related [Kaggle challenge](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset)
  * Dashboards built on their dataset, using GitHub Actions: [covid19dashboards](http://covid19dashboards.com/), built on [fastai/fastpages](https://github.com/fastai/fastpages)

**Looking for:** It doesn’t explicitly say on the website, but presumably ML researchers, model-builders, data visualization folks, data scientists

**How to get involved:**
  * Reach out to the group at COVID19map@jhu.edu or jhusystems@gmail.com
  * Grab the data and build your own project

### Project Open Air (Just One Giant Lab)

**Description:** Project Open Air/Helpful Engineers, hosted within the broader open science group Just One Giant Lab has created a 5,000 strong volunteer organization, with engineers, scientists and doctors around the world who work to organize themselves into teams to design innovative ways to fight the virus. They are quickly trying to design and arrange the production of pragmatic devices to move life-saving air, extend existing tools, or organize volunteers on the ground to bolster medical workers. They have both hardware and software based projects including designing open source, scalable easy to DIY ventilators and O2 concentrators, sentiment analysis for persuasive public health media, diagnostic apps, and more!

**Resources:**
  * Project [homepage](https://app.jogl.io/project/121#about)
  * Google [drive](https://drive.google.com/drive/folders/1qtQlHXeLzfgIWJPnlad803tzfmr0Z_7_) with project documents
  * [GitHub](https://github.com/Helpful-Engineers/resources) for the software projects

**Looking for:** MANY different skills sets: app developers, ML researchers, data scientists, data visualization folks, makers, fabricators, designers, organizers, and especially folks who can volunteer time for project management.

**How to get involved:**
  * See this [doc](https://docs.google.com/document/d/1cM87eJdXhP_8e9gJJZ_SnZXdo_huWsBmMzcqYWbhEOg/edit) and fill out the intake [form](https://docs.google.com/forms/d/e/1FAIpQLScu-4OOB5dGLWoSIA33CkAH__LE6b_M2PKRh0z6PMavL39uUQ/viewform)
  * Join the [Slack](https://helpfulengineering.slack.com/join/shared_invite/zt-cuftcntg-BDc~3oBJ7izijjdmZ6CxZg) and introduce yourself in #introductions
  * Email opensourcehumankind@gmail.com 
  * If you are a medical professional, additionally fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSd8-pTFJKu8goc601K7Q9ZQ2LzQtGfwnKHWFYITzVVYEAnV-w/viewform)

### CHIME: COVID-19 Hospital Impact Model for Epidemics

**Description:** As we prepare for the additional demands that the [COVID-19 outbreak](https://www.cdc.gov/coronavirus/2019-nCoV/index.html) will place on our hospital system, our operational leaders need up-to-date projections of what additional resources will be required. Informed estimates of how many patients will need hospitalization, ICU beds, and mechanical ventilation over the coming days and weeks will be crucial inputs to readiness responses and mitigation strategies.To this end, the [Predictive Healthcare](http://predictivehealthcare.pennmedicine.org/) team at Penn Medicine has developed a tool that leverages [SIR modeling](https://mathworld.wolfram.com/SIRModel.html) to assist hospitals with capacity planning around COVID-19. [CHIME](https://github.com/pennsignals/chime) allows hospitals to enter information about their population and modify assumptions around the spread and behavior of COVID-19. It then runs a standard SIR model to project the number of new hospital admissions each day, along with the daily hospital census. These projections can then be used to create best- and worst-case scenarios to assist with capacity planning. It is currently being used by a few hospitals and they’re looking to expand!

**Resources:**
  * Project [home page](https://codeforphilly.org/projects/chime) (within Code For Philly)
  * Project [GitHub](https://github.com/CodeForPhilly/chime)
  * Project [documentation](https://codeforphilly.github.io/chime/)
  * List of open [issues/projects](https://github.com/codeforphilly/chime/issues)
  * Interactive [dashboard](https://penn-chime.phl.io/) for hospitals

**Looking for:** Primarily Devops folks to help scale up the models/app and automate data collection and Project Managers to help develop documentation and ensure user accessibility. Possibly some modeling folks as well.

**How to get involved:**
  * Join the [Slack](https://codeforphilly.org/chat?channel=covid19-chime-penn)
  * Check out the [Contributing section](https://codeforphilly.github.io/chime/CONTRIBUTING.html) in the user guide
  * Check out the open issues on [GitHub](https://github.com/codeforphilly/chime/issues) and get started on one!

### COVID-19 Risk

**Description:** This project is focusing on research that could lead to an app that shows individuals their risk of COVID-19 infection based off GPS data, known cases, and Bluetooth proximity networks. They aim to do so in a way that preserves transparency and personal privacy. This is a  group of volunteers researching and designing an open-source app to make this idea a reality. Ideally, this app will take the GPS and Bluetooth data of users in an anonymised way, as well as some information about their potential or confirmed infection status, and use it to the benefit of both them and everybody else. There are several ways this could happen: through secure and anonymous [contact tracing](http://covid19risk.com/CSCT.pdf), through the creation of a risk [heatmap](http://covid19risk.com/heatmap), and through more accurate epidemiological modelling.

**Resources:**
  * Project [home page](https://www.covid19risk.com/)
  * Project [blog](https://www.covid19risk.com/blog.html)
  * Effective Altruism [post](https://forum.effectivealtruism.org/posts/8chk6DHZXctGHtNoz/covid-19-risk-assessment-app-idea-for-vetting-and-discussion)

**Looking for:** Public health or epidemiology researchers, app developers, web developers, legal experts around data security/privacy, software engineers to implement spread models, folks who have worked in fundraising/grant writing.

How to get involved:
  * Email [collaborations@covid19risk.com](mailto:collaborations@covid19risk.com) with the role you would like to fill, an introduction to yourself, and links to previous work.

### COVID Compare

**Description:** This project is just kicking off and is working on tracking/mapping the relative risk of Covid19 in the US. 50 cases in Kentucky is not the same as 50 cases in NYC. People aren’t good at normalizing out other variables like population/hospital access so I want to do that for them visually. 

**Resources:**
  * Fast.ai tech help [page](https://forums.fast.ai/t/help-with-algorithm-for-covid19-relative-risk/65328)
  * Map [prototype](https://covidcompare.com/)
  * [Project GitHub](https://github.com/rbracco/covidcompare)

**Looking for:** Data scientists, model builders, public health folks to help build a quantifier for risk and a predictive tool, web app developers and data visualizers, data collectors.

**How to get involved:**
  * Reach out to collaborators on [GitHub](https://github.com/rbracco/covidcompare)


