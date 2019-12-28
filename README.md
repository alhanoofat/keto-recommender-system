<p align="center">


  <h3 align="center">Keto Diet Recommender System</h3>

 
</p>


<!-- ABOUT THE PROJECT -->
## About The Project
Nowadays, there are many weight-loss diets. Keto diet is one of the best and is getting more popular. It primarily consists of high-fats, moderate-proteins, and very-low-carbohydrates.<br>
It could be time consuming to find a meal recipe that is consistent with Keto diet, along with personal preferences. Therefore, I created a recommender system that takes the user inputs, processes them, then outputs the best matches. It is based on a dataset of 1722 meal recipes. This system recommends the best meals that suit a user based on their preferences. It takes into consideration the user preferences of the meat type, such as fish, beef or chicken. It also considers the user's preferences of sorting the results.<br>


### Built With

* Python 3.6
* Jupyter Notebook




<!-- GETTING STARTED -->
## Getting Started


### Data Discription
The dataset could be found here: https://www.kaggle.com/hawkash/spoonacular-food-dataset

### Data Dictionary
| Feature |Type| Description | unit         
| :- |:-|-------------: | :-:
|id| int | a unique number for each recipe  | NA
|title| object | recipe name  | NA
|pricePerServing| float | cost per serving  | USD
|weightPerServing| int | weight per serving  | Gram
|vegetarian| bool | vegetarian recipe or not  | NA
|vegan| bool | vegan recipe or not | NA
|glutenFree| bool | gluten free or not | NA
|dairyFree| bool | dairy free or not  | NA
|sustainable| bool | is it sustainable? for more [click here](https://www.sustainweb.org/sustainablefood/what_is_sustainable_food/) | NA
|veryHealthy| bool | is it very healthy?   | NA
|veryPopular| bool | is it very popular?  | NA
|gaps| object | gaps diet, for more [click here](http://www.gapsdiet.com/) | NA
|lowFodmap| bool | low Fodmap diet or not, for more [click here](https://www.ibsdiets.org/fodmap-diet/fodmap-food-list/)  | NA
|ketogenic| bool | ketogenic diet or not, for more [click here](https://www.healthline.com/nutrition/ketogenic-diet-101)   | NA
|whole30| bool | whole30 diet or not,for more [click here](https://www.thekitchn.com/what-is-whole30-and-why-were-talking-about-it-this-month-239308)| NA
|readyInMinutes| int | time of cooking  | minute
|spoonacularSourceUrl| object | recipe source link   | NA
|image| object | recipe image link  | NA
|aggregateLikes| int | counts of likes  | NA
|spoonacularScore| float | spoonacular score compares a recipe with all the other recipes using top-secret formula  | NA
|healthScore| float | how health is the recipe   | NA
|percentProtein| float | Protein percentage in a recipe| NA
|percentFat| float | Fat percentage in a recipe  | NA
|percentCarbs| float | Carbs percentage in a recipe  | NA
|dishTypes| object | recipe dish type | NA
|ingredients| object | ingredients to make a specific recipe  | NA
|cuisines| object |  Regional recipe preparation traditions | NA
|calories| float |  calories in one recipe | NA
|other featuers| NA |  nutrition facts | different units
|meat| object | The exact type of meat contained in the recipe  | NA
|meat_category| object | The category of the meat: fish, beef, chicken, pork, or not_meat | NA
|keto| boolean | Whether or not the recipe is a keto diet meal  | NA


## Usage

This project can be used as a meal recommender system for people who are on Keto diet.





<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request






<!-- CONTACT -->
## Contact

Alhanoof Al Taisan<br>
alhanoof.at@gmail.com

