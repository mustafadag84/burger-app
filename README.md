
# burger-app-handelbars

### Description

In this assignment, I created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). I followed the MVC design pattern; used Node and MySQL to query and route data in my app, and Handlebars to generate your HTML.

### Usage

* This is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user add a burger's name, my app will display the burger on the top section of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `DEVOUR TIME!` button. When the user clicks it, the burger will move to the middle section of the page.

* My app will store every burger in a database, whether devoured or not.

* [Check out this video of the app for a run-through of how it works](https://drive.google.com/file/d/1JAfKCsFsciCzCfS0CqcLSZn3nBd4Yfco/view).

* Please see [deployed Heroku link](https://afternoon-shore-60190.herokuapp.com/) for more details.


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
### Screenshot
* ![Screenshot (227)](https://user-images.githubusercontent.com/63365781/91646353-35c04b80-ea1c-11ea-92ed-c456abe37938.png)

### Links
* https://github.com/mustafadag84/burger-app-handlebars

* https://afternoon-shore-60190.herokuapp.com/





