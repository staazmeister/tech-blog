# tech-blog
Week 14 Homework
This week's project was to build a CMS-style blog, where developers can publish their own post and comment on other's post as well. Objective is to follow the MVC paradigm, use Handlebars.js, Sequelize, and express-session npm package to autheticate.

# Installation
1. Copy the clone link of the repository from GitHub
2. Open Bash or Terminal Window
3. When the console opens, navigate to the directory the repository will be added to
4. In the console, type the command "git clone" and paste the link to repository
5. Open repository in preferred code editor
6. Open terminal in code editor
7. Type in terminal "npm init -y" to install dependency packages needed

  Ensure the following packages are installed
- npm init -y
- npm install dotenv
- npm install express
- npm install MySQL2
- npm install sequelize



# Usage
1. After repository has been cloned, in the terminal, log in to MySQL by entering: mysql -u root -p and enter your password when prompted
2. Using MySQL run the schema.sql by typing: source schema.sql. This will create the database needed for this application
3. Quit MySQL by typing: \q
4. Start the app by running command: node server.js


## User Story (provided in the homework instructions)
```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```
## Acceptance Criteria (provided in the homework instructions)
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

## Why this project is important
The purpose of this project is apply our newly learned skills using command node js.

Skills to be implemented on this project are:
- MVC paradigm
- Handlebars.js
- Sequelize
- Express-session npm for authetication

## Actions taken for this project
- Utilized MVC paradigm
- Utilized Handlebars.js
- Utilized Sequelize
- Utilized express-session npm for authetication
- Used git commands to add, commit, and push all changes on to GitHub repository

## View of deployed app
![Screen Shot 2022-04-18 at 8 51 46 PM](https://user-images.githubusercontent.com/94095220/163916762-117f00f8-b545-4f62-8196-1f13a84ab185.png)




## Links to Application and GitHup Repository
- Link to deployed app: https://git.heroku.com/johill-techblog.git
- URL for GitHub repository: https://github.com/staazmeister/tech-blog.git
