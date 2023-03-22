# Exploring the Relationship Between Text and Rating: A Sentiment Analysis Study
This is our final project for STA220 in winter 2023. A collaborative work with <a href="https://github.com/wswu001">WunSyuan Wu</a>.

## Overview
The process of sentiment analysis involves employing natural language processing techniques to recognize, extract, measure, and investigate emotional states and subjective details. In this project, we aim to explore sentiment analysis and implement it on the review data collected from different platforms. In particular, we wonder if the text of reviews is helpful to reflect the rating.

To achieve this goal, we start by collecting several sizable datasets of reviews for various places and businesses. We then preprocess the text by removing irrelevant information such as stopwords, punctuation, and special characters. Those datasets are merged into one dataset and used in our exploratory data analysis to identify any trends or patterns in the reviews. After that, we apply a sentiment analysis algorithm to the processed text to classify it as positive, negative, or neutral.

To evaluate the performance of our sentiment analysis model, we compare its predictions with the actual ratings given by the reviewers. We also calculate several performance metrics such as accuracy. Moreover, we investigate the relationship between the sentiment of the text and the corresponding rating. This analysis will help us understand whether the text of the reviews is a good indicator of the rating or not.

In conclusion, this project aims to provide insights into the effectiveness of sentiment analysis for predicting ratings based on the text of the reviews. The results of this study can be useful for businesses and organizations to gain a better understanding of their customer's opinions and improve their products or services accordingly.

## Contents
Our project is organized into separate Jupyter notebooks as follows.
<ol>
<li><a href="html/data.html">Data Acquisition</a></li>
<li><a href="html/merge.html">Merge Data across Sources</a></li>
<li><a href="html/eda.html"> Exploratory Data Analysis</a></li>
<li><a href="html/base.html">Naive Model</a></li>
<li><a href="html/model.html">Scikit-learn Classifiers</a></li>
<li><a href="html/comparision.html">Comparision between Models</a></li>
<li><a href="html/conclusions.html">Conclusions</a></li>
</ol>

The HTML template is provided by <a href = 'https://github.com/orderedlist'>orderedlist</a>. Syntax highlighting is provided on GitHub Pages by <a href = 'http://pygments.org'>Pygments</a>.
