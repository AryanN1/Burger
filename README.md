# Burger
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.
Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.
This app will store every burger in a database, whether devoured or not.

App Setup

1. Create a GitHub repo called `burger` and clone it to your computer.

2. Make a package.json file by running `npm init` from the command line.

3. Install the Express npm package: `npm install express --save`.

4. Create a server.js file.

5. Install the Handlebars npm package: `npm install express-handlebars --save`.

6. Install the method-override npm package: `npm install method-override --save`.

7. Install the body-parser npm package: `npm install body-parser --save`.

8. Install MySQL npm package: `npm install mysql --save`.

9. Require the following npm packages inside of the server.js file:
   * express
   * method-override
   * body-parser
   
Directory structure

All the recommended files and directories from the steps above should look like the following structure:

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
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
