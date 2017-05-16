# RecommenderSystem
This contains the notebooks created as part of my Capstone Project for Springboard.  The project is an implementation of the Alternating List Squares algorithm as a recommender system for a movie ratings data set.

Description of Files:

CapProjProposal.doc - This is a word document that contains the description of the initial project proposal.

CapstoneReportLite.doc  - This is an explaination of the intial results of the recommender system project.

CapstoneReportFinal.doc - This is the word document containing the final report.

A Recommender System.pptx  - This is a power point presentation of the project.

Algorithm.ipynb - This is the jupyter notebook containing the weighted alternating least squares algorithm, the code for performing the five-fold cross validation, and the code for providing the recommendation output for each user.

AlgorithmFinal.ipynb - This is the jupyter notebook containing the final code and final results.  The code was optimized in some areas for speed.  Also, a 1D array denoted Y-vector was created containing the mean rating of each movie.  This array was used to create a baseline Q_hat matrix of predictions containing the means.  This was compared to the Q matrix of ratings to come up with a baseline rmse which was 0.897.  This was also used in pre-loading the Y factor vector.

MovieLensDataExploration.ipynb - This is the jupyter notebook that was used to investigate various aspects of the data such as the distribution of the ratings by rating value, distribution of average rating by user, and average number of ratings per user.

MergeFilesTest.ipynb - This file is the jupyter notebook that was used to do some cleanup work, investigate null values, duplicate values, and learn how to merge the files properly.

workwithtimestamp.ipynb - This is the jupytere notebook that was used to analyze and investigate using the timestamp to understand user engagement.
