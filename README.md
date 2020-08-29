
# burger-app-handelbars

### Description

In this assignment, I created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). I followed the MVC design pattern; used Node and MySQL to query and route data in my app, and Handlebars to generate your HTML.

### Usage

* This is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user add a burger's name, my app will display the burger on the top section of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `DEVOUR TIME!` button. When the user clicks it, the burger will move to the middle section of the page.

* My app will store every burger in a database, whether devoured or not.

* [Check out this video of the app for a run-through of how it works](https://drive.google.com/file/d/1JAfKCsFsciCzCfS0CqcLSZn3nBd4Yfco/view).


* **This assignment must be deployed.** Be sure to utilize the [MYSQL Heroku Deployment Guide](../../03-Supplemental/MySQLHerokuDeploymentProcess.pdf) in order to deploy your assignment.



### Directory structure

All files and directories look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

### Reminder: Submission on BCS

* Please submit both the deployed Heroku link to your homework AND the link to the Github Repository!


### Hosting on Heroku

Now that we have a backend to our applications, we use Heroku for hosting. Please note that while **Heroku is free**, it will request credit card information if you have more than 5 applications at a time or are adding a database.

Please see [Heroku’s Account Verification Information](https://dashboard.heroku.com/apps/afternoon-shore-60190) for more details.

- - -

### Add To Your Portfolio

After completing the homework please add the piece to your portfolio. Make sure to add a link to your updated portfolio in the comments section of your homework so the TAs can easily ensure you completed this step when they are grading the assignment. To receive an 'A' on any assignment, you must link to it from your portfolio.

- - -




