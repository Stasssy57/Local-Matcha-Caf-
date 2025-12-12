# Local Matcha Cafe

## Project Summary 

Our Local Matcha/Coffee Café Menu Ordering System is designed to provide customers with a quick and customizable way to order their favorite matcha/coffee on the go. The system features a clean UI where customers can choose from a variety of matcha and coffee options, drink preferences such as size, sweetness level, and milk type, and different matcha flavors (strawberry amd banana). To enhance convenience and customer loyalty, the system also includes a phone-number–based point tracking feature that rewards frequent buyers with discounts and makes online ordering and pickup more efficient. Overall, this project aims to improve customer experience while supporting a modern, cozy café environment. 

 

## Project Details 

The menu ordering system is an interactive, simple application where customers are able to choose amongst a variety of drinks. The drinks range from multiple flavors of coffee and matcha in which you can adjust the sweetness level, sizes, and milk choice. Once a drink is chosen, the UI will display a description of the drink and the types of ingredients included in it. From there, customers will select their preferences.  

To keep customer satisfaction and engagement, customers have the option to input their phone numbers as part of our rewards system. Each dollar spent is 1 point and is added to the customer’s profile, which can later be redeemed for discounts and free drinks. Once the order is fully processed, a receipt is printed out listing the drink, cost, and a number for the order.  

### Logic Flow

1) Start 
2) Display Main Menu 
    * Show drink categories: Matcha, Coffee 
    * Show flavor options 
    * Show text box for phone number for loyalty points 
3) Customer Selects Drink Type 
    * Matcha or Coffee 
4) Customer Selects Specific Drink 
    * e.g., Banana Matcha, Americano, Latte, etc. 
5) Display Customization Options 
    * Size (Small / Large) 
    * Sweetness level 
    * Milk type
6) Add Drink to Order 
7) Check for Additional Items 
    * If yes → return to Main Menu 
    * If no → continue 
8) Enter Phone Number (Optional) 
    * System retrieves or creates loyalty profile 
    * Apply eligible discounts 
9) Calculate Total Price 
10) Display Order Summary 
11) Customer Confirms Order 
    * If confirmed → proceed 
    * If not → return to Main Menu 
13) Submit Order to System 
14) Update Loyalty Points 
15) Display Order Confirmation 
16) End 
    
### Users Guide 

Section 1: Getting Started 
How to launch the application 
Login instructions (demo credentials) 

### Section 2: Ordering Process 

Login with phone number/password 
Browse matcha/coffee menu 
Select drink and customize 
Add to cart 
View cart and apply loyalty points 
Complete payment 
Print/save receipt 

### Section 3: Loyalty System 

How points are earned (1$ = 1 point) 
Redeeming points for discounts 
Viewing point balance 

### Section 4: Administrative Features (if implementing admin view) 

View all orders 
Update menu items 
Generate daily reports 

### Code Print-Out 
