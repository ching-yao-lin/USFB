# USFB Project
**Construct Sentiment Score with Facebook Comments on US Politics**

This project leverages the power of deep learning! State-of-the-art models (BERTs) are adopted for NLP and sentiment extraction from texts.

## Overview
**Project Goal**:<br>
Propose a way to construct sentiment score with respect to social media comments

**High-level description**:<br>
In this project, I was dedicated to building a recipe for extracting sentiment scores out of Facebook comments. These scores would then be used to accomplish other downstream tasks, mainly econometric analyses such as analyzing the social impact of Trump making an indiscreet remark. The sentiment scores serve as an important outcome on regression analyses expected to be conducted by graduates in the Economics Department in NTU.

Special thanks to [Prof. Ming-jen Lin](https://econ.ntu.edu.tw/zh_tw/people/faculty0/faculty1/%E6%9E%97-%E6%98%8E%E4%BB%81-73113963) for providing me with this amazing opportunity to conduct a hands-on, end-to-end, interesting as well as challenging standalone project.

**Project Result**:<br>
Three types of Sentiment Score are constructed:
* Aspect-based Sentiment - Scores on joy, love, surprise, sadness, anger, fear
* Binary Sentiment Labels - POSITIVE or NEGATIVE
* Continuous Sentiment Scores - A score between -1 and +1, indicating a sentiment spectrum from negative to positive emotions
<br><br><br>
![](/images/aspect_based_trump.png)
<br><br>
![](/images/aspect_based_hillary.png)
<br><br>
![](/images/social_listener_continuous.png)


## Details
**Directories**:
* [USFB_quick_results](/USFB_quick_results.pdf): A quick walkthrough for this project
* [USFB_full_presentation](/USFB_full_presentation): An extremely detailed presentation on how this project was done from end to end
* [code](/code)
  * [preprocessing](/code/preprocessing.ipynb)
  * [EDA](/code/EDA.ipynb)
  * [Model Building, Sentiment Score, Analytical Results](/code/Model%20Building,%20Sentiment%20Score,%20and%20Analytical%20Results.ipynb)

**Data**:<br>
Facebook Data on Top 1000 political pages (including pages, posts, comments, reactions).<br>
This data is provided by [Behavioral and Data Science Research Center (台大行為與資料科學研究中心)](https://bdsrc.ntu.edu.tw/).

**Main Libraries**:
* pandas - for data wrangling
* matplotlib - for data visualization
* huggingface - for BERT models
