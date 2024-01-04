# Analyzing User Behavior, Trends and Communities using Reddit Posts

## 1. Introduction
This project revolves around leveraging Reddit data to gain valuable insights and trends. Reddit supports a vast variety of discussion and content without many restrictions, enabling users to put forth their opinions free of reservations. Analyzing such posts and comments on Reddit can serve as a good opinion when compared to obtaining information from a single source which may be tainted due to restrictions/guidelines. The project aims to address sentiment analysis of subreddits and identifying trending topics across various subreddits.

## 2. Background
Since the inception of transformers in the field of Natural Language Processing, there has been a substantial proliferation, leading to notable advancements. This transformation has yielded significant achievements in various tasks, including Sentiment Analysis, Question Answering, and Information Retrieval. In recent literature, a prevailing trend involves the application of transformer-based architectures to scrutinize social media platforms, seeking insights into emerging trends.

## 3. Experimental Setup
The project relies on the cutting-edge techniques within the field of Natural Language Processing, with a particular focus on transformer models. These models have revolutionized the way we handle text data, offering unprecedented capabilities for understanding the sentiment within textual content and extracting trending topics from the vast landscape of Reddit discussions.

### 3.1. Dataset
The dataset encompasses fundamental Reddit information, such as author details, score, titles, subreddits, and more, organized into submissions and comments. The dataset includes posts belonging to all the subreddits, spanning from June 2005 to December 2022, and is substantial, totaling approximately 2.4 TB of data stored as .zst files.

### 3.2. Approach
The project addresses two specific issues through analytical examination, constructing distinct models for each problem. The modeling approach for sentiment analysis is elucidated, while the methodology employed for trending topic identification is outlined. An experiment is conducted aimed at gaining a comprehensive understanding of the predominant topics within diverse subreddit communities and their corresponding sentiments.

## 4. Results and Analysis
The findings are categorized into three distinct subsections, as illustrated below. This division allows for a more focused analysis within each section. Additionally, this structured approach enhances the clarity and comprehensibility of our results, aiding in the extraction of meaningful insights from the research outcomes.

### 4.1. Sentiment Analysis
To gauge the performance of the sentiment analysis models we have used evaluation metrics like F-score, precision, and recall, on the four scenarios-BERT and RoBERTa, each fine-tuned on both balanced and unbalanced datasets.

### 4.2. Trending Topic Identification
To assess the efficacy of our trending topic models, we conducted experiments using data from two distinct subreddits, namely r/apple and r/explainlikeim5. The rationale behind selecting these subreddits lies in their divergent nature: r/apple, being more generic in discussions, and r/explainlikeim5, characterized by its potential for unique and random topics.
