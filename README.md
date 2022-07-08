# Data Fruit Machine Learning Models 
## Using Random Forest Classification and Grid Search to create a model predicting types of date fruit. 
**By Meryum Syeda**: 

### Business problem:
There is a huge date fruit market! There are also many different types of dates with different shapes, densities, and tastes. Currently humans are doing the manual labor of filtering through them, but with the integration of machine learning, we can create models of predict types of dates! 


### Data:
This data includes 898 rows of dates and 35 columns related to different aspects of dates. From the date's entrophy to denisty, this dataset includes the various ways dates are accessed by humans before they are released into the market! 

![image](https://user-images.githubusercontent.com/101068535/178037557-8bb03361-767e-4af3-90fc-6021b4a31742.png)


This above graph is interesting because when data was collected, it was thought that if there was a variation of areas for each class of dates, that using the area to predict the type of date would be easier! In this case, I do see some variation, so it may be helpful to run further analyses to explore this relationship.

I also clustered the data to see whether I could draw correlations between two factors!

![image](https://user-images.githubusercontent.com/101068535/178039416-7dcfad4d-0ea2-4809-8fac-f7534161d649.png)

Above I can see there are two clusters formed between entrophy and perimeter! I see that there is a greater variation of the permeter among dates with the strongest entrophy. This is interesting because entrophy is the amount of energy or nutrients stored in a date, so it's related to how people value the quality of the fruit. Learning more about this inspires us to dive deeper in seeing what else is related to entrophy or the quality of our dates in our dataset. I will also be proposing a model to predict the classification of different dates that could further assist in date production. 


## Methods
We can see that there are no unnessary columns or rows to delete in our dataset. All are also continuous, so I do not hope to take out an outliers as they may be indicative of something else, such as a deformity in the date.


## Results

#### Here's the Random Forest Classification Model:

![image](https://user-images.githubusercontent.com/101068535/178029424-e77ff950-292d-4341-a644-fc138a48b937.png)

The results here are amazing! The accuracy shows the probability of a random prediction being correct, meaning that there's a 92% chance the classification of a date can be predicted correctly. The F1-score is an important value to look at because it considers both how well we are predicting the correct classication of the date (precision) and recall, which could show of all the SOGAY's, we predicted 85% of them to be SOGAY's.

#### Grid Search 

After doing the grid search, there continues to be a 92% accuracy! This grid search helps fine-tune our model where it goes through each permuatation of each parameter we put in! We can continue to do this to improve our model and make predictions on the types of dates in the market! Due to this high accuracy rate as well as good precison and recall discussed before, the future can be to integrate machine learning in date fruit filtering and catagorization rather than having humans do the manual labor of doing this.

## Recommendations:

We should work together with farmers and food companies to inform them about our machine learning model as it's shown that it can appropriately catategorize dates into it's correct classication. This may help decrease labor costs for businesses and lead to greater efficiency in date production!


## Limitations & Next Steps

Just as there is human error, there is also error in this model. Therefore, next steps should include more data collection on date qualities as there may be a greater variety than the 7 classes of dates in this dataset. More information may lead to greater accuracy and f1-scores across all types of dates!


### For further information


For any additional questions, please contact meryum.syeda01@gmail.com
