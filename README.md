# Music-Genre-Classification-PySpark 🎶
Have you ever questioned how it is that humans can distinguish between two songs from completely different genres? How do we innately distinguish between heavy metal and pop music? Although this kind of classification may seem simple to us, a machine would find it quite challenging to do. Hence, the question is: Is it possible to develop an automatic genre classification model? <br> <br>
For this project, **PySpark** will be used to categorise music into a collection of **23 electronic genres** based on a variety of attributes.<br>
An application like Pandora might use this technique to suggest songs to users or just to make interesting channels. amazing fun!

## Dataset
### Source: https://www.kaggle.com/caparrini/beatsdataset
beatsdataset.csv Each row is an electronic music song. The dataset contains 100 song for each genre among 23 electronic music genres, they were the top (100) songs of their genres on November 2016. The 71 columns are audio features extracted of a two random minutes sample of the file audio. These features have been extracted using pyAudioAnalysis (https://github.com/tyiannak/pyAudioAnalysis).
## Our Task
Create an algorithm that classifies songs into the 23 genres provided. Test out several different models and select the highest performing one. Also play around with feature selection methods and finally try to make a recommendation to a user. <br> <br>

![image](https://user-images.githubusercontent.com/53153292/227954901-6c78c7cc-dfd3-4408-bc24-b3d11ffdec71.png)

## Steps
1) Cleaning and Preparing the data
2) Using vector Assembler to convert the columns into vectorized feature that is used as input to the model.
3) Features Selection
4) Training and Evaluating different models <br>
:point_right: 
We tried and evaluated each of the following models:
    - one vs rest
    - logistic regression
    - multi layer preceptron
    - linear SVC
    - Naive Bayes
    - GBT Classifier
    - Random Forest
    - Decision Tree
    <br>
![image](https://user-images.githubusercontent.com/53153292/227953946-fa5b2afc-cafc-44d6-85a6-0cd283298c0f.png)

5) Implementing the best model (Random Forest)
6) Evaluating on the test set
