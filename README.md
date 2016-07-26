# burger
In this homework assignment, we created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). Following the MVC design pattern we used Node and MySQL to query and route data in the app, and Handlebars to generate the HTML.

#### Directory structure:
All the recommended files and directories from the steps above should look like the following structure:
```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
