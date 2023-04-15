# Model a SQL Database



Every Record will have:
Created At - datetime
Updated At - datetime
Deleted At - datetime
# Create Entity Relationship Diagram
* [ ] Database Schema - Draft
* [ ] Database Model - Draft

# Entities in an Automate Mobile App
* [x] User
* [x] Address
* [x] Vehicle
* [x] Brand
* [x] Model
* [x] Services
* [x] Services Category
* [x] Emergency
* [x] Emergency Type
* [ ] Quotation
* [ ] Shop
* [ ] Shop Location
* [ ] Cart
* [ ] Cart Item
# Seed Databases
  * [x] Address
  * [x] Brand & Model
  * [x] Car Assets
  * [ ] Emergencies Type
  * [ ] Services Category 
  * [ ] Services
# Database (Supabase & Postgresql)
* [ ] Database Schema - Draft
* [ ] Entity Relationship Diagram - Draft

# Seed Databases
  * [x] Address
  * [x] Brand & Model
  * [x] Brand logo and Model images
  * [x] Emergencies Type
  * [ ] Services Category - Partial
  * [ ] Services

# Screens and Features
* [ ] User Authentication and Authorization
  * [x] Develop a user authentication system using OAuth 2.0 
    * [x] Sign In
    * [x] Sign Up  
  * [ ] OTP for Email and Phone 
  * [ ] Implement role-based access control for different user types (e.g., mechanics, shop_owners, customers)
  
* [ ] User Registration (Province, City, Barangay)
  * [ ] Load Province data in a background
  * [ ] Populate City and Barangay based on User selects.
  * [ ] Identification Validation  

* [ ] Vehicle Register Screen (Brand, Model, Vehicle) 
  * [x] Load and Display Brand data and images
  * [x] Load and Display Model data and images
  * [x] Cache Brand and Model data
  * [ ] Once User submit, save to Vehicle Table.
 
* [ ] Home Screen (Emergency Type, Services - parent category)
  * [x] Load and Display Emergency
  * [x] Load and Display Services 
  * [x] Cache Emergency and Services Data

* [ ] Services Screen/Section (Services - parent category and sub-category, Vehicle, Cart, Shop, )
  * [ ] Load and Display Services Parent Category - Partial
  * [ ] Load and Display Services Details (e.g., Description, Images, Price)
  * [ ] Allow User to select vehicle from it's list.
  * [ ] Saved to database either from Cart or Shop Order
* Profile Screen 
  * [x] Allow User to Logout
  * [ ] Display User Information
  * [ ] Allow User to Update its Info
  * [ ] Display User vehicles
  * [ ] Allow User to add or update Vehicles
  
* User Cart Screen
  * [ ] Load and Display Cart Items
* 

* [ ] Shop Management System
  * [ ] Develop a backend system for creating and managing shops 
  * [ ] Implement database schema and APIs for shop creation, editing, and deletion
  * [ ] Allow shops to create services to offered in shop.

# API Endpoints
* [ ] User
  * [x] Sign In User
  * [x] Sign Up User
  * [ ] Update
  * [ ] Delete 
* [ ] Addresses
  * [x] Create
  * [x] List
  * [ ] Update
  * [ ] Delete
* [ ] Vehicle
  * [ ] Create
  * [ ] List
  * [ ] Update
  * [ ] Delete
* [ ] Emergency Type
  * [x] List
* [ ] Emergency Request
  * [ ] Create
  * [ ] List
  * [ ] Update
  * [ ] Delete
 
  


