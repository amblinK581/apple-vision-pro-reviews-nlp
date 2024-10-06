# apple-vision-pro-reviews-nlp
 Market Reception of Apple Vision Pro

This repository contains the project “Market Reception of Apple Vision Pro: Harnessing Latent Dirichlet Allocation (LDA) and Longformer-based NLP for Consumer Insight Analysis.” The project focuses on analyzing online customer reviews of the Apple Vision Pro using advanced machine learning and natural language processing techniques.

Project Overview

The Apple Vision Pro, a highly innovative product from Apple, has sparked both excitement and debate due to its advanced features and high price point. This project seeks to understand how customers perceive the product by analyzing over 500 reviews collected from Quora using topic modeling and feature prediction techniques. The analysis aims to uncover key themes in consumer sentiment and product features to drive product innovation and improve market positioning.

Table of Contents

	•	Introduction
	•	Data Source
	•	Methodology
	•	Results
	•	Conclusion
	•	How to Use This Repository
	•	Requirements
	•	License
	•	Authors

Introduction

With the release of the Apple Vision Pro, Apple enters the highly competitive head-mounted display market. This project aims to leverage user-generated content on Quora to extract insights into consumer opinions about the product, highlighting both positive and negative feedback.

Data Source

The data used in this project was collected from Quora, where over 500 customer reviews regarding the Apple Vision Pro were gathered. We used Selenium to scrape the reviews, then pre-processed them for analysis.

Methodology

We employed a combination of natural language processing and machine learning techniques:

	1.	Latent Dirichlet Allocation (LDA): Applied for topic modeling to identify key themes in customer feedback.
	2.	Longformer Model: Used to predict product features discussed in the reviews, allowing for a deeper analysis of customer concerns and preferences.
	3.	K-Means Clustering & K-Nearest Neighbors (KNN): Additional machine learning models were used to further segment and classify review data.
	4.	Sentiment Analysis: Employed support vector machines (SVM) and random forests to classify reviews into positive, negative, or neutral sentiments.

Results

	•	Topic Modeling: LDA identified seven key themes, including price, technology, and AR/VR experiences.
	•	Feature Prediction: The Longformer model provided insights into specific product features discussed, such as the user experience and headset design.
	•	Sentiment Analysis: The random forest classifier was optimized to detect overall positive sentiment towards the Apple Vision Pro, with areas of improvement focused on price and AR/VR performance.

Conclusion

Our analysis reveals that while customers generally view the Apple Vision Pro positively, they express concerns regarding its price and certain AR/VR features. These findings provide valuable insights for future product enhancements and marketing strategies.

How to Use This Repository

	1.	Data: The data/ folder contains the cleaned dataset of Quora reviews.
	2.	Scripts: The scripts/ folder includes Python code for data cleaning, topic modeling, feature prediction, and sentiment analysis.
	3.	Results: The results/ folder contains visualizations, topic models, and sentiment analysis results.
	4.	Report: The final project report is available in the docs/ folder.

Requirements

	•	Python 3.x
	•	Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk, transformers, PyTorch

Install the required libraries by running:

pip install -r requirements.txt


Authors

	•	Ce Zhao
	•	Shu-Yu Hsu
	•	Tzu-Hsuan Lin
	•	Xudong Li
