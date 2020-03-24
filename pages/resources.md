---
title: Resources
permalink: /resources/
---

# COVID-19 ML and Tech Related Open Science Projects

## Context

This document is a place to collect details on open science/open source technology based projects related to COVID-19. This includes modeling, public health interventions, medical technology, resource distribution, and more. Please feel free to add your own project or other projects that you know of! We just ask that you keep the doc organized and follow the yaml format below:

```yaml
title: Project Title
description: |
    A brief description of the project
resources:
- Links to important info about the project (include related articles if possible!)
needs: What kind of folks can best contribute to this project?
involved: Include links to sign up forms, GitHub issues, Slack channels, etc
tags:
  - ds
  - ml
```

Let’s make the most of our work from home time and try to help our fellow humans (and maybe learn some new skills!). 

To reach out to the doc creator, please email savannah.thais@gmail.com.

## Projects


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

### Crowdfight COVID-19

**Description:** This is an initiative from the scientific community to put all available resources at the service of the fight against COVID-19. It has separate portals for those already doing COVID-19 related research to request resources and for those not yet engaged to volunteer.  As of March 21, 2020 this appears to be a (primarily) European initiative.

**Resources:**
  * Project [home page](http://crowdfightcovid19.org/)
  * Twitter [feed](https://twitter.com/Crowdfightcovi1)

**Looking for:** almost any skill set, from the ability to transcribe data from text into databases to highly expert. They will try to match people to appropriate projects.

**How to get involved:** register on their [volunteers page](http://crowdfightcovid19.org/volunteers)
