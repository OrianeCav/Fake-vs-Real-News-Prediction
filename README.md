# Fake-vs-Real-News-Prediction
Early fake news detection aims to give early alerts of fake news during the dissemination process before it reaches a broad audience. Therefore, early fake news detection methods are highly desirable and socially beneficial.  The goal of this project is to detect fake news shared on social media, specifically on Twitter. A binary classification machine learning model will be developed to detect patterns in the article or post, it will classify the news as Fake(1) or Real(0).   In the data analysis part, aside from analyzing the news contents and titles using Natural Language Processign techniques, we also analyzed the social interaction dynamics in fake and real news dissemination on Twitter.

## Description of the Data and Source
In this project we used datasets from FakeNewsNet repository (https://github.com/KaiDMML/FakeNewsNet). This repository contains a collection of almost 24,000 articles collected in 2018 from two different sources:

* __PolitiFact.com__: PolitiFact is a nonprofit project that relies on the collaboration of journalists and policy experts to evaluate the veracity of political news. In FakeNewsNet we can find more than 1000 articles classified by PolitiFact in two categories: Real and Fake News.


* __Gossip Cop__: Gossip Cop (now part of Suggest.com) is a website that fact-checks celebrity reporting. In contrast with PoliFact, Gossip Cop provides a rating in the scale 0-10 for every article on the website. A higher rating means a higher confidence that the story is true. Since Gossip Cop focus is to find Fake News, most of the news from Gossip Cop are Fake News (rating lesser than 5). Therefore, Gossip Cop is the source of Fake News while the celebrity news labeled as real come from E! Online, a well-known trusted media website for publishing entertainment news pieces. However, there have not been any verification process for the news in E! Online and, therefore, the reliability of this part of the data is not as high as in the case of PoliFact.

There are 4 datasets available in the official FakeNewsNet repository:
* *gossipcop_fake.csv*: dataset with the fake news collected from Gossip Cop and E! Online
* *gossipcop_real.csv*: dataset with the real news collected from Gossip Cop and E! Online
* *politifact_fake.csv*: dataset with the fake news collected from PolitiFact
* *politifact_real.csv*: dataset with the real news collected from PolitiFact
