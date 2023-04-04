# UTA-Bootcamp-Challenge14
## Model-View-Controller (MVC) Challenge: Tech Blog
----------------------------------------------------------------------
## Description

This is a CMS-style blog site that enables users to create articles and blog posts. It follows the Model View Controller (MVC) architectural pattern, and uses Handlebars.js as the templating language, Sequelize as the ORM, and express-session npm package for authentication. The homepage displays published blog posts, links for the homepage and dashboard, and an option for logging in.

----------------------------------------------------------------------

## User Story

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```
* "User Story" & "Acceptance Criteria" listed above have been provided by the UTA Bootcamp Program 2022.
----------------------------------------------------------------------

## Table of Contents

- [Installation](#installation)
- [Built Using](#built-using)
- [Preview](#preview)
- [Links](#links)
- [License](#license)

----------------------------------------------------------------------

## Installation

1. Clone/download git repository.
2. Run command "npm i"
3. Run command "npm run start" to open app on live server.


#

## Built Using

- Node.js
- MySQL2
- Sequelize
- Handlebars
- bcrypt
- Express.js
- Inquirer
- dotenv
- Heroku

#

## Preview

<img src= "assets/images/C14 Screenshot 1.png"/>
<img src= "assets/images/C14 Screenshot 2.png"/>
<img src= "assets/images/C14 Screenshot 3.png"/>
<img src= "assets/images/C14 Screenshot 4.png"/>

#

## Links

- Deployment Link: https://uta-techblog.herokuapp.com/ 
- GitHub Repository Link: https://github.com/khevb27/UTA-Bootcamp-Challenge14

----------------------------------------------------------------------
## License

Please refer to licensing documentation in the project repository.

<img src="https://img.shields.io/badge/license-MIT License-blue.svg" alt="GitHub License">

----------------------------------------------------------------------
