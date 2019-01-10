# Reddit-QA-corpus-
A question and answer corpus from the /r/askreddit subreddit. Designed for training seq2seq neural networks. The total corpus is 4,976,760 question and answer pairs. 


## Creation 
Data was gathered from http://pushshift.io reddit data dump on the 15/06/2018. 

All submission to the subreddit where taken as questions, and the first comment on each submission was taken as the answer. 

## Cleaning 

* A submission must have a comment to be included 
* Comments which where [deleted] , [removed] or posted by the subreddit auto bot where removed. 
* Submission which didn't contain questions where removed (Subreddit bot automatically inforces that all submissions must have a question mark) 

## Data 
Each file is just under half a GB, hence why it's stored on a remote server. 

* [Answers](http://fionndelahunty.com/Datasets/Reddit/Answers_R.txt)
* [Questions](http://fionndelahunty.me/Datasets/Reddit/Questions_R.txt)

## Numbers 
7,102,717  Questions
12,039,795 Answers 
 - 2,548,641 Autobots
 - 831,108 Deleted 
 - 73,881
=8,586,165	
4,976,759 Questions and Answers pairs



## Referencing 
If used for academic purposes please contact fionnd [at] pm.me for full refencing infomation.  

 
