# Food-recipe-database-application
### COMS4111-proj
### PostgreSQL
#### Account: sl4653
#### Password: 6906

### URL of web application
#### http://35.190.178.170:8111/

What we implemented:
1. Searching by keyword: Users could get recipes based on searching keywords of ingredients, or part of recipe's name.
2. Recipe display: Users could see recipe instructions and past users' reviews and ratings about certain recipe.
3. View all recipes and top rating ones.
4. Searching by recipe full name to redirect to recipe page.

What's left:
1. Filtering: We are still trying to built filtering function so user could filtering recipes by ratings, cuisines, cooking tools required, cooking time, level of difficulty of cooking, and
nutrition of the dish, etc. 
2. Even through this is not mentioned in part1, we are trying to add links to search results that can redirect to recipe pages.

Two interesting pages:
1. Top rating recipes page: It selects all the recipes that has ratings from users and ranked them by average rating descendingly. 
Our initial idea is to list only recipes got five points rating. However, we found some recipes have a lot ratings while some have none, so we chose to rank all recipes by ratings. We think it would be useful for users to try top rated recipe first.
2. Recipe page: When I searched "muffin" in database I found two muffin recipes that has similar names(i yam what i yam two  muffins, i yam what i yam  muffins). 
By reading them, we found these 2 recipes are created by same user that one is the updated version. 
We think it could be helpful for users if we can display other recipes created by same contributor. 
