---
title: "Tackling Messy Data with Data cleaning"
date: 2022-04-03T22:53:58+05:30
draft: false
#github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Meghana Puttaswamy"
tags:
  - Data Cleaning
  - Data Quality
  - Accuracy
  - Prediction
image: /images/Data-Cleaning-scaled.jpeg
description: ""
toc: 
---
## Why does data cleaning matter?

College is a whirlwind of lectures, assignments, and caffeinated study sessions. Amidst the chaos, I had to finish my first machine learning project on image segmentation, would turn out to be my first encounter with the world of machine learning. I had no idea that we start the project by cleaning the data. I used to think to myself how in the world can you clean a image dataset but little did I know that became the cause for the failure of the project. No matter what type of the data we are working with, data quality is very crucial to obtain best performing model.

---

## what is data cleaning?

Data cleaning is the artistic endeavor of guaranteeing that data meets the criteria and ready for use. One can purify data by reducing inaccuracies,  or meticulously handling the data as required to reduce the recurrence of such inaccuracies.

While the majority of data cleaning can be accomplished through the aid of software tools, a certain portion necessitates human effort. Although this might seem like a daunting task, it is an essential aspect of managing a company's data.

---

## What are the benefits of data cleaning?

There are numerous advantages to having clean data: 
- Removing significant errors and inconsistencies that are inevitable when multiple sources of data are being pulled into one dataset. 
- Utilizing tools to tidy up data will enhance the efficiency as we will be able to quickly obtain the necessary information from the available data. 
- Reducing errors leads to happier customers and less frustration among employees. 
- Enabling us to establish connections between different data variables, and gain a better understanding of the purpose and source of the data.

---

## What are the steps?

The first step before starting a data cleaning project is to first look at the big picture. Ask yourself: What are your goals and expectations?

To achieve those goals you’ve set, next, you must plan a data cleanup strategy. A great guideline is to focus on your top metrics. Some questions to ask:

- What is your highest metric looking to achieve? 
- What is your company’s overall goal and what is each member looking to achieve from it?

A good way to start is to get the key stakeholders together and brainstorm.

There are six standard techniques to be followed in order to maintain the data quality before modeling based on your requirement, remember each project is unique. A best way to narrow down what technique to use is to identify the source of the discrepency in the data:

**1. Remove duplicates:**

The duplicates can originate from various reasons including humar oversight. Duplicates can skew the data distribution and confuse the results. The best action is to remove the duplicates as soon as noticed.

---

**2. Remove irrelavent data:** 

Nowadays, we work with huge chunks of data, ingested by algorithms and models. Retaining irrelavent data can simply slow down the process. The best action is again remove such data. This might include hash values that carry no information or multiple identifiers that serves same purpose etc.,

---

**3. Convert Data Types:**

Numbers are the most common data type that needs to be cleaned to represent uniform format. For instance, if we consider time HH:MM:SS, this should be standardized in the entire dataset. Similarly 10th September 2023 or 10-09-2023 indicates same date but need to convert it into one format before further insights are drawn. While numbers are most common, string type variables can also have similar issue. Consider, EN and England, both are indicating country names but there is a need to have a single format throughout.

---

**4. Missing Values:**

When it comes to dealing with missing values, you have two choices. You can either eliminate the observations that contain these missing values or you can input the missing data. The decision you make will depend on your analysis objectives and what you intend to do with your data next.

Completely removing the missing value may result in the loss of valuable insights from your data depending on the percentage of missing values. After all, there must have been a reason why you wanted to retrieve this information in the first place. Hence in the case of huge data loss due to missing data removal, one can opt to impute the missing data based on the pattern or value.

---

**5. Fix Error:**

It probably goes without saying that you’ll need to carefully remove any errors from your data. Errors as avoidable as typos could lead to you missing out on key findings from your data. Some of these can be avoided with something as simple as a quick spell-check but most other require careful mannual examination on to why the error was caused, if the error can be corrected or to be removed. 

---

**6. Standardization:**

Maintain a single standard meaning to data values throughout the data. For instance, if its the text data, Will can indicate both name and will can entirely change the meaning. So making sure that such words are standardized are crucial in Natural language processing. If you have a mixture of capitalization, this could lead to different erroneous categories being created. It could also cause problems when you need to translate before processing as capitalization can change the meaning. Text cleaning becomes crucial here.

---

In the above techniques we mostly spoke about numerical data, what if it is a text data in case of Natural Language Processing or image data in case of Computed Vision. Further, these techniques can be built upon to suite respective use case. For instance, if we are building a face recognition system, the images that do not have face or in a different posture that does not make face visible is of no use and thus can be discarded as part of data cleaning. When it comes to NLP, there are techniques to translate the entire document to one language which is further easy to process.


While it can sometimes be time-consuming to clean your data, it will cost you more than just time if you skip this step. “Dirty” data can lead to a whole host of issues, so we want it clean before we begin your analysis. 
