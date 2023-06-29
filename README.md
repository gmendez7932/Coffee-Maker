# Coffee-Maker
Instructions on how to use Coffee Maker:
Coffee-Maker is a program that is used to help Coffee Shops have an application that is able to make orders and hold an inventory.
To use the program it requires a Inventory.txt file to read through that is structured as "Ingredient= #" where the # is an int.

Once it has this, the program will show the user its menu and then prompt the user to make a selection using a number.
1. User will be prompted a series of questions to build a coffee object then add this object to their order list.
   once this is made, the user will be prompted to exit or continue adding to the order. Exiting will bring the user back to the main menu.
2. User can re-load the inventory to view what is currently in the inventory.
3. User uses this after making orders to update the inventory and correctly subtract the used ingredients from the orders.
4. User can expand their inventory if they need to add more of an ingredient
5. User can use this to view the orders that the application has made that session
6. User can use this to exit the code.

Black Coffee: Handles BlackCoffee specific tasks
Coffee: Interface for many Coffee objects
Coffee Decorator: Parent Class for Coffee Add-ons
Coffee Order: Class to handle lists of coffee orders and their functions
Espresso: Handles Espresso specific tasks
Inventory.txt: Where the inventory is read and written to
Main: WHere user runs and interacts with application
WithFlavor: Handles Flavor related ingredients
WithHotWater: Handles Hot Water ingredient specific tasks
WithMilk: Handles Milk ingredient specific tasks
WithSugar: Handles Sugar ingredient specific tasks
WithWhippedCream: Handles Whipped Cream ingredient specific tasks
