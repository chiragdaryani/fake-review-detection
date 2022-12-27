# Fake Reviews Detection

In this project, we are attempting the problem of Fake Review Detection on the Yelp restaurant review dataset. We explore rule-based, machine learning and aggregation based approaches. The rules were based on our data analysis. For machine learning we consider dealing with textual and non-textual features separately. 

We optimize the sytem performance by experimenting with various combination/aggregation techniques, which allowed us to leverage the strengths of both rule-based and machine-learning methods and enabled us to achieve enhanced results.




## Data

Our project uses the YelpZip dataset, which contains about 608,598 reviews from Yelp.com. These reviews are written for 5,044 restaurants and are written by 260,277 reviewers. It contains features like the text of the review, the date when the review was written, user information, product information, rating given by the user to the product, etc. Based on the anti-fraud filter that Yelp uses, each of the reviews has been labeled as either genuine or fake. We would use these labels as the ground truth for our experiments.

The preprocessed training data can be found in the file [new_data_train.csv](/new_data_train.csv) and the test data can be found in the file [new_data_test.csv](/new_data_test.csv). The original unprocessed dataset can be downloaded from [Google Drive](https://drive.google.com/file/d/1U35JaRIE71512aF5m2S5zP2FuJMo5tDp/view?usp=sharing)



## References
[
Collective Opinion Spam Detection: Bridging Review Networks and Metadata](http://shebuti.com/wp-content/uploads/2016/06/15-kdd-collectiveopinionspam.pdf) Shebuti Rayana, Leman Akoglu, ACM SIGKDD, Sydney, Australia, August 10-13, 2015

[Collective Opinion Spam Detection using Active Inference.](http://shebuti.com/wp-content/uploads/2016/06/16-sdm-active.pdf) Shebuti Rayana, Leman Akoglu, SIAM SDM, Miami, Florida, USA, May 5-7, 2016

http://odds.cs.stonybrook.edu/yelpzip-dataset/

https://arxiv.org/pdf/2203.09936.pdf

https://ieeexplore.ieee.org/document/9320592/;

https://dl.acm.org/doi/10.5555/2935490

https://github.com/darshandagly/Fake-Review-Detection/blob/master/Code/main.py

https://www.semanticscholar.org/paper/A-Novel-Approach-for-Opinion-Spam-Detectionin-Shirin-Erfan/f79347cdff7f669568ec56dd1e5e76c517ea9046
