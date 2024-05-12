# text-summarization-liputan6

# 1. Introduction
By using **Liputan6 News** dataset, developing a system for summarizing documents using text understanding method which can obtain the main idea of a news story. 

Basically the system is able to summarize text into a shorter summary but still maintains the key points, phrases and context of the text. So you get the text in a more concise and concise form.

To achieve that, we use **BERT and T5 models**.

# 2. Objectives
Developing a model for summarizing documents using a text understanding method that can obtain the main idea of a news item.

# 3. Dataset
The dataset used is a collection of summarization data from the Liputan6 website.

The dataset covers various topics and events from October 2000 to October 2010. Those topics as below:
- Politics
- Business
- Sport
- Technology
- Health
- Entertainment

Each data contains the following information:
1. id
2. url
3. clean_article
4. clean_summary
5. extractive_summary

# 4. Project Flow

![Flow Diagram](./images/flow-diafram.png)

- Explore Datasets
- Explore some pre-trained models
- Model evaluation
- Take conclusions

# 5. Output / Conclusion
- Both models got average Rouge metric score around 0.45 - 0.47 which is reasonably good.
- In some inference results, T5 produces more abstractive summary
- Overall the performance of BERT and T5 similarly good in variations of Rouge metric such as: Rouge-1, Rouge-2, Rouge-L, or Rouge-L Sum
