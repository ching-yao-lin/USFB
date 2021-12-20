# USFB Project
**Construct Sentiment Score with Facebook Comments on US Politics**

**Project Goal**: Propose a way to construct sentiment score with respect to social media comments<br>
**High-level description**: In this project, I was dedicated to building a recipe for extracting sentiment scores out of Facebook comments. These scores would then be used to accomplish other downstream tasks, mainly econometric analyses such as analyzing the social impact of Trump making an indiscreet remark. The sentiment scores serve as an important outcome on regression analyses conducted by graduates in the Economics Department in NTU.

Special thanks to [Prof. Ming-jen Lin](https://econ.ntu.edu.tw/zh_tw/people/faculty0/faculty1/%E6%9E%97-%E6%98%8E%E4%BB%81-73113963) for providing me with this amazing opportunity to conduct a hands-on, end-to-end, interesting as well as challenging standalone project

Result: three scores

(graphs)



Directories:
* [USFB_quick_results](/USFB_quick_results.pdf): A quick walkthrough for this project
* [USFB_full_presentation](/USFB_full_presentation): An extremely detailed presentation on how this project was done from end to end
* [code](/code)
  * [preprocessing](/code/preprocessing.ipynb)
  * [EDA](/code/EDA.ipynb)
  * Model Building, Sentiment Score, Analytical Results

Data:
Facebook Data (including pages, posts, comments, reactions) on Top 1000 political pages

Main Libraries:
* pandas - for data wrangling
* matplotlib - for data visualization
* huggingface - for BERT models
