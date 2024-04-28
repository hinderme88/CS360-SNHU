# CS360-SNHU

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
### This is an inventory management app, designed to provide users with an interface which will allow them to effectively manage their inventory from a mobile device. It is designed to be simple, streamlined, and easy to use. The core functionality includes the ability to add an item to the database, add details such as description and quantity, edit details, delete items, and receive notifications when items fell beneath a certain predefined quantity threshold.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
### The most important screen in this application is undoubtedly the main inventory screen. This screen uses a grid to store different items, with items being organized into individual rows that could be easily scrolled through. Other necessary screens were the item add screen, and item update screen. Both of these screens allowed users to enter item details and make necessary changes to items in inventory. Navigation was kept simple and straightforward to increase user efficiency in traversing the app. The UI was consistent throughout the various screens, which is important in establishing app 'brand' or identity, while also providing users with a steady, predictable experience.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
### I began with the UI, to ensure that the most important elements were all in place and accounted for. Placing the various widgets and studying their relationships in the xml files helped when coding the back end later on. This also helped keep user needs at the forefront, which is a strategy which should be employed for just about any application.

## How did you test to ensure your code was functional? Why is this process important and what did it reveal?
### I tested my code by interacting with the app as if I was the end customer. This helped ensure I was achieving the level of user confidence that I intended. Stepping through the entire process bit by bit, from the login screen to the main inventory grid, really helped weed out any inconsistencies, oversights, or shortcomings.

## Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
### Learning how to incorporate a database, and working with SQLite, was a new challenge for me. It was something I was anxious about as I had no prior experience, but I followed a few references to develop a database helper class that could perform all of the necessary data-related actions. At the end I felt as though I had a much clearer understanding of how app data works.

## In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
### I feel that the most successful component of my design was the recyclerview. I could have chosen to use a listview, but I felt that the efficiency boost of the recyclerview was too impressive to overlook. It seemed like the best practice when it comes to large, changing lists of items, so even though it was challenging to implement and to understand, I am glad that I perservered and was able to get it to work in my app.
