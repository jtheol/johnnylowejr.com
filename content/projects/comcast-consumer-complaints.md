+++
author = "Johnny"
title = "Topic Modeling in Customer Feedback: Insights from Comcast Complaints"
date = "2024-03-26"
description = "Topic modeling"
tags = [
    "nlp",
]
+++

Examined consumer complaints about Comcast using a data set spanning from 2000-2016.

Firstly, we preprocess the data and divides complaints based on their ratings. Then, we employ TF-IDF vectorization to identify the most common words in negative comments, focusing on topics like Comcast packages and customer support wait times.

Utilizing Latent Dirichlet Allocation (LDA), identify topics within the negative complaints and prints key terms per topic, and further examine complaints related to customer service.

Lastly, utilize BERTopic, a state-of-the-art topic modeling technique, to identify and visualize topics within negative complaints, notably highlighting issues similar to customer service complaints.

The process provides an insightful exploration of consumer sentiments, shedding light on prevalent issues and sentiments within Comcast consumer complaints