Project 1: CO2 Emission Prediction: 

*Generated Regression plot and Scatter Plot using seaborn and Matplotlib libraries and concluded the model is Linear.

*Predicted the Carbon DiOxide emission for several cars with the help of ENGINESIZE,FUELCONSUMPTION COMBINED,CYLINDERS,FUELCONSUMPTION_HWY,FUELCONSUMPTION_CITY      using Scikit learn(linear models) in g/km with an accuracy of 87%.

Tools used: 

Pandas,Scikit-Learn,Seaborn,Matplotlib

Project 2: Loan Repayment Prediction
To Determine, Whether the customer can able to repay the loan based on several other users who already repaid and to determine the best classifier among KNN, Decision Tree, SVM and Logistic Regression  and to evaluate the accuracy of each model

The evaluation was done using: Jaccard Similarity Score, F1 score, Log Loss

Field	Description :

Loan_status	- Whether a loan is paid off on in collection
Principal -	Basic principal loan amount at the
Terms	Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule
Effective_date -	When the loan got originated and took effects
Due_date - Since it’s one-time payoff schedule, each loan has one single due date
Age	- Age of applicant
Education	- Education of applicant
Gender -	The gender of applicant

Result:
KNN and Decision Tree are the Best models with an accuracy of 70%

Tools used: Pandas, Matplotlib,Scikit-Learn,Algorithms-SVM,KNN,LOGISTIC REGRESSION,DECISION TREE

Project 3: Movie Recommendation Engine

*To suggest the movies to the users based on the similar movies they have already watched.
*The Genre of the movie is rated by the user, is summed up to predict the favorites content such as Action, Adventure, Comedy, Crime, Drama, Fantasy and so on and the movie similar to that genres are recommended

Improvisation of the model:
The model can still be developed with item based rather than genre-based using Pearson Coefficient techniques

Project 4: Segmenting and Clustering Neighborhoods in Toronto

*To recommend the places, to go near a user's current location using segmentation and clustering 
*The Toronto data is web scraped from Wikipedia and is cleansed.The Foursquare API credentials are used to locate, famous nearby places, and the cluster labels are generated according to each place.

Algorithm: K means 
Tools used: Folium,Pandas,SCikit Learn,Foursquare,Geocoder,Matplotlib
