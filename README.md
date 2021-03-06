
# Comment Verification with Machine Learning

According to Wikipedia, "**Machine learning (ML)** is the scientific study of algorithms and statistical models that computer systems use to perform a specific task without using explicit instructions, relying on patterns and inference instead". In this project, we have a data set consisting of comments of an online shopping website in Iran (Digikala), and our goal is to be able to determine wheter a comment should be shown on the product's page or not. You can download the data set from [my Google Drive](https://drive.google.com/file/d/1uDerAt-nBFZtKbQ-1czYrKVvbo6sIpcL/view?usp=sharing).

The algorithm used in this project is called *Naive Bayes*. It simply uses the Bayes' theorem to calculate the probability of a comment being spam, based on some prior knowledge on its words.

There are two programs in the repository. In "Comment Verification Without learning libraries.ipynb", I implemented this concept from scratch. in "Comment Verification with learning libraries.ipynb", I implemented the algorithm with *sklearn* library. Also, there are some other files in the repository:

- **CommentJudge.jar** - put your answers in a file named ans.csv, and run this jar file to see your accuracy. 
- **requirements.txt** - If you are familiar with python, you know that this file helps running the program without version conflict problems in the libraries. 
- **stop_words** - These are some Persian stop words I used to improve my accuracy.

if you don't want to wait for "Comment Verification Without learning libraries.ipynb" to calculate probabilities, you can download two respective CSV files I uploaded in [my Google Drive](https://drive.google.com/file/d/1xAwm_t4FlwCEbMMGVllTqMoIVeWkEg75/view?usp=sharing). Commands for loading these 2 files into the program are available in the code. 

Also, If you want to implement your approach, pay attention that you have to put your outputs in a file named ans.csv. This file should have two columns. The first column's name is "id", and it contains the id of the comment in one row. The second column is verification_status, and it shows whether the comment in one row is spam or ham. 
