# Reddit-QA-corpus-
A question and answer corpus from the /r/askreddit subreddit. Designed for training seq2seq neural networks. The total corpus is almost 5 million questions and answers. 

## Creation 
Data was gathered from http://pushshift.io reddit data dump on the 15/06/2018. 

All submission to the subreddit where taken as questions, and the first comment on each submission was taken as the answer. 

## Cleaning 

* A submission must have a comment to be included 
* Comments which where [deleted] , [removed] or posted by the subreddit auto bot where removed. 
* Submission which didn't contain questions where removed. 

 
