---
layout: page
title: Quotebank
subtitle: "A Corpus of Quotations from a Decade of News"
cover-img: "assets/img/data.jpg"
---

_“Quotations will tell the full measure of meaning, if you have enough of them.”_  
_—James Murray_
<div style="text-align: justify">
### Quotebank dataset 
[Quotebank](https://dl.acm.org/doi/10.1145/3437963.3441760) is a corpus of quotations attributed to the speakers who uttered them, extracted from 162 million English news articles published between 2015 and 2020. The quotations have been extracted with _Quobert_, a machine learning framework used for extracting an attributing quotations from a corpus of news articles.

### Clean and filtered Quotebank Climate-related dataset
In this project we used a subset of the Quotebank dataset, a corpus of quotations that we identified as climate-change-related, extracted from the entire Quotebank dataset. It results from the cleaning and filtering of the Quotebank dataset. The filtering to obtain climate-related quotes was done using a list of keywords, that was extracted using logistic regression and the two given test sets.

### Speaker dataset
In addition to the climate-related Quotebank subset we used a  the list of all the speakers that appear in the Quotebank dataset, containing their caracterists, such as nationality, gender, education, political party, date of birth, ethinc group and religion. We also enriched this data with one more column, containing boolean values describing whether this person talk about climate or not. The first value is True if any quote from this speaker is found in the Climate related Dataset.

### Model training dataset
These two dataset were used to train and test the logistic regression model used to classify our quotes as climate related or not. They were found in the article from [Varini et al.](https://arxiv.org/abs/2012.00483). These datasets are composed of sentences labeled as climate related or not. They were obtained using Active Learning on previously existing datasets. 



All our dataset can be found [here](https://drive.google.com/drive/folders/1kafZtuinbhqQUU2syhdQeBHnJ9_C5E6E?usp=sharing).
<\div>
