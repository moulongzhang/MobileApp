# MobileApp

## Objective

Food Loss is currently a serious problem in the Foodservice industry. 

The Mobile App that we developed is intended to create an environment:
  - restaurants can offer dishes and profit from food that were supposed to be thrown away
  - customers can get meals for discounted prices and contribute to minimize food wastes in the world
  
## 1. App for customers

This is the core app of the project.
### 1. Login in Page
  - Cusomers should be able to Login/Sign up for an account on the Login page
  ### key features
    - Create a database accouringly
    - Incorporate Facebook, Google account for login/Sign up if possible

### 2. General Page
  - Customers should be able to do variety of General tasks on the page:
    - List of Restaurants available
    - Setting (Preview/Edit Account info)
    - Convert to Map

  ### key features
    - GPS tracker (for map)
  
### 3. Store specific page
  - This is the page shows customized information for a specific store
  - The restaurant should be able to customize
  - The page shows various information such as available menu, discount details and so on
  
  ### key features
    - Customer Reviews
  
### 4. Order/Transaction Page
  - Display orders in the cart
  - Execute transaction
  ### key features
    - credit card transaction
    
### 5. Account Info / Settings Page
  - Display Customer information:
    - Preview/Edit Account info (payment info)
    - Order History

  ### key features
    - 
### 6. Map (alternative representation of General page)
  - Display a map:
    - list available restrant on the map
    - using GPS info for current location

  ### key features
    - GPS    
    
    
 


    
 ### list of functions
 Login
 - login form
 - sign up form
 
 Home (General)
 - Photo Display: displays photos (promotions, events)
 - time counter: Display time
 - Display restaurants
  - filter display mechanism
 - Display another pages
 - Search bar for restaurant
 
 MAP
 - GOOGLE MAP API
 - display registered restaurant
 
 FOOD
 - info function (work with database) address, hours, phone number, website
 - overall food display function (menu bar)
 - specific food display (detailed info)
 - add to cart button (save)
 - view order / checkout button (redirect the page to payment page)
 - timer / # of stocks

 Account/ Setting
 - display/edit all info under user ID (database)
 - change password (e-mail verification)
 - display order history (database)
 - change/update payment info (default button)
 - Signout
 
 Payment-page
 - Calculation page (for tax etc..)
 - back button (navigate back to previous page)
 - edit payment info
 - transaction button (check if card is valid)


## 2. App for restuarant

### 1. Login in Page
  - Restaurant should be able to Login/Sign up for an account on the Login page
  ### key features
    - Create a database accordingly
    - Sign-up would redirect to a page where user can fill up the application    
    
### 2. General Page
  - User should be able to do variety of General tasks on the page:
  - View the list of live orders 
  - Setting (Preview/Edit Account info)
  - Accept or decline the order
  - On/Off the availability of restaurant
  ### key features
    - 
### 3. Store specific page
  - This is the page shows customized product information by the user
  - The page shows various information such as available menu, discount details and so on
  - Adding or deleting or editing products
  - Changing the available of products
  ### key features
    - 
### 4. Account Info / Settings Page
  - Display Restaurant information:
  - Preview/Edit Account info (Bank info)
  - Order History
### key features
    - Display a list of history orders for a specified period of time 
    - Display each order’s payment detail
    - Generate a report for a specified period of time (monthly) for tax purposes
