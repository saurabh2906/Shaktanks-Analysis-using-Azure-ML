# Sharktanks-Analysis-using-Azure-ML
Here, we have got an dataset containing Shark Tank episodes with 495 records where each entrepreneur making their pitch to investors (aka sharks). Using multiple algorithms, we will predict given the description of new pitch, how likely is the pitch will convert into success or not.
My Approach is :
CHECK FOR MISSING VALUES: NO MISSING VALUES IN DATA EXCEPT ENTREPRENEURS AND WEBSITE.
REMOVING UNNECESSARY COLUMNS i.e. website
TARGET VARIABLE - DEAL : CATEGORICAL, that means I will be using CLASSIFICATION TECHNIQUES and will try to sort the best algorithm.
TEXT ANALYSIS ON DESCRIPTION
WILL USE ASSOCIATION FOR FURTHER INSIGHTS.

Techniques used :
LOGISTIC REGRESSION : 50.4% ACCURACY
SUPPORT VECTOR MACHINE : 48.7% ACCURACY
BOOSTED DECISION TREE : 52.2% ACCURACY
DECISION FOREST : 49.3% ACCURACY

BOOSTED DECISION TREE gives the highest accuracy among all but still it is very low. We will go for ASSOCIATION RULES NEXT.

VISIT THE AZURE GALLERY TO VIEW THE EXPERIMENT :
https://gallery.cortanaintelligence.com/Experiment/SHARKTANK-ALGO
https://gallery.cortanaintelligence.com/Experiment/SHARKTANK-TEXT-ANALYSIS

