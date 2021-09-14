Task 3
Assume we have the following paragraph describing a cooking app named MyCookingApp:
"The goal of this project is to create a web application where we can view, remove, post, update and search among cooking recipes. The app allows its user to view, modify, and share new cooking recipes with other users. Also, it allows for searching among all recipes using different filters e.g., title keywords, ingredients, recipe type, etc.
Answer the followings:
Is MyCookingApp a CRUD application or does it go beyond CRUD? why or why not?
MyCookingApp is a CRUD application. The four elements of CRUD are Create, Read, Update, and Delete. These are the only operations that are defined in the project description. 
	Create- Users can use POST, and share new recipe elements. 
	Read- Users can view (GET) recipes and search for a subset of posts using filters.
	Update- Users can update (PUT), and modify recipes. 
	Delete- Users can remove (DELETE) recipes. 
Since there are no other functionalities, MyCookingApp is a CRUD application. 
 
If MyCookingApp is a CRUD app, come up with at least two ideas how to make this app go above and beyond CRUD?

Go beyond CRUD is by implementing user profiles. Users can make accounts to save data to their profile (diet, favorite ingredients, allergies) and bookmark recipes to easily refer back to. 
With user profile, we can implement permissions for DELETE operation as it is a destructive operation.
Integrate access controls and user authentication. User authentication can be used to verify profile access. Additionally, because users have personal profiles with a “sign-in” functionality, they can have exclusive editing access to their recipes. 
PATCH is a very useful operation, as it can help in updating individual resources of the recipe than providing all the resources of the recipe.
 
Try and see if you can come up with a novel idea to make MyCookingApp stand out from existing solutions? In other words, try to make MyCookingApp different from the other popular cooking apps, such as Allrecipes or BigOven, that are already out there.
From the current definition, MyCookingApp is a fairly standard recipe web application and is fairly similar to Allrecipes. One feature that stands out to me from BigOven is its ability to create grocery lists using recipes from the website. With Covid restrictions, and the travel restrictions, the market is seeing a growing popularity of meal kits and grocery delivery services. Add-on feature to the existing services would be to implement a similar grocery list functionality, and link it with user’s local grocery delivery services, or their regular grocery shop. This would allow users to customize their meal plans and directly purchase groceries from the website from the store of their choosing (Target, Costco, Amazon Fresh). 
A variant we are starting to observe in the marketplace is the grocery store map in terms of the placement of the items. We can carve the path of entry and exit from the grocery store. 
We can use google maps to enhance it with an instore map, and provide navigational directions for finding ingredients on the aisle.

