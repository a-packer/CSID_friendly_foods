# CSID_friendly_foods
## An app that helps people diagnosed with CSID figure out which foods have sucrose and starch
People with CSID have little to no sucrase, the enzyme needed to digest sucralose. They have to completely cut out sucrose from their diet (or take expensive medicine) and usually have to limit their starch intake. Sucrase assists in starch digestion, but depending on the type of starch and how complex it is, sucrose may not be needed for digestion.

# 1. What goal will your website be designed to achieve? 
A user will be able to search for a food and discover if it has sucrose and/or starch. A user will be able to save a list of foods they want to remember. Maybe they can have different lists for different food groups like: veg, protien, fruit, or other

# 2. What kind of users will visit your site? In other words, what is the demographic of your users?
People with CSID or friends/family members who need to know what they can and can't eat

# 3. What data do you plan on using? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain.
A nutritional data API that states how much sucrose or starch is in a serving of a certain food

# 4. In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:
# a. What does your database schema look like?
User -< User_list  (one to many)
Food >< User_list  (many to many)

# b. What kinds of issues might you run into with your API?
Maybe there will be difficulties resolving things like cheese vs cheddar cheese?
Sometimes servings sizes are unexpectedly small or large, so I'll need to make that info clear to the user

# c. Is there any sensitive information you need to secure?
no

# d. What functionality will your app include?
Sign Up, Sign In, Logout, Search for food in food database, Save foods that are 'favorited', delete foods 
Stretch Goals: 
Sort favorited foods by starch content. 
Have a general food search option by veg, fruit, or protien and let the user choose a low-starch option or no-starch option to filter results

# e. What will the user flow look like?
Log In or Sign up. Lookup a food in the food search bar. Save the returned food to a list (if multiple lists, check box for which lists to save to)

# f. What features make your site more than CRUD? Do you have any stretch goals?
Homepage sorting and filtering based on user preferences 
The Homepage is where I would have a general food search option where a user can just click on 'veg' or 'fruit' or 'protien' and a list of results with foods that contain no sucrose in alphabetical order, starch content order, or popularity by how many times a food was saved?


