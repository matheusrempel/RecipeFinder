# RecipeFinder
Python demo which uses deep learning to find recipes for pictures taken of food.

-----
Demo.ipynb is a jupyter notebook with an effective demo of the project. In order to run, download the images folder in the repo, comment out the line of choice an run. Keep in mind that in order to run this, CLIP, along with many other packages must be installed. In the top section of the demo notebook, all pip install code has been pre-coded for convience. 
----
CLIP_food_classifications is a juypter notebook containing the entire project; from testing various models, to eventually picking CLIP. It also has functions for returning the top 1, 3, and 5 outputs given an input image. 
----
Find_Recipes is the jupyter notebook used with BeautifulSoup4 in order to parse html code containing ingredients and recipes of the classified image. The recipes all come from: allrecipes.com . 
---
Predict Foods is a jupyter notebook containing the minimal code required to predict the food if obtaining a recipe is not desirable. 
---
The categories available include: 

'Apple pie', 'Baby back ribs', 'Baklava', 'Beef carpaccio', 'Beef tartare', 
        'Beet salad', 'Beignets', 'Bibimbap', 'Bread pudding', 'Breakfast burrito', 
        'Bruschetta', 'Caesar salad', 'Cannoli', 'Caprese salad', 'Carrot cake', 'Ceviche', 
        'Cheese plate', 'Cheesecake', 'Chicken curry', 'Chicken quesadilla', 'Chicken wings', 
        'Chocolate cake', 'Chocolate mousse', 'Churros', 'Clam chowder', 'Club sandwich', 
        'Crab cakes', 'Creme brulee', 'Croque madame', 'Cup cakes', 'Deviled eggs', 'Donuts', 
        'Dumplings', 'Edamame', 'Eggs benedict', 'Escargots', 'Falafel', 'Filet mignon', 
        'Fish and chips', 'Foie gras', 'French fries', 'French onion soup', 'French toast', 
        'Fried calamari', 'Fried rice', 'Frozen yogurt', 'Garlic bread', 'Gnocchi', 'Greek salad', 
        'Grilled cheese sandwich', 'Grilled salmon', 'Guacamole', 'Gyoza', 'Hamburger', 
        'Hot and sour soup', 'Hot dog', 'Huevos rancheros', 'Hummus', 'Ice cream', 'Lasagna', 
        'Lobster bisque', 'Lobster roll sandwich', 'Macaroni and cheese', 'Macarons', 'Miso soup', 
        'Mussels', 'Nachos', 'Omelette', 'Onion rings', 'Oysters', 'Pad thai', 'Paella', 
        'Pancakes', 'Panna cotta', 'Peking duck', 'Pho', 'Pizza', 'Pork chop', 'Poutine', 
        'Prime rib', 'Pulled pork sandwich', 'Ramen', 'Ravioli', 'Red velvet cake', 'Risotto', 
        'Samosa', 'Sashimi', 'Scallops', 'Seaweed salad', 'Shrimp and grits', 'Spaghetti bolognese', 
        'Spaghetti carbonara', 'Spring rolls', 'Steak', 'Strawberry shortcake', 'Sushi', 'Tacos', 
        'Takoyaki', 'Tiramisu', 'Tuna tartare', 'Waffles'
        
---

Project co-written by Matheus Rempel & Christopher Le of Rice University 
