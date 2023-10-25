# HW_21_Machien_learning
1 - What variable(s) are the target(s) for your model?
    is_succsefull is the target

2 - What variable(s) are the features for your model?
    APPLICATION_TYPE	AFFILIATION	CLASSIFICATION	USE_CASE	ORGANIZATION	STATUS	INCOME_AMT	SPECIAL_CONSIDERATIONS	ASK_AMT are all features 

3 - What variable(s) should be removed from the input data because they are neither targets nor features?
    Name and EIN

4 - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    I picked 3 layers due to the amount of data and reading that adding more than 2 hidden layers does not always increase performance. I picked a large amount of nuerons due to the large amount of collums in the data set after setting dummies. The activation functions I used were shown to be good generalist and due to the amount of data and different fetures I thought this was a good idea to use.

5 - Were you able to achieve the target model performance?
    I was not after adjusting many times. Please note the key to getting optimal performance. I dropped many different rows but it seemed to work best with all of them.

6 - What steps did you take in your attempts to increase model performance?
    One sugestions I heard was to leave the name in. I was supprised to see it hit 95% accuracy but then the test data accuracy was very low probably due to new names that were not trained. I also tried dropping other rows and increasing and decreasing the epochs but found that anything over 50 seemed to be overkill. 