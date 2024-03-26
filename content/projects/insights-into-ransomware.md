+++
author = "Johnny"
title = "Insights Into Ransomware"
date = "2024-03-26"
description = "Capstone project"
tags = [
    "eda",
    "data science"
]
+++

Extracted structured information from unstructured text data related to ransomware negotiations and 60,000+ internal ransomware group conversations. Applied exploratory and natural language processing methods to obtain meaningful insights. Analyzed quantitative information on global ransomware attacks across multiple industries and ransomware strains.

The capstone project analyzed datasets related to ransomware, including global ransomware attacks from 2018-2023, anonymized negotiation chats between victims and 11 ransomware groups, and leaked internal chat messages from the Conti group. Analysis showed the healthcare industry experienced the most attacks, while utilities paid higher average ransoms. The project focused on Conti given their success and available data, mapping their negotiators and analyzing time-based patterns. Topic modeling extracted key themes like user support, negotiations, data leakage, and infiltration methods. Overall the project compiled and analyzed multiple ransomware datasets to gain insights into how groups like Conti operate.

The project utilized two topic modeling techniques - Latent Dirichlet Allocation (LDA) and BERTopic using class-based TF-IDF - to extract key topics from the ransomware negotiation chat datasets. Topic modeling identifies common themes in text documents by analyzing frequently used words.

BERTopic produced more interpretable topics including files stolen, user support, negotiation process, threats of data leaks, and infiltration methods. LDA found similar topics but BERTopic's visualizations provided better representation.

Topic modeling results were used to identify documents of interest for further analysis, excluding less relevant topics. Main limitations were the amount of available negotiation data and quality of translations.

Overall, topic modeling provided a useful unsupervised method to extract important themes from the ransomware negotiations and surface documents for further exploration.