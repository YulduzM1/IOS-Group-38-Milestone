Original App Design Project - README Template
===

# Recipe Playlist

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
A social media app where users can share their favorite recipes and add categories and tags that help users discover recipes that match their needs.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:**
- **Mobile:**
- **Story:** 
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [fill in your required user stories here]
* [ ] User can login/logout of their account
* [ ] User can create a new account
* [ ] User can post a recipe and add appropriate tags
* [ ] User can view existing posts from other users
* [ ] User can like/dislike these posts, and will be less likely to see poorly received posts
* [ ] User can save recipes they love and view them later
* [ ] User can search for posts that have certain tags

**Optional Nice-to-have Stories**

* [fill in your required user stories here]
* [ ] User can report posts that violate core policies or have inaccurate tags
* [ ] User can create playlists of recipes they like
* [ ] New recipes will be automatically suggested for user playlists
* [ ] User can join communities around certain dietary or culinary topics / categories and see recipes liked by that community
* [ ] User can select topics they like when signing up

### 2. Screen Archetypes
Preliminary:

* Login
   * [ ] User can login to the app
   * [ ] User can create an account
   * [ ] **Optional**: User can select topics they like while creating their account
* Home Page
    * This is a tableview
   * [ ] User can see recipes and the tags / likes / dislikes associated
   * [ ] User can select to create a recipe
   * [ ] User can expand each recipe page modally
   * [ ] User can infinite scroll through recipes
   * [ ] User can add filters to the page to only see certain posts
   * [ ] **Optional**: User can use a search bar to search for a particular recipe
* Recipe Page
    * [ ] User can see the ingredients, the steps
    * [ ] User can view a story associated with the recipe (e.g. this was my grandma's favorite dish for thanksgiving blah blah blah)
    * [ ] User can choose to skip this story
    * [ ] User can view a set of tips (e.g. you can use more sugar to make cakier cookies, you want to use a very hot skillet, you want to mix the batter very gently, etc.)
    * [ ] User can skip the tips
    * [ ] **Optional**: User can post and see comments on the recipe
    * [ ] **Optional**: if the user created this recipe, they can edit or delete it
* Create a Recipe
    * [ ] User can view a template to help them separate their recipe into logical components: ingredients, steps, story, tips
    * [ ] User can cancel creation of their recipe
* Playlists
    * [ ] User can view their playlists of recipes
* Playlist Page
    * Tableview
    * [ ] User can see the recipes in the playlist
    * [ ] User can view each recipe modally
    * [ ] **Optional**: User can see recommendations for further recipes to add to playlist
* Account
    * [ ] User can logout
    * [ ] **Optional:** User can activate dark mode
    * [ ] **Optional:** User can view all the recipes they've created
* Communities
    * [ ] User can view existing communities
    * [ ] User can view a summary of each community modally
    * [ ] User can search for a community by name
    * [ ] User can select an option to create a community
* Create Community
    * [ ] User can create a new community and provide a description
    * [ ] User can add filters associated with community
    * [ ] User can create rules for community
    * [ ] **Optional**: The request will be reviewed before finally being created (developers approve community based on description, rules, and whether such a community already exists)

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [Home Page]
* [Recipe Page]
* [Playlist Page]
* [Account(Profile)]
* [Communities]

**Flow Navigation** (Screen to Screen)

* [Forced Log-in -> Account creation if no log in is available]

* [Communities]
   * [Create a Community]

* [Playlist Page]
   * [Save a Recipe]
   * [Cart]

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

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
