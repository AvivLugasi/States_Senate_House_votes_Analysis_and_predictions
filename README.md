# States_Senate_House_votes_Analysis_and_predictions

This is the work of me and my co-student Guy Yehezkel in the course Machine learning.
We have been provided with data regarding US elections, general county information, life expectancies and economic data.

Our worked included:
1)Exploring the data using tables, visualizations by using plots.<br>
2)Applying different methods of pre-processing to the data in order to prepare it for the models such as:<br>
      a)exclusion (features selection, null drop..etc).<br>
      b)data imputation(Using KNN).<br>
      c)features selection for the analysis and clustering of counties of 4 requested states by using classifiaction tree, to classify samples of counties<br>
      of the requested states and selecting the features with the highest importances.
      d)features engineering(creating new features based on analysis we performed), for example we discovered that on presidential election's years
      the vote turn out in the House elections, presidential elections and the Senate elections is higher by up to 40%, therefor we created a feature to               indicate if a given year, was a presidential election year, in oreder to help us predict vote turn outs 
      for the House and Senate elections in each state.
      We also estimated our dependent variable(Vote turn outes) by using  given demographic that included , population size 
      and proportion of citizens under the age of 18 in each county and total votes in each state.
3)Applying PCA and T-SNE dimensionality reduction algorithms on the counties samples of California, Florida, South Dakota, and Wyoming, and clustered them 
by thier state in order to understand which states are similler and in what features(based on the features selection we applied in part 2.c).
after that we implimented and applied the silhouette coefficient in order to understand  which algorithm performed better.
4)Predicting the vote turn outs in each state in the House elections in 2010 and 2012 based on data from 2002- 2008,
then we improved the predictions for 2 of the states with the worst predicitons by over sampling samples of those states.
5)Predicting the house majority party(D-Democratic/R-Republican) in the elections of 2010 and 2012 using data from 2002-2008.
6)Using data from 2000-2020 we predicted the outcome of the 2022 midterm Senate elections, then we used our predicitons and a given data of the current,
proportions of D and R senators to create an image of what the up coming proportions of D and R senators will look like after the elections based on our predicitons.
      
linkedIn of creators:
Aviv Lugasi: https://www.linkedin.com/in/aviv-lugasi-b89693235/
Guy Yehezkels:https://www.linkedin.com/in/guyyehezkel/
