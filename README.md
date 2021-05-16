# HackerEarth_Pet_adoption (rank: 49)

### A ML multi-class classification project to identify pet and breed category

This projects helps classifying the pet and breed category provided the following features:
1. pet_id:	Unique Pet Id
2. issue_date:	Date on which the pet was issued to the shelter
3. listing_date: Date when the pet arrived at the shelter
4. condition:	Condition of the pet
5. color_type:	Color of the pet
6. length(m):	Length of the pet (in meter)
7. height(cm):	Height of the pet (in centimeter)
8. X1,X2:	Anonymous columns
9. breed_category:	Breed category of the pet (target variable)
10. pet_category: Category of the pet (target variable)

## Evaluation Metric
s1:  weighted average f1_score for breed category
s2:  weighted average f1_score for pet category 
score = 100*(s1+s2)/2

## Project Structure
1. train.csv and test.csv files contain the training and testing data, respectively
2. Pet_adoption.ipynb file gives the walkthrough over the complete project. 
3. vclf.pkl file is the saved pickle file of final model of pet category as target variable
4. vcl2f.pkl file is the saved pickle file of final model of breed category as target variable

## Please feel free to connect for any suggestions or doubts!!!

## Credits
This dataset was from HackerEarth competetion and hence credit for the dataset used for training goes to https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-pet-adoption/problems/
