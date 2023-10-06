### Instagram Fake Account and Detection

# First task is to Create a new environment

```
conda create -p venv python==3.7 -y
```
Next step after creating an environment is to install all the requirment liabraries from requirment.txt

``
pip install -r requirments.txt
``
# Dataset Source

Basically I took dataset from Kaggle competations.

# About Dataset 

This dataset contains 12 Features and 576 rows 

Features are:

1.ProfilePic :It is going to tell whether a insta account has profile pic or not(1 (or) 0).                                                                 
2.Name==username : whether his name and username both matches or not.                                                                                                    
3.description length :it going to tell length of description.                                                                                                            
4.private :it is going to tell whether account is private or not.                                                                                                       
5.nums/length username :nums length in a username.                                                                                                                     
6.fullnamewords :how many number of full name words are matching.                                                                                                        
7.nums/length fullname :nums length in full name.                                                                                                                       
8.posts :number of posts he has posted                                                                                                                                  
9.followers :number of follower his account has.                                                                                                                         
10.following :number of people following his account.                                                                                                                    
11.fake or not :whether account is fake or not.                                

# Data pre-processing :

1.At first we checked the statistics of the data by using describe,shape.                                                                                             
2.Then after we checked whether a dataset contains any null values or not.But this dataset doesnt contain any null or na values if our dataset contains the we can use techniques like mean,median,imputations or full null values with 0.And so on.                                                                                 
3.Next i checked wheather the data is balanced or not this data is balanced .if the dataset is not balanced then we can use tecchniques like oversampling and undersampling.                                                                                                                                                      
4.next i checked whether dataset contains any outliers or not with the help of boxplot but our dataset dont have outliers we can treat them just by removing them.       
5.Next i checked whether there is an correlation or not by using heatmap and corr() method.                                                                             

# Model Implementation

After doing all the pre-processing steps we have applied a random forest classifier model with the help of this Machine Learning Model it has given a accuracy of 93% which tells that how well our model is performing.                                                                                                                       
we have printed a classification report which is going give us precision,recall and f1_score.                                                                          

# Github 

Next we have Created a github account and cloned my project into my github account with a repository named Instagram Fake Account Detection 

# requirments.txt

requirments.txt file contains all necessary liabraries,frameworks requirmed for this project by using simple comand you can install all the necessary liabraries.

``````
pip install -r requirments.tx
``````
by using this simple comand you can install all the necessary liabraries.                                                                
Then after we have intialised a gitignore file which consists all the unnecessary liabraries that you dont want to install or keep them in your github account.

### software and tools requirments

1.[Github Account](https://github.com)               
2.[Vs code IDE](https://code.visualstudio.com/)      
These are the software tools required for building a project and deploying it in heroku platform
