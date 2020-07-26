# Food-recipe-database-application
### COMS4111-proj
### PostgreSQL

### URL of web application
#### http://35.190.178.170:8111/

Our project is to create an application that helps people to figure out what they can cook with the ingredients left in their fridge. In order to make our application more functional, we will build this application based on recipe description, recipe ratings, and ingredient nutrition data sets. For our database, we would have 6 entities: Person, Recipes, Reviews, Ingredients, Tags, Subtags, and following relationships: gives_rating_to, contribute_to, contains, was_given, assigned_with, and belongs_to. The interesting part of this project is that we are going to build a relatively practical and useful application. However, since we are considering adding filter functions and pictures, it is difficult to match recipes and pictures in our datasets and categorize tags from recipes.  
We found an inspirational dataset on Kaggle called Food.com Recipe and Interactions, which is collected from Food.com website. It contains 230K+ recipes and 1000K+ reviews from users. We will expand this dataset by adding nutritions dataset from USDA, recipe pictures from Food.com.
