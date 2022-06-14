Original App Design Project - README Template
===

# When to Fly

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
When to Fly is an app that tracks historical flight data within the past year to help its user determine the best time to purchase a flight. By simpling inputting the date the user would like to fly, When to Fly will return the number of days prior to the fly date which would be most optimal to purchase. 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Travel
- **Mobile:** This app would be primarily developed for mobile users but could be extended to a desktop app. Functionality would not be limited to mobile devices - however, the mobile version could potentially have more features.
- **Story:**
- **Market:** Any individual over the age 12 can choose to use this app.
- **Habit:** This app could be used every time the user needs to purchase a flight.
- **Scope:** First, I would start by looking at historical flight data of all flights. Later on, I could potentially look at historical flight data by the preferred airline of the user, as well as international flight data.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create a new account
* User can login
* User can input arrival and departure cities
* User can look at flights within WA
* Profile pages for each user

**Optional Nice-to-have Stories**

* User can search for flights via preferred airline
* User can have non-stop vs. stopping options
* User can search for domestic flights
* User can search for international flights
* Profile Add on: user can save their preferred flight routes to their profile
* Settings (Notification to purchase flight __ days in advance)

### 2. Screen Archetypes

* Login
* Register - User signs up 
   * Upon Reopening of the application, the user is brought to the home page to look at flights
* Profile Screen
   * Allows user to see their saved flight routes
* Home Page (departure & arrival airports)
   * Scrolling screen (kind of like twitter/Instagram, etc)
* Flight Detail Screen
   * Showcases the number of days in advance to book
   * Airline to book with

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Page
* Profile
* Settings

**Flow Navigation** (Screen to Screen)

* Forced Login -> Account creation if no login is available
* Home Page -> Flight Detail Screen
* Profile -> Displays tracked flights
* Settings -> Toggle Settings

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="Capstone Wireframes.pdf" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
