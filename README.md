# project-practice --------------------------------------------------------------------------//

Question i asked on the chatGpt: So now give a project question, which should contain navigating 5 different pages, and give some ui and functionaltiy for each page, and give functionality in such a way that there is use of objects of data and passing the data from one page to another, the question should be interesting

Question generated thorugh chatGpt : 

Here is a project question that combines the concepts of navigating different pages, UI design, data manipulation, and data passing:

Project: Building a Recipe App

You are tasked with building a recipe app that allows users to browse and save their favorite recipes. The app should have the following features:

1. Home page: The home page should display a list of popular recipes, retrieved from an API. Each recipe should have a title, image, and brief description. Users should be able to click on a recipe to view more details.  

2. Recipe detail page: When a user clicks on a recipe from the home page, they should be taken to a recipe detail page that displays more information about the recipe, such as the ingredients, instructions, and nutritional information. Users should be able to save the recipe to their "favorites" list by clicking a button.

3. Search page: The app should have a search page that allows users to search for recipes by keyword. The search results should be displayed in a list, similar to the home page.

4. Favorites page: The app should have a favorites page that displays a list of the user's saved recipes. Users should be able to remove a recipe from their favorites list by clicking a button.

5. Profile page: The app should have a profile page where users can view and edit their account information.

6. An about us page that contains information about the app developer.

For the data manipulation, you can use the data provided above, you can use it to filter out the recipes based on different criteria like ingredients, cusine, etc. and for passing the data from one page to another you can use url parameters or use browser local storage.

This project will require you to use JavaScript for data manipulation and navigation between pages, HTML and CSS for UI design, and you can use any popular javascript framework for building the app like React, Angular, Vue or use pure javascript to build the app.


If you want to use API then go ahead, otherwise here is the data of recipes: 


[    {        
        recipeName: "Pizza Margherita",       
        price: 12.99,        
        rating: 4.5,        
        country: "Italy",        
        ingredients: ["tomato sauce", "mozzarella cheese", "basil", "olive oil", "flour"],
        prepTime: 20,
        cookTime: 15,
        hotelName: "La Pizzeria",
        diet: "non-vegetarian",
        image: "pizza_margherita.jpg",
        taste: "savory"
    },
    {
        recipeName: "Sushi Platter",
        price: 18.99,
        rating: 4.0,
        country: "Japan",
        ingredients: ["sushi rice", "seaweed", "tuna", "salmon", "avocado"],
        prepTime: 25,
        cookTime: 10,
        hotelName: "Sushi Paradise",
        diet: "non-vegetarian",
        image: "sushi_platter.jpg",
        taste: "savory"
    },
    {
        recipeName: "Chocolate Cake",
        price: 8.99,
        rating: 4.7,
        country: "France",
        ingredients: ["flour", "sugar", "cocoa powder", "eggs", "milk"],
        prepTime: 30,
        cookTime: 45,
        hotelName: "Le Patisserie",
        diet: "vegetarian",
        image: "chocolate_cake.jpg",
        taste: "sweet"
    },
    {
        recipeName: "Vegetable Biryani",
        price: 14.99,
        rating: 4.2,
        country: "India",
        ingredients: ["basmati rice", "vegetable", "spices", "ghee","water"],
        prepTime: 40,
        cookTime: 25,
        hotelName: "Kebab House",
        diet: "vegetarian",
        image: "vegetable_biryani.jpg",
        taste: "savory"
    },
    {
        recipeName: "Carbonara",
        price: 12.99,
        rating: 4.5,
        country: "Italy",
        ingredients: ["spaghetti", "eggs", "black pepper","cheese","bacon"],
        prepTime: 20,
        cookTime: 15,
        hotelName: "Spaghetti House",
        diet: "non-vegetarian",
        image: "carbonara.jpg",
        taste: "savory"
    },
    {
    recipeName: "Pad Thai",
    price: 12.99,
    rating: 4.5,
    country: "Thailand",
    ingredients: ["rice noodles", "chicken", "bean sprouts", "peanut sauce", "lime"],
    prepTime: 20,
    cookTime: 15,
    hotelName: "Thai Kitchen",
    diet: "non-vegetarian",
    image: "pad_thai.jpg",
    taste: "savory"
  },
  {
    recipeName: "Tandoori Chicken",
    price: 18.99,
    rating: 4.0,
    country: "India",
    ingredients: ["chicken", "yogurt", "spices", "lemon juice", "ginger"],
    prepTime: 25,
    cookTime: 10,
    hotelName: "Tandoori Palace",
    diet: "non-vegetarian",
    image: "tandoori_chicken.jpg",
    taste: "savory"
  },
  {
    recipeName: "Banana Bread",
    price: 8.99,
    rating: 4.7,
    country: "USA",
    ingredients: ["flour", "sugar", "banana", "eggs", "milk"],
    prepTime: 30,
    cookTime: 45,
    hotelName: "Grandma's Bakery",
    diet: "vegetarian",
    image: "banana_bread.jpg",
    taste: "sweet"
  },
  {
    recipeName: "Beef Stroganoff",
    price: 14.99,
    rating: 4.2,
    country: "Russia",
    ingredients: ["beef","onion","mushrooms","sour cream","butter"],
    prepTime: 40,
    cookTime: 25,
    hotelName: "Russian Delight",
    diet: "non-vegetarian",
    image: "beef_stroganoff.jpg",
    taste: "savory"
  },
  {
    recipeName: "Falafel",
    price: 12.99,
    rating: 4.5,
    country: "Middle East",
    ingredients: ["chickpeas","onion","parsley","coriander","flour"],
    prepTime: 20,
    cookTime: 15,
    hotelName: "Falafel House",
    diet: "vegetarian",
    image: "falafel.jpg",
    taste: "savory"
  },
  {
    recipeName: "Paella",
    price: 16.99,
    rating: 4.3,
    country: "Spain",
    ingredients: ["rice", "chicken", "seafood", "saffron", "peas"],
    prepTime: 30,
    cookTime: 45,
    hotelName: "Paella Paradise",
    diet: "non-vegetarian",
    image: "paella.jpg",
    taste: "savory"
},
{
    recipeName: "Spaghetti Bolognese",
    price: 11.99,
    rating: 4.2,
    country: "Italy",
    ingredients: ["spaghetti", "ground beef", "tomato sauce", "onion", "garlic"],
    prepTime: 20,
    cookTime: 30,
    hotelName: "Italian Delight",
    diet: "non-vegetarian",
    image: "spaghetti_bolognese.jpg",
    taste: "savory"
},
{
    recipeName: "Peking Duck",
    price: 24.99,
    rating: 4.5,
    country: "China",
    ingredients: ["duck", "hoisin sauce", "scallions", "cucumber", "steamed buns"],
    prepTime: 45,
    cookTime: 60,
    hotelName: "Peking Palace",
    diet: "non-vegetarian",
    image: "peking_duck.jpg",
    taste: "savory"
},
{
    recipeName: "Green Curry",
    price: 14.99,
    rating: 4.4,
    country: "Thailand",
    ingredients: ["coconut milk", "green curry paste", "chicken", "bamboo shoots", "basil"],
    prepTime: 20,
    cookTime: 25,
    hotelName: "Green Curry House",
    diet: "non-vegetarian",
    image: "green_curry.jpg",
    taste: "spicy"
},
{
    recipeName: "Samosas",
    price: 8.99,
    rating: 4.6,
    country: "India",
    ingredients: ["potatoes", "peas", "cumin", "coriander", "flour"],
    prepTime: 30,
    cookTime: 20,
    hotelName: "Samosas Delight",
    diet: "vegetarian",
    image: "samosas.jpg",
    taste: "savory"
},
{
    recipeName: "Black Bean Soup",
    price: 10.99,
    rating: 4.1,
    country: "Mexico",
    ingredients: ["black beans", "onion", "garlic", "chili powder", "oregano"],
    prepTime: 15,
    cookTime: 30,
    hotelName: "Soup Kitchen",
    diet: "vegetarian",
    image: "black_bean_soup.jpg",
    taste: "savory"
}
]

























