# FoodStacks

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
iOS app to help users decide where to eat out.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:Food/Restaurant**
- **Mobile:Yes**
- **Story:Useful app to food lover**
- **Market:Restaurant**
- **Habit:Eating**
- **Scope:Merced**

## Product Spec

### 1. User Stories

**Required Must-have Stories**

* User home screen
    * Login/sign up
* Map display
    * Shows name/location of restaurants
    * User's current location
* "Find Where to eat" button
    * Takes all restaurante within location range, and decides one to eat at
* Location range
    * Default range 10-15 miles from user location
* Screen that displays decided place to eat
    * Location
    * Contact info
    * Operating Hours

**Optional Nice-to-have Stories**

* Information of Restuarants
    * Operating Hours
    * Photos
    * Location
    * Contact info
    * Reviews(?)
        * Likes
        * Feedback
* Filter Options
    * Favorite/prefferred restaurrants
    * Extend/limit location range
    * Food categories
        * Types of cuisine(i.e., American, Mexican, Asian, etc.)
        * Price range
        * Dining experience
            * Fast food vs. dine-in
            * Take-out options
* Collaborative
    * Several users contribute with filters
        * Requires user creation/login

### 2. Screen Archetypes

* Loading Screen (Splash Page)
   * [list associated required story here]
   * a lauch screen with logo "FoodStacks"
* Login Screen (Login/Register)
   * list associated required story here
   * Request username and password 
* Find a Place Screen (Creation)
   * [list associated required story here]
   * button to generate a restaurant to go eat 
* Place Screen (Detail)
   * [list associated required story here]
   * having restaurant GPS and detail 
* Filter Screen (Creation)
   * list associated required story here
   * option to select the type of food and condition you want to eat 

*Shown in the sketch and wireframe

### 3. Navigation

**Tab Navigation** (Tab to Screen)
* the back symbol: allow users to go back to the previous page
* the three bar tab: will lead to the filter of your food option
* fill out your first tab: tab sign in will lead to the home screen to find restaurant button
* fill out your second tab: the selected restaurant pop up, which include the GPS location and store details
* fill out your third tab: click on the restaurant image that lead to the full detail

**Flow Navigation** (Screen to Screen)

* Loading Screen
   * Login Screen
* Login Screen
   * Find a Place Screen
* Find a Place Screen
   * Place Screen
   * Filter Screen
   * Login Screen
* Place Screen
   * Find a Place Screen
* Filter Screen
   * Find a Place Screen

*Shown in the GIF: http://g.recordit.co/WC6ZOyn2bB.gif
 

## Wireframes
<img src="https://i.imgur.com/Rm5TA3c.png" width=200><img src="https://i.imgur.com/j3ioINf.png" width=200><img src="https://i.imgur.com/pQlDxqg.png" width=200>
<img src="https://i.imgur.com/bRmoXNI.png" width=200><img src="https://i.imgur.com/NZfeZYm.png" width=200><img src="https://i.imgur.com/D1s3O56.png" width=200>

### [BONUS] Digital Wireframes & Mockups
Digital Wireframe: https://www.figma.com/file/XklBhdDw58CgKC8nIYOb9f/FoodStacks-Mockup?node-id=0%3A1


### [BONUS] Interactive Prototype
Interactive Prototype GIF: http://g.recordit.co/WC6ZOyn2bB.gif

## Schema 
This section will be completed in Unit 9
### Models
Add table of models
### Networking
- Add list of network requests by screen 
- Create basic snippets for each Parse network request
- OPTIONAL: List endpoints if using existing API such as Yelp
